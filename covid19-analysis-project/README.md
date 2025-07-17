# COVID-19 Global Data Analysis & Visualization

This project provides a beginner-friendly analysis and visualization of global COVID-19 data using Python (Pandas, Matplotlib, Seaborn) and Power BI.

## Project Structure

```
covid19-analysis-project/
├── data/
│   └── covid_19_data.csv           # Main COVID-19 dataset
├── notebook/
│   └── covid_analysis.ipynb        # Jupyter notebook for analysis & visualization
├── outputs/
│   ├── summary.txt                 # (Optional) Summary of findings
│   ├── cleaned_covid19_global.csv  # Cleaned dataset for dashboarding
│   ├── Covid-19 Analysis Dashboard.pbix # Power BI dashboard file
│   └── Covid-19 Data Analysis Dashboard.jpeg # Screenshot of the dashboard
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
```

## How to Use

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
2. **Open the notebook:**
   ```
   jupyter notebook notebook/covid_analysis.ipynb
   ```
3. **Run the cells** to explore data loading, cleaning, EDA, and visualizations.
4. **Exported cleaned data** is saved to `outputs/cleaned_covid19_global.csv` for use in Power BI or Tableau.
5. **Power BI Dashboard:**
   - Open `outputs/Covid-19 Analysis Dashboard.pbix` in Power BI Desktop to view and interact with the dashboard.
   - A screenshot of the dashboard is also attached as `outputs/Covid-19 Data Analysis Dashboard.jpeg` for quick reference.

## Key Features
- Handles missing values and date parsing
- Answers key questions:
  - Top countries by cases and deaths
  - Weekly/monthly growth trends
  - Mortality rates by country
- Visualizes findings with line plots, bar charts, maps, and heatmaps
- Interactive dashboard built in Power BI

---
**Dataset Source:** Kaggle COVID-19 Global Dataset

**All analysis, visualizations, and dashboarding were completed by the project author.** 