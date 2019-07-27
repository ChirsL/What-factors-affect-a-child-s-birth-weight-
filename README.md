# What-factors-affect-a-child-s-birth-weight
Perform a comprehensive statistical analysis of a dataset to answer the question using different statistical methods and models. Different methods and models allow us to gain insights about the relationships of interest.


Are birth weights associated to variables such as mother’s age, race, and smoking status?
The variables in the dataset are defined as follows:
low: indicator of birth weight less than 2.5 kg (1=low birth weight, 0=otherwise).
age: mother’s age in years.
lwt: mother’s weight in pounds at last menstrual period.
race: mother’s race (1 = white, 2 = black, 3 = other).
smoke: smoking status during pregnancy (1=smoking, 0=non-smoking).
ptl: number of previous premature labours.
ht: history of hypertension.
ui: presence of uterine irritability.
ftv: number of physician visits during the first trimester.
bwt: birth weight in grams.

##1
In the following analyses, using α = 0.05 significance level if needed. For each of the following ques- tions, state your final conclusions in words.
(a) Draw (i) a side-by-side boxplot of birthweight (bwt) versus mother’s smoking status, (ii) a side-by-side boxplot of birthweight (bwt) versus mother’s race, and (iii) a scatterplot of birthweight (bwt) versus mother’s age. Do birthweights appear to be associated with mother’s smoking status, race, and age?
(b) Perform a hypothesis test to test if there is an association between low/high birth weights (birth weight less than 2.5 kg or not) and smoking status. State the reason of choosing this test method in one sentence. Is the result likely to be reliable?
(c) Perform a hypothesis test to test if there is an association between low/high birth weights and mother’s races. State the reason of choosing this test method in one sentence. Is the result likely to be reliable?
(d) Perform (i) a two-sample t-test, (ii) a Wilcoxon rank sum test, (iii) a permutation test, and (iv) a bootstrap method to test if birth weights (in grams) are the same for smoking and non- smoking mothers. Summarize the results in a single table. Which test may be most reliable here? Which test may be most powerful here?

##2
Consider the birthweight dataset in Problem 1 again. Perform further anal- yses as follows.
(a) Perform an ANOVA test to test if birth weights (in grams) are the same for all three races. State your conclusions.
(b) Conduct a two-way ANOVA test with smoking status and mother’s race as two factors and birth weight as response, without interaction. State your conclusions.
(c) Is there a significant interaction between smoking status and mother’s race? Draw a pic- ture to check possible interaction, and then test if the interaction is statistically significant. Do you need to modify the model and conclusion in (b)? If so, write down the model and state your updated conclusions.
(d) Is the average birthweight from white mother the same as the average birthweight of the mean birthweights from black and others? Write down the hypotheses and carry out the hypothesis testing. State your conclusion.
(e) Are the conclusions from (a) – (c) consistent with those from Problem 1? State the reasons in no more than three sentences.

##3
Consider the birthweight dataset in Problem 1 again.
(a) Find the sample correlation between mother’s ages and birth weights (in grams). Using the bootstrap method to find the standard error of the sample correlation. Use bootstrap replications of 100. Hint: In bootstrap sampling, you should sample the subject ID numbers, rather than sampling the ages and birthweights separately (which may distort the correlation).
(b) Find a 95% bootstrap confidence interval for the unknown population correlation between mother’s ages and birth weights. Use bootstrap replications of 100 and 200 respectively, compare the results, and state your conclusion.
(c) Test if there is a significant correlation between mother’s ages and birth weights (i.e., test whether the population correlation is zero or not) using a bootstrap method. Use bootstrap replications of 100 and 200 respectively, compare the results, and state your conclusion.
(d) Based on the above results, are mother’s age and birth weights correlated? Is the con- clusion consistent with the scatterplot in Problem 1? How does the number of bootstrap replications affect the results?

##4
Consider the birthweight dataset in Problem 1 again. Perform the following further analyses:
(a) Fit a simple linear regression model with birth weight (in grams) as the response and smoking status as a predictor. Summarize and interpret the results. Is your conclusion consistent with that in Problem 1?
(b) Fit a multiple regression model with birth weight as the response and mother’s age, mother’s smoking status, and mother’s race as predictors. (i) Summarize and interpret the results; (ii) Interpret the meaning of the regression coefficient for mother’s race (in words); (iii) Are your conclusions the same as those in Problems 1 – 3? Briefly explain your answers in words.
(c) (i) Based on all the results from Problems 1 – 4, what is your overall conclusion for the analyses of this dataset (in simple language understandable by non-statisticians)? (ii) Why are you asked to do the data analysis using so many different models and methods? (iii) Discuss the pros and cons of all the methods used in Problems 1 – 4 and offer your suggestions for choosing the methods.
