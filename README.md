# Exploratory Data Analysis (EDA) on the Iris Dataset by Kgomotso Mongale  

## Project Description
This project focuses on performing a comprehensive Exploratory Data Analysis (EDA) on the renowned Iris flower dataset. The primary goal is to understand the dataset's structure, identify data characteristics, and visualize relationships between features to gain insights into the data.

## Dataset
Dataset Link: https://www.kaggle.com/datasets/arshid/iris-flower-dataset

The Iris dataset contains 150 entries and 5 columns:
- **Numerical Data**: `sepal_length`, `sepal_width`, `petal_length`, and `petal_width` (all in centimeters).
- **Categorical Data**: `species`.
- The dataset is well-structured and contains no missing values.

## File and Code Description
The analysis is contained within the `EDA_on_Iris_Dataset.ipynb` Jupyter Notebook. The notebook is structured into logical steps:
1. **Initial Data Loading**: The `iris.csv` file is loaded into a pandas DataFrame, and initial checks are performed using methods like `.head()`, `.shape`, and `.info()` to understand the data's composition.
2. **Data Cleaning**: The code verifies that there are no null values in the dataset using `df.isnull().sum()`.
3. **Data Visualization**: Various plots and graphs are generated to visualize the distribution of features and their relationships. The visualizations include:
   - 2-D Scatter Plot
   - Pair Plot
   - Histogram
   - Violin Plot
   - Multivariate Probability Density
   - Contour Plot

## Requirements
The project requires the following Python libraries:
```bash
pip install pandas matplotlib seaborn numpy scipy

