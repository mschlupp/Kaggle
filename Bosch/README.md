# Quality insurance in Bosch production

* first step will a multidimensional gaussian p-value analysis to reduce the number of observations
* analyse the remaining observations to better predict failures
	* feature reduction algorithm(?)
	* MVA training

# Some facts:

* We have 1,183,747 training observations:
	* 99.42 % are perfectly fine (background).
	* 0.58 % are actually failing.

* In the numeric data, there are 968 features

* There are 1,183,748 predictions to be made. 	

## Numerical:

* L0 has 24 stations and with 168 features
* L1 has 2 stations 513 features
* L2 has 3 stations with 42 features
* L3 has 21 stations 245