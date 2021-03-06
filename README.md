Overview
========

Included Mods
-------------

* Lazy Newb Pack for Linux 0.5.3-SNAPSHOT-20130822
* DF Hack 0.34.11-r3
* Falconne's DFHack UI Plugins v0.35
* SoundSense r42 (app only)
* Tilesets
  - [08x12] ASCII Default 0.34.11
  - [09x12] Jolly Bastion 34.10v5
  - [12x12] Jolly Bastion 34.10v5
  - [16x16] CLA v15
  - [16x16] Ironhand 0.73.4
  - [16x16] Mayday 0.34.11
  - [16x16] Phoebus 34.11v01
  - [16x16] Obsidian 0.8a
  - [16x16] Spacefox 34.11v1.0


Features
========

Complete
--------

 * Downloads and installs the latest Lazy Newb Pack UI.
 * Downloads and installs tilesets.
 * Checks all files for SHA1 validity.
 
TODO
----

 * Automatically check your system for program requirements and install as necessary.
 * Continue adding more features from the Windows and Mac LNPs.


System Requirements
===================

* A Java runtime environment for the LNP GUI.
* SDL 1.2, 32-bit
* OpenAL 1.2, 32-bit
* Git
* The following fairly standard Linux utilities:
  - wget
  - sha1sum
  - tar
  - unzip
  - unrar



Full Installation
=================

0. Clone the git repository with "git clone https://github.com/andrewd18/df-lnp-installer.git"
1. Run ./df-lnp-installer.sh and follow the prompts.
2. Once DF is installed, enter the DF folder and run ./startlnp.
3. Start the SoundSense r42 utility from the Utilities tab.
4. Point SoundSense at the df_linux/gamelog.txt file.
5. Click the "Pack Update" tab.
6. Click "Start Automatic Update".
7. Get a Dwarven Ale; it's going to be a while.
8. Once finished, close SoundSense, and muck about with LNP as normal.

Tested On
=========

* Debian 7 "Wheezy", stable, using Dash (default) shell.