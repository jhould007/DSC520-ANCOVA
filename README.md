# ANCOVA
 An assignment for DSC520 at GCU that focused on the creation, use, and analysis of ANCOVA models.

Check out the full report [here.](https://github.com/jhould007/DSC520-ANCOVA/blob/main/ANCOVA.ipynb)

# Assignment Instructions
Analysis of covariance is used to test the main and interaction effects of categorical variables on a continuous dependent variable, controlling for the effects of selected other continuous variables, which co-vary with the dependent. The control variables are called the covariates.

For this activity, complete the following:

Examine the "Database MiniPONS.csv" dataset from the topic Resources. 

ANCOVA can be performed when each of the within-group trends have the same slope, are parallel to one another, and are parallel to the overall trend. Make this determination with respect to your data (i.e., the MiniPONS dataset) and state the results.

ANCOVA cannot be performed when the resulting adjustments must be extrapolated from a linear relationship outside the measured range of the covariate. If you determine that this dataset does not loan itself to ANCOVA analysis, work with your instructor on mitigating steps or finding an alternative dataset. Otherwise, complete the following.

State the null hypotheses using formal mathematical notation and explain what is meant by "groups" and "pooled population" in the model.

Factor A - The main treatment effect: a) The adjusted population group means are all equal. b) The effect of each group equals zero.<br>
Factor B - The covariate effect: a) The pooled population slope equals zero.<br>
The covariates are used to adjust the response values. Describe the ANCOVA design (linear model) you chose and explain the adjustments you made. For example, if your linear model includes a single categorical and a single covariate, then you would have the following equations as seen in the "DSC-520 Equation Image." 

Perform ANCOVA and address the following:<br>
Describe the factors. For example: a) A is categorical, B is continuous covariate. b) A and B are categorical; C is continuous covariate.<br>
Calculate the total variability of the response variable.<br>
Calculate the unexplained residuals and F-ratios for each factor.<br>
Calculate the covariate levels.<br>

Verify the assumptions:
Residuals are normally distributed. Use boxplots.<br>
Residuals are equally varied. Use boxplots and means against variance and scale as needed.<br>
Residuals are independent of one another.<br>
The relationship between the response variable and each covariate is linear.<br>
If treatment levels within blocks cannot be randomly ordered, the variance/covariance matrix displays sphericity.<br>
If your design uses blocking, there is no block within block interaction.<br>
Make predictions by stating their nature or other results that can be made, explaining the predictions computationally and graphically, and discussing your confidence in their accuracy.

Then, submit a professionally written and formatted software-based technical report. Make sure the documentation contains the code, relevant plots, your analysis, and the appropriate citations and references.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.

This assignment uses a rubric. Review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.

You are not required to submit this assignment to LopesWrite.   
