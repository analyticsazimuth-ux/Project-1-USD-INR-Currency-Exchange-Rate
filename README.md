# Project-1-USD-INR-Currency-Exchange-Rate
A Statistical Study of USD/INR Currency Exchange Rate to understand it's behavior.

## Scope of the study
To Understand the USD/INR exchange rate through statistical application.

## Data Source Used
RBI Daily interbank forex rates (USD vis-a-vis INR) Period:(08-08-2000 – 30-06-2026).
+ Source: Reserve Bank of India (RBI) https://dbie.rbihub.in/statistics?table=financial_markets.r691_daily_interbank_forex_rates_usd_vis_a_vis_inr

+ Dataset: Daily Interbank Forex Rates (USD vis-à-vis INR)

+ Period: 08 August 2000 – 30 June 2026

+ Frequency: Daily

+ Observations: 6,308

## Methodology
This study uses quantitative descriptive statistical methods to examine historical movements and volatility in
the USD/INR exchange rate. Pandas, Numpy, Matplotlib, Statsmodels, scipy, seaborn python libraries are used
for analysis and visualization.

## Finding

## Tree Structure of this folder:
```text
    ├── data
    │   └── data.xlsx
    ├── graphs
    │   ├── annual_stats.png
    │   ├── hist.png
    │   ├── historical_probability.png
    │   ├── percentage_change.png
    │   ├── rol_volatility.png
    │   └── timeseries.png
    ├── notebook
    │   └── analysis.ipynb
    ├── README.md
    ├── report
    │   ├── analysis.html
    │   └── analysis.pdf
    └── requirements.txt
```
## Installation and Setup

You will need Python 3.10 or later and Jupyter Notebook installed on your computer.

Step 1: Clone the repository
```
git clone YOUR_GITHUB_REPOSITORY_URL
```
Step 2: Navigate to the project directory
```
cd currency-data-statistics
```
Step 3: Create a virtual environment
```
python -m venv venv
```
Activate the environment:

Linux / macOS
```
source venv/bin/activate
```
Windows
```
venv\Scripts\activate
```
Step 4: Install dependencies
```
pip install -r requirements.txt
```
Step 5: Launch Jupyter Notebook
```
jupyter notebook
```
Open the notebook located inside the notebooks directory.

## Running the Analysis

Follow these instructions to reproduce the analysis:

+ Clone or download the repository.

+ Install the required Python libraries.

+ Ensure the original dataset is available inside the data directory.

+ Open the Jupyter Notebook.

Execute the notebook cells sequentially, starting from the first cell.

Review the statistical outputs, tables and visualisations generated throughout the notebook.

Important: The notebook uses relative file paths. Run it from the repository structure described above, or update the dataset path if you change the folder arrangement.
