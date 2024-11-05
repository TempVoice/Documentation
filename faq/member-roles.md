---
icon: badge-check
description: >-
  If your Discord server has a verification system and you want to prevent
  @everyone from using temporary channels.
---

# How to integrate my verification system?

## Define your **Member Roles**

&#x20;[Dashboard](https://tempvoice.xyz/dashboard) -> Select a Creator -> Permissions Tab -> Member Roles

<figure><img src="../.gitbook/assets/image (19) (1).png" alt=""><figcaption></figcaption></figure>

After you defined your roles, a newly created temporary channel will set the permission of those roles by default for `Connect` and `View Channels` to <img src="../.gitbook/assets/On.png" alt="" data-size="line">.

On the other side the permission of `@everyone` for `View Channels` will be set to <img src="../.gitbook/assets/Off.png" alt="" data-size="line">. This prevents users without one of those roles to use temporary channels.
