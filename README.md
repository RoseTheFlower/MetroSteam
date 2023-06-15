# Metro skin for Steam chat and friends UI

This skin for the new chat and friends UI was created after Valve made it problematic to revert to the old-style windows.
My quest was to make the new windows look as close as possible to those of [the original Metro skin](https://steamcommunity.com/groups/metroforsteam).

## Installation
1. Go to your Steam\steamui\css\ folder and ensure there is no library.css file.
1. Save the [friends.custom.css file](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/friends.custom.css) to your PC and put in your Steam\steamui\ folder.
1. [Download](https://github.com/PhantomGamers/SFP/releases) the latest version of SFP to modify Steam.
1. Launch the patcher and wait for it to apply the changes.
1. Restart Steam if necessary.

## Help and options
The [wiki](../../wiki) answers some of the most asked questions and contains a few extras.

## Uninstallation
### Windows
* Ensure that Steam and the patcher tool are closed, then remove the %LOCALAPPDATA%\Steam\htmlcache\Cache\ folder.
* For purity, remove the Steam\clientui\css\ folder (and Steam\steamui\css\ if using the library skin) inside your Steam installation folder.

## Credits
* [PhantomGamers](https://github.com/PhantomGamers) for creating the tool that allows to apply skins, and for tips on managing the randomized class names.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the new chat, which I initially used as a template.
* [Shiina](https://github.com/AikoMidori) for helping me find a few elements and for making me realize where to look.
* [Ruben7173](https://github.com/Ruben7173/) for pointing at an element and for inspiring me to implement custom scroll bar buttons.
* [Laser](https://github.com/LaserFlash) for an idea on tackling randomized class names.
