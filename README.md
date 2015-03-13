Ethanon Engine: sublime plugin (linux)
===========================

Through this modification in the build system file (Ethanon Engine's build system for sublime) it's possible compile your project on Linux to Windows and run it through the wine.

Dependencies
============
* wine (https://www.winehq.org/download/)

Installation
==============

- Open Sublime Text, go to **Preferences** -> **Browse Packages**
- Copy the directory "/Ethanon/" to "sublime-dir/Packages/"


Setting up build option
==============

- Open the *.angelscript file from your project with Sublime Text
- Go to **Tools** -> **Build system** and pick **Ethanon**
- Use **Ctrl + B** to Build and **F5** to Run
