<div align="center">

# MD ASIF AHMED ANTOR

**MECHANICAL ENGINEERING UNDERGRADUATE STUDENT**

MANUFACTURING ENGINEERING · VEHICLE ENGINEERING · COMPUTATIONAL METHODS

Southwest Petroleum University · Expected Graduation: June 2027

[GitHub](https://github.com/asifahmedantor) · [CNC Optimization Project](https://github.com/asifahmedantor/CNC-machining-parameter-optimization-ml) · [OEE Dashboard Demo](https://manufacturing-oee-dashboard.streamlit.app)

</div>

---

## ABOUT ME

I am an undergraduate student in Mechanical Engineering at Southwest Petroleum University, with academic interests in **advanced manufacturing and vehicle engineering**.

My engineering foundation includes manufacturing processes, engineering materials, CAD modeling, workshop practice, and CNC and lathe operations. Through independent projects, I explore how **Python, machine learning, and interactive visualization** can support machining analysis and manufacturing performance evaluation.

I am interested in graduate study and research that connects mechanical engineering fundamentals with computational methods to address practical engineering problems.

## PROJECT PORTFOLIO

## 01 — CNC MACHINING PARAMETER OPTIMIZATION

### Surface Roughness Prediction · Regression Modeling · Parameter Search

Developed a machine learning application to predict surface roughness (Ra) from depth of cut, feed rate, cutting speed, material type, and cutting tool. The project combines regression modeling, group-aware model validation, parameter search, and an interactive Streamlit dashboard.

### KEY CONTRIBUTIONS

- Compared Linear Regression, Random Forest, Gradient Boosting, and Extra Trees using 5-fold group-aware cross-validation with R², MAE, and RMSE.
- Grouped identical machining parameter combinations within the same validation fold to reduce data leakage from repeated machining conditions.
- Implemented a parameter search within the ranges represented in the dataset to identify machining conditions associated with lower predicted surface roughness.
- Built a Streamlit dashboard with interactive surface roughness prediction, feature importance, parameter-effect analysis, and 3D optimization visualizations.
- Ranked model-predicted machining conditions by predicted surface roughness and displayed the Top 10 candidate conditions.
- Added downloadable optimization results and reports.

### VALIDATED MODEL PERFORMANCE

| Model | Mean R² | R² SD | Mean MAE | Mean RMSE |
|---|---:|---:|---:|---:|
| **Extra Trees** | **0.9738** | **0.0341** | **0.0758** | **0.1479** |

Performance is reported using **5-fold group-aware cross-validation**, where identical machining parameter combinations are kept within the same fold to reduce data leakage.

### MODEL-BASED OPTIMIZATION RESULT

| Parameter | Best Model-Predicted Condition |
|---|---:|
| Depth of Cut (ap) | **0.75 mm** |
| Feed Rate (f) | **0.10 mm/rev** |
| Cutting Speed (Vc) | **200 m/min** |
| Material | **41Cr4** |
| Cutting Tool | **DNMG150608** |
| Predicted Surface Roughness (Ra) | **0.362 µm** |

> The optimization result is a model prediction obtained within the parameter ranges represented in the available dataset. It should not be interpreted as an experimentally verified optimal machining outcome.

### TECHNOLOGIES

Python · Scikit-learn · Pandas · NumPy · Streamlit · Plotly · Matplotlib

[EXPLORE PROJECT →](https://github.com/asifahmedantor/CNC-machining-parameter-optimization-ml)

---

### 02 — MANUFACTURING OEE DASHBOARD

**Manufacturing KPIs · Equipment Performance · Downtime Analysis**

Developed an interactive dashboard to evaluate **Overall Equipment Effectiveness (OEE)** and its Availability, Performance, and Quality components.

**KEY CONTRIBUTIONS**

- Calculated and visualized manufacturing KPIs using synthetic production data for three machines.
- Implemented machine and date filters, KPI indicators, and daily OEE trends.
- Compared machine performance and analyzed downtime to identify potential improvement priorities.
- Included interactive chart tooltips, production data tables, and empty-filter handling.

**DATA CONTEXT:** Educational project using synthetic manufacturing data.

**TECHNOLOGIES:** Python · Pandas · Streamlit · Altair

[EXPLORE PROJECT →](https://github.com/asifahmedantor/Manufacturing-OEE-Dashboard) · [OPEN LIVE DEMO →](https://manufacturing-oee-dashboard.streamlit.app)

---

## TECHNICAL FOUNDATION

| AREA | KNOWLEDGE & TOOLS |
|:-----|:------------------|
| Mechanical Engineering | Manufacturing processes, engineering materials, workshop practice |
| Design & Machining | CAD modeling, CNC operations, lathe operations |
| Programming & Data | Python, Pandas, NumPy |
| Machine Learning | Scikit-learn, regression modeling, model evaluation |
| Visualization | Plotly, Matplotlib, Altair |
| Application Development | Streamlit |
| Manufacturing Analytics | OEE, Availability, Performance, Quality, downtime analysis |

## ACADEMIC & RESEARCH INTERESTS

**ADVANCED MANUFACTURING**  
Machining parameter optimization, surface quality prediction, and manufacturing performance analysis.

**VEHICLE ENGINEERING**  
An area I intend to explore further through coursework, engineering projects, and graduate study.

**COMPUTATIONAL ENGINEERING**  
Applications of machine learning, data analysis, and visualization to mechanical engineering problems.

## EDUCATION

**BACHELOR’S DEGREE IN MECHANICAL ENGINEERING**  
Southwest Petroleum University  
School of Mechanical and Electrical Engineering  
September 2023 – June 2027 *(Expected)*

## ACADEMIC ENGAGEMENT

- **Participant** — 1st International Symposium on Oil & Gas CCUS and New Energy · June 2026
- **Participant** — Sanxingdui Research Practice Activity · July 2025
- **Student Representative** — International Conference on Carbonate Exploration and Development · December 2024

---

<div align="center">

**EXPLORING THE CONNECTION BETWEEN MECHANICAL SYSTEMS, MANUFACTURING, AND DATA.**

</div>
