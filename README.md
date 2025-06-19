# 📊 Crime Rates in the US using Python
This project analyzes violent crime rates across US states in 1973 using Python and the built-in USArrests dataset. The analysis explores correlations between different crime types and the effect of urban population on crime rates.

## 🧠 Objective
To explore whether violent crime rates are related to one another and whether urban population size correlates with crime:

- Rape vs. Murder

- Murder vs. Assault

- Assault vs. Rape

- Crime vs. Urban Population

## 📁 Dataset
Source: USArrests dataset (via statsmodels)

Variables:

- Murder: Murder arrests per 100,000

- Assault: Assault arrests per 100,000

- Rape: Rape arrests per 100,000

- UrbanPop: Percent urban population

## 📊 Visualizations
### 📦 Boxplots
Boxplots were generated to understand the distribution of each variable:

- Murder

- Assault

- Rape

- Urban Population

### 🔁 Correlation Analysis
Scatter plots with regression lines were created to analyze correlations between:

- Rape & Murder

- Murder & Assault

- Assault & Rape

All three comparisons showed positive correlations.

### 🏙️ Crime vs. Urban Population
Additional scatter plots explored whether each violent crime had a correlation with the urban population percentage:

Weak or no clear trends were found.

## 📈 Summary Statistics
| Variable |	Mean |	Min | Max |
|----------|-------|-------|-------|
| Murder	| 7.79 |	0.8	| 17.4 |
| Assault	| 170.76	| 45 |	337 |
| Rape	| 21.23	| 7.3	| 46 |
| UrbanPop	| 65.54	| 32 |	91 |

## 🧪 Tools & Libraries
Language: Python

Libraries: pandas, matplotlib, numpy, statsmodels

## ✅ Conclusion
All three violent crime types show positive correlations with each other.

Urban population does not appear to be strongly correlated with violent crime rates in this dataset.

Further analysis could include multivariate regression or time-based comparisons using additional datasets.
