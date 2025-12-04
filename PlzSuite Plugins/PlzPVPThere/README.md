# PlzPVPThere

## Description
A custom PVP interaction plugin. Allows setting custom PVP rules for players, worlds, or areas.

## Features:
- Enable/Disable PVP in a world
- Enable/Disable PVP for specified player

## Planned Features:
- GUI settings
- Enable/Disable PVP for areas of the world
- Enable/Disable PVP when a player/entity is around (like admin sharing something so no one within a certain radius can fight, useful for livestream events)
- Support for factions (Plugins to support pending)


## Commands
<u>-- PlzPVPThere Commands --</u>

- /plzpvpthere <world | player> <NAME> <enable | disable>

- alias:
  - plzpvp

- plzpvpthere world <WORLD_NAME> <enable | disable > - Enable/Disable PVP in world

- plzpvpthere player <PLAYER_NAME> <enable | disable > - Enable/Disable PVP for a specified player


## Dependencies
 - PlzCore

## Permissions
### Op by default permissions
- plzpvpthere.admin - Allows the player to use the PlzPVPThere commands
- plzpvpthere.blocked - Blocks the player from PVP

## Changelog
- 1.21.10-alpha:
  - Updated to MC version 1.21.10
  - Updated to be a paper plugin