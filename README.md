# EDA_US_Citizens


Explanatory data analysis on the US citizens income survey

**Aim of the Project**

Applying Exploratory Data Analysis (EDA) and preparing the data to implement the Machine Learning Algorithms;
	1	Analyzing the characteristics of individuals according to income groups
	2	Preparing data to create a model that will predict the income levels of people according to their characteristics (So the "salary" feature is the target feature)

**Steps:**
		
	•	Dataset Info
	•	Importing Related Libraries
	•	Recognizing & Understanding Data
	    ⁃	Check the head, shape, data-types of the features.
	    ⁃	Check if there are some dublicate rows or not. If there are, then drop them.
	    ⁃	Check the statistical values of features.
      ⁃	If needed, rename the columns' names for easy use.
      ⁃	Basically check the missing values.
	•	User defined functions for statistical analysis and null values
	•	Univariate & Multivariate Analysis
        ⁃	Examine all features (first target feature("salary"), then numeric ones, lastly categoric ones) separetly from different aspects according to target feature.
        ⁃	to do list for numeric features:
        ⁃	Check the boxplot to see extreme values
        ⁃	Check the histplot/kdeplot to see distribution of feature
        ⁃	Check the statistical values
        ⁃	Check the boxplot and histplot/kdeplot by "salary" levels
        ⁃	Check the statistical values by "salary" levels
        ⁃	Write down the conclusions you draw from your analysis
        ⁃	to do list for categoric features:
        ⁃	Find the features which contains similar values, examine the similarities and analyze them together
        ⁃	Check the count/percentage of person in each categories and visualize it with a suitable plot
        ⁃	If need, decrease the number of categories by combining similar categories
        ⁃	Check the count of person in each "salary" levels by categories and visualize it with a suitable plot
        ⁃	Check the percentage distribution of person in each "salary" levels by categories and visualize it with suitable plot
        ⁃	Check the count of person in each categories by "salary" levels and visualize it with a suitable plot
        ⁃	Check the percentage distribution of person in each categories by "salary" levels and visualize it with suitable plot
        ⁃	Write down the conclusions you draw from your analysis
        ⁃	Note : Instruction/direction for each feature is available under the corresponding feature in detail, as well. 
	•	Other Specific Analysis Questions
        ⁃	1. What is the average age of males and females by income level?
        ⁃	2. What is the workclass percentages of Americans in high-level income group?
        ⁃	3. What is the occupation percentages of Americans who work as "Private" workclass in high-level income group?
        ⁃	4. What is the education level percentages of Asian-Pac-Islander race group in high-level income group?
        ⁃	5. What is the occupation percentages of Asian-Pac-Islander race group who has a Bachelors degree in high-level income group?
        ⁃	6. What is the mean of working hours per week by gender for education level, workclass and marital status? Try to plot all required in one figure.
		
	•	Dropping Similar & Unneccessary Features
	•	Handling with Missing Values
	•	Handling with Outliers through domain knowledge
	•	Correlation between features
	•	Final Step to make ready dataset for ML Models
	•	The End of the Project
