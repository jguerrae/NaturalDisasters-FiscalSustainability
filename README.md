# Impact of Extreme Natural Disaster Events on Public Finances

## Description
This repository addresses the profound impact that Extreme Natural Disaster Events (ENDEs) have on public finances, using a methodological approach that combines Local Projection Approximation and Extreme Bound Analysis. The goal is to understand the short and medium-term effects, as well as the long-term fiscal sustainability, of ENDEs in various countries in Latin America and the Caribbean.

## Document Structure
- **Data and Methodology:** Describes the data sources and precisely defines what is considered an ENDE to ensure consistency in our study.
- **Fiscal Sustainability Analysis:** Explores how ENDEs could affect fiscal sustainability through Extreme Bound Analysis (EBA), providing a probabilistic distribution of changes in fiscal reaction.

## Methodology
### Data
A database covering from 2000 to 2020 was constructed, including data from 24 countries in Latin America and the Caribbean, with information sourced from:
- **EM-DAT Database** for natural disaster events.
- **World Economic Outlook (IMF-WEO)** for macroeconomic and fiscal indicators.
- **World Governance Indicators (WGI)** from the World Bank and the financial openness index by Chin and Ito (2021).
- **Brent Price** compiled by FRED.

### Definition of Extreme Natural Disaster Episodes (ENDEs)
An ENDE is classified based on:
- Economic damages reaching or exceeding 2% of GDP.
- The proportion of the affected population surpasses the 95th percentile within the sample.

### Fiscal Sustainability
Fiscal sustainability in the face of ENDEs is examined through EBA, balancing between the approaches of Leamer (1985) and Sala-I-Martin (1997). Fiscal reaction functions are estimated using Pooled OLS under different functional forms:

```math
PB_{i,t} = \beta_0 + \beta_1Debt_{i,t-1} + \alpha_0ENDE_{i,t-1} + \alpha_1Debt_{i,t-1} * ENDE_{i,t-1} + \eta'X_{i,t} + e_{i,t}
```
These equations allow us to evaluate fiscal reaction in response to changes in public debt under the influence of ENDEs, providing a framework to understand fiscal sustainability.

## Data and Sources
Our study integrates data from various reliable sources to ensure a comprehensive analysis of the impact of ENDEs on public finances.

## License
This project is licensed under the MIT License.

### Contact
For inquiries or collaborations, please contact [Jorge Guerra](mailto:ja.guerrae@uniandes.edu.co).
