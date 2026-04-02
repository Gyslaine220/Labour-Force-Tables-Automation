# Labour Force Table Automation

## Project Overview
This project aims to **automate the generation of Labour Force Survey (LFS) tables** using Python.  
Traditionally, tables are produced manually in Stata, which is time‑consuming and repetitive.  
With Python, we can build **reproducible pipelines** and **interactive dashboards** that make outputs dynamic, transparent, and easy to update.

---

## Features
- Import raw survey data directly from Stata `.dta` files or CSV/Excel.
- Clean and transform datasets with reproducible scripts.
- Generate automated summary tables (employment by age, gender, education, region).
- Export results to Excel, HTML, or JSON for institutional use.
- Interactive dashboard built with **Streamlit**  for filtering and visualization.
- Modular design for scalability (easy to add new tables or indicators).

---

##  Tech Stack
- **Python** (pandas, numpy)
- **Streamlit** (dashboard & interactivity)
- **Plotly** (visualizations)
- **Stata → Python integration** via `pandas.read_stata`

---

## Project Structure

##  Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/Gyslaine220/Labour-Force-Table-Automation.git
   cd Labour-Force-Table-Automation
   
## Install dependencies
pip install -r requirements.txt

## - Run the Streamlit dashboard
streamlit run dashboard/app.py
## Example Outputs
- Employment status by age group and gender (interactive table).
- Labour force participation by education level.
- Regional breakdowns with bar charts.

## Impact
This project supports evidence‑based policy by:
- Reducing manual coding time.
- Ensuring reproducibility and transparency.
- Making labour market statistics accessible through interactive dashboards.
 ## Next Steps
- Add more indicators (unemployment rate, underemployment, informal sector).
- Deploy dashboard on institutional website.
- Expand to other surveys (e.g., CPI, household surveys).

## Author
ISHIMWE GYSLAINE
Applied Statistician | Data Scientist | Innovator in Social Impact Analytics
Currently at the National Institute of Statistics of Rwanda (NISR), focusing on automation and dynamic dashboards for labour force analytics.
