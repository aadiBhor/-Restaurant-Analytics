# -Restaurant-Analytics
Cognifyz Data Analysis internship project: restaurant dataset par Level 1–3 notebooks (top cuisines, city analysis, price range, online delivery; cuisine combos, geo mapping, chains; reviews keywords, votes correlation, price vs services) with visualizations and insights. Notebooks reproducible; PDF brief included.

# Cognifyz Data Analysis – Restaurant Analytics

Ye repo Cognifyz Data Analysis internship ke Level 1–3 tasks ke notebooks aur report ko organize karta hai. Isme exploratory analysis, visualization aur insights cover kiye gaye hain.

## Repository structure
- docs/
  - Data-Analysis.pdf — Internship brief aur task list.
- notebooks/
  - Level_1_Task.ipynb — Top cuisines, city analysis, price range, online delivery comparison.
  - Level_2_Task.ipynb — Cuisine combinations, geographic mapping, restaurant chains analysis.
  - Level_3_Task.ipynb — Reviews keywords, review length vs rating, votes correlation, price vs services.
- README.md — Overview, setup, run aur results.
- .gitignore — Jupyter checkpoints, cache, OS files ignore.

## Environment
- Python 3.9+ recommended
- Install:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk
  - folium

Quick setup:
- Windows:
  - python -m venv .venv
  - .venv\Scripts\activate
- macOS/Linux:
  - python -m venv .venv
  - source .venv/bin/activate
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
- notebooks/ me Jupyter ya VS Code se notebook open karke cells sequentially run karein.
- Agar notebook me CleanedDataset.csv ka path use ho raha ho, to file ko same folder me rakhein ya cell me path update karein.
- Charts/outputs notebooks me render ho jayenge.

## Highlights

### Level 1
- Top cuisines distribution; North Indian sabse common; Chinese/Fast Food comparatively kam share.
- City analysis: New Delhi me max restaurants; city-wise average ratings compute.
- Price range distribution: Histogram/bar + percentage split.
- Online delivery: Delivery vs non-delivery ratings compare.

### Level 2
- Cuisine combinations: Frequent pairs/combos identify; rating lift check.
- Geographic analysis: Lat/Long par KDE + scatter; popular zones me clustering.
- Restaurant chains: Branch count, average rating, total votes; top chains by rating/votes charts.

### Level 3
- Reviews: Positive/negative keywords; review length vs rating relation.
- Votes: Highest/lowest votes; rating correlation.
- Price vs services: Higher price ranges vs online delivery/table booking relationship.

## Using this repo
- Clone:
  - git clone <repo-url>
  - cd cognifyz-data-analysis
- Env setup (upar diya) and run notebooks.
- Issues/PRs welcome.

## License
- Internship demonstration purpose; reuse se pehle org policies check karein.

## Acknowledgments
- docs/Data-Analysis.pdf (internship brief/tasks)

