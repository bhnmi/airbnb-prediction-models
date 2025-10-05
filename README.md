**Airbnb Listing Prediction**

Author: Behnam Zoghi Roudsari
Project: Predictive modeling of Airbnb listing performance

**Overview**

This project uses machine learning and econometric models to predict Airbnb listing outcomes. The analysis focuses on listings in Sicily (March and December) and Rome, exploring model performance, feature importance, and generalizability across dates and cities.

**Methodology**

**Data Preparation:**

Downloaded Airbnb listings data for Sicily and Rome.

Carried out data wrangling: extracted amenities, imputed missing values, and created engineered features.

**Model Building:**

Four models were implemented:

OLS

LASSO

Random Forest

XGBoost

LightGBM

Models were evaluated using cross-validation and holdout datasets.

Feature importance was analyzed for Random Forest, XGBoost, and LightGBM.

**Validation:**

Applied models to two “future” datasets:

Later date in the same city (Sicily December)

Another city (Rome)

Compared predictive performance and discussed generalizability.

**Results & Discussion**
**Future Data (Sicily, Later Date)**

R-squared decreased slightly, but overall performance remained stable.

Machine learning models (Random Forest, XGBoost, LightGBM) maintained or slightly improved performance.

Random Forest remained the top performer, followed by LightGBM and XGBoost.

LASSO and OLS showed significant deterioration, highlighting sensitivity to scaling and model construction.

**Other City Data (Rome)**

Performance dropped significantly for all models.

R-squared values were low or negative; RMSE increased.

Machine learning models still outperformed OLS and LASSO, but differences among Random Forest, LightGBM, and XGBoost were less pronounced.

Features like location and neighborhood were predictive in Sicily but less transferable to Rome.

Results emphasize that models trained on one city may not generalize well to cities with different characteristics.

