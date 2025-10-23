# 🌧️ WRF Model Rainfall Skill Evaluation (CNTL vs DA)

> 🔍 **Developed by Nishant**  
> Evaluating rainfall prediction accuracy of the **Weather Research and Forecasting (WRF)** model during **Super Cyclone Kyarr (2019)** using **Control (CNTL)** and **Data Assimilation (DA)** experiments.  
> This open-source project performs both **day-wise** and **threshold-wise** skill analysis using **GPM** and **TRMM** observations, producing visual analytics and an automated `.docx` report.

---

## 🚀 Highlights

✅ **Day-wise & threshold-wise skill evaluation** (POD, ETS, HSS, RMSE, Bias, Correlation)  
✅ **Comparison between CNTL & DA runs** against GPM and TRMM observations  
✅ **Automatic report generation** (`.docx` format with plots and tables)  
✅ **Clean, reproducible Python/Colab workflow**  
✅ **Includes sample data for quick testing**

---

## 🧩 Key Metrics
| Metric | Description |
|:--|:--|
| **POD** | Probability of Detection — model’s success rate in detecting rainfall |
| **ETS** | Equitable Threat Score — accuracy after removing random hits |
| **HSS** | Heidke Skill Score — overall model skill against chance |
| **RMSE** | Root Mean Square Error — deviation from observed rainfall |
| **Bias** | Mean difference between model and observation |
| **r** | Pearson correlation — linear agreement strength |

---

## 🌦️ Dataset Overview

- **Model Outputs:** CNTL (Control run) & DA (Data Assimilation run)  
- **Observations:** GPM & TRMM satellite rainfall data  
- **Event:** *Super Cyclone Kyarr (October 2019)*  
- **Analysis Period:** Days 1–5 + Combined case (24–30 Oct 2019)

---

## 🧮 Outputs

📊 **Plots:**  
- Day-wise skill metrics (POD, ETS, HSS, RMSE, Bias, r)  
- Threshold-wise performance curves  
- Comparison bar charts across GPM & TRMM  

📑 **Report:**  
- `Final_Super_Cyclone_Kyarr_Rainfall_Analysis_Report.docx`

---

## 🧠 Citation / Use
If you use this work, please cite as:
> *Nishant (2025). WRF Model Rainfall Skill Evaluation (CNTL vs DA). GitHub Repository.*

---

⭐ **Star** this repo if you find it useful!  
👩‍🔬 Contributions and collaborations welcome!
