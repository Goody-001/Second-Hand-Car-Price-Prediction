# Second-Hand-Car-Price-Prediction
This project builds a machine learning model using **Linear Regression** to predict the prices of second-hand cars based on various numerical features. It uses structured data and serves as an introductory project into regression modeling.

## Dataset
- **File**: `Car_prices.csv`
- The dataset includes structured data related to second-hand cars, such as mileage, engine size, and power, along with the target variable: **current price**.
- The dataset is included in this repository.

## Project Overview
- Environment: **Jupyter Notebook**
- Language: **Python**
- Model Used: **Linear Regression** (baseline model)
- Goal: Predict `current price` based on other numerical features.

## Performance
- **R² Score**: `0.8797`
- **RMSE**: `42,533.48`
- **Price Range**: 28,226.50 – 584,267.50
The model performs well for a first attempt, capturing approximately 88% of the variance in car prices. Further performance gains are expected with more advanced models in future iterations.

## Key Steps
- Data Loading and Exploration
- Data Cleaning and Feature Selection
- Data Visualization (Correlation Heatmap)
- Model Training (Linear Regression)
- Evaluation using R² and RMSE

## Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

To install dependencies:
pip install -r requirements.txt

## How to Run
Clone this repository or download the files.
Ensure you have Python installed with the required libraries.
Open the Jupyter Notebook (.ipynb) file.
Run the cells in order to reproduce the results.

Next Steps
This project uses Linear Regression as a starting point and was created as part of my learning journey into machine learning.

## Future updates may include:
Training more advanced models (e.g., Random Forest, XGBoost)
Hyperparameter tuning
Feature engineering
Outlier detection and scaling

These updates will be added and uploaded progressively as I continue learning.

## License
This project is licensed under the MIT License — feel free to use, modify, and share with attribution.

## Acknowledgments
This is a personal learning project to understand basic regression modeling using real-world data.
