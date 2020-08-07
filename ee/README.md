## EE (Comp. Sci)

- `POSSIBLE` HM Type system | investigating time/space complexity of algorithm W maybe?
  - [type inference alg in python](https://eli.thegreenplace.net/2018/type-inference/)
  - [a haskell implementation, step-by-step](https://github.com/wh5a/Algorithm-W-Step-By-Step/blob/master/AlgorithmW.pdf)
  - [HM wiki](https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system)
  - HM space/time complexity is actually exponential (!) [check the answer here](https://stackoverflow.com/questions/22060592/growth-of-type-definition-in-sml-using-hindley-milner-type-inference)

- `POSSIBLE` How does the number of neurons in the hidden layers of a 4-layer neural network for recognizing digits affect the performance of the neural network? Or maybe even checking if odd vs even number of neurons affects performance? or maybe accuracy? ALSO maybe checking the time/space complexity of neural network algorithms?
  - [3b1b: But what is a neural network?](https://www.youtube.com/watch?v=aircAruvnKk)
  - [gradient descent](https://www.youtube.com/watch?v=IHZwWFHWa-w)
  - maybe look for a better "hyperparameter" to tweak, maybe cost function? (sigmoid vs reLu?)

- Dynamic programming (dp) *using* Markov decision processes (not even sure about this, lots of research needed)
  - see Howard's Dyamic Programming and Markov Processes (1960)

- NLP (strictly text-based)/text generation with Markov processes (very cool stuff, and also very doable, but a bit more research needed, of course)
  - see that one post on codinghorror about this stuff. plus see source code for @Mimic by Toby Larone

- Maybe investigation on different load factors for hashmap implementations, or hashing algorithms for hashmap implementations? i.e how changing them affects the performance of the hashmap.
  - useful for implementing faster hashmaps :/
  - see chapter on hashmap implementation in CraftingInterpreters, Robert Nystrom

- Investigation into optimizing (a set of? sorting/searching/etc.) algorithms using dynamic programming (recursive -> memoized / bottom up) / Investigating recursive top-down approach in algorithms vs bottom-up dp/incremental (im not sure what the term was) approach?
  - show benefits of dp.
  - the lecture on dp by Eric Domaine (on YT, the 6006 MIT Algorithms class)
  - (2nd one) same as above (difference is that in the above you're just going from one algorithm to "faster versions" of the same algorithm. in this one, you're comparing the "faster versions" to see which ones are more performant.

- **`LIKELY`** Evaluating the performance of BEAM processes and how elixir and the Erlang RTS leverage them to allow performant, scalable, distributed and fault-tolerant systems.
  - Relevant because Moore's law is failing and processors are reaching their limits, which means distributed environments are going to become more and more common due to performance and cost benefits. This means erlang/elixir is going to become more relevant.
  - https://blog.stenmans.org/theBeamBook/#CH-Processes
  - https://github.com/erlang/otp/tree/master/erts/emulator/beam
  - https://medium.com/m/global-identity?redirectUrl=https%3A%2F%2Fblog.lelonek.me%2Felixir-on-erlang-vm-demystified-320557d09e1f
  - [making reliable distributed systems](https://erlang.org/download/armstrong_thesis_2003.pdf)
  - https://erlang.org/doc/search/
  - http://blog.erlang.org/beam-compiler-history/
  - [SO question that also compares process speeds of in different languages](https://stackoverflow.com/questions/2708033/technically-why-are-processes-in-erlang-more-efficient-than-os-threads?noredirect=1&lq=1) but remember that its quite old!
  - https://medium.com/flatiron-labs/elixir-and-the-beam-how-concurrency-really-works-3cc151cddd61
  - concurrent FIFO queue algorithms [paper](https://www.cs.rochester.edu/~scott/papers/1996_PODC_queues.pdf) READ this and make use of it.
  - for discussion, this paper on the Reduceron, a processor optimized for running parallel processes and functional programming. https://www.cs.york.ac.uk/fp/reduceron/jfp-reduceron.pdf. Website: https://www.cs.york.ac.uk/fp/reduceron/.
