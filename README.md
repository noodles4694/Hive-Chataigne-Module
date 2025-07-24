# Hive-Chataigne-Module

This is a simple Chataigne module for controling Hive Beeblade, Beebox and Nexus media engines with Chataigne.

Installation:

Copy all the files into a folder named Hive and then copy that folder into <Documents>/Chataigne/modules

Usage:

The module can be found under Hardware->Comunity Modules->Hive Beeblade , click the add button in the modules section to add an instance
Add as many instances as you have Beeblades even if they are configured as Queen / Worker groups

In the inspector in the parameters section you need to set the Device IP to the IP of the Hive device.
There are options to auto update layers/modules and effects. By default, all the values for the layers/effects/modules in the vlaues panel with be fetched upon startup of Chataigne, but after that will not update, so if you adjust a value in Chataigne then you are fine but if you adjust a value directly on the Hive player, Chataigne will not know about it.
By enabling the auto update options the values will be updated at the rate set by the Update Rate parameter.

IMPORTANT: Updates of entire sections is havy on network traffic and load on the Hive player, it is much better to use the update commands and only call them just before you need to read a value.

In the value panel you have access to values for all parameters on all layers, all effects on all layers and the parameters and enable/disable of each of the main Hive modules (Playlist,Timecode Cue List, Timeline and Scheduler).

There are a set of commands availiable in the command list, you can choose to update a smaller set of values by triggering Update Layer Values, Update Effect Values or Update Module Values commands.
There are also a set of commands that can be used to control the playlist such as Goto Row x and Goto First Row etc..

Have fun !!
