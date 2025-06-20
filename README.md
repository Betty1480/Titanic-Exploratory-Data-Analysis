# Titanic-Exploratory-Data-Analysis

Overview
This week’s assignment will develop hands-on experience on Exploratory Data Analysis using Kaggle Data Set and publishing your work on Kaggle.

Link: https://www.kaggle.com/code/mariyamalshatta/masterclass-1-a-comprehensive-guide-for-eda

The purpose of the assignment is to practice Exploratory Data Analysis steps:

Initial Data Exploration
Handling Missing Values and Outliers
Univariate Analysis
Bivariate Analysis
Multivariate Analysis
Target Variable Analysis
Instructions 
Personalize your Exploratory Data Analysis of the data set, ensuring that you:

Profile the list of features and analyze their: data types, missing values, duplicates, errors, and plots you can explore per feature. Here are some essential pandas functions used for initial exploration:
df.head(): Displays the first few rows of the dataset to give you a quick preview.
df.shape: Returns the number of rows and columns in the dataset.
df.info(): Provides details about the columns, their data types, and the number of non-null (non-missing) values.
df.describe(): Provides summary statistics (mean, median, min, max, etc.) for numerical columns.
df.columns: Lists the names of all columns in the dataset.
df.nunique(): Returns the number of unique values in each column.
df.duplicated(): Checks for duplicate rows
Univariate Analysis: Examine each feature at a time to understand its distribution and seek to answer questions like:
What is the age distribution of passengers?
How many passengers embarked from each location?
Are ticket prices evenly distributed, or are they skewed?
Bivariate Analysis: Examine pairs of features of interest. Justify which features you would like to pair in the analysis and seek to answer questions like?
Does the Fare change depending on the Pclass?
Are younger passengers more likely to survive on the Titanic?
Does the Embarked location affect survival rate?
Multivariate analysis: Explore more complex relationships between three or more variables simultaneously. Detect interactions, combined effects, and hidden patterns that may not be visible in bivariate analysis. This can help answer complex questions, such as:
How do Pclass, Age, and Fare jointly affect survival?
Are survival rates different for Embarked locations when considering Pclass?
Outlier detection and handling: There are different ways to handle outliers, which include removing, capping, imputing, or leaving them as is. Argue and justify your selected method of handling outliers for each feature, e.g.
Removing outliers in Fare may help for predictive models, but could hide important insights for understanding passenger wealth.
 Target Variable Exploration: Analyze the Target/Dependent Variable Survived and explore:
The distribution of the target variable (Survived) using countplots and bar plots.
How balanced or imbalanced the dataset is.
What factors (like age, gender, class, or embarkation point) may influence survival?
Use combined plots to detect interaction effects
