# D-Project3-U.S.-Traffic-Accident-Analysis-Dashboard


This project analyzed a large-scale dataset of U.S. traffic accidents from **2016–2023**, containing over **7.7 million records** and 46 features across all 49 states.  
Using **PySpark** for preprocessing and **Tableau** for visualization, we developed a scalable analytical dashboard to identify trends, high-risk regions, and contributing factors behind road accidents.

* **Dataset:** U.S. Traffic Accident Dataset (2016–2023, 7.7M records, 46 features).  
* **Tools:** PySpark, Tableau.  
* **Techniques:** Data reduction, feature selection, distributed computing, and interactive dashboard design.  
* **Objective:** Provide policymakers with actionable insights to enhance traffic safety and reduce accidents.  

---

### ⚙️ Data Preparation
- Used **PySpark** to handle large parquet files efficiently (up to 70GB).  
- Compared Pandas vs. PySpark performance — PySpark achieved stable runtime and avoided memory crashes.  
- Selected **14 essential features** (e.g., Severity, Start Time, Weather Condition, Traffic Feature) for focused analysis.  
- Reduced data size from **3.06 GB → 1.53 GB**, improving Tableau performance and stability.  

---

### 📊 Dashboard Components
- **Slicers:** Filter by year and severity to compare accident trends (Current Year vs. Previous Year).  
- **Cards:** Display monthly trends in accidents by severity level.  
- **Map:** Visualizes accident density by severity using color codes (blue–green–orange–red).  
- **Donut Chart:** Shows weather condition proportions during accidents.  
- **Stacked Bar Chart:** Highlights accident frequency near key traffic features (e.g., crossings, junctions, signals).  

<img src="images/US Dashboard1.png" width="700"/>
<img src="images/US Dashboard2.png" width="700"/>
<img src="images/US Dashboard3.png" width="700"/>

---

### 🚦 Key Findings
- **Steady Increase in Accidents:** +74.79% (2016→2017), +24.42% (2017→2018).  
- **Severity 2 Accidents Dominate:** Most common category across all years.  
- **Weather:** ~48% of accidents occurred in clear weather, showing human/infrastructure factors are major causes.  
- **Traffic Signals:** The most common accident location (≈21%).  
- **Urban Hotspots:** Accidents concentrated near major traffic infrastructures and densely populated areas.  

---

### 🔍 Recommendations
- Strengthen driver education and compliance near intersections.  
- Improve signal visibility and timing to reduce signal-related crashes.  
- Use predictive analytics on historical data to allocate enforcement and maintenance resources efficiently.  

---

### 🧠 Skills Demonstrated
- Big data preprocessing with **PySpark**  
- Interactive visualization using **Tableau**  
- Feature selection and data reduction for scalability  
- Analytical storytelling for transportation safety insights  

