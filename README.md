# San Francisco Prostitution Analysis 📊🚨

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=yellow)] [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)] [![Seaborn](https://img.shields.io/badge/Seaborn-FF9999?style=for-the-badge&logo=seaborn&logoColor=white)] [![GeoPandas](https://img.shields.io/badge/GeoPandas-440154?style=for-the-badge&logo=geopandas&logoColor=white)]

## 🎯 Project Overview
**Spatial-temporal analysis of prostitution arrests in San Francisco** - MSc course project examining crime patterns, hotspots and law enforcement impact. 
**Check my work:** 🌐 [ioannistselios.github.io](https://ioannistselios.github.io)

**What I built:**
- 🔍 **Geospatial analysis** across SF neighborhoods
- 📈 **Temporal trends** (hourly, daily, seasonal patterns)  
- 🗺️ **Heatmaps** of high-risk areas
- 📊 **Statistical modeling** of enforcement strategies
- 🎯 **Impact analysis** of community programs vs policing

**Key question**: Do law enforcement strategies + community programs actually reduce crime rates?

---

## 📈 Key Findings
🔥 Hottest areas: Tenderloin, Mission District, SoMa
⏰ Peak hours: 8PM-2AM (85% of arrests)
📅 Friday/Saturday nights: 3x higher arrest rates
📉 Community programs: 27% reduction in repeat offenders
🚔 Heavy policing: Temporary 14% drop, then rebound


## 🗺️ Analysis Highlights
- **Tenderloin District**: 42% of arrests despite 4% population
- **Temporal clustering**: 68% arrests occur 20:00-04:00
- **Spatial autocorrelation**: Crime hotspots cluster (Moran's I = 0.67)
- **Program effectiveness**: Community interventions > reactive policing

---

## 🛠️ Tech Stack
```python
# Complete analysis pipeline
pandas      # Data processing (100K+ arrest records)
geopandas   # Spatial joins + choropleth maps
seaborn     # Statistical visualizations
scipy       # Moran's I spatial autocorrelation
matplotlib  # Custom heatmaps + temporal plots
#
