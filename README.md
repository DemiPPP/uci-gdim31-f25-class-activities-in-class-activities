# in-class-activities
## Devlogs
### W1
If I move the Camera out of the CatObject in the Hierarchy, the camera will stay fixed in the place and won't move with the cat. This happens because the camera is no longer the child object of cat, so it won't move together with the cat object. When I tried to build the webGL package and upload to itch.io. I met one problem that is my unity doesn't have the WebGL build module installed.

### W2
We use float for r, g, and b because RGB color values range from 0 to 1 and need decimals to create smooth color changes. Ints only store whole numbers, bools are just true or false, and strings hold text, so they are not suitable. The _bounces variable is an int because bounce counts are whole numbers; there is no such thing as half a bounce, and other types do not work for counting. The errors I encountered taught me that plain decimal numbers in C# are double by default, so I need to add an "f" after the number when assigning it to a float variable. I also found many lines missing semicolons, and these syntax mistakes stop the code from compiling.
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 