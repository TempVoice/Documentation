---
description: >-
  Set how many members of a temporary channel have to vote for a kick before the
  user gets kicked.
---

# Vote Kick Percentage

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> Select the **correct** Creator Channel -> Click on the `Moderation` tab -> `Vote Kick Percentage`

<figure><img src="../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

Choose a value between **10%** and **100%** in steps of 5%. The default is **50%**.

The percentage is taken from the members connected to the temporary channel when the votes are counted, rounded up. The user being voted on and bots are not counted, and at least one vote is always needed.

| Voters in the channel | 25% | 50% | 75% | 100% |
| --------------------- | --- | --- | --- | ---- |
| 2                     | 1   | 1   | 2   | 2    |
| 4                     | 1   | 2   | 3   | 4    |
| 5                     | 2   | 3   | 4   | 5    |
| 10                    | 3   | 5   | 8   | 10   |

A vote runs for 2 minutes. Learn how members start and cast votes in [/voice user kick](../../commands/voice/user/kick.md#vote).

{% hint style="info" %}
You can disable vote kicks or limit them to certain roles with the **Starting Vote Kicks** feature in [Toggle Features](features.md). While vote kicks are disabled, this setting shows a **Requires Starting Vote Kicks** badge and has no effect.
{% endhint %}
