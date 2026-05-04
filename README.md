# Titanic Survival Analysis
## Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns and
key factors that influenced passenger survival. The analysis covers passenger demographics including age,
gender, and ticket class, and presents findings through clear visualizations.

## Dataset
### Property               Details

Source                 Titanic Test Dataset

Rows                   418 passengers

Columns                12 features

File                   titanic.csv

## Features Description:

### Column                  Description

PassengerId             Unique ID for each passenger

Survived                Survival status (0 = No, 1 = Yes)

Pclass                  Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name                    Passenger name

Sex                     Gender

Age                     Age in years

SibSp                   No. of siblings/spouses aboard

Parch                   No. of parents/children aboard

Fare                    Passenger fare

Cabin                   Cabin number

Embarked                Port of embarkation (C, Q, S)

## Key Findings

### Insight                       Finding

Gender & Survival             100% of females survived vs. 0% of males in this dataset

Class & Survival              1st class: 46.7% | 2nd class: 32.3% | 3rd class: 33%

Missing Data                  Age: 86 missing (~21%), Cabin: 327 (~78%), Fare: 1

Average Age                   Mean age of passengers was ~30.3 years

Total Survivors               152 out of 418 passengers survived (~36%)

## Technologies Used

• Python 3.x — Core programming language

• Pandas — Data loading, cleaning, and analysis

• NumPy — Numerical operations

• Matplotlib — Data visualizations (8+ charts)

• Jupyter Notebook — Development environment
 Visualizations
 
### The project includes 8+ charts and graphs:

• Survival count bar chart

• Survival rate by gender

• Survival rate by passenger class

• Age distribution histogram

• Correlation heatmap

• Missing values visualization

• Fare distribution by class

• Embarked port vs. survival

## Data Cleaning Steps

1. Identified missing values across all 12 columns
  
2. Imputed missing Age values using median age
 
3. Dropped Cabin column due to high missing rate (~78%)
 
4. Filled missing Fare value with column median
   
5. Verified no duplicates in the dataset
   
 ## How to Run
1. Clone the repository
   
2. git clone https://github.com/Abhilasha-git/Titanic-survival-analysis.git cd
Titanic-survival-analysis

4. Install required libraries
 
5. pip install pandas numpy matplotlib jupyter
   
6. Launch Jupyter Notebook
         jupyter notebook

7. Open the notebook
       Open Titanic_EDA.ipynb and run all cells
   
## Project Structure

### Titanic-survival-analysis/
     titanic.csv           # Dataset
     Titanic_EDA.ipynb   # Main analysis notebook
     README.md           # Project documentation
     
## Conclusions

• Gender was the strongest predictor of survival — female passengers had significantly higher survival
rates

• Passenger class played a key role — 1st class passengers had nearly double the survival rate of 2nd
and 3rd class

• Age showed moderate influence, with children having slightly higher survival rates

• Fare was positively correlated with survival, reflecting the class advantage

### Author
#### Abhilasha Aavya

 abhilasha.aavya@gmail.com
 
 http://github.com/Abhilasha-git
 
