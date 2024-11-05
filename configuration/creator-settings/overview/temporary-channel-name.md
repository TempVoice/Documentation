---
description: >-
  Set a default name for temporary channels when a user creates a channel for
  the first time.
---

# Temporary Channel Name

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### Placeholders

The default name can contain placeholders that can display information dynamically.

{% hint style="info" %}
Users can overwrite the default name of their temporary channel by using the [`/voice name`](../../../commands/voice/name.md) command or an [`interface`](../../../commands/interface.md), unless changing the channel name or the restore feature is disabled.
{% endhint %}

## Censor Channel Names

If you allow your users to change their channel names, there is a risk that they will use inappropriate names. To moderate this automatically, you can specify a list of words that cannot be used as channel names.

1. Click on the `**` button.

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

2. Type the words you want to censor one by one, and press `Enter` to save them with the `✔` button.

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Partial Matching <a href="#partial-matching" id="partial-matching"></a>

Use `*` at the beginning or end of a word for partial replacement. **Just like Discords Automod**.

<pre><code>[CENSOR] *pet, java*, *leg*, get
<strong>
</strong><strong>Carpet | JavaScript | Wholegrain | Together
</strong>****** | ********** | ********** | to***her
</code></pre>
