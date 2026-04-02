# 📊 Applied Statistics in R: Distributions, Hypothesis Testing & Regression

[![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)](https://www.r-project.org/)
[![Statistics](https://img.shields.io/badge/Statistics-Hypothesis_Testing-blue?style=flat)](#)
[![Data Analysis](https://img.shields.io/badge/Data_Analysis-Regression-green?style=flat)](#)

## 📖 Project Overview
This repository contains a comprehensive suite of applied statistical analyses conducted in **R**. The project demonstrates how to solve real-world engineering, scientific, and socio-economic problems using probability distributions, rigorous hypothesis testing, and predictive linear regression models. 

By transitioning from theoretical mathematics to practical R programming, this repository showcases the end-to-end process of data evaluation, statistical computation, and graphical visualization.

## 🗂️ Analytical Modules

### Section 1: Normal & Sampling Distributions
This module explores cumulative probabilities and inverse distributions across various industrial and consumer scenarios using `pnorm()` and `qnorm()`.
* **Materials Engineering:** Evaluated the ultimate tensile strength (UTS) of two metal alloys to determine failure probabilities below critical thresholds.
* **Predictive Maintenance:** Calculated the upper-tail mileage (top 8%) for vehicle timing belt lifespans to inform manufacturer replacement schedules.
* **Consumer Electronics:** Utilized the Standard Error of the Mean (SEM) to predict the average lifespan distribution of cell phone batches.
* **Civil Engineering:** Assessed the probability of concrete compression strength failing to meet the required 5000 psi standard.
* **Energy Sector:** Modeled the distribution of horizontal oil well depths in Alberta to identify the deepest 15% of drilling operations.

### Section 2: Hypothesis Testing
This module applies inferential statistics to determine if observed differences in data are statistically significant or due to random chance.
* **Proportion Testing (Z-Test):** Analyzed a massive dataset of AP Exam scores (over 350,000 students) using `prop.test` to prove a statistically significant difference in calculus exam participation between male and female students (p < 0.05).
* **Paired T-Tests:** * Compared wholesale seafood prices between East Coast and West Coast suppliers, finding no statistically significant difference in pricing.
  * Evaluated UK Department of Transportation data to determine if traffic and activity patterns change significantly on "Friday the 13th" compared to the 6th of the month.

### Section 3: Correlation & Linear Regression
This module builds predictive models and evaluates the strength of relationships between continuous variables using `cor()` and `lm()`.
* **Electrical Engineering:** Modeled the relationship between current (amps) and effective power (watts) in a circuit. Developed a linear regression equation (y = 3.11 + 1.18x) with an R-squared value of 66.59% to predict power delivery.
* **Socio-Economic Traffic Patterns:** Conducted a deep-dive regression analysis on the Friday the 13th traffic data. Discovered a near-perfect positive correlation (r = 0.9999), proving that overall baseline traffic volume dictates activity far more than the superstition of the date itself.

## ⚙️ Methodology & R Functions
* **Distributions:** `pnorm()`, `qnorm()`, `dnorm()`
* **Hypothesis Testing:** `t.test(paired = TRUE)`, `prop.test()`
* **Regression & Correlation:** `lm()`, `cor()`, `predict()`, `summary()`
* **Visualizations:** Base R graphics (`plot()`, `curve()`, `polygon()`, `abline()`) were utilized extensively to shade rejection regions, plot lines of best fit, and visually validate calculated p-values and Z/T-statistics.

## 💻 How to Run Locally

1. Clone the repository to your local machine.
2. Ensure you have R and RStudio installed.
3. Open the R scripts corresponding to each section.
4. *Note: Datasets for the Seafood Pricing and Friday the 13th Traffic are fetched directly via URL within the scripts. An active internet connection is required to run those specific chunks.*
5. Run the scripts to generate the statistical summaries and density/scatter plots in your R plotting window.

---

### 📝 Repository Description & Topics (For GitHub Settings)

**Description:**
> 📊 Applied statistical analysis in R featuring Normal/Sampling Distributions, Hypothesis Testing (Z-tests, Paired T-tests), and Linear Regression. Includes real-world case studies in engineering, economics, and logistics.

**Topics (Tags):**
* `r`
* `rstats`
* `hypothesis-testing`
* `linear-regression`
* `probability-distributions`
* `statistical-analysis`
* `predictive-modeling`

**✍️ Author**
Oluwafemi Gabriel, James
*Applied Statistics | Data Analysis*
