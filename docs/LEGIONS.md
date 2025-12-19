# Legions

## Design

Legions are a group of units. They are also what is usually understood of "units" in other 4X games like Civ. The legions are the entities that you can select, move around the map and let fight against other units.

A Legion can contain only units of the same type (same id).

A legion has a maximum size, which is calculated by summing up all the unit sizes in the legion. The max size is 12.

In contrary to units, legions do not have any types/templates, as they are only a group of units. So the stats of a legion is defined by its unit type.

## Legion variables

### Stats

I am not sure yet what stats should be shown for the legion..

- Total health
- Health percentage? (totalHealth/unitCount*unitMaxHealth)
- Unit count (just len(units))
- Total damage? (or maybe split in attacks & damage and people need to calculate?)

### Other variables

- Unit type (id)
- Units (list of units)
- Display name? (like in SOVL?)
