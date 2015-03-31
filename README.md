Ethanon Engine's Sublime plugin 4 LINUX
===========================

Through this modified sublime text plugin is possible to develop your Ethanon Engine's projects on Linux. (does not compile for Linux, only generates a new updated game.bin).

* What's my point ?
  * Being capable of develop for Android and Windows from Linux. The game.bin bytecode generated by Ethanon is universal, just changing their nomenclature (example: android_game.bin, ios_game.bin). (http://doc.ethanonengine.com/manual/83)


Dependencies
============
* wine (https://www.winehq.org)
* ethanon engine (www.ethanonengine.com)
 * download the SDK Windows and install through wine
* sublime text (http://www.sublimetext.com/)
 * linux build

Installation
==============

- Open Sublime Text, go to **Preferences** -> **Browse Packages**
- Copy the directory "/Ethanon/" to "sublime-dir/Packages/"


Setting up build option
==============

- Open the main.angelscript file from your project with Sublime Text
- Go to **Tools** -> **Build system** and pick **Ethanon**
- Use **Ctrl + B** to Build and **F5** to Run
