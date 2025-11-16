# Economic History - Assignment 1

This repository contains Assignment 1 for an Economic History course, analyzing the economic impact of the 1929 stock market crash on consumption patterns across U.S. states.

## Authors
- Abdul Baari Bakpa
- Liming Liu
- Vuk Rikanovic
- Zihoa Liu

## Contents

### Assignment Files
- `Assignment1.rmd` - R Markdown source file containing the analysis code and write-up
- `Assignment1.pdf` - PDF output of the assignment
- `Assignment1.html` - HTML output of the assignment
- `Assignment1.docx` - Word document version of the assignment

### Data Files
- `stock_income.xlsx` - Stock market exposure data by state (dividend income and total income)
- `StateNewCarRegistrations.xlsx` - New car registration data by state and time period

## Analysis Overview

This assignment uses a difference-in-differences approach to estimate the causal effect of the 1929 stock market crash on consumption (measured by new car registrations). The analysis:

1. Constructs a measure of state-level exposure to the stock market based on dividend income as a share of total income
2. Estimates how states with higher stock market exposure experienced differential changes in car registrations after the October 1929 crash
3. Evaluates whether this approach captures the "wealth channel" versus the "uncertainty channel" of the crash's economic impact

## Requirements

To run the analysis, you need R with the following packages:
- `tidyverse`
- `readxl`
- `here`
- `fixest`

## Usage

To reproduce the analysis:

```r
# Open Assignment1.rmd in RStudio
# Knit the document to generate PDF/HTML output
```

## License

This is an academic assignment repository.
