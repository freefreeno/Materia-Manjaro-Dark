 
## Materia-Manjaro-Dark

Materia Manjaro Dark - This is a port of the popular [Materia KDE](https://github.com/PapirusDevelopmentTeam/materia-kde) for Plasma 5 desktop.

In this repository you'll find:

- Folder icons
- Konsole Color Scheme
- Three Plasma Color Schemes
- Four Plasma Desktop Themes
- Plasma Look-and-Feel Settings
- Three Materia Manjaro Dark GTK's made specifically for KDE.
- Three Aurorae themes

## Recommendations

- First of all there is four plasma themes so try them all to see which one you prefer.

- Install Materia Manjaro Dark icons for better looking desktop.Also I have a full icon set that match this theme that can be found here: Please rate them if you like.

https://www.pling.com/p/1328981

- Set tree menu view for systemsettings

- On systemsettings set **Noto Sans** font for title, menu and toolbar

- For better looking use toolbar icons without text with 16px size (for Papirus themes)

- For Blur enable translucency and blur effects on KDE sytemsettings. Set value 4 to 6 for blur and 2 for noise strengths on blur effect settings. This is only my suggestion so do it how you like.

- Recommended software for better experience with Materia Blur: Dolphin, Ark, Kate,Falkon, Konsole

- If you don't like my aurorae themes try the theme with Breeze and set shadows to medium or large at 75% and at color #000000

## Hacks for small screen resolution

- Install widgets [Active Window Control](https://github.com/kotelnik/plasma-applet-active-window-control) & [Application Menu](https://cgit.kde.org/plasma-workspace.git/tree/applets/appmenu) and move to panel
- Disable window buttons & titlebar on decoration:

open rc-file on aurorae theme and set:
```
ButtonHeight=0
ButtonWidth=0
TitleHeight=0
TitleEdgeTop=0
```
- Use [GTK3-noCSD](https://github.com/PCMan/gtk3-nocsd) script 

## Known issues

- On some propietary video drivers Aurorae have wrong rendering by default with Materia theme. For fix that use this config on ~/.Xresources:

```
Xft.dpi:       96
Xft.antialias: true
Xft.hinting:   true
Xft.autohint:  false
Xft.hintstyle: hintslight
Xft.lcdfilter: lcddefault
Xft.rgba:      rgb 
```
## Theme download locations. If you would like to help me out please download the theme from these locations and not from here. This way you can rate them good or bad and at the same time it supports the project. Downloading from here does not support me at all and I am not required to put anything but the Plasma theme on here but I always add it all.Thanks

The GTK themes are here:
https://www.pling.com/p/1306506

The Konsole theme is here:
https://www.pling.com/p/1322077

The look and feel theme is here:
https://www.pling.com/p/1309269

The folder icons are here:
https://www.pling.com/p/1313094

The Aurorae themes are here:
https://www.pling.com/p/1309265

The Plasma themes are here:
https://www.pling.com/p/1306505

The Plasma color schemes are here:
https://www.pling.com/p/1306504

## Donate

If you like my project, you can donate at:

<span class="paypal"><a href="https://www.paypal.me/freefreeno" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>


## License

GNU GPL v3

## License for icons

Creative Commons Attribution-NonCommercial-ShareAlike

## Credits go to: Alexey Varfolomeev - https://github.com/PapirusDevelopmentTeam/materia-kde for the orginal Materia-dark theme and many thanks go to him for making such an awesome theme that inspired me to create.

## Wallpaper for theme: Charlie Henson at:
- https://store.kde.org/p/1296893
- https://store.kde.org/p/1319754

## New gradient Aurorae theme is made from the Breezemite Aurorae theme so many thanks goes to them. Original is here https://store.kde.org/p/1169286                                                            https://github.com/andreyorst/Breezemite
