#### `math`
Explain why alg efficiency is important.<br>
Talk about how alg efficiency is measured/described [asymptotic analysis]<br>
talk about how asymptotic analysis only showws how algs scale, which means algs with same time complexities (worst AND avg) could still be quite different in terms of actual running time because asymptotic analysis doesn't consider the extra *c* constant. give example of this.<br>
Then take two algs with same time complexity, run tests, gather data.<br>
Graph it. See if they are both roughly the same in efficiency or not.<br>
Then, using graph data, find the actual *c* value for both.<br>
If one is better than the other, say that.<br>
If (hopefully) there are *intervals* of input size where one is better than other, highlight those.<br>
If there are notable local maxima/minima, highlight those.<br>
Analyse graphs to find a function for each alg's avg running time.<br>
If useful, differentiate each of these functions and find notable maxima/minima. See if it matches what is seen in the graph.<br>

- use statistics to check if space needed by algorithms has any effect on the running speed of algorithms. Remember, we're not looking at asymptotic space/time complexities here, we're looking at actual running times of algorithms compared to the space needed. IV: space, DV: running time. running time calculated using benchmarks, space calculated beforehand based on input size + auxiliary space.
  - https://stackoverflow.com/questions/11810503/running-time-complexity-vs-space-complexity-in-sorting

- take two similar algorithms with similar time complexities, and then run tests and graph their time complexities on my computer. then, "derive" their time complexity, and analyse the graphs to see which algorithm is better for which intervals of input size (maybe i can make use of differential calculus (optimization) here!). obviously, i'll also run analysis for the correlational coefficient, and put the graphs together for comparison, make some other graphs and so on to make it a "proper" statistical analysis paper. ish.
  - [big o cheatsheet!](https://www.bigocheatsheet.com/)
  - [examples of algos with complexities on SO](https://stackoverflow.com/questions/1592649/examples-of-algorithms-which-has-o1-on-log-n-and-olog-n-complexities)
