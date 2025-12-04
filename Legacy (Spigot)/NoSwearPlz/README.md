# NoSwearPlz

## Description
This is a bukkit plugin that will block any swear words from being said in chat.
The current implementation uses a large list of words stored in words.txt that you can customize as needed.

This will also handle words split by spaces or words with special charactes.

### Examples:
- "d4mn 5#!7" -> "**** ****"
- "a$$" -> "****"
- "d a m n" -> "****"

## Commands
<u>-- NoSwearPlz Commands --</u>

- /nosearplz <word | bypass > <add | remove> <words | players>

- /nsp word add [words] - Add words to the list of banned words

- /nsp word remove [words] - Remove words from the list of banned words

- /nsp bypass add [players] - Add players to the list of players that can bypass the filter

- /nsp bypass remove [players] - Remove players from the list of players that can bypass the filter

- /nsp reload - Reload the plugin configurations


<u>-- NoSwearPlz Menu Commands --</u>

- /nspm - Shows the NoSwearPlz menu.


## Dependencies
 - LuckPerms

## Permissions
### Op by default permissions
- nsp.menu - Allows the player to use /nspm command
- nsp.write - Allows the player to use /nsp commands

###  No one has these permissions by default
- nps.bypass - Allows the player to bypass the filter


## Changelog
- 1.3.2:
  - NoSwearPlz not uses PlzLib & is required
  - Moved NoSwearPlz folder to /PlzSuite/NoSwearPlz
- 1.3.1:
  - Replaced default words.txt file with a shorter one (delete old for new one to appear)
  - Fixed many false positive (thanks to the new words.txt file)
  - Added bannedChatLog.json that stores all messages with a banned word (for debugging)
  - When a player uses a banned word, the console shows the original message (for cases like false positives)
- 1.3.0 : 
  - Fixed bug that would tell players they didn't have permission when moving items in their inventory.
  - Added new filter style to prevent false positives.
  - Removed the need for an exceptions file & its commands.
  - Removed ability to suggest exempt words
  - GUI Menu.
- 1.2.2 : 
  - Added tab completion for commands.
- 1.2.1 : 
  - Added Permissions, more commands, and a menu, & excpetion words