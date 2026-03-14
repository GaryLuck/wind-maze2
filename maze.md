# Maze Explorer

Interactive web-based maze generator and solver with animated pathfinding visualization.

## Architecture

- **Frontend-only logic**: All maze generation and solving runs client-side in the browser
- **Canvas rendering**: Uses HTML5 Canvas for performant grid rendering
- **Single html file**: Facilitates download and sharing of the game
- **client side only**: DO NOT TEST WITH A SERVER

## Features

- The maze consists of a grid of open squares and black squares
- black squares are walls, and open squares are a path
- when generating a maze, the computer drills a path through the black squares
- Three maze generation algorithms: Recursive Backtracking (DFS), Prim's, Kruskal's
- Three solving algorithms: BFS, DFS, A*
- Animated step-by-step solution visualization
- Adjustable animation speed
- Three maze sizes (Small, Medium, Large)
- Green start cell, red end cell
- Explored cells shown in purple, solution path in yellow
- Play/Pause/Reset controls
- Algorithm info panel and legend
