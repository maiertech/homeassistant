# AC unit heating (Office TM)

Create an automation from the `AC unit heating` blueprint with these values.
Keep `automations/heating_office_tm.yaml` until this instance works, then remove
it.

| Input                         | Value                              |
| ----------------------------- | ---------------------------------- |
| AC unit                       | `climate.office_tm_toshiba`        |
| Room temperature sensor       | `sensor.office_tm_avg_temperature` |
| Occupancy entity              | `input_boolean.office_tm_occupied` |
| Unoccupied target temperature | 16 °C                              |
| Occupied target temperature   | 22 °C                              |
| Night setback start           | `00:00:00`                         |
| Night setback end             | `07:00:00`                         |

The heating season is fixed at 1 October to 31 March, so there is no heating
season entity to select.
