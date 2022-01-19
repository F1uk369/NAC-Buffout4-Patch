# NAC Buffout 4 Patch
This mod patch lets NAC work with Buffout 4.

I will rarely update the .esm here, so here is how to do it yourself:

1) Download [XEdit/Fallout4Edit](https://www.nexusmods.com/fallout4/mods/2737?tab=description)
2) Open Fallout4Edit
3) Make sure all modules are selected then press OK. Leave this for a few minutes to load, and DO NOT continue until its loaded.
4) If it asks for Fallout4Patch modgroups (Only if you have Unofficial Fallout 4 patch installed) you can deselect the checkbox for it and press OK.
5) In the top left, enter 000D3C85 in the FormID and press enter, this will take you to the value VATSApplyCriticalMod under Image Space adapter.
6) Scroll down in the right menu until you find Saturation Mult (Saturation Multiplier)
7) In the NAC.esm column the Saturation Mult value should be 0. Double click on the entry, and change this to 1 (or greater), there might be a warning, just wait, and proceed.
8) Hold Control(CTRL) and press S to save.
9) Exit FO4Edit
10) If everything has been done correctly, your NAC mod file should be patched, and now compatible with Buffout 4.
