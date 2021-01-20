# Parallel Matrix Multiplication
The project aims to use the power of parallel processing by applying matrix multiplication operations in-parallel with the usage of OpenMP API of C language.

## Project Experiment
In this project, you need to write a parallel program using OpenMP that calculates the multiplication of 2 matrices A and B of size MxM. 

Run the code using p= 1,2,3,4 processors (threads) and with M=100, 200, 500, 1000, 2000 sizes. Print the results in a table. You need to run each case multiple times to take a representative average. When measuring
the time make sure that the machine has only the parallel program running to reduce variations in
run time measurement. Also, find the speedup and efficiency for each run and list it down in a table.

Before starting, test your program on a small matrix (M=3) to make
sure the multiplication is correct before running for a large size matrix to measure the time.

Finally, write a report that summarizes your experiment, also observations, and conclusions.

You can find [**The Team Report**](https://github.com/Faisal-AlDhuwayhi/Parallel-Matrix-Multiplication/blob/master/Final_Report.pdf) and [**The Individual Report**](https://github.com/Faisal-AlDhuwayhi/Parallel-Matrix-Multiplication/blob/master/Individual_Report.pdf) -contains other observations besides the team report- of the project in the repository.



## Requirements 
- [C language](https://www.guru99.com/c-gcc-install.html)

- [OpenMP](https://www.openmp.org/resources/openmp-compilers-tools/)

## Run
In a terminal or command window, navigate to the top-level project directory `Parallel-Matrix-Multiplication/` (that contains this README) and run the following command:

```
gcc -o Matrix-Multi -fopenmp Matrix-Multi.c
```  

Then run the following command:
```
Matrix-Multi
```


### OpenMP Resources
- [Installation](https://www.geeksforgeeks.org/openmp-introduction-with-installation-guide/)
  - Note that OpenMP does come with some gcc versions.
- [HelloWorld example](https://www.geeksforgeeks.org/openmp-hello-world-program/)