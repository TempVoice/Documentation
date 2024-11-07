---
icon: lock
description: This can be easily done by syncing role permissions
---

# How to block roles access to all channels?

## Enable permission syncing

1. [Dashboard](https://tempvoice.xyz/dashboard) -> Select a Creator -> Permissions Tab -> Synchronize Permissions

<figure><img src="../../.gitbook/assets/image (15) (1).png" alt=""><figcaption></figcaption></figure>

***

## Set permission in category

2. All permissions you set in the category for roles will be applied and synced to temporary channels. Deny `View Channels` or `Connect` permission to avoid that role to join temporary channels.

{% hint style="warning" %}
**Permissions for @everyone**

You cannot sync `Connect`, `View Channel` and `Send Message` permissions for `@everyone`, because these permissions are managed when using [/voice privacy](../../commands/voice/privacy.md)!

If your Discord server has a verification system and you want to prevent @everyone from using temporary channels, read [How to integrate my verification system?](../member-roles.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/image (16) (1).png" alt=""><figcaption></figcaption></figure>
