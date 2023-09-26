# Better Green Screen
v1.0 9/9/20
This mod was created by Wiethoofd.
Distributed by Sour Dani.

Extract or move the **BetterGreenScreen** folder from this zip to your `tf/custom` folder.

It makes the background behind weapons and skins larger and green, prevents them from spinning, as well as a revised slimmed down UI.

(Full guide available on Steam)[https://steamcommunity.com/sharedfiles/filedetails/?id=2224490198]

## Files in this mod

`resource\ui\econ\inspectionpanel.res` 
- This file creates the dynamic and larger greenscreen.
(If you have a mod that already changes this file this mod may take priority.)

`cfg\bettergreenscreen.cfg`
- Contains `tf_item_inspect_model_auto_spin 0`
    - This console command prevents the weapon from spinning.

`cfg\valve.rc`
- Tells the game to run `bettergreenscreen.cfg` on startup.

`info.vdf`
- This file loads the HUD.

## Info
**Enable spinning animation**
- If you wish to turn the war paint spin animation on, set `tf_item_inspect_model_auto_spin` to `1` in console.

**Change greenscreen color**
- If you wish to change the color of the greenscreen, go to the mod folder, navigate to `resource/ui/econ/InspectionPanel.res` and open it in any text editor.
- Look for `"bgcolor_override" "0 255 0 255"` on line 21, and change those RGBA values accordingly.
- Save the file and launch Team Fortress 2 to enjoy your new background color.

---
Thanks for downloading! Enjoy!

