# SimpleBatteryViewer
This is a fork of the SimpleBatteryViewer plugin for PSP and Adrenaline (PS Vita), with a one-line change that adds support for viewing battery info in the HOME menu while playing PSX games via POPS. All other functionality is unchanged.

For more detailed documentation, see https://www.gamebrew.org/wiki/Simple_Battery_Viewer_PSP.

## Installation

Note: This plugin uses prxcmlib_pack.zip from [prxlibmenu](https://code.google.com/p/prx-common-libraries/downloads/list) (unzip and copy the lib folder to seplugins).

To install, copy SimpleBatteryViewer.prx to the seplugins folder of your Memory Stick (or internal storage for PSP Go).

Open game.txt and pops.txt in the same seplugins folder, then write the following path

> ms0:/seplugins/SimpleBatteryViewer.prx 1

For PSP Go, add this line to the text files instead

> ef0:/seplugins/SimpleBatteryViewer.prx 1

## User Guide

The battery information will be displayed just below where the date and time located (on the Home screen).

## Compatibility

Supported Firmwares:

6.20 to 6.60 
