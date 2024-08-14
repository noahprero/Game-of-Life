# Description
This custom iteration of John Conway's Game of Life introduces new types of cells, which bring about new and unique patterns that aren't possible in the ordinary game.

# Cells
- Alive cell (black): This is the same cell from the original game. It follows all the basic rules of the Game of Life.
- Trapper cell (green): When other cells come into contact with the Trapper cell, they freeze in place and become a Trapper as well.
- Voyager cell (purple): This cell travels in a straight line towards the right of the screen.
- Builder cell (blue): By opening the menu, you can choose the preset that the builder will make. These presets consist of formations from the original game along with new formations discovered using the previously stated new cells. The Builder cell is not affected by the Trapper cell.

# Controls
```
MENU - Opens build gallery
START/STOP - Starts and stops the game
CLEAR - Clears the grid
NEXT - Run the game for one iteration
RAND - Initialize the grid to a random formation
GRAVITY - Affect the cells with gravity (Voyager stays still, Alive acts as a solid, and Trapper acts as a liquid)