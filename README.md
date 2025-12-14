# 🌍Power-BI-Earthquakes-Report
<img width="972" height="546" alt="Earthquakes Report" src="https://github.com/user-attachments/assets/0fecbf92-93c2-4ef5-bef0-6037bb5c2ee4" />


## 📌 Project Overview
 The report provides a comprehensive view of earthquake frequency, magnitude, depth, temporal trends, and geographic concentration. Its primary purpose is to help analysts, researchers, and decision-makers understand seismic patterns and identify high-risk regions based on historical evidence.

The dashboard is fully interactive, enabling users to filter results by **magnitude type**, **time period**, and **location**, making it a powerful exploratory and analytical tool.

---

## 📊 Key Performance Indicators (KPIs) & Summary Statistics

| Metric | Value |
|------|------|
| **Average Magnitude** | **6.71** |
| **Total Earthquakes Analyzed** | **754** |
| **Magnitude Type** | **mb (Body Wave Magnitude)** |
| **Data Timeframe** | **January 5, 1900 – March 17, 2014** |

These KPIs provide a high-level snapshot of the seismic activity covered in the dataset.

---

## 📈 Core Visualizations & Insights

### 1️⃣ Total Earthquakes by Month
**Visualization Type:** Bar Chart  

**Key Insights:**
- **March** recorded the **highest number of earthquakes (94)**.
- **February** had the **lowest activity (49)**.
- Other relatively high-activity months include:
  - **May (71)**
  - **July (69)**
  - **October (67)**
- Earthquake occurrences show seasonal variation but no extreme monthly outliers.

---

### 2️⃣ Total Earthquakes by Year
**Visualization Type:** Line Chart  

**Key Insights:**
- The period from **1900 to 2014** shows **significant year-to-year volatility**.
- Several sharp spikes indicate years of heightened seismic activity.
- No consistent long-term upward or downward trend is evident, highlighting the unpredictable nature of earthquakes.

---

### 3️⃣ Top 10 Places with Most Earthquakes
**Visualization Type:** Pie Chart  

**Top Locations:**
- **Vanuatu:** **67.06%** (dominant hotspot)
- **Western Luzon, Philippines:** ~**16.4%** (significant contributor)
- **Tonga:** **5.88%**
- **Volcano Islands:** **1.18%**

**Insight:**  
Earthquake activity is **highly concentrated geographically**, with a small number of tectonically active regions accounting for the majority of events.

---

### 4️⃣ Total Earthquakes by Magnitude
**Visualization Type:** Histogram  

**Key Insights:**
- **Magnitude 6:** **131 events** (most frequent)
- **Magnitude 7:** **103 events**
- The distribution is **heavily skewed toward magnitudes 6–7**, indicating that most recorded earthquakes in this dataset are strong to major events.

---

### 5️⃣ Depth Distribution (Depth Histogram)
**Visualization Type:** Histogram  

**Key Insights:**
- **0–100 km (Shallow):** **417 earthquakes**
- **100–200 km:** **187 earthquakes**
- After **200 km**, earthquake frequency drops sharply.
  
**Conclusion:**  
The majority of earthquakes occur at **shallow depths**, which typically pose higher risk to surface infrastructure and populations.

---

### 6️⃣ Depth vs. Magnitude Relationship
**Visualization Type:** Scatter Plot  

**Key Insights:**
- Most **high-magnitude earthquakes (≥6)** are clustered at **depths below 200 km**.
- Deeper earthquakes are less frequent and show more dispersed magnitudes.
- The plot suggests a **moderate inverse relationship** where stronger earthquakes are more common at shallower depths.

---

## 🗂️ Data Source & Timeframe
- **Time Period Covered:** *January 5, 1900 – March 17, 2014*
- **Magnitude Type Used:** *mb (Body Wave Magnitude)*
- The dataset aggregates global earthquake records suitable for long-term trend and distribution analysis.

---

## 🛠️ Tools & Technologies Used
- **Microsoft Power BI**
  - Data modeling
  - Interactive visualizations
  - KPI cards, slicers, and charts
- **DAX (Implicitly via Power BI)** for calculated metrics and aggregations

---

## 🧭 Navigation & Usage Guide
- Use the **slicers at the top** of the report to filter by:
  - **Magnitude Type**
  - **Year range**
  - **Geographic location**
- Hover over charts to view **tooltips with exact values**.
- Click on bars, pie segments, or data points to **cross-filter** all visuals simultaneously.
- Designed for **read-only exploration**, suitable for presentations and analytical reviews.

---

## 📎 Conclusion
This Power BI Earthquakes Report delivers a clear, data-driven understanding of seismic activity across time, depth, magnitude, and geography. It highlights critical patterns such as shallow-depth dominance, regional concentration, and magnitude clustering, making it a valuable asset for data analysts, geoscience enthusiasts, and risk assessment professionals.

---
