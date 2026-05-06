# Used Car Pricing Analysis

## Overview

This project analyzes a dataset of over 400,000 used car listings to identify the key factors that influence vehicle pricing. The goal is to provide actionable insights for used car dealerships to better understand market dynamics and make more informed inventory and pricing decisions.

---

## Key Findings

- **Vehicle age is the strongest driver of price**  
  Cars depreciate quickly in the first few years and then level off, making age a critical factor in pricing.

- **Mileage impacts price, but less than age**  
  Higher mileage generally lowers price, but its effect is smaller when compared to vehicle age.

- **Manufacturer and model significantly influence value**  
  Certain brands and models consistently command higher prices, making them strong candidates for inventory selection.

- **Condition and features contribute to pricing**  
  Better condition, drivetrain, fuel type, and transmission all play a role in determining price.

- **Nonlinear relationships are important**  
  Incorporating polynomial features (e.g., age², mileage², and interactions) significantly improved model performance.

---

## Model Performance

- Final Model: Ridge Regression with Polynomial Features
- R² Score: **~0.69**

This indicates the model explains approximately 69% of the variation in used car prices, representing a strong fit for this type of real-world dataset.

---

## Recommendations

- Focus on **newer vehicles**, especially within the first few years of use
- Prioritize **high-demand manufacturers and models**
- Consider **age and mileage together**, rather than independently
- Use data-driven insights to refine pricing strategies

---

## Notebook

You can view the full analysis and modeling process here:

👉 [View Notebook](./Car_Price.ipynb)

---

## Repository Structure

├── Car_Price.ipynb
├── README.md
├── images/
└── data/

---

## Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
