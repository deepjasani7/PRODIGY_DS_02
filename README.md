# Exploratory Data Analysis on Titanic Dataset

## Repository Overview
This repository contains an analysis of the famous Titanic dataset using Python. The focus of this project is **Exploratory Data Analysis (EDA)**, which aims to uncover initial insights and patterns in the data. The analysis is performed in a Jupyter Notebook using Python libraries like `pandas`, `matplotlib`, and `seaborn`.

## Files in the Repository
- **Titanic data.csv**: The dataset used for analysis. This contains information about passengers on the Titanic, including survival status, age, gender, ticket class, etc.
- **Task_2.ipynb**: A Jupyter Notebook that contains the code for performing Exploratory Data Analysis (EDA) on the Titanic dataset. It includes data cleaning, visualizations, and analysis to understand the key factors related to survival on the Titanic.

## Dataset Overview
The dataset contains information on Titanic passengers with the following columns:
- `PassengerId`: Unique identifier for each passenger
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger's name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings or spouses aboard the Titanic
- `Parch`: Number of parents or children aboard the Titanic
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Analysis Overview
In the notebook, the following steps have been performed:
1. **Data Loading**: Loading the Titanic dataset from the CSV file.
2. **Data Cleaning**: Handling missing values and dealing with inconsistencies in the data.
3. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics
   - Data visualization (survival rates, class distribution, gender analysis, etc.)
   - Correlation analysis to find relationships between variables such as gender, age, fare, and survival.
4. **Conclusion**: Insights drawn from the EDA, highlight factors that might have influenced passenger survival.

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone <repository-url>
