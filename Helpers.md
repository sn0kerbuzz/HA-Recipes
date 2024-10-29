# Helpers

## Running state based on power consumption

Lets say that you have a device that is plugged in an outlet with power consuption monitoring and you want to know if it is running or not based on the power consumed. In this case you can create a running binary template helper with this template:

```jinja
{{ states('sensor.<current_entity_of_the_plug>>') | float(0) > 0.0 }}
```
