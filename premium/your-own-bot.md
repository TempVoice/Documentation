---
description: >-
  Once you have subscribed to the Your Own Branding™ premium plan, you can start
  with the setup of your own bot.
icon: robot
---

# Your Own Branding™

With the **Your Own Branding™** premium plan, you get your own instance of TempVoice, which lets you customize the username, icon and banner of the bot.

Furthermore, your bot has access to all premium benefits + excusive features, like the [Activity Placeholders](../faq/placeholders/activity_name.md) and _Reserving Channels (Coming soon)_.

## Setup your bot

To get started, go to [https://tempvoice.xyz/premium](https://tempvoice.xyz/premium), subscribe if you haven't, choose your Discord server to activate premium and provide us a Discord bot token.\
\
After providing the token, the installation will start in the background which takes approximately 2 minutes.

Once it has been finished, you can invite your bot to your server.

{% hint style="warning" icon="gear-complex" %}
**Have you used the public TempVoice bot before?**

The public TempVoice bot has to be kicked from the server on which you invited your bot.

All **Creator Channels** you had with the public TempVoice bot will continue work. Just the interfaces have to be recreated using `/setup` -> `New Interface`.
{% endhint %}

<figure><img src="../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" icon="shield" %}
By providing your bot token, you confirm that you've read our [Terms of Service](https://tempvoice.xyz/terms-of-service) (section 3d) and authorize us to host a TempVoice™ instance on your behalf.
{% endhint %}

## How to get a bot token? <a href="#token" id="token"></a>

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
