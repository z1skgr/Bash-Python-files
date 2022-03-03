# Process Files

* Linear Regression
* File processing (.txt format)

## Table of contents
* [General Info](#general-information)
* [How to run](#how-to-run)



## General Information
### Regr
Calculate the linear regression parameters that minimize the total square err error of the approach [^1].
* Accepts as program parameters a list of files. 
* Each file contains at least 3 lines.

#### Input format
```
num1:num2
``` 
where `num1 => X` <br> &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp; 
      `num2 => Y` <br>

#### Output format
```
FILE: input1, a=5.31 b=2.32 c=1 err=1340.32
FILE: input2, a=-2.31 b=1.23 c=1 err=13.25
FILE: input3, a=0 b=3 c=1 err=0
```
where `input1 => file name #1` etc <br>
<br><br><br><br><br>




### Results
Calculate scores of teams and points. The teams must be ordered based on scores.
In tie, ascending order to name.

#### Input format
> Team1-Team2: Score1-Score2
```
Portugal-Greece:1-2
Greece-Spain:2-1
```

#### Output format
```
1.    Portugal  6 3-2
2.    Greece  4 4-4
3.    Spain 4 2-2
```
where `input1 => file name #1` etc <br>

<br><br><br><br><br>


## How to run
1. Open terminal and create a Bash file
```
$ touch regr.sh
$ touch results.sh
```

2. Open your script and add the following commands
```
#!/bin/bash
```
3. Save and close

4. Set executable permissions
```
$ chmod u+x regr.sh
$ chmod u+x results.sh
```
5. Run executable scripts
```
$ ./regr.sh
$ ./results.sh
```
or 
```
$ bash regr.sh
$ bash results.sh
```
or
```
$ sh regr.sh
$ sh results.sh
```

6. Make sure you include the required parameters for execution to each file
```
./regr input1 input2 input3
./results input1
```




[^1]: The equations are also shown in the pronunciation in the form of .pdf with name "lab"



