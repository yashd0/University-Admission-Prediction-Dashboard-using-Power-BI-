# University-Admission-Prediction-Dashboard-using-Power-BI- Multiple Linear Regression

In this repository, I have implemented various machine learning models that predict whether the probability of a student getting accepted into a University offering a Masters degree. Upon noting the validation accuracies on each of the model, I have selected the best of all on them and shown how the key performance indicators(KPIs) vary in their values.
#Data
The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters included are :

GRE Scores ( out of 340 )
TOEFL Scores ( out of 120 )
University Rating ( out of 5 )
Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
Undergraduate GPA ( out of 10 )
Research Experience ( either 0 or 1 )
Chance of Admit ( ranging from 0 to 1 )


#Model

For this dataset, we tried the following four models with their accuracies listed as below
Model	Validation Accuracy
Linear Regression	0.822831
Artificial Neural Networks(5-layers)	0.805562
Decision Tree	0.460020
Random Forest	0.797299
As we can see, the best model is our Multiple Linear Regression model with a validation accuracy of 0.822831

#Insights

The mean for the GRE scores is 316
Mean for TOEFL score is 107
Standard deviation for the GRE score is 11, which suggests that about 68% of the students scored between 305 and 327
Average University Ranking is 3
There is a very high correlation between GRE and TOEFL scores. A student who scores higher on GRE tends to score higher on their TOEFL exam
The chance of admission acceptance increases as GPA, SOP and University Ranking improve/increase
Students who have research experience in the past, tend to have a higher chance of getting into a University with a ranking of 3

#Key Performance Indicators(KPIs)

In the following text, I have explained what role each KPI plays and what the value that we have got suggests about our best model(Multi-Linear Regression)
Mean Absolute Error(MAE)

We achieve a MAE of 0.0383 on the multiple linear regression model. Being a measure of the avg magnitude of error, as our MAE is very close to zero, we can say that our predictions are very close to the right predictions.
Mean Square Error(MSE)

MSE, in this case, is 0.00268, which is a value close enough to 0. This tells us that there are very few outliers in the data since if there would have been a higher number of outliers, the MSE value would have been higher.
Root Mean Square Error(RMSE)

We can see that the RMSE value is 0.052. This tells us that the standard deviation of the residuals is a lower value.
R^2 (Coefficient of Determination)

R-squared value is 0.82 which means that 82% of the variance in our dataset can be explained by the regression model.
Adjusted R-squared value

We can see that the adjusted R-squared value is 0.80432. We can see that the value of adjusted R-squared is high which suggests that the predictors used in the model are all useful. If there are any such predictors that do not play a significant role in predicting the outcome, Adjusted R-square value decreases as it penalises such predictor factors.


#Build an attractive and eye-catching  dashboard

Visualize gender & racial diversity using graphs & charts in Power BI

Explore buttons, themes, filters & slicers to make the dashboard interactive & smart

SKILLS YOU WILL GAIN

power bi dashboards
Data Visualization (DataViz)
Student dashboard
Microsoft Power BI
