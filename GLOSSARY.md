# Glossary

## Heating

**AC indoor unit**: The indoor part of an air-conditioning unit. It can heat,
cool, dry, and run in fan-only mode. Heating control applies to AC indoor units
only, never to the outdoor unit.

**AC heating switch**: The `input_boolean` that turns heating on or off for a
room. Turning it on selects heat and applies the target temperature. Turning it
off selects off on the AC indoor unit.

**Target temperature**: The room temperature that heating aims to achieve, as
measured by the room temperature sensor. It depends on whether the room is
occupied.

**Occupied**: The room is in use, so the occupied target temperature applies.

**Unoccupied**: The room is not in use, so the unoccupied target temperature
applies.

**Set temperature**: The temperature the AC indoor unit is told to aim for. When
the AC heating switch turns on, the set temperature is initially the target
temperature. While heating, it is stepped up or down.

**Deadband**: A band around the target temperature within which the set
temperature is left unchanged.
