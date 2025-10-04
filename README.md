# 🚗 US Road Accidents Analysis (2016–2023)

## 📖 Table of Contents

* [Project Overview](#project-overview)
* [Purpose](#purpose)
* [Features](#features)
* [Technology Stack](#technology-stack)
* [Project Structure](#project-structure)
* [Installation & Setup](#installation--setup)
* [Usage Guide](#usage-guide)
* [Analysis Components](#analysis-components)
* [Key Findings](#key-findings)
* [Data Processing](#data-processing)
* [Contributing](#contributing)
* [Known Limitations](#known-limitations)
* [License](#license)
* [Team](#team)
* [Acknowledgements](#acknowledgements)

---

## 🧭 Project Overview

This project presents a comprehensive data science analysis of **US Road Accident Data (2016–2023)** using more than **7 million accident records**.
The goal is to uncover hidden trends, evaluate risk factors, and visualize how different elements such as weather, infrastructure, and time influence accident severity.

By leveraging data-driven insights, this project aims to support traffic safety improvements, informed policymaking, and public awareness.

---

## 🎯 Purpose

* Identify **key patterns and risk factors** contributing to road accidents.
* Support **data-driven decision-making** in traffic management and safety initiatives.
* Deliver **insightful visualizations** for policymakers and researchers.
* Encourage the development of **preventive strategies** to reduce accident rates.

---

## ⚙️ Features

### 🔍 Core Analytical Components

* **Univariate Analysis:** Explore the distribution of key variables (e.g., severity, time, weather).
* **Bivariate Analysis:** Study relationships between accident factors.
* **Multivariate Analysis:** Use correlation and dimensionality reduction (PCA) to reveal deeper trends.
* **Geospatial Mapping:** Identify high-risk regions and accident hotspots.
* **Temporal Insights:** Analyze patterns across days, months, and seasons.

### 📊 Visualization Capabilities

* Interactive heatmaps
* Geographic accident plotting
* Statistical distribution plots
* Correlation matrices
* Time series visualizations
  
---

## 🧰 Technology Stack

### 🐍 Core Technologies

* **Python 3.x**
* **Jupyter Notebook**

### 🧩 Key Libraries

| Category            | Libraries                         |
| ------------------- | --------------------------------- |
| Data Manipulation   | `pandas`, `numpy`                 |
| Visualization       | `matplotlib`, `seaborn`, `folium` |
| Geospatial Analysis | `geopandas`, `shapely`            |
| Data Access         | `kaggle`                          |

---

## ⚙️ Installation & Setup

1. **Clone the repository**

2. **Install dependencies**

   ```bash
   pip install pandas numpy matplotlib seaborn folium geopandas shapely
   ```

3. **Download the dataset**

   * Obtain the dataset from Kaggle (US Accidents Dataset 2016–2023).

4. **Run Jupyter Notebooks**

   * Open the notebooks in sequence for step-by-step analysis.

---

## 🚀 Usage Guide

* Start with the **EDA notebook** to understand data composition and quality.
* Progress through **univariate → bivariate → multivariate → geospatial** notebooks.
* Run each notebook cell-by-cell to generate updated visualizations and statistics.
* View exported plots in the `visuals/` directory.

---

## 🧩 Analysis Components

| Component                 | Description                                                      |
| ------------------------- | ---------------------------------------------------------------- |
| **EDA Overview**          | General understanding, missing value treatment, and data checks. |
| **Univariate Analysis**   | Frequency and distribution of individual variables.              |
| **Bivariate Analysis**    | Pairwise relationships (e.g., severity vs. weather).             |
| **Multivariate Analysis** | Correlation, PCA, and combined feature impact.                   |
| **Geospatial Analysis**   | Mapping and density visualization of accident locations.         |
| **Hypothesis Testing**    | Validating assumptions about time, weather, and region effects.  |

---

## 📈 Key Findings

### 🌦️ Weather Impact

* Accidents increase significantly in **rainy, foggy, and snowy** conditions.
* **Poor visibility** correlates strongly with higher severity levels.
* **Clear weather** sees more frequent accidents but with lower severity.

### 🏙️ Infrastructure Influence

* **Traffic signals, crossings, and urban intersections** contribute heavily to accident density.
* **Urban clusters** show more frequent but less severe accidents compared to rural zones.

### ⏰ Temporal Patterns

* Peak hours correspond to **morning and evening rush times**.
* **Seasonal variations** show increased incidents during winter and rainy months.

---

## 🧹 Data Processing

* Removal of **duplicates** and handling **missing values**.
* Conversion of timestamps into **date–time features** (hour, weekday, season).
* Encoding categorical variables for compatibility with analysis.
* Creation of **engineered features** (e.g., visibility levels, weather categories).

---

## 🤝 Contributing

Contributions are always welcome!
To contribute:

1. Fork this repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request describing your improvements

Please ensure code quality, clear commit messages, and proper testing.

---

## ⚠️ Known Limitations

* Dataset may not include every accident type or region.
* Some features contain **incomplete or inconsistent values**.
* The project provides **observational insights**, not definitive causal relationships.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify with attribution.
See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

* Dataset: [US Accidents Dataset (Kaggle)](https://www.kaggle.com/sobhanmoosavi/us-accidents)
* Libraries: Python, Pandas, NumPy, Seaborn, Matplotlib, GeoPandas
* Inspiration: Real-world data-driven policymaking for road safety

---

Would you like me to **add badges (for Python version, license, dataset, or contributions)** and make it look like a professional **GitHub-style visual README** with emojis and color tags (e.g., shields.io badges)?
It’ll give it a polished open-source project look.
