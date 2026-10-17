# 🪐 NASA Kepler Exoplanet Data Analysis

**An Exploratory Data Analysis Project Using Python**

## 📌 Overview

This project explores data from NASA's Kepler mission to investigate exoplanet observations and understand the distribution of confirmed planets, planetary candidates, and false-positive detections.

Using Python, I performed exploratory data analysis (EDA), examined planetary radius measurements, and explored patterns in a dataset containing **9,564 rows and 50 columns**.

This project reflects my interest in data science, scientific computing, and astronomy.

## 🎯 Objectives

- Explore and understand an astronomical dataset.
- Analyze the distribution of Kepler Objects of Interest (KOIs).
- Investigate planetary radius measurements and potential outliers.
- Practice data cleaning, statistical analysis, and visualization.
- Present findings through a Jupyter Notebook.

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Dataset

The analysis uses a dataset of Kepler Objects of Interest.

Two important variables explored in this project are:

- `koi_disposition`: the classification assigned to an object.
- `koi_prad`: the planetary radius measurement, expressed in Earth-radius units.

### Classification Results

| Classification | Number of observations |
|---|---:|
| False Positive | 5,023 |
| Confirmed | 2,293 |
| Candidate | 2,248 |
| **Total** | **9,564** |

These counts represent the dataset analyzed in this project.

## 🔬 Methodology

1. **Data inspection:** Examined the dataset's dimensions, columns, and data structure.
2. **Exploratory analysis:** Investigated the distribution of classification categories.
3. **Data investigation:** Examined planetary radius measurements and potential outliers.
4. **Visualization:** Created plots to explore patterns in the data.
5. **Interpretation:** Reviewed the results and considered the limitations of the analysis.

## 💡 Key Findings

- False positives represent the largest classification group in the analyzed dataset.
- Confirmed planets and candidates make up the other two classification groups.
- Planetary radius measurements benefit from careful examination of extreme values.
- Data visualization helps communicate patterns that may not be obvious from tables alone.

## 📁 Project Files

- [`kepler_analysis.ipynb`](kepler_analysis.ipynb) — The notebook containing the analysis, code, tables, and visualizations.

## 🚀 Explore the Project

- **GitHub Notebook:** Browse the notebook in this repository.
- **Kaggle Notebook:** [View the original analysis on Kaggle](https://www.kaggle.com/code/yasminesaidi2/nasa-kepler-exoplanet-data-analysis).

## 🔭 Future Improvements

- Explore relationships between planetary radius and orbital period.
- Add further statistical comparisons and visualizations.
- Document data-cleaning and outlier-handling decisions in more detail.
- Explore machine learning classification as a separate extension.

## 👩‍💻 Author

**Yasmine Saidi**

Aspiring Computer Science student interested in data science, artificial intelligence, and scientific computing.

- [GitHub Profile](https://github.com/yasmine-saidi-cs)
- [Kaggle Profile](https://www.kaggle.com/yasminesaidi2)

## 📚 References

- [NASA Kepler Mission](https://science.nasa.gov/mission/kepler/)
- [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)

---

*This project is for educational and exploratory data analysis purposes. It does not independently confirm new exoplanet discoveries.*
