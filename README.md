<h1>Formula 1 Race Strategy & Driver Performance Intelligence Platform</h1>

An end-to-end Data Science, Analytics, and Strategy Optimization system built on 70+ years of Formula 1 race data to predict race outcomes, optimize pit strategies, and simulate race scenarios using Machine Learning and Monte Carlo methods.

**🚀 Project Overview**

This project replicates how real F1 race strategy teams use data to make decisions.

The platform:
  1. Predicts Podium, Top-5, and DNF probabilities using ML
  2. Quantifies driver skill vs car performance
  3. Optimizes pit stop windows using tire degradation modeling
  4. Models Safety Car risk using logistic regression
  5. Runs 10,000+ Monte Carlo simulations to estimate race outcomes
  6. Visualizes insights via Power BI dashboards
  7. Deploys a live Streamlit race strategy web app



**🧠 Business Problems Solved**

| Question                                | Solution Built                           |
| --------------------------------------- | ---------------------------------------- |
| Who will finish on the podium?          | XGBoost prediction model (ROC-AUC: 0.87) |
| When should a driver pit?               | Pit-loss crossover optimization engine   |
| Who outperforms their car?              | Driver Efficiency Index (DEI)            |
| Which team dominates seasons?           | Constructor Dominance Index (CDI)        |
| Does weather change outcomes?           | Wet vs Dry performance delta             |
| What is the risk of chaos (Safety Car)? | Logistic risk model                      |
| What strategy maximizes success?        | Monte Carlo race simulator               |




**🗂️ Data Sources**

1. Ergast F1 API (official historical data)
2. Kaggle F1 World Championship dataset
3. Historical race weather data
   
Tables engineered: drivers, constructors, races, lap_times, pit_stops, results, qualifying, standings, race_weather.




🛠️ Tech Stack

Python: Pandas, NumPy, Scikit-learn, XGBoost, SHAP
SQL: PostgreSQL (CTEs, Window Functions, Materialized Views)
Visualization: Power BI
Deployment: Streamlit
Statistics: Hypothesis Testing, ANOVA, Variance Modeling
Simulation: Monte Carlo methods



🧩 Key Modeling Components

1. Driver & Constructor Performance Modeling
Driver Efficiency Index (DEI)
Constructor Dominance Index (CDI)
Track Dominance Score (TDS)
Overtake Aggression Score (OAS)
Consistency Index (CI)


2. Machine Learning Models
   
| Model               | ROC-AUC  |
| ------------------- | -------- |
| Logistic Regression | 0.71     |
| Random Forest       | 0.82     |
| XGBoost             | 0.87     |

Targets:
  Podium Finish
  Top-5 Finish
  DNF Risk
Explainability using SHAP feature importance.


3. Strategy Optimization Engine
   
    A. Tire degradation regression
    B. Pit window optimization
    C. Undercut vs Overcut simulation
    D. Safety Car probability model
    E. 10,000+ race Monte Carlo simulations

**📊 Power BI Dashboards**
Driver Performance Intelligence
Constructor Strategy War Room
ML Race Outcome Predictor
Pit Strategy & Monte Carlo Simulator


**🌐 Streamlit Web Application**

_Interactive app where user selects:_
Driver
Track
Weather
Pit strategy

_And receives:_
Podium probability
Optimal pit lap
Expected finish position
Strategy recommendation
