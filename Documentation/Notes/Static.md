# Static

## Etc

### PlayerInfo.szs

`PlazaNpcPreset.bin`

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
00 ZZ = (u16) Letters for display name
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
