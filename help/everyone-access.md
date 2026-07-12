---
description: >-
  If your Discord server has a verification system and you want to prevent
  @everyone from using temporary channels.
icon: badge-check
---

# How to integrate my verification system?

## Define your **Member Roles**

[Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> Select the **correct** Creator Channel -> Permissions Tab -> Temporary Channel Access Roles

<figure><img src="../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

After you defined your roles, a newly created temporary channel will set the permission of those roles by default for `Connect` and `View Channels` to <img src="../.gitbook/assets/On.png" alt="" data-size="line">.

On the other side the permission of `@everyone` for `View Channels` will be set to <img src="../.gitbook/assets/Off.png" alt="" data-size="line">. This prevents users without one of those roles to use temporary channels.
