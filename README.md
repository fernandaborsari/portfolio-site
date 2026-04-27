# Portfolio — Fernanda Borsari Miguel

Personal portfolio website built with HTML and Tailwind CSS.

## Data Sources

The projects featured on this site use publicly available data. The raw files are **not included** in this repository — download them directly from the sources below.

---

### NTX Real Estate Market Analysis

| Source | File to download | Link |
|---|---|---|
| Redfin Market Tracker | `zip_code_market_tracker.tsv` | [redfin.com/news/data-center](https://www.redfin.com/news/data-center/) |
| Zillow ZHVI — All Homes | `Zip_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv` | [zillow.com/research/data](https://www.zillow.com/research/data/) |
| Zillow ZHVI — By Bedroom | `Zip_zhvi_bdrmcnt_[1-5]_uc_sfrcondo_*.csv` | [zillow.com/research/data](https://www.zillow.com/research/data/) |

After downloading, place the files in `NTX_REAL_ESTATE_ANALYSIS/pipeline/data/raw/` and run `pipeline/main.py` to regenerate the processed data.

---

### Academic Stress — ETL Pipeline

| Source | Link |
|---|---|
| Kaggle — Student Stress Factors dataset | [kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis](https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis) |

---

## Tech Stack

- HTML5 · Tailwind CSS (CDN)
- Google Fonts — Inter
- No build step required — open `index.html` directly in the browser
