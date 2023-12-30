# Pack

This will be ordered like this:
- [Enemy.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#enemypack)
- [Env.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#envpack)
- [Layout.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#layoutpack)
- [Obj.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#objpack)
- [ObjSmall.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#objsmallpack)
- [Player.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#playerpack)
- [Sound.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#soundpack)
- [Static.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#staticpack)
- [System.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#systempack)
- [Weapon.pack](https://github.com/Delus1onL/Splatoon-Decompile-For-Splatoon-Legends/blob/main/Documentation/Files/Pack.md#weaponpack)

# Enemy.pack
These are the models and animations related to the enemies in Story Mode.
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

# Layout.pack
This deals with the UI/HUD elements of the game. For example, the title screen or the gamepad's layout.

### AddRoomBtn_00
|GambitPatternS_02^r.bflim|HomeGroundUp^q.bflim|Light_01^s.bflim|ResultMeter_00^f.bflim|
|------------|------------|------------|------------|
|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/GambitPatternS_02%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/HomeGroundUp%5Eq.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/Light_01%5Es.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/ResultMeter_00%5Ef.bflim.png)|

### AmiiboCourseBtn_00
|AmiiboCourseBtn_00^s.bflim|ClearIcon_00^t.bflim|GambitPatternL_04^r.bflim|GambitPatternL_05^r.bflim|GambitPatternL_11^r.bflim|GambitPatternSS_00^r.bflim|GambitPatternSS_01^r.bflim|GambitPatternSS_02^r.bflim|GambitPatternSS_03^r.bflim|GambitPatternSS_06^r.bflim|Ink128_00^s.bflim|LightRS_00^r.bflim|MisInfo_00^s.bflim|
|------|------|------|------|------|------|------|------|------|------|------|------|------|
|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/AmiiboCourseBtn_00%5Es.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/ClearIcon_00%5Et.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternL_04%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternL_05%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternL_11%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternSS_00%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternSS_01%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternSS_02%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternSS_03%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/GambitPatternSS_06%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/Ink128_00%5Es.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/LightRS_00%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AmiiboCourseBtn_00/AmiiboCourseBtn_00/MisInfo_00%5Es.bflim.png)|

### AreaAddTime_00
|GambitPatternS_02^r.bflim|HomeGroundUp^q.bflim|Light_01^s.bflim|ResultMeter_00^f.bflim|
|------------|------------|------------|------------|
|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/GambitPatternS_02%5Er.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/HomeGroundUp%5Eq.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/Light_01%5Es.bflim.png)|![img](https://github.com/Delus1onL/Images/blob/main/layout/AddRoomBtn_00/AddRoomBtn_00/ResultMeter_00%5Ef.bflim.png)|

# Obj.pack
place
# ObjSmall.pack
place
# Player.pack
This has multiple things, like the inkling models, octoling models, hidden Miiverse posts, paint textures, and more.
# Sound.pack
This holds most of the sound effects the game uses. (At least most of them; some of them are saved as stream files, or .bfstm files, in the /content/Sound/Resources/Stream directory.)
# Static.pack
This deals with a lot of parameters, like weapons (how they shoot), maps (object layout), and more.
# System.pack
place
# Weapon.pack
This pack holds all the weapons originally released with the game, without updates, whereas the rest of the weapons are singular models in the "/content/Models" directory.

## E-Liter 3K (EU: E-Litre 3K)
![jkt2](https://github.com/Delus1onL/Images/blob/main/Models/Wmn_Charge_Long.png)
- Was: Wmn_Charge_Long.szs
- Acquired: Weapons Shop
