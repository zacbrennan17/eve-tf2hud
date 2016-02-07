# How to install #
Inside the archive you'll find a folder called **"eve hud"**. Move it to the following location:

  * Windows:
```xml

~\Steam\steamapps\common\Team Fortress 2\tf\custom```

  * Mac:
```xml

~/Library/Application Support/Steam/SteamApps/common/Team Fortress 2/tf/custom```

  * Linux:
```xml

~/.local/share/Steam/SteamApps/common/Team Fortress 2/tf/custom```

# How to uninstall #
Remove the "eve hud" folder from your "custom" folder.

# Overrides #
There is one more folder called "overrides". It contains alternative version of files that will allow you to change various components.

Each override contains **"resource"** and/or **"scripts"** folders.

Copy them to the **"eve hud"** folder.

  * how to change a number or a size of kill notifications:
    1. Open tf\scripts\hudlayout.res.
    1. Search for "##Kill Notifications##".
    1. Change following values to your liking:
    * "MaxDeathNotices" – maximum number of notifications visible at the same time
    * "LineHeight" – height/size of each notification

  * 4:3 fixes – this should fix all errors in a 4:3 aspect ratio
  * alternative damage colors and sizes – this will change color/size/location of damage values:
    * left side/right side
      * big/standard
        * pink as hell
        * red
        * turquoise
        * yellow
  * alternative Pip-Boy screens – this will change a color of the Pip-Boy's build menus
    * amber
    * blue
    * disabled – use standard build menus
  * bigger chat font - increases the font size of chat messages
  * centered ubercharge – ubercharge meter will be placed under your crosshair
  * health and ammo:
    * bigger fonts - increases the font size of your health and ammo
    * borders – adds a border around player's current health (yes, I made it look like that)
    * no animation – removes an animation when low on health or ammo
  * left align main menu – aligns buttons to the left, for frequent console users
  * main menu shortcuts - you can enable 6 custom buttons that will instantly connect you to selected servers, install the override and add the following commands to your autoexec.cfg:
    * alias ServerShortcut1 "connect SERVERIP"
    * alias ServerShortcut2 "connect SERVERIP"
    * ...
  * no class avatars - removes your class' avatar near your health
  * no last damage done – you won't see last damage done above your weapon
  * prophunt, Saxton hale fix – fixes a missing time panel in the prophunt/Saxton Hale game mode
  * scoreboards:
    * 24p scoreboard (no minmode) – disables an alternative scoreboard in minmode
    * 32p scoreboard (no minmode) – allows you to see up to 32 players on the scoreboard and disables an alternative scoreboard in minmode
    * 32p scoreboard (with minmode) – allows you to see up to 32 players on the scoreboard and you keep an alternative version in minmode