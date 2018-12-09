# Parallel TSP

Ariel Flaster and Stella Wroblewski

Creating a parallel solution finder to the traveling salesperson problem


## For the solution to the original problem type `make`
## And run `./tsp`

We tested this solution with different numbers of cores. We ran with the parameters of a pop size of 6, mutation rate of 0.4 and tested the number of cores variable.

| Cores        | Time           | Result |
| ------------- |:-------------:|----------:|
| 1      | 1 min 50s | 18728.9 |
| 2      | 50s | 18581.6 |
| 4 | 1 min 20s | 18887 | 
| 8 | 50s | 19544 | 


As you can see, 2 cores ran twice as fast as 1 core, which shows our parallelization working :)

However, 4 cores takes longer than 2 cores, but 8 is much shorter than 4, and comparable to 2 cores. Odd.
