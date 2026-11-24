# Consumer Behaviour Analysis — Tesco Grocery 1.0

An exploratory data analysis project investigating seasonal grocery purchasing patterns, geographical variations in consumer behaviour and associations between nutritional purchasing patterns and educational attainment across Greater London.

**University of Bath | MSc Data Science | Applied Data Science**

## Project Overview

This project explores the Tesco Grocery 1.0 dataset alongside UK government educational attainment statistics to identify purchasing trends and investigate potential relationships between nutrition and academic performance.

## Datasets

The Tesco Grocery 1.0 dataset represents:

- 420 million transactions
- 1.6 million Tesco Clubcard users
- 411 Tesco stores
- 17 food categories
- Grocery purchases across Greater London during 2015

The analysis uses geographically aggregated data from this dataset.

**Data sources:**
- [Tesco Grocery 1.0 — Scientific Data](https://www.nature.com/articles/s41597-020-0397-7)
- [Department for Education — GCSE Results 2014–2015](https://www.gov.uk/government/statistics/revised-gcse-and-equivalent-results-in-england-2014-to-2015)

## Methodology

- Exploratory data analysis
- Data preprocessing and dataset integration
- Temporal and geographical purchasing analysis
- Literature-driven hypothesis formulation
- Correlation analysis
- Statistical visualisation
- Data storytelling for technical and non-technical audiences

## Key Findings

### Seasonal Purchasing Patterns

- Beer purchases increased during warmer months, while tea and coffee purchases were generally higher during colder months.
- Beer and tea/coffee purchasing patterns exhibited a negative correlation of −0.49.
- Wine and spirit purchases peaked in December.
- Purchasing behaviour varied across London boroughs.

### Nutrition and Educational Attainment

| Purchasing indicator | Reported correlation |
|---|---:|
| Fruits and vegetables | +0.49 |
| Fibre | +0.47 |
| Carbohydrates | −0.26 |
| Sugar | −0.22 |

These findings represent exploratory area-level associations rather than causal relationships.

## Potential Business Applications

- Seasonal demand analysis
- Inventory planning
- Regional product assortment
- Promotional campaign planning
- Consumer behaviour insights

## Limitations

- Selection bias associated with Tesco Clubcard membership.
- Limited coverage of purchases from other retailers.
- Temporal differences between grocery and educational datasets.
- Potential socioeconomic confounding variables.
- Grocery purchases do not necessarily reflect individual dietary consumption.
- Correlation does not imply causation.

## Repository Contents

- [ads_work.ipynb](ads_work.ipynb) — Exploratory data analysis and visualisations.

## Future Improvements

- Incorporate socioeconomic indicators.
- Investigate statistical significance and potential confounding variables.
- Develop an interactive dashboard for regional and seasonal purchasing analysis.
