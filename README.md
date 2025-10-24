
# 🧾 Calories Burnt Prediction – Machine learning

_Predict Calories Burnt using XGBOOST._

---

## 📌 Key feautres
- <a href="#Data Preprocessing">Merges and cleans two related datasets</a>
- <a href="Exploratory Data Analysis (EDA)">Uses Seaborn and Matplotlib for visualization</a>
- <a href="#Feature Engineering">Feature Engineering</a>
- <a href="Model Training"> Implements the `XGBoost Regressor` for accurate calorie prediction</a>
- <a href="Model Evaluation"> Assesses performance using Mean Absolute Error (MAE)</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project predicts the **number of calories burnt** during physical exercise using **machine learning**.  
It combines user demographic data and physical attributes with exercise-related information to train a predictive model.

The goal is to build a regression model that accurately estimates calorie expenditure useful for **fitness apps, wearables, and health analytics platforms**.

---
<h2><a class="anchor" id="problem-statement"></a>problem-statement</h2>

With increasing awareness around fitness tracking, accurate estimation of calories burnt has become an essential feature for health applications.
However, calorie burn depends on multiple factors like body composition, workout intensity, and duration making it non-linear and difficult to estimate manually.
This project addresses the problem by:
- Analyzing user and exercise data to find hidden patterns.
- Using an XGBoost Regression Model to predict calories burnt with high accuracy.
- Evaluating performance with metrics such as Mean Absolute Error (MAE) to ensure reliability.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple CSV files located in `/data/` folder (Calories,exercise)
- Download Datasets
[Kaggle - Calories Burnt Prediction Dataset](https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos)

---



---
<h2><a class="anchor" id="datasets description"></a>Datasets Description"</h2>

```
| Feature      | Description                              |
| ------------ | ---------------------------------------- |
| `User_ID`    | Unique identifier for each user          |
| `Gender`     | Male/Female                              |
| `Age`        | Age of the user                          |
| `Height`     | Height (in cm)                           |
| `Weight`     | Weight (in kg)                           |
| `Duration`   | Exercise duration (in minutes)           |
| `Heart_Rate` | Average heart rate during activity       |
| `Body_Temp`  | Average body temperature during activity |
| `Calories`   | Target variable (calories burnt)         |

```
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Programming Language 
- Python  
- Data Handling 
- Pandas, NumPy 
- Visualization  Matplotlib, Seaborn 
- Machine Learning  XGBoost, Scikit-learn 
- Metrics  MAE (Mean Absolute Error) 


---
<h2><a class="anchor" id="model performance"></a>Model Performance</h2>

- Model Used: XGBoost Regressor
- Evaluation Metric: Mean Absolute Error (MAE)
---
<h2><a class="anchor" id="expected output"></a>Expected output (EDA)</h2>

**Mean Absolute error:**
- 1.47


<h2><a class="anchor" id="Visualisations"></a>Visualizations</h2>

- Visualizations:
  - Gender distribution
  - Age, Height, and Weight distributions
  - Correlation heatmap between variables
  



---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https://abhi209iv/calories-burnt-prediction.git
```
2. Load the CSVs and ingest into database:
```bash
python calories_burnt_prediction.py

```

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Add more models (Random Forest, Linear Regression) for comparison
- Hyperparameter tuning using GridSearchCV
- Add more models (Random Forest, Linear Regression) for comparison
- Integrate with smartwatch/wearable device data

---
