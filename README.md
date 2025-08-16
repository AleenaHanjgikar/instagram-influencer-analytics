<img width="964" height="558" alt="Overview" src="https://github.com/user-attachments/assets/d1673077-5225-4437-8a62-649c43f9e3fb" /># instagram-influencer-analytics
Power BI project analyzing Top Instagram Influencers — followers, likes, engagement (60-day), and country insights. Includes .pbix dashboard, cleaned CSV, SQL queries, and project brief. Columns: rank, channel_info, influence_score, posts, followers, avg_likes, 60_day_eng_rate, new_post_avg_like, total_likes, country.

# Instagram Influencer Analytics Dashboard

📊 Power BI project analyzing **Top Instagram Influencers** — followers, average likes, engagement (60-day), and country distribution.  
This repo contains the Power BI dashboard, cleaned dataset, SQL queries, documentation, and screenshots.

---

## 🔹 Project Files
- **`top_insta_dashboard.pbix`** → Interactive Power BI Dashboard  
- **`top_insta_influencers_cleaned.csv`** → Cleaned dataset used in the dashboard  
- **`SQL Queries.sql`** → SQL queries for data analysis & aggregation  
- **`Top Instagram Influencers Dashboard.pdf`** → Project documentation (business analysis brief)  
- **`screenshots/`** → Key dashboard visuals in PNG format  

---

## 🔹 Overview
The dashboard provides insights into Instagram’s top influencers using:  
- Followers count  
- Average likes per post  
- 60-day engagement rate  
- Country-wise influencer distribution  
- Ranking by influence score  

👉 This enables brands/analysts to **identify high-impact influencers** for marketing strategies.

---

## 🔹 Data Dictionary
| Column                | Type   | Description                                |
|------------------------|--------|--------------------------------------------|
| `rank`                | int    | Global rank by influence score             |
| `channel_info`        | text   | Influencer username / handle               |
| `followers`           | int    | Number of followers                        |
| `avg_likes`           | int    | Average likes per post                     |
| `60_day_eng_rate`     | float  | Engagement rate across last 60 days        |
| `new_post_avg_like`   | int    | Avg. likes on most recent posts            |
| `total_likes`         | bigint | Total likes received across posts          |
| `country`             | text   | Influencer’s country                       |

---

## 🔹 SQL Query Highlights
- Create table schema for influencers  
- Query top 10 influencers by engagement rate  
- Country distribution of influencers  
- Ranking by followers vs engagement  

---

## 🔹 How to Use
1. Download the `.pbix` file and open in **Power BI Desktop**.  
2. Use the **CSV file** as dataset (already cleaned).  
3. Run `SQL Queries.sql` in MySQL (or any RDBMS) for reproducible queries.  
4. Explore dashboard filters for **Country** and **Engagement Rate buckets**.  

---

## 🔹 Screenshots
 
OVERVIEW:
<img width="964" height="558" alt="Overview" src="https://github.com/user-attachments/assets/8142c81f-8fe3-49af-b436-d27e6597c871" />

COUNTRY INSIGHTS:
<img width="964" height="558" alt="Country Insights" src="https://github.com/user-attachments/assets/19eb8b2c-8a2e-4f90-b453-dd2684ae41a3" />

TOP INFLUENCER-1:
<img width="964" height="559" alt="Top Influencer-1" src="https://github.com/user-attachments/assets/fb8beb5c-9213-4627-bb78-64ae801e214d" />

TOP INFLUENCER-2:
<img width="965" height="558" alt="Top Influencer-2" src="https://github.com/user-attachments/assets/5a4dd23e-bfc9-45fd-889a-3eb2ed2ec3bd" />

GEO INSIGHTS
<img width="965" height="561" alt="Geo Insights" src="https://github.com/user-attachments/assets/f9333a5c-9e9d-4539-addd-363ac10e5801" />

---

## 🔹 Tech Stack
- Power BI (Data Visualization)  
- SQL (Queries & Aggregations)  
- Excel/CSV (Data Cleaning)  

---

## 🔹 License
This project is licensed under the **MIT License** – feel free to use and adapt.  

---

## 🔹 Author
👩‍💻 **Aleena Hanjgikar**  
🔗 [LinkedIn](https://www.linkedin.com/in/aleena-hanjgikar-89a723251/)  
📧 aleenahanjgikar@gmail.com  

---
