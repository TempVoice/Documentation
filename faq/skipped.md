---
description: >-
  Sometimes you'll select a user on a command and TempVoice won't act on them.
  Instead of silently doing nothing, the bot tells you exactly who was skipped
  and why.
icon: users-slash
---

# Why some users get ignored/skipped?

Every action on a temporary voice channel, like inviting, trusting, blocking, kicking or transferring ownership, first runs a few checks against each selected user. Some checks protect you (you can't invite yourself), some protect the server (moderators can't be blocked out of a channel), and some simply reflect what Discord allows (bots can't receive invites).

<figure><img src="../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

When you select several users at once, the checks run per user: everyone who passes is handled normally, and only those who fail are listed back to you. The reasons below explain each one.

## Is you <a href="#you" id="you"></a>

The selected user is the person running the command. You can't invite, trust, block, kick or transfer ownership to yourself, so you are always skipped.

Raised by: every action that targets a user.

## Is a bot <a href="#bot" id="bot"></a>

The selected user is a bot account. Bots can't accept invites, receive DMs, or be granted trust, so they are excluded from member selections.

Raised by: invite, trust, block, transfer.

## Is blocked <a href="#blocked" id="blocked"></a>

The selected user is on your block list. Inviting them would let them into a channel you blocked them from. [Unblock](../commands/voice/user/unblock.md) them first if you want to invite them.

Raised by: invite.

## Is a moderator <a href="#moderator" id="moderator"></a>

The selected user holds a server permission that makes them immune to channel moderation: **Ban Members**, **Kick Members** or **Timeout Members**. Moderators can't be blocked, kicked or vote kicked from a temporary voice channel.

If the server grants channel owners **Move Members** with [Temporary Channel Owner Permission](../settings/permissions/owner.md), owners can still kick moderators instantly.

Raised by: block, kick, vote kick.

## Is the channel owner <a href="#owner" id="owner"></a>

The selected user owns the temporary channel. A channel owner can't be voted out of their own channel.

Raised by: vote kick.

## Has not accepted the server rules <a href="#rules" id="rules"></a>

The selected user is still in Discord's membership screening ("pending") state. Until they accept the rules they aren't a full member and can't be invited or trusted.

Raised by: invite, trust.

## Has no access role <a href="#role" id="role"></a>

The server has restricted temporary voice channels to specific [access roles](../settings/permissions/access-roles.md), and the selected user has none of them. Giving them access would contradict that restriction, so they are skipped. If no access roles are configured, everyone passes this check.

Raised by: invite, trust.

## Is not in this voice channel <a href="#voice" id="voice"></a>

The selected user isn't connected to your temporary voice channel, so there is nothing to disconnect. An instant kick still works on a user you invited who hasn't joined yet, because it takes back the invite.

Raised by: kick, vote kick.

## Could not be found <a href="#not-found" id="not-found"></a>

Discord did not return usable data for the selected user. Most likely they left the server or the selection expired. Reopen the menu and select the user again.

Raised by: every action that targets a user, as the fallback.
