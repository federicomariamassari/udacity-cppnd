[Table of Contents](https://github.com/federicomariamassari/udacity-cppnd/blob/master/README.md) | Next: [P2 System Monitor]()

# C++ Nanodegree: P1 Build an OpenStreetMap Route Planner
__Federico Massari__

## Overview
This program uses the __A* search algorithm__ to find the shortest travelled distance between two popular landmarks in Ulaanbaatar, Mongolia: the Circus' Square (Циркийн талбай) and Chinggis' Square (Чингисийн талбай), where the Parliament is located. The circus is a jagged-edged, circular building in the South-Western corner of the map, and its position is identified by the red marker. The Parliament is a large, square-shaped structure in the North-Eastern region of the map, and it is identified by the green marker. The optimal path might look a bit convoluted, but this is because footways are excluded from the search.


<td align="center"><img align="center" src="./img/route.png" height=400 width=400/></td>

## Map area
Ulaanbaatar, Mongolia (City Centre)

## How to run the program

Run the Unix executable on Terminal or Command Window via:

```bash
cd ./build
./OSM_A_star_search -f ../data/ulaanbaatar_city_centre.osm
```
