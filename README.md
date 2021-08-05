# Chitubox_install_script
This script will install chitubox (with icons and .desktop link).

## This is intended to be used on Ubuntu 20.04, Pop!_OS 20.04 and Solus 4.
It may work on other distros, please let me know and I'll update this readme.

# What it does
- Deploys Chitubox with your other apps (in /usr/bin)
- Creates a Wrapper-Script to use the included Libraries
- Creates a .desktop file, so you can access Chitubox from Gnome, like any other app
- Deploys the icon, required for the above .desktop link
- Creates file association for .chitubox files (chitubox project file format)

# Instructions
1. Download/Clone this repo
2. Download the linux **version 1.8.1** of Chitubox from https://www.chitubox.com/download.html (**you will need to create a Chitubox account**)
3. Place the downloaded tar.gz in the same directory as the install script
4. Run the install script (**root access will be required**). If required, add exec permission with *chmod +x*.
Note: You may have to restart your session for the icon to be properly displayed in gnome
