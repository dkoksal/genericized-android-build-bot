Android-Build-Bot-Script
========================

About:

This script will allow you to automatically build an android ROM and Gapps from their source directories.  


Flags:

Each of these flags acts as a switch that will change the associated variable from a \"y\" to a \"n\" and vise versa.  
It changes it based on the default value set in this script.


Example: ./buildbot -g -s -j 9


-r toggles whether or not to build roms

-g toggles whether or not to build gapps

-s toggles whether or not to run repo sync

-c toffles whether or not to run make clean

-m toggles whether or not to move the roms and gapps to a specified directory after building

-5 toggles whether or not an MD5sum should be generated for both roms and gapps

-a toggles whether or not the fixes to build on Arch Linux should be applied

-j allows you to specify the number to be used in the make command" 