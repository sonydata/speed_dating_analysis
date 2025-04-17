# Behavioral Analysis of Speed Dating Decisions 💘

This project investigates behavioral and psychological patterns underlying attraction and dating decisions, using real-world speed dating data from events hosted at Columbia University. The analysis aims to understand what makes people interested in each other — across decisions to date, mutual matches, and second dates.

---

## 📂 Repository Structure

| File / Folder                   | Description                                               |
|--------------------------------|-----------------------------------------------------------|
| `Speed_dating_analysis.ipynb`  | Main Jupyter Notebook with full analysis and insights     |
| `Speed+Dating+Data.csv`        | Cleaned dataset with participant and interaction data     |
| `Speed+Dating+Data+Key.doc`    | Official variable dictionary / metadata                   |
| `images/`                      | Folder containing visualizations used in the notebook     |
| `README.md`                    | Project overview (this file)                              |

---

## Project Goal

**Main question:** _What makes people interested in each other during speed dating?_

Using behavioral data, psychological self-ratings, and partner evaluations, we explore how decisions unfold across different interaction stages and social dynamics.

---

## 🔍 Notebook Structure & Analysis Flow

### ✅ Step 1: Exploring and Cleaning the Dataset
- Raw dataset inspection and summary statistics
- Missing values and inconsistencies handling
- Data standardization using mapping

### 👥 Step 2: Getting to Know the Participants
- Described the sample by gender, age, race, dating habits and goals

### 📊 Step 3: Exploratory Data Analysis
We investigated key behavioral questions using descriptive statistics, correlation plots, decision trees, and radar charts.

#### 1. What Predicts a Match?
- Most predictive: being rated as fun, attractive, or having shared interests
- Participant's own ratings and perceived partner interest also mattered

#### 2. Do Similar Backgrounds Help?
- Shared race had no significant impact on match probability
- Shared interests showed a positive effect

#### 3. Does Self-Perceived Attractiveness Matter?
- Strong association between self-rated attractiveness and being contacted after the event
- Callback rates rose steadily with higher self-ratings

#### 4. Does Timing Influence Interest?
- Early interactions had the highest "yes" and match rates
- Decision fatigue likely set in mid-event, with a rebound toward the final rounds

#### 5. How Accurate Are Gendered Perceptions?
- Radar charts show gaps between what men/women believe the opposite sex values vs. actual preferences
- Men overestimate how much women value attractiveness
- Women underestimate how much men value traits like sincerity and intelligence

#### 6. What Predicts Going on a Second Date?
- **Top predictor**: being contacted afterward
- Other contributors: ambition, shared interests, being fun, lifestyle indicators (e.g. yoga/hiking)

---

## 📁 Visualizations

All plots and figures used in the notebook are saved in the [`images/`](images/) folder. These include:

- Correlation bar charts
- Match rate plots
- Radar charts by gender and perception
- Line plots for decision order effects
- Decision tree for second date prediction

---

## 🛠️ Tools & Libraries

- `pandas`, `numpy`: data handling
- `plotly`, `matplotlib`: data visualization
- `scikit-learn`: decision tree modeling

---

## 📈 Dataset Source

- Data from speed dating events held at Columbia University (2002–2004)
- Each row = one interaction between male and female participants
- Includes:
  - Ratings of self and others
  - Preferences and beliefs
  - Final decisions (match, yes/no)
  - Demographic and lifestyle info

---

## 💡 Insights

Summarized interpretations and final conclusions can be found in the notebook under:

**Step 4: Interpretation & Insights**


