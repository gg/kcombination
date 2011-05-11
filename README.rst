kcombination
============

Prints the k-combination at a specified position.

See this `wikipedia entry`_ for details.

Example
~~~~~~~
The following will print the 5-combination at position 72::

  $ ./kcombination 5 72
  8 6 3 1 0 

Boost
~~~~~
kcombination depends on Boost_ (``boost::math::binomial_coefficient<T>`` to
calculate binomial coefficients`, and  ``boost::lexical_cast`` to parse input
strings into integers).

Compiling
~~~~~~~~~
On Linux::

  $ g++ kcombination.cc -o kcombination -I /path/to/boost


.. _Boost: http://boost.org
.. _wikipedia entry: https://secure.wikimedia.org/wikipedia/en/wiki/Combinatorial_number_system#Finding_the_k-combination_for_a_given_number
