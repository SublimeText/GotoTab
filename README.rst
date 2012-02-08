Description
-----------
Lets you open tabs tab number # counting from the left in Sublime Text 2. See: http://www.sublimetext.com/ 

Package Installation
--------------------
From the package manager (https://github.com/wbond/package_control_channel), this is listed under 'GotoTab'.

From Git:

* Bring up a git-enabled command line in the Packages/ folder of your Sublime user folder, and execute the following:

  > git clone git://github.com/leegould/GotoTab.git


Install manually:

* Download this repository

* Go to menu "Preferences" -> "Browse Packages"

* There should be a lot of folders. Create a new folder called "GotoTab"

* Put this repository into that folder


Defaults
--------
* The default windows key bindings set ctrl-1 through ctrl-0 as tabs 1 through 10
* The default osx key bindings set cmd-1 through cmd-0 as tabs 1 through 10

Usage
-----
The plugin allows you to switch to the numbered tab via a key binding. Currently bindings are included for Windows and OSX.

After you have installed the plugin; an example of use, if you have 3 files open in 3 tabs, pressing ctrl+1 (windows) / 
cmd-1 (OSX) will switch to the first tab, ctrl+2/cmd+2 will switch to the second tab and ctrl+3/cmd+3 will switch to the third tab. 
ctrl+4/cmd+4 will do nothing until you have a fourth tab open.