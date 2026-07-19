

# reece's config
A complete Team Fortress 2 config.
This is mostly for my personal use but i'd be glad if it could help others


![https://i.ibb.co/FksszwqW/tf2logo2.png](https://i.ibb.co/FksszwqW/tf2logo2.png)

## Regular Install:
1. Download the latest reececonfig.zip
https://github.com/systemclove/reececonfig/releases/download/latest/reececonfig.zip
2. Right click TF2 in the steam library list and select Manage > Browse local files
3. Extract the "tf" folder from reececonfig.zip into the "Team Fortress 2" folder (the folder that contains the existing "tf" folder). Allow it to replace/overwrite files if it asks to.
4. Right click TF2 in the steam library again and select Properties > General
5. Set your launch options to these: (make sure to replace -w 1920 -h 1080 with whatever your monitor's resolution is.)

``-dxlevel 95 -windowed -noborder -w 1920 -h 1080 -console -novid -high -condebug -conclearlog -usercon -g15``

7. Launch the game, the config should be installed now! Look for the bunny in console to verify.

Note: since this skips clearing out the old "custom" and "cfg" folders, any leftover configs, scripts, or hud files from before could conflict with the new ones. If something looks off or breaks in-game, that's the most likely cause. worth doing the clean install instead in that case.

## Clean Install:
1. Download the latest reececonfig.zip
https://github.com/systemclove/reececonfig/releases/download/latest/reececonfig.zip
2. Right click TF2 in the steam library list and select Manage > Browse local files
3. Navigate to the "tf" folder and delete the "custom" and "cfg" folders
4. Right click TF2 in the steam library again and select Properties > General
5. Remove any launch options you already have specified and replace them with just "-autoconfig"
6. Launch the game once then close it
7. Extract the "tf" folder from reececonfig.zip into the "Team Fortress 2" folder (the folder that contains the existing "tf" folder). Allow it to replace/overwrite files if it asks to.
8. Remove "-autoconfig" from your launch options and replace them with these: (make sure to replace -w 1920 -h 1080 with whatever your monitors resolution is.)

``-dxlevel 95 -windowed -noborder -w 1920 -h 1080 -console -novid -high -condebug -conclearlog -usercon -g15``

9. Launch the game, the config should be installed now! look for the bunny in console to verify

## Settings:
Edit cfg/mybinds.cfg to add custom binds without disturbing other configs

## Changes:
### --- General ---
- Duck rebound to Q
- F1, F2, F3, F4 Bound to loadout preset swapping
- Scrolling bound to jump (for bhopping)
- Net graph can be toggled with "-"
- My personal default map selection
- My hitsound and killsound
### --- Medic ---
- Mouse5 bound to Ubercharge ready (team chat bind + voiceline)
- Mouse4 bound to quickbow script (hold to fire a crossbow bolt, let go to switch back to medigun)
### --- Engineer ---
- Mouse4 bound to build sentry
- Mouse5 bound to destroy sentry
- 4 bound to build dispenser
- E bound to build teleporter entrance
- R bound to build teleporter exit
(Note the last 3 will also destroy your old building, if you have one, as soon as you press the bind)
- B bound to teleport to spawn (eureka effect)
- Shift + B bound to teleport to teleporter exit (eureka effect)
(thanks solarlight)


## Credits
SolarLight - Eureka Effect tp script
Oatmeal - offline jump script
cfg.tf - "Tweaks" folder cfg files, some parts of the other cfg files, and i believe they made the demo recording cfg

