# Milestone 1 - Ideation
encode -> normalize -> train -> evaluate

## Concept 1 
### Wildfire Risk Prediction in the US

Data Sources:

https://firms.modaps.eosdis.nasa.gov/

https://www.ncdc.noaa.gov/

https://www.usgs.gov/core-science-systems/national-land-imaging-program/land-cover

Data Processing:
-Merge datasets on location and date (fire reports + weather)
-Encode vegetation types and soil moisture levels numerically
-Normalize temperature, humidity, and wind speed

80/20 Train/Test Split and Train

Evaluation:
-Calculate accuracy of risk classification using Precision-Recall scores.
-Feature weightage (e.g., temperature vs. wind speed).
-Geo-Heatmaps to visualise high-risk areas.


## Concept 2
### Inflation Analysis with Egg Price Index in the US

Data Sources:

https://data.bls.gov/timeseries/APU0000708111

https://data.bls.gov/dataViewer/view/timeseries/APU0000708111

https://fred.stlouisfed.org/series/APU0000708111

https://tradingeconomics.com/commodity/eggs-us

https://worldpopulationreview.com/state-rankings/egg-prices-by-state

Data Processing:
-Aggregate egg prices by state
-Adjust price accounting for inflation using CPI data

80/20 Train/Test Split and Train

Evaluation:
-Calculate accuracy using RMSE.
-Visualize seasonal patterns and inflation impact on prices
-Predict when current wave of eggflation will end

