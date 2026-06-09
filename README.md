# DAV 5400 — Analytical Programming (Python)

Coursework and projects for **DAV 5400** (M.S. Data Analytics & Visualization, Yeshiva University). Python fundamentals → pandas → web data → end-to-end analytical projects.

> 🌟 **The strongest projects from this course have been polished into their own standalone, recruiter-ready repositories** (cleaned, executable, with READMEs, results, and figures):
>
> | Polished standalone repo | What it is |
> |---|---|
> | **[climate-change-analysis-python](https://github.com/Nikkat-Afrin/climate-change-analysis-python)** | Final project — CO₂ / temperature / sea-level / disaster multi-dataset study |
> | **[customer-purchase-prediction](https://github.com/Nikkat-Afrin/customer-purchase-prediction)** | Project 4 — scikit-learn purchase prediction (RF ROC-AUC ≈ 0.98) |
> | **[hdi-global-policy-analysis](https://github.com/Nikkat-Afrin/hdi-global-policy-analysis)** | Project 1 — Human Development Index analysis + policy insights (R² ≈ 0.98) |
> | **[airline-survey-analysis](https://github.com/Nikkat-Afrin/airline-survey-analysis)** | Project 3 — air-travel behavioral survey analysis |

## 📚 Coursework in this repo
| Module | Topic |
|---|---|
| M1–M2 | Python basics, files, lists & comprehensions |
| M3 | NumPy |
| M4 | pandas |
| M7 | Regular expressions |
| M9 (Project 2) | HTML, JSON, web scraping & web APIs |
| M10 | Data reshaping (melt/pivot) |
| Project 1 / 3 / 4 / Final | see standalone repos above |

This repo also hosts some of the raw datasets loaded by the course notebooks via `raw.githubusercontent.com` URLs.

## ⚠️ Security note (action required)
The Module 9 / Project 2 web-scraping notebook historically contained a **hard-coded `newsdata.io` API key**. If that notebook is in this repo's history:
1. **Rotate the key** at newsdata.io (assume it is compromised).
2. Replace it with an environment variable (`os.environ["NEWSDATA_KEY"]`).
3. Scrub it from git history if feasible (`git filter-repo`).

## 🛠️ Tech stack
`Python` · `pandas` · `NumPy` · `BeautifulSoup` · `requests` · `Matplotlib` · `Seaborn`
