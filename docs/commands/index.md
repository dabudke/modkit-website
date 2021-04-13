---
layout: page
permalink: /docs/commands/
title: Commands
menubar_toc: true
toc_title: "Commands"
---

## Moderation Commands

### `^warn (user) [reason...]`

Warn a user.

Example: `^warn @LittleKitacho#4507 disrespecting staff`

Parameters:

* `user` - Optional.  User to warn.
* `reason` - Optional, long.  Reason for warning.

Aliases: `^!`

### `^ban(user) [length] [reason...]`

Ban a user.

Example: `^ban @LittleKitacho#4507 1d harassing other users`

Parameters:

* `user` - Required.  User to ban.
* `length` - Optional.  Length to ban the user for.  Uses additional parameters:
  * `years` - Years to ban for, represented by `(years)y`
  * `months` - Months to ban for, represented by `(months)M`
  * `days` - Days to ban for, represented by `(days)d`
  * `hours` -  Hours to ban for, represented by `(hours)h`
  * `minutes` - Minutes to ban for, represented by `(minutes)m`
  * `permanent` - Mutually exclusive.  Permenantly ban the user, represented by `p`
* `reason` - Optional, long.  Reason to ban the user for.  Starts after first
non-digit, non-whitespace character, or after `p`

Aliases: `^tempban`

### `^mute (user) [length] [reason...]`

Mute a user in text channels.

Example: `^mute @LittleKitacho#4507 5m spam`

Parameters:

* `user` - Required.  User to mute.
* `length` - Optional.  How long to mute the user for.
  * `years` - Years to mute for, represented by `(years)y`
  * `months` - Months to mute for, represented by `(months)M`
  * `days` - Days to mute for, represented by `(days)d`
  * `hours` -  Hours to mute for, represented by `(hours)h`
  * `minutes` - Minutes to mute for, represented by `(minutes)m`
  * `permanent` - Mutually exclusive.  Permanently mute the user, represented by `p`
* `reason` - Optional, long.  Reason to mute the user for.  Starts after first
non-digit, non-whitespace character, or after `p`

Aliases: `^tempmute`

### `^unban (user) [reason]`

Unban a user from your server.

Example: `^unban @LittleKitacho#4507 ban appeal`

Parameters:

* `user` - Required.  User to unban.
* `reason` - Optional, long.  Reason for unban.

### `^unmute (user) [reason]`

Unmute a user from your server.

Example: `^unmute @LittleKitacho#4507 raid cooldown`

Parameters:

* `user` - Required.  User to unmute.
* `reason` - Optional, long.  Reason for unmute.

### `^kick (user) [reason]`

Kick a user from your server.

Example: `

Parameters:

* `user` - Required.  User to kick.
* `reason` - Optional, long.  Reason for kick.

### [+2 more](/docs/commands/moderation/1)
