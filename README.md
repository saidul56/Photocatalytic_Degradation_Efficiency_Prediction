 # Title: Predicting Nanomaterial Assisted Photocatalytic Degradation Efficiency Using Machine Learning: A Comparative Study of Regression Models
Machine learning–based prediction of nanomaterial-assisted photocatalytic degradation efficiency using comparative regression models, with XGBoost as the selected predictor

## 👤 Author
Saidul Islam
MS Research Fellow
Machine Learning & Chemometrics Enthusiast
M.Sc. in Inorganic Chemistry
Hajee Mohammad Danesh Science and Technology University, Dinajpur-5200

## 📌 Project Overview
Photocatalytic degradation is a critical process for environmental remediation, particularly in wastewater treatment using nanomaterial-based photocatalysts. However, experimental evaluation of degradation efficiency is time-consuming and resource-intensive.
This project applies **machine learning regression models** to **predict photocatalytic degradation efficiency** based on nanomaterial properties and experimental conditions. Multiple regression models were evaluated, and **XGBoost** was identified as the best-performing model.

## 🎯 Objectives
* Predict photocatalytic degradation efficiency using ML
* Compare multiple regression models(RF,SVR,XGBoost,NB)
* Identify the most robust and accurate predictive model
* Reduce experimental trial-and-error in photocatalyst desig

## 📊 Dataset Description
The dataset consists of experimentally derived or literature-compiled parameters related to photocatalytic degradation.

### 🔹 Input Features (Examples)
* Nanomaterial type / composition
* Band gap energy
* Surface area
* Catalyst dosage
* Initial pollutant concentration
* pH
* Light source / irradiation time

### 🔹 Target Variable (Calculated)
* **Photocatalytic degradation efficiency (%)**

## 🧪 Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Feature scaling
   * Train–test split

2. **Regression Models Evaluated**
   
   * Support Vector Regression (SVR)
   * Random Forest Regressor
   * Neive Bias
   * **XGBoost Regressor (Selected Model)**

4. **Model Evaluation Metrics**
   * R² score
   * Mean Absolute Error (MAE)
   * Root Mean Squared Error (RMSE)

## 🏆 Model Selection
Among all tested models, **XGBoost** demonstrated:

* Highest predictive accuracy
* Strong generalization capability
* Lower prediction error compared to other regressors
Therefore, XGBoost was selected as the **final predictive model**.

## 📈 Key Results

* Excellent agreement between predicted and experimental values
* Reduced overfitting through optimized hyperparameters
* Reliable performance across validation data

(See plots and metrics in the notebook for detailed analysis.)


## 🔬 Scientific Significance

* Enables **rapid screening** of photocatalysts
* Supports **data-driven materials design**
* Reduces experimental cost and time
* Bridges **nanomaterials chemistry and machine learning**

## 🛠 Tools & Libraries
* Python
* NumPy, Pandas
* Scikit-learn
* XGBoost
* Matplotlib / Seaborn


## 📚 Potential Applications

* Wastewater treatment optimization
* Environmental nanotechnology
* Sustainable photocatalyst development
* AI-assisted materials science research





