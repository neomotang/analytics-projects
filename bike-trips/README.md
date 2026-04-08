# Analysing Bicycle Trips

---

## Overview
In this project, bike trips over the period November 2025 - February 2026 were analysed, as part of the Google Data Analytics Professional certificate. Data source: .csv files at https://divvy-tripdata.s3.amazonaws.com/index.html

## Steps performed
- EDA, normalizing and further transformations of the data in a `Jupyter` notebook using `Python`; a copy of the notebook used is provided (GoogleDataCap.ipynb)
- A star schema was applied and `Tableau` was used to vizualize the data and create the report below:
<img width="1308" height="785" alt="image" src="https://github.com/user-attachments/assets/8d4dad76-1c2e-49eb-9b19-41b0cfd92460" />


### Report interactions
- Cross-filtering and highlighting is enabled between visuals
- The user can also: enter a `Top N` parameter for the top stations information to be summarized; choose a `swap parameter` (either number of trips or trip length) to plot over time; and `show/hide` a map visual displaying the location of the selected top N stations
<img width="1308" height="785" alt="image" src="https://github.com/user-attachments/assets/5a13dbb2-aead-4525-8b00-9482ed2cb09c" />


## Key insights
- Most trips are from registered **Members**, although **Casual** riders tend to take longer trips
- For the top 10 most visited stations, there are slightly more **Electric** bike rides than Classic bike rides; however **Classic** bikes have a longer trip duration
