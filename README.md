README
Requirements
- Python 3.8+
- Packages: scikit-learn, pandas, numpy, matplotlib, shap, dice-ml, plotly, scipy, tqdm, seaborn (the script attempts to pip-install missing packages).

Installation and usage
1. Place recidivism_full.csv in your working directory.
2. Run the script containing the provided code. The top block will attempt to pip-install missing dependencies automatically. To install manually:
	pip install scikit-learn pandas numpy matplotlib shap dice-ml plotly scipy tqdm seaborn
3. Run the notebook cells in order.

Outputs:
- Console: model metrics (Accuracy, AUC) and aggregate summaries of CF and SHAP actionable coverage.
- Visual: feature importances bar chart, SHAP waterfall plots for inspected instances.
