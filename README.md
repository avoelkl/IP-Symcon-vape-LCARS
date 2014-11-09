IP-Symcon-vape-LCARS
===============
LCARS-Skin for IP-Symcon WebFront in different colours
* Skin: black/orange (standard)
* Skin: blue (see info on switch to blue skin below)
* based on LCARS-Framework

Screenshot:
http://anna.vape.net/ip-symcon/lcars-skin/

## LCARS-Framework:
jquery plugin for star-trek style LCARS interface, fork of existing project

see:
* https://github.com/ryepup/jquery.lcars
* http://www.prolenet.org/LCARS/index.html

### LCARS-Color color palettes
http://www.colorhunter.com/tag/lcars/1

Features
-------------
Supports IP-Symcon Library modules:
- IPSCam

Compatibility
-------------
LCARS Skin for IP-Symcon was developed and tested with the following version:
- IP-Symcon 3.10
- Minimum required resolution: 1024x768

Browsers
-------------
LCARS Skin for IP-Symcon was developed and tested with the following browsers:
- Internet Explorer 11 (Windows 8)
- Mozilla Firefox 29.0.1 (Windows 7)
- Chrome 35 (Windows 7)

Installation Instructions
-------------------------

## IP-Symcon < 3.2:
1. Open http://your-webfront-url:webfront-port/user/skins
2. Enter GitHub URL: https://github.com/avoelkl/IP-Symcon-vape-LCARS
3. Install skin!

## IP-Symcon 3.2
1. Open IP-Symcon Managment Console
2. Open your instance (path in DE: "Objektbaum > Logische Baumansicht > Konfigurator Instanzen")
3. Go to configuration > view (2nd tab) (path in DE: "Konfiguration > Darstellung")
4. Click button "configure" ("Konfigurieren")
5. Click add and enter this URL: https://github.com/avoelkl/IP-Symcon-vape-LCARS

Update Instructions
-------------------------
If you already have the IP-Symcon-vape-LCARS theme installed (with Git), you can update it the following way:

1. Go to your IP-Symcon folder: for ex. C:\IP-Symcon\webfront\user\skins\IP-Symcon-vape-LCARS
2. Open Git Bash (right click in the explorer windows, select "Git Bash" from menu)
3. Pull the latest changes with Git: "git pull" (without quotes)
4. The update including the branch with the new blue skin is downloaded
5. Exit console

Switch to blue skin
-------------------------
Similar to the update process, you can switch to the blue colour skin:

1. Go to your IP-Symcon folder: for ex. C:\IP-Symcon\webfront\user\skins\IP-Symcon-vape-LCARS
2. Open Git Bash (right click in the explorer windows, select "Git Bash" from menu)
3. Checkout the blue skin branch: "git checkout skin_blue" (without quotes)
4. The branch is now changed to the blue skin
5. Exit console

You might want to adapt your on/off and info colours a bit so that it looks nicer.
Change the red colour from RGB 255/0/0 to 170/0/0.
Change the green colour from RGB 255/0/0 to 0/170/0.

Developer
---------
* Anna Völkl (@rescueAnn)
* [http://www.vape.net](http://www.vape.net)
* [@rescueAnn](https://twitter.com/rescueAnn)

Copyright
---------
(c) 2014 Anna Völkl
