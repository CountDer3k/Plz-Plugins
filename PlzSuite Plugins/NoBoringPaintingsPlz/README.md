# NoBoringPaintingsPlz

## Description
Bring a touch of reality to your server. Create custom paintings and maps from image you have or from the web.
This is an ongoing project & more features/image type support will be added in time.

## Features:
- Create a custom painting of a specified size as a single painting
- Create a custom painting of a specified size as multiple individual paintings
- Create custom paintings from local images
- Create custom paintings from web images
- Create custom maps from local images
- Supports (JPG/JPEG, PNG, BMP, WBMP, GIF [maybe])

## Planned Features:
- Create custom maps from web images
- Allow non-op players to create custom images
- Support for gif
- Support for more image types
- Support for WEBP images
- Support for videos
- Make painting unbreakable without custom tool
- Resize painting when on wall
- Store images to be reusable (save on processing power & improve speed)
- Add NSFW filters to prevent unsafe images from being loaded by players.

## Commands
<u>-- NoBoringPaintingsPlz Commands --</u>

- /plzpaint <stored | url> <IMAGE_NAME> <WIDTH> <HEIGHT> <combined | split>

- /plzpaint stored <IMAGE_NAME> <WIDTH> <HEIGHT> combined - Creates a custom painting from an image stored in "plugins/PlzSuite/NoBoringPaintings/images" as a single painting item.

- /plzpaint stored <IMAGE_NAME> <WIDTH> <HEIGHT> split - Creates a custom painting from an image stored in "plugins/PlzSuite/ NoBoringPaintings/images" split into multiple separate painting items.

- /plzpaint url <URL> <WIDTH> <HEIGHT> combined - Creates a custom painting from the url (must be an image) as a single painting item.

- alias:
  - plzp


- plzreplacemap <MAP_ID> <IMAGE_NAME> - Replaces a map with a custom image (must be an already processed image)

- alias:
  - plzpm


## Dependencies
 - PlzCore

## Permissions
### Op by default permissions
- plzpaint.admin - Allows the player to use the NoBoringPaintingsPlz commands

###  No one has these permissions by default
- plzpaint.create - Allows the player to create custom painting maps


## Changelog
- 1.21.10-alpha:
  - Updated to MC version 1.21.10
  - Updated to be a paper plugin