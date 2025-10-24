**USAGE INSTRUCTIONS**

The Player_Took_Damage roll will automatically prompt you when your players modify their 'hp' on their character sheet, or in a bar value (as long as that bar value is associated with the hp value from their character sheet). It also notifies you if a player falls unconscious or regains consciousness. The actual amount healed or damage taken will be whispered to the DM.

1. Create a character (case sensitive) named: ScriptCards_Triggers

1. Restart your API sandbox.

1. Navigate to the Attributes & Abilities section of the new 'ScriptCards_Triggers' character sheet.

1. Create a new ability called 'change:attribute:hp', copy paste'Player_Took_Damage.roll' into the body of the Ability.