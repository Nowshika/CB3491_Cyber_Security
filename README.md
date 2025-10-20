# 🔐 Visualizing Global Cybersecurity Threats (2015–2024)

**Author:** Nowshika Mirza R  
**Project Type:** Mini Project – Cyber Threat Visualization  
**Tech Stack:** Python, Jupyter Notebook, Pandas, Plotly, Matplotlib, Seaborn, WordCloud  

---

## 🖥️ Project Overview

Cybersecurity threats have grown exponentially in the last decade, targeting organizations across industries and countries worldwide. This project provides a **comprehensive visualization of global cyber threats from 2015 to 2024**, analyzing trends, financial losses, affected users, incident resolution times, and defense mechanisms.  

The visualizations aim to provide **actionable insights** for cybersecurity analysts, educators, and enthusiasts, highlighting the most frequent attack types, high-risk industries, and countries most affected by cyber attacks.  

---

## 📚 Extended Description

### 🔹 Context
Cyber attacks such as ransomware, phishing, DDoS, and malware are not only increasing in frequency but also in sophistication. Understanding historical trends helps organizations and policymakers **strategically plan defense mechanisms**, allocate resources, and mitigate risks.  

This project leverages **real-world cybersecurity datasets** to create an **interactive and insightful dashboard** for visual exploration of cyber threats over the last decade.

### 🔹 Objectives
- Identify **financial loss trends** over the years by attack type.  
- Highlight **industries most affected** by cyber attacks.  
- Analyze **average incident resolution times** by attack source.  
- Visualize **attack type distribution** using word clouds and pie charts.  
- Explore **security vulnerabilities and defense mechanism usage**.  
- Generate **advanced visualizations** like heatmaps, correlation matrices, and ransomware trend analysis.  

### 🔹 Methodology
1. **Data Loading & Cleaning:** Read the dataset, fill missing values, convert categorical columns.  
2. **Exploratory Data Analysis:** Summarize the dataset, identify top attack types, industries, and countries.  
3. **Interactive Visualizations:** Using Plotly to create dynamic bar charts, pie charts, and line plots.  
4. **Static Visualizations:** Matplotlib and Seaborn for heatmaps, boxplots, and correlation matrices.  
5. **Word Cloud Analysis:** Highlight frequent attack types for a visual summary of threats.  
6. **Advanced Analysis:**  
   - Heatmap of attack types vs. target industries (financial loss).  
   - Yearly ransomware financial loss trend.  
   - Correlation of numeric features to explore relationships between losses, affected users, and resolution times.

---

## 📊 Dataset

- **File:** `Global_Cybersecurity_Threats_2015-2024.csv`  
- **Columns Include:**  
  - `Year` – Year of the incident  
  - `Attack Type` – Type of cyber attack  
  - `Target Industry` – Industry affected  
  - `Target Country` – Country affected  
  - `Number of Affected Users` – Users impacted  
  - `Financial Loss (in Million $)` – Estimated financial impact  
  - `Incident Resolution Time (in Hours)` – Time to resolve the attack  
  - `Attack Source` – Origin of attack  
  - `Security Vulnerability Type` – Vulnerabilities exploited  
  - `Defense Mechanism Used` – Mitigation strategies applied  

---

## 🔧 Technologies & Libraries Used

- **Python 3**  
- **Jupyter Notebook**  
- **Libraries:**  
  - `pandas` – Data manipulation and aggregation  
  - `plotly` – Interactive visualizations (bar, line, pie)  
  - `matplotlib` – Static plots and word clouds  
  - `seaborn` – Heatmaps and advanced visualization  
  - `wordcloud` – Display frequent attack types  

---

## 📈 Key Visualizations

1. **Financial Loss Over Years by Attack Type** – Interactive grouped bar chart.  
2. **Top Target Industries by Affected Users** – Horizontal bar chart.  
3. **Average Incident Resolution Time by Attack Source** – Interactive bar chart.  
4. **Common Cyber Attack Types** – Word cloud visualization.  
5. **Attack Type Distribution** – Interactive pie chart.  
6. **Financial Loss by Industry** – Top 15 industries, colored bar chart.  
7. **Incident Resolution Time Distribution** – Boxplot showing variance.  
8. **Top Security Vulnerability Types** – Horizontal bar chart.  
9. **Defense Mechanism Usage** – Donut chart visualization.  
10. **Attack Types vs Target Industries Heatmap** – Visualizing financial loss correlation.  
11. **Yearly Ransomware Financial Loss Trend** – Line chart with markers.  
12. **Correlation Matrix** – Numeric features correlation heatmap.

---

## 💻 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/CyberThreatsVisualization.git
