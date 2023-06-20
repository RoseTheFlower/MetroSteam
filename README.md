# Metro skin for Steam

This skin for the new UI framework was created after Valve made it problematic to revert to the old-style windows and subsequently removed support for user-made themes.
My quest was to make the windows look as close as possible to those of [the original Metro skin](https://steamcommunity.com/groups/metroforsteam).

## Installation
1. Go to your Steam\steamui\css\ folder and ensure there is no library.css file.
1. Save the [friends and chat skin](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/friends.custom.css) to your PC and put in your Steam\steamui\ folder.
1. Save the [library skin](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/libraryroot.custom.css) to your PC and put in your Steam\steamui\ folder.
1. [Download](https://github.com/PhantomGamers/SFP/releases) the latest version of SFP to modify Steam.
1. Run the tool alongside Steam and wait for it to apply the changes.
1. Restart Steam if necessary.

## Help and options
The [wiki](../../wiki) answers some of the most asked questions and contains a few extras.

## Uninstallation
* Ensure that Steam and the patcher tool are closed, then remove the %LOCALAPPDATA%\Steam\htmlcache\Cache\ folder.
* For purity, remove the Steam\clientui\css\ and Steam\steamui\css\ folders inside your Steam installation folder.

## Credits
* [PhantomGamers](https://github.com/PhantomGamers) for creating the tool that allows to apply skins, and for tips on managing the randomized class names.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the chat and friends windows, which I initially used as a template.
* [Sims](https://github.com/suchmememanyskill) for ideas and code examples related to animating the Steam menu and the dynamic placement of bottom bar buttons.
* [Shiina](https://github.com/AikoMidori) for helping me find a few elements and for making me realize where to look.
* [Laser](https://github.com/LaserFlash) for an idea on tackling randomized class names.
