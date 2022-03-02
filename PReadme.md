# PYTHON
> Program in python for processing input files

 
 ## Table of contents
* [General Info](#general-information)
* [Features](#features)
* [Acknowledgements](#acknowledgements)

## General Information
`computeSales.py` that reads `.txt` files and does correctness check, and can print requested statistics.

### computeSales
The program reads records with receipts sales of products, is able to do a correctness check and is able to print after statistics requested.

The input file format is like: <br />


```
------------------- 
AFM:AAAAAAAA 
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE 
... 
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE 
TOTAL: TOTAL VALUE 
-------------------- 
AFM:AAAAAAAB 
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE 
... 
PRODUCT_NAME: QUANTITY UNIT_PRICE TOTAL_VALUE 
TOTAL: TOTAL VALUE 
-------------------- 
```


## Features
### .TXT files [^1]:
1. Each file contains 1 or more receipts (but at least 1)
2. Each receipt begins and ends with lines containing only the ‘-’ character.
3. Receipts are separated by lines containing only the ‘-’ character.
4. The first line of each receipt contains the VAT number of the company (10-digit number).
5. The last line of each receipt contains the total purchases for that receipt.
6. In a file there can be receipts of different companies (AFM).
7. Each receipt includes the sale of multiple products (1 or more).
8. A product may appear on a receipt more than once. [^2]
9. The number of spaces in the lines between the fields is variable and your program should not make assumptions about the number of empty characters.
10. Any evidence that contains an error should be omitted, but the remaining evidence in the file should be read and saved.

### Program
Prints the following user menu repeatedly:
1. Read input file[^3]. 
2. Print statistics for a specific product.
3. Print statistics for a specific AFM. 




## How to run
* In Linux
1. Refresh repository lists
```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update
```
3. Install latest versions of python
```
$ sudo apt-get install python3.8
```
3. Verify installation and compile
```
$ python3.8
$ python3.8 computeSales.py
```
In any python IDE


**Python** programs can run in an pythom platform




## Acknowledgments

[^1]: Every input file satisfies constraints about numerical values and format it sustains.
[^2]: In the proof, the product XORIATIKI may appear again later in the same proof.
[^3]: The program works for a non-specific archive length.
