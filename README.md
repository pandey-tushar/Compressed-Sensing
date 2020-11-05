# Compressed-Sensing
This repository will be focussed on some codes for deterministic construction of compressed sensing matrices and possibly some random matrices for comparison.
## Devore's Matrix
The first code is the construction of DeVore's matrix using finite fields. There exists a better (circulant) version of this matrix but I still need to figure that out in an optimal way. 
## PV Expander Matrix
This is a great breakthrough in deterministic compressed sensing because s = O(m^{1-a}) for any a>0. And there is a lot of freedom in choice of m and N. For the linear order, however, large N is required. The code provides 
'''math
s = M^{2/3}
'''
/ 5 which is not quite bad. 
