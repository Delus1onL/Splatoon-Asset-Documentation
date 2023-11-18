# Splatoon
Heres what I understand about Splatoon, through what I’ve learned, and what others have learned. 

# Music
Yeah, they’re just .bfstm files. They are standard to create/convert to bcstm, except for bfstm files that have multiple streams. Someone suggested a different program to make those, but I forgot who and what. Most sound effects are .bars (or another format I dont remember right now) in the Sound.Pack file, except for the “BREAKING NEWS” sound notification, which is .bfstm like the main soundtracks. Not much more to say about these.

# Models

Basic game models are in .bfres file format. This stores the model, bones, and its textures. Textures are defined as “alb” (color), “nrm” (bump), “spm” (color used for material properties/where material shows up), “tcl” and another one starting with “t” (these deal with where the ink color/other changeable colors show up on a white-color scale for one file type, and then a color-black scale for the other).

# Paint

For weapons, this is basically textures on top of models’ original textures. However, ink, as far as I can tell, calls on some graphics system a lot, which I guess makes sense but still.

# Static.Pack

This holds param files that deal with things like ink colors, camera location, object location, object scale, weapon actions, etc. Thats why edited static.pack online is very risky, and almost a guaranteed ban. 

# System.pack

This holds what I’ve heard called “special params.” Editing this also leads to ban from what I understand, but this can let you do things like start up the game on any scene, like lobby or a weird version of battle dojo instead of news. This has a lot of old params, but a lot of them do not work without rpx modification. Photograph mode is the only thing that works, at least for the modern version of Splatoon.

# Boss files

These deal with map rotations, and splatfests. TGM has a great video showing how to edit the boss files to make your own splatfest.

# Gambit.rpx

Recently I started messing around with this more. Fun. I’m using Cemu to look at the PowerPC assembly and the RAM, while I use rpl2elf and wiiurpxtool to decompress and compress the rpx file. I have tried some things from what others have done for Splatoon. I do not feel comfortable yet sharing this information in detail. 

# Text Files

Not much here. Pretty straight forward. .msbt are weird text files for Splatoon that you can edit. 

# Layout.pack

This deals with HUD and/or UI. You can edit how the screen looks with whatever pngs you so choose… to an extent. 

# Maps

Maps are identified in the boss files by IDs. The game loads the appropriate model by string. If you patch the string in RAM for an ID (ex: Urchin’s string, with ID #0, gets replaced by the shooting range’s string, which now has ID #0), when it loads urchin, it actually loads shooting range. (TGM and cemu patches showed that).
