# Hull Tactical Market Prediction - Final Project Report
## Kaggle Competition-Based Machine Learning Project

**Student:** Divit Pratap Singh
**Project Type:** Individual (Solo)
**Repository:** https://github.com/dps08/kaggle-market-prediction
**Competition:** https://www.kaggle.com/competitions/hull-tactical-market-prediction

---

## Team Contributions

**Team Member:** Divit Pratap Singh (Solo)

**Contributions:**
- Data collection and preprocessing: 100%
- Exploratory data analysis: 100%
- Feature engineering: 100%
- Model development: 100%
- Hyperparameter tuning: 100%
- Model evaluation: 100%
- Code implementation: 100%
- Documentation: 100%

**Total:** Individual project, all work completed independently.

---

## Code Repository

**GitHub Repository:** https://github.com/dps08/kaggle-market-prediction

### Repository Structure:
- `Final_Project.ipynb` - Complete analysis notebook with all code and results
- `results/` - Model performance metrics and outputs
  - `final_best_model.csv` - Best model performance
  - `all_model_results.csv` - Comprehensive results
  - `feature_importance.csv` - Feature rankings
  - `figures/` - Visualization outputs
- `data/` - Input data directory (download from Kaggle competition)
- `README.md` - Project overview and instructions

### How to Reproduce:
1. Clone repository: `git clone https://github.com/dps08/kaggle-market-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Download data from Kaggle competition
4. Run `Final_Project.ipynb` notebook

### Random Seeds:
All models trained with `random_state=42` for reproducibility

---

## Project Summary

This project tackles the Hull Tactical Market Prediction Kaggle competition, which challenges participants to predict S&P 500 daily excess returns. The project demonstrates:

1. **Advanced feature engineering** (94 → 238 features)
2. **Multiple machine learning models** (Ridge, XGBoost, LightGBM)
3. **Proper time-series validation** (prevents data leakage)
4. **Ensemble methods** for improved performance
5. **Domain-driven approach** using financial market knowledge

**Key Results:**
- Information Coefficient: 0.068 (exceeds 0.05 target)
- Statistical significance: p-value = 0.012
- Kaggle competition score: 3.489

All code, results, and analysis available in the repository above.
