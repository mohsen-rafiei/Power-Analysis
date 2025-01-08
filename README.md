# Power Analysis Project

This project demonstrates how to perform power analysis in UX and HF research. Power analysis is crucial for determining the sample size needed to detect meaningful effects with specified confidence and power levels.

---

## Overview

Power analysis ensures that your study has enough participants to detect an effect if one exists. This project includes:
1. **Two-Sample t-Test**: Calculates the sample size needed to compare two groups.
2. **One-Way ANOVA**: Estimates the sample size required for a one-factor experimental design with multiple groups.

---

## Files Included

1. **`power_analysis_data.csv`**  
   - A dataset with simulated scores for two groups (`Group_1` and `Group_2`).

2. **`power_analysis.Rmd`**  
   - An R Markdown file that includes:
     - Data visualization.
     - Effect size calculation (Cohen's d for t-tests, Cohen's f for ANOVA).
     - Power analysis for t-tests and ANOVA.

---

## Steps to Run the Analysis

1. **Download the Files**:  
   Clone this repository or manually download the files.

2. **Install Required R Packages**:  
   Install the following R libraries:
   ```R
   install.packages(c("tidyverse", "pwr"))
   ```

3. **Open and Run the R Markdown File**:  
   Open `power_analysis.Rmd` in RStudio. Knit it to generate an HTML report that provides:
   - Effect size calculations.
   - Required sample sizes for t-tests and ANOVA.

---

## Why Perform Power Analysis?

1. **Avoid Underpowered Studies**: Ensure you have enough participants to detect meaningful effects.
2. **Resource Efficiency**: Avoid unnecessary recruitment of participants beyond what’s needed.
3. **Scientific Rigor**: Report effect sizes and power to validate your experimental results.

---

## Contribution

Suggestions for improvement? Found an issue? Open a pull request or raise an issue to contribute.

---

## License

This project is licensed under the [MIT License](LICENSE). Use, adapt, and share it freely with proper attribution.
