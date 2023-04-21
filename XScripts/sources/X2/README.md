#X2 The Threat Scripts
[ **En** | [**Ru**](/README.RU.md) ]

## DEVICES

not exists.

## COMMANDS

### Turret AI: Defense (TAI Def.)

_CMD_TURRET_AI_DEF_ 

Destroy all enemies in range, in order of priority:

1. Missiles, aimed on the ship.
2. Script target.
3. Attacker.

If script has no target it will save when it is selected.

### Turret AI: Attack (TAI Atk.)

_CMD_TURRET_AI_ATK_ 

Destroy all enemies in range, in order of priority:

1. Missiles, aimed on the ship.
2. Ship's target, if exists.
3. Script target, if exists.
4. Attacker.
5. Nearest enemy.

If script has no target it will save when it is selected.

### Station: Sale price managment

_CMD_STATION_PRICEMANAGER_ 

Parameter: minimum price.

The script change the prise of the good betmin the maximum market price and user 
defined according the volume in storage.

### Ship AI: Patrol

_CMD_SHIP_AI_PATROL_

Parameter: target sector.

The ship attack all enemy ships in sector. If enemies aren't exists the ship 
will starts to collect flying wares. If ware is not a missile it will be 
destryed.

## INSTALL

Simple extract this content into the game directory.
