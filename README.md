# MPG Analysis: Manual vs Automatic Transmissions

## 📊 Project Overview

This project investigates whether manual or automatic transmission vehicles are more fuel efficient, using the `mtcars` dataset. The analysis is part of the Coursera Regression Models course and aims to apply linear regression techniques to a real-world dataset.

## 🎯 Objective

- Determine if transmission type (manual vs. automatic) significantly affects miles per gallon (MPG)
- Quantify the difference in MPG between transmission types
- Adjust for other variables (e.g., weight, horsepower, number of cylinders) that may also affect MPG

## 🧪 Methods

- **Exploratory Data Analysis (EDA)**: Summary statistics and visualizations were used to compare MPG across transmission types.
- **Simple Linear Regression**: Initial model with only transmission as a predictor.
- **Multiple Linear Regression**: Final model included weight, horsepower, and number of cylinders to adjust for other influencing factors.
- **Model Diagnostics**: Residual plots were analyzed to validate model assumptions.

## 📁 Files Included

- `regression_mpg.Rmd` – R Markdown file with full analysis
- `regression_mpg.pdf` – Knitted report (PDF output)
- `README.md` – Project summary and instructions

## 🧵 How to Knit

To knit the R Markdown file to PDF:

1. Open `regression_mpg.Rmd` in RStudio
2. Make sure required libraries are installed: `tidyverse`
3. Knit to **PDF** or **HTML**
   - For PDF, you may need to install TinyTeX:
     ```r
     install.packages("tinytex")
     tinytex::install_tinytex()
     ```

## ✅ Project Status

✔️ Completed and submitted for peer review as part of the Regression Models course.

---

## 📌 Author

**Daniel Aklilu**  
August 2025
