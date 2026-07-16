# earthquake-analysis-dashboard
Interactive Power BI dashboard analyzing global earthquake activity from 2020 to 2025, built using USGS earthquake data. Includes magnitude based geo visualization, regional trends, and KPI tracking.

# USGS Earthquake Dashboard

A Power BI dashboard I built to explore global earthquake activity from 2020-2025, using data from USGS.

## Objectives

Shows where earthquakes are happening around the world, how strong they are, and how frequency has changed year to year. You can filter by year and by magnitude range.

## Data

Earthquake data pulled from the USGS earthquake catalog (2020-2025).

## Content

- KPI cards: total earthquakes, max magnitude, average magnitude, average depth
- Map showing earthquake locations, colored by magnitude (yellow = low, red = high)
- Bar chart of the most active regions
- Line chart of earthquakes per year
- Bar chart breaking down earthquakes by magnitude category
- Year and magnitude filters

## Design

Went with a dark theme + orange/red accent colors, inspired by the "Ring of Fire" since that's where most of the activity is concentrated. The map colors scale with magnitude so the more severe earthquakes stand out.

## Key Insights

- The Pacific "Ring of Fire" is clearly visible on the map — most earthquake activity is concentrated along this belt rather than spread evenly across the globe
- Indonesia had the highest earthquake count in this dataset
- Earthquake frequency has stayed relatively stable year over year from 2020-2025, without major spikes

## Tools

Power BI, Power Query, DAX
