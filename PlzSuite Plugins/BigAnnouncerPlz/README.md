# BigAnnouncerPlz

## Description
This plugin allows announcements to happen on the server that can run repeatedly and automatically.


## Features:
- Add a message to display on the server at a specified frequency.

## Planned Features:
- Control with GUI
- Add Announcements that appear in-front of the player (Large text or invisible armorstand or private message)

## Commands
<u>-- BigAnnouncerPlz Commands --</u>

- /plzannounce <add | remove> <frequency_type> <frequency_value> <text>

- alias:
  - plza

  FREQUENCY_TYPES:
  * ONCE
  * SECONDS
  * MINUTES
  * HOURLY
  * DAILY
  * WEKKLY
  * MONTHLY

  FREQUENCY_VALUES: any positive number

  TEXT: What you want the announcement to say

## Dependencies
 - PlzCore

## Permissions
### Op by default permissions
- plzbigannounce.admin - Allows the player to use the BigAnnouncerPlz commands



## Changelog
- 1.21.10-alpha:
  - Updated to MC version 1.21.10
  - Updated to be a paper plugin