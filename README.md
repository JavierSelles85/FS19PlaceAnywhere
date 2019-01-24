# Place Anywhere mod for Farming Simulator 19
This mod lets you place buildings anywhere in your land, including within other buildings.

![Place Anywhere](https://i.imgur.com/FZ4SIYF.png)

# Installation
1. Download the latest version from the [releases page](https://github.com/napalm00/FS19PlaceAnywhere/releases)
2. Place the downloaded zip in your `Documents/My Games/FarmingSimulator19/mods` folder
3. Launch the game and enable the mod in the mission start screen

# Controls
`0` to toggle terrain deformation (default: deformation on)

`8` to toggle terrain ownership checks (default: land ownership required)

# Configuration
You can change the cost of terrain modifications by opening `PlaceAnywhere.lua` in the mod's zip file and changing the value of
```
PlacementScreenController.DISPLACEMENT_COST_PER_M3 = 1; -- Edit this to change the terrain modification cost per cubic meter (game default: 50)
```

Additionally you can also change the cost of landscaping by editing this line in the same file:
```
Landscaping.SCULPT_BASE_COST_PER_M3 = 1; -- Edit this to change the landscaping cost per cubic meter (game default: 50)
```

# Notes
I've tested this mod and didn't notice any side effects, however it might still cause issues as it removes some game checks.

# Changelog

**1.4**: Added ownership toggle for terraforming/painting tool ([courtesy of 206airmail](https://github.com/napalm00/FS19PlaceAnywhere/pull/4))

**1.3**: Added landscaping cost change and terrain ownership/deformation toggle controls (courtesy of scfmod)

**1.2**: Fixed crash when placing sheds

**1.1**: Fixed bug when buying vehicles

**1.0**: Initial release
