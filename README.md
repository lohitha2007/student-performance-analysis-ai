# Student Performance Analysis Using Data Analytics and AI

**Author:** Lohitha Galeti

## Project description
This beginner-friendly project demonstrates an end-to-end data analytics workflow using a student-performance dataset: data loading, data-quality checks, exploratory data analysis (EDA), charts, and a baseline linear regression model to estimate final grades.

## Problem statement
Educational stakeholders may benefit from understanding how study habits, previous grades, absences, and other variables relate to final academic results. This project explores these relationships in a dataset and presents descriptive visualizations and a simple prediction baseline.

## Dataset
- **Primary source:** UCI Machine Learning Repository — Student Performance
- **Dataset page:** https://archive.ics.uci.edu/dataset/320/student+performance
- The notebook attempts to download the official UCI archive automatically.
- If the download fails, the notebook generates synthetic demonstration data so the workflow can still run. Synthetic results must not be described as findings from the UCI dataset.

## Technologies used
- Python
- Jupyter Notebook / Google Colab
- pandas and NumPy
- Matplotlib
- scikit-learn

## Files
- `Lohitha_Student_Performance_Analysis.ipynb` — complete notebook and analysis workflow
- `requirements.txt` — Python dependencies
- `Lohitha_ProjectReport.docx` — project documentation

## How to run
### Option A: Google Colab
1. Open https://colab.research.google.com/
2. Choose **Upload notebook** and upload `Lohitha_Student_Performance_Analysis.ipynb`.
3. Run each cell from top to bottom.
4. If prompted, allow the notebook to access the internet to download the public UCI dataset.

### Option B: Local Python
1. Install Python 3.10 or newer.
2. Create and activate a virtual environment if desired.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter:
   ```bash
   pip install notebook
   jupyter notebook
   ```
5. Open the `.ipynb` file and run all cells.

## Analysis included
- Dataset shape, data types, missing values, duplicate rows, and descriptive statistics
- Distribution of final grades
- Average grade by study-time category when the column is available
- Absences versus final grades when the column is available
- Correlations between grade periods
- A baseline linear regression model evaluated using MAE, RMSE, and R-squared

## Limitations and responsible use
Correlation does not imply causation. The dataset represents a specific educational context. The model is a learning demonstration and should not be used for high-stakes decisions about individual students. If synthetic fallback data was used, results are illustrative only.

## Reference
UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/320/student+performance
