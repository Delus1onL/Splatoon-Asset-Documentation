# File types

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

![jkt3](https://github.com/Delus1onL/Images/blob/main/bametaExample.png)
    
```
- X1: Possibly file version? I've only ever seen `01` at this value.
- X2: File Length; in this case, it would have the value `B0`.
- X3: place
- X4: place
- XXXX: Number of samples in the associated `.bfwav` file.
- X(first in long line of Xs): String length
- XXX....: String of `.bfwav` file it is associated with.
```
    
  To edit this, I suggest using the website `Hexed.it`, but any hex editor should work.

## .bars

## .bfres

## .msbt

## .bflyt

## .bflim

## .kcl

## .params

## .btsnd

## .bffnt

## .(animation  files)
