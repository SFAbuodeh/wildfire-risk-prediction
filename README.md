# wildfire-risk-prediction


## Project Overview
This project analyzes and predicts wildfire behavior across the United States using real incident data (FPA-FOD). It includes:

- Exploratory Data Analysis (EDA) on wildfire trends, causes, and sizes
- Interactive maps showing wildfire locations and concentrations
- Animated heatmaps showing wildfire spread over time
- Machine Learning models predicting whether a fire will become large (≥ 1000 acres)

## Technologies Used
- Python (pandas, scikit-learn, folium, matplotlib)
- Jupyter Notebooks
- GitHub

## Key Results
- Logistic Regression achieved ~74% balanced accuracy and high recall for large fires
- Random Forest achieved ~99% overall accuracy but lower recall for large fires
- Visualized fire locations and risk patterns with interactive maps

## File Structure
- `/data/` - Data files
- `/notebooks/` - Analysis and modeling notebooks
- `/outputs/` - Interactive maps and visualizations
- `README.md` - This file

## Future Improvements
- Improve fire size prediction precision using SMOTE or advanced models (XGBoost)
- Integrate real-time NASA FIRMS satellite fire data

---
