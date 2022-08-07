# fever-sos___dangun-feveron___rom-hack-patches
Collection of different patch files to get changes for either Fever SOS or Dangun Feveron roms.

### Patches
- Lower the default top-5 highscore table so it is easier to get your own score there
- Change the initials of the default top-5 scores
- Change the number of disco men the default top-5 have
- Change ship color (P1 and P2)
- Have 255 lives if you select start with 5 lives options from settings (Other number of lives settings work as normal)

### Background
These are  my first rom hacks and other people have already done most of the heavy lifting regarding Fever SOS and the Dangun Feveron rom hacks.

Zakk4223 had made the 5th highscore change for Dangun Feveron which was the inspiration to get similar effect for the Fever SOS version. The same patch script didn't work for Fever SOS since the data is slightly in a different place but the data was similar regarding the scores that it helped me found what I needed to change faster.
https://github.com/zakk4223/dangun-feveron-patches

There was also a change in Zakk patch script to make the ROM check always pass. There is no visible ROM/RAM check ok screen in Dangun Feveron / Fever SOS and my knowledge on how the actual game runs is pretty shallow at the moment so didn't know what it does actually. When I tried to replicate similar changes for the Fever SOS the game worked fine on MAME but when I tried it on the actual PCB it just kept reseting the game before proper boot up.

There was however patch for the Fever SOS to remove security protection so it could be run on actual JP version of PCB. By copying the changes made to that I was able to get the game running on both MAME and actual international version of the PCB. 

### Tools
Use an IPS patch utility like for example 'Lunar IPS' to apply the patches.

If you would like to continue the work or make the changes without patch files you will need a 'Hex editor'. There are a lot of options for this, but I used 'Cygnus Hex Editor' which you can buy for cheap from Windows Store.
