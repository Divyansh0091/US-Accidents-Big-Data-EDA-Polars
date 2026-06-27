# 🚦 US Traffic Accident Analysis: Scalable Big Data Insights (7.7M+ Records)

### 📌 Project Overview
An end-to-end Exploratory Data Analysis (EDA) project focusing on over **7.7 million traffic accident records** across the United States. The primary objective was to move beyond basic descriptive statistics and uncover actionable temporal patterns and rush-hour accident hotspots using high-performance computing techniques.

---

### 🚀 Technical Excellence & Scalability
Processing a 7.7M+ row dataset on standard hardware is a challenge. This project demonstrates:
* **High-Performance Ingestion:** Utilized `Polars` for lightning-fast reading and processing, outperforming traditional Pandas-based workflows in memory-constrained environments.
* **Data Sanitization & Integrity:** * Addressed spatial anomalies by imputing missing coordinate values (`End_Lat`/`End_Lng`) using origin-based logic.
    * Type-casting and optimization for memory-efficient `Float64` precision.
* **Feature Engineering:** Derived high-utility temporal features (`Start_Hour`, `Start_Weekday`) to isolate peak accident windows.

---

### 📊 Key Business Insights (The "So-What?")
The analysis successfully identifies the "Commuter Risk Factor":
1. **Rush-Hour Hotspots:** Accident density spikes significantly during standard morning (07:00–09:00) and evening (16:00–18:00) commute windows.
2. **Weekend Behavior:** A noticeable reduction in accident frequency during weekends suggests that traffic composition—not just volume—is a major contributor to accident severity.
3. **Strategic Utility:** These findings can assist traffic management departments in resource allocation and emergency service positioning during high-risk hours.

---

### 🛠 Tech Stack
| Domain | Tools/Libraries |
| :--- | :--- |
| **Data Processing** | Python, Polars |
| **Data Manipulation** | Pandas (Bridge for Visualization) |
| **Visualization** | Seaborn, Matplotlib |
| **Environment** | Jupyter Lab, Google Colab |

---

### 📈 Visualizing the Trends
*(Insert your heatmap: us_accidents_rush_hour_hotspots.png)*
*This heatmap illustrates the cross-correlation between the time of day and the day of the week, providing a clear visual representation of high-risk accident density.*

---

### 🎓 Lessons Learned
Handling a multi-million row dataset taught me the critical importance of **Lazy Evaluation** and **Memory Management**. It reinforced that clean code isn't just about syntax—it's about building scalable pipelines that handle data growth effectively.

---
*Built with professional rigor for scalable data analysis.*

<img width="857" height="488" alt="us_accidents_rush_hour_hotspots" src="https://github.com/user-attachments/assets/87632872-03c2-42b5-bd7a-2e3afac3c8e4" />
