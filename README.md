# astar
A* Algorithm
## Introduction
As part of a javascript 2D board game project, implementation of the A * algorithm.
___
## Use
path.app() return :
* true if there is no path
* false if there is a path

```Javascript
// Create an instance of Astarpathfinding with as parameter a map object and a start box and an arrival box
// This notation is specific to my initial project
var path = new Astarpathfinding (map, map.board[xa][ya], map.board[x][y]);                            
path.app();
```
___
## Ressources
* [Wiki - Algorithme A* - French](https://fr.wikipedia.org/wiki/Algorithme_A*)
* [Wiki - A* search algorithm - English](https://en.wikipedia.org/wiki/A*_search_algorithm)
* [A* Pathfinding Tutorial - French](https://www.youtube.com/watch?v=0MoYR35yrBw)
* [A* Pathfinding Tutorial - English](https://www.youtube.com/watch?v=KNXfSOx4eEE)
* [Coding Challenge 51.1: A* Pathfinding Algorithm - English](https://www.youtube.com/watch?v=aKYlikFAV4k)
* [Brian Grinstead : A* Search Algorithm in JavaScript - English](https://briangrinstead.com/blog/astar-search-algorithm-in-javascript/)
* [qiao.github.io - English](https://qiao.github.io/PathFinding.js/visual/)
___
## TODO
..* Diagonals
..* Make the application independent