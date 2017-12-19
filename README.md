# retropie-burninator

This python script extracts a retropie gzip archive and burns it to your SD card.

Simply place retropie-burninator in the same folder as your retorpie gzip archive,
plug your SD card into your computer, and run the burninator.

At this time, the script will only work in Linux. 
The user that executes the script must be in the system's sudoers file.

Feel free to modify and make the burninator better!

If you have questions, tweet at me: @redsquirrel_7

V1.1 Release notes:
- Fixed umount permission error

V1.2 Release notes:
- Fixed check for archives
- Changed message for when there is more than one archive found
