# 💘 Speed Dating Data Analysis

This project explores behavioral and psychological patterns behind dating decisions, using real-world speed dating data collected from events at Columbia University. The analysis aims to understand what drives interest, mutual matches, and follow-up actions.

---

## 📊 Project Objectives

- Understand the characteristics most predictive of:
  - Saying "yes" to a date
  - Getting a "yes" from others
  - Achieving a mutual match
  - Going on a second date

- Explore how preferences differ by gender and perception

- Investigate the impact of interaction timing on match success

---

## 🔍 Key Analyses Conducted

### 1. **Factors Predicting a Match**
- Compared mutual decisions with participant/partner attribute ratings (`attr`, `fun`, `intel`, etc.)
- Identified top predictors: perceived attractiveness, fun, shared interests, and expected partner interest

### 2. **Impact of Race and Interest Similarity**
- Explored how `samerace` and `int_corr` relate to match probability
- Found shared interests more predictive than shared race

### 3. **Self-Perceived Attractiveness and Callback Likelihood**
- Analyzed whether self-ratings influence whether participants get contacted post-event (`them_cal`)
- Found that higher self-rated attractiveness increased callback probability

### 4. **Timing and Decision Fatigue**
- Investigated if early vs. late dates influence decision outcomes (`order`)
- Found higher "yes" and match rates in early and final interactions

### 5. **Gendered Perception vs. Reality**
- Used radar charts to compare:
  - What each gender values
  - What they believe the opposite gender values
- Revealed mismatches between perception and actual preferences

### 6. **Second Date Predictors (Post-Match)**
- Built a decision tree on `date_2` using only matched users
- Found that being contacted, shared interests, ambition, fun, and lifestyle indicators (e.g. yoga, hiking) were predictive

---

## 📁 Project Structure

- `Speed_dating_analysis.ipynb`: Full notebook with code, visualizations, and interpretations
- Visualizations: Pie charts, bar plots, radar charts, decision trees, and interaction order line plots using Plotly
- Tools used: 
  - **Pandas**, **NumPy** for data manipulation  
  - **Seaborn**, **Plotly**, **Matplotlib** for visualizations  
  - **Scikit-learn** for the decision tree model

---

## 📌 Dataset

- Sourced from Columbia University’s speed dating experiments (2002–2004)
- Contains over 8,000 interactions with detailed pre/post surveys
- Each interaction includes:
  - Self-ratings and ratings of others
  - Decisions made (yes/no)
  - Preferences, perceptions, and demographic info

---

## 🧠 Insights

You can find structured insights in **Step 4: Interpretation & Insights** of the notebook, including markdown summaries and visual support.

---

## 🗂️ Repository Navigation

| Folder/File                    | Description                                      |
|-------------------------------|--------------------------------------------------|
| `Speed_dating_analysis.ipynb` | Main notebook for analysis & insights            |
| `/images`                     | Visualizations (radar charts, plots)             |
| `README.md`                   | Project overview and documentation               |

---

## 🚀 Future Ideas

- Build a predictive model for match likelihood
- Cluster participants by decision patterns

