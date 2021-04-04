# RuleElementGenerator

This is a working rule element generator for the Foundry VTT PF2e system.  

* To run it you must either use the binder link [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TikaelSol/RuleElementGenerator/HEAD) or download the repository and run it using Jupyter.
* Once Binder has loaded, open 'RuleElements.ipynb' then from the cell menu select 'Run All'.
* The code will hide itself and you'll see the interface for generating rule elements.
* Scroll down to see a gif of this in action making a rule element that will apply a +1 potency rune to all unarmed attacks.

There is also a bracket maker, to use it just open the BracketGenerator.ipynb file and run the cell, the prompts will ask you for input.  If you want to make a new one run the code cell again.

Notes:
* For general questions about rule elements or to learn the more advanced features please visit the PF2e system wiki (https://gitlab.com/hooking/foundry-vtt---pathfinder-2e/-/wikis/Quickstart-guide-for-rule-elements) or the PF2e channel on the Foundry Discord (https://discord.gg/foundryvtt).
* If you cannot enter a value in a cell that cell is disabled by choices you made earlier.  For example a bonus to intimidation checks will not have a damage type field, so this input is disabled unless you have a rule that supports it.
* The "Create Rule Element" button takes the current selections in all fields, the "Set" buttons just determine which fields to enable. So if you change the key or selector you can end up with an invalid rule element.
* Advanced selectors always display, but most combinations of selector and advanced selector don't make sense.
* When using override remember that the number of dice will be bonus dice.  So if you just want to change the base damage to d12 without adding dice the dice number should be 0.
* If you encounter an issue please submit an Issue on the github page (https://github.com/TikaelSol/RuleElementGenerator/issues) or ping me on Discord (Tikael#6851).

I know the code isn't commented and parts are probably superflous.  I will be commenting the code soon for anyone wanting to follow along.  This is my first time using iPython widgets so I'm sure some implementation could be done cleaner.


![rulelementgenerator](https://user-images.githubusercontent.com/80183198/113496306-5971d580-94c6-11eb-91c6-67aa7b50edcc.gif)
