Project Overview

This project performs an Exploratory Data Analysis (EDA) of the Titanic dataset
 to understand the factors affecting passenger survival. Using Python and Jupyter Notebook, it provides visual insights into demographics, travel class, fare, and survival trends.

Dataset

The dataset includes:

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Passenger class (1, 2, 3)

Sex – Gender

Age – Age in years

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation

Key Visualizations
1. Survival Count

Shows the number of passengers who survived vs. those who did not.


Insight: More passengers did not survive than survived.

2. Gender vs Survival

Compares survival rates between male and female passengers.


Insight: Females had significantly higher survival rates than males.

3. Passenger Class vs Survival

Shows how survival probability varied across passenger classes.


Insight: 1st class passengers survived more often than 3rd class.

4. Age Distribution vs Survival

Analyzes survival across different age groups.


Insight: Children and younger passengers had slightly better chances of survival.

5. Fare vs Survival

Examines relationship between ticket fare and survival.


Insight: Passengers paying higher fares (mostly in higher classes) survived more.

6. Correlation Heatmap

Shows correlation among numeric features (Age, Fare, SibSp, Parch, Survived).


Insight: Fare has a small positive correlation with survival; other features show minimal correlation.

Tools & Libraries

Python 3.x

Jupyter Notebook

Pandas & NumPy (data manipulation)

Matplotlib & Seaborn (visualizations)

How to Use

Clone this repository:

git clone <repository-url>


Open Titanic_Survival_Visualization.ipynb in Jupyter Notebook.

Run the notebook to explore data cleaning, analysis, and visualizations.

Conclusion

This project highlights key factors affecting Titanic survival, including gender, age, and passenger class, providing insights that can be used for predictive modeling in machine learning projects.
