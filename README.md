# Mathematical & Statistical Analysis for Data Science

## Project Overview

This project demonstrates the practical application of mathematical and statistical concepts used in Data Science using Python.

The notebook covers three major areas:

1. **Linear Algebra Implementation**
2. **Probability Concepts**
3. **Descriptive Statistics**

The objective is to understand how mathematical operations, probability, probability distributions, and descriptive statistics can be implemented and interpreted using Python libraries such as NumPy, Pandas, and the Python `statistics` module.

## Objectives

- Perform vector and matrix operations using NumPy.
- Calculate matrix determinants and inverses.
- Compute eigenvalues and eigenvectors.
- Apply probability concepts to a sales scenario.
- Calculate the probability of successful sales across customer segments.
- Apply Bayes' Theorem.
- Simulate a binomial distribution.
- Generate normal and uniform distributions.
- Calculate descriptive statistical measures.
- Interpret skewness and kurtosis of sales data.

## Project Structure

```text
Mathematical-Statistical-Analysis/
│
├── M3_Mathematical_&_Statistical_Analysis_for_Data_Science.ipynb
├── README.md
└── requirements.txt
```

## Technologies Used

- Python 3
- NumPy
- Pandas
- Statistics (Python Standard Library)
- Google Colab / Jupyter Notebook

## Tasks Covered

### Task 1 – Linear Algebra Implementation

The notebook demonstrates:

- Vector addition
- Vector subtraction
- Dot product
- Matrix addition
- Matrix multiplication
- Determinant
- Matrix inverse
- Eigenvalues
- Eigenvectors

Example vector operations are performed using NumPy arrays, while matrix calculations use NumPy linear algebra functions.

### Task 2 – Probability Concepts

A sales scenario is used to demonstrate probability.

Customer segments:

- Premium
- Regular

The notebook assigns sales-success probabilities and segment-specific purchase probabilities.

The calculated probability of successful sales is approximately **69.5%**.

The purchase probabilities are:

- Premium customers: **80%**
- Regular customers: **50%**

#### Bayes' Theorem

Bayes' Theorem is applied to calculate an updated probability.

The notebook calculates:

**P(A|B) ≈ 0.5161**

or approximately **51.61%**.

#### Binomial Distribution

A binomial distribution is simulated using:

- Number of trials: 20
- Success probability: 0.65
- Number of simulations: 20

#### Normal and Uniform Distributions

The notebook generates:

- A normal distribution with mean = 50 and standard deviation = 10.
- A uniform distribution between 0 and 1.
- 1,000 observations are generated for each distribution.

### Task 3 – Descriptive Statistics

A sample sales dataset containing 20 observations is analyzed.

The following statistical measures are calculated:

| Measure | Result |
|---|---:|
| Mean | 165.5 |
| Median | 165.0 |
| Mode | 135 |
| Range | 90 |
| Variance | 534.75 |
| Standard Deviation | 23.1247 |
| Skewness | 0.0326 |
| Kurtosis | -0.5493 |

## Statistical Interpretation

The sales dataset is approximately symmetric because its skewness is very close to zero.

The skewness value of approximately **0.0326** indicates a very weak positive skew, which is close to a symmetric distribution.

The negative kurtosis value of approximately **-0.5493** indicates that the distribution is flatter and has lighter tails compared with a normal distribution.

The mean (165.5) and median (165.0) are also very close, supporting the observation that the dataset is approximately symmetric.

## Key Learning Outcomes

Through this project, I practiced:

- Numerical computation with NumPy
- Matrix and vector mathematics
- Probability calculations
- Bayes' Theorem
- Probability distributions
- Statistical measures
- Statistical interpretation
- Python-based data analysis

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-link>
cd Mathematical-Statistical-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open the `.ipynb` file using:

- Jupyter Notebook
- JupyterLab
- Visual Studio Code
- Google Colab

### 4. Run the cells

Execute the notebook cells sequentially to reproduce the calculations and outputs.

## Requirements

Create a `requirements.txt` file containing:

```text
numpy
pandas
```

The `statistics` module is part of the Python Standard Library and does not require a separate installation.

## Project Status

**Completed**

This project was created as part of my Data Science learning journey to strengthen my understanding of mathematical and statistical concepts required for data analysis and machine learning.

## Author

**Jaxson**

Aspiring Data Scientist
