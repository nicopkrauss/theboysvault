---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/beast/giant-octopus/","tags":["ttrpg-cli/compendium/src/5e/mm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"]}
---

# [Giant Octopus](3-Mechanics\CLI\bestiary\beast/giant-octopus.md)
*Source: Monster Manual p. 326. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Giant Octopus"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "52"
"hit_dice": "8d10 + 8"
"stats":
- !!int "17"
- !!int "13"
- !!int "13"
- !!int "4"
- !!int "10"
- !!int "4"
"speed": "10 ft., swim 60 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
- "desc": "While out of water, the octopus can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "The octopus has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made while underwater."
  "name": "Underwater Camouflage"
- "desc": "The octopus can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 15 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage. If the target is a creature, it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 16). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
    \ and the octopus can't use its tentacles on another target."
  "name": "Tentacles"
- "desc": "A 20-foot-radius cloud of ink extends all around the octopus if it is underwater.\
    \ The area is heavily obscured for 1 minute, although a significant current can\
    \ disperse the ink. After releasing the ink, the octopus can use the Dash action\
    \ as a bonus action."
  "name": "Ink Cloud (Recharges after a Short or Long Rest)"
"source":
- "MM"
"image": "3-Mechanics/CLI/bestiary/beast/token/giant-octopus.webp"
```{ #statblock}


## Environment

underwater