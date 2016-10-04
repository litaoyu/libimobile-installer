# libimobile-installer
An un-official installer for libimobiledevice.
# Instructions

1 - Download the installer and place it in any directory, if you are using `git clone` you don't need to worry about this. If not already set, make the installer executable with `chmod +x ./limdd-install.sh`

2 - Run the installer with `sudo` as the prefix is not by default added to it. For example, you will see `apt-get install something` instead of `sudo apt-get install something` in the installer file. This is so that root users don't get 'no need to run as sudo!' messages constantly.

3 - After connecting the device and the installer has given the details of the device, you should try running `idevicepair`.

That's it.

VERSION: v1.0
