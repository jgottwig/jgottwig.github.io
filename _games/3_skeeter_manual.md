---
title: "Skeeter's Grid Gameplay Manual"
categories:
  - games
image:
  path: /images/games/skeeters-grid-banner.jpg
  thumbnail: /images/games/controls-thumb.png
  caption: "Skeeter's Grid Manual"
permalink: /games/skeeters-grid-manual/ 
---
Early Access Skeeter's Grid Manual
---

*Disclaimer: Because this game is in Early Access, this manual is subject to change. Not only this, but it may be necessary to purge some or all saved data in the event of structural changes. This will happen automatically and will hopefully be minimal.*

The general concept of Skeeter's Grid is simple:

Reconnect the data hubs.

These hubs, for the most part, take the form of the data-towers as seen in grid 0.0.0.

| ![data-tower](/images/games/skeet-help/hub.png) |
|:--:|
| *data-tower* (example) |

Skeet completes grids by rotating light-cubes and trading light-cubes with null-cubes until the path is completed. Once Skeet has a Mobility Core, you can also swap most cubes, but this function costs Skeet juice, which can take time to replenish, so hold this tool in reserve.

| ![null-cube](/images/games/skeet-help/null-cube.png) |
|:--:|
| *null-cube* |

| ![light-cube](/images/games/skeet-help/light-cube.png) |
|:--:|
| *light-cube (example) |

There are often multiple solutions to any grid, but it is possible to use every light-cube (which yields a points bonus and achievement) on even the most complex of grids.

Because there can sometimes be multiple active hubs in any given grid, the active hub can be identified by a gentle pulsing. Every few pulses, the active hub will also release a spray of sparks

Once the grid is completed (and this may require connecting multiple hubs), the elevator will re-active. Return to the elevator (either by skipping or recalling) to continue to the next grid.

| ![elevator](/images/games/skeet-help/elevator.png) |
|:--:|
| *elevator* |

Playing the game in *Story / Tutorial* mode should provide the contextual controls needed to understand the game, and thus, is recommended, but one can just as easily use hold the Help key to get a list of available actions. Note that if a control is out-of-context at the time, it will not appear in Help. Contextual actions are noted in the list of controls below. For example, if Skeet isn't standing on an activatable cube, the Activate action will not appear in the list of Help commands, and thus, is out of context.

Note that, at this time, only Keyboard and Steamdeck/XBox controls are tested and supported. I did attempt adding support for Playstation and Switch controllers as well, but this functionality is unverified. Touch is completely unsupported, but I hope to add it eventually.

## Controls

If a control is market as contextual, it is not always available.

### Move

![W A S D](/images/games/skeet-help/keyboard-wasd.png)

![D-Pad](/images/games/skeet-help/gamepad-dpad.png)

Basic move and Skeet skips across the grid. Or, if Skeet is standing on a light-cube and moves into a null-cube, the light-cube will trade places with the null-cube. I did, begrudgingly, add support for analog stick, but d-pad is the intended movement schema.
* Contextual? No

### Rotate

![Left and Right Arrow Keys](/images/games/skeet-help/keyboard-lr.png)

![Triggers](/images/games/skeet-help/gamepad-triggers.png)

When standing over any unlocked light-cube, tap one of the rotate buttons, and the cube will rotate either clockwise or counter-clockwise.
* Contextual? No

### Jump (hold)

![Hold Down Arrow](/images/games/skeet-help/keyboard-down.png)

![Hold South Button](/images/games/skeet-help/gamepad-south.png)

For Skeet to jump, hold the action button for a second or so and tap a direction. If nothing in the way, Skeet will jump over any single cube or empty space.
* Contextual? No

### Activate (tap)

![Down Arrow](/images/games/skeet-help/keyboard-down.png)

![South Button](/images/games/skeet-help/gamepad-south.png)

Some cubes or tools need to be activated. Tap the action button. If a task takes time to activate, tapping this button will cancel activation in most cases.
* Contextual? Yes
* Some Cubes Require: Security Core

### Recall (hold)

![R key](/images/games/skeet-help/keyboard-r.png)

![North Button](/images/games/skeet-help/gamepad-north.png)

Once a grid is complete, hold the recall key/button for a quick trip back to the elevator. This option only appears if the elevator is activated.
* Contextual? Yes

### Swap (tap)

![Down Arrow](/images/games/skeet-help/keyboard-down.png)

![South Button](/images/games/skeet-help/gamepad-south.png)

Use Skeet's juice to swap two unlocked cubes. Keep in mind that Skeet's juice is a limited resource but can be replenished.
* Contextual? Yes
* Requires: Mobility Core

### Help (hold)

![H Key](/images/games/skeet-help/keyboard-h.png)

![West Button](/images/games/skeet-help/gamepad-west.png)

Hold the Help key/button to get a list of possible actions. This list should (generally) be truncated to list only available actions.
* Contextual? No. 

### Pause

![Escape](/images/games/skeet-help/keyboard-esc.png)

![East Button](/images/games/skeet-help/gamepad-east.png)

Opens the pause menu, which includes options for restarting a grid, scrolling through collectables, and evaluating completed grids.
* Contextual? No (but game will not pause during some transitions)
