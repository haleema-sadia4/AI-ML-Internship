# AI/ML Internship Tasks - DevelopersHub

## Task 1 - Iris Dataset Exploration

**Objective:** Load, inspect and visualize the Iris dataset

**Dataset:** Iris Dataset (loaded via seaborn)

**What I did:**
- Loaded the dataset using pandas
- Inspected shape, columns and statistics
- Created scatter plot, histograms and box plots

**Key Finding:** Setosa species is clearly different from 
Versicolor and Virginica, especially in petal size.
## Task 6 - House Price Prediction

**Objective:** Build a Machine Learning model to predict house prices

**Dataset:** California Housing Dataset (loaded via sklearn)

**What I did:**
- Loaded and inspected a dataset of 20,640 houses
- Checked for missing values (none found)
- Explored data using statistics and histogram
- Split data 80% training / 20% testing
- Trained a Linear Regression model
- Evaluated model performance
- Visualized actual vs predicted prices

**Results:**
- Mean Absolute Error (MAE): 0.53 ($53,000 average error)
- R2 Score: 0.58 (model explains 58% of price patterns)

**Key Finding:** The model performs well for mid-range houses 
but struggles with very cheap and very expensive properties. 
Linear Regression is a good starting point but more advanced 
models like Random Forest would improve accuracy.
