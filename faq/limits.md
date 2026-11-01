---
description: >-
  TempVoice itself can create unlimited temporary voice channels, there's no
  premium paywall on our side. However, Discord's platform has its own hard
  limits, and TempVoice uses a few cooldowns to stay within them.
icon: hand
---

# What are the limitations for TempVoice?

## Discord Server

* **500 channels per server** — A Discord server can have a maximum of 500 channels in total (text, voice, and categories combined). Once this limit is reached, no new channels can be created until existing ones are removed.
* **50 channels per category** — Each category can hold up to 50 channels. If the category for temporary voice channels is full, you'll need to configure [**fallback categories**](../settings/creator/overview/category.md#fallbacks) (Premium), which will be used to place the new temporary channels.

## Discord API

* **2,000 channels per day** — Discord also limits channel _creation_, not just how many can exist at once. A server can have a maximum of **2,000 new channels created per rolling 24-hour period**, shared across **all bots and users combined**. On very active servers, this can become an issue. [Learn more about Ratelimits](../troubleshooting/tempvoice-not-working.md#ratelimit). With [Your Own Instance](../help/premium.md#your-own-instance), [Temporary Channel Pooling](../settings/server/advanced/pooling.md) reuses channels instead of creating new ones.
* **Rename every 6 minutes** — A channel can only be renamed once every 6 minutes. This is because Discord only allows **2 channel updates per 10 minutes**. Keep in mind: if you're using the [`{PRIVACY}`](../help/placeholders/privacy.md) placeholder in your channel name, changing your privacy with [/voice privacy](../commands/voice/privacy.md), [/voice password](../commands/voice/password.md) or [/voice waiting](../commands/voice/waiting.md) also triggers a rename, so it's affected by this same cooldown. [/voice reset](../commands/voice/reset.md), [/voice claim](../commands/voice/claim.md) and [/voice transfer](../commands/voice/transfer.md) can rename your channel too.

## TempVoice

* **25 trusted/blocked users per channel** — When you trust or block a user, TempVoice adds a permission overwrite to your channel. Based on experience, too many overwrites slow down API requests. If you need to block more than 25 users, we recommend **locking your channel** with [/voice privacy](../commands/voice/privacy.md) and using a waiting room with [/voice waiting](../commands/voice/waiting.md).
* **2 Creator Channels on the Free plan** — The Free plan lets you set up **2 Creator Channels** at no cost. If your server needs more than that, [**TempVoice Premium**](https://tempvoice.xyz/premium) unlocks unlimited Creator Channels.
* **Creating channels** — You have to wait **6 seconds** before you can create your next temporary channel, and 6 seconds longer for each channel you create within a minute. A server can also create up to **4 channels within 30 seconds**. If you have to wait, you're disconnected from the Creator Channel and TempVoice tells you when you can try again. [Your Own Instance](../help/premium.md#your-own-instance) has no cooldown per user.
* **5 invites per hour** — A user can send up to 5 invites per hour with [/voice user invite](../commands/voice/user/invite.md).
* **Vote kicks** — A [vote kick](../commands/voice/user/kick.md#vote) runs for 2 minutes. If it fails, the user who started it has to wait 2 minutes before starting another one.
* **10 fallback categories** — A Creator Channel can have up to 10 [fallback categories](../settings/creator/overview/category.md#fallbacks).

{% hint style="danger" icon="hearts" %}
Unlike other bots, TempVoice puts almost no essential features behind a paywall, there's no limit on how many temporary channels or interfaces you can create, regardless of your plan.
{% endhint %}
