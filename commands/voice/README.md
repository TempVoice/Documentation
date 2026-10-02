---
description: >-
  After you create a temporary channel, you are the owner of that channel and
  can use this command to change the properties of your channel and manage
  users.
icon: terminal
---

# /voice

You have to be connected to a temporary channel to use `/voice`. Most subcommands can only be used by the owner of that channel. The exceptions are [/voice info](info.md), [/voice claim](claim.md) and starting a [vote kick](user/kick.md#vote).

| Command                                     | What it does                                              | Requires vote |
| ------------------------------------------- | --------------------------------------------------------- | :-----------: |
| [/voice name](name.md)                      | Rename your channel                                       |               |
| [/voice limit](limit.md)                    | Set how many users can join                               |               |
| [/voice privacy](privacy.md)                | Lock, hide or lock the chat of your channel               |               |
| [/voice status](status.md)                  | Set the status text shown below your channel              |       ✓       |
| [/voice waiting](waiting.md)                | Create a waiting room for join requests                   |       ✓       |
| [/voice password](password.md)              | Let users join a locked channel with [/join](../join.md)  |       ✓       |
| [/voice thread](thread.md)                  | Create a temporary text thread                            |       ✓       |
| [/voice invite](lfp.md)                     | Post an invite to your channel in a public chat           |       ✓       |
| [/voice region](region.md)                  | Change the voice region                                   |       ✓       |
| [/voice bitrate](bitrate.md)                | Change the audio quality                                  |       ✓       |
| [/voice info](info.md)                      | Show an overview of your channel                          |       ✓       |
| [/voice claim](claim.md)                    | Take over a channel whose owner left                      |       ✓       |
| [/voice transfer](transfer.md)              | Give ownership to another user                            |       ✓       |
| [/voice delete](delete.md)                  | Delete your channel, even with users inside               |       ✓       |
| [/voice reset](reset.md)                    | Reset all your channel settings to default                |               |
| [/voice user trust](user/trust.md)          | Let users join while your channel is locked or hidden     |               |
| [/voice user untrust](user/untrust.md)      | Remove users from your trusted list                       |               |
| [/voice user block](user/block.md)          | Keep users out of your channel                            |               |
| [/voice user unblock](user/unblock.md)      | Remove users from your block list                         |               |
| [/voice user invite](user/invite.md)        | Invite a user directly by DM                              |       ✓       |
| [/voice user kick](user/kick.md)            | Kick users instantly or start a vote kick                 |               |

{% hint style="info" %}
Commands marked with ✓ are available for 12 hours after voting on [Top.gg](https://top.gg/bot/762217899355013120/vote). After that, you'll need to vote again. With [TempVoice Premium](https://tempvoice.xyz/premium), you don't need to vote at all.
{% endhint %}

Server admins can turn off most of these commands, or limit them to certain roles, with [Toggle Features](../../settings/moderation/features.md).

{% hint style="info" %}
A user needs **Use Application Command** permission to use this command.

![](<../../.gitbook/assets/image (76) (1).png>)
{% endhint %}
