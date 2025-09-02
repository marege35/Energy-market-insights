# Energy Market Analysis: Electricity Prices in Southern Norway (2017–2023)

## Project Overview
This project investigates the main drivers of **electricity spot prices in Southern Norway** using time-series data (2017–2023).  
The goal was to identify how **global energy markets, weather conditions, and local hydropower factors** affect electricity price volatility.  

*This project was developed as part of a term paper at **Noroff University College (NUC)**.*  

## Research Questions
The analysis focused on five business-oriented questions:
1. How do **gas prices** affect electricity spot prices during high vs. low reservoir levels?  
2. Has the influence of **wind power generation** grown compared to rainfall in recent years?  
3. Are extreme electricity price spikes more strongly related to **global commodity prices** (oil, gas, coal) or **local factors** (reservoirs, temperature)?  
4. Has the relationship between **spot prices and actual electricity prices** changed after 2020?  
5. Do **global financial markets (dollar prices)** have more influence on spot prices than local weather factors?  

## Dataset
- Source: European electricity market data (Southern Norway)  
- Period: 2017–2023  
- Size: **54,264 entries** across **20 variables**  
- Variables include:  
  - Energy prices: electricity (spot & actual), gas, oil, coal  
  - Hydropower reservoir levels  
  - Wind generation, temperature, precipitation  
  - Consumption, production, dollar exchange rate  

## Methods & Tools
- **Statistical methods**:  
  - Descriptive statistics  
  - Pearson correlation  
  - t-tests  
  - Scatter plots & trend analysis  
- **Tools used**:  
  - Python (Pandas, NumPy, Matplotlib)  
  - Jupyter Notebook  
  - Pandas Profiling  

##  Key Findings
- **Gas prices** strongly correlated with electricity spot prices (0.74), especially when reservoir levels are low.  
- **Wind power** is becoming more influential than rainfall in recent years.  
- **Extreme price spikes** are more strongly linked to global gas and coal markets than local conditions.  
- After **2020**, the link between spot and actual prices weakened → making spot markets less reliable for predicting consumer prices.  
- **Dollar exchange rates** impact electricity prices more than local weather factors.  

## My Role
I performed the **data cleaning, statistical analysis, visualization, and interpretation**, and authored the full report.  

## Repository Contents
- `Energy analysis.pdf` – Full project report with data analysis and results  
- (Optional) Jupyter Notebook – *if included, contains code to reproduce the analysis*  

## How to Use
- Open `Energy analysis.pdf` for the full analysis and findings.  
- If the notebook is included, run it in Jupyter Notebook/Lab to reproduce the results.  

---

### Conclusion
This project highlights how **global energy markets (especially gas and currency fluctuations)** dominate local electricity pricing in Southern Norway.  
It showcases skills in **data wrangling, statistical analysis, and business-focused reporting** using real-world energy market data.  

