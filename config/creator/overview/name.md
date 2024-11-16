---
description: >-
  Define a default name for temporary channels when a user creates a channel for
  the first time.
---

# Temporary Channel Name

> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your server -> Select the **correct** creator channel -> Click on the `Overview` tab -> `Temporary Channel Name`

<figure><img src="../../../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Placeholders `{ }`

The default name can contain placeholders that can display information dynamically.

{% hint style="info" %}
Users can adjust this setting for their temporary channel by using the [`/voice name`](../../../commands/voice/name.md) command or [`interface`](../../../commands/interface.md).

To enforce default settings, disable the name [command](../features/restore.md) or the [restore](../features/restore.md) setting.
{% endhint %}

***

## Censor Channel Names

If you allow your users to change their channel names, there is a risk that they will use inappropriate names. To moderate this automatically, you can specify a list of words that cannot be used as channel names.

1. Click on the `**` button.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Type the words you want to censor one by one, and press `Enter` to save them with the `✔` button.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

***

### Partial Matching <a href="#partial-matching" id="partial-matching"></a>

Use `*` at the beginning or end of a word for partial replacement. **Just like Discords Automod**.

<pre><code>[CENSOR] *pet, java*, *leg*, get
<strong>
</strong><strong>Carpet | JavaScript | Wholegrain | Together
</strong>****** | ********** | ********** | to***her
</code></pre>
