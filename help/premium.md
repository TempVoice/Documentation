---
description: >-
  Once you've subscribed to a TempVoice Premium plan, getting started only takes
  a few clicks.
icon: robot
---

# How can use I use TempVoice Premium™?

{% stepper %}
{% step %}
### Activate Premium <a href="#activate-premium" id="activate-premium"></a>

No matter which Premium plan you subscribe to, if you purchased it on the **TempVoice website** (rather than through Discord), you'll need to **activate Premium** on the server where you want to use its benefits.

Go to [tempvoice.xyz/premium](https://tempvoice.xyz/premium), log in with your Discord account if you're not already logged in, and select your server from the dropdown menu.

<figure><img src="../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

Make sure you click "Save Changes" afterwards.

<figure><img src="../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Your Own Branding™

If you subscribed to the **Your Own Branding™** premium plan, you get your own instance of TempVoice, which lets you customize the username, icon and banner of the bot.

Furthermore, your bot has access to all premium benefits + excusive features, like the [Activity Placeholders](placeholders/activity_name.md) and _Reserving Channels (Coming soon)_.

### Setup your bot

To get started, you have to provide us a [Discord bot token](premium.md#token) to start the installation. This process takes approximately 2 minutes.

<details>

<summary>How to get a <strong>Bot Token</strong>?</summary>

Don't worry, it won't get too technical.

Visit [https://discord.com/developers/applications](https://discord.com/developers/applications), login with your Discord account and click on **New Application**.

<figure><img src="../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

Go to the **Bot** tab, scroll down to **Authorization Flow** and enable **Presence Intent** and **Server Members Intent**.

Optionally you can turn off **Public Bot**, but <mark style="color:$primary;">don't</mark> turn on **Requires OAuth2 Code Grant.**

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>

Scroll up, upload your icon/banner, change the username and click on **Reset Token.**

<figure><img src="../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" icon="key" %}
Treat this token like a password, do not share it with anybody.
{% endhint %}

</details>

<figure><img src="../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

Once it has been finished, you can invite your bot to your server.

### Has you Discord Server more then 10.000 Members?

If you are using your bot in a Discord server with **more then 10.000 members**, then you might be informed by Discord that you need to apply to **Privileged Intents**.

<details>

<summary>How to apply for <strong>Privileged Intents?</strong></summary>

Visit [https://discord.com/developers/applications](https://discord.com/developers/applications), login with your Discord account and go to your application.

If you see a banner like below, click the **Apply** botton and fill out the asked information.

<figure><img src="../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

Simply copy-paste all answers from here:

### Application Details

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

```
Creates voice channels that are temporary, a channel that is empty, will be deleted.
For a detailed overview, please check: https://easy.tempvoice.xyz/
```

Do you have a public Privacy Policy telling your users about their data usage?

```
Yes
```

Where is your Privacy Policy available?

```
The /help command includes a button with a link to the privacy policy.
```

Please share a link to your Privacy Policy.

```
https://tempvoice.xyz/privacy-policy
```

Privileged Gateway Intents

```
[ ] Server Members Intent
[X] Presence Intent
[ ] Message Content Intent
```

### Presence Intent

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Why do you need the Guild Presences intent?

```
Displaying the current playing game/activity of a user in the voice channel name.
```

Please provide links to screenshots and/or videos that demonstrate your use case

```
https://ibb.co/qLNSsThD
```

Can users opt-out of having their Presence data tracked?

```
Yes
```

Are you storing user activity data off-platform (outside of Discord)?

```
Yes
```

Are you storing user activity data for 30 days or less?

```
No
```

How do users contact you to request deletion of their activity data?

```
Users can request their data to be deleted via email to contact@tempvoice.xyz or on the support server https://discord.gg/tempvoice
```

Are you encrypting the data that you store at rest, as is required by our developer policy?

```
Yes
```

</details>
{% endstep %}
{% endstepper %}

{% hint style="warning" icon="gear-complex" %}
**Have you used the public TempVoice bot before?**

The public TempVoice bot has to be kicked from the server on which you invited your bot.

All **Creator Channels** you had with the public TempVoice bot will continue work. Just the interfaces have to be recreated using `/setup` -> `New Interface`.
{% endhint %}

{% hint style="info" icon="shield" %}
By providing your bot token, you confirm that you've read our [Privacy Policy](https://tempvoice.xyz/privacy-policy) & [Terms of Service](https://tempvoice.xyz/terms-of-service) (section 3d) and authorize us to host a TempVoice™ instance on your behalf.
{% endhint %}

