# Kentucky I-65 Traffic Volume Prediction with XGBoost

This project predicts hourly traffic volume on Interstate I-65, Jefferson County, Louisville, Kentucky using Machine Learning.

**Live Link:** You are here!

### 📊 Data Source
- Kentucky Transportation Cabinet (KYTC) - TRAK Continuous Count Station Program
- Location: I-65 Station, Jefferson County
- Period: Jan-Mar 2023, 500 hourly records

### ⚙️ Features Used
- **Hour** (0-23), **DayOfWeek**, **IsWeekend**
- **Weather** (Clear, Rain, Snow - one-hot encoded)
- **Target:** TrafficVolume (cars/hour)

### 🧠 Workflow
1. Data cleaning and exploration with Pandas
2. One-hot encoding for categorical features
3. Train/Test Split: 80% / 20%
4. Model: **XGBoost Regressor** (n_estimators=100)
5. Evaluation: **RMSE = 142 cars/hour**, **Accuracy = 89.5%**
6. Visualization: Actual vs Predicted plot

### 📈 Key Result
- Average hourly traffic: **1355 cars/hour**
- Model error: only **142 cars** (10.5% error)
- Model captures peak hour patterns effectively

### 🛠️ Tools
Google Colab, Pandas, Scikit-learn, XGBoost, Matplotlib

### ▶️ How to Run
Open `Kentucky_I65_XGBoost.ipynb` in Google Colab and Run All.

### 👤 Author
Elvis Kwabena Wilson - Civil Engineering background, focusing on Transportation & ML
