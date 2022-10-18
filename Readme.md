# Quick tutorial. 
## Finding eigenvalues of a density matrix using Newton Identities and the Faddeev LeVerrier algorithm.
### Antonio Ruiz Molero. 2022. INL
Notebook that explains how to find the eigenvalues of a density matrix using the Faddeev Leverrier (F-L) algorithm. We compute an array of traces of the different powers of the density matrix: $ \{ \text{Tr} A^i \}\; i=1,...,d$ where $d$ is the dimension of the system. This array is used by the F-L algorithm to compute the coefficients of the characteristic polynomial. The polynomial can be solved with any method suited for that task, like the ones found in numpy

**Disclaimer**: The algorithms are direct implementations of the pseucode available at Wikipedia. There might be errors. We have checked  solutions finding the eigenvalues with numpy and comparing the results, but proper testing of the functions is required. 