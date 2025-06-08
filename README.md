
# ✈️ Aviation Accident Data Analysis

This project explores a dataset of aviation accidents to uncover trends and insights related to incident frequency, injury severity, aircraft types, and more. The goal is to clean the data, perform exploratory analysis, and visualize key patterns that could inform safety assessments or further research.

---

## 📁 Project Structure

- `analysis.ipynb`: Main Jupyter notebook containing all code for data cleaning, analysis, and visualization.
- `AviationData.csv`: Source dataset (not included here but referenced in the notebook).

---

## 📊 Objectives

- Clean and preprocess the aviation dataset.
- Analyze accident trends over time.
- Explore the distribution of injury severity.
- Examine emergency responses and accident phases.
- Visualize findings using Seaborn and Matplotlib.

---

## 🔧 Key Tasks Performed

### 1. **Data Cleaning**
- Removed or filled null values based on proportion and data type.
- Standardized text fields (e.g., `Injury.Severity`, `Emergency.Response`).
- Converted `Event.Date` to datetime format.
- Extracted year and month from date for trend analysis.
- Unified units in the `House Size` field (separate context).

### 2. **Feature Engineering**
- Extracted year from `Event.Date` to study yearly trends.
- Trimmed injury severity values to remove counts in parentheses (e.g., `"Fatal(80)"` → `"Fatal"`).

### 3. **Visualizations**
- **Line Plot**: Aviation accidents over time by year.
- **Bar Chart**: Distribution of injury severities.
- **Pie Chart**: Share of Yes/No responses for emergency situations.
- **Additional insights**: Phase of flight analysis, aircraft damage extent, etc.

---

## 📈 Sample Insights

- There is a noticeable fluctuation in the number of accidents over the years.
- Fatal injuries are the most commonly reported severity.
- Emergency response was reported in a relatively small proportion of cases.
- Most accidents occur during specific flight phases such as landing or takeoff.

---

## 🛠️ Tools & Libraries Used

- **Python** with:
  - `pandas` – for data cleaning and manipulation
  - `matplotlib` – for plotting
  - `seaborn` – for attractive statistical visualizations
  - `re` – for regular expression-based text cleaning

---

## 📌 How to Run

1. Clone this repo or download the notebook and dataset.
2. Open the notebook in Jupyter or a compatible environment.
3. Make sure `AviationData.csv` is in the correct path or update the path in the notebook.
4. Run all cells to view the analysis and plots.

---