---
description: >-
  Empty temporary channels move into these categories and stay hidden instead of
  being deleted, so new channels are ready right away.
icon: crown
---

# Temporary Channel Pooling

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> `Advanced Settings` -> `Temporary Channel Pooling`

{% hint style="info" icon="crown" %}
Pooling is only available with [Your Own Instance](../../help/premium.md#your-own-instance), and your own bot has to be on the server. The public TempVoice bot always deletes empty channels.
{% endhint %}

## Why use pooling?

Normally, TempVoice creates a new channel when someone joins a Creator Channel and deletes it when it's empty. With pooling, empty channels are kept and reused:

* New temporary channels are ready right away.
* Reusing a channel doesn't count toward Discord's limit of [2,000 channel creations per day](../../faq/limits.md#discord-api).

## How it works

{% stepper %}
{% step %}
### The last user leaves

Instead of deleting the channel, TempVoice moves it into the first selected category that has room and hides it from `@everyone`. Its chat is cleared, except for messages with embeds sent by the bot. Its temporary thread and waiting room are deleted.
{% endstep %}

{% step %}
### Someone joins a Creator Channel

TempVoice looks for an empty channel that came from the same Creator Channel. If it finds one, the user is moved in, and the channel is moved back to the [Temporary Channel Category](../overview/category.md) with the settings of its new owner.
{% endstep %}

{% step %}
### No channel is available

TempVoice creates a new temporary channel as usual.
{% endstep %}
{% endstepper %}

## Good to know

* You can select up to **10 categories**. A Discord category holds up to 50 channels, so 10 categories can pool up to 500 channels at most.
* Pooled channels still count toward Discord's limit of [500 channels per server](../../faq/limits.md#discord-server).
* Pooled channels are hidden from regular members, but members with the **Administrator** permission can still see them.
* A channel whose [rename cooldown](../../faq/limits.md#discord-api) is still running is skipped, because it couldn't be renamed for its new owner.
* A reused channel gets the name, user limit and permissions of its new owner, but it keeps its [region](../../commands/voice/region.md) and [bitrate](../../commands/voice/bitrate.md).
* A channel that only bots are left in is deleted, not pooled.

{% hint style="warning" %}
If all selected categories are full, an empty channel stays where it is and stays visible until it is reused. Select enough categories for your server.
{% endhint %}

