# Particle Shield Compatibility Tester #

## Flow - HTML ##

1.	User creates a new "shield stack" by selecting among different "base shields"
2.	User adds a new shield to their stack by selecting a shield from a drop down or by searching by manufacturer
3.	Script loads shield config

 - If the shield has a default configuration that configuration is selected. 
 - If the shield does not have a default configuration the user is prompted to select one
 - If the shield does not have configuration data (so no blocking pins) no configuration is shown
5.	Script checks for compatibility issues. 
 - Warnings are shown by highlighting the shield.
 - Additional checks could be performed against all available configurations. 
 - Additionally, results could be cached and stored in a database for faster compatibility check
6.	User repeats step 2 until all shields are selected.
7.	User is given shield stack report
 - Compatibility score (0-100%)
 - OSHW Score (0-100%)
 - Price total (a la OctoPart)
 - Option to purchase shields (Particle + 3rd Party Vendors) as group
 - Option to purchase shields individually 
 - Option to combine shields into a single prototype. (using Professional Services providers automatically calculated)
