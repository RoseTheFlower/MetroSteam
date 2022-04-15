# Metro skin for Steam chat and friends UI

This skin for the new chat and friends UI was created after Valve made it problematic to revert to the old-style windows.
My quest was to make the new windows look as close as possible to those of [the original Metro skin](https://steamcommunity.com/groups/metroforsteam).

## Installation
### Windows
1. Save the [friends.custom.css file](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/friends.custom.css) to your PC and put in your Steam\clientui\ folder.
1. [Download](https://github.com/PhantomGamers/SteamFriendsPatcher/releases) the latest patcher or its [newer but more experimental version](https://github.com/PhantomGamers/SFP/releases) to allow for customization.
1. Launch the patcher and wait for it to apply the changes.
1. Restart Steam if necessary.
### Linux and Mac
1. Copy and add the [friends.custom.css code](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/friends.custom.css) to Steam/skins/[skin name]/resource/webkit.css
1. Search the file contents for *Linux* or *Mac* in any text editor.
1. Remove sections as instructed within the code.

## Help and options
The [wiki](../../wiki) answers some of the most asked questions and contains a few extras.

## Uninstallation
### Windows
* Use the dedicated patcher UI button to clear the cache.
* Alternatively, ensure that Steam and the patcher tool are closed, then remove the %LOCALAPPDATA%\Steam\htmlcache\Cache\ folder.
  - For purity, remove the Steam\clientui\css\ folder (and Steam\steamui\css\ if using a library skin) inside your Steam installation folder.

## Credits
* [PhantomGamers](https://github.com/PhantomGamers) for creating the tool that makes customization possible.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the new chat, which I initially used as a template.
* [Shiina](https://github.com/AikoMidori) for helping me find a few elements and for making me realize where to look.
* [Ruben7173](https://github.com/Ruben7173/) for pointing at an element and for inspiring me to implement custom scroll bar buttons.
