# Analyzing How Different Factors Affect a Billionaire’s Net Worth

## Overview

This project examines how **industry, gender, inheritance, and region** influenced the net worth of billionaires across **1996, 2001, and 2014**. Using **exploratory data analysis** and **regression models**, we identify trends in wealth distribution and analyze the role of key factors in shaping a billionaire’s financial standing.

## Research Question

**How did wealth origin, industry, gender, and region affect the net worth of billionaires in 1996, 2001, and 2014?**

## Data Source

- Dataset: **CORGIS Dataset Project** (Forbes World’s Billionaires lists from 1996, 2001, and 2014).
- Additional variables provided by **Caroline Freund and Sarah Oliver (Peterson Institute for International Economics).**
- Each observation represents an individual billionaire across the three years.

## Key Variables

| Variable                   | Description                                       | Type        |
| -------------------------- | ------------------------------------------------- | ----------- |
| `demographics.gender`      | Male/Female status of the billionaire             | Categorical |
| `location.region`          | Region of residence (e.g., North America, Europe) | Categorical |
| `inherit`                  | Self-made or inherited wealth                     | Categorical |
| `year`                     | The year of billionaire status (1996, 2001, 2014) | Categorical |
| `broad_industry`           | Industry classification of the billionaire        | Categorical |
| `wealth.worth.in.billions` | Net worth in billions                             | Numerical   |

## Methodology

- **Exploratory Data Analysis (EDA):**
  - Visualization of industry representation, gender disparities, and regional wealth distribution.
  - Analysis of wealth origin trends over time.
- **Linear Regression Model:**
  - Dependent variable: `wealth.worth.in.billions`
  - Independent variables: `year`, `inherit`, `broad_industry`, `demographics.gender`, `location.region`
  - **Bootstrapping** to estimate confidence intervals for regression coefficients.

## Key Findings

1. **Industry Trends:**
   - The **Technology and Real Estate sectors** showed a steady increase in billionaire representation.
   - **Finance, Natural Resources, and Retail** remained stable over time.
   - The **Media/Entertainment sector** saw a decline.
2. **Gender Disparity:**
   - Males **dominate** the billionaire status group (\~2000 males vs. <250 females).
   - Female billionaires surpassed male billionaires in **median net worth by 2014** (\$2.4B vs. \$2.1B).
3. **Regional Wealth Trends:**
   - **North America and Europe** had the highest billionaire representation.
   - **South Asia and the Middle East** showed an increase over time.
4. **Inheritance Trends:**
   - **Self-made billionaires became the majority** by 2014, overtaking inherited wealth.
   - Billionaires without inherited wealth experienced more fluctuations in net worth.

## Limitations

- **Limited years (1996, 2001, 2014)** restrict the ability to analyze long-term economic trends.
- **Possible underreporting of billionaire net worth** due to privacy concerns.
- **Low R-squared value in regression model** suggests that additional factors (e.g., business strategies, macroeconomic policies) influence billionaire wealth.

## Future Work

- Expand dataset to include **more years** for a broader trend analysis.
- Incorporate **additional predictors** such as education level, political affiliations, and philanthropy.
- Explore **nonlinear modeling techniques** (e.g., decision trees, random forests) for better wealth prediction.
- Conduct **region-specific** and **gender-specific** analyses for deeper insights.

---

This project provides valuable insights into **billionaire wealth accumulation** and economic trends over time, highlighting **systemic advantages, barriers, and industry transformations**.

