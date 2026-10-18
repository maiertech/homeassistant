# Glossary

## Heating

**AC unit**: An air-conditioning unit that can heat, cool, dry, and run in
fan-only mode. Heating control applies to AC units only.

**AC heating switch**: The `input_boolean` that turns heating on or off for a
room. Turning it on selects heat and applies the target temperature. Turning it
off selects off on the AC unit.

**Target temperature**: The room temperature that heating aims to hold. It
depends on whether the room is occupied.

**Occupied**: The room is in use, so the occupied target temperature applies.

**Unoccupied**: The room is not in use, so the unoccupied target temperature
applies.

**Setpoint**: The temperature the AC unit is set to heat to.

**Deadband**: A band around the target temperature within which the setpoint is
left unchanged.
