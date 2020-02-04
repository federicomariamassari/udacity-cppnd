[Table of Contents](https://github.com/federicomariamassari/udacity-cppnd/blob/master/README.md) | Next: [P2 System Monitor]()

# C++ Nanodegree: P1 Build an OpenStreetMap Route Planner
__Federico Massari__

## Overview
This program uses [__A* search__](https://en.wikipedia.org/wiki/A*_search_algorithm) to find the shortest travelled distance between two popular landmarks in Ulaanbaatar, Mongolia: the Circus' Square (Циркийн талбай) and Chinggis' Square (Чингисийн талбай), where the Parliament is located.

The circus is a jagged-edged, circular building in the South-Western corner of the map, and its position is identified by the red marker, the starting point. The Parliament is a large, square-shaped structure in the North-Eastern region of the map, and it is identified by the green marker, the end point. The optimal path might look a bit convoluted, but this is because footways are excluded from the search.

<td align="center"><img align="center" src="./img/route.png" height=400 width=400/></td>

## Map area
Ulaanbaatar, Mongolia
- Ulaanbaatar city centre: https://www.openstreetmap.org/export#map=15/47.9171/106.9183

## How to run the program

Clone the repository and navigate through the `build` directory on Terminal (macOS) or Command Prompt (Windows):
```bash
% git clone https://github.com/federicomariamassari/udacity-cppnd.git
% cd ./udacity-cppnd/projects/p1/build
```

Run the Unix executable `OSM_A_star_search` specifying the path of the file:
```bash
% ./OSM_A_star_search -f ../data/ulaanbaatar_city_centre.osm
```

Enter the coordinates of the starting and end nodes: (27; 17) is the position of the circus, (66, 75) that of the Parliament.
```
Enter four coordinates in [0; 100] separated by space or return:
27 17 66 75
```

Terminate the program by pressing `CTRL+C` if needed.
