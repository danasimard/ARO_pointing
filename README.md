# ARO_pointing
Example of generating a pointing script for observations with the ARO 46-m

A few things to keep in mind: 
* ARO slews at ~7-8 deg per minute
* Start tracking your source ~30 sec before you want good data to prevent oscillations
* For steady slewing, you should have one entry in the pointing script per second
* ARO can slew clockwise from 41 degrees, through 360 degrees, to 51 degrees.
