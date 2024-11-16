## Geospatial Outlier Detection in Sokoto State’s 2023 Elections
This repository contains the analysis and findings from a geospatial outlier detection study conducted on the 2023 elections in Sokoto State, Nigeria. The project explores voting patterns to identify anomalies and potential areas for further investigation.

### Project Overview
This analysis aimed to detect outliers in polling unit (PU) voting patterns using geospatial data, combining Google Sheets for initial data preparation and Python for advanced geospatial analysis. The full documentation detailing the methodology, findings, and insights is available on Medium.

- **Google Sheets Data Preparation:** Geocoded polling unit addresses to derive coordinates (latitude, longitude) for spatial analysis.
- **Geospatial Analysis in Python:** Identified neighboring PUs within a 10 km radius using geodesic distances and calculated outlier scores for each major political party (APC, LP, PDP, NNPP) based on deviations from neighboring units' voting patterns.

### Links to Detailed Documentation
- View Full Analysis on Jupyter Notebook - file:///C:/Users/Kabeera/Downloads/SOKOTO%20Election%20Analysis%20(1).html
- [Read Full Documentation on Medium](https://medium.com/@kabirabusari/geospatial-outlier-detection-in-sokoto-states-2023-elections-40dfb6c6c645)
- [View Google Sheets Data Preparation](https://docs.google.com/spreadsheets/d/1Hg0Ej0GWhARuwYbLwLJXePIE7FLlmIlsxI1W9_MjKI4/edit?usp=sharing)

### Key Findings
- Significant Outliers Identified: The study highlighted PUs with unusually high or low votes, suggesting potential irregularities or unique voting influences.
- APC Top Outliers: GIDAN HABIBU ‘A’ with a score of 112.49.
- LP Top Outliers: OPP BELLO KWARE MOSQUE with a score of 128.74.
- PDP Top Outliers: M.P.S. DUNDAYE with a score of 172.6.
- NNPP Top Outliers: S/ADARAWA with a score of 10.59.
- 
These findings underscore the value of data analysis in enhancing electoral transparency and identifying possible discrepancies in polling data.
