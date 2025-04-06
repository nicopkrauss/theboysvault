---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/elemental/earth-elemental/","tags":["ttrpg-cli/compendium/src/5e/mm","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/elemental"]}
---

# [Earth Elemental](3-Mechanics\CLI\bestiary\elemental/earth-elemental.md)
*Source: Monster Manual p. 124. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

An earth elemental plods forward like a walking hill, club-like arms of jagged stone swinging at its sides. Its head and body consist of dirt and stone, occasionally set with chunks of metal, gems, and bright minerals.

Earth elementals glide through rock and earth as though they were liquid. Earthbound creatures have much to fear from an earth elemental, since the elemental can pinpoint the precise location of any foe that stands on solid ground in its vicinity.

## Elementals

Elementals are incarnations of the elements that make up the universe: air, earth, fire, and water. Though little more than animated energy on their own planes of existence, they can be called on by spellcasters and powerful beings to take shape and perform tasks.

### Living Elements

On its home plane, an elemental is a bodiless life force. Its dim consciousness manifests as a physical shape only when focused by the power of magic. A wild spirit of elemental force has no desire except to course through the element of its native plane. Like beasts of the Material Plane, these elemental spirits have no society or culture, and little sense of being.

### Conjured by Magic

Certain spells and magic items can conjure an elemental, summoning it from the Inner Planes to the Material Plane. Elementals instinctively resent being pulled from their native planes and bound into service. A creature that summons an elemental must assert force of will to control it.

### Bound and Shaped

Powerful magic can bind an elemental spirit into a material template that defines a specific use and function. Invisible stalkers are air elementals bound to a specific form, in the same way that water elementals can be shaped into water weirds.

### Elemental Nature

An elemental doesn't require air, food, drink, or sleep.

```statblock
"name": "Earth Elemental"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "8"
- !!int "20"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 30 ft."
"damage_vulnerabilities": "thunder"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": "Terran"
"cr": "5"
"traits":
- "desc": "The elemental can burrow through nonmagical, unworked earth and stone.\
    \ While doing so, the elemental doesn't disturb the material it moves through."
  "name": "Earth Glide"
- "desc": "The elemental deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The elemental makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage."
  "name": "Slam"
"source":
- "MM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/earth-elemental.webp"
```{ #statblock}


## Environment

underdark