# 🚔 Crime and Weather Analysis in Colchester (2023)

## 📊 Project Overview

This project explores how **crime rates in Colchester (UK)** vary across time, space, and **weather conditions**, using a dataset of 6,878 police reports from 2023 and a dataset containing local weather data. Conducted as part of my MSc in Applied Data Science, this project demonstrates how data visualisation can reveal actionable patterns in public safety.

---

## 🎯 Objectives

- Analyse monthly trends in crime frequency  
- Visualise geographic crime hotspots on an interactive map  
- Examine weather variables (sunshine, temperature, visibility, precipitation, wind) and their relation to crime volume and its different types 

---

## 🛠️ Tools & Technologies

- **Language**: R  
- **Libraries**: `dplyr`, `ggplot2`, `leaflet`, `tidyverse`, `lubridate`, `plotly`, `ggcorrplot`, `ggforce`, `knitr`  
- **Techniques**:  
  - Facets with ggplot: pie charts, histograms
  - Geospatial plotting with Leaflet (interactive)
  - Other interactive plots: correlogram, box plots  
  - Time-series visualisation
  - Stacked bar graph   

---

## 📈 Key Insights

- **Violent crime** was the most prevalent, with nearly 2,600 incidents in 2023. Despite this, it also has the highest proportion of the outcome ‘unable to prosecute suspect’, with around 50% of all violent crime resulting in this outcome.
-  The outcome **“investigation complete; no suspect identified”** had the highest proportion among all the outcomes, and that the categories bicycle theft, burglary, arson, other theft, theft from the person, and vehicle crime in particular were most likely to have this outcome.
- The **interactive map** showed high crime density in central Colchester areas.
- **British Transport locations** appeeared to have a much higher proportion of **bicycle theft, other types of theft, and public order offences** compared to other crimes (though more data from various years would be needed to confirm this)
- Crime rates were **highest in January** and **lowest in February**, possibly linked to the holiday period.
- Slight **increase in crime on warm days**  (with exception of January)
- There was generally **less crime when it was less windy**.

---

## 🌍 Visual Outputs

- **Bar Chart**: Frequency of different crime categories
- **Pie Chart Facets**: Proportion of outcomes (e.g. offender given a caution etc.) within each crime category; Proportion of crime categories for each location type
- **Interactive Leaflet Map**: Hotspot visualisation of crime locations
- **Frequency Table**: Frequency of crimes at different location types (British Transport Locations vs Force locations)
- **Line Charts**: Monthly crime trends
- **Interactive Correlogram**: Correlogram of weather variables
- **Boxplots**: Monthly temperatures
- **Histogram Facet**: Sunshine Duration Throughout 2023  


---

## 🧠 What I Learned

- How to create complex plots that are also easy to understand
- How to integrate and analyse multi-source data (weather + crime)  
- Effective use of **interactive geospatial visualisation** tools  
- Communicating complex insights through compelling plots

---

## 📁 Project Structure

📦 crime-weather-analysis/
┣ 📄 Crime_Weather_Analysis.html ← Full interactive report
┣ 📄 README.md ← This file
┣ 📄 /scripts/ ← R script for creating whole Rmd file
┗ 📁 /data/ ← Datasets


---

## 🚀 How to Reproduce

1. Clone the repository  
2. Open the `.Rmd` or `.R` scripts in RStudio  
3. Install required packages:  
   ```R
   install.packages(c("dplyr", "ggplot2", "leaflet", "tidyverse", "lubridate", "plotly", "ggcorrplot", "ggforce", "knitr"))



