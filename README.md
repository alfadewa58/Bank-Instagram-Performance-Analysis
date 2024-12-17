
# Project: Danamon IG Q4 Performance Analysis

This project analyzes the performance data for Danamon IG Q4 using a Jupyter Notebook. The analysis includes data cleaning, visualizations, and engagement insights to provide actionable recommendations for improving Instagram strategies.

---

## Table of Contents

1. [Business Understanding](#business-understanding)
2. [Data Understanding](#data-understanding)
3. [Data Cleaning](#data-cleaning)
4. [Data Analysis And Visualization](#data-analysis-and-visualization)
5. [Conclusions](#conclusions)
6. [Recommendations](#recommendations)
7. [Dependencies](#dependencies)
8. [Usage](#usage)
9. [Output](#output)
10. [Author](#author)

---

## 1. Business Understanding

### **Context**

Bank Danamon is one of Indonesia's leading banks, actively using social media—particularly Instagram—to:

- Build **brand awareness**
- Promote **products and services**
- Enhance **customer engagement**

With over **130,000 followers in 2024**, the bank aims to optimize its digital strategy for better performance.

### **Stakeholders**

- **Digital Marketing Team**: Focuses on social media content and KPIs.
- **Senior Management**: Evaluates ROI and overall digital marketing effectiveness.

### **Problem Statements**

1. How is Bank Danamon's Instagram performance during Q4 2024?
2. What type of content generated the highest engagement?

### **Goals**

- Evaluate overall Instagram performance during Q4 2024.
- Identify trends in **likes**, **comments**, and **content types**.
- Provide **data-driven recommendations** for the next quarter.

---

## 2. Data Understanding

The data consists of:

- **Number of Posts**: 102
- **Post Types**:
   - Images: 82
   - Videos: 20
- **Metrics**: Likes, Comments, Posting Hours, Hashtags, and Captions.

---

## 3. Data Cleaning

The following steps were applied to clean and prepare the data:

- Removed duplicate entries.
- Checked and handled missing values in key fields (likes, comments).
- Ensured data consistency for post types, timestamps, and engagement metrics.
- Derived new features such as **median metrics** and **post categories**.

---

## 4. Data Analysis And Visualization

### **Engagement Metrics (Q4 2024)**

- **Overall Engagement**: Q4 contributed **8%** of total annual engagement, the lowest among quarters.
- **Likes Median**: 48.5
- **Comments Median**: 2.5

#### **Media Type Comparison**:
- **Images**:
   - Likes Median: **44**
   - Comments Median: **2**
- **Videos**:
   - Likes Median: **82.5**
   - Comments Median: **3**

### **High Engagement Posts**:
- **Criteria**: Posts with **400+ likes**.
- **Best-performing post**: **Seminar Post** on **2024-11-15** with **946 likes**.
- **Common Posting Hours**: **05:00 and 12:00**.
- **Caption Length**: **461 characters** (average).

### **Moderate Engagement Posts**:
- **Criteria**: Likes between **150-400**.
- **Key insights**:
   - Captions include awards to boost credibility.
   - Posting Hours: Inconsistent but peaks around **05:00, 11:00, and 12:00**.
- **Caption Length**: **563.56 characters**.

### **Low Engagement Posts**:
- **Criteria**: Likes below **150**.
- **Issues**: Overly promotional content, lack of storytelling, and poor hashtag usage.
- **Common Posting Hours**: Dominated by **05:00**.
- **Hashtags**: Generic, average usage **3.6 per post**.

---

## 5. Conclusions

### **Engagement & Metrics on Q4**

- Videos consistently outperform images in likes and comments.
- High engagement posts are concise, event-driven, and have clear CTAs.
- Posting Hours: **05:00 and 12:00** are most effective.

### **Correlation**
- **Weak correlation** between likes and comments: **0.147**.

### **Content Trends**
- Seminar, SME funding, and mortgage assistance topics perform the best.

---

## 6. Recommendations

### **Increase Video Content**:
- Aim for a **1:2 ratio** of videos to images.

### **Promote High-Value Content**:
- Topics: Seminars, SME funding, and mortgage assistance (KPR).
- Highlight competitive financing solutions for vehicles and homes.

### **Optimize Hashtag Strategy**:
- Use **2-3 focused hashtags**:  
   - **#kpr** (1.6M reach)
   - **#dukungumkm** (115K reach)
   - **#pinjamanmudah** (108K reach)

### **Consistent Posting Schedule**:
- Focus on **05:00 and 12:00** as proven peak hours.

### **Enhance Captions**:
- Keep captions **400-500 characters**.
- Include storytelling, trending topics, and strong CTAs.

### **Collaborate with Influencers**:
- Partner with financial influencers to expand reach:
   - **Felicia Putri Tjiasaka**
   - **Prita Hapsari Ghozie**
   - **Raymond Surya Chin**

---

## 7. Dependencies

Install required packages:

```bash
pip install pandas matplotlib seaborn numpy
```

---

## 8. Usage

1. Open `DanamonIGQ4Performance.ipynb` in Jupyter Notebook.
2. Run the cells sequentially.
3. Review visualizations, metrics, and recommendations.

---

## 9. Output

The outputs include:

- Cleaned data tables
- Engagement metrics visualizations
- Insights and recommendations for Q4 2024

---

## 10. Author

Developed to evaluate and enhance Bank Danamon's Instagram Q4 performance.

---

## License

This project is for educational and analytical purposes only.

