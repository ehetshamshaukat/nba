# 🏀 NBA Player Stats Project (Day #1 — DataExpert.io Lab)

> A PostgreSQL-based analytics project using advanced SQL features (`STRUCT` and `ARRAY`) to model yearly NBA player stats. Based on the [DataExpert.io](https://dataexpert.io) Day #1 Lab by Zack Wilson, this project structures per-season player performance into nested arrays and enables cumulative, year-over-year analysis.

---

## 🎯 Objective

To model NBA player performance by season using PostgreSQL’s structured types and arrays. The goals include:

- Capturing **player stats per season** in an array of structured records.
- Building **cumulative year-over-year stats** per player.
- Using **custom logic** to classify players (e.g., `star`, `average`, `bench`).
- Applying **CTEs**, `Struct`, `Array`, and conditional aggregation in PostgreSQL.

---

## 🧰 Tech Stack

- **Database**: PostgreSQL
- **Concepts**: Custom Types, Arrays, Structs, CTEs, Aggregation, Joins

---

## 📊 Schema Overview

### 🧱 Step 1 — Custom Type: `player_stats`

```sql
CREATE TYPE player_stats AS (
    gp INT,
    pts FLOAT,
    reb FLOAT,
    ast FLOAT,
);
```
### 🧱 Step 2 — Create Table: `players`

```sql
CREATE Table player_stats AS (
  player_stats player_stats[]
  season
);
```
## 📁 Project Structure


## 📬 Contact

**Ehetasham Ul Haq**  
📧 [ehetsham.s@gmail.com](mailto:ehetsham.s@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ehetshamshaukat)
