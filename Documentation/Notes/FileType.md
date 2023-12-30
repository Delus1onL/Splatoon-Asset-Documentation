# File types (Basic Descriptions)

This will go over the different files used, and at least some basic information about them.

## .szs
  This is sort of like a `.zip` file; it compresses files used for the game, which can store models, textures, text files, layouts, etc. You can open these with Switch ToolBox.
## .pack
  This is like a `.zip` file as well, except it more specific to Wii U, as the 3DS has it's own `.szs` file format. Although both Wii U and 3DS have `.szs` files, they are not interchangable. You can open these with Switch ToolBox.
## .bfstm
  This is the file format used for soundtracks in-game, like the 3DS' `.bcstm` file format. These are streamed to the RAM, and require constant reading, or else the game could crash. You can open these with BrawlBox or Switch ToolBox.
## .bfwav
  This is the file format for sound effects, like the 3DS' `.bcwav` file format. These files are typically found in `.bars` files. You can open these with -- or Switch ToolBox.
## .bameta
  This is the file format for presumably the `.bfwav`'s metadata. More analyzing will have to be done. With no tool to directly edit these, I took it into `Hexed.it` and tried understanding it. Here's what I found (in hex editor format).

|Address|00|01|02|03|04|05|06|07|08|09|0A|0B|0C|0D|0E|0F|
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|0x00000000|41|4D|54|41|FE|FF|X1|00|X2|X2|X2|X2|00|00|00|00|
|0x00000010|00|00|00|80|00|00|00|8C|44|41|54|41|00|00|00|60|
|0x00000020|00|00|00|00|00|00|00|00|00|X3|00|02|3F|49|93|26|
|0x00000030|00|00|X4|00|00|00|00|00|X5|X5|X5|X5|00|00|00|00|
|0x00000040|00|00|00|00|3F|80|00|00|00|00|00|00|3F|80|00|00|
|0x00000050|00|00|00|00|3F|80|00|00|00|00|00|00|3F|80|00|00|
|0x00000060|00|00|00|00|3F|80|00|00|00|00|00|00|3F|80|00|00|
|0x00000070|00|00|00|00|3F|80|00|00|00|00|00|00|3F|80|00|00|
|0x00000080|4D|41|52|4B|00|00|00|04|00|00|00|00|53|54|52|47|
|0x00000090|X6|X6|X6|X6|X7|X7|X7|X7|X7|X7|X7|X7|X7|X7|X7|X7|
|0x000000A0|X7|X7|X7|X7|X7|X7|X7|->|
    
```
- X1 = (?) Possibly file version? I've only ever seen `01` at this value.
- X2 = (?) File Length; in this case, it would have the value `A8`.
- X3 = place
- X4 = place
- X5 = (int32) Number of samples in the associated `.bfwav` file.
- X6 = (?) String length
- X7 = (u8 string) String of `.bfwav` file it is associated with.
```
    
  To edit this, I suggest using the website `Hexed.it`, but any hex editor should work.

## .bars
  These files contain, for Splatoon, `.bfwav` sound effects, and the `.bameta` data files. These can be opened with Switch Toolbox.
## .bfres
  These are the files that contain models, textures, and animations. These can be opened with Switch Toolbox.
## .msbt
  These are basically complicated text files for things in the game like dialogue, rank display, level display, etc. These can be opened with DJMrTV's Spoon Text Edit tool.
## .bflyt
  These are the HUD/UI layout files. These can be opened with Switch Toolbox.
## .bflim
  These are image files, used for textures. This can be opened using Switch Toolbox.
## .kcl
  This file is the collision file for the related model. These can be created using Wexos' Toolbox, and can be viewed in Switch Toolbox.
## .params
  These are the files that deal with parameters in things like weapons, abilities, etc. These can be opened with Notepad or TextEdit, or the text editor in Switch Toolbox, although it cannot be edited with Switch Toolbox.
## .btsnd
  This is the audio file for Splatoon, which plays when you start the game. I do not know how to open this file yet.
## .bffnt
  These deal with the fonts for Splatoon. These can be opened with Switch Toolbox.
## .(animation  files)
  place
## PlazaNpcPreset.bin

This is the general byte layout for the player's data in the Plaza. Here is the general data layout as shown in a hex editor.

|Address|00|01|02|03|04|05|06|07|08|09|0A|0B|0C|0D|0E|0F|
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|0x00000000|FF|FF|FF|FF|01|EF|00|ZZ|00|ZZ|00|ZZ|00|ZZ|00|ZZ|
|0x00000010|00|ZZ|00|ZZ|00|ZZ|00|ZZ|00|ZZ|00|00|00|00|00|00|
|0x00000020|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|
|0x00000030|00|00|00|00|GB|GB|GB|GB|SC|SC|SC|SC|EC|EC|EC|EC|
|0x00000040|WI|WI|WI|WI|WM|WM|WM|WM|WS|WS|WS|WS|SW|SW|SW|SW|
|0x00000050|TI|TI|TI|TI|HG|HG|HG|HG|00|00|00|00|00|00|00|00|
|0x00000060|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|
|0x00000070|CG|CG|CG|CG|00|00|00|00|00|00|00|00|00|00|00|00|
|0x00000080|00|00|00|00|00|00|00|00|00|00|00|00|SG|SG|SG|SG|
|0x00000090|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|00|
|0x000000A0|00|00|00|00|00|00|00|00|00|00|00|00|LV|LV|LV|LV|
|0x000000B0|00|00|00|00|FF|FF|FF|FF|FF|FF|FF|FF|00|00|00|00|
|0x000000C0|FF|EF|EF|EF|FF|FF|FF|FD|FF|FF|FF|FF|00|00|EF|EF|
|0x000000D0|NP|NP|NP|NP|00|00|00|00|00|04|EF|EF|P1|P1|P1|P1|
|0x000000E0|P2|P2|P2|P2|P3|P3|P3|P3|P4|P4|P4|P4|

```
00 ZZ = (u16 string) Letters for display name
GB = (int32) Gender
SC = (int32) Skin Color
EC = (int32) Eye Color
WI = (int32) WeaponSet ID
WM = (int32) Weapon Main ID
WS = (int32) Weapon Sub ID
SW = (int32) Weapon Special ID
TI = (int32) Turf Inked with the weapon equipped
HG = (int32) Headgear ID
HB = (int32) Headgear brand ID
HM = (int32) Headgear Main Ability ID
H1 = (int32) Headgear Sub Ability 1 ID
H2 = (int32) Headgear Sub Ability 2 ID
H3 = (int32) Headgear Sub Ability 3 ID
CG = (int32) Clothes ID
CB = (int32) Clothes brand ID
CM = (int32) Clothes Main Ability ID
C1 = (int32) Clothes Sub Ability 1 ID
C2 = (int32) Clothes Sub Ability 2 ID
C3 = (int32) Clothes Sub Ability 3 ID
SG = (int32) Shoes ID
SB = (int32) Shoes brand ID
SM = (int32) Shoes Main Ability ID
S1 = (int32) Shoes Sub Ability 1 ID
S2 = (int32) Shoes Sub Ability 2 ID
S3 = (int32) Shoes Sub Ability 3 ID
RN = (int32) Rank
LV = (int32) Level
NP = (int32) Plaza NPC number
P1 = (float) Ink Color Param Red
P2 = (float) Ink Color Param Green
P3 = (float) Ink Color Param Blue
P4 = (float) Ink Color Param Alpha
```

