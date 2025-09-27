# Texas-Game-Jam-2026

Warning: Don't overwrite files that aren't yours when you save. Save it into a new file. To chain files together, we can use #include for Lua code, and data carts.

Data Carts for music and art:  
-- load sprites and map from "art.p8"  
reload(0x0000, 0x0000, 0x2000, "art.p8") -- sprites + map  

This way we can have:  
game.p8   (code only, no sprites)  
art.p8    (contains sprites + map)  
music.p8  (contains music)   

How to have the same game version with Github:
- Download Github Desktop 
- In Pico-8, type "folder" in console (escape key) to find where your game runs
- Clone the repository in that folder
- Type "ls" to see what your folder / directory looks like
- Type "cd Texas-Game-Jam-2026" in Pico-8 console
- Type "load game.p8"
- Type "run"
