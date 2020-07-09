# Data Science & Analytics Portfolio by Sean McConnell
This portfolio is a compilation of notebooks that I created for data cleaning, analysis, visualization, and machine learning modeling. A complete listing of all notebooks can be found here.

## Machine Learning Projects
### Titanic Survival Analysis and Machine Learning in Python
[Github](https://github.com/smcconn5/Portfolio/blob/master/Projects/.ipynb_checkpoints/Titanic%20Survival%20Analysis%20and%20Machine%20Learning-checkpoint.ipynb) [nbviewer](https://nbviewer.jupyter.org/github/smcconn5/Portfolio/blob/master/Projects/.ipynb_checkpoints/Titanic%20Survival%20Analysis%20and%20Machine%20Learning-checkpoint.ipynb)

This notebook took a full fledged analysis of the passenger data, as well as utilize supervised machine learning techniques to predict survival based on input factors. The following machine learning models were utilized to predict survival on the test dataset:
  - Logistic Regression
  - k-Nearest Neighbors
  - Support Vector Machines
  - Naive Bayes classifier
  - Decision Tree
  - Random Forest
  
### NYC Real Estate Sales - Modeling with Category Variables in R
[This kernel](https://www.kaggle.com/smcconn5/nyc-re-sales-modeling-with-category-variables) examined real estate sales in NYC over a 12-month period from September 2016 to September 2017 and focused on one family dwellings. A linear model for sale price was created using sqft, location, and the sqft/location interaction. Since location is a categorical variable, the data was re-coded into binary for Manhattan, Bronx, Brooklyn, and Queens. R2 of 0.642 on the training dataset and 0.650 on the validation data set.

### Jain University Candidate Placement: Full Analysis in Python
[This kernel](https://www.kaggle.com/smcconn5/jain-university-candidate-placement-full-analysis) examines at job placement for students at Jain University in Bangalore, India. The analysis begins with a look at certain factors such as: gender, placed or not, degree specialization, prior work experience, and undergraduate degree in relation to the whole population. Next it analyzes placement and salary based on gender lines. Finally, a logistic regression model was built to predict successful placement with 83.3% accuracy on the validation data set.

### 2019 NFL Combine ANOVA & Regression in R
[This kernel](https://www.kaggle.com/smcconn5/2019-nfl-combine-anova-regression) took the results of the 2019 NFL Combine and performed 2 analyses:
1.	One-Way ANOVA on hand size by position zone to assess if mean hand size by position zone differed. For the ANOVA model to meet the residual assumptions, a log transformation of hand size was performed. Line positions were the only players with a different mean hand size. The remaining positions on the field had statistically similar mean hand sizes.
2.	Linear regression to see which physical factors impacted 40-yard dash times and create a predictive model. Evidently, weight was the only effect that impacted 40-yard dash times. The model resulted in an R2 of 0.4955 on the training dataset and 0.5677 on the validation data set. The predictive equation was time = 3.806874 + weight*(0.003796).

This is the same project in the SAS section, but updated with more experience, knowledge, and modeling techniques from additional classes.

## School Projects
### Southern Company Predictive Analytics in SAS
This was a school sponsored project with Southern Company, in which my team took first place. Essentially, Southern Company installed smart meters on a section of their natural gas business, which produced a mountain of structured data. My team utilized SQL within SAS to join multiple tables, cleaned the data, calculated daily usage over the course of a year for unique meter numbers, incorporated historic weather data from a third party source, and created a model to predict gas usage for individual customers. The code was turned over to Southern Company. A LinkedIn post from the sponsoring professor can be found [here](https://www.linkedin.com/feed/update/urn:li:activity:6609995794374373376/).

### Product Longevity Simulation Project in SAS
[This](https://github.com/smcconn5/Portfolio/blob/master/Projects/Longevity%20Simulation%20Project.pdf) was a end of term class project for statistical modeling in which an electrical engineering firm needed to differentiate between two semiconductor designs where the only difference was longevity of the circuit. Based on the manufacturer longevity distributions, a simulation of 1000 samples was created for each circuit to determine which circuit lasted longer on average.

### 2019 NFL Combine ANOVA & Regression in SAS
[This project](https://github.com/smcconn5/Portfolio/blob/master/Projects/2019%20NFL%20Combine%20Analysis.pdf) took the results of the 2019 NFL Combine and performed 2 analyses:
1.	One-Way ANOVA on hand size by position zone to assess if mean hand size by position zone differed. For the ANOVA model to meet the residual assumptions, a log transformation of hand size was performed.
2.	Linear regression to see which physical factors impacted 40-yard dash times and create a predictive model.

This was the first draft of the analysis completed in the 'Kaggle Projects" section during my first semester of the MS in Applied Statistics Program. I updated the analysis using R which came to different conclusions due to more experience, knowledge, and modeling techniques.

### Puzzle Experimental Design Project in Minitab
[This project](https://github.com/smcconn5/Portfolio/blob/master/Projects/Puzzle%20Experimental%20Design%20Project.pdf) challenged me to create, design, execute, and analyze an experiment of my choosing. I decided to measure the time it took to complete puzzles of varying sizes with individuals of different ages to see if either of the factors impacted the pieces solved per minute (PPM).
