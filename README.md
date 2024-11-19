I developed two algortihms to see and compare different functions that try to solve the same problem. 
The first alghoritm is a Evolutionary Alghorithm and the second is a Simulation Anelling:

## Evolutionary Algorithm
This is a slow but more accurate algorithm, compared with the next one.
Mutation function: 
- Inversion mutation

Selection of parents:
- Tournament selection

Crossover functions:
- Order crossover
- Inver over

### Result obtained

Parameters choose:
```
POPULATION_SIZE = 100
GENERATIONS = 1000
MUTATION_RATE = 0.1
TOURNAMENT_SIZE = 5
OFFSPRING_SIZE = 5
```

With the following parameters I got:

|  Country |  Final Cost |  Number of calls |  
|---|---|---|
| Italy  | 4174.93  |  1041167 | 
|  China | 337059.68  |  1039907 |  
|  Russia | 57789.41  |  1041212 |  

## Simulated Annealing
This is a fast but not accurate algorithm, compared with the previous one.

Tweak function:
- single_mutation

### Result obtained

Parameters choose:
```
NUM_CITIES = len(DIST_MATRIX)
MAX_STEPS = 10000
INITIAL_TEMPERATURE = 1000
COOLING_RATE = 0.985
```

With the following parameters I got:

|  Country |  Final Cost |  Number of calls |  
|---|---|---|
| Italy  | 10135.55  |  1061169 | 
|  China |  969329.42 |  1059909 |  
|  Russia | 323858.62  |  1061214 |  
