## PAR5E Documentation on NPC data

Input:
* Empty lines denote the start of a new NPC
* Resistances, Vulnerabilities and Immunities can span multiple lines
* TRAIT/ACTION/REACTION names must start on a new line
* TRAIT/ACTION/REACTION description text can span multiple lines

```
[{Name of Monster}\n
{Tiny|Small|Medium|Large|Huge|Gargantuan} {Aberration|Beast|Celestial|Construct|Dragon| Elemental|Fey|Fiend|Giant|Humanoid|Monstrosity|Ooze|Plant|Undead}, {alignment}\n
Armor Class #\n
Hit Points # (#d#);
Speed {speeds}\n
STR DEX CON INT WIS CHA # (-/+#) # (-/+#) # (-/+#) # (-/+#) # (-/+#) # (-/+#)
Saving Throws {text}\n
Skills {text}\n
Damage Vulnerabilities {text}\n
Damage Resistances {text}\n
Damage Immunities {text}\n
Condition Immunities {text}\n
Senses {senses}\n
Languages [{language},]\n
Challenge # (# XP)\n
[{trait name}. {trait text}\n ]
ACTIONS\n
[{action name}. {action text}\n ]
REACTIONS\n
[{reaction name}. {reaction text}\n ]
L!EGENDARY ACTIONS\n
[{legendary action name}. {legendary action text}\n ]
##;
[{npc descriptive text}\n]\n]
```
e.g.
```
COMMONER
Medium humanoid (any race), any alignment
Armor Class 10
Hit Points 4 (1d8)
Speed 30 ft.
STR DEX CON INT WIS CHA 10 (+0) 10 (+0) 10 (+0) 10 (+0) 10 (+0) 10 (+0)
Senses passive Perception 10
Languages anyone (usually Common)
Challenge 0 (10 XP)
ACTIONS
Club. Melee Weapon Attack: +2 to hit, reach 5 ft. , one target. Hit: 2 (ld4) bludgeoning damage.
##;
Commoners include peasants and serfs, slaves and servants, pilgrims, merchants, artisans, and hermits.
CULTIST
Medium humanoid (any race), any non good alignment
Page 17of3  6
Armor Class 12 (leather armor)
Hit Points 9 (2d8)
Speed 30 ft .
STR DEX CON INT WIS CHA 11 (+0) 12 (+1) 10 (+0) 10 (+0) 11 (+0) 10 (+0)
Skills Deception +2, Religion +2
Senses passive Perception 10
Languages anyone (usually Common)
Challenge 1/8 (25 XP)
Devotion. The cultist has advantage on saving throws against being charmed or frightened.
ACTIONS
Scimitar. Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (ld6 + 1) slashing damage.
##;
Cultists swear allegiance to dark powers. They conceal their activities to avoid being o!stracized, imprisoned, or executed for their beliefs.

```
