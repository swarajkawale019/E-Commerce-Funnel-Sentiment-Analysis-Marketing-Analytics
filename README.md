# E-Commerce-Funnel-Sentiment-Analysis-Marketing-Analytics
 
**Goal :** Diagnose declining engagement & conversion rates for ShopEasy (an online retailer) and deliver actionable insights to boost performance.  

---

## 📌 Executive Summary  
This project analyzed customer behavior across the full journey—from initial engagement to final purchase and feedback. Using SQL, Python (NLP), and Power BI, the study revealed that a small set of products and seasonal peaks drive most conversions. Engagement was declining across channels, and customer sentiment highlighted service gaps. Based on these insights, targeted marketing, improved content strategy, and customer feedback loops were recommended to enhance ROI and loyalty.  

---

## 🏦 Business Problem
ShopEasy, an online retail business, has recently launched several online marketing campaigns. However, the company is experiencing reduced customer engagement and conversion rates. The purpose of this analysis is to help ShopEasy conduct a detailed investigation and identify areas for improvement in their marketing strategies.

**Reduced Customer Engagement :** The number of customer interactions and engagement with the site and marketing content has decreased.

**Decreased Conversion Rates :** Fewer site visitors are converting into paying customers.

**High Marketing Expenses :** Significant resources are spent on marketing campaigns with limited returns.

**Need for Customer Feedback Analysis :** Understanding customer opinions about products and services is crucial for improving engagement and conversions.
  

---

  ## 🔬 Methodology
**Data Extraction and Cleaning :** I began by writing SQL queries to extract and clean raw transactional and engagement data from the company's database.

**Sentiment Analysis :** I developed a Python script to perform Natural Language Processing (NLP) on over 500 customer reviews, programmatically assigning sentiment scores and categories (Positive, Negative, Neutral) to quantify customer feedback.

**Data Modeling and Visualization :** I designed and implemented a relational star-schema data model in Power BI to connect disparate datasets. Using this model, I developed a dynamic, interactive dashboard to track KPIs and present findings to stakeholders in an intuitive format.

---

## 🛠️ Tools & Skills  
- **SQL:** Data extraction, cleaning.  
- **Python (Pandas, NLP):** Sentiment analysis on reviews.  
- **Power BI:** Star schema modeling, DAX measures, KPI dashboards.    

---

## 📊 Results & Recommendations 

**Key Findings**

1. **Conversion Rates Are Highly Seasonal and Product-Dependent :** The overall conversion rate stands at 8.5%, but it fluctuates significantly throughout the year, peaking at 18.5% in January and hitting a low of 4.3% in May. A few key products, such as the Kayak (21.4% conversion) and Ski Boots (20.0% conversion), are major drivers of successful sales.

2. **Social Media Engagement Is Declining :** While blog content generates the most views, overall social media views saw a steady decline in the second half of the year. Furthermore, interaction rates (clicks and likes) are low compared to view counts, indicating that the content is not effectively compelling users to act.

3. **Customer Satisfaction Has Room for Improvement :** The average customer rating is 3.7 out of 5, which is below the company's target of 4.0. While the majority of reviews (275) are positive, a significant number of negative reviews (82) are impacting the overall score and highlight specific areas of customer dissatisfaction.

**Actionable Recommendations**

1. **Optimize Marketing Spend with a Targeted Strategy :** Instead of broad campaigns, focus marketing efforts on top-performing products like Kayaks and Ski Boots. Launch seasonal promotions to align with peak conversion months like January and September to maximize return on investment.

2. **Revitalize the Content Strategy to Boost Engagement :** Combat declining views by introducing more engaging content formats, such as interactive videos and user-generated content campaigns, especially in the low-performing second half of the year. Optimize the placement of calls-to-action in high-traffic blog posts to convert passive viewers into active leads.

3. **Implement a Proactive Customer Feedback Loop :** Systematically analyze mixed and negative reviews to identify common product or service issues. By addressing these specific pain points and following up with dissatisfied customers, ShopEasy can improve its average rating, enhance customer loyalty, and foster a more positive brand image.

---

## 🔮 Next Steps  
- Granular **funnel drop-off** analysis.  
- **RFM segmentation** for personalized marketing.  
- Implement **A/B testing** framework for campaigns.  
