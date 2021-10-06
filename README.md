# simplex-algorithm
Input format:
n = number of inequalities, m = number of variables  
next i = [1..n] lines are the coefficients  
second to last line is solutions to inequalities  
last line is the coefficients of the objective  
Example:  
2 2 (2 inequalities for 2 variables)  
0 1 (first inequality is of form 0x_1 + 1x_2)  
1 0 (second inequality is of form 1x_1 + 0x_2)  
2 2 (0x_1 + 1x_2 <= 2, 1x_1 + 0x_2 <= 2)  
-1 2 (objective is to maximize -1x_1 + 2x_2)  
