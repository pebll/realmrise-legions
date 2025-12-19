# Ideas

## Experience & Leveling

The idea until now was that units themselves can't level up, and only the "factory" can level up (after producing enough units) and then all subsequent units will get a chosen upgrade.

The reason behind this is that with so many units, there will always be some unit leveling up and choosing upgrades is painful for each unit.

But I still want leveling up, maybe just for the feeling of having your old first legion still alive and fighting strong, even against now leveled up enemies.

So now the question arises: how do we allow for units levelling up without spamming the user with level up choices?

### Answers

Currently two (three) answers arise:

#### 1: Predefined unit leveling path

For each unit type, there exists a precoded leveling path, that will be followed no matter what when leveling.

- (+) no need to make any choices, leveling just happens
- (-) can't choose how to specialize your units
- (-) upgrading factories now becomes weird, as there is then two different leveling mechanics (or we just dont allow for choice in the factory upgrade but that seems off too)

#### 2: Legion leveling

Do not level factories, do not level units, but level legions directly. This would mean that each legion can have its own identity by choosing a distinct leveling path.

- (+) This is very intuitive and allows for not very frequent and significant upgrades
- (-) What happens with refilling the legion? Imagine a LVL5 rat legion survives with one unit, do all the refilled units get LVL5? That seems a bit unfair.. but how to do it else? And also what happens then when merging/splitting units of different levels..? More thought has to be put in this...

Actually some thought has now been put into this and i think i've come up with an elegant solution:

- Legions level up (not individual units or factories)
- Units leaving a legion = become LVL0
- Units joining a legion = inherit that legion's level
- New legions start at LVL0

Why this works:

- No micro-management (one choice per legion level, not per unit)
- Creates "veteran warband" identity and attachment
- Prevents split-exploit (splitting gives LVL5 + LVL0, not 2x LVL5)
- Refilling works naturally (new recruits join veterans, become elite)

#### 3: Only factory leveling (change nothing)

Change nothing and don't do leveling for now.
