#  Tracking Unique Insect Species in the City of Melbourne

This project analyzes open biodiversity datasets to track insect species sightings in Melbourne and across Australia. The goal is to identify species unique to specific locations, biodiversity hotspots, and seasonal patterns — supporting urban conservation and planning. Analysis of insect biodiversity in Melbourne using open datasets and the GBIF API. Includes species uniqueness tracking, biodiversity heatmaps, clustering, and seasonal trends for conservation insights.

---

## Project Overview
- Integrated **3 datasets**: BioBlitz 2014, BioBlitz 2016, *Little Things That Run the City*, and live data from the **GBIF API**.  
- Processed and cleaned **1,100+ records** of insect sightings.  
- Applied **geospatial analysis, clustering (DBSCAN)**, and visualizations to detect biodiversity hotspots.  
- Built **interactive maps** (Folium) and **heatmaps** to reveal species richness across Melbourne and Australia.  

---

## Key Findings
- **370+ unique species** recorded, with many only found at a single location → high conservation value.  
- **Royal Park, Carlton Gardens, and Flagstaff Gardens** showed the highest biodiversity in Melbourne.  
- **Seasonal peaks** in Autumn and Spring, matching known insect activity cycles.  
- **Hymenoptera (bees, ants)** emerged as the most diverse order.  
- DBSCAN clustering revealed **dense insect activity zones** in both urban and rural areas.
- This project taught me how data + environment + conservation come together to tell stories about our ecosystems.
-   

---

## Tools & Libraries
- **Python** (pandas, numpy, matplotlib, seaborn)  
- **Geospatial:** geopandas, folium, shapely  
- **Clustering:** scikit-learn (DBSCAN)  
- **Data Sources:** City of Melbourne Open Data, GBIF API  

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/rohang-7/Tracking-unique-insect-species.git
   cd Tracking-unique-insect-species

Install dependencies:
pip install -r requirements.txt


Open the notebook:
jupyter notebook Tracking_Unique_Insect_Species_in_City_of_Melbourne.ipynb


Explore the interactive maps:
unique_species_map → Species distribution map
cluster_map → High-density insect clusters
### 🌍 Interactive Maps

- [Species Distribution Map](https://rohang-7.github.io/Tracking-unique-insect-species/unique_species_map.html)  
- [Insect Clusters Map](https://rohang-7.github.io/Tracking-unique-insect-species/cluster_map.html)


---

## Future Work
- Automate data fetching from APIs for real-time dashboards.  
- Add predictive models to forecast biodiversity shifts under climate change.  
- Extend analysis to birds, mammals, or plants for broader ecosystem insights.  
