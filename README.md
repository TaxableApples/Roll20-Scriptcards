<<<<<<< HEAD
# Roll20-Scriptcards
=======
# Roll20-Scriptcards

Scriptcards is an API for Roll20 developed by Kurt Jaegers, for scriptcards tutorials and examples see his [youtube channel](https://www.youtube.com/@kurtjaegers265) and [GitHub Page](https://github.com/kjaegers/ScriptCards)
    
Usage Documentation can be found [here](https://wiki.roll20.net/Script:ScriptCards)

**Requirements:**
-You must have a Roll20 Pro Account.
-I recommend using D&D 2014 Character sheets.
-As of writing this, scriptcards are not compatible with D&D 2024 or Jumpgate.
-Install the Following APIs into your game in the API MOD Menu: 
    --Scriptcards 
    --TokenMod 
    --Supernotes

**Optional Custom Setup:**
For each of your characters, navigate to the Attributes & Abilities tab on their character sheet.
-Under 'cust_spellcasting_ability', type their plain text spellcasting ability, for example "Wisdom". This is optional, but will allow the players to see their spellcasting ability is correct when inspecting attack rolls.

Placing some custom status icons on a token will flag that creature to automatically roll with advantage or disadvantage on saving throws, but you will need to create these status icons.
From the game Launch Screen on the right side you will find a section called 'Token Marker Sets' Create two tokens named: 'Advantage', 'Disadv'. The icon itself can be anything you want. I found dice icons with up and down arrows online that work great. 

**Usage**
-Macros can be pasted into the chat, and if you have the required APIs installed in Roll20, the script will execute.

-I recommend adding these Macros as Token Actions on a Player's Character Sheet, in the Attributes & Abilities Section, under Abilities.

-The macros I share will be compatable with Dungeons & Dragons 5e ruleset, and will include content from the D&D 5e [V5.1 Systems Reference Document (including Creative Commons)](https://media.wizards.com/2023/downloads/dnd/SRD_CC_v5.1.pdf)

**About This Project**
I'm not going to make every spell, but I wanted to make a library of macros for attacks and spells that are either thematically fun, or useful to speed up combat in Roll20. All of the spells can be customized by modifying the variables at the top of the macro. I created a ToDo.md file and I will cross off spells, abilities and attacks as I finish them.

I think these macros will work best when used by the players only, as this will allow them to have more hands on control over the game, while significantly speeding up combat. However, I won't be making macros for NPCs other than maybe some visual FX. I don't care to add any functions that will change the players character sheet in any way, as I trust my players to manage their own spell slots, hit points, class feats etc and IMHO doing otherwise is detremental to their player agency.

Happy dungeon crawling!
>>>>>>> master
