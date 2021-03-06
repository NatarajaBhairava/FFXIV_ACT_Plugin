FFXIV_ACT_Plugin
================
The ACT Parsing Plugin for Final Fantasy XIV

This project is to track releases and issues for the ACT FFXIV Plugin.  The source code is not currently public.

The DLL file included in this project  enables the multi-game parser Advanced Combat Tracker (ACT) to process and display combat information from Final Fantasy XIV patch 4.50. 

DISCLAIMER: Use of this program is at your own risk. Square Enix does not permit the use of any third party tools, even those which do not modify the game.  They have stated in interviews that they did not view parsers as a significant problem unless players use them to harass other players, so the consensus is to not discuss parsers or DPS in-game at all.

I have started a Discord server for discussions regarding this plugin. All are welcome to join, but keep in mind this is for the purpose of developing and improving the plugin, and so may be moderated if discussions go wild.
https://discord.gg/ahFKcmx

Installation Instructions:

1) Download & install ACT. If you have an existing ACT installation, please remove any other plugins, to ensure there are not any conflicts to start with.  ACT can be downloaded here:<br>
http://advancedcombattracker.com/download.php

2) Make sure FFXIV is running in DX11 mode.  You can verify this by opening the FFXIV Launcher and clicking the gear icon on the bottom row.  There is a slider that must be turned on to enable DX11.

3) Launch the ACT Startup Wizard. On the Parsing Plugin tab, click the 'Get Available parsing plugins' button. Choose #73 "FFXIV Parsing Plugin", and click the "Use this plugin" button. Continue the wizard or close it as desired.

4) Make a decision to either:
* Parse FFXIV data by scanning network data sent to FFXIV.  This will improve the overall parse quality, because network data is communicated reliably to the plugin, and includes some data which is not available in memory.  If you choose this:
    a) You must run ACT as an Administrator.
    b) You must configure your firewall software to allow ACT to communicate through it.  Reddit user Xepher01 contributed some instructions for Windows 7  <a href="http://imgur.com/a/QU86T">here</a>, and EQ2Flames user Aristar added instructions for windows 8 & 10  <a href="http://imgur.com/a/HiGKr">here</a>.
* If you prefer to not use this data, you can instead parse from game memory.  To do this, you must check the "Disable Parsing from Network Data" checkbox on the FFXIV Settings tab inside ACT.  
 
However, keep in mind that there are known problems with memory-only parsing that will cause some combat information to be lost.  Network mode is more accurate, and should always be used when comparing parses between players.



