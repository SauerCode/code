# Your solution to E28

Performance analysis, comparing all three designs you have implemented
instead of Design 1 with Design 5 as the book says.

To do this evaluation (of E26, E28-E30), for each design create random instances and
then call each method many thousands of times, and then find the elapsed time in milliseconds
for the fixed number of iterations. Make sure that your program runs each time for about
10 seconds, so you get a good measure of performance. Test each method separately.
Run each version several times to ensure that your results are consistent and use
the median result as your definitive result, plus give the maximum and minimum.

| Design | How cartesian coordinates are computed | How polar coordinates are computed | aklkl |
| --- | --- | --- | --- |
| Design 2: Store polar coordinates only 
---|| Computed on demand, but not stored| Simply returned |
| Design 3: Store cartesian coordinates only | Simply returned | Computed on demand, but not stored |
| Design 6: Interface with designs 2 and 3 as classes implementing it. | Depends on the concrete class used | Depends on the concrete class used |
