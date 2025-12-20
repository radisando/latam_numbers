## 🌎 Latin America in Numbers

Latin America in Numbers is a data visualization project designed to explore and compare key social and macroeconomic indicators across Latin American countries. **The goal of this project is
to present regional data in a clear, interactive, and visually engaging way**, enabling quick comparisons and a better understanding of long-term trends.

The project **combines data engineering in Python with interactive charts built in Tableau**, using trusted international data sources such as the World Bank, UNDP, and the World Happiness Report.

🔗 Check out the final result here: 
[Latin America in Numbers - Interactive Dashboard](https://public.tableau.com/app/profile/rafael.sandoval/viz/LatinAmericainNumbers/LATAM)

<img width="2227" height="1366" alt="image" src="https://github.com/user-attachments/assets/f01dc08d-458e-451b-a86e-b6d7c4e7531a" />


### 📌 Project Scope

This dashboard focuses on the following indicators:

- Total Population

- Gross Domestic Product (GDP)

- GDP per Capita (PPP)

- Life Expectancy at Birth

- Happiness Index

- Human Development Index (HDI)

Data was collected, cleaned, and harmonized by myself using Python notebook to ensure comparability across countries.


### 📚 Data Sources

- World Bank – Population, GDP, GDP per Capita, Life Expectancy

- World Happiness Report (2024) – Happiness Index

- UNDP Human Development Reports (HDI)

All sources are publicly available and widely used in economic and social analysis.


### 🖥️ Python Notebooks

The Python workflow includes:

- Manual mapping of Latin American countries to ISO codes

- Data retrieval from the World Bank API (Population, GDP, Life Expectancy)

- Integration of external datasets (Happiness Index, HDI)

- Data cleaning, formatting, and validation

- Selection of the latest available year per indicator (either 2023 or 2024)

- Export of Tableau-ready datasets as CSV


### 💻 Tableau Integration

- Loaded the final CSV file into Tableau

- Built individual charts per indicator

- Used parameters and control visibility to switch between metrics

- Combined all views into a single interactive dashboard
