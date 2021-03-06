# A* Algorithm Visualization

An algorithm to visualize [A*](https://en.wikipedia.org/wiki/A*_search_algorithm) search algorithm working.

The heuristic used is Manhattan Distance (or *Taxicab Geometry*, more [here](https://en.wikipedia.org/wiki/Taxicab_geometry) and [here](https://xlinux.nist.gov/dads/HTML/manhattanDistance.html)).

For the version with diagonal movement included, check [here](https://github.com/EduardoLisboa/AStar-Visualization/tree/diagonal_movement).

For the required libraries, see the [requirements](../master/requirements.txt) file.

For a similar visualizator, for the Dijkstra algorithm, go [here](https://github.com/EduardoLisboa/Dijsktra-Visualization).

### To run from the terminal, use the command:
* Windows:
```
python main.py
```
* Linux or Mac:
```
python3 main.py
```
------
## Instructions:
When the program starts, the first left click from the mouse will be the starting point, the second click will be the ending point and all other clicks will be considered barriers.

Clicking with the right mouse button will erase the point you clicked, including start and end.

You can hold the mouse button and drag on the screen both when drawing and erasing.

If you want to clear the entire grid, press **"c"** on your keyboard.

If you want to generate a random maze, press **"r"** on your keyboard.

Press the **spacebar** to start the algorithm. When it is finished, you can press **"c"** or **"r"** and try again.
