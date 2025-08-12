# 🍔 US State Fast Food & Demographics Analysis

## 📌 Overview
[Summarize the project aim, research question, and relevance.]
In this project, we answer the central question: How is fast food restaurant choice across the US states affected by the number of given fast food restaurants in each state, obesity rates, unemployment rates, 
and median household income? The answer to this question informs these various fast food restaurants how they can gain more customers in the future, considering demographic information.

## 📊 Data
- **Sources:**
  - [Obesity Scores](https://wallethub.com/edu/fattest-states/16585)
  - [Number of fast food restaurants per state](https://www.nicerx.com/fast-food-capitals/)
  - [US State Median Household Income](https://worldpopulationreview.com/state-rankings/median-household-income-by-state)
  - [US State Unemployment Rates](https://worldpopulationreview.com/state-rankings/unemployment-rate-by-state)
  - [US State Most Popular Fast Food Restaurants](https://worldpopulationreview.com/state-rankings/most-popular-fast-food-by-state)
- **Description:**
  - **Obesity Scores:** `Overall Rank*`, `State`, `Total Score`, `Overweight & Obesity Prevalence`, `Health Consequences`, `Food & Fitness`
  - **Number of fast food restaurants per state:** `State`, `All fast food restaurants`, `Full-service restaurants`
  - **US State Median Household Income:** `State`, `HouseholdIncome`
  - **US State Unemployment Rate:** `State`, `rate22`, `rate21`
  - **US State Most Popular Fast Food Restaurants** `State`, `MostPopular`
- **Target:** Most popular fast food restaurants.
- **Size (approx.):** Obesity Scores ≈ 50 × 6; Number of fast food restaurants per state ≈ 50 × 11; US State Median Household Income ≈ 50 × 2; US State Unemployment Rate ≈ 50 × 3; US State Most Popular Fast Food Restaurants ≈ 50 × 2

## 🛠️ Methods
- **Data gathering & preprocessing:** Web scraping (Python), manipulating data to be tidy, combining data, creating database, creating tables in database, populating tables in database
- **EDA:** Visualizations including Cloropleth map, bar plots
- **Correlation Analysis:** Visualizations including stacked bar plots, bar plots, and comparative box plots

## 📈 Results
- On average, states who had Chick-fil-a or McDonalds as their most popular fast food restaurant saw higher obesity scores. 
- There is a correlation between median income and total obesity scores. The lower a state's median income, the higher a state's obesity score was.
- Generally, states who had In-N-Out or Panda Express as their most popular fast food restaurant saw higher median household income. Chick-Fil-A saw lower median household income. 
-There seemed to be more Dunkin Donuts per 100,000 people in the states that had McDonalds as their favorite fast food restaurant. There seemed to be more McDonalds per 100,000 people in the states that had In-N-Out as their favorite fast food restaurant. 
-2021 saw much higher average unemployment rates than 2022 did. 
-All of the states in the southeast and southwest region with the exception of West Virginia all had Chick-fil-a as their most popular fast food restaurant.
-The least healthy states based on our data are:
West Virginia
Mississippi
Kentucky
Alabama
Arkansas
-The highest median household income states are:
Maryland
New Jersey
Massachusetts
Hawaii
Connecticut

## 📌 Future Work
In the future, statistical models such as logistic regression could be conducted to get a more concrete estimate on the relationship between state demographics and fast food restaurant choice. 
