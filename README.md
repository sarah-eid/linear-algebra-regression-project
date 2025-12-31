# Linear Algebra Final Project: Normal Equation Implementation

A comprehensive demonstration of solving linear regression problems using pure linear algebra, bypassing iterative algorithms like gradient descent. This project showcases the mathematical foundation of machine learning through an interactive web application that implements the Normal Equation for three real-world datasets.

## Project Overview

This project develops an interactive implementation of the Normal Equation to solve linear regression problems, answering the fundamental question:
**How can we find optimal parameters (θ) directly using matrix operations?**

By implementing core linear algebra concepts (transpose, multiplication, inverse) in JavaScript, we provide an intuitive understanding of how machine learning algorithms work at their mathematical core.

## Key Features

- **Pure Linear Algebra Approach**: Implements the closed-form solution θ = (XᵀX)⁻¹Xᵀy without gradient descent or iterative methods
- **Interactive Web Application**: Complete HTML/CSS/JavaScript implementation with real-time visualizations using Chart.js
- **Step-by-Step Matrix Calculations**: Toggle to view each mathematical operation (Transpose, Multiplication, Inverse) in detail
- **Three Real-World Datasets**: Applied to Housing Prices, Student Performance, and Book Sales scenarios
- **Complete Model Interpretation**: Calculates intercept (θ₀), slope (θ₁), and R² score with practical interpretations
- **No External Dependencies**: Self-contained implementation using only vanilla JavaScript

## Results Summary

### Model Performance Across Datasets

| Dataset | Intercept (θ₀) | Slope (θ₁) | R² Score | Interpretation |
|:--------|:---------------|:-----------|:---------|:---------------|
| **Housing Prices** | 40191.96 | 136.3803 | 99.7% | Excellent fit |
| **Student Performance** | 47.61 | 4.4167 | 93.0% | Good fit |
| **Book Sales** | 32.86 | 3.6308 | 96.7% | Excellent fit |

## Repository Structure
```
├── linear_regression.html          # Main interactive web application
├── Linear Algebra Final Project.pdf # Complete project report
└── README.md                       # Project documentation
```

## Technologies Used

- **Frontend**: HTML5, CSS3 (Custom responsive design with gradients)
- **Programming**: Vanilla JavaScript (ES6) with custom matrix operations
- **Visualization**: Chart.js for dynamic scatter plots and regression lines
- **Mathematical Implementation**: Custom transpose(), matrixMultiply(), and inverse2x2() functions

## Methodology

1. **Mathematical Foundation**: Derivation of the Normal Equation from minimizing the cost function
2. **Matrix Operation Implementation**: Building blocks for transpose, multiplication, and inverse
3. **Dataset Preparation**: Three distinct datasets representing different real-world scenarios
4. **Normal Equation Implementation**: Sequential application of θ = (XᵀX)⁻¹Xᵀy
5. **Visualization & Analysis**: Interactive charts with actual vs. predicted values
6. **Interpretation**: Practical meaning of intercepts, slopes, and R² scores

## Linear Algebra Concepts Demonstrated

### Core Operations
1. **Matrix Transpose**: Flipping rows and columns to align dimensions for multiplication
2. **Matrix Multiplication**: Combining feature information through dot products
3. **Matrix Inverse**: "Dividing" matrices to isolate the parameter vector θ
4. **Closed-Form Solution**: Direct computation versus iterative approximation

## Contributors

- Sarah Eid | [Judy Abuquta](https://github.com/JudyAbuquta) | Nadine Elhaddad | [Abeer Hussain](https://github.com/abeerahrar) 

## How to Use

### Running the Application
1. **Simple Method**: Open `linear_regression.html` directly in any modern web browser
3. **Local Server**: Run a local server for full functionality


---

**Tags**: `linear-algebra` `linear-regression` `normal-equation` `javascript` `machine-learning` `mathematics` `data-science` `matrix-operations` `interactive-learning`
