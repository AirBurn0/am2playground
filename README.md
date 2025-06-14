<p align="center">
    <img width="360" src="https://i.imgur.com/vAnOOaI.png" alt="AM2PGLogo">
</p>

# AM2PlayGround

[![Code license (CC BY-NC-ND 3.0)](https://img.shields.io/badge/License-CC%20BY--NC--ND%203.0-blue.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-nd/3.0)
[![CurseForge](https://cf.way2muchnoise.eu/title/am2playground.svg)](https://www.curseforge.com/minecraft/mc-mods/am2playground)
[![Modrinth](https://img.shields.io/modrinth/dt/am2playground?label=Modrinth&logo=Modrinth&style=flat-square)](https://modrinth.com/mod/am2playground)

Public repository for AM2PlayGround (Ars Magica 2 1.7.10 addon) resources: localization, addon issues reports and suggestions

## What it is?

AM2PlayGround, or AM2PG for short, is a quick-made Ars Magica 2 Addon, as far as I know, fisrt of any among its own (Ima adding spell components, dude. New spell components!) (except [this](https://github.com/Mithion/APIDemoMod) thing; This is made along before I made my own, but as far as you can see - it has no use)

### Main and only goal of this addon:
* Make __AM2__ expirience nicer (more funny, arcane, long and less torture).

## What it does?
It adds new spell shapes, components, modifiers, some talents, rebalances mechanics (like Clarity - it was broken as hell, for sure. But don't worry, it's still can be used as a 0 mana cost exploit), adding new items and recipes, bring some compatability and integration with my other favorite mods and a lots of other stuff that I'm stupidly forget to mention there (or there was some purpose for it not to be mentioned 😉)

## Known AM2 forks compatibility status:

### Mithion forks-family
* ###  <b>[Ars Magica 2 by Mithion](https://github.com/Mithion/ArsMagica2)</b>
  Good-old original ~~bugs~~ mod.

  Only v1.4.0.009 (latest) is supported;
  
### TCLProject forks-family
* ###  <b>[Ars Magica 2.5 LTS by TCLProject](https://github.com/TCLProject/ArsMagica2-5)</b> 
  Most canonical sequel with some old bugs fixed and brand-new added.

  Only from v1.6.5 (corresponding AM2PG version is v0.11.0) to v1.6.7 (latest) is supported;

* ###  <b>[Ars Magica 2.5 LE by DrParadox7](https://github.com/DrParadox7/ArsMagica2)</b>
  Currently based on TCLProject fork. Used in the Lost Era Modpack (what?).

  v1.6.9-LE will be considered as TCLProject version and should work fine, but later versions [may not work](https://github.com/AirBurn0/am2playground/issues/30#issuecomment-2657529188).

* ###  <b>[Ars Magica 2.5 RE by RubilaxXxx](https://github.com/RubilaxXxx/ArsMagica2-5)</b>
  Based on DrParadox7 fork, but implements some fixes and reworks how Magic Resistance works. Also removes bosses damage softcap to make battles more (or less lmao) fair.

  v1.6.9-RE will be considered as TCLProject version and should work fine.

* ###  <b>[Ars Magica 2.5 BE by brandyyn](https://github.com/brandyyn/Voids-Rift/releases/tag/ArsMagica2.5)</b>
  Based on TCLProject fork, but implements some fixes and disables native way to fill Crystal Phylactery (for FPS improvements).

  v1.7-BE.FX will be considered as TCLProject version and should work fine, otherwise brandyyn will crash and I'll go fix that.

### ToCraft forks-family
* ###  <b>[Ars Magica 2 by ToCraft](https://github.com/ToCraft/ArsMagica2)</b> 
  Contains built-in integration with LotR mod, some new spell parts (shapes, components, modifiers), and some new config options.

  Only v1.4.1.001 is supported, for nevest versions see Ars Magica 2 by kutschkem;

* ###  <b>[Ars Magica 2 by kutschkem](https://github.com/kutschkem/ArsMagica2)</b>
  Adds all content from ToCraft's fork and [something](https://github.com/kutschkem/ArsMagica2/releases/tag/v1.4.1.002) else as well.

  Versions from v1.4.1.002 to v1.4.1.003 is supported;

## FAQ
### <b>Q</b>: Where is the source-code? Is the project not open-source?

  <b>A</b>: Someday I'll upload source code to this repository. Or maybe not. As for now, this project __IS NOT__ open source! You can still decompile the sources at your own risk (to see the code that even worse than in original AM2 repo) if you're interested, but not allowed to steal or make any changes to it.
### <b>Q</b>: With which mods there is an iteration?

  <b>A</b>: For now, it's Thaumcraft and Baubles (by Azanor), Thaumic Tinkerer (by Pixlepix), Forbidden Magic and Avaritia (by SpitefulFox), Blood Magic (by WayofTime), Botania (by Vazkii), Aether-Legacy (by The-Aether-Team), Traveller's Gear (by BluSunrize), Tinker's Construct (by mDiyo), Witchery (by Emoniph), and some other minor stuff. Some of compatabilities is more global, like Thaumcraft one, some - less, like Aether one.
### <b>Q</b>: Can you make an integration for X?

  <b>A</b>: As long as it's not an Alfheim, and mod is intresting enough - sure. There is one problem tho - if I haven't integrated with X yet, and didn't plan to, then I simply don't know about the existence of this mod, or about what specific content needs to be added so that playing with AM2 and X can be more fun.
### <b>Q</b>: I have a localization file/bug report/idea to suggest, what should I do?

  <b>A</b>:

  If it's localization file, fork this project, do some git magic, make pull request with localization file added.

  If it's bug report - make a new issue with detailed info provided: crash log, situation conditions (that I can actually reproduce bug by myself, debug and finally fix it) and some additional info like screenshots will not be superfluous.

  If it's idea suggestion - create a new issue with detailed information about what do you want me to add (what's it, how it must work, etc.), and why must I actually spent my time doing it instead of adding something else. Resources like models and textures if you wanted something complex is appreciated as well.
  
  If you are too young for github or your intentions cannot be carried out with it, contact me in a way that is accessible for you (I have some social networks but you must figure them out by yourself).
### <b>Q</b>: Can I use it on my server?

  <b>A</b>: Okay, listen here: at the bottom, is the license, and it clearly says that you cannot earn income with my addon, and also you cannot recompile its sources to suit your needs, and this means that <b>IF</b> you start a public server with some commercial targets or even donation function, only answer that I can give you is <b>NO</b>. But if you just open a local server to throw some Random Damage spell at faces of your friends - well, I won't know about it anyway.
### <b>Q</b>: Can I use it in my modpack?

  <b>A</b>: Yeah, feel free. Unless, of course, you are going to run it on a server with commercial purposes.
### <b>Q</b>: Are there any bugs?

  <b>A</b>: Yeah, lots of them, exactly like in any other mod, if not more. It's no secret that AM2 is buggy as hell, and in general... I'm fine with it.
  Most of the bugs like chrono-dispel or more funny ones like 42 prosperity spell, for me now it's more of a gameplay feature than anything else.
  Dupes with a book and other bugs that obviously kills all the interest in the game aren't, but what does not work well in AM2 - most likely does not work well in addon either, because of AM2 API and my <b>skill issue</b>.

  But btw, I fixed some of AM2 built-in bugs (you will never figure out which ones, for sure).
### <b>Q</b>: Will you port it on newer minecraft versions?

  <b>A</b>: To date, a relatively stable and canon version of AM2 exists only on 1.7.10. AM2 1.10.2 - not canon and WAAAAAY more bugged than AM2 on 1.7.10 version. It's just unplayable for me. There is Ars Magica Legacy on 1.18.0+ Minecraft versions, but it is not finished yet and much more effort is needed to make it at least at the level at which AM2 already was in 2014. So technically, I just got nowhere to port the addon, and my answer is NO, until they make it playable enough.
### <b>Q</b>: when it will be compatable with Alfheim?

  <b>A</b>: Not today.
### <b>Q</b>: Is it gameplay-balanced?

  <b>A</b>: No.
### <b>Q</b>: Did you think twice before making this addon?

  <b>A</b>: Think twice? Man, I don't even think once.
### <b>Q</b>: What is your favorite Minecraft 1.7.10 magic mod?

  <b>A</b>: Ars Magica 2. I guess it was obvious.
### <b>Q</b>: Can you add more Warframe Lavos reference?

  <b>A</b>: Ce'nos, again, my final answer is:
### no

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/">Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License</a>.
This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License. 

To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-nd/3.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

Summary
https://creativecommons.org/licenses/by-nc-nd/3.0

You are free to:
* Share — copy and redistribute the material in any medium or format
* The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following conditions:
* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* NonCommercial — You may not use the material for commercial purposes.
* NoDerivatives — If you remix, transform, or build upon the material, you may not distribute the modified material.
* No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Original mod is courtesy of Mithion with sources available at https://github.com/Mithion/ArsMagica2;
Modified version AM2.5 is courtesy of TCLProject with sources available at https://github.com/TCLProject/ArsMagica2-5.

The exceptions to this license are textures and models, wich are courtesy of opengameart.com, and licenses are that of their respective owners.
