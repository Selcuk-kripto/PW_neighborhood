The code "comb2fun.cpp" produces and saves the truth tables of the Boolean functions which are obtained from the Patterson-Wiedemann (PW) functions using 
all the combinations mentioned in [1]. Their cryptographic properties are also computed and classified.
It is required to have 2GB disk space to save all the functions. The code is compiled with Microsoft Visual C++ 2010.

The following files are needed to run the code:
"Reprs15.txt":        Contains all the orbits for 15-variable RSBFs
"Reprs15_3.txt:       Contains all the orbits for 15-variable 3-RSBFs
"Combinations_d8.txt":Contains all the combinations found in [1], giving 1-resilient functions with nonlinearity 16264 from the PW function with degree 8
"Combinations_d9.txt":Contains all the combinations found in [1], giving 1-resilient functions with nonlinearity 16264 from the PW function with degree 9
The other combinations in [1] are defined as the elements of the corresponding arrays in "comb2fun.cpp".

The code generates the following files:
"Stats.txt":        Counter used to classify the results in terms of absolute indicator and algebraic degree
"d8_16264_res.txt": 1-resilient functions with nonlinearity 16264 obtained from the PW function with degree 8
"d9_16264_res.txt": 1-resilient functions with nonlinearity 16264 obtained from the PW function with degree 9
"d8_16272_bal.txt": Balanced functions with nonlinearity 16272 obtained from the PW function with degree 8 
"d9_16272_bal.txt": Balanced functions with nonlinearity 16272 obtained from the PW function with degree 9 
"d8_16266_192.txt": Balanced functions with nonlinearity 16266 and absolute indicator 192 obtained from the PW function with degree 8
"d8_16268_192.txt": Balanced functions with nonlinearity 16268 and absolute indicator 192 obtained from the PW function with degree 8
"d9_16268_192.txt": Balanced functions with nonlinearity 16268 and absolute indicator 192 obtained from the PW function with degree 9

Written by Selçuk Kavut, Balikesir University, Turkey.

[1] S. Kavut. Improved cryptographic properties of Boolean functions obtained from the neighbourhood of Patterson-Wiedemann functions. 
