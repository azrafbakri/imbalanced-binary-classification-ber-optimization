# Imbalanced Binary Classification (BER Optimization)

End-to-end workflow for **imbalanced binary classification**, selecting and tuning models to minimize **Balanced Error Rate (BER)**.

## What this project demonstrates
- Metric-first evaluation using Balanced Accuracy → **BER = 1 − Balanced Accuracy**
- **Stratified 5-fold cross-validation** for reliable estimates with class imbalance
- Model comparison (Logistic Regression, Decision Tree, Random Forest, AdaBoost, Bagging)
- Iterative hyperparameter refinement for the selected model
- Diagnostics: confusion matrix, ROC curve, precision–recall curve

## How to run
1. Create a virtual environment (optional)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place your datasets in the repo root (or update paths in the notebook):
   - `ProjectLABELED2025.xlsx`
   - `ProjectUNLABELED2025.xlsx` (optional)
4. Run the notebook:
   - Jupyter: `jupyter notebook`
   - VS Code: open the notebook and run all cells

## Output
If an unlabeled dataset is provided, the notebook writes:
- `predictions.csv` with `index` and `predicted_class`

