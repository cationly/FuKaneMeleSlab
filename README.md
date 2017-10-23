# FuKaneMeleSlab

Microscopic tight-binding model of topological a insulator slab as in:

G. Siroki, P. D. Haynes, D. K. K. Lee and V. Giannini Phys. Rev. Mater. 1, 024201 (2017)

The original tight-binding Hamiltonian is presented here:

L. Fu, C. L. Kane, and E. J. Mele, Phys. Rev. Lett. 98, 106803 (2007)

Dependencies:
gcc
Armadillo
LAPACK

To compile run:
g++ -std=c++11 -o slab slab.cc -llapack -lblas -lgfortran -larmadillo
