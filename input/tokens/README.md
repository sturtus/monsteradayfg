Folder for an alphabetical listing of all tokens, png format, top down style. Use the pog_base01.psd file in the root of this project as a base for your token.

## PAR5E Documentation on Tokens

Tokens can be linked to both the Campaign classes of 5E (under Personalities) and the Reference Library (NPC). Token content is parsed using a single source folder.
✦ tokens

### Tokens

Input:
* PNG tokens located in the token path will be copied to the module.
* Tokens which match the sane name of Traps/NPCs will be linked to the objects. A sane name is a name converted to lowercase and with all spaces removed and non-alpha characters converted to _ characters.
```
Fred Blog = fredblog.png
Skeleton (Undead) = skeleton_undead_
```
* If a sane name match cannot be made, an attempt to match the first letter of the NPC/Trap against tokens is made (caters for generic letter tokens).
* NOTE: Sanenames of Encounter NPCs which use a title must match the encounter npc title instead of the encounter npc name.
```
1;Bugbear;Klarg; requires a token named as klarg.png
1;Wolf;Ripper; requires a token named as ripper.png
```
