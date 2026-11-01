# Life Expectancy Analysis

An Excel-based analysis of life expectancy across 163 countries in
2015, completed as a group project for BUSS1020 at the University
of Sydney in November 2025.

## Research question

How are health and socioeconomic indicators associated with
differences in life expectancy across countries?

## Methods

- Data preparation and descriptive statistics
- Visualisation and correlation analysis
- Confidence intervals
- Two-sided Welch's t-test comparing life expectancy between
  high- and low-income-composition groups
- Multiple linear regression and residual diagnostics

## Selected findings

The high-income-composition group had a mean life expectancy of
76.90 years, compared with 65.64 years in the low-income-composition
group. Groups were defined using the sample median income
composition score.

The two-sided Welch's t-test provided evidence of a difference
between the group means. The estimated difference was 11.27 years,
with a 95% confidence interval of approximately [9.66, 12.87].

These findings describe associations and do not establish causality.

## My contribution

My work included data preparation, hypothesis testing, regression
modelling, graphs, organising group meetings, and presentation
materials. Some analysis and presentation work was shared with
teammates, who also contributed to the report.

This repository presents a group coursework project, not solely
individual work.

## Files

- `Life_Expectancy_Analysis.xlsx`: Excel workbook containing data
  and analysis. The `Sheet1` worksheet contains the final
  163-country sample used in the report.
- `Life_Expectancy_Report.pdf`: Revised report.

## How to review

Download the workbook and open it in Microsoft Excel to inspect
the data and calculations. Read the PDF for the methodology,
interpretation, and discussion.

## Limitations and future improvements

- Cross-sectional associations do not establish causal effects.
- Removing countries with missing values may introduce selection bias.
- Independence between countries is an assumption that may be affected
  by shared regional conditions.
- Regression fit was assessed within the analysed sample;
  predictive accuracy on new data was not evaluated.
- The model does not directly estimate the effects of specific
  health interventions.

Future improvements include clearer workbook organisation,
additional checks of variable definitions and units, out-of-sample
validation, and longitudinal analysis.

## Revision note

The report was revised after the original coursework submission
to clarify statistical interpretations and limitations.

## Data source

The dataset was supplied as an Excel file for the University of
Sydney's BUSS1020 coursework. No original public dataset link
was provided.

The final analysis uses 163 countries after cleaning.