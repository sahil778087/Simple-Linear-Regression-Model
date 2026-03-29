# Simple-Linear-Regression-Model
Simple Linear Regression implementation in Python using Scikit-Learn to analyze the correlation between experience and compensation.
# 📈 Salary Prediction using Simple Linear Regression

A Machine Learning project that predicts a professional's salary based on their years of experience using the Simple Linear Regression algorithm.

## 🎯 Project Objective
The goal of this project is to establish a relationship between **Years of Experience** (Independent Variable) and **Salary** (Dependent Variable). This is a fundamental regression task used to demonstrate how a model can learn from historical data to make continuous numerical predictions.

## 🧠 Mathematical Background
The project utilizes the Simple Linear Regression equation:

$$y = \beta_0 + \beta_1 X + \epsilon$$

Based on this specific dataset, the model calculated the following parameters:
* **Intercept ($\beta_0$):** $26,816.19$ (The base salary for 0 years of experience).
* **Slope ($\beta_1$):** $9,345.94$ (The average annual salary increase).

**Final Predictive Equation:**
$$\text{Salary} = 26816.19 + (9345.94 \times \text{YearsExperience})$$

## 🛤️ Workflow Roadmap
1.  **Data Acquisition**: Loading the `Salary_Data.csv` dataset.
2.  **Preprocessing**: Splitting the data into Features ($X$) and Target ($y$).
3.  **Data Partitioning**: Splitting the dataset into Training (2/3) and Test (1/3) sets.
4.  **Model Training**: Fitting the `LinearRegression` model to the training data.
5.  **Prediction**: Estimating salaries for the test set.
6.  **Visualization**: Using `matplotlib` to plot the regression line against actual data points.

## 🧰 Tools & Technologies
| Category | Tool / Library |
| :--- | :--- |
| **Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn |
| **Visualization** | Matplotlib |

## 🚀 How to Use
1. Clone the repository:
   ```bash
git clone https://github.com/sahil778087/Simple-Linear-Regression-Model.git
cd Simple-Linear-Regression-Model
