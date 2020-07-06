# Data Science & Analytics Portfolio by Sean McConnell
This portfolio is a compilation of notebooks that I created for data cleaning, analysis, visualization, and machine learning modeling. A complete listing of all notebooks can be found here.

## Kaggle Projects

### Southern Company Predictive Analytics in SAS
This was a school sponsored project with Southern Company, in which my team took first place. Essentially, Southern Company installed smart meters on a section of their natural gas business, which produced a mountain of structured data. My team utilized SQL within SAS to join multiple tables, cleaned the data, calculated daily usage over the course of a year for unique meter numbers, incorporated historic weather data from a third party source, and created a model to predict gas usage for individual customers. The code was turned over to Southern Company. A LinkedIn post from the sponsoring professor can be found here.

### 2019 NFL Combine ANOVA & Regression in R
This notebook took the results of the 2019 NFL Combine and performed 2 analyses:
1.	One-Way ANOVA on hand size by position zone to assess if mean hand size by position zone differed. For the ANOVA model to meet the residual assumptions, a log transformation of hand size was performed. Line positions were the only players with a different mean hand size. The remaining positions on the field had statistically similar mean hand sizes.
2.	Linear regression to see which physical factors impacted 40-yard dash times and create a predictive model. Evidently, weight was the only effect that impacted 40-yard dash times. The model resulted in an R2 of 0.4955 on the training dataset and 0.5677 on the validation data set. The predictive equation was time = 3.806874 + weight*(0.003796).

### NYC Real Estate Sales - Modeling with Category Variables in R
This notebook examined real estate sales in NYC over a 12-month period from September 2016 to September 2017 and focused on one family dwellings. A linear model for sale price was created using sqft, location, and the sqft/location interaction. Since location is a categorical variable, the data was re-coded into binary for Manhattan, Bronx, Brooklyn, and Queens. R2 of 0.642 on the training dataset and 0.650 on the validation data set.

### Google Play Store Cleaning & Basic Exploration in R
This notebook demonstrates what to look for while cleaning data to be used. Data Scientists report that cleaning data takes 75% of their time, so it is essential to know what to look for and how to "clean" it. Once the data was cleaned, limited exploration was performed.

### Jain University Candidate Placement: Full Analysis in Python
This notebook examines at job placement for students at Jain University in Bangalore, India. The analysis begins with a look at certain factors such as: gender, placed or not, degree specialization, prior work experience, and undergraduate degree in relation to the whole population. Next it analyzes placement and salary based on gender lines. Finally, a logistic regression model was built to predict successful placement with 83.3% accuracy on the validation data set.
