# 🎬 Movie Rental Database Analysis

## 📌 Overview
SQL analytics project analyzing a movie rental database to extract customer behavior insights, movie performance metrics, and revenue optimization strategies.

**Business Context:** Data-driven decision analysis for a movie rental company's inventory, marketing, and customer retention strategies.

## 🛠️ Tech Stack
**Database:** SQL Server | **Skills:** Joins, Subqueries, CTEs, Window Functions, OLAP (CUBE/ROLLUP), Aggregations

## 📊 Database Schema
- `renting` - Rental transactions & ratings
- `customers` - Customer demographics
- `movies` - Movie catalog (genre, price)
- `actors` - Actor information
- `actsin` - Movies-Actors relationships

## 🔍 Key Analyses

### 1. Customer Analytics
**Questions Answered:**
- Which customers are highly engaged (7+ rentals)?
- Who are at-risk customers (< 5 rentals)?
- Which customers provide ratings vs. silent viewers?
- How many millennials are in our customer base?

## 💡 Business Insights

**Customer Behavior:**
- Power users (7+ rentals) are prime loyalty program candidates
- Low-engagement customers (< 5 rentals) need re-activation campaigns
- Not all customers rate movies - incentivize feedback

**Movie Performance:**
- Movies with 8+ avg rating = premium catalog
- Frequently rented titles (5+) drive consistent revenue
- Drama genre has exceptional performers (9+ ratings)

**Revenue & Market:**
- Geographic preferences vary significantly - localize content
- Top revenue movies should guide acquisition strategy
- Country-level KPIs reveal market maturity

**Content Strategy:**
- Genre preferences differ by demographics and geography
- Spanish market has distinct actor preferences
- Young international talent (born > 1990) represents growth opportunity

## 🎯 Recommendations

1. **Loyalty Program** - Reward customers with 7+ rentals
2. **Re-engagement Campaign** - Target < 5 rental customers
3. **Feedback Incentives** - Offer discounts for ratings
4. **Localized Marketing** - Tailor by country-genre preferences
5. **Premium Tier** - Bundle 8+ rated movies
6. **Inventory Priority** - Stock frequently rented titles
7. **Age-Based Targeting** - Use demographic insights for recommendations

## 📂 Project Structure
├── README.md
├── queries/
│ ├── customer_analytics.sql
│ ├── movie_performance.sql
│ ├── revenue_analysis.sql
│ ├── actor_preferences.sql
│ └── advanced_olap.sql
├── results/
│ └── screenshots/
└── schema/
└── database_schema.sql

## 🚀 How to Use

1. Clone repository: `git clone https://github.com/khaled-hasan-hasan/SQL-Data-Driven-Decision-Analysis.git`
2. Import database schema
3. Run queries in order by category
4. Review results and business insights

## 📚 Skills Demonstrated

**SQL Techniques:** Complex JOINs • Correlated Subqueries • CTEs • Aggregations • OLAP (CUBE/ROLLUP/GROUPING SETS) • Window Functions • Set Operations (INTERSECT) • EXISTS/IN Operators

**Business Analytics:** Customer Segmentation • KPI Tracking • Revenue Analysis • Geographic Analysis • Demographic Insights • Performance Evaluation

## 👨‍💻 About

**Khaled Hasan** - Data Analyst | ITI Power BI Developer Trainee

Specialized in SQL, Python, Power BI, and Business Intelligence. Transforming data into actionable insights.

**Skills:** SQL Server • Python • Power BI • Data Analysis • Business Intelligence

**Connect:** [LinkedIn](www.linkedin.com/in/khaled-hasan-abdo) • [GitHub](https://github.com/khaled-hasan-hasan) • [Email](khaled.habdo@gmail.com)

---

## 📝 License
MIT License

---

⭐ **Found this helpful? Give it a star!**

