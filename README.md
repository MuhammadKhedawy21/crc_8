## Data Communications Assignment 1
#### Contributers:
Palak Singhal 16CO129
<br>
Sharanya Kamath 16CO140
<br>
#### Q21. MATLAB code for CRC-8 for the analysis of % of error detection and correction w.r.t to the input data words for 1, 2, 3, ... n-bit errors and for 8-bit divisor.
We have included sample message (msg) in the program. This message can be changed in the main function (assg1_129_140.m). 
<br>
We have used CRC8 generator polynomial (poly) as divisor in the program. This can be changed to any 8 bit divisor in the main function (assg1_129_140.m).
#### Description of files:
##### assg1_129_140.m
Main function
##### codeword.m          
Function to append bits to message and generate transmitted codeword
##### synd.m            
Function which takes input received codeword and returns the syndrome
##### graphfunc.m         
Function to plot percentage error detection vs no. of error bits graph