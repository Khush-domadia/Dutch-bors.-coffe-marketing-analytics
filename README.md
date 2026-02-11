# Dutch Bros Coffee – Marketing Segmentation & Analytics

## 📌 Project Overview

This project applies marketing analytics techniques to identify and profile distinct customer segments for **Dutch Bros Coffee**, one of the fastest-growing drive-thru coffee chains in the United States.

Using survey data and statistical modeling in **Enginius**, we conducted:

- Hierarchical Cluster Analysis
- Discriminant Analysis
- Segment Profiling
- Classification Modeling
- Marketing Strategy Development

The goal was to move beyond broad demographic targeting and develop **data-driven segmentation strategies** to improve customer retention, brand positioning, and marketing effectiveness.

---

## 🎯 Business Problem

As competition intensifies in the specialty coffee industry (Starbucks, Dunkin’, local cafes), Dutch Bros must better understand:

- Who their customers are  
- What motivates them  
- How attitudes influence loyalty  
- Which segments are most valuable  

Without clear segmentation, marketing efforts risk being too generalized and inefficient.

---

## 📊 Data & Methodology

### Sample
- 17 valid survey responses (cleaned dataset used in segmentation)
- Convenience sampling via campus and social networks
- Current or recent Dutch Bros customers

### Segmentation Variables (Attitudinal Bases)

Six Likert-scale variables (Q9_1 – Q9_6) were used as clustering bases:

- Coffee as daily routine  
- Preference for fun & energetic brand culture  
- Community orientation  
- Willingness to pay for unique flavors  
- Social media engagement  
- Preference for personalized service  

These were clustered using **Hierarchical Clustering (Ward’s Method)** in Enginius.

---

## 🔎 Segmentation Results

### Initial Model (Exploratory)
- 5-cluster solution
- Statistically valid but too fragmented (small cluster sizes)
- Limited managerial usability

### Final Model (Validated)
- 2-cluster solution retained
- Combined with discriminant analysis
- 100% classification accuracy (in-sample)

### Final Segment Sizes:
- **Segment 1: 18%**
- **Segment 2: 82%** :contentReference

---

## 👥 Segment Profiles

### 🟠 Segment 1 – Low-Engagement Traditionalists (18%)

**Characteristics:**
- View coffee as functional
- Lower emotional connection to brand
- Lower social engagement
- Occasional visits
- More price-sensitive

**Marketing Opportunity:**
- Increase frequency
- Emphasize speed & convenience
- Offer value promotions

---

### 🔵 Segment 2 – Brand-Engaged Loyalists (82%)

**Characteristics:**
- Coffee is part of daily routine
- Strong alignment with fun & energetic culture
- Value personalization & friendly service
- Higher visit frequency
- Higher spending per visit
- Active on social media

**Marketing Strategy:**
- Loyalty programs
- App-based rewards
- Exclusive drops / limited-time drinks
- Community engagement events

---

## 🧠 Discriminant & Classification Analysis

A multinomial logit classification model was used to test whether observable descriptors (age, gender, purchase type, visit frequency, etc.) could predict segment membership.

### Confusion Matrix Results:
- 100% correct classification (17/17 observations)
- High predictive power using behavioral and demographic variables

This confirms that the segments are:
- Statistically distinct  
- Managerially actionable  
- Predictable using observable traits  

---

## 📈 Key Marketing Insights

1. Dutch Bros’ core revenue driver is the **Brand-Engaged Loyalist segment (82%)**
2. Emotional alignment with brand personality drives frequency and spending
3. Community + personalization significantly impact loyalty intentions
4. Functional coffee drinkers represent a growth opportunity
5. Segmentation improves targeting efficiency and strategic clarity

---

## 🏗️ Theoretical Framework

This study integrates:

- **STP Framework (Segmentation–Targeting–Positioning)**
- **Consumer Behavior Theory**
- **Brand Personality & Relationship Theory**

Conceptual relationship:

Demographics + Psychographics  
→ Behavioral Patterns  
→ Segment Membership  
→ Brand Satisfaction  
→ Loyalty & Advocacy  

---

## 🛠 Tools Used

- Enginius (Cluster & Discriminant Analysis)
- Excel (Data Cleaning)
- Survey Instrument Design
- Hierarchical Clustering (Ward's Method)
- Multinomial Logit Classification Model

---

## 📂 Repository Structure

- `/Data` – Cleaned dataset (CSV & Excel)
- `/Segmentation Reports` – Enginius output reports
- `/Final Report` – Full academic report (PDF/DOCX)
- `/Presentation` – Final presentation deck
- `/Questionnaire` – Survey instrument

---

## 🚀 Strategic Recommendations

### Primary Target: Brand-Engaged Loyalists
- Expand loyalty ecosystem
- Increase emotional engagement
- Strengthen app personalization

### Secondary Target: Traditionalists
- Convenience messaging
- Promotional bundles
- Drive-thru value incentives

---

## ⚠ Limitations

- Small sample size (n=17 used for final segmentation)
- Convenience sampling
- In-sample classification accuracy may overestimate real-world predictive power

Future research should:
- Increase sample size
- Use probability sampling
- Validate model out-of-sample

---

## 📌 Conclusion

This project demonstrates how marketing analytics can transform raw survey data into actionable strategic insights.

By identifying high-value customer segments and validating them statistically, Dutch Bros can:

- Improve targeting precision
- Increase loyalty
- Strengthen brand positioning
- Optimize marketing ROI
