PALADIN MOD 1.0 for LH 1.8 7/23/15

by D. Elliot Lamb (davrovana on the Elemental forums, forums.elementalgame.com)
Amazon author page: http://www.amazon.com/D.-Elliot-Lamb/e/B010YMF3X2/ref=sr_tc_2_0?qid=1437673439&sr=1-2-ent

---

I. Release notes

II. Installation

III. Compatibility

IV. Thanks

V. Guide to the Paladin

APPENDIX I: What is the Background Unitstat Library?

---

I. This is the 'full' version of this mod. It has been tested very thoroughly at this point, but please feel free to report any bugs at the forum thread above.
I still support (and play!) this mod as of July 2015.

Path of The Paladin is part of the 'Between Life and Death' Mod pack. However a version of it is included as a component of XtraDeconstruct by Primal_Savage. Thanks to Primal for featuring it and doing the compatibility work! 

---

II. Installation

Step 0: Delete the old version, if any!

Step 1: Unpack the .rar file into your Legendary Heroes Mods folder.

"Documents > MyGames > LegendaryHeroes > Mods"

Step 2: Move the 'Paladin path Graphics' folder to "Documents > MyGames > LegendaryHeroes > Mods > Gfx"

Step 3: Make sure "use mods" is selected in the games preference file. If not, toggle this setting and re-start the game.

Step 5: Delete "A_LHLIB_UnitStat_BG_vL" if you already have it installed elsewhere (comes with Children Of Storm, Demons & Wizards, etc.)

---

III. Compatibility

This mod is compatible with Children Of Storm, Demons And Wizards, and XtraDecontruct, Black Market Bazaar, Champion Bonanza, any mod by me, and most other mods.

I may try to add some interesting interactions with the Priest class in Demons and Wizards in the future.

---

IV: Thanks

Thanks to fsemprini for his incredible work with the graphics. 

Thanks to Soronarr for his Kingdom Of Vanyar mod that used this mod extensively and raised awareness of it. I in turn used some of his graphics for this mod, which make it look even better.

The Spirit Warg icon was a generous Christmas gift from the Santa/Jesus of modding, Primal_Savage.

Thanks to Brad and Derek for making the game so moddable. 

Special thanks to Hellions for making the swords in his excellent Black Market Bazaar mod compatible with paladin sword unitstats.

Thanks to Heavenfall, parrotmath, Primal_Savage, abob101, and all the modders or mod players who have helped me learn to mod and tweak this game engine. 

To Primal_Savage, in particular, for the many bugs he has helped to find.

---

V. GUIDE TO THE PALADIN

The Paladin is a very powerful path. But not necessarily the best, because he requires a lot of leveling up to really shine. Also, several of his abilities require tithing in gold. Early game, the paladin can be expensive to level up. A magic-focused paladin will burn through mana ruthlessly if you aren't careful (get him enchanted with Mantle Of Oceans!).

His tree has two major paths, the 'physical damage' path at the top, and the 'magic' path at the bottom.

The Paladin can be a warrior as tough as the Warrior class - but only if he's in a small army, or uses a sword. His penalty to initiative in armies of 5 or larger reflects a need to be a hero, not a soldier. Without a sword, his advanced damage abilities are useless.

The Paladin really shines as a border patrol or guerilla warfare unit - team him up with two strong archer or mage units, and you can kill monsters or attack undefended fronts of the enemy.

(If you're looking for your hero primarily to deal strong physical damage and get along with large armies, the Warrior equipped with an axe or blunt weapon is probably the better choice.)

The Paladin can be a powerful spellcaster, but with a catch. Almost are his spells are close-range, and he does not get the mage's tactical mana discounts. 

(So if you want a pure spellcaster, be a Mage - or even Sorcerer!).

If you're willing to send your paladin in head-first with plenty of mana, though, his spells can fell entire armies (damaging himself in the process, most likely).

Also keep in mind that Paladins can summon squires, which are Paladin henchmen. This can let you 'build your own' champions that don't split xp, with only one catch: they must be paladins. 

---

APPENDIX I: What is the background Unitstat Library?

The library is in the folder "A_LHLIB_UnitStat_BG_vL"

If you're like I was when I first began installing mods, I am very wary of installing anything I do not understand. So here's a quick explanation of what the library is, and why the Paladin mod requires it.

-WHAT IT IS: The library mod adds 'unitstats' to many units, spells, and abilities. They custom stats (stats include hit points, attack, spell resist, etc) created so that 

What's cool about creating new stats is that they do nothing at all unless something else calls for that stat - like, say, the paladin mod.

So if you install ONLY the unit stat background library mod, there would be zero gameplay change, and only a few new icons would appear to let you know you'd installed anything at all.

-WHY PALADIN NEEDS IT: The Paladin and Anti-Paladin have abilities that give them damage bonuses against creature types, like undead, oversized units, sovereigns, etc.

The unitstat library inserts all the needed stats into monsters and units throughout the game. With the library, the game is checking to see if a unit is a sovereign attacks it, and giving a damage bonus if so.

Without the library, your paladin's special bonuses would do nothing at all.

-BONUS TO USING THE UNITSTATS LIBRARY:

Other mods use it, too, so one install makes your game ready for new mods when you're ready (like Children of Storm, Demons & Wizards, XtraDeconstruct).