🧪 Soil Health Nutrient Analysis



This project automates the scraping, consolidation, and analysis of macro and micro-nutrient soil data from India's Soil Health Portal. It helps identify regional soil deficiencies and trends across multiple years.

📁 Project Structure
soil-nutrient-analysis/
├── data/
│   ├── raw/          # Raw scraped data (organized by year/state/district/block)
│   └── processed/    # Final consolidated dataset
├── get_raw_data.py   # Web scraper for soil nutrient tables
├── consolidate_data.py # Merges macro & micro CSVs into one cleaned dataset
├── eda_analysis.ipynb # Exploratory Data Analysis & Visualizations
├── requirements.txt  # All Python dependencies
├── README.md         # You're reading it!
└── .gitignore

⚙️ Setup Instructions
1.Clone the repository
git clone https://github.com/yourusername/soil-nutrient-analysis.git
cd soil-nutrient-analysis

2.Install dependencies
pip install -r requirements.txt

3.Run the data scraper
python get_raw_data.py

4.Consolidate the data
python consolidate_data.py

5.Open the analysis notebook
jupyter notebook eda_analysis.ipynb

📊 Key Insights in the EDA Notebook

📉 State-wise nutrient deficiencies (N, P, K, Zn, Fe, etc.)
🧭 Year-wise nutrient trends (e.g., decline in Nitrogen)
🔁 Correlation between macro and micro-nutrients
🔥 Heatmaps and distribution plots by region
📍 Top nutrient-deficient villages
