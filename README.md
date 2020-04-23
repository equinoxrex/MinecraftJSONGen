# Minecraft JSON Genenrator
 A json generator for minecraft model and blockstate files.
 
 Data files such as loot tables and recipes coming soon.
 
## Installation Instructions
 1. Place all the .py files inside your mods `resources` folder.
 2. change the `modID` variable inside `DefaultConfig.py` to your mod id.
 3. Run `GenAssets.py` to open the generator.

## Using the Generator
 The generator has many options for different block types such as stairs, slabs, and walls.
 
 The only option selected by default is the main block, however this is changeable in `DefaultConfig.py`.
 
 #### Block
  With this selected the generator will create files for a block with the same name as the value in the entry box.       
  The drop-down menu next to it will determine the type of block created, for exampleif `Three Way Rotatable (Axis)`
  is selected it will generate files for a pillar type block, while if `Not Rotatable - Cube Column` it will
  generate files for a block that has a different top and bottom texture like a pillar, but is not rotatable.
  The `No Block - 2D Item Only` option will not generate a block model or blockstate file
  (I know this is in the block option dropdown but it wasthe best place for it)
  
 
 #### Slabs, Stairs, Walls, etc.
  If any of these options are selected the generator will create files for these blocks based upon the entered name.
  **You do not have to append `_stairs` or whatever to the name it will do that for you**.
  This allows you to create multiple blocks with the same base name while only running the generator once, 
  e.g. `oak_boards`, `oak_board_slabs`, and `oak_board_stairs` (The generator de-pluralizes it for you where needs be).
 
## Collections
 Collections are commonly used groups of blocks, if one of these is selected it will ignore the other options.
 
 #### Wood Collections
  Creates a wood set based on the input name, which would just be the name of the wood without any additions.
  This currently includes Logs, Stripped Logs, Wood, Stripped Wood, Leaves, Planks, Slabs, and Stairs.
  
  
  
Contact: `@Equinox#6661` on Discord
