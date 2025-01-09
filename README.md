# Linear Regression Analysis Project

## Project Overview

This project demonstrates the use of **Linear Regression** to analyze and predict a target variable based on independent variables. The dataset contains customer data, including features such as average session length, time spent on an app, time spent on a website, and length of membership. The target variable is the **Yearly Amount Spent** by customers.

### Key Objectives:

- Explore and understand the dataset.
- Perform data visualization to identify patterns and relationships.
- Build and evaluate a linear regression model.
- Analyze the residuals to validate the model's performance.

---

## Dataset

The dataset used in this project is a CSV file (`Ecommerce Customers`) containing the following columns:

- **Email**: Customer email address (categorical).
- **Address**: Customer address (categorical).
- **Avatar**: Customer avatar type (categorical).
- **Avg. Session Length**: Average session length in minutes (numerical).
- **Time on App**: Average time spent on the app in minutes (numerical).
- **Time on Website**: Average time spent on the website in minutes (numerical).
- **Length of Membership**: Number of years the customer has been a member (numerical).
- **Yearly Amount Spent**: Total amount spent by the customer in a year (numerical, target variable).

---

## Project Workflow

1. **Exploratory Data Analysis (EDA):**

   - Visualized distributions, relationships, and correlations using `pandas`, `matplotlib`, and `seaborn`.
   - Plotted pairwise relationships and heatmaps to identify important features.

2. **Data Preprocessing:**

   - Checked for missing values and duplicates.
   - Scaled/normalized features for consistent model performance (if needed).

3. **Model Building:**

   - Built an **Ordinary Least Squares (OLS)** regression model using `statsmodels`.
   - Split the data into training and test sets using `scikit-learn`.

4. **Model Evaluation:**

   - Evaluated the model using metrics like **Root Mean Squared Error (RMSE)** and **R-squared**.
   - Visualized the predictions vs. actual values.
   - Plotted residuals to validate assumptions of linear regression.

---

## Key Results

- **Significant Features**: Identified the most influential features affecting yearly spending.
- **Model Performance**:
  - R-squared: Indicates the proportion of variance explained by the model.
  - RMSE: Measures the average prediction error in the same units as the target variable.
- **Residual Analysis**: Confirmed the residuals followed a normal distribution, validating the linear regression assumptions.

---

## Technologies Used

- **Python Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `statsmodels` for building and analyzing the regression model.
  - `scikit-learn` for data splitting and evaluation metrics.

---

## How to Run the Project

1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn statsmodels scikit-learn
   ```
3. Run the Jupyter Notebook or Python script containing the code.

---

## Future Improvements

- Explore advanced regression techniques (e.g., Ridge, Lasso, or Polynomial Regression).
- Implement feature selection to improve model interpretability.
- Extend the analysis with real-time or additional data sources.

---

## Acknowledgments

This project was inspired by common data science workflows and aims to provide hands-on experience with linear regression modelling.





