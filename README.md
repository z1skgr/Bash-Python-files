# Process Files
  bash-python

# BASH
# Regr
The program accepts as program parameters a list of files. Assume that each file has lines of the format:
**num1:num2**. Each file should contain at least 3
Lines. The program scan each file to calculate the linear regression parameters a,b,c to minimize the total square error of the **cY=aX+b** approach. 

# Results
The program accepts as program parameter a file name. This file will contain rows of the format: **Team1-Team2:Score1-Score2**.
The project calculates the scores and points. The teams must be 
ordered based on scores. The results are exported to file.

# PYTHON
# computeSales
The program reads records with receipts sales of products, is able to do a correctness check and is able to print after statistics requested.

The input file format is like: <br />
------------------- <br />
AFM:AAAAAAAA <br />
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE <br />
... <br />
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE <br />
TOTAL: TOTAL VALUE <br />
-------------------- <br />
AFM:BBBBBB <br />
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE <br />
... <br />
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE <br />
TOTAL: TOTAL VALUE <br />
-------------------- <br />

Every input file satisfies constraints about numerical values and format it sustains.

The program prints the following user menu repeatedly:
1: read new input file. <br />
2: print statistics for a specific product. <br /> 
3: print statistics for a specific AFM. <br />
4: exit the program. <br />

The program works for a non-specific archive length.

# How to run
**Bash script** programs can run in terminal. Execute
**./regr input1 input2 input3**

where **input1,input2,input3** are file names with the specified format for the regression program.

**./results input1 **

where **input1** is file name with the specified format for the results program.


**Python** programs can run in an pythom platform

Bash scripts have been created in notepadd program.
computeSale has been created in pyCharm.


