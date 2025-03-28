# KICS 4.1.2 [EliteVA] profile changes.

= 29 March 2025 [B 0.33]
- Fixed a bug in the startup command

= 23 March 2025 [B 0.32]
- Shortened the [Build 0.32] part of the profile name to [B 0.32]
- Fixed a couple of bugs in some commands that the QA department missed (OK I missed 'em)
- improved a command by adding spoken feedback

= 21 March 2025 [Build 0.32]
- Updated the c# function in common.commands that checks to see if VA is running as Admin to work on either VA v1 or v2
- Profile now outputs various version info upon 1st load.
- Modified various commands to include some appropriate QoL improvements.
- Added a few options;
	- No fire zone notice on/off
	- Star scoopable notice on/off
	- Station service check on/off (only checks for IF and Rescue service)

= 19 December 2024 [Build 0.31]
- Expanded on the changes made yesterday to include more error checking. Now if an error occurs command processing will be stopped.
- Included profile data so the questions upon first run of the profile are no longer asked, but the info can still be changed to the users liking by running the appropriate commands in Options.

= 18 December 2024 [Build 0.31]
- fixed a filename error so now the saved data should be loaded now once saved after first boot of profile

= 18 November 2024 [Build 0,30]
- Changed 2 commands in the common.commands profile;
	- Log.in.VA
	- Log.in.VA.Multiline
	
	Added an inline function to both commands to handle all the print to log stuff ... made over 60 lines of code redundant

= 16 November 2024 [Build 0.30]
- Tweaked the Nav Panel tab movements due to the Ascendancy Updated, affected commands;
	- Request Docking
- Added 2 more helper functions for Panel Tab movements
- Added a check to make sure the common.commands profile is included within this profile

= 22 May 2024 [Build 0.29]
- added a build number, makes it easier to keep track of things
- went through every command and changed all the global variables to profile ones
- added a check to see if the VLC player was running before trying to play any music
- added feature to auto deploy landing gear once your altitude is less than 1100 metres
	- it will also auto retract once you're above 1000 m
- added some more options to control options;
	- enable/disable music
	- logging show time (shows the current time next to any log messages)
	- no fire zone notice on/off (lets you know when you've entered/exited the no fire zone)
	- turn on/off VA listening
- created a profile package, makes it easier to install the sound files AND the profiles in one go

= 11 February 2024
- Updated all keybinds to now include the following:
	- Missing keybind for: (The key needs to be set in game)
- Updated the *Current game mode* command to now tell you which version of the game you're playing Horizons or Odyssey
- Updated various EliteAPI.Events

= 30 January 2024
- Added options to set various things such as;
	- Set healer firegroup
	- healer trigger
	- ship composition scanner firegroup
	- ship composition scanner trigger
	- ship data link scanner firegroup
	- ship data link scanner trigger
	- SRV composition scanner firegroup
	- SRV composition scanner trigger
	- SRV data link scanner firegroup
	- SRV data link scanner trigger

= 19 January 2024
- Initial release