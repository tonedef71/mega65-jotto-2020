This D81 disk image may be used to build a release disk.  It is to be run on the MEGA65 or XMEGA64 emulator to transforms a blank D81 disk image into a game disk image by copying over the game files and creating the
random files which are needed by the game at runtime.

To begin, mount this disk image (the source disk) to unit 8 and then mount a blank target disk image to unit 9.

Load and run the program "prepare-target" from unit 8.

At the first prompt, select 8 as the source drive.

At the second prompt, select 9 as the target drive.

At the third and final prompt, press the "q" key to quit or any other key to proceed with the setup.

When the program finishes, the target disk will be ready for playing the game.