# 🌧️ WRF Model Rainfall Skill Evaluation (CNTL vs DA)

**Developed by Nishant**

This repository evaluates rainfall forecasts from the WRF model during *Super Cyclone Kyarr (October 2019)*.
It compares **Control (CNTL)** and **Data Assimilation (DA)** configurations against **GPM** and **TRMM** satellite datasets.

## 🔍 Features
- Day-wise (1–6) and threshold-wise (2.5–124.5 mm) verification
- Metrics: POD, ETS, HSS, RMSE, Bias, Correlation
- Automatic plot generation and `.docx` report builder

## 📦 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Rainfall_Skill_Evaluation.ipynb
Outputs appear under /outputs/reports/.

📄 License

MIT License © 2025 Nishant
