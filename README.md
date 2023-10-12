# Watermelon-Game-English-Patch

Hello! This is an English translation patch for スイカゲーム aka Watermelon Game. 
The patches are in xdelta format and you'll need a couple of things to get started.

First, you need xDelta: https://www.romhacking.net/utilities/598/
and NxDumpTool: https://github.com/DarkMatterCore/nxdumptool

Use NxDumpTool to create a romFS dump of your copy of the game, then get 3 files from your dump.
"resources.assets" ; "sharedassets1.assets" ; "sharedassets3.assets"

Copy them into wherever you put your xDelta patches from the download, and patch each file from your romFS dump with the corresponding patch.

Then, we'll make a LayeredFS folder structure to have these newly patched files loaded instead of the original game files.

Folder structure should look like this:

SDROOT\atmosphere\contents\0100800015926000\romfs\Data\*3 patched files here*

Start up the game and enjoy! There is a tiny bit of untranslated text related to date/time on the scoreboard that I just couldn't find, maybe someone better with Unity can help with this. 

I did a quick bug check but I'm not 100% sure everything is fine, if there is an issue just let me know and I'll fix it. 

Enjoy!
