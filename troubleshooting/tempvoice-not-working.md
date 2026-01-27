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

Most Discord servers have a limit of 2,000 channel creations per 24 hours, which applies to all bots. Once this global limit has been reached, no bot can create any more channels until the limit is reset. This limitation is imposed by Discord and we cannot prevent or increase it.

Very active communities should not rely entirely on temporary channels. Provide enough casual voice channels at the top of your server as a first choice so that users might prefer not to use a temporary channel for a quick call.

As this limit applies to all bots, it is advisable to avoid using bots that create channels, such as ticket bots. As an alternative, you can use forum channels or modmail bots.

It's also recommended to lock temporary channel creation behind a role with some requirements (level, time, etc).

This can help prevent your community from reaching the total limit for creating channels.

***

## Check for missing permissions <a href="#check-permissions" id="check-permissions"></a>

Reinvite TempVoice to quickly refresh all permissions:

{% embed url="https://tempvoice.xyz/invite" %}
