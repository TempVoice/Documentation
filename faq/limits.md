---
description: >-
  TempVoice itself can create unlimited temporary voice channels, there's no
  premium paywall on our side. However, Discord's platform has its own hard
  limits that apply to any bot or server.
icon: hand
---

# What are the limitations for TempVoice?

## Discord Server

* **500 channels per server** — A Discord server can have a maximum of 500 channels in total (text, voice, and categories combined). Once this limit is reached, no new channels can be created until existing ones are removed.
* **50 channels per category** — Each category can hold up to 50 channels. If the category for temporary voice channels is full, you'll need to configure [**fallback categories**](../settings/overview/category.md#fallbacks), which will used to place the new temporary channels.

## Discord API

* **2,000 channels per day** — Discord also limits channel _creation_, not just how many can exist at once. A server can have a maximum of **2,000 new channels created per rolling 24-hour period**, shared across **all bots and users combined**. On very active servers, this can becomes an issue. [Learn more about Ratelimits](../troubleshooting/tempvoice-not-working.md#ratelimit).
* **Rename every 5 minutes** — You can only rename your channel once every 5 minutes. This is because Discord only allows **2 channel updates per 10 minutes**. Keep in mind: if you're using the [`{PRIVACY}`](../guides/placeholders/privacy.md) placeholder in your channel name, changing your privacy with [/voice privacy](../commands/voice/privacy.md) also triggers a rename, so it's affected by this same 5-minute cooldown.

## TempVoice

* **25 trusted/blocked users per channel** — When you trust or block a user, TempVoice adds a permission overwrite to your channel. Based on experience, too many overwrites slow down API requests. If you need to block more than 25 users, we recommend **locking your channel** with [/voice privacy](../commands/voice/privacy.md) and using a waiting room with [/voice waiting](../commands/voice/waiting.md).
* **2 Creator Channels on the Free plan** — The Free plan lets you set up **2 Creator Channel** at no cost. If your server needs more than that, you'll need [**TempVoice Premium**](https://tempvoice.xyz/premium) to setup unlimited.

{% hint style="danger" icon="hearts" %}
Unlike other bots, TempVoice puts almost no essential features behind a paywall, there's no limit on how many temporary channels or interfaces you can create, regardless of your plan.
{% endhint %}
