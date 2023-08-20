# Metro skin for Steam

This skin for the new UI framework was created after Valve made it problematic to revert to the old-style windows and subsequently removed support for user-made themes.
My quest was to make the windows look as close as possible to those of [the original Metro skin](https://steamcommunity.com/groups/metroforsteam).

## Applying the skin
### Using SFP
<details>
<summary><strong>Breakage prevention for returning skin users (clickable)</strong></summary>
1. Close Steam.<br>
2. Navigate to its folder, back up and remove the clientui, skins, and steamui\css folders.
</details>

1. [Download the skin archive](/../../archive/refs/heads/master.zip).
1. Extract the archive to **Steam\steamui\skins** (create the skins folder if doing this for the first time).
   - If you like, rename the MetroSteam-master folder to `Metro by Rose`.
1. [Download](https://github.com/PhantomGamers/SFP/releases) the latest version of SFP to modify Steam.
1. Run the tool and select the skin under *Steam skin* in its settings.
1. In SFP, click on Start Injection unless already done.

#### Extra options
- If you'd like to customize the colors, decals and more, also download [custom.css](https://raw.githubusercontent.com/RoseTheFlower/newsteamchat/master/custom.css) and put in the same folder as the rest of the files, then edit this file in any text editor as desired.
- Check out the [wiki](../../wiki) to enable automatic skin updates or learn more about customizing the skin.

### Using CSSLoader
1. Download [CSSLoader](https://deckthemes.com/download/windows).
1. Go to the Store tab.
1. Search for Metro and install **Metro by Rose**.
* Note that the skin version available via the CSSLoader store may not have the latest updates of this repo.

## Credits
* [Dom](https://github.com/minischetti) for creating the original Metro skin, which has been the reference point for many parts of my remake.
* [PhantomGamers](https://github.com/PhantomGamers) for creating the tool that allows to apply skins, and for tips on managing the randomized class names.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the chat and friends windows, which I initially used as a template.
* [Sims](https://github.com/suchmememanyskill) for ideas and code examples related to animating the Steam menu and to the dynamic placement of the repositioned bottom bar buttons.
* [Ruben7173](https://github.com/Ruben7173/) for pointing at an element and for inspiring me to implement custom scroll bar buttons.
* [Shiina](https://github.com/AikoMidori) for helping me find a few elements and realize where to look.
* [Laser](https://github.com/LaserFlash) for an idea on tackling randomized class names.
