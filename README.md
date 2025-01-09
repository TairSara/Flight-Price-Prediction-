# Flight Price and Destination Prediction

## Overview
This project focuses on predicting flight prices and destinations using various machine learning models including Decision Trees, XGBoost, Random Forest, and Naive Bayes. The project analyzes airline data to provide insights into pricing dynamics and travel patterns.

## Dataset
The dataset used in this project contains flight information including:
- Airlines
- Origin and destination
- Travel dates
- Departure and arrival times
- Flight duration
- Number of stops
- Prices
- Additional flight-related information

## Project Structure
- `flight_analysis.ipynb`: Jupyter notebook containing all the analysis and model implementations
- Data preprocessing scripts
- Model evaluation tools
- Visualization components

## Models Implemented
1. **Regression Models (Price Prediction)**:
   - Linear Regression (R² = 0.6171)
   - Decision Tree Regressor (R² = 0.7336)
   - XGBoost (Test accuracy: 0.7302)

2. **Classification Models (Destination Prediction)**:
   - Decision Trees (Test accuracy: 0.8811)
   - SVM (Test accuracy: 0.5292)
   - Random Forest
   - Naive Bayes

## Key Features
- Comprehensive data preprocessing
- Feature engineering
- Model comparison and evaluation
- Cross-validation (10-fold)
- Performance metrics analysis
- Handling of categorical variables
- Price category classification

## Results
- Strong performance in regression tasks, particularly with tree-based models
- Effective destination prediction using classification models
- Successful handling of overfitting through cross-validation
- Detailed performance analysis using various metrics (MSE, R-squared, Accuracy, ROC AUC)

## Technical Details
### Libraries Used
- Python
- Pandas for data manipulation
- Scikit-learn for machine learning algorithms
- Matplotlib and Seaborn for data visualization
- XGBoost for gradient boosting
- Missingno for missing data visualization

### Preprocessing Steps
1. Removal of unnecessary columns
2. Handling missing values
3. One-hot encoding of categorical variables
4. Feature normalization
5. Data splitting for training and testing

## Future Improvements
- Feature selection optimization
- Ensemble method exploration
- Investigation of external factors affecting flight prices
- Hyperparameter tuning for better model performance

## Authors
- Noam Dahan
- Tair Tubol
