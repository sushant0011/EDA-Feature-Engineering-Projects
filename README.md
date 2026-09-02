# EDA & Feature Engineering Projects

Is repository me maine alag-alag datasets par kiya gaya **Exploratory Data Analysis (EDA)** aur **Feature Engineering** ka kaam collect kiya hai. Har notebook ek real-world dataset ko explore karta hai — missing values, distributions, outliers, correlations dekhta hai, aur model-ready features banata hai.

## 📁 Projects

| # | Notebook | Dataset | Highlights |
|---|----------|---------|------------|
| 09 | [Red Wine Quality EDA](notebooks/09_Red_Wine_DatasetEDA.ipynb) | [Wine Quality (Red)](https://archive.ics.uci.edu/dataset/186/wine+quality) | Data profiling, distribution analysis, correlation heatmap, outlier detection on physicochemical wine properties |
| 10 | [Flight Price Prediction EDA](notebooks/10_Flight_Price_predictionEDA.ipynb) | Flight Price Dataset | Date/time feature extraction (day, month, duration), categorical encoding, price trend analysis |
| 11 | [Google Play Store EDA + Feature Engineering](notebooks/11_EDA_Feature_Eng_gplaystoreDataset.ipynb) | [Google Play Store Apps](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv) | Duplicate handling, missing value treatment, category-wise analysis, feature transformation |

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📂 Repository Structure
```
.
├── notebooks/
│   ├── 09_Red_Wine_DatasetEDA.ipynb
│   ├── 10_Flight_Price_predictionEDA.ipynb
│   └── 11_EDA_Feature_Eng_gplaystoreDataset.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

> **Note:** Raw dataset files (`.csv` / `.xlsx`) are not included in this repo to keep it lightweight. Dataset sources/links are mentioned above — download and place them in a local `data/` folder before running the notebooks (update file paths if needed).

## 🚀 How to Run
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
jupyter notebook
```

## 📌 About
These notebooks are part of my data analysis and feature engineering practice—aimed at sharpening my EDA workflow and feature transformation techniques through hands-on work with real datasets.

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
