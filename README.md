# Formula 1 Strategy & Performance Audit (SQL Capstone)

## 🏎️ Project Overview
This project serves as a data-driven retrospective analyzing over 70 years of Formula 1 history for **Apex Racing Analytics**. The objective was to ingest historical database tables, execute data hygiene audits, and answer critical business questions regarding driver performance, constructor competitiveness, and pit stop efficiency using relational SQL.

## 📊 Dataset Architecture
The relational database consists of 5 primary tables:
* **`drivers`**: Master catalog of all F1 drivers (`driverId` PK).
* **`constructors`**: Master catalog of racing teams (`constructorId` PK).
* **`races`**: Grand Prix events across seasons (`raceId` PK).
* **`results`**: Fact table containing driver finishing data per race (`resultId` PK, foreign keys to drivers, races, and constructors).
* **`pit_stops`**: Granular timing data for race pit stops starting from 2011.

## 🔍 Key Analytical Tasks Covered
1. **Data Hygiene & Inspection**: Row-count verification and missing value audits.
2. **All-Time Driver Victory Leaderboard**: Top 10 drivers ranked by total Grand Prix wins.
3. **Single-Season Team Standings (2023)**: Constructor competitiveness evaluated via total points scored.
4. **The "Comeback Kings"**: Extraordinary race wins starting from grid position 10 or lower.
5. **Modern Pit Crew Efficiency Audit**: Constructor ranking by average pit stop duration (2021+).
6. **"Best of the Rest"**: Identifying consistently strong drivers (5+ podiums) who never secured a Grand Prix win.

## 📝 Executive Summary
*Add your 3–4 sentence business takeaway here answering which team or driver performance trend was most surprising and why.*