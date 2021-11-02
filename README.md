# MaiaTransparent-plasma-theme
A fully transparent Plasma KDE desktop theme based on Manjaro's Maia theme.

This is a fully transparent theme for fans of extreme transparency for usage with dark, homogeneous wallpapers. In other cases, it won't work too well. It is basically slightly modified Manjaro's Maia Desktop Theme under GPL 3 license (https://gitlab.manjaro.org/artwork/themes/maia/blob/b61312cc80cb9d12b0d8a55b3e61668eb6b77d2d/LICENSE), but with the completely transparent panel and menus (except dashboard menu, which doesn't follow theme background settings). Version 4 contains media icon fix for Plasma 5.13 and higher.

To install:
- unpack
- move/copy folder to: ~/.local/share/plasma/desktoptheme or /usr/share/plasma/desktoptheme/

Note: When first applying this theme it's quite common that the panel border will be displayed as a temporary remnant. It will go away after rebooting plasmashell process or plasma session. Also, don't forget to turn off the blur effect in desktop effects!

Release Notes:

Version: 4.2

 Update metadata.desktop

In metadata.desktop removed a duplicated line: "X-KDE-PluginInfo-Category=Plasma Theme" that interfered with the downloader.

Version: 4.1

- updated metadata.desktop file
- converted all svgz files from 90 to 96 DPI

Version: 4.0

- fixed media icon for Plasma 5.13+

Version: 3.1

- changes in the readme file 
- small name change in metadata file for better name presentation

Version: 3.0

I. Icons on task panel now show 7 possible status indicators:

1) Program window is not turned off - no indication on a panel.
2) Program window is opening - launching animation.
3) Program window is opened and active/on top - icon has emerald,  translucent, square background.
4) Program windows is opened but inactive/in background (behind other windows) - icon has gray,  translucent, square background.
5) Program windows is minimized - icon has horizontal stripe underneath.
6) Program has two or more windows opened - icon has additional, round indication +2.
7) File or directory is being copied or moved - animation of progress in a form of stronger, emerald progress bar on a icon of a used program (like Dolphin, Krusader, etc.)

II. Fixed lack of specified folder name. 

III. Name of the folder as well as data in metadata.desktop file where improved and updated.

Version 2.0

I. Desktop panel now have no borders.

Version 1.0

I. First release of transparent desktop panel with white borders.
