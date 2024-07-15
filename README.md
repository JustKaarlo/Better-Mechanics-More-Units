# Better Mechanics : More Units Development


## TERRAIN TYPES
| Types         | Notes         |
| ------------- | ------------- |
| forest        |               |
| hills         |               |
| mountain      |               |
| plains        |               |
| urban         |               |
| jungle        |               |
| marsh         |               |
| desert        |               |
| river         |               |
| amphibious    |               |
| fort          |               |
| snow          | This can end up stacking with terrain benefits |
### TERRAIN MODIFIERS
| Modifier      | Effect        |
| ------------- | ------------- |
| movement      | `0.00`        |
| attack        | `0.00`        |
| defence       | `0.00`        |

---

| Option                    | Boolen        | Example                            | Note          |
| -------------             | ------------- | -------------                      | ------------- |
| active                    | `yes` `no`    | `active = yes`                     | Whether the unit is usable without explicit unlocking in technology |
| special_forces            | `yes` `no`    | `special_forces = yes`             | Used to define subunit as special forces |
| can_be_parachuted         | `yes` `no`    | `can_be_parachuted = yes`          | Used to define subunit as paratroopers. |
| is_convertable            | `yes` `no`    | `is_convertable = yes`             | Can be converted |
| affects_speed             | `yes` `no`    | `affects_speed = yes`              | Used to check if the unit will affect the template's speed, support companies have it set to no. |
| transport                 | `<equipment>` | `transport = mechanized_equipment` | Sets the speed of subunit via equipment. Used for motorized/mechanized |
| can_exfiltrate_from_coast | `yes` `no`    | `can_exfiltrate_from_coast = yes`  | Can this subunit board convoys from a non-port location. |
| same_support_type         | `unit_type`   | `same_support_type = recon `       | Blocks adding other recon types to template |
