# ExtendedRuleTile

![alt text](https://github.com/FaithGamer/ExtendedRuleTile/blob/master/header.png?raw=true)

Better rule tile for Unity allowing bigger pattern than tile size.
Theses script are a copy from the original Unity Package, but with some twist.

Once added in your project, you can create an Extended Rule Tile in the create asset menu.
It will behave just like the Rule Tile asset but allow for a new Output: Extended.

Extended output will allow you to add multiple sprites that will be choosen according to the tile position in the tile map.
Make sure that ExtendDimension.x * ExtendDimension.y  == Size.

ExtendDimension is the dimension of your pattern in tile size. Size is the number of sprite.

This behaviour allow you to draw your repeating tile pattern bigger than the size of one tile.

Known Bugs:

- The extend neighbor option is broken for unkown reasons.
- There might be other unkown problems due to some lines of the original code being commented away for simplicity.

To do:

- Size should automatically be adjusted depending to ExtendDimension.
- Somehow it would be nice to automate the creation of each individual rule and the filling each sprite by hand...
