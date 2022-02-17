# Sobol-sequence

Implementation of Sobol sequence generator up to 21201 dimensions using the directions numbers from https://web.maths.unsw.edu.au/~fkuo/sobol/.

**Presentation**

The generator is implementing using class.

Method sobol_mat is used to generate the matrix directions.
Method sobol_pts is used to generate the points in every directions.
Method load is used to load the directions numbers (for example s = 7 and a = 28 gives [1,0,1,1,1,0,0,1])

Several utility functions are used:

binary_aray(n,b): transform an integer into a list of his base b representation
rightmost_zero_index: return the rightmost zero index is the base reprensentation compare to the rightmost index ([b-1,b-1,...,b-1] will return len(a)+1)
next_bary(a,b): increment of 1 the base b representation


**Files**

Sobol-sequence.ipynb: the main files.

new-joe-kuo-6-21201.csv: the files containing the 21201 direction numbers.

**Example**

Generation of 512 points in 21201 dimensions:

*sampler = sobol_generator(21201)*

*sample = sampler.sample(512)*

Give the folowing distribution over the dimensions 1, 2, 9784 ans 10764:

![This is an image](https://github.com/aalp75/Sobol-sequence/blob/main/dim1-dim2.png) ![This is an image](https://github.com/aalp75/Sobol-sequence/blob/main/dim9784-dim10764.png)


**References**

*Constructing Sobol sequences with better two-dimensional projections*, S. Joe and F. Y. Kuo (2008).

*Monte Carlo methods in financial engineering*, Paul Glasserman.

**Author**

aalp75

Last update: 17/02/2022
