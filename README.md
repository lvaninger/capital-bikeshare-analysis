# Capital Bikeshare Ride Analysis

## Project Overview

This project analyzes 862,444 Capital Bikeshare trips in Washington, D.C., using Python to identify ridership trends, station usage patterns, and rider behavior.

The goal is to explore how people use the bike-sharing system and identify opportunities to improve bike availability, station utilization, and operational planning.

## Business Questions

- Which stations have the highest and lowest ride activity?
- What days and hours experience the highest ridership?
- How does ridership differ between members and casual riders?
- What is the typical trip duration?
- How much activity comes from the 20 least-used stations?

## Tools & Technologies

- Python
- Pandas
- Plotly Express
- Jupyter Notebook
- Data Visualization
- Exploratory Data Analysis (EDA)

## Key Findings

- **862,444 total rides** across 13 dataset columns.
- **771 unique starting stations** recorded.
- Friday was the busiest day, with approximately 149,000 rides.
- Monday was the least busy day, with approximately 102,000 rides.
- 5:00 PM was the most common rental start hour.
- Members accounted for 549,216 rides, compared to 313,228 casual rides.
- Average trip duration was approximately 18.3 minutes.
- Median trip duration was 10 minutes.
- The 20 least-used starting stations accounted for only 102 rides, or approximately 0.012% of all trips.

## Recommendations

1. Use peak ridership patterns to improve bike distribution and availability.
2. Investigate low-usage stations to determine whether location or awareness contributes to limited activity.
3. Develop targeted promotions to encourage casual riders to become members.
4. Use trip-duration trends to support maintenance and operational planning.

## Data Limitations

Some station names and IDs contain missing values, which may affect station-level comparisons. However, these records can still be included in analyses of trip duration, time, and membership.

Low station usage alone does not establish that a station should be relocated. Additional geographic and operational information would be needed.

## Project Structure

```text
capital-bikeshare-analysis/
│
├── README.md
├── capital_bikeshare_analysis.py
├── requirements.txt
├── .gitignore
│
└── datasets/
    └── README.md
