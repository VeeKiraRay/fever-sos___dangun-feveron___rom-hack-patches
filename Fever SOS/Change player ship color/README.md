# Change player ship color
There are 255 possible ship color palettes. I think most of them are loaned from enemies or some other GFX.

In the preview picture you can see a few options including the default ones. 
These patches apply 05 for player one and 08 for player two but you can change the value by editing the the cv01-u34.ips file with a hex editor. By changing the 4th last value from 05 or 08 to something between 00 and FF you can get different results.

The P1 ship color is at 0x528E (03) and P2 ship color is at 0x529A (22)

![Alt text](preview.jpg?raw=true "Preview picture")
