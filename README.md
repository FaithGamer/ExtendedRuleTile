# ExtendedRuleTile
Better rule tile for Unity allowing bigger pattern than tile size

Once added in your project, you can create an Extended Rule Tile in the create asset menu.
It will behave just like the Rule Tile asset but allow for a new Output: Extended.

Extended output will allow you to add multiple sprites that will be choosen according to the tile position in the tile map.
Make sure that ExtendDimension.x * ExtendDimension.y  == Size.

ExtendDimension is the dimension of your pattern in tile size. Size is the number of sprite.

This behaviour allow you to draw your repeating tile pattern bigger than the size of one tile.
