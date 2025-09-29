### CHANGELOG

## 1.4.2

* Fixed shield buff text when recasting if having one active, the absorbed damage value was not reset

## 1.4.1

* Added remaining absorb damage to the magic shield buff icon, dynamically updated when being hit
* Fixed several text updates during the blood magic skill events. For the record, the Blood Magic skill up happens when:
  * your tamed allies hit an enemy (summoned troll is NOT an enemy)
  * your magic shield is destroyed or your tamed allies magic shields are destroyed

## 1.4.0

* Updated custom options panel with same background as rest of game window backgrounds
* Little tweak to skill up message sliders when the value is 0 (messages are not shown)
* Fixed skill up messages when slider values are 0 (they must not pop up)

## 1.3.7

* Fixed new skill "dodge" to update on buffs section at the same time a dodge is done successfully
* Recompiled with latest game libraries. Everything else didn't break with the update.

## 1.3.6

* Update libraries for latest game version
* Fixed issue with level up messages

## 1.3.5

* Translating options panel in .cfg file
* Small adjust to panel options

## 1.3.4

* Using inventory font style for detailed levels menu

## 1.3.3

* ServerSync integration
* Added option to configure the skill loss percentage in the world (server-synced)

## 1.3.2

* Small fix to prevent random NREs when opening inventory
* Default hotkey changed to F4

## 1.3.1

* Small fix for exception when pressing Esc or tab for first time in the game

## 1.3.0

* Created wood panel with options for the mod at the bottom of the skills dialog panel (only in English for now):
	1) Added existing options of current skill loss and reload tracked skills after dying
	2) Added new controls to configure level up messages
* Now the toggle value to reload skill buffs after dying remains when exiting the game
* Removed option to disable the mod by config (who does after installing a mod anyway lol)

## 1.2.2

* Added toggle in skills panel to save skill buffs when dying and setting them automatically when respawning

## 1.2.1

* Added small icon and text with exact value of the skills percentage lost when dying (not hardcoded. If you change with other mods, it will be shown here)
* Added option to change skill background color in skills dialog from configuration file

## 1.2.0

* Added new buttons to sort skills dialog by name and by skill, up and down
* Fixed skill dialog hotfix to avoid opening/closing while game is paused

## 1.1.2

* Adding hotkey to skill dialog button tooltip in inventory

## 1.1.1

* Added configurable hot key to open/close skills dialog (default = F7)
* Fixed issue when new skill is learnt, it was not creating the buff at that very moment

## 1.1.0

* Added new feature to select skills and attach them to the buff UI and check progress continuously while fighting, running, building, etc

## 1.0.3

* Small fix for removing error in log when loading mod

## 1.0.2

* Small fix for yellow message when showing level achieved
* Refactored code for future new features

## 1.0.1

* Added configuration file for manipulating new options
* Enable/disable the mod and the debug logs entirely (logs disabled by default)
* Choose how many decimals you want to see from 0 to 15 (default = 2)
* Choose how often you want to see the yellow message in the center when you skill up (default = each 5 levels)

## 1.0.0

Initial version