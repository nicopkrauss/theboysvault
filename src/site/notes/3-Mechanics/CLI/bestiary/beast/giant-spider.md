---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/beast/giant-spider/","tags":["ttrpg-cli/compendium/src/5e/mm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"]}
---

# [Giant Spider](3-Mechanics\CLI\bestiary\beast/giant-spider.md)
*Source: Monster Manual p. 328. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

To snare its prey, a giant spider spins elaborate webs or shoots sticky strands of webbing from its abdomen. Giant spiders are most commonly found underground, making their lairs on ceilings or in dark, web-filled crevices. Such lairs are often festooned with web cocoons holding past victims.

```statblock
"name": "Giant Spider"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "2"
- !!int "11"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "7"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
- "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the spider knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The spider ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 9 (2d8) poison damage on a failed save, or half as much damage\
    \ on a successful one. If the poison damage reduces the target to 0 hit points,\
    \ the target is stable but [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
    \ while [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in this way."
  "name": "Bite"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one creature. Hit:\
    \ The target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) by\
    \ webbing. As an action, the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ target can make a DC 12 Strength check, bursting the webbing on a success. The\
    \ webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire\
    \ damage; immunity to bludgeoning, poison, and psychic damage)."
  "name": "Web (Recharge 5-6)"
"source":
- "MM"
"image": "3-Mechanics/CLI/bestiary/beast/token/giant-spider.webp"
```{ #statblock}


## Environment

underdark, forest, swamp, urban, desert