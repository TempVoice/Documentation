---
description: >-
  Choose which features temporary channel owners are allowed to use while they
  are in control of the channel.
---

# Toggle Features

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> Select the **correct** Creator Channel -> Click on the `Moderation` tab -> `Toggle Features`

<figure><img src="../../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

Every feature can be available to `@everyone`, limited to up to 10 roles, or disabled for everyone. A new Creator Channel starts with every feature available to `@everyone`.

When a user tries a feature they can't use, TempVoice tells them whether it was disabled or which roles are allowed to use it.

| Feature                           | What it controls                                                                                      |
| --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| In-Voice Chat                     | The text chat built into every voice channel.                                                         |
| Send an invite to a public chat   | [/voice invite](../../commands/voice/lfp.md)                                                          |
| Creating Temporary Chat           | [/voice thread](../../commands/voice/thread.md)                                                       |
| Creating Waiting Rooms            | [/voice waiting](../../commands/voice/waiting.md). Requires **Locking Channel**.                      |
| Locking only In-Voice Chat        | Locking the chat with [/voice privacy](../../commands/voice/privacy.md)                               |
| Locking Channel                   | Locking the channel with [/voice privacy](../../commands/voice/privacy.md)                            |
| Hiding Channel                    | Hiding the channel with [/voice privacy](../../commands/voice/privacy.md)                             |
| Force Deleting Channel            | [/voice delete](../../commands/voice/delete.md)                                                       |
| Claiming Channels                 | [/voice claim](../../commands/voice/claim.md)                                                         |
| Transferring Channels             | [/voice transfer](../../commands/voice/transfer.md)                                                   |
| Kicking/Disconnecting User        | Instant kicks with [/voice user kick](../../commands/voice/user/kick.md#instant) and **Disconnect**    |
| Starting Vote Kicks               | Vote kicks with [/voice user kick](../../commands/voice/user/kick.md#vote)                            |
| Inviting Users                    | [/voice user invite](../../commands/voice/user/invite.md) and **Send Invite**                         |
| Trusting / Blocking Users         | [/voice user trust](../../commands/voice/user/trust.md), untrust, block and unblock                   |
| Changing Channel Name             | [/voice name](../../commands/voice/name.md)                                                           |
| Changing Channel Status           | [/voice status](../../commands/voice/status.md)                                                       |
| Changing Channel User Limit       | [/voice limit](../../commands/voice/limit.md)                                                         |
| Changing Channel Region           | [/voice region](../../commands/voice/region.md)                                                       |
| Changing Channel Bitrate          | [/voice bitrate](../../commands/voice/bitrate.md)                                                     |

**Disconnect** and **Send Invite** are [Apps commands](../../commands/apps.md) and follow the same feature as their `/voice` counterpart.

Disabling a feature also stops saved owner settings from being reused. For example, disabling **Changing Channel Name** means new temporary channels use the default [Temporary Channel Name](../overview/name.md) again, instead of the name the owner set before.

{% hint style="info" %}
Unlike the other features, **Starting Vote Kicks** isn't limited to the owner: every member of the temporary channel who is allowed to use it can start a vote.
{% endhint %}

***

<h3 id="ownerless-mode" align="center">Ownerless Mode</h3>

<figure><img src="../../.gitbook/assets/image (19) (1).png" alt="" width="73"><figcaption></figcaption></figure>

<p align="center">Switch <strong>Owner Managed</strong> off when you want to use temporary channels as public game channels. The user who created the temporary channel <strong>will not</strong> be able to customize or moderate it, and the feature list above is locked.</p>
