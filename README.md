# Movie Industry Correlation Analysis 🎬

This project utilizes Python and the Pandas library to investigate the factors that most strongly influence the gross revenue of movies.

## 📊 Overview
**Context:** Completed as part of the Stellenbosch University / HyperionDev Data Science Bootcamp.
**Goal:** To identify which variables (Budget, Votes, Genre, Score) have the highest correlation with a movie's Gross Earnings.

## 🛠️ Technologies Used
* **Jupyter Notebook**
* **Pandas:** Data manipulation and cleaning.
* **Seaborn & Matplotlib:** Visualization (Regression plots, Correlation Matrices).

## 🔎 Key Analysis Steps
1.  **Data Cleaning:** Handled missing data and fixed data types (converting float budgets to integers).
2.  **Correlation Matrix:** Used `df.corr()` to determine numerical relationships.
3.  **Visualization:** Created heatmaps and scatter plots to visualize the linear relationship between Budget and Gross Revenue.

## 📈 Findings
* **Budget vs. Gross:** There is a high positive correlation between budget and gross revenue, suggesting that higher investment generally yields higher returns.
* **Votes vs. Gross:** Audience engagement (votes) also showed a significant correlation with revenue.

## 🚀 How to Run
1. Ensure `movies.csv` is in the same directory as the notebook.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
