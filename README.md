# Project Title: COVID-19 Global Data Tracker

1️⃣ Data Collection

Goal: Obtain a reliable COVID-19 dataset.

✅ Data Sources:
Our World in Data COVID-19 Dataset (CSV & API)
✅ Action:

Download owid-covid-data.csv from the above link.

Save in your working folder.

2️⃣ Data Loading & Exploration

Goal: Load the dataset and explore its structure.

✅ Tasks:

Load data using pandas.read_csv().

Check columns: df.columns.

Preview rows: df.head().

Identify missing values: df.isnull().sum().

✅ Tools:

pandas

📌 Key columns:

date, location, total_cases, total_deaths, new_cases, new_deaths, total_vaccinations, etc.


3️⃣ Data Cleaning

Goal: Prepare data for analysis.

✅ Tasks:

Filter countries of interest.

Drop rows with missing dates/critical values.

Convert date column to datetime: pd.to_datetime().

Handle missing numeric values with fillna() or interpolate().

✅ Tools:

pandas

4️⃣ Exploratory Data Analysis (EDA)

Goal: Generate descriptive statistics & explore trends.

✅ Tasks:

Plot total cases over time for selected countries.

Plot total deaths over time.

Compare daily new cases between countries.

Calculate the death rate: total_deaths / total_cases.

✅ Visualizations:

Line charts (cases & deaths over time).

Bar charts (top countries by total cases).

Heatmaps (optional for correlation analysis).

✅ Tools:

matplotlib

seaborn

5️⃣ Visualizing Vaccination Progress

Goal: Analyze vaccination rollouts.

✅ Tasks:

Plot cumulative vaccinations over time for selected countries.

Compare % vaccinated population.

✅ Charts:

Line charts.

Optional: Pie charts for vaccinated vs. unvaccinated.

✅ Tools:

matplotlib

seaborn

6️⃣ Insights & Reporting

Goal: Summarize findings.

✅ Tasks:

Highlight anomalies or interesting patterns.

Use markdown cells in Jupyter Notebook to write your narrative.

✅ Deliverables:

A well-documented Jupyter Notebook combining:

Code

Visualizations

Narrative explanations
