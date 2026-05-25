# Tutoring Platform Insights

A data project comparing customer reviews across three UK tutoring platforms — Tutorful, MyTutor and Superprof — using data scraped from Trustpilot.

---

## What this project covers

- Scraping reviews from Trustpilot for three tutoring companies
- Cleaning and combining the data into one dataset
- Exploring ratings and review patterns across platforms
- Sentiment analysis using TextBlob and VADER
- Keyword extraction to find common themes per company
- A model to predict star rating from review text
- A Powr BI dashboard comparing all three platforms

---

## Project Structure

```
tutoring-platform-insights/
├── notebooks/
│   ├── 01_scraping.ipynb
│   ├── 02_data_wrangling.ipynb
│   ├── 03_EDA.ipynb
│   ├── 04_sentiment.ipynb
│   ├── 05_keywords.ipynb
│   └── 06_modelling.ipynb
├── data/                  # not tracked in git
├── .gitignore
└── README.md
```

---

## Tools Used

| Tool | What it was used for |
|---|---|
| Python | Main analysis language |
| Requests / BeautifulSoup | Web scraping |
| Pandas | Data cleaning and analysis |
| Matplotlib / Seaborn | Charts and graphs |
| TextBlob | Sentiment analysis |
| VADER | Sentiment analysis |
| Scikit-learn | Star rating prediction model |
| Power BI | Interactive dashboard |

---

## Data Source

Reviews scraped from [Trustpilot](https://www.trustpilot.com) for:
- [Tutorful](https://www.trustpilot.com/review/tutorful.co.uk)
- [MyTutor](https://www.trustpilot.com/review/www.mytutor.co.uk)
- [Superprof](https://www.trustpilot.com/review/www.superprof.co.uk)

---

## Key Findings

*(to be updated once analysis is complete)*

---

## License

MIT
