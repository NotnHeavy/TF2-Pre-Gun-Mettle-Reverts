# Pre-Gun-Mettle-Reverts

Hey, have you missed playing with the ridiculously fast Degreaser? Have you missed gardening 7 out of 9 classes with ease with the Caber? What about Tide Turner crits, or Baby Face's Blaster with little to no boost loss, or the Sandman and Flying Guillotine combo, or the Beggar's Bazooka shotgun that is the Panic Attack, etc etc. If so, you have come to the right place!

This is a SourceMod plugin that reverts weapon attributes to just before Gun Mettle (July 2 2015), as accurately as possible. This is my first SM plugin as well, so it may not be perfect, but I worked up to my hardest!

You may always look up the attributes of weapons before Gun Mettle, but just a brief analysis: The TF2 Gun Mettle update was the first major update that marked a significant turn in weapon functionality. Some weapons got nerfs, some weapons got buffs, etc etc. Tough Break also brought a lot of changes to weapons, mostly nerfs instead however. This is the main reason why I picked before Gun Mettle as the timestamp of this project, so you could get a proper taste of old TF2, while also being able to experience nearly every weapon that TF2 still has (only the Dragon's Fury, Second Banana, Thermal Thruster and Gas Passer didn't exist before Gun Mettle).

## Installation.
Head over to the releases tab and download the most recent version. This plugin has been developed with SourceMod 1.11, for what it's worth. Once you have downloaded your ZIP, what you'll need to do first is move everything in "NotnHeavy's pre-Gun Mettle reverts\tf\\" to your server's \tf\ directory. Then, if your server also uses FastDL, move everything in "NotnHeavy's pre-Gun Mettle reverts\fastdl\\" to your server's FastDL directory. That's pretty much it! :)

## Things that have not been reverted.

I will say however, that flame mechanics are very difficult to look into and so I will not be looking into reverting them for the time being. It may not sound like much, but trust me, old flamethrowers were cursed as hell. I still managed to tune afterburn at least.

Airblast mechanics are mostly reverted (tf_airblast_cray 0), however the hitboxes and target auto-aim (the direction your projectiles went used to be influenced by which opponent you were looking at as well) have not been reverted either since I'm not sure what to do about those either. I'll look into it though.

I haven't reverted weapon models/weapon sounds at the moment either. The Rocket Jumper/Sticky Jumper are both an exception, however, since as of v1.2 I have fully reverted those weapons.

## Influences

This plugin has been influenced not only by my somehow massive interest in TF2's old mechanics, but also by a plugin called Weapon Reverts by bakugo (https://forums.alliedmods.net/showthread.php?p=2717299). I really enjoyed playing on servers with this plugin, and I thought about writing my own historically-accurate plugin with as many reverts as possible. Thank you bakugo :).

## Dependencies:
- asherkin's TF2Items extension.
- Dr!fter's DHooks extension (already a part of SourceMod since version 1.11, so you shouldn't have to worry about downloading it).
- Scags' SM-Memory extension.

## Cvars:
- **notnheavy_gunmettle_reverts_reject_newitems 0-1 (defaults to 1)** - block weapons that were not present before Gun Mettle.

## Credits.
- Thank you to nosoop for providing samples of code (functions used for memory management in this case) with your stocksoup plugin (https://github.com/nosoop/stocksoup)!

Project on AlliedModders: https://forums.alliedmods.net/showthread.php?p=2775250
