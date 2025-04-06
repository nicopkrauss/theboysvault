---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/undead/ghast/","tags":["ttrpg-cli/compendium/src/5e/mm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/undead"]}
---

# [Ghast](3-Mechanics\CLI\bestiary\undead/ghast.md)
*Source: Monster Manual p. 148. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Ghouls roam the night in packs, driven by an insatiable hunger for humanoid flesh.

## Devourers of Flesh

Like maggots or carrion beetles, ghouls thrive in places rank with decay and death. A ghoul haunts a place where it can gorge on dead flesh and decomposing organs. When it can't feed on the dead, it pursues living creatures and attempts to make corpses of them. Though they gain no nourishment from the corpses they devour, ghouls are driven by an unending hunger that compels them to consume. A ghoul's undead flesh never rots, and this monster can persist in a crypt or tomb for untold ages without feeding.

## Abyssal Origins

Ghouls trace their origins to the Abyss. Doresain, the first of their kind, was an elf worshiper of Orcus. Turning against his own people, he feasted on humanoid flesh to honor the Demon Prince of Undeath. As a reward for his service, Orcus transformed Doresain into the first ghoul. Doresain served Orcus faithfully in the Abyss, creating ghouls from the demon lord's other servants until an incursion by Yeenoghu, the demonic Gnoll Lord, robbed Doresain of his abyssal domain. When Orcus would not intervene on his behalf, Doresain turned to the elf gods for salvation, and they took pity on him and helped him escape certain destruction. Since then, elves have been immune to the ghouls' paralytic touch.

## Ghasts

Orcus sometimes infuses a ghoul with a stronger dose of abyssal energy, making a ghast. Whereas ghouls are little more than savage beasts, a ghast is cunning and can inspire a pack of ghouls to follow its commands.

```statblock
"name": "Ghast"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "36"
"hit_dice": "8d8"
"stats":
- !!int "16"
- !!int "17"
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "Any creature that starts its turn within 5 feet of the ghast must succeed\
    \ on a DC 10 Constitution saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ until the start of its next turn. On a successful saving throw, the creature\
    \ is immune to the ghast's Stench for 24 hours."
  "name": "Stench"
- "desc": "The ghast and any ghouls within 30 feet of it have advantage on saving\
    \ throws against effects that turn undead."
  "name": "Turn Defiance"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 12\
    \ (2d8 + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage. If the target is a creature other than an undead,\
    \ it must succeed on a DC 10 Constitution saving throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Claws"
"source":
- "MM"
"image": "3-Mechanics/CLI/bestiary/undead/token/ghast.webp"
```{ #statblock}


## Environment

underdark, swamp, urban