---
description: >-
  TempVoice needs to be online and have all required permissions to be
  functional.
icon: heart-crack
---

# TempVoice not working

## Check if TempVoice is online <a href="#check-the-status-page-and-may-be-patient" id="check-the-status-page-and-may-be-patient"></a>

See if Discord has announced any outage or has an increased api latency here [https://discordstatus.com/](https://discordstatus.com/). You can also join the support server [https://discord.gg/tempvoice](https://discord.gg/tempvoice) and look in [#notification](https://discordapp.com/channels/904322845646135317/916444589622177902) for maintaince/outage announcements.

***

## Check your DMs <a href="#turn-on-your-dms-and-do-not-block-tempvoice" id="turn-on-your-dms-and-do-not-block-tempvoice"></a>

TempVoice sends you a notification when there was an error creating a temporary channel. Make sure you have DMs enabled and didn't blocked TempVoice.

***

## Ratelimit

Most Discord servers have a total channel creation limit of 2,000 per 24 hours. Once this limit has been reached, no bot can create additional channels until the limit is reset. This limitation is imposed by Discord and cannot be prevented or increased by us.

Very active communities should offer enough casual voice channels and avoid the use of other bots which also create channels like ticket bots. It's also recommended to lock temporary channel creation behind a role with some requirements (level, time, etc).

This can help to prevent reaching the total channel creation limit.

***

## Check for missing permissions <a href="#check-permissions" id="check-permissions"></a>

Reinvite TempVoice to quickly refresh all permissions:

{% embed url="https://tempvoice.xyz/invite" %}

***

## Required

```
✅ Manage Roles
✅ Manage Channels
✅ Create Invite
✅ Manage Webhooks
✅ Read Messages
✅ Send Messages
✅ Send Messages in Threads
✅ Create Public Threads
✅ Create Private Threads
✅ Manage Threads
✅ Embed Links
✅ Attach Files
✅ Use External Emojis
✅ Connect
✅ Speak
✅ Move Members
```

## Optional

Required if you want to sync "Manage Permissions"

```
✅ Administrator
```

{% hint style="warning" %}
**Ratelimit**

If TempVoice is online, has all permissions and worked fine before, you might experience a ratelimit. This can happen when bots created too many channels in a short time.

This ratelimit will resolve itself after some time.&#x20;
{% endhint %}
