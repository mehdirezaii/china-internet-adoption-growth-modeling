# China Internet Adoption Growth Modeling

## Overview

This project analyzes the growth of internet adoption in China from 2000 to 2023 using nonlinear regression techniques.

The main objective is to explore historical internet usage data, fit different mathematical models, and compare their performance in describing the observed growth pattern.

Three nonlinear regression models are implemented and evaluated:

- **Exponential Regression**
- **Logarithmic Regression**
- **Sigmoid (Logistic) Regression**

## Project Objectives

- Analyze the historical growth of internet usage in China.
- Visualize trends and patterns in the dataset.
- Implement different nonlinear regression models.
- Estimate model parameters using curve fitting.
- Compare model performance using statistical evaluation metrics.
- Investigate which mathematical model best represents the observed data.

## Dataset

The dataset contains annual internet usage statistics for multiple countries.

For this project, data corresponding to **China** is extracted and analyzed.

- **Country:** China
- **Time Period:** 2000–2023
- **Target Variable:** Internet Usage (%)
- **Observation Frequency:** Annual

## Models

### 1. Exponential Regression

Used to investigate exponential growth patterns in internet adoption.

### 2. Logarithmic Regression

Used to examine growth patterns characterized by rapid initial changes followed by a decreasing growth rate.

### 3. Sigmoid Regression

Used to model S-shaped growth patterns, including an initial slow-growth phase, a rapid-growth phase, and a gradual slowdown toward an upper limit.

## Technologies and Libraries

The project is implemented in Python using the following libraries:

- **NumPy:** Numerical computations
- **Pandas:** Data manipulation and analysis
- **Matplotlib:** Data visualization
- **SciPy:** Nonlinear curve fitting
- **Scikit-learn:** Model evaluation metrics

## Evaluation Metrics

The models are evaluated using:

- **R² (Coefficient of Determination):** Measures how well the model explains the variation in the observed data.
- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction error while giving greater weight to larger errors.

## Project Structure

```text
china-internet-adoption-growth-modeling/
│
├── data/
│   └── internet_usage.csv
│
├── notebooks/
│   └── china_internet_adoption_modeling.ipynb
│
├── README.md
└── requirements.txt
```

## Installation and Usage

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/china-internet-adoption-growth-modeling.git
```

2. Navigate to the project directory:

```bash
cd china-internet-adoption-growth-modeling
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the project notebook and run the cells.

## Key Considerations

The percentage of internet users is naturally bounded between 0% and 100%. Therefore, the sigmoid model provides an interesting mathematical approach for representing adoption processes with an upper limit.

However, a model's suitability should not be determined by its visual appearance alone. Evaluation metrics and performance on unseen data are also important when comparing regression models.

## Conclusion

This project demonstrates how nonlinear regression techniques can be applied to real-world data to investigate and model technological adoption trends.

It also provides a practical comparison of exponential, logarithmic, and sigmoid functions in the context of internet adoption growth in China.

---

**Project Focus:** Machine Learning | Nonlinear Regression | Data Analysis | Python