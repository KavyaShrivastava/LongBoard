# LongBoard-Data-Analysis 
# Introduction

This data analysis project focuses on developing a linear regression model to predict the average speed of a LongBoard based on a given set of predictors. The goal is to optimize the model by identifying outliers, examining deviations from the normal distribution, and addressing other influential factors through data visualization techniques. These techniques include QQ plots, residual vs. fitted plots, and correlation analysis to enhance the R-squared measure. Additionally, the Box-Cox method is employed to transform variables and achieve a normal distribution. The analysis also aims to understand the individual influence of predictors on the model.

#Methodology
The following steps were performed in this data analysis:

Data Collection: The dataset containing information on LongBoard speed and various predictors was obtained for analysis.
Data Preprocessing: Any missing or incomplete data was handled appropriately to ensure the dataset's quality.
Exploratory Data Analysis: Initial exploration of the data was conducted to understand the relationships between the predictors and the target variable (average speed). This involved generating summary statistics, histograms, and scatter plots.
Outlier Detection: Outliers were identified using visualization techniques like box plots and removed from the dataset to prevent their influence on the model.
Normality Check: The normality assumption of the target variable and predictors was examined using QQ plots and other statistical tests. If deviations from normality were detected, the Box-Cox method was applied to transform the variables and achieve a more normal distribution.
Correlation Analysis: The correlation between different predictors was analyzed to avoid multicollinearity issues and enhance the accuracy of the model.
Model Building: A linear regression model was developed using the predictors to predict the average speed of the LongBoard. The model was then evaluated for goodness-of-fit using R-squared and other relevant metrics.
Variable Transformation: Some predictors were transformed to better understand their individual impact on the model and improve its performance.
Model Optimization: The model was optimized by iteratively making adjustments based on the findings from data visualization, correlation analysis, and transformation of variables.
 Model Validation: To ensure the model's generalizability, it was validated using appropriate techniques like cross-validation.

 It also explores whether equipment focused predictors were correlated more to avg speed vs non-equipment fouced predictors. 
