# Automagical
Automagical is a collection of handy OSX Automations for WordPress website dev

## Setup

1. Clone (or download) the repo to your computer
2. Double click on of the Automation files
3. Sit back and bask in the glory

## How They Work

Automation files are files for the Automator application included in OSX (sorry Windows users). You don't need to have Automator running to execute an Automator file.

### Basic WordPress

1. Double click the Automator file
2. You'll be prompted to enter a name for the folder (default is WordPress). This will be placed on your desktop. To avoid errors, keep words lower case and hyphenate them together. Avoid special characters or symbols as well. You can change the folder name after the Automation has run.
3. Automator will then run away and grab the latest copy of WordPress. It will unzip all the files and clean up afterwards. This includes removing the license.txt and readme.html.

*While the automation is running, you will see a small gear icon spinning in the menu bar. This icon will disappear once the automator file has finished.*

### WordPress with Theme

The WordPress with Theme automation will follow the first three steps of the Basic WordPress automation:

1. Once WordPress has downloaded, unzipped and cleaned itseld up, a dialog will open prompting you to enter a name for your WordPress theme (to be placed in the wp-content/themes directory). For the theme name - keep words lower case and hyphenate them together. Avoid special characters or symbols as well.
2. Once you give the theme folder a name a dialog will open asking you to locate the theme on your HDD to copy from. If you're like me, you'll have a directory on your HDD with some base starter WordPress themes in it. The dialog will default to the Desktop and you can navigate from there.
3. Once you select the folder, a copy of all the files in it will be made and pasted in the theme folder you just created.
4. You're good to go.

Hopefully you will find these automations save you a bunch of time setting up your new WordPress installs!