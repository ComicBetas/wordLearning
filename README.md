wordlearning
============

Similar to typeahead: based on what is typed in the past predict words that will probably be used

_Logic_:
<br> Use a COMMON dictionary as a base.
<br> Commonly used words by the user are added to a USER dictionary.
<br> As a user types the JS references the USER dictionary first to give suggestions, then lists words from the COMMON dictionary in a dropdown menu. Every time a user finishes typing the word they typed is added to the USER dictionary. This USER dictionary needs to be editable.

Sample dropdown:
user types in "Ga" and gets the following:
<br>*Gareth*
<br>*Gauntlet*
<br>*Gain*
<br>Gads
<br>Gae
<br>Gale
<br>Gall
<br>Gallent
<br>Garish
<br>Gazette

The ideal dropdown contains:
<br>4*USER
<br>6*COMMON
<br>_behavior_
<br>as USER words become irrelavent they are replaced by COMMON words
<br>as USER words become more relavent they move up the list
