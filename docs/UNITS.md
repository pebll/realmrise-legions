# Units

## Design

Units are a single entity of a fantasy creature/character. It can be anything from a human archer to a undead skeleton, a goat or a huge dragon.

They are the fighting force. They always are part of a legion, and will do whatever the legion does (move, attack).

There are unit templates (aka. unit types) that have predefined stats and variables (like the example Orc Barbarian). A unit instance inherits from a template and then can get modified by taking damage for example.

## Unit Variables

### Stats

- Health (the number of damage a unit can take before death)
- Damage (the number of damage a unit deals on each attack)
- Attacks (the number of attacks a unit performs in one combat)

- Movement (the number of hexes a unit can move in one turn)
- Size (determines how many units can fit in a legion)

### Other variables

- id (unique string that references this unit e.g. orc_barbarian, maybe ENUM?)
- Display name (e.g. Orc Barbarian, should (where possible) be automatically generated from id)
- Asset path (e.g. orc_barbarian.png, should be generated from id)

## Example unit: Orc barbarian

- Health: 6
- Damage: 2
- Attacks: 2
- Movement: 2
- Size: 2

- id: "orc_barbarian"
- Display name: "Orc Barbarian"
- Asset path: orc_barbarian.png
