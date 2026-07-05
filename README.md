# 🏥 Hospital Accessibility Analysis of Sylhet District, Bangladesh



A GIS-based hospital accessibility analysis project developed in QGIS to evaluate the accessibility of healthcare facilities across Sylhet District, Bangladesh. This project uses OpenStreetMap road network data and hospital locations to identify road segments within different service distances from hospitals.



---



## 📌 Project Overview



Access to healthcare is a critical factor in regional planning and public service delivery. This project analyzes hospital accessibility by creating service areas around hospitals and identifying the road network that falls within those accessibility zones.



The analysis focuses on the Sylhet District and visualizes how much of the road network is accessible within a 500-meter distance from hospitals.



---



## 🎯 Objectives



- Analyze hospital accessibility in Sylhet District.

- Create hospital service areas using buffer analysis.

- Identify roads accessible within 500 meters of hospitals.

- Produce professional GIS maps suitable for planning and portfolio presentation.



---



## 🛠 Software Used



- QGIS 3.x

- OpenStreetMap (Geofabrik)

- GADM Administrative Boundary Dataset



---



## 📂 Project Structure



```

project_4_hospital_accessibility_analysis/

│

├── data/

│   ├── raw/

│   └── processed/

│

├── documentation/

│

├── screenshots/

│

├── layouts/

│

├── Hospital_Accessibility.qgz

│

└── README.md

```



---



## 📊 Workflow



1. Download administrative boundary data (GADM).

2. Download OpenStreetMap road and POI datasets from Geofabrik.

3. Extract Sylhet District boundary.

4. Extract hospital locations from POI dataset.

5. Clip road network to Sylhet District.

6. Reproject data to WGS 84 / UTM Zone 46N (EPSG:32646).

7. Create hospital buffers (500 m, 1000 m, and 2000 m).

8. Extract roads within each accessibility zone.

9. Design professional cartographic layouts.



---



## 🗺 Analysis Performed



### Hospital Buffer Analysis



- 500 m Buffer

- 1000 m Buffer

- 2000 m Buffer



### Road Accessibility Analysis



- Roads within 500 m

- Roads within 1000 m

- Roads within 2000 m



---



## 📄 Map Layouts



### Layout 1

**Hospital Accessibility Analysis of Sylhet District**



Displays:



- Hospital locations

- 500 m buffer

- 1000 m buffer

- 2000 m buffer

- Road network

- District boundary



---



### Layout 2

**500 m Hospital Accessibility Road Network Analysis**



Displays:



- Hospitals

- 500 m accessibility zone

- Roads within 500 m

- Sylhet District boundary



---



## 📂 Data Sources



- **Administrative Boundary:** GADM v4.1

- **Road Network & Hospital Locations:** OpenStreetMap (Geofabrik)



---



## 📍 Coordinate Reference System (CRS)



**EPSG:32646**



WGS 84 / UTM Zone 46N



---



## 📸 Project Outputs

## Layout 1 — Hospital Accessibility Analysis

![Hospital Accessibility Analysis](https://github.com/zahid-gis/hospital-accessibility-analysis-sylhet/blob/main/output/layout_1_hospital_accessibility.png)

---

## Layout 2 — 500m Hospital Accessibility Focus

![500m Hospital Accessibility](output/Layout_2_500m_Accessibility.png)



- Hospital Accessibility Map

- 500 m Accessibility Analysis Map

- Hospital Buffer Layers

- Road Accessibility Layers

- Print Layouts

- GIS Project File



---



## 📚 GIS Techniques Used



- Data Extraction

- Attribute Filtering

- Clip

- Reprojection

- Buffer Analysis

- Extract by Location

- Spatial Analysis

- Cartographic Design

- Print Layout



---



## 💼 Skills Demonstrated



- GIS Analysis

- Spatial Analysis

- Healthcare Accessibility Mapping

- Cartography

- OpenStreetMap Data Processing

- QGIS Workflow

- Data Preparation

- Map Layout Design



---



## 👨‍💻 Author

**Zahid Hasan**



Aspiring GIS Analyst 

| Remote Sensing & Spatial Data Enthusiast
