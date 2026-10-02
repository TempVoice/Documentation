---
description: >-
  Placeholders are replaced with valuable information to make channel names or
  welcome messages more personal to the user.
icon: brackets-curly
---

# How to use Placeholders?

## The power of placeholders

{% embed url="https://youtu.be/9HG0nN1ILBk?si=J4_mTmoIoNXSpETE&t=117" %}

## How to use placeholders in the dashboard?

Using placeholders is easy. Click the `{ }` button and you will see all available placeholders for that option.

<figure><img src="../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

## Where can I use which placeholder?

Placeholders work in three settings: the [Temporary Channel Name](../../settings/overview/name.md), the [Waiting Room Name](../../settings/overview/name.md#waiting-rooms) and the [Temporary Channel Greeting](../../settings/others/greeting.md). Not every placeholder makes sense everywhere:

| Placeholder                                                                       | Channel Name | Waiting Room Name | Greeting |
| --------------------------------------------------------------------------------- | :----------: | :---------------: | :------: |
| [{CUSTOM}](custom.md)                                                             |       ✓      |                   |          |
| [{PRIVACY}](privacy.md)                                                           |       ✓      |                   |          |
| [{RANDOM}](random.md)                                                             |       ✓      |         ✓         |     ✓    |
| [{OWNER\_USERNAME}](owner_username.md), [{OWNER\_NICKNAME}](owner_nickname.md)    |       ✓      |         ✓         |     ✓    |
| [{OWNER\_CREATED}](owner_created.md), [{OWNER\_JOINED}](owner_joined.md)          |       ✓      |         ✓         |     ✓    |
| [{OWNER\_MENTION}](owner_mention.md), [{OWNER\_ID}](owner_id.md)                  |              |                   |     ✓    |
| [{NUMBER}](number.md) and its variants                                            |       ✓      |         ✓         |     ✓    |
| [{ROLE\_HIGHEST}](role_highest.md), [{ROLE\_HOIST}](role_hoist.md)                |       ✓      |         ✓         |     ✓    |
| [{GUILD\_ID}](guild_id.md), [{CHANNEL\_ID}](channel_id.md)                        |              |                   |     ✓    |
| [{ACTIVITY\_...}](activity_name.md) (Your Own Branding™ only)                     |       ✓      |                   |          |

{% hint style="info" %}
Channel names are cut off after 100 characters, and words blocked by [Censor Channel Names](../../settings/moderation/censor.md) are censored after the placeholders are replaced.
{% endhint %}
