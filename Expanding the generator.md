**Adding new rule element keys**

* Edit the rule element csv file and add a new row, fill in a friendly name and the full key for rule element then enter y or n for each option.  At this point selector == mandatory is not needed and likely won't ever be used but for the few rule elements that don't need selectors this would in theory let us skip the selector step.
* Once all options are filled out save the csv, the new key is ready to use.

**Adding a new selector**
* Add the selector in selectors.csv
* Add the selector to RuleElements.csv and fill in y/n for each current key.  If in doubt enter n.

**Adding new options**
* Add the option to the options.csv
* Add the new option as an argument for PrepareOptions()
** Add a new step in the PrepareOptions() to format the option correctly.  Follow the existing steps as an example.
* Add default values and a disabled=True line in ResetState().
* Add a new conditional in SetSelector() for the new option to enable it by setting disabled=False.
* Add the new option as an input for the PrepareOptions() call in FinishElement()
* Create a new widget as an input, set a default value that will leave it blank if not filled in ('' works normally).
** Set disabled=True
* Add a display call where you want the input at.
