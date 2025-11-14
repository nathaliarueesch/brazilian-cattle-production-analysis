
# Brazilian Cattle Production Analysis

This project presents a small statistical analysis of Brazilian cattle slaughter over time, based on simulated data inspired by official IBGE charts.  
The goal is to practice descriptive statistics and basic probability concepts using a simple time series of quarterly cattle slaughter volumes.

The project is part of my Data Science learning journey and focuses on:

- Working with tabular time series data in Python  
- Computing descriptive statistics (mean, median, etc.)  
- Deriving probabilities from a finite sample space  
- Interpreting results in a clear, data-driven way

---

## 1. Dataset Description

The dataset contains quarterly cattle slaughter data for Brazil between 2019 and 2024.  
Each row represents one quarter in a given year and includes:

- `Year` – calendar year  
- `Quarter` – quarter number (1–4)  
- `TotalMillionHead` – total number of slaughtered cattle (in millions of head)  
- `FemaleSharePercent` – percentage of females in the slaughter for that quarter  
- `MaleSharePercent` – percentage of males in the slaughter for that quarter

> The values are *simulated and approximate* based on patterns visible in public IBGE charts.  
> They are used for educational and portfolio purposes only, not for official analysis.

---

## 2. Statistical Questions Explored

The notebook answers questions such as:

- In which quarter was the total slaughter volume highest?  
- What was the highest estimated number of females slaughtered in a quarter?  
- Is slaughter volume always increasing over time, or does it fluctuate?  
- What are the **mean** and **median** of first-quarter slaughter volumes across years?  
- Is there a **mode** in the first-quarter slaughter volumes?  
- Among all quarters from 2019 to 2023, what is the probability that a randomly selected quarter is an odd quarter (Q1 or Q3) *and* is the highest slaughter quarter in its year?

These questions mirror typical exercises in introductory statistics, but are implemented programmatically in Python.

---

## 3. Files in This Repository

- `data/cattle_quarterly.csv`  
  Simulated quarterly cattle slaughter dataset.

- `src/statistics_utils.py`  
  Helper functions for computing descriptive statistics and simple probabilities.

- `notebooks/cattle_analysis.ipynb`  
  Jupyter Notebook with the full analysis, calculations and explanations.

- `README.md`  
  Project documentation.

- `requirements.txt`  
  Python dependencies for running the notebook.

---

## 4. How to Run the Project

1. (Optional) Create and activate a virtual environment.

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
notebooks/cattle_analysis.ipynb
```

---

## 5. Technologies Used

- Python 3  
- pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook

---

## 6. Author

**Nathalia Rüesch Neiva**  
Data Science & Behavioral Analysis Student  
Based in Bern, Switzerland
