# 🌱 Greenhouse Gas Emission Forecasting

This project is developed as part of the **AICTE – Green AI Internship (June 2025 Cycle)**.  
The objective is to forecast greenhouse gas (GHG) emissions in various industries using real-world supply chain data.

---

## 📌 Project Objective

To analyze and predict **carbon dioxide (CO₂)** emissions using time series forecasting models, based on supply chain emissions data from US industries between 2010–2016.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `GHG_EmissionWEEK1.ipynb` | Week 1: Data import, merging multiple Excel sheets, and preparing a combined dataset |
| `GHG_EmissionWEEK2.ipynb` | Week 2: Forecasting CO₂ emissions using the ARIMA model and visualizing future trends |
| `ghg_data.csv` | Exported cleaned dataset used for model training |
| `README.md` | This project summary and documentation file |

---

## 🧪 Tools & Libraries Used

- **Python**
- **Pandas** & **NumPy** (Data handling)
- **Matplotlib** & **Seaborn** (Data visualization)
- **pmdarima** (Auto ARIMA modeling)
- **Scikit-learn** (Scaling, model comparison)

---

## 📊 Highlights

- ✅ Merged and cleaned over 7 years of GHG supply chain data across industries and commodities
- ✅ Grouped and visualized year-wise CO₂ emission trends
- ✅ Used ARIMA to forecast emissions from 2017 to 2021
- ✅ Output is presented in both code and graphical format

---

## 📚 Dataset Details

**Source**:  
`SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`  
Provided by **Edunet Foundation** for the Green AI Internship (2025)

**Data Includes**:
- Supply chain emission factors (CO₂, CH₄, N₂O, other GHGs)
- Industry/Commodity codes and names
- DQ scores for reliability, temporal/geographic/technological correlations

---

## 📈 Forecast Output Example

![CO2 Emission Forecast](https://github.com/VINAY-TEJA-29/Greenhouse-Gas-Emission-Forecast/assets/example-forecast.png)  
*Note: Add your own image or remove this line if not used*

---

## 🙋‍♂️ Author

**Polampalli Vinay Teja**  
B.Tech CSE – AI & ML (2023–2027)  
Malla Reddy Engineering College (MREC), Hyderabad  
- 📧 vinayteja292005@gmail.com  
- 🔗 [GitHub](https://github.com/VINAY-TEJA-29)

---

## 📌 Future Work (Week 3 Ideas)

- 📊 Build a Streamlit Dashboard to show top polluting industries
- 🔍 Compare ARIMA with Random Forest regression
- 📉 Analyze which GHG is increasing the most over time

---
