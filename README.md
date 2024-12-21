# IMDb Score Prediction for Movies 🎬

This project focuses on analyzing movie metadata to predict IMDb scores and classify movies into categories based on their ratings. By leveraging machine learning algorithms, we explore various features such as cast popularity, budget, and critic reviews to gain insights into what makes a movie successful.

## Key Features

### Data Cleaning & Preprocessing:
- Removed irrelevant or redundant columns.
- Handled missing values effectively using median and most-frequent replacements.
- Binned IMDb scores into categories (Bad, Average, Good, Excellent).

### Exploratory Data Analysis (EDA):
- Visualized relationships between IMDb scores, profit percentage, and critic reviews.
- Identified top-performing movies, actors, and countries contributing to movie success.

### Feature Engineering:
- Created new features like `Profit_Percentage` and `critic_review_ratio`.
- Consolidated categories like countries and content ratings for model efficiency.

### Machine Learning Models:
- Implemented and compared **SVC**, **Random Forest**, and **Gradient Boosting** models.
- Performed hyperparameter tuning using `GridSearchCV`.
- Evaluated models using accuracy, precision, recall, and F1 scores.

### Visualization:
- Plotted classification metrics and accuracy comparisons.
- Highlighted key contributors to movie success with bar charts and scatterplots.

## Results
- **Random Forest** achieved the highest accuracy (~74.4%), making it the most reliable model for this dataset.
- Visualizations helped in understanding the trade-offs between commercial success and critical acclaim.
