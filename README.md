# in-class-activities
## Devlogs
### W1
If I move the Camera out of the CatObject in the Hierarchy, the camera will stay fixed in the place and won't move with the cat. This happens because the camera is no longer the child object of cat, so it won't move together with the cat object. When I tried to build the webGL package and upload to itch.io. I met one problem that is my unity doesn't have the WebGL build module installed.

### W2
We use float for r, g, and b because RGB color values range from 0 to 1 and need decimals to create smooth color changes. Ints only store whole numbers, bools are just true or false, and strings hold text, so they are not suitable. The _bounces variable is an int because bounce counts are whole numbers; there is no such thing as half a bounce, and other types do not work for counting. The errors I encountered taught me that plain decimal numbers in C# are double by default, so I need to add an "f" after the number when assigning it to a float variable. I also found many lines missing semicolons, and these syntax mistakes stop the code from compiling.

### W3
## Activity 1: methods discussion
1. 'GetResponse'
    - input: `int friendshipLevel`, `bool knowsSecret`;
    - output: `string`, the character's dialogue response.
2. 'SetLightDimness'
    - input: `float sanityLevel` (0 – 100)
    - output: `void`, because the method changes the light directly.
3. 'DidPlayerHitBeat'
    - input: `float keyPressTime`
    - output: `bool`
 ## Activity 2:Components & classes metaphor
 A class is like a blueprint for a house. The blueprint describes what a house can have and do, but it is not itself a house in the scene. A Component is like one actual house built from that blueprint. Member variables are the house’s traits, such as its color or number of floors. Methods are the actions it can perform, such as opening a door or turning on a light. Multiple houses can be built from the same blueprint, just as multiple Components can be created from one class.
## Activity 3: methods coding activity
Every time the fast ball bounces, we multiply its color by 1.5. This value stacks on each collision. Repeated multiplication pushes the RGB color values far above 1, so the ball becomes extremely bright after many bounces.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 