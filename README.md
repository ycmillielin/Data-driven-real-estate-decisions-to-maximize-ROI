# Data-driven-real-estate-decisions-to-maximize-ROI

**Goal**: Identify the 10 areas (US Census Tract) in the country with the highest expected rent growth in the next three years (2025).

**Methodology**: Use property level rent data in conjunction with additionally gathered data (Economics, Demographic, Location) to train models that predicts the change in rent for the entire country from 2022 to 2025.

**Final dataset for machine learning model**: https://drive.google.com/file/d/1K9_PYgt8vkdneCvKcAkVhpQuRllePO-y/view?usp=sharing

**Modeling Process**: 
  - Way to train the model ![Screen Shot 2022-09-01 at 1 50 38 PM](https://user-images.githubusercontent.com/96958028/188010072-8c869895-39ba-448c-bc7c-2120a2cbed8e.png)
  - Models to apply: Linear Regression, Decision Tree, Random Forest, XG Boost, LightGBM, RNN Long short-term memory(LSTM)  
  - Conducted GridSearchCV with 10-fold cross validation to find the best hyper-parameters in each machine learning algorithm 
  - Result: We choose XGBoost as our final model with highest average R squared, which is about 0.96

**Result**:  
  - Final model: XGBoost 
  - R-Squared Value: 0.9644
  - Expected 3 Year ROI* ($10m): $9.17 Million Profit

**Project sponsor: Centro.io**      
Centro is a data driven asset management firm based in Miami, Florida, focused on the acquisition and management of apartment communities and shopping centers throughout the southeast United States and Texas. Centro in its partnership with Fondo Atlas manages assets in excess of $125M and properties totaling more than 600,000 sq. ft.
  
  
