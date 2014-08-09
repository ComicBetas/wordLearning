wordlearning
============

Similar to typeahead: based on what is typed in the past predict words that will probably be used

Logic:
use a COMMON dictionary as a base
commonly used words are added to a USER dictionary
as a user types the JS references the USER dictionary first to give suggestions, then lists words from the COMMON dictionary in a dropdown menu:

Sample dropdown:
user types in "Ga" and gets the following:
*Gareth*
*Gauntlet*
Gads
Gae
Gain
Gale
Gall
Gallent
Garish
Gazette

2*USER
8*COMMON
as USER words become irrelevant they are replaced by COMMON words
