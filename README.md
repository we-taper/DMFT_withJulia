# DMFT_withJulia
## The Dynamical Mean Field Theory (DMFT) with the continuous-time auxiliary-field Quantum Monte Carlo method with Julia 0.7.0.
I made the continuous-time auxiliary-field Quantum Monte Carlo (CTAUX) method with Julia (cometscome/ctaux_Julia).
I also made the numerical analytical continuation with the use of the sparse modeling technique (cometscome/SMAC).
So, we can do the DMFT calculation with CTAUX impurity solver with Julia 0.7.0. 

This code calculates the DMFT in the Bethe lattice. 
The code works in Julia 1.0.0.

Note: This code is a test code. I do not guarantee any results with this code. 
Just play it!


*_forv06* files are for Julia 0.6.x. 

## Requirements

```julia
import Pkg; Pkg.add("Dierckx")
import Pkg; Pkg.add("FFTW")
import Pkg; Pkg.add("Plots")
```