# Hydrological Modeling and Watershed Delineation of Sikkim

## 📌 Project Overview
[cite_start]This project presents a comprehensive hydrological analysis of the Sikkim region using Digital Elevation Model (DEM) data[cite: 1, 4]. [cite_start]The goal was to delineate watershed boundaries and map stream networks to understand the drainage patterns of this high-altitude terrain[cite: 14, 21]. [cite_start]The study area is geographically situated between approximately 88.000°E to 89.000°E and 27.000°N to 28.000°N[cite: 2, 3, 5, 6].

## 🛠️ Tools & Technologies
* **Software:** QGIS
* [cite_start]**Process:** Raster Analysis & Hydrological Modeling [cite: 4, 36, 38]
* [cite_start]**Data Source:** Sikkim DEM (Band 1 Gray) [cite: 9, 10]

## 🗺️ Methodology & Workflow
The analysis followed a standardized geospatial workflow to ensure hydrological consistency:

1. [cite_start]**Preprocessing (Sikkim DEM):** Initial processing of the raw elevation data, which identified a vertical relief ranging from **241m** to **7,958m**[cite: 10, 11].
2. [cite_start]**Hydrological Correction (Fill DEM):** Generation of a **Fill DEM** to remove localized depressions (sinks) and ensure continuous flow across the digital surface[cite: 36].
3. [cite_start]**Flow Analysis (Flow Direction):** Computation of a **Flow Direction** model to determine the steepest descent path for every cell in the raster grid[cite: 38].
4. [cite_start]**Watershed Delineation:** Identification of the specific **Watershed Area** and the designation of a precise **Outlet** point[cite: 14, 20].
5. [cite_start]**Stream Ordering:** Classification of the drainage network into a hierarchy of **Stream Orders 1 through 6**[cite: 17, 71, 77].

## 📊 Technical Specifications
| Parameter | Value |
| :--- | :--- |
| **Study Area** | [cite_start]Sikkim, India [cite: 1] |
| **Minimum Elevation** | [cite_start]241 m [cite: 11] |
| **Maximum Elevation** | [cite_start]7,958 m [cite: 10] |
| **Highest Elevation Class** | > [cite_start]6,440 m [cite: 54] |
| **Stream Order Range** | [cite_start]1 - 6 [cite: 17, 77] |

## 📁 Repository Structure
* `/data`: Links to raw DEM files.
* `/Sikkim Hydrology.pdf`: High-resolution final Map.
* `README.md`: Project documentation.

## 📈 Key Insights
* [cite_start]**Extreme Hypsometry:** The elevation analysis highlights a diverse landscape, with significant terrain classified in the highest tier exceeding **6,440m**[cite: 54].
* [cite_start]**Drainage Complexity:** The final model delineates a complex network reaching a **6th-order stream**, indicating a significant catchment area and high runoff capacity for the basin[cite: 19, 77].

## 🤝 Contact & Support
Created by [Hemungshew Borgohain]
* **LinkedIn:** [https://www.linkedin.com/in/hemungshew-borgohain-651ba235a/]
* **GitHub:** [https://github.com/hemungshewborgohain7777]
