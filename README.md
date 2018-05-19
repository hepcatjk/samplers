# samplers
A collection of Samplers for Quasi-Monte Carlo methods

## Samplers by [Leonhard Gruenschloss](http://gruenschloss.org/)

### Halton
A very fast C++ implementation of the Halton sequence that supports both Faure-permutations and random digit permutations. Together with the component (i / N) this will yield a Hammersley point set. Comes with a Python script to generate optimized code for arbitrary dimensions. It also includes code to enumerate samples in a 2D domain, for example pixels.

### LFSR
A C++ implementation of the small linear feedback shift registers (LFSR) for use in a Markov chain quasi-Monte Carlo context, as described in S. Chen, M. Matsumoto, T. Nishimura, and A. Owen: New inputs and methods for Markov chain quasi-Monte Carlo.

### Sobol-sequence
A C++ implementation of a simple and fast random-access Sobol'-sequence generator, based on the direction numbers published in S. Joe and F. Y. Kuo: Constructing Sobol sequences with better two-dimensional projections. (come in single and double double-precision floating-point)