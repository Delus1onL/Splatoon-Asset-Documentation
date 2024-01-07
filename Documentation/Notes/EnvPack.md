# Env.pack
This pack deals specifically with the environments of all stages, as far as sun location, skydome, lighting color, intensities, brightnesses, etc.

## File Order
The Env.pack file contains an '.szs' file for every stage (I will use the word scene from here on out). This is the order of those files:

```
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
- Shop.szs (Weapons Shop, Gear Shop, Tshirts Shop, Shoes Shop)
- UpDown.szs (Arowana Mall)
- Quarry.szs (Piranha Pit)
- Amida.szs (Port Mackerel)
- Stampking.szs (place)
- MisSkyDay.szs (place)
- VSFinalResult.szs (Win-Lose Screen(?))
- MisSkyTwilight.szs (place)
```

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
Hiagari.szs
```
place
```
MisCharge.szs
```
place
```
Lobby.szs 
```
place
```
RailKing.szs 
```
place
```
Jyoheki.szs
```
place
```
SeaPlant.szs
```
place
```
World.szs
```
place
```
LytSys.szs
```
place
```
CapPaneCmn.szs
```
place
```
MisDozer.szs 
```
place
```
LytCmn.szs
```
place
```
LytHUD.szs
```
place
```
Pivot.szs 
```
place
```
Plaza.szs 
```
place
```
Cmn.szs 
```
place
```
MisSkyGreen.szs
```
place
```
MisSkyGray.szs 
```
place
```
MisSkyGalaxy.szs 
```
place
```
MisBattle.szs 
```
place
```
Customize.szs
```
place
```
MisSkySunset.szs 
```
place
```
MisSkyDay01.szs
```
place
```
Mouthking.szs 
```
place
```
MisSkyNight.szs
```
place
```
IconCapture.szs
```
place
```
Athletic.szs 
```
place
```
Ruins.szs 
```
place
```
Warehouse.szs 
```
place
```
Kaisou.szs 
```
place
```
Tuzura.szs 
```
place
```
SkatePark.szs 
```
place
```
Office.szs
```
place
```
CmnMiniMap.szs 
```
place
```
CylinderKing.szs
```
place
```
MisMonitorBroken.szs
```
place
```
Tutorial.szs 
```
place
```
Crank.szs 
```
place
```
Maze.szs
```
place
```
Shop.szs 
```
place
```
UpDown.szs 
```
place
```
Quarry.szs
```
place
```
Amida.szs 
```
place
```
Stampking.szs
```
place
```
MisSkyDay.szs
```
place
```
VSFinalResult.szs
```
place
```
MisSkyTwilight.szs
```
place
```
