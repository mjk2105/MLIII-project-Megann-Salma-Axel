# Advanced Anomaly Detection: Predictive Maintenance
**Course:** Machine Learning III - Albert School
**Group:** Megann Kouandjeu - Salma Kamoun - Axel Chartier

## Project Overview
This project implements an unsupervised machine learning pipeline to detect failures in heavy machinery. We compare four key algorithms:
* Isolation Forest
* One-Class SVM
* Local Outlier Factor (LOF)
* Elliptic Envelope

## Key Findings
* **Optimal Model:** Isolation Forest.
* **Business Strategy:** We recommended a 6% contamination threshold to balance the high cost of machine downtime (€15,000) against maintenance alert fatigue.

## How to Run
1. Clone this repository.
2. Ensure you have `scikit-learn`, `pandas`, `seaborn`, and `matplotlib` installed.
3. Run the Jupyter Notebook `Session5_Anomaly_Detection_Notebook.ipynb`.
