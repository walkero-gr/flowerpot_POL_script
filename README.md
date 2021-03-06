# flowerpot_POL_script
Flowerpot is a package for installing AmigaOS 4 on Windows and MacOS, using an emulator. The procedure to do that is really straight forward with FlowerPot. With this script you can install the Windows version under Linux, using WINE and PlayOnLinux.

Installation Procedure
----------------------
 1. Download the script ***POL_install_FlowerPot*** wherever you want
 3. When you start PlayOnLinux go to the menu "Tools > Run a local script". Choose the ***POL_install_FlowerPot*** file.
 4. Follow the instructions. You will see a message about the signature of the script, that it is not valid. Ignore and continue the installation.
 5. Follow and approve every step

**CAUTION:** This creates a wine prefix named FlowerPot. If one exists it will ask you what to do and if you want to overwrite the old one. If this is something you do not want to lose, then cancel the installation and change the following line with a different name, so that there is no conflict.

```
PREFIX="FlowerPot"
```

The script may ask you to update itself, if there is a new version online and you are running an older one.

Prerequisites
-------------
* You need to have installed at your system the [PlayOnLinux v4.2.10](https://www.playonlinux.com/en/download.html)
* [AmigaOS 4.1 FE for Classic Amiga](https://www.amikit.amiga.sk/os4) 

Credits
-------
* Flower Pot © 2017 by Ján Zahurančík [www.amikit.amiga.sk](http://www.amikit.amiga.sk)
* Quick Launcher by Rex Schilasky
* Skin by Kenneth E. Lester, Jr. [www.five-star.com](http://www.five-star.com)
* WinUAE emulator engine by Toni Wilen [www.winuae.net](http://www.winuae.net)

