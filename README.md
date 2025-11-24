# EV Population Analysis in Washington State:

## Overview
This project analyzes electric vehicle (EV) adoption trends in Washington State. The goal is to identify regional disparities, infrastructure gaps, and awareness challenges, and to provide data-driven recommendations for the Washington State Department of Transportation (WSDOT).

## Dataset
- Source: Washington State EV registration and infrastructure datasets (publicly available or provided by WSDOT).
- Format: CSV/Excel.
- Includes: EV registrations by county, charging station locations, demographic indicators.

## Data Cleaning
- Removed duplicates and irrelevant entries.
- Standardized county and city names.
- Handled missing values in registration and infrastructure data.
- Created derived metrics such as EV adoption rate per 1,000 residents.

## Analysis
- Conducted exploratory data analysis (EDA) in Jupyter Notebook.
- Compared EV adoption across counties and cities.
- Visualized growth trends over time.
- Examined correlations between charging infrastructure, demographics, and adoption rates.
- Built a dashboard to present findings interactively.

## Key Insights
- Leading counties (e.g., King, Snohomish) show strong EV adoption.
- Underserved rural and lower-income counties lag behind due to infrastructure gaps.
- Charging station availability is a key driver of adoption.
- Awareness and policy incentives remain uneven across regions.

## Recommendations
- Expand charging infrastructure in underserved counties.
- Launch targeted awareness campaigns for businesses and policymakers.
- Provide incentives to accelerate adoption in lagging regions.
- Prioritize investments where adoption potential is high but infrastructure is limited.

## Tools & Libraries
- Python: pandas, numpy, matplotlib, plotly
- Jupyter Notebook
- Tableau 
- GitHub
  
## Project Structure

Washington-EV-Capstone/
├── data/ # Dataset, #Raw 
├── notebooks/ # EDA+ Cleanup notebook
├── dashboard/ # Tableau
├── presentation/ # Final PPT
├── README.md 
├── requirements.txt 
└── LICENSE


## Future Improvements
- Add predictive modeling for EV adoption trends.
- Integrate survey data on awareness and policy engagement.
- Automate dashboard updates with live data feeds.

## Acknowledgements
- Washington State Department of Transportation (WSDOT) for data from Data.gov website.

## License
MIT License
