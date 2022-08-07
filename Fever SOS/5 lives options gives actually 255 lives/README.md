# 5 lives option gives actually 255 lives
Tired of putting in more credits while you just want to practice? This change was a fun discovery that it leaves 3 of the 4 options including factory default as is and these training wheels can be opt in through the games own settings.

I stumbled on to this by trying to find patterns that are visible in games UI like the lives settings will go in order from 3 -> 5 -> 2 -> 1.

The settings value are found on rom 33 at 0x41bf (03 05 02 01). This patch changes the 05 to FF value.

There are values around these that also seem to affect the lives count but then they affect no matter what your in game settings are.
For example 04 at 0x41bd was a weird one if set to 00 will start the player wihout any lives and when a life was lost I think it rolled over to 255. Setting any other value seemed to give over 6 lives.

![Alt text](preview.jpg?raw=true "Preview picture")