# 🔐 Visualizing Global Cybersecurity Threats (2015–2024)

**Author:** Nowshika Mirza R  
**Project Type:** Mini Project – Cyber Threat Visualization  
**Tech Stack:** Python, Jupyter Notebook, Pandas, Plotly, Matplotlib, Seaborn, WordCloud  

---
##  ABSTRACT

**Understanding Cybersecurity Risks Through Data Visualization**
In a time when cyber threats are escalating at an alarming pace, data-driven visualization becomes essential for comprehending and addressing these risks. The mini-project, “Visualizing Cyber Threats Using Dataset Logs,” focuses on analyzing extensive cybersecurity data, utilizing visualization and statistical modeling to reveal significant trends, anomalies, and patterns. In today's interconnected world, the ability to swiftly interpret and react to cyber threats can mean the difference between security and vulnerability.
By harnessing Python-based tools like Pandas, Plotly, and Seaborn, this project enables the development of interactive dashboards. These dashboards visually represent critical metrics such as attack frequency, type, region, and severity, providing users with valuable insights into the nature and distribution of cyber threats. This approach not only aids in real-time monitoring but also supports strategic decision-making by highlighting potential vulnerabilities and hotspots.
In today's digital landscape, where data is central to every business and institution, cybersecurity remains a pressing concern. Organizations depend heavily on log data to identify and address potential security threats. This report examines how visualizing cyber threats through dataset logs offers clarity, efficiency, and early detection of attacks. By converting vast amounts of raw data into graphical formats, analysts can identify anomalies, decipher threat patterns, and take proactive measures. This transformation of data into visual insights empowers security teams to act quickly and efficiently, minimizing the potential damage from cyber incidents.
The project utilizes real-world datasets, such as AWS CloudTrail logs, to extract and visualize patterns associated with suspicious activities, failed logins, and privilege escalations. The use of versatile Python libraries, including Pandas, Matplotlib, and Seaborn, underscores the importance of seamless data manipulation and visualization. Through these tools, visualization dashboards illustrate how data can transform into actionable insights. Furthermore, this research underscores the interconnectedness of cybersecurity and global initiatives by emphasizing how strong cybersecurity underpins Sustainable Development Goals (SDGs)—specifically SDG 9 (Industry, Innovation & Infrastructure), SDG 13 (Climate Action), and SDG 16 (Peace, Justice & Strong Institutions). The amalgamation of security, transparency, and sustainability fosters a resilient and ethical digital ecosystem.
It aligns with Sustainable Development Goal (SDG) 16: Peace, Justice, and Strong Institutions by advancing the creation of secure digital environments and robust infrastructures. This is accomplished through promoting transparency and implementing data-driven defense strategies, which are crucial for nurturing peace and justice in the digital sphere. By fortifying digital landscapes, the project contributes to a stable, trustworthy, and equitable online environment, essential for both innovation and societal advancement.

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
