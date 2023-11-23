# Finding Correlations Among Seemingly Unrelated Variables

## Motivation

This project aims to explore the curious intersections between seemingly unrelated variables. Using data from Gapminder, we investigate how total forest area and frequency of natural disasters correlate with a country's obesity and murder rates. This experimental approach seeks to uncover unexpected patterns and draw novel, possibly comical, conclusions.

## Introduction

**Broad Question:** How do total forest area and frequency of natural disasters impact a country's obesity rates and murder rates?

**Data Source:** All data were obtained from Gapminder.

### Dataset Features (`gapminder_all.csv`)

- **Country**
- **Year**
- **Natural Disasters** (Drought, Earthquake, Epidemic, Flood, Storm killed)
- **Total Forest Area** (in square kilometers)
- **Average BMI Rate** (by country and year, for both genders)
- **Murder Rate** (deaths per 100,000)

## Research Questions

1. Which country has the highest homicide rate? Is this an outlier?
2. Do countries with less forest area tend to have higher rates of death by drought?
3. How have global obesity rates changed in countries with high vs. low forest area?
4. Is there a correlation between the likelihood of experiencing a natural disaster and homicidal tendencies?

## Findings

### Overall

1. Earthquakes caused the most deaths on average, while floods caused the least.
2. The global average murder rate is around 7 per 100,000, with a maximum of 131 per 100,000.
3. Droughts show the highest variability in mortality counts.
4. The average total forest area is 18,615 square kilometers.
5. Female BMI scores are more variable and higher on average than male BMI scores.
6. Floods are the most frequent but least deadly natural disaster.

### Detailed Results

#### Question 1: Murder Rate by Country and Year
- Guatemala in 1981 had the highest global murder rate.
- This rate is an outlier, coinciding with the Guatemalan Civil War.

#### Question 2: Total Forest Area and Death by Drought
- Less forest land correlates with higher death rates by drought.
- Statistical analysis shows no significant prediction capability of forest area on drought deaths.

#### Question 3: Total Forest Area vs. BMI Scores
- Countries with less forest area show more variability in BMI scores.
- Forest area is decreasing in more countries than it is increasing.

#### Question 4: Natural Disaster Deaths vs. Murder Rates
- Except for floods, higher natural disaster deaths correlate with lower murder rates.
- Statistical significance found only for Epidemic and Storm deaths.

## Limitations

### Overall
- Incomplete or missing data in several datasets.
- The `df_epidemic` dataset was missing the year 1973.

### Specific to Research Questions
- Guatemala's murder rate data is highly variable and unpredictable.
- Forest area data had significant outliers.
- Countries with no forest area showed high variability in BMI rates.
- Natural disaster data was clustered around 0, complicating analysis.

---

*This project was conducted with the intention of exploring novel relationships between disparate variables. The findings are exploratory and highlight the complexity and nuances in data analysis.*
