numba_examples
=================

No code changes, except for making the print statements Python 3 compatible.

An observation: The speed up between the numba and the cuda version of the code did show up on my system (Xeon E3 skylake, 8 cores) only in the Jupyter notebook. Running the code standalone in terminal had the same runtime between the two versions.
