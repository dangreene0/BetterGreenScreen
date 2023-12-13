# Better Green Screen
v1.2 12/12/23
This mod was created by Wiethoofd and is maintained by Sour Dani.

Extract or move the **BetterGreenScreen** folder from this zip to your `tf/custom` folder.

A tool HUD that offers a larger green screen, prevents models from spinning, with a slimmed down UI.

[Full guide available on Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=2224490198)

## Files in this mod

`resource\ui\econ\inspectionpanel.res` 
- This file creates the dynamic and larger greenscreen.
    - If you have a mod that already changes this file this mod may take priority.)

`cfg\valve.rc`
- Contains `tf_item_inspect_model_auto_spin 0`
    - This console command prevents the weapon from spinning.

`info.vdf`
- This file loads the HUD.

## FAQ/Info
**Enable spinning animation**
- If you wish to turn the war paint spin animation on, set `tf_item_inspect_model_auto_spin` to `1` in console.

**Change greenscreen color**
- If you wish to change the color of the greenscreen, go to the mod folder, navigate to `resource/ui/econ/InspectionPanel.res` and open it in any text editor.
- Look for `"bgcolor_override" "0 255 0 255"` on line 21, and change those RGBA values accordingly.
- Save the file and launch Team Fortress 2 to enjoy your new background color.

**Enable zooming**
- Navigate to `resource/ui/econ/InspectionPanel.res` on line 153, and change `"allow_manip"` from `"0"` to `"1"`

---
Thanks for downloading! Enjoy!

