# UIDAI Data Hackathon – Aadhaar Data Analysis

## 📌 Problem Overview

This project analyzes UIDAI Aadhaar datasets to identify meaningful patterns, trends, and anomalies that can support data-driven decision-making and system improvements.

The analysis focuses on:

* Enrolment trends
* State-wise comparisons
* Biometric update patterns
* Demographic insights
* Simple anomaly detection

---

## 📂 Dataset Used

Official UIDAI datasets provided for the hackathon:

* Aadhaar Enrolment Data
* Aadhaar Biometric Data
* Aadhaar Demographic Data

The datasets were used **as provided**, without modification or artificial data generation.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook (VS Code)

No web technologies (HTML/CSS/JS) were used.

---

## 📁 Project Structure

```
UIDAI_DATA_HACKATHON/
│
├── data/
│   ├── api_data_aadhar_biometric/
│   │   ├── api_data_aadhar_biometric_0_500000.csv
│   │   ├── api_data_aadhar_biometric_500000_1000000.csv
│   │   ├── api_data_aadhar_biometric_1000000_1500000.csv
│   │   └── api_data_aadhar_biometric_1500000_1861000.csv
│   │
│   ├── api_data_aadhar_demographic/
│   │   ├── api_data_aadhar_demographic_0_500000.csv
│   │   ├── api_data_aadhar_demographic_500000_1000000.csv
│   │   ├── api_data_aadhar_demographic_1000000_1500000.csv
│   │   └── api_data_aadhar_demographic_1500000_2000000.csv
│   │
│   └── api_data_aadhar_enrolment/
│       ├── api_data_aadhar_enrolment_0_500000.csv
│       ├── api_data_aadhar_enrolment_500000_1000000.csv
│       └── api_data_aadhar_enrolment_1000000_1500000.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── figures/
│   │   ├── enrolment_trends.png
│   │   └── state_wise_comparison.png
│   │
│   └── tables/
│       ├── anomaly_detection.csv
│       └── summary_statistics.csv
│
│
└── requirements.txt
│
└── README.md



## ▶️ How to Run

1. Open `analysis.ipynb` in VS Code or Jupyter
2. Ensure required Python libraries are installed
3. Run all cells from top to bottom

All outputs (graphs and tables) are saved automatically.

---

## 📊 Key Insights

* Aadhaar enrolments are concentrated in a few high-population states
* Biometric updates correlate with enrolment-heavy regions
* Certain time periods show anomalous enrolment spikes
* Dataset limitations restrict trend analysis to available periods

---

## 👥 Team Contribution

* **Data Engineering & Analysis:** Notebook implementation, visualizations, anomaly detection
* **Research & Documentation:** Problem study, insights interpretation, report writing

---

## ⚠️ Note

This analysis strictly uses the data provided for the hackathon and avoids assumptions beyond the dataset scope.
