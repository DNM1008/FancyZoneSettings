# FancyZoneSettings
My FancyZoneSettings.json file

## Installation

As of right now, you can't just download this file and then replace this file into your FancyZone setting folder to get the custom layout that I have. This is intended for **1080p displays only**. If you want to try my layout, you will need to do the following:
* Disable PowerToys (this is very important)
* Look in the <code>"custom-zone-sets" </code>
* Select and Copy the section <code>"zones"</code>
* Open your FancyZone editor, normally <code>Win+`</code>
* Create a new layout, name it to whatever you like, but set the type to Canvas (So that zones can be placed over lapping each other), make a couple of zones so that (you will delete these with your custom zones later so don't worry, this is only to make sure that the layout is created correctly)
* Go to %LOCALAPPDATA%\Microsoft\PowerToys\FancyZones, there you should find a file called <code>zones-settings.json</code>, open (edit) it with your preferred text editor
* Go down to <code>"custom-zone-sets"</code>, then look for <code>"zones"</code> (should be a couple of lines below if this is your only custom layout)
* Select the zones that you have created and paste the zones you copied (replace the dummy zones that you have created with the ones that you want)
* Save the file then run PowerToys
* Open the FancyZone editor, then choose the layout that you have edited on the monitor(s) that you want
* That should do it

## Recommendations

* You might want to enable Override Windows Snap shortcut, then chose Win+Up/Down/Left/Right to move windows based on relative positions, since we have a lot of zones, moving through all of them to get to the layout that you want is a pain
* If you have multiple monitors, enable Move windows between zones a cross all monitors

## Zone Layout:

There are 18 zones, each has a 6px padding between themselves and the edge of the monitor:
* There is 1 large zone that spreads to the edges of the display area (barring the 6px padding)
* There are 2 zones that separate the display area vertically
* There are 2 zones that separate the display area horizontally
* There are 4 zones that separate the display area into a quadron of equal-sized zones
* There are 3 zones that separate the display area into 3 collumns
* There are 2 zones that take up 2/3 of the display area horizontally all all of it vertically (2/3 of the first zone)
* There are 4 zones that take up 2/3 of the display area horizontally and half of it vertically (half the height of the zones right above)

