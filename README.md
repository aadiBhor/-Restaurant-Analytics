# -Restaurant-Analytics
Cognifyz Data Analysis internship project: restaurant dataset par Level 1–3 notebooks (top cuisines, city analysis, price range, online delivery; cuisine combos, geo mapping, chains; reviews keywords, votes correlation, price vs services) with visualizations and insights. Notebooks reproducible; PDF brief included.

# Cognifyz Data Analysis – Restaurant Analytics

This repository contains the deliverables for a multi-level restaurant analytics project completed during the Cognifyz Data Analysis internship, including exploratory analysis, visualization, and insights across Level 1–3 tasks.

## Repository structure
- docs/
  - Data-Analysis.pdf — Internship brief, task list, and submission notes.
- notebooks/
  - Level_1_Task.ipynb — Top cuisines, city analysis, price range distribution, online delivery impact.
  - Level_2_Task.ipynb — Cuisine combinations, geographic mapping, restaurant chains analysis.
  - Level_3_Task.ipynb — Review NLP, votes correlation, price vs. online delivery and table booking.
- README.md — Project overview, setup, and results.
- .gitignore — Jupyter and Python cache ignores.

## Environment
- Python 3.9+ recommended

### Recommended packages
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- nltk or spacy (optional)
- folium or geopandas (optional for maps)

### Create a virtual environment and install
- macOS/Linux:
  - python -m venv .venv && source .venv/bin/activate
- Windows:
  - python -m venv .venv && .venv\Scripts\activate
- Install:
  - pip install pandas numpy matplotlib seaborn scikit-learn nltk folium

Optional requirements.txt:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- folium

## How to run
- Open notebooks in notebooks/ with Jupyter or VS Code.
- Ensure any referenced CSV (e.g., CleanedDataset.csv if required by a notebook cell) is placed in the same working directory or update the paths inside cells before running.
- Run all cells sequentially to reproduce charts and outputs.

## Highlights by level

### Level 1
- Top cuisines: A large share of restaurants serve North Indian; Chinese and Fast Food are present but smaller proportions.
- City analysis: New Delhi has the highest number of restaurants in the dataset.
- Price range: Distribution visualized; share per band estimated.
- Online delivery: Compared ratings with/without delivery.

### Level 2
- Cuisine combinations: Identified frequent pairs and triads; checked rating lift by combo.
- Geographic analysis: Kernel density + scatter shows clustering of all price ranges in popular zones.
- Restaurant chains: Built chain table with average rating, branch count, and total votes; top chains by rating and votes visualized.

### Level 3
- Reviews NLP: Most frequent positive keywords include “Very Good/Excellent”; negatives skew toward “Average/Poor/Not rated.”
- Review length vs rating: Found a clear negative correlation; longer reviews trend to lower ratings.
- Votes analysis: Identified highest/lowest votes; explored correlation with ratings.
- Price vs services: Analyzed if higher price ranges more often offer online delivery/table booking.

## Notes and assumptions
- The PDF in docs/ defines the scope and submission guidelines followed for this work.
- Some notebooks expect an input CSV (e.g., CleanedDataset.csv); please place it alongside the notebook or adjust paths.
- Visual outputs are reproducible by re-running notebooks with the same dataset version.

## License
This project is for internship demonstration purposes. Check organization policies before reuse.

## Contact
For questions or collaboration, open an issue on this repository.

## Optional: One-command setup files
If needed, a requirements.txt and minimal environment.yml can be generated from the notebooks to make setup one-command.
