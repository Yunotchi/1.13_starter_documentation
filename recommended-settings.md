<p align="center">
  <img src="113.png" alt="Jagged Alliance 2 1.13">
</p>

# Jagged Alliance 2 v1.13 - Recommended Settings

> **THIS DOCUMENT IS A WORK IN PROGRESS**

> This documentation is up to date as of 1.13 r8675.

This document provides a set of some settings we recommend taking a look at to potentially make the game more enjoyable for you.
<!--
### Contents
- [1. INI tweaks](#1-ini-tweaks)
- [2. XML tweaks](#2-xml-tweaks)
-->

## 1. INI tweaks
The following settings can be found in `\Data-1.13\JA2_Options.ini`.
> The `1.13` part should be replaced if playing a mod other than 1.13, e.g. `\Data-AIM\JA2_Options.ini` for AIMNAS.

### 1.1 Difficulty related

|  r7609  |  r8675  | Setting | Description |
|  :---:  |  :---:  |   ---   |     ---     |
| &check; | &check; | `TRIGGER_MASSIVE_ENEMY_COUNTERATTACK_AT_DRASSEN` | Should be set to `FALSE` for a new player. It is somewhat infamous for being very difficult to handle so early in the campaign. |
| &cross; | &check; | `REDUCED_INSTANT_DEATH` | Lowers lethal damage to cause the merc to fall into a coma rather than die. |
| &check; | ? | `MINE_INCOME_PERCENTAGE` | Changes how much cash mines generate. |
| ? | ? | `WHICH_MINE_SHUTS_DOWN` | --- |
| &check; | ? | `STEALING_FROM_SHIPMENTS_DISABLED` | Disables stealing from shipments (e.g. Pablo in Drassen). |
| &check; | ? | `CHANCE_OF_SHIPMENT_LOSS` | Sets the chance of a whole shipment from Bobby Ray being lost. |
| &check; | ? | `CHANCE_TONY_AVAILABLE` | Can be set to 100% if you always want to meet Tony (a useful fellow). |
| ? | ? | `ENABLE_ALL_WEAPON_CACHES` | --- |
| ? | ? | `DROP_ALL` | --- |
| &check; | ? | `SELL_ITEMS_WITH_ALT_LMB` | Allows the player to sell their items from the sector inventory screen whenever they wish. |
| ? | ? | `SELL_ITEMS_PRICE_MODIFIER` | --- |

### 1.2 Misc. settings

|  r7609  |  r8675  | Setting | Description |
|  :---:  |  :---:  |   ---   |     ---     |
| &check; | ? | `MERCS_CAN_BE_ON_ASSIGNMENT` | Decides if all mercs will be available at the start of the game and if they will go on other assignments during the campaign. |
| &check; | ? | `MERCS_CAN_DIE_ON_ASSIGNMENT` | Allows mercs to die when away on other assignments. |
| &check; | ? | `SHOW_SKILLS_IN_HIRING_PAGE` | Shows skills and traits as a tooltip on a merc's portrait in both the AIM & MERC hiring page. |
| ? | ? | `SLAY_STAYS_FOREVER` | --- |


## 2. XML tweaks
All XML files can be found in in the `\Data-1.13\TableData` directory.
> The `1.13` part should be replaced if playing a mod other than 1.13, e.g. `\Data-AIM\TableData` for AIMNAS.

TODO: note regarding XML editor

### 2.1 Starting money
To change the amount of money you start with, open `\Data-1.13\TableData\DifficultySettings.xml` and edit the `<StartingCash>` value of the difficulty you want to play.

### 2.2 Vehicle capacity
By default, the helicopter, hummer and ice cream truck all hold a maximum of six mercs. If you are fielding larger squads than this, you can edit each vehicle's capacity to make squad movement easier.

In `\Data-1.13\TableData\Vehicles.xml`, find `<uiIndex>` 160 (hummer), 162 (ice cream truck) and 163 (helicopter). For each, you can change the `<SeatingCapacities>` value from 6 to 8, 10, or whatever you want.


## 3. Advanced

### 3.1 dgVoodoo
TODO: create & upload zip of files; check license!

### 3.2 Wine
TODO