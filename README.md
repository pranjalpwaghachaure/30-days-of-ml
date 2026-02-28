Day 01 — Titanic EDA
30 Days of Machine Learning**

 What This Project Covers
-  Data loading & first look
-  Data cleaning & null handling
- survival stats & analysis
- 6 visualizations (donut, bar, histogram, heatmap, boxplot, correlation)
- Bonus: Logistic Regression baseline model (~78% accuracy, AUC: 0.82)

📁 Files
| File | Description |
|------|-------------|
| `titanic_eda.ipynb` | Main notebook — run this! |
| `titanic.csv` | Dataset (891 passengers) |
| `titanic_model.pkl` | Saved Logistic Regression model |
| `*.png` | All generated visualizations |

 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook titanic_eda.ipynb
```

 Key Findings
- Overall survival rate: **38%**
- Women had **~74%** survival rate vs men **~19%**
- 1st class passengers had **~63%** survival vs 3rd class **~24%**
- Children had higher survival rates
- Model: Logistic Regression → **78.2% accuracy**, **0.82 AUC**

Tech Stack
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-learn`


Day 1/30 — #30DaysOfML 
