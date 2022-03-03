# Process Files

* Linear Regression
* File processing (.txt format)

## Table of contents
* [General Info](#general-information)
* [Components](#components)
* [Schematic](#schematic)
* [Acknowledgements](#acknowledgements)

## General Information
### Regr
Calculate the linear regression parameters that minimize the total square err error of the approach [^1].
* Accepts as program parameters a list of files. 
* Each file contains at least 3 lines.

#### Input format
```
**num1:num2** 
``` 





### Results
The program accepts as program parameter a file name. This file will contain rows of the format: **Team1-Team2:Score1-Score2**.
The project calculates the scores and points. The teams must be 
ordered based on scores. The results are exported to file.



Bash scripts have been created in notepadd program.
computeSale has been created in pyCharm.

**Bash script** programs can run in terminal. Execute
**./regr input1 input2 input3**

where **input1,input2,input3** are file names with the specified format for the regression program.


**./results input1**

where **input1** is file name with the specified format for the results program.


[^1]: The equations are also shown in the pronunciation in the form of .pdf with name "lab"



