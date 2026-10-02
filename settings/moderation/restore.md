---
description: >-
  Recovers a temporary channel with the same settings it had before being
  deleted, including name, permissions and user limit.
---

# Recover Owner Settings

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> Select the **correct** Creator Channel -> Click on the `Moderation` tab -> `Recover Owner Settings`

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

Choose which settings of the owner are recovered when they create a new temporary channel:

| Option                          | Set with                                                                                                        |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Name                            | [/voice name](../../commands/voice/name.md)                                                                     |
| User Limit                      | [/voice limit](../../commands/voice/limit.md)                                                                   |
| Trusted & Blocked Users         | [/voice user trust](../../commands/voice/user/trust.md) and [/voice user block](../../commands/voice/user/block.md) |
| Privacy Mode (Locked or Hidden) | [/voice privacy](../../commands/voice/privacy.md)                                                               |

If you turn an option off, users can still change it while their channel exists, but a new temporary channel starts with the default configuration of the Creator Channel again.
