# NoSwearPlz

## Description
This is a bukkit plugin that will block many swear words (and other offensive language) from being said in chat.
The current implementation uses a large list of words stored in words.txt that you can customize as needed.

This will also handle words split by spaces or words with special charactes.

### Examples:
- "d4mn 5#!7" -> "**** ****"
- "a$$" -> "****"
- "d a m n" -> "****"

## Features:
- Replace offensive language in chat automatically
- Ability to add/remove words on the fly
- Ability to allow players to bypass filter.

## Commands
<u>-- NoSwearPlz Commands --</u>

- /plznoswear <word | bypass > <add | remove> <words | players>

- alias:
  - plznsp

- /plznsp word add [words] - Add words to the list of banned words

- /plznsp word remove [words] - Remove words from the list of banned words

- /plznsp bypass add [players] - Add players to the list of players that can bypass the filter

- /plznsp bypass remove [players] - Remove players from the list of players that can bypass the filter

- /plznsp reload - Reload the plugin configurations


## Dependencies
 - PlzCore

## Permissions
### Op by default permissions
- plznoswear.admin - Allows the player to use the NoSwearPlz commands

###  No one has these permissions by default
- plznoswear.bypass - Allows the player to bypass the NoSwearPlz filter


## Changelog
- 1.21.10-alpha:
  - Updated to MC version 1.21.10
  - Updated to be a paper plugin