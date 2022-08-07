# Fever SOS rom hack patch files
This is a collection of patch files to make changes to Fever SOS roms. These will not work with Dangun Feveron version of the game.

### Tools
Use an IPS patch utility like for example 'Lunar IPS' to apply the patch.

### Changes
Addition to the change indicated by the folder name. This also removes protection from the ROMs that were preventing 'clean' Fever SOS from working on a JP version of the PCB. Seems that by creating rom hacks triggers some safety mechanism which prevents the roms from booting. This was not my discovery but I needed it as a base when creating my own hacks.

### Testing
These have been tested in MAME by launching the game from a command line witj 'mame.exe .\roms\feversos.zip'. MAME will complain about the hash code not matching but will boot up after around 5-10 seconds after that. Through the GUI it doesn't go past the error that hashcode is not matching.

The 'Change default top-5 score' has also been tested on the international version of the PCB where the is no 'Cave' logo near the JAMMA edge and working.

I Will try to test out the rest on actual hardware as soon as possible and update the documentation.