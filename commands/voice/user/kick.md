---
description: >-
  Disconnect users from your temporary channel and revoke their access, or start
  a vote and let the members of your channel decide.
---

# kick

<figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (62) (1).png" alt=""><figcaption><p>Before</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>After</p></figcaption></figure>

{% hint style="info" %}
You can only kick users while your temporary channel is locked or hidden with [/voice privacy](../privacy.md), or has a user limit set with [/voice limit](../limit.md). In a public channel without a limit, a kicked user could join again right away.
{% endhint %}

When both kick modes are available to you, TempVoice first asks whether you want an **Instant Kick** or a **Vote Kick**.

## Instant Kick <a href="#instant" id="instant"></a>

Only the owner of the temporary channel can kick instantly. Select up to **3 users** at once:

* Users connected to your channel are disconnected.
* Their permissions on your channel are removed, which also takes them off your trusted list.
* You can also select a user you [invited](invite.md) who hasn't joined yet to take back the invite.

Kicked users can join again if your channel is public and they aren't [blocked](block.md).

## Vote Kick <a href="#vote" id="vote"></a>

Members of the temporary channel can start a vote to kick one user, so the owner doesn't have to be around.

{% stepper %}
{% step %}
### Start the vote

Select the user. TempVoice posts a vote message in the in-voice chat of the channel. Starting a vote counts as a **yes** vote.
{% endstep %}

{% step %}
### Members vote

Everyone connected to the channel can vote **yes** or **no** with the buttons and can change their vote while it runs. The user being voted on can't vote.
{% endstep %}

{% step %}
### The vote ends

The user is kicked as soon as enough members voted **yes**. The vote fails once too many members voted **no** for it to pass, and it ends after **2 minutes** if not enough members voted in time.
{% endstep %}
{% endstepper %}

The number of votes needed is the [Vote Kick Percentage](../../../settings/moderation/vote-kick-percentage.md) of the members connected to the channel, rounded up. The user being voted on and bots are not counted.

> **Example:** 6 users are in the channel and one of them is voted on. That leaves 5 voters. With a percentage of 50%, **3** yes votes are needed.

Only one vote kick can run in a channel at a time. The owner of the channel and moderators can't be vote kicked, and a vote fails if the user being voted on becomes the owner, for example with [/voice claim](../claim.md).

## Who can't be kicked? <a href="#immune" id="immune"></a>

Members with the **Ban Members**, **Kick Members** or **Timeout Members** permission are moderators and can't be kicked. If the server grants channel owners **Move Members** with [Temporary Channel Owner Permission](../../../settings/permissions/owner.md), the owner can instantly kick moderators too. Moderators are always protected from vote kicks.

See [Why some users get ignored/skipped?](../../../faq/skipped.md) for every reason a user can be skipped.

{% hint style="success" icon="gear-complex" %}
Server admins can turn off or restrict both modes to certain roles with [Toggle Features](../../../settings/moderation/features.md): **Kicking/Disconnecting User** and **Starting Vote Kicks**.
{% endhint %}
