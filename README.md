# plist.add_control
## Arguments
* **Fieldname** - string
* **Control** - ui object
* **Default Value** - ui value type

# Note
* plist.get and plist.set function as normal, they have been modified to work with added controls as well as default controls.
* Either paste the code into your script or require it.

## Example Usage
```
plist.add_control("Blockbot Priority", ui.new_checkbox("Players", "Adjustments", "Blockbot priority"), false)

plist.get(player, "Blockbot Priority")

plist.set(player, "Blockbot Priority", true)
```
