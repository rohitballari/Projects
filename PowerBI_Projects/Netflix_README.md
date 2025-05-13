
# 📊 Netflix Content Analytics Dashboard

A data analytics project built in Power BI to explore and visualize Netflix content data, user reviews, and viewership trends. The goal is to extract actionable insights that support Netflix’s content strategy, audience targeting, and engagement optimization.

![Netflix Banner](./netfliximage.jpg)

---

## 🚀 Project Overview

This project integrates multiple datasets related to Netflix titles, user reviews, and viewership statistics. It builds interactive Power BI dashboards that allow exploration of content performance, viewer behavior, and sentiment trends.

**Key Objectives:**
- Analyze content popularity by genre, country, and time.
- Visualize audience engagement patterns (watch time, drop-off).
- Understand user sentiments through reviews.
- Enable dynamic filtering and drilldown in reports.

---

## 📂 File Structure

| File Name                                      | Description                                                                 |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| `Netflix_Dashboard_Project_Proposal.pdf`       | Project scope, methodology, and objectives                                 |
| `Netflix.pbix`                                 | Final Power BI dashboard file                                              |
| `netflix_titles.csv`                           | Metadata of Netflix content (title, genre, year, country)                  |
| `netflix_viewership.csv`                       | Viewership stats (user engagement, watch time)                             |
| `netflix_reviews.csv`                          | User reviews and ratings                                                   |
| `NetflixOriginals.csv`                         | Netflix Original shows and movies with associated metrics                  |
| `netflix-rotten-tomatoes-metacritic-imdb.csv` | External ratings data for benchmarking                                     |
| `BrandAssets_Logos_01-Wordmark.jpg`            | Netflix logo used for branding                                             |
| `netfliximage.jpg`                             | Hero image used in the dashboard and README                               |

---

## 🧠 Methodology

- **Data Cleaning & Integration:** Merge datasets using title/ID keys.
- **Sentiment Analysis:** Performed on user reviews using Python NLP libraries (e.g., TextBlob).
- **Metric Derivation:** Average watch time, sentiment scores, genre breakdowns, and ratings.
- **Dashboard Design:** Power BI visuals with slicers for year, genre, country, and sentiment.

---

## 📊 Dashboard Features

- **Content Explorer:** Filter content by genre, year, and region.
- **Viewer Insights:** Engagement metrics with trend analysis and drop-off points.
- **Sentiment Visualization:** Pie and bar charts showing user sentiment distribution.
- **Top Performers:** Identify most-watched and best-rated shows and movies.

---

## 🛠️ Tools Used

- Power BI
- Python (Pandas, TextBlob/Vader for sentiment analysis)
- Excel (Data preview & cleaning)
- SQL (for potential querying)

---

## ⚠️ Challenges

- Inconsistent title naming across sources
- Sentiment analysis complexities due to informal or mixed-language text
- Creating intuitive visuals for non-technical audiences

---

## ✅ Outcomes

- A dynamic, interactive Power BI dashboard
- Actionable insights for content acquisition and marketing
- A replicable analytics pipeline for future updates

---

## 📸 Sample Dashboard Screenshots

(Add screenshots of the dashboard here if available)

---

## 📬 Contact

For queries or contributions, please open an issue or contact the repository owner.
