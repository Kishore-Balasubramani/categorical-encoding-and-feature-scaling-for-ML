# Categorical Encoding and Feature Scaling for ML

##  Overview
This project demonstrates preprocessing techniques including:
- Categorical Encoding
- Feature Scaling

## Dataset
Small passenger dataset with:
- Gender
- City
- Size
- Age
- Fare

##  Techniques Used

### 1. Encoding
- Gender → Label Encoding
- City → One-Hot Encoding (drop first column)
- Size → Ordinal Encoding (Small=0, Medium=1, Large=2)

### 2. Feature Scaling
- Used RobustScaler due to presence of outliers in Fare

##  Output
Clean dataset ready for machine learning models

##  Author
Kishore Balasubramani
