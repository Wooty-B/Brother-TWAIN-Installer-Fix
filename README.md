# Brother TWAIN Installer Fix

This is a batch file I created to repair the Windows 7/8/10+ Brother Print & Scanner installer when it thinks a TWAIN driver is already installed. Several years ago issues popped up at work when trying to repair a Brother scanning issue. Some of the issues I ran across were:

- When trying to reinstall, a restart would be required after removing all drivers before the "Scanner Driver" option would appear.
- When trying to reinstall, after removing all drivers and restarting, sometimes I would still get an issue with the "Scanner Driver" missing.

This script simply removes the offending Windows registry entry and allows you to immediately select the Scanner Driver upon relaunching the installer.

As a precaution, as with any random registry keys/scripts downloaded off the internet, please be mindful and backup your existing keys and examine the .REG file beforehand.

Check "Releases" for the script.
