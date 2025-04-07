# LaLiga Data Analysis and Prediction 📊⚽

This project focuses on **analyzing** and **predicting** outcomes for LaLiga teams based on data from the past **11 seasons** (2014–2025).  
It combines **exploratory data analysis (EDA)** with a **Random Forest Classifier** to estimate the probability of different outcomes for the current season.

---

## 📂 Dataset
- Historical LaLiga standings and team statistics from **2014 to 2025**.
- Each row represents a team's performance in a specific season.
- Features include: points, wins, draws, losses, goals scored, goals conceded, possession percentage, and more.

---

## 🛠️ Project Structure
### 1. Hypothesis Setting
- **Main Questions:**
  - Who is most likely to win LaLiga this year?
  - Which two teams are most likely to be relegated?
  - Which team is most likely to qualify for the Conference League (7th place)?

---

### 2. Data Exploration 📈
- Analyze **number of appearances** of teams over the seasons.
- Identify **top 3 finishes** by teams.
- Plot **visualizations** using Plotly:
  - Bar charts showing top teams based on their rankings.
- Summary statistics and data overview.

---

### 3. Machine Learning Model 
- **Model Used:** Random Forest Classifier (from `sklearn.ensemble`)
- **Goal:** Predict probabilities for different outcomes (win, relegation, 7th place) based on team statistics.
- **Features Used for Prediction:**
  - Points
  - Goal Difference
  - Goals Scored
  - Goals Conceded
  - Wins, Draws, Losses
  - Possession %
  - and other performance metrics.

- **Steps:**
  - Prepare training and testing datasets.
  - Train the Random Forest model on historical data.
  - Predict probabilities for the current season's teams.
  - Display top teams based on predicted outcomes.

---

##  Key Results
- Predicted the **most probable LaLiga champion** based on current and past performance.
- Identified the **teams most at risk of relegation**.
- Predicted the **team most likely to finish 7th** (Conference League spot).

---

## 📦 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `plotly`
- `sklearn`
