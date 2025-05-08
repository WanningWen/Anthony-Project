# Anthony-Project
SAS coding with stats tests 


# Techniques (Methods) when dealing with two variables

1. Two categorical variables: Use Chi-square analysis to test for association.
Null hypothesis: Two categorical variables are independent (or No association)
Versus research hypothesis: They are Not Independent.
If P-value is large (more than 5%) then there is no association.
Small P-value means two variables are associated to each other. Further, we usually need to check the kind of association by looking into appropriate proportions. 

2. One numerical variable and one categorical variable (factor), to compare means of the numerical variable:
(a) If categorical variable has two levels:  use (independent-samples) t TEST.
Null hypothesis: Two means are equal
Versus research hypothesis: The means are different (could be one-sided test).
We need to determine whether the variances are equal or not first to use the corresponding t test.
Also check: Normality condition.
(b) If categorical variable has more than two levels: use one-way ANOVA.
Ho: All means are the same. Ha: There are some differences in means.
If P-value is small, use Post Hoc comparison procedures. ( Also check Normality condition). 

3. When both are numerical variables 
(a) Use (Correlation), and Regression analysis. 
Need to interpret R-square, check model P-value, establish the regression equation, and check residual plots.
(b) If both are numerical measures of the same kind from the same (or related) objects, paired-samples t test may be appropriate.


# Dataset information
> [!source]
> https://archive.ics.uci.edu/dataset/236/seeds

## Additional Variable Information
To construct the data, seven geometric parameters of wheat kernels were measured: 
1. area A, 
2. perimeter P, 
3. compactness C = 4*pi*A/P^2, 
4. length of kernel,
5. width of kernel,
6. asymmetry coefficient
7. length of kernel groove.
All of these parameters were real-valued continuous.