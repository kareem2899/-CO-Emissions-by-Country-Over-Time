📊 Dataset

Source: Our World in Data – CO₂ Emissions

This dataset provides global CO₂ emission statistics from fossil fuels, industry, coal, oil, and gas, broken down by country and year.

📖 Description

In this project, we explore:

Historical CO₂ emissions by country and region.

Growth rates in emissions over decades.

The top contributors to global emissions.

Different sources of emissions (coal, oil, gas, cement, etc.).

Normalized emissions per capita for fair country comparison.

We also use analytical storytelling with time series analysis and data visualization to better understand global environmental trends.

🎯 Learning Outcomes

By completing this project, interns will gain experience in:

📅 Time series analysis of emissions data.

🔢 Multi-index grouping with countries and years.

📊 Data visualization using line charts, bar plots, and heatmaps.

📉 Rolling averages for trend smoothing.

🌐 Comparative analysis of countries and regions.

💡 Hints & Approach

Normalize CO₂ emissions per capita for fairness.

Use rolling averages to smooth long-term trends.

Compare 1990 vs. 2020 emissions for the top 10 countries.

Create heatmaps to visualize emissions by country and year.

🛠️ Tech Stack

Python 3

Pandas (data cleaning & analysis)

Matplotlib / Seaborn (visualizations)

Numpy

Jupyter Notebook (interactive analysis)

📂 Project Structure
CO2-Emissions-Analysis/
│
├── data/
│   └── co2_emissions.csv          # Dataset (downloaded from Our World in Data)
│
├── notebooks/
│   └── co2_emissions_analysis.ipynb   # Main analysis notebook
│
├── scripts/
│   └── co2_analysis.py            # Reusable Python script for analysis
│
├── README.md                      # Project documentation
└── requirements.txt               # Required Python libraries

🚀 How to Run the Project


Install dependencies

pip install -r requirements.txt


Download dataset
Get the dataset from Our World in Data
 and place it inside the data/ folder.

Run Jupyter Notebook

jupyter notebook notebooks/co2_emissions_analysis.ipynb

📊 Example Visualizations

📈 Line chart of global CO₂ emissions over time.

🔥 Heatmap of emissions by country and year.

🌍 Bar chart comparing 1990 vs. 2020 emissions for the top 10 emitters.

👥 Per capita emissions distribution.

🌱 Insights from the Analysis

Global CO₂ emissions have increased sharply since the industrial revolution.

The top 5 countries account for more than 50% of emissions.

Coal remains a major contributor, though renewable energy is rising.

Per capita analysis reveals huge disparities between developed and developing countries.

📌 Future Work

Add forecasting models (ARIMA, Prophet) for emission predictions.

Explore renewable energy adoption trends vs. CO₂ reduction.

Perform regional clustering of countries by emission patterns.

🤝 Contributing

Contributions are welcome! Feel free to fork this repository, open issues, or submit pull requests.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
