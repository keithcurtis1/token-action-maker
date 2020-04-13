*Created by Kevin,*

*modified by keithcurtis*

This script creates token actions on selected tokens for the D&D 5e by Roll20 sheet. Tokens must represent character sheets, either PC or NPC.

**!ta** This command will create a full suite of token action buttons for a selected character. Actions for NPCs and Attacks for PCs.

You can create specific classes of abilities by using the following arguments separated by spaces:
- **attacks** Creates a button for each attack. In the case of NPCs, this includes all Actions.
- **spells** Creates a button that calls up a chat menu of all spells the character can cast.
- **checks** Creates a drop down menu of all Ability and Skill (Ability) checks
- **saves** Creates a dropdown menu of all saving throws
- **init** Creates a button that rolls initiative for the selected token
- **help** Calls up this help documentation

Example:
**!ta saves checks** will create token ability buttons for Ability Checks and Saving Throws.
