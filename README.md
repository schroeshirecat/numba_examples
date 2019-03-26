numba_examples
=================

No code changes, except for making the print statements Python 3 compatible.
The .py files are added to allow running of the programs without Jupyter in terminal mode. If you don't want the image to be displayed, simple comment out the show() line.

An observation: The speed up between the numba and the cuda version of the code did show up on my systems (Xeon E3 skylake, and AMD broadwell 8 cores each with Nvidia Quadro M4000 GPU) only in the Jupyter notebook. Running the code standalone in terminal had the same runtime between the two versions.
Note: The figures were optained on a Linux Ubuntu 18.10 and Windows 10 systems with Cuda versions 10.1 and 9.0 respectively.
