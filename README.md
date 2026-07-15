# DAV 5400 - Analytical Programming (Python)

Coursework and projects for **DAV 5400** (M.S. Data Analytics & Visualization, Yeshiva University). Python fundamentals → pandas → web data → end-to-end analytical projects.

> 🌟 **The strongest projects from this course have been polished into their own standalone, recruiter-ready repositories** (cleaned, executable, with READMEs, results, and figures):
>
> | Polished standalone repo | What it is |
> |---|---|
> | **[climate-change-analysis-python](https://github.com/Nikkat-Afrin/climate-change-analysis-python)** | Final project - CO₂ / temperature / sea-level / disaster multi-dataset study |
> | **[customer-purchase-prediction](https://github.com/Nikkat-Afrin/customer-purchase-prediction)** | Project 4 - scikit-learn purchase prediction (RF ROC-AUC ≈ 0.98) |
> | **[hdi-global-policy-analysis](https://github.com/Nikkat-Afrin/hdi-global-policy-analysis)** | Project 1 - Human Development Index analysis + policy insights (R² ≈ 0.98) |
> | **[airline-survey-analysis](https://github.com/Nikkat-Afrin/airline-survey-analysis)** | Project 3 - air-travel behavioral survey analysis |

## 📚 Coursework in this repo
| Module | Topic |
|---|---|
| M1-M2 | Python basics, files, lists & comprehensions |
| M3 | NumPy |
| M4 | pandas |
| M7 | Regular expressions |
| M9 (Project 2) | HTML, JSON, web scraping & web APIs |
| M10 | Data reshaping (melt/pivot) |
| Project 1 / 3 / 4 / Final | see standalone repos above |

The module notebooks live in [`notebooks/`](notebooks). This repo also hosts some of the raw datasets loaded by the course notebooks via `raw.githubusercontent.com` URLs.

## ⚠️ Security note
The Module 9 / Project 2 web-scraping notebook (`notebooks/Fnu_NikkatAfrin_P2_Assn.ipynb`) originally contained a hard-coded `newsdata.io` API key. The key has been **removed from the notebook** in this repo (replaced with a `YOUR_NEWSDATA_KEY` placeholder - set your own key, e.g. via `os.environ["NEWSDATA_KEY"]`). Since the old key was previously exposed, it should still be **rotated** at newsdata.io.

## 🛠️ Tech stack
`Python` · `pandas` · `NumPy` · `BeautifulSoup` · `requests` · `Matplotlib` · `Seaborn`
