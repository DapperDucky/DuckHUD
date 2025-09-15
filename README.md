# DuckHUD [**BETA**]

A minimalistic Heads Up Display for Dual Universe

***When you think Heads Up, think Duck!***

## Contents

1. [Contents](#contents)
1. [Installation](#installation)
1. [Overview](#overview)
1. [Support](#support)

## Overview

DuckHUD is a minimalistic general purpose heads up display with a focus on providing useful and easy to digest information and functionality without overwhelming the pilot's screen or the game's performance.

[Buy me a coffee I can turn into code](buymeacoffee.com/DapperDucky)

## Installation

To install and use DuckHUD:

1. Add the ```duckhud_vx_x_x.conf``` to your Dual Universe ```\My Dual Universe\Game\data\lua\autoconf``` directory
1. Restart the game to ensure that new configuration is loaded correctly by Dual Universe
1. Apply the configuration to the control unit in game
   + This can be done by using the control units in-game menu and navigating to ```Advanced > Run Custom Autoconfigure``` and selecting DuckHud from the list

To get the most out of the HUD the construct should a gyroscope. (***Note:** How a gyroscope is placed on a construct matters. It should be oriented the same as the core to ensure correct avionics*)


## Custom Controls

+ Select next custom destination: Press ```ALT+1```
+ Clear custom destination: Hold ```ALT+1``` for 2 seconds
+ Place waypoint marker from custom destination: Press ```ALT+2```
+ Place waypoint marker to nearest edge of safe space: Press ```ALT+3```
+ Increase sunsheild: Press ```ALT+8```
+ Decrease sunshield: Press ```ALT+9```

## Text Commands

*Text commands are entered via the lua chat channel while piloting the construct*

+ Save a new custom destination: ```wp <POS> <NAME>``` ex. ```wp ::pos{0,0,34312,51234,41324} Diven's Cool Space Base```
+ Set antigravity target altitude in meters: ```ag <TARGET ALTITUDE>``` ex. ```ag 2500```
+ Enable antigravity: ```ag on``` or ```ag enabled```
+ Disable antigravity: ```ag off``` or ```ag disabled```

## Support

[Buy me a coffee I can turn into code](buymeacoffee.com/DapperDucky)
