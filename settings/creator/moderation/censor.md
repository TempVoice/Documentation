---
description: Automatically censor inappropriate words in temporary channel names.
---

# Censor Channel Names

> **Where do I find this?**
>
> Open the [Dashboard](https://tempvoice.xyz/dashboard) -> Select your Discord server -> Select the **correct** Creator Channel -> Click on the `Moderation` tab -> `Censor Channel Names`

<figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (16) (1).png" alt=""><figcaption></figcaption></figure>

You can add up to **64 words** with up to **16 characters** each, and change these options:

| Option                 | What it does                                                                                           | Default |
| ---------------------- | ------------------------------------------------------------------------------------------------------ | ------- |
| Replacement Symbol     | The symbol that replaces each character of a censored word: `*`, `#`, `>`, `<`, `@`, `+` or `-`        | `#`     |
| Commonly Flagged Words | Censors a preset of words that are widely recognized as offensive, inappropriate or potentially harmful | On      |
| Bypass Protection      | Replaces non-Latin characters that look like Latin letters (e.g., Cyrillic) with their Latin equivalents | On      |

***

### Partial Matching <a href="#partial-matching" id="partial-matching"></a>

Use `*` at the beginning or end of a word for partial replacement.\
**Just like Discord's AutoMod**.

<pre><code>[CENSOR] *pet, java*, *leg*, get
<strong>
</strong><strong>Carpet | JavaScript | Wholegrain | Together
</strong>****** | ********** | ********** | to***her
</code></pre>

The censor also applies to [Waiting Room Names](../overview/name.md#waiting-rooms), [/voice status](../../../commands/voice/status.md) and [/voice invite](../../../commands/voice/invite.md).
