<div align="center">

# 📊 Social Media Sentiment Analysis

### Turning Social Media Data into Actionable Business Insights

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Analytics-107C10?style=for-the-badge)](https://learn.microsoft.com/dax/)
[![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-007ACC?style=for-the-badge)](https://github.com/)
[![Status](https://img.shields.io/badge/Project-Completed-2EA44F?style=for-the-badge)](https://github.com/)

**An interactive Power BI dashboard for understanding sentiment, engagement, platform performance, and trends across social media data.**

<br>

### ⭐ If you find this project useful, consider giving it a star!

</div>

---

## 🧠 About the Project

Social media generates a massive amount of customer opinions, reactions, and feedback every day. Raw social media data can be difficult to interpret because sentiment, engagement, platforms, topics, and time-based patterns are spread across thousands of records.

This project transforms that raw information into an **interactive Business Intelligence solution using Microsoft Power BI**.

The dashboard helps stakeholders quickly answer:

> **What are people saying? Where are they saying it? How are they engaging? And how is sentiment changing over time?**

---

## 🎯 Problem Statement

Organizations need a reliable way to monitor public sentiment and social media engagement. Without a centralized analytical dashboard, it can be difficult to identify negative feedback, understand audience behavior, compare platforms, and detect changes in sentiment.

### The goal of this project is to:

- Analyze **Positive, Negative, and Neutral** sentiment.
- Track sentiment movement over time.
- Compare social media platforms.
- Measure audience engagement.
- Identify topics/categories generating negative feedback.
- Detect important changes and patterns.
- Convert social media data into actionable business insights.

---

## 💼 Business Questions

| # | Business Question |
|---|---|
| 01 | What is the overall sentiment of social media activity? |
| 02 | What percentage of posts are Positive, Negative, and Neutral? |
| 03 | How does sentiment change month by month? |
| 04 | Which platform generates the highest engagement? |
| 05 | Which platform has the most positive or negative sentiment? |
| 06 | Which topics/categories receive the most negative feedback? |
| 07 | How does engagement differ across sentiment categories? |
| 08 | Are there spikes or sudden changes in negative sentiment? |
| 09 | Which areas require attention from marketing or CX teams? |

---

## 📊 Dashboard Highlights

### 🔢 Executive KPIs

The dashboard provides an executive-level overview of social media performance, including:

- **Total Posts**
- **Total Engagement**
- **Positive Posts**
- **Negative Posts**
- **Neutral Posts**
- **Average Engagement**
- **Sentiment %**

### 😊 Sentiment Analysis

Understand the distribution of:

🟢 **Positive**  
🔴 **Negative**  
🟡 **Neutral**

### 📈 Sentiment Trend

A time-series view helps identify:

- Growth or decline in positive sentiment
- Increasing negative sentiment
- Monthly patterns
- Sudden sentiment changes
- Potential campaign/event impact

### 📱 Platform Performance

Compare available social media platforms based on:

- Post volume
- Engagement
- Sentiment
- Average engagement
- Sentiment percentage

### 🔍 Interactive Analysis

Use dashboard filters/slicers to explore the data dynamically by dimensions such as:

`Date` • `Platform` • `Sentiment` • `Topic/Category`

---

## 🖼️ Dashboard Preview

> 📌 **Add your actual Power BI dashboard screenshot here.**

```text
screenshots/
└── dashboard.png
```

Then display it in GitHub using:

```markdown
![Social Media Sentiment Dashboard](screenshots/dashboard.png)
```

### 💡 GitHub Portfolio Tip

For maximum recruiter impact, add **2–3 clean screenshots** showing:

1. Executive KPI overview
2. Sentiment trend & platform analysis
3. Detailed sentiment/category analysis

---

## 🔄 Data Analytics Workflow

```text
                ┌─────────────────────┐
                │   Raw Social Data   │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │  Data Cleaning      │
                │  & Transformation   │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │   Data Modeling     │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ DAX Measures & KPIs │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Power BI Dashboard  │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Business Insights   │
                └─────────────────────┘
```

---

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| 🟨 **Power BI** | Interactive dashboard & visualization |
| 🟦 **Power Query** | Data cleaning & transformation |
| 🟩 **DAX** | KPIs, calculations & analytical measures |
| 🗂️ **Data Modeling** | Relationships & analytical structure |
| 📄 **CSV / Excel** | Source data, where applicable |

---

## 🧹 Data Preparation

The project workflow includes common data preparation activities:

- Removing duplicate records
- Handling missing values
- Standardizing categorical values
- Correcting data types
- Creating date fields
- Preparing sentiment categories
- Creating analytical fields
- Establishing relationships
- Validating the final dataset

---

## 🧮 Example DAX Measures

```DAX
Total Posts =
COUNTROWS('Social Media')
```

```DAX
Total Engagement =
SUM('Social Media'[Likes])
+ SUM('Social Media'[Comments])
+ SUM('Social Media'[Shares])
```

```DAX
Positive Posts =
CALCULATE(
    [Total Posts],
    'Social Media'[Sentiment] = "Positive"
)
```

```DAX
Negative Posts =
CALCULATE(
    [Total Posts],
    'Social Media'[Sentiment] = "Negative"
)
```

```DAX
Positive Sentiment % =
DIVIDE(
    [Positive Posts],
    [Total Posts],
    0
)
```

> **Note:** Adjust table and column names to match the final Power BI model.

---

## 📌 Recommended Visuals

| Visual | Purpose |
|---|---|
| 🎯 KPI Cards | Executive summary |
| 🍩 Donut Chart | Sentiment distribution |
| 📈 Line Chart | Sentiment trend |
| 📊 Bar Chart | Platform comparison |
| 📊 Stacked Column | Sentiment by platform |
| 📊 Bar Chart | Sentiment by topic |
| 📋 Matrix | Detailed analysis |
| 🎛️ Slicers | Interactive filtering |

---

## 💡 Business Value

### 📣 Marketing Teams
- Measure audience reaction to campaigns.
- Identify positive and negative content.
- Improve content strategy.

### 🤝 Customer Experience Teams
- Detect recurring complaints.
- Identify customer pain points.
- Prioritize areas requiring attention.

### 👔 Management
- Monitor public perception.
- Track sentiment changes.
- Support data-driven decisions.

### 📊 Data Analysts
This project demonstrates practical experience with:

`Data Cleaning` → `Data Modeling` → `DAX` → `Visualization` → `Business Storytelling`

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/social-media-sentiment-analysis-powerbi.git
```

### 2️⃣ Open the Power BI file

Open:

```text
SOCIAL MEDIA SENTIMENT.pbix
```

using **Microsoft Power BI Desktop**.

### 3️⃣ Refresh the data

If the source data is included, refresh the dataset from:

**Home → Refresh**

### 4️⃣ Explore the dashboard

Use the available slicers and visuals to perform interactive analysis.

---

## 📂 Repository Structure

```text
social-media-sentiment-analysis-powerbi/
│
├── 📊 SOCIAL MEDIA SENTIMENT.pbix
├── 📖 README.md
├── 🚫 .gitignore
│
├── 📁 documentation/
│   └── problem_statement.md
│
├── 📁 screenshots/
│   ├── dashboard.png
│   ├── sentiment-trend.png
│   └── platform-analysis.png
│
└── 📁 data/
    └── social_media_sentiment.csv
```

> If the original dataset contains sensitive, licensed, or restricted information, do not upload it publicly. Instead, provide a data dictionary or sample dataset.

---

## 🏆 Skills Demonstrated

<p align="center">

`Power BI` • `DAX` • `Power Query` • `Data Cleaning` • `Data Modeling` • `Data Visualization` • `Sentiment Analysis` • `KPI Development` • `Time-Series Analysis` • `Business Intelligence` • `Data Storytelling`

</p>

---

## 📈 Project Outcome

The final solution provides a **single interactive analytical view of social media performance**, allowing users to move from high-level KPIs to detailed sentiment and engagement analysis.

### From:

❌ Raw social media records  
❌ Difficult-to-read data  
❌ Limited visibility into sentiment  
❌ Manual analysis  

### To:

✅ Interactive dashboard  
✅ Clear sentiment insights  
✅ Trend monitoring  
✅ Platform comparison  
✅ Actionable business intelligence  

---

## 👨‍💻 Author

<div align="center">

### **Santanu Pathak**

**Aspiring Data Analyst | Power BI | SQL | Python | Excel**

📍 Kolkata, West Bengal, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/santanu-pathak-3640672a5)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/s2097p-de)

</div>

---

## ⭐ Support

If you found this project helpful:

⭐ **Star the repository**  
🍴 **Fork the repository**  
💬 **Share your feedback**

---

<div align="center">

### 📊 Data → Insights → Decisions

**Built with Power BI | Designed for Business Intelligence**

</div>

