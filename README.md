# Metro skin for Steam

This skin for the new UI framework was created after Valve made it problematic to revert to the old-style windows and subsequently removed support for user-made themes.
My quest was to make the windows look as close as possible to those of [the original Metro skin](https://steamcommunity.com/groups/metroforsteam).
<br><br>
<a href='https://ko-fi.com/J3J3U4PJ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi5.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## Applying the skin
### Using SFP
<details>
<summary><strong>Breakage prevention for returning skin users (clickable)</strong></summary>
1. Close Steam.<br>
2. Navigate to its folder, back up and remove the clientui, skins, and steamui\css folders.
<hr>
</details>

1. [Download the skin archive](/../../archive/refs/heads/master.zip).
1. Extract the archive to **Steam\steamui\skins** (create the skins folder if doing this for the first time).
   - If you like, rename the MetroSteam-master folder to `Metro by Rose`.
1. [Download the latest version of SFP](https://github.com/PhantomGamers/SFP/releases) to modify Steam.
1. Run the tool and select the skin under *Steam skin* in its settings.
1. In SFP, click on Start Injection unless already done.

#### Extra options
- If you'd like to customize the colors, decals and more, also download [custom.css](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/custom.css) and put in the same folder as the rest of the files, then edit this file in any text editor as desired.
- Check out the [wiki](../../wiki) to enable automatic skin updates or learn more about customizing the skin.

### Using CSSLoader
1. [Download CSSLoader](https://deckthemes.com/download/windows).
1. Go to the Store tab.
1. Search for *Metro* and install **Metro by Rose**.
* Note that the skin version available via the CSSLoader store may not have the most recent updates of this repo, though you can manually override it with the [latest files](/../../archive/refs/heads/master.zip).

### Using Millennium
Refer to the instructions provided by the patcher developer on its repository pages to access its themes, which include **Metro by Rose**.

Installing manually is also an option:
1. Follow the SFP steps above to extract the skin files to the Steam folder.
1. [Download the Millennium patcher](https://github.com/ShadowMonster99/millennium-steam-patcher/releases) and install it.
1. Launch Steam and select the skin in Settings->Interface.

## Credits
* [Dom](https://github.com/minischetti) for creating the original Metro skin, which has been the reference point for many parts of my remake.
* [PhantomGamers](https://github.com/PhantomGamers) for creating the first tool to alow skinning, SFP.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the chat and friends windows, which I used as an early template.
* [Sims](https://github.com/suchmememanyskill) for ideas and code examples related to animating the Steam menu, to the dynamic placement of the repositioned bottom bar buttons, and to the context menu borders.
* [Ruben7173](https://github.com/Ruben7173/) for pointing at an element and for inspiring me to implement custom scroll bar buttons.
* [Shiina](https://github.com/AikoMidori) for helping me find a few elements and realize where to look.
* [Shadow](https://github.com/ShadowMonster99) for the [ClassMapper](https://github.com/SteamClientHomebrew/ClassMapper) that allowed to convert to the randomized class names.
* [Contributors](../../graphs/contributors) to this repository.
