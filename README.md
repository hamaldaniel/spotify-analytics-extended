# spotify-analytics-extended
Extended Spotify Data Analysis project using SQL + PostgreSQL, ETL pipelines, and Spotify API. Includes ready-made SQL queries (Wrapped-style insights), a Streamlit dashboard, and Docker Compose for easy setup. Designed to enrich Spotify Takeout history with live metadata &amp; audio features, and visualize listening patterns over time.

## Features
- PostgreSQL schema with constraints & indexes
- ETL pipeline
- Import Spotify Takeout history (JSON/CSV) → DB
- Fetch track/artist/album metadata + audio features via Spotify API
- Ready‑made analysis SQL (Wrapped‑style)
- Streamlit app for quick insights
- Docker Compose for Postgres + pgAdmin
- GitHub Actions CI for linting & seed‑data checks


## Quickstart


### 1) Clone & configure
git clone https://github.com/<your-username>/spotify-analytics-extended.git
cd spotify-analytics-extended

