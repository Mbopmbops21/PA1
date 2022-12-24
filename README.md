### COP2073C Module 1 Programming Assignment  
- This assignment should be completed using your posit.cloud account.  
- Accept the GitHub classroom invitation provided in the Canvas assignment page for this module.  
- Clone your repository in posit.cloud using the new GitHub workspace option.  
- In the console, install and load the tidyverse package as follows:  
    install.packages('tidyverse')  
    library(tidyverse)  
- Edit the Module1.R script file provided in your cloned repository so it completes the following steps:  
	- reproduce the vector from the first task of this module's practice exercise  
	- use the sample function to extract a sample vector of size 10 from the original vector  
	- use various summary statistics functions to display descriptive statistics for the sample  
		- call the mean, median, min, and max functions for your sample vector  
	- use the summary function to also display descriptive statistics for the sample  
		- compare the results of the individual function results to your summary function results  
	- create and print a tibble from the sample vector. A tibble is a tidyverse-specific data type derived from base R data frames (we will cover both of these in this course). We are doing this step to practice loading a package and using its functions. To create a tibble, pass the sample vector as an argument to the tibble() function and assign the returned object to a variable.   
	- Use the commit option in posit.cloud to commit your changes. Be sure to include an ID header in your script file.  
### Sample output follows, your data will vary:  
original vector: 5 4.7 4.4 4.1 3.8 3.5 3.2 2.9 2.6 2.3 2 1.7 1.4 1.1 0.8 0.5 0.2 -0.1 -0.4 -0.7 -1 -1.3 -1.6 -1.9 -2.2 -2.5 -2.8 -3.1 -3.4 -3.7 -4 -4.3 -4.6 -4.9 -5.2 -5.5 -5.8 -6.1 -6.4 -6.7 -7 7.3 -7.6 -7.9 -8.2 -8.5 -8.8 -9.1 -9.4 -9.7 -10 -10.3 -10.6 -10.9  
sample vector: -1.6 -7.9 3.5 -1.3 -0.7 -3.1 2.9 -4.6 -9.7 -10.9  
mean = -3.34  
median = -2.35  
min = -10.9  
max = 3.5  
Min. 1st Qu. Median Mean 3rd Qu. Max.  
-10.900 -7.075 -2.350 -3.340 -0.850 3.500  
A tibble: 10 x 1  
sample_a  
<dbl>  
1 -1.60  
2 -7.9  
3 3.5  
4 -1.30  
5 -0.7  
6 -3.10  
7 2.9  
8 -4.6  
9 -9.7  
10 -10.9  