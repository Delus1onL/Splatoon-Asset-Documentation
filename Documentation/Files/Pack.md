# Pack

This will be ordered like this:
- [Enemy.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#enemy.pack)
- [Env.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#env.pack)
- [Layout.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#layout.pack)
- [Obj.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#obj.pack)
- [ObjSmall.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#objsmall.pack)
- [Player.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#player.pack)
- [Sound.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#sound.pack)
- [Static.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#static.pack)
- [System.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#system.pack)
- [Weapon.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#weapon.pack)

# Enemy.pack
place
# Env.pack
This pack deals specifically with the environments of all stages, as far as sun location, skydome, lighting color, intensities, brightnesses, etc.

## File Order
The Env.pack file contains an '.szs' file for every stage (I will use the word scene from here on out). This is the order of those files:

- ShootingRange.szs (Shooting Range)
- Hiagari.szs (Mahi-Mahi Resort)
- MisCharge.szs (place)
- Lobby.szs (MatchRoom)
- RailKing.szs (place)
- Jyoheki.szs (Flounder Heights)
- SeaPlant.szs (Saltspray Rig)
- World.szs (Octo Valley)
- LytSys.szs (place)
- CapPaneCmn.szs (place)
- MisDozer.szs (place)
- LytCmn.szs (place)
- LytHUD.szs (place)
- Pivot.szs (Museum d'Alfonso)
- Plaza.szs (Plaza(Day))
- Cmn.szs ("Common?")
- MisSkyGreen.szs (place)
- MisSkyGray.szs (place)
- MisSkyGalaxy.szs (place)
- MisBattle.szs (place)
- Customize.szs (place)
- MisSkySunset.szs (place)
- MisSkyDay01.szs (place)
- Mouthking.szs (place)
- MisSkyNight.szs (place)
- IconCapture.szs (place)
- Athletic.szs (Camp Triggerfish)
- Ruins.szs (Bluefin Depot)
- Warehouse.szs (Walleye Warehouse)
- Kaisou.szs (Hammerhead Bridge)
- Tuzura.szs (Moray Towers)
- SkatePark.szs (Blackbelly Skatepark)
- Office.szs (Ancho-v-Games)
- CmnMiniMap.szs (Minimap lighting)
- CylinderKing.szs (place)
- MisMonitorBroken.szs (place)
- Tutorial.szs (Tutorial)
- Crank.szs (Urchin Underpass)
- Maze.szs (Kelp Dome)
- Shop.szs (place)
- UpDown.szs (place)
- Quarry.szs (place)
- Amida.szs (place)
- Stampking.szs (place)
- MisSkyDay.szs (place)
- VSFinalResult.szs (Win-Lose Screen(?))
- MisSkyTwilight.szs (place)

## Contents
Each file has its own contents. Here is what each generally has, and what each term means. This will be shown as follows:
file.szs
^^file directory
^^^^^^^^...name [datatype] / desc


ShootingRange.szs
```
^^Crank.baglccrex
^^Crank.genvb
^^^^crank.baglccrex
^^^^^^param_root
^^^^^^^^Objects {}
^^^^^^^^^^color_correction
^^^^^^^^^^^^enable [Boolean] / on or off
^^^^^^^^^^^^hue [float] / place
^^^^^^^^^^^^saturation [float] / how much light color is absorbed
^^^^^^^^^^^^brightness [float] / how bright
^^^^^^^^^^^^gamma [float] / place
^^^^^^^^^^^^toycam_enable [Boolean] / place
^^^^^^^^^^^^toycam_offset1 [Color4F] / R G B A float numbers(to 1.0)
^^^^^^^^^^^^toycam_level1 [Color4F] / R G B A float numbers(to 1.0)
^^^^^^^^^^^^toycam_level2 [Color4F] / R G B A float numbers(to 1.0)
^^^^^^^^^^^^toycam_saturation1 [float] / place
^^^^^^^^^^^^toycam_saturation2 [float] / place
^^^^^^^^^^^^toycam_brightness [float] / place
^^^^^^^^^^^^toycam_contrast [float] / place
^^^^^^^^^^^^toycam_mul_color [Color4F] / place
^^^^^^^^^^^^level [Curve4] / place
^^^^^^^^^^2921014748
^^^^^^^^^^^^674039309 [float] / place
^^^^^^^^^^^^3461196268 [float] / place
^^^^^^^^^^^^3756975577 [float] / place
^^^^^^^^^^^^2379954372 [float] / place
^^^^^^^^^^^^4009682607 [float] / place
^^^^crank.bgenv
^^^^^^param_root
^^^^^^^^List {}
^^^^^^^^^^convert_parts_array
^^^^^^^^^^normal_parts_array
^^^^^^^^^^set_array
^^^^cranknight.baglenv
^^^^crank.baglenvset
^^^^cranknight.bglght
^^^^common.baglenv
^^^^crankday.baglatex
^^^^vr_model.txt
^^^^crank.baglcube
^^^^crankday.bglght
^^^^crankday.bgsdw
^^^^crankday.baglccr
^^^^crankday.baglenv
```
## Hiagari.szs
## MisCharge.szs
## Lobby.szs 
## RailKing.szs 
## Jyoheki.szs
## SeaPlant.szs
## World.szs
## LytSys.szs
## CapPaneCmn.szs
## MisDozer.szs 
## LytCmn.szs
## LytHUD.szs
## Pivot.szs 
## Plaza.szs 
## Cmn.szs 
## MisSkyGreen.szs
## MisSkyGray.szs 
## MisSkyGalaxy.szs 
## MisBattle.szs 
## Customize.szs
## MisSkySunset.szs 
## MisSkyDay01.szs
## Mouthking.szs 
## MisSkyNight.szs
## IconCapture.szs
## Athletic.szs 
## Ruins.szs 
## Warehouse.szs 
## Kaisou.szs 
## Tuzura.szs 
## SkatePark.szs 
## Office.szs
## CmnMiniMap.szs 
## CylinderKing.szs
## MisMonitorBroken.szs
## Tutorial.szs 
## Crank.szs 
## Maze.szs
## Shop.szs 
## UpDown.szs 
## Quarry.szs
## Amida.szs 
## Stampking.szs
## MisSkyDay.szs
## VSFinalResult.szs
## MisSkyTwilight.szs

# Layout.pack
place
# Obj.pack
place
# ObjSmall.pack
place
# Player.pack
place
# Sound.pack
place
# Static.pack
place
# System.pack
place
# Weapon.pack
place
