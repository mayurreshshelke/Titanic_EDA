
## 🛠️ Technologies Used

- **Python**: The primary programming language used for data analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Support for large, multi-dimensional arrays and matrices.
- **Matplotlib & Seaborn**: Data visualization libraries.
- **Missingno**: Visualization of missing data.

## 📊 Dataset Overview

The dataset contains information about passengers such as:
- **Survived**: Whether the passenger survived (1) or not (0).
- **Pclass**: Passenger's class (1st, 2nd, 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Fare**: Fare paid by the passenger.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## 📈 Key Insights & Visualizations

- **Missing Values**: Identified missing values and handled them appropriately.
- **Age Distribution**: Distribution of ages of passengers aboard.
- **Survival Rate by Gender**: Explored survival rates by gender and passenger class.
- **Correlation Heatmap**: Analyzed correlations between numeric variables.

## 🧹 Data Cleaning Process

1. **Missing Values**: 
   - Filled missing **Age** with the median value.
   - Filled missing **Embarked** with the most common value.
   - Dropped the **Cabin** column due to a high number of missing values.
   
2. **Duplicates**: Removed duplicate rows from the dataset.

3. **Data Types**: Ensured correct data types for each column.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Titanic_EDA.git
