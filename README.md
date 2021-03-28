# RuleElementGenerator

This is a working rule element generator for the Foundry VTT PF2e system.

* To run it you must either use the binder link [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TikaelSol/RuleElementGenerator/HEAD) or download the repository and run it using Jupyter.
* Once Binder has loaded, open 'RuleElements.ipynb' then from the cell menu select 'Run All'.
* The code will hide itself and you'll see the interface for generating rule elements.


Notes:
* For general questions about rule elements or to learn the more advanced features please visit the PF2e system wiki (https://gitlab.com/hooking/foundry-vtt---pathfinder-2e/-/wikis/Quickstart-guide-for-rule-elements) or the PF2e channel on the Foundry Discord (https://discord.gg/foundryvtt).
* If you cannot enter a value in a cell that cell is disabled by choices you made earlier.  For example a bonus to intimidation checks will not have a damage type field, so this input is disabled unless you have a rule that supports it.
* The "Create Rule Element" button takes the current selections in all fields, the "Set" buttons just determine which fields to enable. So if you change the key or selector you can end up with an invalid rule element.
* Advanced selectors always display, but most combinations of selector and advanced selector don't make sense.
* When using override remember that the number of dice will be bonus dice.  So if you just want to change the base damage to d12 without adding dice the dice number should be 0.
* If you encounter an issue please submit an Issue on the github page (https://github.com/TikaelSol/RuleElementGenerator/issues) or ping me on Discord (Tikael#6851).
