Titanic Dataset Analysis

Introduction
The Titanic Dataset is one of the most popular datasets used in data analysis and machine learning. It contains information about passengers who traveled on the RMS Titanic, which sank on April 15, 1912, after hitting an iceberg.
This project aims to analyze passenger data using Python (Pandas & NumPy) to understand the factors that influenced survival, such as age, gender, passenger class, fare, and family size.
By performing statistical analysis, we can identify patterns and draw meaningful insights from the dataset.

 Titanic Dataset Overview
The dataset represents passengers aboard the RMS Titanic.
Common Columns in Dataset:
•	PassengerId – Unique ID of passenger
•	Survived – Survival status (0 = No, 1 = Yes)
•	Pclass – Passenger class (1 = First, 2 = Second, 3 = Third)
•	Name – Passenger name
•	Sex – Male or Female
•	Age – Age of passenger
•	SibSp – Number of siblings/spouses aboard
•	Parch – Number of parents/children aboard
•	Fare – Ticket fare
•	Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
 Dataset Characteristics:
•	Total Passengers: 891 (training dataset)
•	Contains missing values (especially Age, Cabin)
•	Mix of numerical and categorical data

Methodology
The following steps were followed to analyze the dataset:
Step 1: Data Loading
•	Imported dataset using Pandas.
•	Checked shape, columns, and data types.
 Step 2: Data Cleaning
•	Handled missing values (filled or removed).
•	Converted categorical data (Male/Female) into numerical form.
•	Removed unnecessary columns (Cabin, Ticket if needed).
Step 3: Exploratory Data Analysis (EDA)
•	Used:
o	.describe() for statistical summary
o	.value_counts() for categorical analysis
o	.groupby() for survival comparison
Compared survival rates based on:
o	Gender
o	Passenger class
o	Age group
o	Fare amount
 Step 4: Statistical Analysis
•	Calculated mean, median, standard deviation.
•	Compared survival percentages.
•	Analyzed correlations between features.

Statistical Analysis
1. Overall Survival Rate
•	Around 38% survived
•	Around 62% did not survive
2. Survival by Gender
•	Female survival rate was significantly higher.
•	Most males did not survive.
This shows “Women and children first” policy effect.
 3. Survival by Passenger Class
•	First-class passengers had highest survival rate.
•	Third-class passengers had lowest survival rate.
 Higher class passengers had better access to lifeboats.
4. Age Analysis
•	Children had better survival rate.
•	Elderly passengers had lower survival rate.
 5. Fare Analysis
•	Passengers who paid higher fares had higher survival probability.
•	Fare is positively related to survival.
6. Family Size
•	Small families had better survival compared to very large families or people traveling alone.

Conclusion
From the analysis of the Titanic dataset, we conclude:
1.	Gender was the strongest factor influencing survival.
2.	Passenger class significantly affected survival chances.
3.	Higher fare and better socioeconomic status improved survival probability.
4.	Children had better chances of survival.
5.	Data analysis helps uncover hidden patterns in historical events.
This project demonstrates how data analysis techniques using Pandas and NumPy can extract meaningful insights from real-world datasets.
