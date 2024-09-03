# 📊 Bank Marketing Campaign Analysis

<p align="center">
  <a href="#overview">
    <img src="https://img.shields.io/badge/-Overview-blue?style=for-the-badge" alt="Overview">
  </a>
  <a href="#-data-overview">
    <img src="https://img.shields.io/badge/-Data%20Overview-green?style=for-the-badge" alt="Data Overview">
  </a>
  <a href="#-tools-used">
    <img src="https://img.shields.io/badge/-Tools%20Used-orange?style=for-the-badge" alt="Tools Used">
  </a>
  <a href="#-insights--business-impact">
    <img src="https://img.shields.io/badge/-Insights%20%26%20Business%20Impact-red?style=for-the-badge" alt="Insights & Business Impact">
  </a>
  <a href="#design-principles-implemented">
    <img src="https://img.shields.io/badge/-Design%20Principles%20Implemented-purple?style=for-the-badge" alt="Design Principles Implemented">
  </a>
  <a href="#why-this-topic-matters-to-me">
    <img src="https://img.shields.io/badge/-Why%20This%20Topic%20Matters%20to%20Me-yellow?style=for-the-badge" alt="Why This Topic Matters to Me">
  </a>
  <a href="#key-takeaways">
    <img src="https://img.shields.io/badge/-Key%20Takeaways-pink?style=for-the-badge" alt="Key Takeaways">
  </a>
  <a href="#conclusion">
    <img src="https://img.shields.io/badge/-Conclusion-lightblue?style=for-the-badge" alt="Conclusion">
  </a>
</p>

<p align="center">
  <a href="https://github.com/devarchanadev/Tableau-Visualization-of-Bank-Marketing-Analysis">
    <img src="https://img.shields.io/badge/Visit-GitHub_Repo-181717?style=for-the-badge&logo=github" alt="GitHub Repo">
  </a>
  <a href="https://www.kaggle.com/datasets/muhammedsal98/bank-marketing">
    <img src="https://img.shields.io/badge/Download-Dataset_Source-20BEFF?style=for-the-badge&logo=kaggle" alt="Dataset Source">
  </a>
</p>

---

## Overview
In this project, I analyzed the effectiveness of bank marketing campaigns using a modified dataset from [Kaggle](https://www.kaggle.com/datasets/muhammedsal98/bank-marketing). The focus was on understanding how different customer demographics, occupations, and campaign outcomes influence the likelihood of a successful purchase. My goal was to provide actionable insights to the Board that would help them make informed decisions based on high-level metrics.

---

## 📁 Data Overview
- **Dataset Source**: [Kaggle Bank Marketing Dataset](https://www.kaggle.com/datasets/muhammedsal98/bank-marketing) (modified version)
- **Objective**: To predict whether a contacted client will purchase or accept joining the deposits, based on their profile and previous campaign results.
- **Data Cleaning**: I cleaned the dataset to remove inconsistencies and irrelevant fields. One key step was converting the "Purchase" field into a binary field (`CalcPurchase`) to simplify the analysis and make the results more actionable.

> 💡 **Tip**: Use `Python` or `Excel` for initial data cleaning and exploration.

---

## 🛠 Tools Used
| Tool      | Purpose                                                                 |
|-----------|-------------------------------------------------------------------------|
| **Tableau** | Creating interactive dashboards that are easy to navigate and understand |
| **Python**  | Initial data cleaning, processing, and preparation                      |
| **Excel**   | Basic data exploration and initial checks                               |

---

## 📈 Insights & Business Impact
1. **Campaign Effectiveness**: A higher number of campaigns doesn’t necessarily lead to more purchases. For instance, 2017 had the most campaigns, but purchases peaked in 2018. This indicates that **quality** over quantity is crucial.
  <img width="523" alt="Screenshot 2024-09-02 211028" src="https://github.com/user-attachments/assets/233b61d6-e453-4166-a533-fe052576f35a">

2. **Predictive Factors**: Job type, education level, and balance significantly predict the likelihood of a purchase. This insight can help tailor future campaigns to target high-potential demographics.
<img width="486" alt="Screenshot 2024-09-02 211059" src="https://github.com/user-attachments/assets/92730f1b-0843-402d-9ba5-209c19fe9a81">

3. **Outcome-Based Strategy**: Campaigns with a known successful outcome (POUTCOME) are more likely to lead to purchases, emphasizing the need for targeted follow-up campaigns.
<img width="479" alt="Screenshot 2024-09-02 211125" src="https://github.com/user-attachments/assets/4b001ba8-eae0-44f6-ae13-7a19bf481c99">

---

## 🎨 Design Principles Implemented

I focused on using **Gestalt principles** to create a clear, structured, and effective presentation:

1. **Similarity**: Consistent colors were used across visuals to group related information and reduce distractions.
2. **Proximity**: Equal spacing between bars and charts ensured no unintended relationships were implied between categories.
3. **Closure**: Added trend lines and reference lines guided the viewer's eye towards important trends and patterns.
4. **Connectivity**: Reference lines, like averages, grouped and contained related values for easier identification of key insights.
5. **Carpeted Area**: Different shades of similar colors were used to visually separate different sections of the dashboard while maintaining a cohesive look.
6. **Grid Layout**: The entire dashboard was designed using a grid layout with square grids that were evenly spaced, providing a disciplined and organized appearance.
<img width="477" alt="Screenshot 2024-09-02 211147" src="https://github.com/user-attachments/assets/b572d9b5-66df-4e38-a828-0adf420ff5b1">
<img width="470" alt="Screenshot 2024-09-02 211224" src="https://github.com/user-attachments/assets/b1ed48a9-b95e-4712-b403-4f67a2a3c682">

---

## ❤️ Why This Topic Matters to Me

I am particularly passionate about this topic because it sits at the intersection of data analysis and real-world business impact. Understanding customer behavior and optimizing marketing strategies are critical for businesses that want to grow and succeed. This project allowed me to transform raw data into actionable insights that can directly influence business decisions.

---

## 🎯 Key Takeaways

1. **More Campaigns ≠ More Success**: Focus on quality and targeting rather than just increasing the number of campaigns.
2. **Predictive Power of Demographics**: Use job type, education, and financial balance to segment and target customers effectively.
3. **Actionable Follow-ups**: Prioritize follow-ups where past outcomes were successful to increase the likelihood of conversions.
<img width="472" alt="Screenshot 2024-09-02 211308" src="https://github.com/user-attachments/assets/e4ca838c-e38a-40c5-9d6d-d63000a7be37">

---

## 🚀 Conclusion

This project highlighted the importance of focusing on quality over quantity in marketing campaigns. By understanding the key factors that drive customer purchases, businesses can optimize their strategies to increase conversion rates. The use of **Gestalt principles** and thoughtful design choices made the insights easy to digest for stakeholders, ensuring that the Board could make data-driven decisions with confidence.

<p align="center">
  <a href="https://github.com/devarchanadev/Tableau-Visualization-of-Bank-Marketing-Analysis">
    <img src="https://img.shields.io/badge/Visit-GitHub_Repo-181717?style=for-the-badge&logo=github" alt="GitHub Repo">
  </a>
  <a href="https://www.kaggle.com/datasets/muhammedsal98/bank-marketing">
    <img src="https://img.shields.io/badge/Download-Dataset_Source-20BEFF?style=for-the-badge&logo=kaggle" alt="Dataset Source">
  </a>
</p>
