# 🩸 Blood Donation Prediction (AutoML)

### Project Overview
A machine learning project to predict whether a donor will return to a blood center. This helps healthcare providers manage supply and target their outreach more effectively.

### Key Features
* **RFM Analysis:** Uses Recency, Frequency, and Monetary metrics to understand donor behavior.
* **AutoML with TPOT:** Used Genetic Programming to automatically discover the most efficient machine learning pipeline.
* **Data Cleaning:** Implemented Log Normalization on skewed monetary data to improve model performance.

### Results
* **Metric:** ROC-AUC Score (Receiver Operating Characteristic - Area Under Curve)
* **Score:** 0.7890
* **Interpretation:** A score of ~0.79 indicates a strong predictive model, significantly better than a random baseline (0.5), effectively distinguishing between returning and non-returning donors.

### How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt.`
3. Run the notebook `blood_donation.ipynb`.
