# IBM-Capstone
In this Capstone project, I understand how to use the Data Science techniques,data analysis, data visualization and machine learning by using the Python..
# SpaceX Falcon 9 Landing Prediction
## IBM Data Science Capstone Project

---

## Project Overview
This project predicts whether the SpaceX Falcon 9 
first stage will successfully land after launch.
SpaceX saves money by reusing the first stage booster.
If we predict a successful landing, we can estimate 
the launch cost.

- SpaceX Launch Cost : $62 Million
- Competitor Cost    : $165 Million
- Savings per Launch : $103 Million

---

## Objective
Build a Machine Learning model to predict 
if the Falcon 9 first stage will land successfully.

---

## Dataset
- Source  : SpaceX REST API + Wikipedia
- Records : 101 launches
- Target  : Class (0 = Failed, 1 = Success)
- Features: 83 columns after encoding

---

## Modules Completed
1. Data Collection (API + Web Scraping)
2. Data Wrangling
3. Exploratory Data Analysis (SQL)
4. Data Visualization (Matplotlib + Seaborn)
5. Geospatial Analysis (Folium Maps)
6. Machine Learning Prediction

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- SQLite
- Scikit-learn

---

## Machine Learning Models
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 83.3%    |
| SVM                 | 83.3%    |
| Decision Tree       | 83.3%    |
| KNN                 | 83.3%    |

Best Model: SVM with Linear Kernel

## Key Findings
- Launch success rate improved over time
- KSC LC-39A is the most successful site
- Best payload range is 4000-6000 kg
- LEO orbit has highest success rate
- All launch sites are near coastline

## How to Run
1. Clone the repository
2. Install requirements:
   pip install pandas numpy matplotlib
   seaborn folium scikit-learn
3. Run notebooks in order:
   - 01_data_collection_api.ipynb
   - 02_data_wrangling.ipynb
   - 03_eda_sql.ipynb
   - 04_eda_visualization.ipynb
   - 05_folium_maps.ipynb
   - 06_machine_learning.ipynb

## Conclusion
All 4 models achieved 83.3% accuracy in 
predicting SpaceX Falcon 9 landing success.
SVM with linear kernel is recommended as 
the best model.

## Author
IBM Data Science Capstone Project
