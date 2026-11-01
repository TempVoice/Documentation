---
description: >-
  Choose which buttons your interface shows, give it your own design and send it
  to a text channel.
icon: sparkles
---

# Customize and Send the Interface

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> `Interface Preview`

The preview works like the real [interface](../../commands/interface-message.md): click on a part of it to change it, then use `Save Changes`.

## Buttons

Click a button to disable it, and drag the buttons to rearrange them. Disabled buttons are listed below the preview, so you can add them back at any time. Up to 5 buttons fit in a row.

The **Bitrate**, **Info** and **Reset** buttons are disabled by default.

## Design <a href="#design" id="design"></a>

{% hint style="info" icon="crown" %}
The design options require [TempVoice Premium](https://tempvoice.xyz/premium). Without Premium, the interface uses the default design.
{% endhint %}

| Option      | What it does                                                    | Limit               |
| ----------- | --------------------------------------------------------------- | ------------------- |
| Title       | A short and meaningful title, for example your server name      | 64 characters       |
| Description | Explains the purpose of the interface                           | 4,096 characters    |
| Attachment  | An image shown in the interface. Use a direct `https` image link | 256 characters      |
| Footer      | Context or instructions for the buttons                         | 2,048 characters    |
| Color       | The accent color, as a HEX color code                           |                     |

## Send the interface

Save your changes first. Then, under `Send Interface`, select a text channel and send your interface. We recommend a channel where no one else can write. Channels that TempVoice can't send messages to are locked.

You can also use [/setup](../../commands/setup.md) -> `New Interface` to send it to the channel you are in, or send it to the in-voice chat of every new temporary channel with [TempVoice Interface for In-Voice Chat](../creator/others/interface.md).

{% hint style="warning" %}
Saving doesn't change interfaces that were already sent. Send your interface again after you changed it, and delete the old message.
{% endhint %}

