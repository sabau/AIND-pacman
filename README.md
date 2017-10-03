https://inst.eecs.berkeley.edu/~cs188/fa10/projects/search/search.html

python pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=euclideanHeuristic

python pacman.py -l mediumScaryMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs
python pacman.py -l mediumScaryMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
