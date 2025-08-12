# 🍔 US State Fast Food & Demographics Analysis

## 📌 Overview
This project examines how **state-level demographics**—including obesity scores, unemployment rates, and median household income—relate to **fast-food restaurant choice** across U.S. states. Insights can inform fast-food brands seeking growth strategies.

## 📊 Data
- **Sources**
  - Obesity scores: https://wallethub.com/edu/fattest-states/16585
  - Restaurant counts per state: https://www.nicerx.com/fast-food-capitals/
  - Median household income by state: https://worldpopulationreview.com/state-rankings/median-household-income-by-state
  - Unemployment rates by state: https://worldpopulationreview.com/state-rankings/unemployment-rate-by-state
  - Most popular fast-food by state: https://worldpopulationreview.com/state-rankings/most-popular-fast-food-by-state
- **Description**
  - **Obesity:** `Overall Rank*`, `State`, `Total Score`, `Overweight & Obesity Prevalence`, `Health Consequences`, `Food & Fitness`
  - **Restaurant counts:** `State`, `All fast food restaurants`, `Full-service restaurants`
  - **Income:** `State`, `HouseholdIncome`
  - **Unemployment:** `State`, `rate22`, `rate21`
  - **Most popular chain:** `State`, `MostPopular`
- **Target:** `MostPopular` (state’s most popular fast-food restaurant).
- **Size (approx.):** Obesity ≈ 50×6; Counts ≈ 50×11; Income ≈ 50×2; Unemployment ≈ 50×3; Popularity ≈ 50×2.

## 🛠️ Methods
- **Data gathering & preprocessing:** Web scraping (Python), tidy reshaping, cross-source merges, database table creation and population.
- **EDA:** Choropleth map(s), bar charts.
- **Correlation/association:** Stacked bars, groupwise comparisons, and comparative boxplots.

## 📈 Results
- States whose **most popular chain** is **Chick-fil-A** or **McDonald’s** show **higher obesity scores** on average (in this dataset).
- **Median household income** is **negatively associated** with total obesity scores (lower income ↔ higher obesity score).
- States where **In-N-Out** or **Panda Express** are most popular tend to have **higher median household incomes**, while **Chick-fil-A** states skew lower.
- Restaurant density patterns: more **Dunkin’** per 100k people in states favoring **McDonald’s**; more **McDonald’s** per 100k where **In-N-Out** is most popular.
- **Unemployment**: 2021 averages were **higher** than 2022 across states.
- **Regional pattern**: Most states in the **Southeast/Southwest** (except West Virginia) list **Chick-fil-A** as most popular.
- **Least healthy (by our composite obesity data):** 1) West Virginia  2) Mississippi  3) Kentucky  4) Alabama  5) Arkansas
- **Highest median household income:** 1) Maryland  2) New Jersey  3) Massachusetts  4) Hawaii  5) Connecticut

## 📌 Future Work
- Fit statistical models (e.g., **multinomial/logistic regression**) to estimate adjusted associations between demographics and most-popular chain.
