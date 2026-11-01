---
description: >-
  TempVoice needs to be online and have all required permissions to be
  functional.
icon: heart-crack
---

# TempVoice not working

## Check if TempVoice is online <a href="#check-the-status-page-and-may-be-patient" id="check-the-status-page-and-may-be-patient"></a>

See if Discord has announced any outage or increased API latency at [https://discordstatus.com/](https://discordstatus.com/). You can also join the support server [https://discord.gg/tempvoice](https://discord.gg/tempvoice) and look in [#notification](https://discordapp.com/channels/904322845646135317/916444589622177902) for maintenance and outage announcements.

***

## Check your DMs <a href="#turn-on-your-dms-and-do-not-block-tempvoice" id="turn-on-your-dms-and-do-not-block-tempvoice"></a>

TempVoice sends you a DM when there was an error creating a temporary channel. Make sure you have DMs enabled and haven't blocked TempVoice.

***

## Ratelimit

Most Discord servers have a limit of 2,000 channel creations per 24 hours, which applies to all bots. Once this global limit has been reached, no bot can create any more channels until the limit is reset. This limitation is imposed by Discord and we cannot prevent or increase it.

Very active communities should not rely entirely on temporary channels. Provide enough casual voice channels at the top of your server as a first choice so that users might prefer not to use a temporary channel for a quick call.

As this limit applies to all bots, it is advisable to avoid using bots that create channels, such as ticket bots. As an alternative, you can use forum channels or modmail bots.

It's also recommended to lock temporary channel creation behind a role with some requirements (level, time, etc).

This can help prevent your community from reaching the total limit for creating channels.

***

## Common messages <a href="#common-messages" id="common-messages"></a>

| Message                                                | What to do                                                                                                                                                                                                                 |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Premium Expired!**                                   | The Creator Channel is above the [free limit](../faq/limits.md#tempvoice) because Premium ended. Ask an admin to reactivate Premium or delete a Creator Channel.                                                            |
| **This interface uses a custom design**                | This older interface needs Premium. Send a new interface with `/setup` -> `New Interface`, or reactivate Premium.                                                                                     |
| **This interface is outdated**                         | Ask an admin to send a new interface with `/setup` -> `New Interface`.                                                                                                                                |
| **Slow Down!**                                         | You reached a [cooldown](../faq/limits.md). The message tells you when you can try again.                                                                                                                                   |
| **All available categories have reached their limit**  | Delete channels from the category, or set up [fallback categories](../settings/creator/overview/category.md#fallbacks).                                                                                                             |
| **The limit of 500 channels**                          | Your server reached [Discord's channel limit](../faq/limits.md#discord-server). Delete channels you don't need.                                                                                                              |

***

## The Dashboard can't load your server <a href="#dashboard" id="dashboard"></a>

* **"You don't have permission to manage this server"**: You need the **Manage Server** permission. If you were given access recently, log out and log back in.
* **"We couldn't load this server yet"**: Use the bot once on your server, for example by joining a Creator Channel or running a command. Then try again.
* **"We couldn't find this server"**: The bot was most likely removed from it. [Invite the bot](https://tempvoice.xyz/invite) again, or log out and log back in.

***

## Check for missing permissions <a href="#check-permissions" id="check-permissions"></a>

Reinvite TempVoice to quickly refresh all permissions:

{% embed url="https://tempvoice.xyz/invite" %}
