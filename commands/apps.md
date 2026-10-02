---
description: >-
  Manage the users of your temporary channel straight from their profile,
  without typing a command.
icon: arrow-pointer
---

# Apps Commands

Right-click a user (or long-press on mobile), open **Apps** and choose one of the TempVoice commands. You have to be the owner of the temporary channel you are connected to.

| Command                | Equivalent Chat Command                                   | Requires vote |
| ---------------------- | --------------------------------------------------------- | :-----------: |
| **Disconnect**         | Instant kick with [/voice user kick](voice/user/kick.md)  |               |
| **Send Invite**        | [/voice user invite](voice/user/invite.md)                |       ✓       |
| **Transfer Ownership** | [/voice transfer](voice/transfer.md)                      |       ✓       |

Each Apps command runs the same checks as its chat command. For example, **Disconnect** only works while your channel is locked, hidden or has a user limit, and it skips moderators the same way. See [Why some users get ignored/skipped?](../faq/skipped.md) for details.

{% hint style="info" %}
Commands marked with ✓ are available for 12 hours after voting on [Top.gg](https://top.gg/bot/762217899355013120/vote). After that, you'll need to vote again. With [TempVoice Premium](https://tempvoice.xyz/premium), you don't need to vote at all.
{% endhint %}
