BinomSums
=========

*BinomSums* is a package, for the computer algebra system Maple,
providing functions to handle multiple binomial sums.
It implements the algorithms described in the paper
(soon on the arXiv):

> A. Bostan, P. Lairez, and B. Salvy, “Multiple binomial sums”


Warning
-------

*This is a very preliminary implementation.*
It contains bugs very probably. It is provided *as is*.

Do not hesitate to submit bug report of pull requests.

License
-------

*BinomSums* is released under the terms of the MIT license.

See the file LICENSE for more information.


Installation
------------

1. Execute ```make```, this produces the file ```binomsums.mla```.
2. Check that the variable ```libname``` in Maple contains the path to ```binomsums.mla``` or to its parent directory.
3. Load the package in Maple with ```with(BinomSums);```

