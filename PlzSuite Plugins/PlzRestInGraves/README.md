# PlzRestInGraves

## Description
Add graves to Minecraft!!! Don't just die, die in style!
This will add a grave every time a player dies with their head and their name so they can safely retrieve their belongings.

## Features:
- Places a grave at a player's location with their items (XP not included)
- Access graves from command
- See all graves in the world
- View all graves per player that are active (shows up to 9 at a time, but more can exist).
- Send Message to player on death of death location

## Planned Features:
- Give Players access to view their graves without interacting with it
- Block Players from accessing another player's grave
- Teleport to grave (if enabled by server) from the message given to player
- Storing XP on death
- GUI settings
- Increase max viewable graves screen (paging)
- Nicer looking graves (full "ghost" player, animations, etc.)
- Improve grave interaction (currently requires multiple right-clicks or clicking at a specific area to open. This could be if the head has that extra layer of texture around it that causes the issue)
- Ability to kill all "graves" if graves file is deleted (since the armorstands are both invisible and invulnerable currently)

## Commands
<u>-- PlzRestInGraves Commands --</u>

- /plzgraves <list | open> <PLAYER>

- plzgraves list - Displays a message to the player of a list of active graves on the server

- plzgraves list <PLAYER> - Displays a message the player of a list of active graves for a specific player

- plzgraves open <PLAYER> - opens a GUI displaying all of a player's active graves. If only 1 grave, it displays the grave's contents

- alias: 
  - plzrip

## Dependencies
 - PlzCore

## Permissions
### Op by default permissions
- plzgraves.admin - Allows the player to use the PlzRestInGraves commands

## Changelog
- 1.21.10-alpha:
  - Updated to MC version 1.21.10
  - Updated to be a paper plugin