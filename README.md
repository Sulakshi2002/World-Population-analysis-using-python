# 🌍 World Population Data Analysis

A data analysis project exploring global population trends using Pandas, Matplotlib, and Seaborn.
The dataset includes population counts from 1970–2023, land area, density, growth rate, and continent-level distributions.

📂 Dataset

File: world_population_data.csv
Contains:

Population data from 1970 to 2023

Country, continent, and ISO codes

Land area (km²)

Density (km²)

Growth rate

World population percentage

🔧 Preprocessing

Loaded dataset using Pandas

Checked structure: .head(), .columns, .describe()

Ensured data quality:

No missing values

No duplicate rows

Renamed columns for easier access (e.g., density (km²) → density (km2))

📊 Visualizations

1️⃣ Distribution of 2023 Population

Histogram with KDE curve

Shows how population is spread globally

2️⃣ Average Population by Continent

Grouped by continent

Sorted by highest/lowest average

3️⃣ Top 10 Most Populated Countries

Bar plot ranking countries by 2023 population

4️⃣ Population vs Density

Scatter plot showing relationship between country population and population density

5️⃣ Land Area by Continent

Summed total area per continent

6️⃣ Density Distribution (Violin Plot)

Visualizes density spread within each continent

7️⃣ Density Distribution (Box Plot Without Outliers)

Shows cleaned distribution by removing extreme outliers

🛠️ Technologies Used

Python 3

Pandas

Matplotlib

Seaborn
