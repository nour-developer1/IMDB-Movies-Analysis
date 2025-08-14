# 🎬 IMDB Movies Analysis

This Power BI project delivers an analytics dashboard built from IMDB movie data. It highlights trends in ratings, genres, release years, and box-office performance to support data-driven insights and comparative evaluation.

---

## 🚀 Key Features

- **Ratings Intelligence:** Distribution, averages, and top-rated titles with dynamic ranking.
- **Genre Trends:** Popularity over time and cross-filtering across multiple genres.
- **Release Year Insights:** Year-over-year patterns, cohorts, and lifecycle views.
- **Box Office Performance:** Revenue comparisons, top earners, and profitability proxies.
- **Interactive Slicers:** Filter by year, genre, rating range, runtime, and language.
- **Clean UX:** Focused visuals and KPIs for quick interpretation.

---

## 📁 Repository Contents

- `IMDB virsion1.pbix` – Power BI report (data model + visuals)
- `README.md` – You’re here

> If your PBIX exceeds 100 MB, enable Git LFS and track `*.pbix`.

---

## 🧰 Requirements

- **Power BI Desktop** (latest)
- IMDB dataset embedded in the PBIX (or configure your own source via Power Query parameters)

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open `IMDB virsion1.pbix` in **Power BI Desktop**.
3. Explore the report using the slicers and page navigation.
4. (Optional) Connect to your own IMDB-like source and refresh:
   - Open **Transform Data** → **Data source settings** → update credentials/parameters.
   - Apply and **Close & Apply**.

---

## 🗃️ Data Notes

- The PBIX contains the model and transformations (Power Query + DAX).
- Refresh behavior depends on your configured source; for static demos, use the embedded data snapshot.

---

## 🔧 Technical Highlights (Power BI)

- Star-schema modeling with surrogate keys where applicable.
- Measure layer for KPIs (ratings, counts, revenue comparisons).
- Drillthrough pages for title-level diagnostics.
- Consistent theming and tooltip pages for context.



## 🙋‍♀️ Contact

For feedback or collaboration, open an issue or reach out via GitHub.
