 🌧️ WRF Model Rainfall Skill Evaluation (CNTL vs DA)

**Developed by Nishant**

This repository evaluates rainfall forecasts from the WRF model during *Super Cyclone Kyarr (October 2019)*.
It compares **Control (CNTL)** and **Data Assimilation (DA)** configurations against **GPM** and **TRMM** satellite datasets.

---

## 🔍 Features
- Day-wise (1–6) and threshold-wise (2.5–124.5 mm) verification
- Metrics: POD, ETS, HSS, RMSE, Bias, Correlation
- Automatic plot generation and `.docx` report builder

---

## 🧩 Folder Structure
WRF-Rainfall-Skill-Evaluation/
├── data/
│ ├── sample_case_study/
│ ├── README_data.md
├── notebooks/
│ └── Rainfall_Skill_Evaluation.ipynb
├── outputs/
│ ├── plots/
│ └── reports/
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md

yaml
Copy code

---

## 📦 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Rainfall_Skill_Evaluation.ipynb
🌦️ Dataset
This project originally used rainfall data from the WRF model (CNTL & DA runs)
and observations from GPM and TRMM satellites for Super Cyclone Kyarr (2019).

🧠 Citation
Nishant (2025). WRF Model Rainfall Skill Evaluation (CNTL vs DA). GitHub Repository.

⭐ Star this repo if you find it useful!
🧑‍🔬 Contributions welcome.
