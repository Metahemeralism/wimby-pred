# Tennis Analysis: Wimbledon 2025 Prediction

This project uses machine learning to analyze ATP tennis data and predict the outcome of the men's singles final at Wimbledon 2025 between Carlos Alcaraz and Jannik Sinner.

## Project Structure
- `notebooks/`: Jupyter notebooks for data analysis and modeling
- `data/`: Raw datasets (e.g., `atp_tennis.csv`)
- `images/`: Visualizations and tree diagrams (e.g., `wimby_tree.png`)
- `requirements.txt`: Python dependencies

## Features
- Data cleaning and feature engineering for tennis match data
- Analysis of player form and surface-specific performance
- Random Forest model to predict match outcomes
- Visualization of feature importance and decision trees

## Usage
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run `notebooks/main.ipynb` to reproduce the analysis and predictions

## Results
- The Random Forest model predicts Alcaraz to win the Wimbledon 2025 final.
- Model test accuracy is printed in the notebook.
- All 100 decision trees are visualized in the images folder.

## License
MIT
