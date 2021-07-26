---
layout: post
title: voicemute
subtitle: Mute a user in their current voice channel.
categories: moderation
tags: [mutes]
---

`Syntax: shisa voicemute <users...> [reason]`

`<users...>` is a space separated list of usernames, ID's, or mentions.

`[time_and_reason]`  is the time to mute for and reason. Time is any valid time length such as 30 minutes or 2 days. If nothing is provided the mute will use the set default time or indefinite if not set.

## Examples:

`shisa voicemute @member1 @member2 spam 5 hours`

`shisa voicemute @member1 3 days`

```
Type shisa help <command> for more info on a command. You can also type shisa help <category> for more info on a category.
```