# Lab 3

The goal of this laboratory is to solve an algorith with complexity of n^2-1 with a path search algorithm. 
I've implemented A* alg. that The A* algorithm finds the shortest path between a start and a goal node in a graph by combining known costs (distance traveled) and estimated costs (heuristics) to explore nodes efficiently. It uses the function f(n)=g(n)+h(n), where g(n) is the current path cost, and h(n) is the estimated cost to the goal.

# Results

With this set of variables, I obtained:

PUZZLE_DIM = 5 
RANDOMIZE_STEPS = 100_000

| Path len | Number of calls to function "do_action" |
|-------------|--------------|
| 18        | 142371        |


# Credits
Finding a great way to develop the A* algorithm I discuss with @luca-bergamini.