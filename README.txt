
## Application:

The file "Data.csv" includes a simulated data set with the number of groups being 7000 and two covariates.

The main function is in the file "Analysis File.txt".

Some necessary functions are given in the file "Support functions.txt".

Before running the main function, one needs to put the files "mydata.csv" and "Analysis File.txt" in the working directory.

The obtained results include the point estimate of regression parameter, the standard error estimate and p-value.
The obtained results also include the survival function estimates with pointwise 95\% confidence bands.

#########################################
## Simulation (Tables):

The codes in the file "Simulation-table1.txt" can reproduce the numerical results with alpha=beta=1 given in Table 1 of the main paper exactly.  


The codes in the file "Simulation-tableS1.txt" can reproduce the numerical results with alpha=beta=1 given in Table S1 of the supplementary materials exactly.  


With the two files, one can change alpha and beta values in line 4 of the code to reproduce other results given in Table 1 and Table S1 exactly. 


##########################################
## Simulation (Figures):

In this example, we give the estimates of S(t) with \alpha=\beta=1, five covariates and varying group sizes.
One can change alpha and beta values in the code to obtain other results in the paper. 


In particular, please set the working directory first, such as "setwd("D:/wd21")" in our code.

Before running the main code in the file "Simulation-figures-main.txt", one needs to obtain the estimates of S(t)
with the proposed group testing method, the individual method (n) and the individual method (N).
 
In particular, 

the code in the file "Simulation-figures-GT1.txt" produces the estimates of S(t) with the proposed group testing method;

the code in the file "Simulation-figures-Individual (n) (2).txt" produces the estimates of S(t) with the individual method (n);

the code in the file "Simulation-figures-Individual (N) .txt" produces the estimates of S(t) with the individual method (N).




