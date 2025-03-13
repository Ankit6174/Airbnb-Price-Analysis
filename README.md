# Airbnb EDA Project

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on an Airbnb dataset to uncover key insights about pricing, locations, and listing distributions.

## Dataset Information
- **Source:** `https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data`
- **Columns:** Includes listing details like `price`, `room_type`, `neighbourhood_group`, `latitude`, `longitude`, `reviews`, etc.

## Steps Followed
1. **Data Cleaning & Preprocessing**  
   - Handled missing values, removed duplicates, and converted data types.
2. **Bivariate & Multivariate Analysis**  
   - Price Vs Neighbourhood.
   - Location Vs Price, etc
3. **Geospatial Analysis**  
   - Used `Plotly` to create heatmaps and `Seaborn` for scatter plots.

## Key Insights
- Look at reports folder.

## Project Structure
```
├── data
│   ├── processed
│       ├── raw_data.csv
│   ├── raw
│       ├── cleaned_data.csv
├── notebooks
│   ├── data_cleaning.ipynb
│   ├── EDA.ipynb
├── reports
│   ├── EDA Report.pdf
├── visuals
├── README.md
├── requirement.txt
```

## References
- **Dataset**: `https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data`