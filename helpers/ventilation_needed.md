# Ventilation needed (template binary sensor)

This sensor turns on after humidity stays above 60% for an hour and clears after
the template condition stays false for 15 minutes.

| Field        | Value                                           |
| ------------ | ----------------------------------------------- |
| Name         | `Humidity`                                      |
| State        | Use the template below.                         |
| Device class | `Problem`                                       |
| Device       | Leave blank.                                    |
| Availability | Leave blank (invalid readings evaluate to off). |
| Delay on     | `01:00:00`                                      |
| Delay off    | `00:15:00`                                      |

```jinja
{{ states('sensor.office_tm_humidity') | float(0) > 60 }}
```
