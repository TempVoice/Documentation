---
description: >-
  You don't want your temporary channel to be open to everyone? Create a waiting
  room where you can accept or deny requests to join.
---

# waiting

<figure><img src="../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (33) (1) (1).png" alt=""><figcaption><p>Without Waiting Room</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (34) (1).png" alt=""><figcaption><p>With Waiting Room</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (35) (1).png" alt=""><figcaption><p>Request message after a user joined a waiting room</p></figcaption></figure>

* A waiting room keeps your channel locked. You can't unlock or hide your channel while it has a waiting room, and you can't create one while your channel is hidden.
* When a user joins your waiting room, you get a request. **Accept** moves them into your channel. **Deny** disconnects them and stops them from joining the waiting room again.
* Use the command again to get a button that deletes the waiting room. [/voice reset](reset.md) deletes it too.
* If the server uses [{PRIVACY}](../../help/placeholders/privacy.md) in its naming format, locking your channel renames it, so it has to wait for the [6-minute rename cooldown](../../faq/limits.md#discord-api).
* Server admins can set the name of waiting rooms with the [Waiting Room Name](../../settings/overview/name.md#waiting-rooms).
* A waiting room is a channel too, so it can't be created if the category is full or the server has reached [Discord's channel limit](../../faq/limits.md#discord-server).

{% hint style="info" %}
This command is available for 12 hours after voting on [Top.gg](https://top.gg/bot/762217899355013120/vote). After that, you’ll need to vote again. With [TempVoice Premium](https://tempvoice.xyz/premium), you don’t need to vote at all.
{% endhint %}
