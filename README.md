# 📊 Crime in Los Angeles: Exploratory Data Analysis

This project presents an exploratory analysis of crime data in Los Angeles using Python. It uncovers insights into crime frequency by hour, identifies hotspots for night crimes, and analyzes victim age distributions.

## 📁 Dataset

- `crimes.csv`: Contains crime incident reports with details including time of occurrence, location, and victim age.

## 📘 Notebook Overview

The Jupyter notebook (`notebook.ipynb`) includes:

### 1. **Hourly Crime Trends**
Analyzed the time of occurrence (`TIME OCC`) to extract hourly trends.
- Crimes are most frequent around noon (12:00).

### 2. **Night Crime Hotspots**
Filtered crimes occurring during night hours (10 PM to 3 AM).
- Identified the area with the highest night crime volume using frequency counts.

### 3. **Victim Age Demographics**
Grouped victim ages into brackets:
- `0-17`, `18-25`, `26-34`, `35-44`, `45-54`, `55-64`, `65+`
- Determined which age groups are most affected.

### 4. **Visualizations**
Used `matplotlib` and `seaborn` to plot:
- Crime frequency by hour.
- Victim age distribution.

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📌 How to Run
1. Clone the repository
2. Install dependencies
3. Open `notebook.ipynb` in Jupyter
4. Run all cells to reproduce the analysis

## 📈 Sample Output
- A bar plot showing peak crime hours.
- Console output indicating the most dangerous area at night.
- Summary statistics of age-based victimization.

---

**Author:** Syarwina  
**License:** MIT  
****
