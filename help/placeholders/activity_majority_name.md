---
description: >-
  Replaced by the name of the activity most users in a temporary channel are
  doing, for example the game most of them are playing.
icon: crown
---

# {ACTIVITY\_NAME\_MAJORITY}

## Example

```
{ACTIVITY_NAME_MAJORITY} | {ACTIVITY_DETAILS_MAJORITY}
```

```
Spotify | Never Gonna Give You Up
```

<figure><img src="../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

## How is the majority found?

TempVoice looks at the activities of everyone in the temporary channel, except bots, and uses the most common one. If nobody has an activity, it uses the owner's activity, and then the fallback.

The same works for details and state: `{ACTIVITY_DETAILS_MAJORITY}` and `{ACTIVITY_STATE_MAJORITY}`.

{% hint style="info" icon="crown" %}
Activity placeholders are only available with [Your Own Branding™](../premium.md#your-own-branding). They show the activity of the channel owner, and fall back to `❔` when the owner has none. You can change the fallback in the placeholder settings.
{% endhint %}
