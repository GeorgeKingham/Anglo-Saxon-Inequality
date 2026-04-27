# The Anglo-Saxon Exception: Inequality Across Developed Economies

## Overview
This project investigates income inequality trends across nine developed economies from 1980 to 2023, examining whether English-speaking (Anglo-Saxon) economies follow a different inequality trajectory compared to Continental European and Nordic peers.

## Blog Post
The full blog post can be viewed in: notebooks/Blog.ipynb

## Project Structure
- data/raw/ — Original downloaded datasets
- data/processed/ — Cleaned data produced by scripts
- notebooks/Blog.ipynb — Main blog post with analysis
- output/figures/ — All charts and visualisations

## Data Sources
- OECD Income Distribution Database: https://stats.oecd.org/Index.aspx?DataSetCode=IDD
- World Bank Development Indicators: https://data.worldbank.org/

## How to Replicate
1. Clone the repository: git clone https://github.com/GeorgeKingham/Anglo-Saxon-Inequality.git
2. Create virtual environment: python3 -m venv venv
3. Activate it: source venv/bin/activate
4. Install packages: pip install jupyter pandas matplotlib plotly statsmodels requests wbdata numpy
5. Launch Jupyter: jupyter notebook
6. Open notebooks/Blog.ipynb and select Kernel > Restart & Run All

## Requirements
- Python 3.12+

## Key Findings
- Anglo-Saxon economies have consistently higher income inequality than Continental/Nordic peers across 1980-2023
- The inequality gap has persisted at approximately 0.07 Gini points for four decades but has not widened significantly
- OLS regression confirms Anglo-Saxon economies carry an inequality premium of 0.063 Gini points even after controlling for GDP, trade openness, government spending and unemployment
- Nordic inequality has risen since the 1990s, suggesting broader pressures on all developed economies

## Author
George Kingham
BEE2041 Data Science in Economics
University of Exeter, 2026
