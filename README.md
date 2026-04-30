# 🌍 Global Environmental Inequality: Who Pays the Price?
## 📌 Overview

This project explores the relationship between economic development, air pollution, and human well-being across countries.

The analysis focuses on answering questions:

- How does economic development relate to environmental impact?
- Do wealthier countries experience cleaner air?
- Where is the human impact of pollution the greatest?

## 📊 Data Sources
The analysis is based on publicly available datasets from Our World in Data:

- CO₂ emissions per capita
- GDP and population
- PM2.5 air pollution exposure
- Life expectancy

All datasets were merged by country and year (2019) to ensure consistency.

## 🛠️ Tools & Technologies
- Python (pandas, matplotlib)
- SQL (SQLite)
- Power BI (data visualization, DAX)
- Jupyter Notebook

## 📊 Dashboard
An interactive dashboard was created in Power BI to visualize key relationships:

- GDP per capita vs air pollution (PM2.5)
- Global distribution of pollution
- Top 10 most polluted countries
- Population-weighted exposure

The dashboard highlights how environmental impact and health risks are distributed across countries.

## 📷 Dashboard Preview

![Dashboard](images/dashboard.png)

## 🧮 DAX Measures
Custom DAX measures were used to enhance the analysis:

Average PM2.5 exposure
Population-weighted PM2.5 (reflecting real human exposure)
Total population

The population-weighted metric provides a more realistic perspective by accounting for where people actually live.

## 🗄️ SQL Component
The cleaned dataset was loaded into a SQLite database to demonstrate SQL querying.

Example analyses included:

Identifying the most polluted countries
Comparing CO₂ emissions per capita
Filtering highly populated countries with high pollution levels

## 🔍 Key Insights
1. Wealth vs CO₂ Emissions

Wealthier countries tend to produce more CO₂ emissions per capita. However, emissions vary significantly across countries with similar income levels.

2. Wealth vs Air Pollution

In contrast, PM2.5 exposure decreases as GDP per capita increases. This suggests that richer countries tend to have cleaner air. 

3. Population Exposure

The highest number of people exposed to air pollution is concentrated in middle-income countries.

4. Pollution and Health

Higher exposure to PM2.5 is associated with lower life expectancy, highlighting the human cost of environmental degradation.

## ⚖️ Conclusion

Environmental impact is unevenly distributed across the world.

While wealthier countries contribute more to global emissions, the health burden of pollution is often greater in less developed and rapidly growing regions.

## 📁 Project Structure
````
global-enviro-project/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ └── 01_data_cleaning.ipynb
│
├── images/
│ └── dashboard.png
│
└── README.md
````

## 👩‍💻 Author
This project was created as part of a personal data portfolio to demonstrate skills in data analysis, visualization, and storytelling.

Kristyna Slamova
- [LinkedIn](linkedin.com/in/kristýna-slámová-3a6905168)
- [GitHub](https://github.com/slamova-labs)
