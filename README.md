*Created by Kevin,*

*modified by keithcurtis & Gigs*

This script creates token actions on selected tokens for the D&D 5e by Roll20 sheet. Tokens must represent character sheets, either PC or NPC.

**!ta** This command will create a full suite of token action buttons for a selected character. Actions for NPCs and Attacks for PCs.
**!deleteta** will delete ALL token actions for the selected character, whether they were created by this script or not. Use with caution.

You can create specific classes of abilities by using the following arguments separated by spaces:
- **attacks** Creates a button for each attack. In the case of NPCs, this includes all Actions.
- **spells** Creates a button that calls up a chat menu of all spells the character can cast.
- **checks** Creates a drop down menu of all Ability and Skill (Ability) checks
- **saves** Creates a dropdown menu of all saving throws
- **init** Creates a button that rolls initiative for the selected token
- **name** Normally, Token Actions are created using the character_id. They will still function even if the character is renamed. However this is not always desireable. If a character is moved to a new game via the Character Vault, it will receive a new character_id, and the token actions will not function. If you intend to move the character, use the "name" argument in the string and it will call the token actions by name.
- **help** Calls up this help documentation

Examples:
**!ta saves checks** will create token ability buttons for Ability Checks and Saving Throws.

**!ta name** will create alltoken ability buttons and identify them by name, rather than character_id..
