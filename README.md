Feel free to add or remove mods as you like, this is simply **my view** on how the game can be even better and give me even more fun.

Script Extender not auto-updating sometimes is a known issue, where the recommended is to go delete the previous versions and then launch the game again and it should be fixed. You can go to C:\Users\USER\AppData\Local\BG3ScriptExtender\ScriptExtender and delete everything that exists in there launch the game again and should give you the current version.

***

# Some Features.:

- WASD movement;
- Party Limit Begone;
- No Weight Limit;
- Spells;
- Outfits (Highly suggest to use the camp version of them for balance purposes);
- Subclasses (Optionals);
- Races (Optionals);
- Heads and Hairs;
- Various Frameworks in case you want to add more mods to the collection;
- [Pavelk](https://www.nexusmods.com/users/703937)'s QoL mods.

***

**Requirements**

- Ability to Read;
- [Lslib/Divine Tools](https://github.com/Norbyte/lslib);
- Script Extender (Achievements),  WASD, Native Loader and Native Camera need to be set on mod type to "Engine Injector".

<details><summary>Load Order</summary>
Load order is important and is the cause of most problems. Important points:

![Load Order Concept](https://i.imgur.com/bAGadzL.png)My [Load Order](https://www.nexusmods.com/baldursgate3/mods/4009/) - Put the .lsx file in C:\Users{USERNAME}\AppData\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public or just import it in Vortex. There is also a .json file in case you are using BG3MM.
</details>

<details><summary>Rules & Special Information</summary>
- On Graphical Settings, the option "Animation Level of Detail" needs to be set to "High" otherwise you will have issues with heads/hairs.
- [Better Hotbar 2](https://www.nexusmods.com/baldursgate3/mods/2417), [Slightly Better Trade Menu](https://www.nexusmods.com/baldursgate3/mods/1893), [Slightly Better Topbar](https://www.nexusmods.com/baldursgate3/mods/2790), [Dynamic Sidebar](https://www.nexusmods.com/baldursgate3/mods/2668), [Better Hints and New Loading Screens](https://www.nexusmods.com/baldursgate3/mods/816) are the 16:9 aspect ratio version. You can manually download another version if your screen is not 16:9 aspect ratio, but it may or may not disable co-op if not using the same as friends (not tested, since I use the 16:9).
- If Prompted on "Manage Rules" Load Detailed Lae'zel **After** Better Gith Body and Smooth Gith Body and Load Better Gith Body **after** Smooth Gith Body (check media). You need the three mods, otherwise you will have neck seems.
- All of [Pavelk](https://www.nexusmods.com/users/703937) (Caites)'s mods were selected to Replacers (Mod Type on Vortex). Same happened for [Trips' Old Shader Pack](https://www.nexusmods.com/baldursgate3/mods/4752), [Distinctive Dyes](https://www.nexusmods.com/baldursgate3/mods/4003), [Plus UI](https://www.nexusmods.com/baldursgate3/mods/4273) and [Elves Sit to Trance](https://www.nexusmods.com/baldursgate3/mods/5060).
- All texture mods (they start with a "Generated" folder) were turned into Loose Files (Mod Type on Vortex).
- Some mods are *inactive* after importing the load order on BG3MM, this is intended (those are the same mods that were made replacers on mod type). Check the media to see which mods I have *inactive*.
- [Camp Event Notifications](https://www.nexusmods.com/baldursgate3/mods/1879) makes an exclamation point appear on the top of your character head, meaning that you have long rest events queued up.
</details>

<details><summary>Updating the collection</summary>
- Everytime you update/add/remove mods, you should press "Purge" and then "Deploy" and apply the newest load order.
- Another tip for Updating the Collection, go to profiles, create a new profile. Change to that profile. Add the Collection again to Vortex and then after this new adding is done, you can remove the previous collection without selecting anything (don't remove the mods or archives, otherwise you will have to download everything again).
- After an Update if you find missing textures on bodies (or they turn black, it is more common amongst users to happen to Shadowheart) remove all of the shader mods, auto-reinstall the missing collection files, purge (accept any external changes reported), redeploy, import the load order lsx file. Great tip by [oranhayes](https://www.nexusmods.com/users/942833). The shader mods are the following.:
- [Trips' Old Shader Pack](https://www.nexusmods.com/baldursgate3/mods/4752);
- [Player and NPC - Old Shaders](https://www.nexusmods.com/baldursgate3/mods/4821);
- [Companions - Old Shaders](https://www.nexusmods.com/baldursgate3/mods/4774).
</details>

<details><summary>Additional Information</summary>
- Make sure everything is installed in the same drive ! e.g. Game, mods and mod manager all installed on (C:) (also not recommended to use an external driver).
- If asked by Vortex if you wish to install as replacer, please do so.
- If your Script Extender is having issues (not working or not updating) you can go to C:\Users\USER\AppData\Local\BG3ScriptExtender\ScriptExtender and delete everything that exists in there launch the game again and should give you the current version.
- After revision 235 if you are using bg3mm and import the .json, you will see a bunch of mods on the inactive side (left side), this is also intented and leave them there. Don't worry, the mods are working properly.
- Go to your Vortex Staging Folder, type "info" on search bar and you will see a bunch of "info.json" files, select them all and delete them, this will make your Vortex a bit faster and will resolve some conflicts.
- This collection is not compatible with any mods that use textures from Patch #5 onwards, this happens due to having the Shader mods, which makes the textures the previous ones (before Patch #5) if you want to use mods that have textures from current game version, you can delete/disable the Shader mods, take in mind that the Gith Textures or Orc Textures will no longer work.
- **Party Limit Begone.:** \
  **Camp sleeping bug**: Use one of the awake companions and talk to Lae'zel or reduce your party size to 4 before resting.\
  **Grymforge Map transition:** Reduce your party size to 4 members before sailing with the boat. If you already used it and your characters are stuck, dismiss the ones that are with you and sail back and forth to unstuck the rest.\
  Note: After using the boat a timed quest is triggered and going to camp will progess it.
- If your game is too difficult, you can disable the [Combat Extender](https://www.nexusmods.com/baldursgate3/mods/5207).
- The exlamation point on top of your character head is due to [Camp Event Notifications](https://www.nexusmods.com/baldursgate3/mods/1879), basically tells you if you long rest now a scene will play out and if the exlamation point persists, means that you have more scenes on long rest.
- The mod that shows character approval on dialogue choices is called [OIO - Overexplained Interaction Options](https://www.nexusmods.com/baldursgate3/mods/2631), tells you when you win or lose approval from companions and also tells you when you can start a romance or end it with certain dialogue choices.
</details>

<details><summary>Multiplayer</summary>
Multiplayer: **IT DOES WORK!** I only play BG3 Co-Op, I made the Collection to play with my friend initially. But if for some reason you can't connect to your friends or your friends to you, you all have to make sure everything is okay, needs to be the exact same. Same mod versions, same load order, same mods, same game version, SE version, some mods need to be set engine injector. Check game files, otherwise could break it also. Don't have any mods in the right side of BG3MM (also known as inactive, but like BG3MM mentions, those mods are not totally inactive).\
[DuchessDesigns](https://www.nexusmods.com/users/6850726): Be sure to update the dependencies for the QoL collection in your load order (if you don't see a red structure tree, click the gear icon in the top right and select dependencies) and scroll down until you see the mod name in red and click the '-' button to the right and deploy!
</details>

***

[![](https://storage.ko-fi.com/cdn/kofi2.png)](https://ko-fi.com/saigofu)
