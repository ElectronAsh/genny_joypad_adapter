# genny_joypad_adapter
Genesis / MD joypad adapter for old-skool computers and consoles.

WARNING: Please do not use this adapter yet!

It's still a work-in-progress, and damage may occur to both the console / computer and the joypad.

The resistors should limit the maximum current on each signal pin, and it should in theory work on the "Atari style" joystick ports, 
on machines like the Atari 2600/400/800/1200/130XE/ST, Amiga, Vic 20, C64 / C64GS etc.

The diodes allow the Genesis joypad to only pull the signals LOW on the computer side.

The DIP switches are for enabling two-button support for the Atari 7800.

DIP switch 1 enables connection of pin 6, which is normally the "Fire" button on many retro machines.

DIP switches 2 and 3 allow the PNP transistors to drive pins 9 and 5 HIGH, as those are Active-High on the 7800.
Buttons B and C on the Genesis joypad can then be used as "Left Button" / "Right Button" (respectively) on the 7800.

All DIP switches should be OFF when the adapter is used with machines other than the Atari 7800.

