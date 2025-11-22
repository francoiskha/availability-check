# availability-check

Home Assistant blueprints are useful for creating automations to check the unavailability of Home Assistant entities with a specific label. 
If an entity becomes unavailable or does not report since a certain amount of time then a notification is sent with a list of unavailable entities.

These blueprints are currently only available in French.
- `availability_check_label.yaml`: Checks entities with a specific label.
- `availability_check_wildcards.yaml`: Checks entities whose ID matches a string filter with wildcards.

Full documentation available here: https://www.hacf.fr/surveillance-entites/

