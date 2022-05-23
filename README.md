## Target:
- DFS (Depth First Search)
- BFS (Breadth First Search)
- UCS (Uniform Cost Search)
- A*
- Heuristic

## Prerequisites:
- [Python 2.7.0](https://www.python.org/download/releases/2.7/)

## Run
```python pacman.py```

```python pacman.py --layout testMaze --pacman GoWestAgent```

```python pacman.py --layout tinyMaze --pacman GoWestAgent```

```python pacman.py -h```

```python pacman.py -l tinyMaze -p SearchAgent -a fn=dfs```

```python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs```

```python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=dfs```

```python autograder.py -q q1```

```python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs```

```python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5```

```python eightpuzzle.py```

```python autograder.py -q q2```

```python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs```

```python pacman.py -l mediumDottedMaze -p StayEastSearchAgent```

```python pacman.py -l mediumScaryMaze -p StayWestSearchAgent```

```python autograder.py -q q3```

```python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic```

```python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem```

```python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem```

```python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5```

```python pacman.py -l testSearch -p AStarFoodSearchAgent```

```python pacman.py -l trickySearch -p AStarFoodSearchAgent```

```python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5```

```python pacman.py -l bigSearch -p ApproximateSearchAgent -z .5 -q``` 
