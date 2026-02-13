# Blinkit-Sales-Analysis-Dashboard-

**Uncover hidden patterns in India's fastest-growing quick-commerce platform**

![Blinkit Dashboard Preview](https://via.placeholder.com/800x400.png?text=Blinkit+Power+BI+Dashboard+Preview)  
*(Replace with your actual screenshot link or embed)*

## 🌟 Project Spotlight
Transforming raw Blinkit sales data into **strategic intelligence** through an end-to-end Power BI solution.

This dashboard empowers stakeholders to:
- Track revenue drivers across product attributes & outlets
- Understand customer preferences (ratings & fat content trends)
- Optimize inventory and outlet strategies
- Spot growth opportunities in tiered markets

Built with clean data modeling, custom DAX, and thoughtful UX design.

## 🎯 Business Goal
Deliver a **single-pane-of-glass** view to answer critical questions:
- Which product attributes drive the highest revenue?
- How do outlet characteristics (size, tier, age, type) influence performance?
- Where are satisfaction and sales efficiency strongest/weakest?
- What actionable optimizations can boost profitability?

## 📊 Core KPIs at a Glance

| KPI                | Definition                              | DAX Formula Example                  |
|--------------------|-----------------------------------------|--------------------------------------|
| **Total Sales**    | Aggregate revenue from all transactions | `Total Sales = SUM(Sales[Sales Amount])` |
| **Avg. Sales**     | Revenue per transaction                 | `Average Sales = AVERAGE(Sales[Sales Amount])` |
| **Items Sold**     | Total quantity of items transacted      | `Number of Items = COUNT(Sales[Item Identifier])` |
| **Avg. Rating**    | Mean customer satisfaction score        | `Average Rating = AVERAGE(Sales[Rating])` |

## 📈 Dashboard Highlights – Key Visuals

1. **Fat Content Revenue Share**  
   *Donut Chart* → Reveals consumer preference for **Low Fat** vs **Regular** items

2. **Top-Performing Item Categories**  
   *Horizontal Bar Chart* → Highlights high-revenue product types (e.g., Household, Snacks)

3. **Outlet-wise Fat Content Breakdown**  
   *Stacked Column Chart* → Compares Low Fat vs Regular contribution by outlet

4. **Sales Trend by Outlet Establishment Year**  
   *Line + Area Chart* → Shows how outlet maturity impacts revenue growth

5. **Revenue by Outlet Size**  
   *Donut / Pie Chart* → Demonstrates efficiency of Medium vs Small vs High outlets

6. **Geographic Sales Distribution**  
   *Funnel / Map Visual* → Tier 1, Tier 2, Tier 3 contribution (often Tier 3 leads!)

7. **Outlet Type Comparison Matrix**  
   *Table / Cards* → Side-by-side view of all KPIs segmented by Grocery Store / Supermarket Type1/2/3

## 🛠 Technical Foundation

- **Power BI Desktop** – Core development environment
- **DAX Mastery** – Custom measures & time-intelligence (if extended)
- **Star Schema Modeling** – Fact (Sales) + Dimensions (Item, Outlet)
- **Power Query** – Data cleaning, null handling, type consistency, calculated columns
- **Interactive Features** – Slicers (Outlet Type, Tier, Fat Content, Item Type), cross-filtering, tooltips

## 💡 Business Insights (Update with Your Actual Findings)

- **Low Fat** products often dominate revenue — health-conscious buyers are driving sales
- **Tier 3** locations surprisingly outperform Tier 1 & 2 in total revenue
- **Medium-sized outlets** deliver the best revenue per square foot / efficiency
- Newer outlets show aggressive early growth — strong potential in expansion
- Certain categories (Household / Fruits) consistently achieve high volume + rating
- Opportunity: Increase visibility of high-rated low-fat items in underperforming tiers

## 🧰 Tools & Stack

- Power BI (Desktop + Service)
- Advanced DAX
- Power Query (M Language)
- Data Modeling & Relationship Management
- UI/UX Dashboard Design Principles

## 🚀 Next Steps / Potential Enhancements

- Add time-series forecasting
- Incorporate delivery time / order volume metrics
- Build mobile-optimized layout
- Integrate real-time data refresh
- Export to paginated reports for executives

Feel free to ⭐ the repo if this helped, fork it, or reach out with questions!

Made with 📊 & ❤️ 
Dhanalakshmi.S
