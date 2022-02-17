# Sobol-sequence

**Presentation**

Implementation of Sobol sequence generator up to 21201 dimensions using the directions numbers from https://web.maths.unsw.edu.au/~fkuo/sobol/.

**Files**

Sobol-sequence.ipynb: the main files

new-joe-kuo-6-21201.csv: the files containing the 21201 direction numbers

**Example**

Generation of 512 points in 21201 dimensions

*sampler = sobol_generator(21201)
sample = sampler.sample(512)*

**Images**

Example of 512 points in dimension 1, 2, 9784 ans 10764

![This is an image](https://github.com/aalp75/Sobol-sequence/blob/main/dim1-dim2.png) ![This is an image](https://github.com/aalp75/Sobol-sequence/blob/main/dim9784-dim10764.png)


**References**

*Constructing Sobol sequences with better two-dimensional projections*, S. Joe and F. Y. Kuo (2008)

*Monte Carlo methods in financial engineering*, Paul Glasserman

**Author**

aalp75

Last update: 17/02/2022
