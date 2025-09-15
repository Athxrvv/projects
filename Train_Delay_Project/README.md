# project_train_delay 


This project provides a comprehensive analysis of train delays using historical data. Interactive dashboards and visualizations help understand patterns and identify problem areas for operational improvements.

---

## 📝 Key Insights

### 1️⃣ Delay Distribution
- **0–30 min:** Most trains face minor delays (operationally acceptable).  
- **30–60 min:** Moderate delays → noticeable impact.  
- **60+ min:** Few trains face high delays → focus area.  
- **Insight:** Majority of trains have small delays, extreme delays are rare.

![Delay Distribution](figures/categorywise.png)  
*Figure: Category-wise Delay Distribution*

---

### 2️⃣ Yearly Trend
- Average train delay trends over the years indicate periods of increase or decrease.  
- **Insight:** Identifies years with unusual spikes for investigation.

![Yearly Trend](figures/yearly_trend.png)  
*Figure: Yearly Average Train Delay*

---

### 3️⃣ Weekday Trend
- Certain weekdays (e.g., Friday & Saturday) have higher average delays.  
- **Insight:** Specific days require operational focus.

![Weekday Trend](figures/weekday_trend.png)  
*Figure: Weekday-wise Average Delay*

---

### 4️⃣ Source → Destination Heatmap
- Top 10 sources & destinations with highest delays highlighted in heatmap.  
- **Insight:** Routes needing schedule review or operational improvement.

![Source-Destination Heatmap](figures/heatmap_example.png)  
*Figure: Interactive Heatmap with Year + Week Dropdown*

> You can explore the interactive heatmap directly in the notebook.

---

### 5️⃣ Most Frequent / High Delay Trains
- Frequent trains and consistently late trains identified.  
- **Insight:** Focus on improving punctuality for these trains.

![Top Trains](figures/heatmap_example.png)  
*Figure: Top 10 Frequent / High Delay Trains*

---

## 📊 Interactive Dashboard Features
- **Category-wise Delay:** 0–30, 30–60, 60+ min  
- **Yearly Trend:** Line chart showing average delay per year  
- **Weekday Trend:** Bar chart for average delay per weekday  
- **Source → Destination Heatmap:** Interactive, with **Year + Week dropdown**  
- Hover to see exact average delays, zoom/pan available.

---

## 💡 Usage / How to Explore
1. Explore **distribution charts** first → see where most trains fall.  
2. Use **yearly & weekday trends** → understand when delays occur.  
3. Check **top routes & trains** → find problem areas.  
4. Use **interactive heatmap** → select any year & week to analyze route delays.

---

## 🔧 Tech Stack
- Python, Pandas, Matplotlib, Seaborn  
- Plotly for interactive dashboards  

---

## ✅ Conclusion
- Most delays are minor.  
- Specific trains/routes & weekdays require attention.  
- Dashboard allows detailed exploration and operational planning.

---

### 📌 Notes
- Replace `images/...` with actual screenshots or GIFs from your analysis.  
- GIFs can be added using:  
```markdown
![Dashboard Demo](figures/dashboard-demo.gif)
