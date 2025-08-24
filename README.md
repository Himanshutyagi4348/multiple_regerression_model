# Index Price Prediction using Multiple Linear Regression

**Predict economic index price based on interest rate & unemployment rate**

---

##  Overview
This project explores how macroeconomic variables—**interest rate** and **unemployment rate**—influence an economic **Index Price**. A multiple linear regression model is developed and visualized to provide transparency and baseline insights.

---

##  Features
- **Data Handling**: Load & clean monthly time-series data  
- **Exploratory Analysis & Visualization**: Scatter plots, regression trends with `Seaborn` & `Matplotlib`  
- **Modeling Workflow**: Train/test split, model training, evaluation using `scikit-learn`, insights from regression coefficients  
- **Baseline Interpretability**: Easily understandable model for quick insights and future feature expansion

---

##  Tech Stack
| Package       | Purpose                                |
|---------------|----------------------------------------|
| `NumPy`       | Numerical operations                   |
| `Pandas`      | Data manipulation & preprocessing      |
| `scikit-learn`| Building & evaluating regression model |
| `Matplotlib`  | Plotting & visualization               |
| `Seaborn`     | Enhanced statistical visualization     |

---

##  Installation & Usage

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook index_price_prediction.ipynb

The notebook walks through dataset loading, exploratory visualizations, model training, evaluation, and interpretation.
What You’ll Learn

Clear approach to baseline modeling with regression

Practical use of scikit-learn, Pandas, and visualization tools

How simple models offer actionable insights—especially when explainability matters

Repository Structure
├── data/
│   └── economic_index.csv        # Monthly data with interest_rate, unemployment_rate, index_price
├── notebooks/
│   └── mlr_economic_dataset.ipynb  # EDA, modeling & visual outputs
├── requirements.txt
└── README.md

Future Directions

Add feature engineering (e.g., lag variables, seasonality components)

Evaluate more complex models—like Ridge, Lasso, or tree-based regression

Deploy as a simple web app or API for real-time forecasting
tHub Repository

Access the full code, visuals, and commentary here:
→ https://github.com/Himanshutyagi4348/multiple_regerression_model/new/main?filename=README.md
License

This project is licensed under the MIT License—feel free to explore, modify, or reuse.
