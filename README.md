# **boardroom-business-intelligence-dashboard**

Most dashboards show revenue.

Very few explain what is actually happening to profit.

This project was built as a Boardroom Command Center to help leadership understand:

where profit is being made
where margin is leaking
what decisions need attention
This is not just a dashboard — it is a decision support system.

----------------------------------------------------------------------------------------------------------

🚨** Business Problem**
Most dashboards focus heavily on revenue reporting, but fail to answer critical business questions:

Where is profit actually being generated?
What is causing margin leakage?
Are promotions truly effective or reducing profitability?
Which products, regions, and channels are driving risk?
How do returns impact overall business performance?
Leadership needs decision-ready insights, not just data visualization.

----------------------------------------------------------------------------------------------------------

🎯 Objective
To build a Boardroom Command Center that:

Translates raw data into actionable business insights
Provides end-to-end visibility from revenue → profit → risk
Enables leadership to quickly identify performance drivers and issues
Supports data-driven decision making

------------------------------------------------------------------------------------------------------------

🧠 Solution Approach
This dashboard was designed with a business-first mindset, focusing on:

KPI standardization and metric definition
Logical flow of financial and operational insights
Executive-friendly layout and storytelling
Identification of profit leakage and inefficiencies

-------------------------------------------------------------------------------------------------------------

📊 Dashboard Structure
1. Executive Command Center
High-level KPIs (Revenue, Profit, Margin, Orders, AOV)
Revenue trend with YoY and MoM comparison
Category and regional performance overview

<img width="1308" height="735" alt="image" src="https://github.com/user-attachments/assets/ceaac4e7-446b-4656-b126-31e35c9873ea" />


-------------------------------------------------------------------------------------------------------------
2. Profitability Deep Dive
Profit flow breakdown:

Revenue → Gross Profit → Profit After Freight → Adjusted Profit
Cost, freight, and return impact analysis

Identification of margin leakage

<img width="1292" height="707" alt="image" src="https://github.com/user-attachments/assets/c67308fc-dfdc-43d4-ba03-3814e6dbd85e" />

--------------------------------------------------------------------------------------------------------------

3. Product & Pricing Intelligence
Category-wise and product-level performance

Margin analysis across product hierarchy

Identification of:

- Top profit drivers
- Low-margin products
- Discount impact on profitability

<img width="1306" height="698" alt="image" src="https://github.com/user-attachments/assets/b31e2b54-d6f8-4a41-8793-f15439ec78cf" />

--------------------------------------------------------------------------------------------------------------

4. Customer & Channel Insights
- Revenue and profit by channel (Online, Retail, Enterprise, Partner)
- Customer segmentation (New vs Returning vs VIP)
- AOV and margin comparison across channels

<img width="1283" height="725" alt="image" src="https://github.com/user-attachments/assets/9b57867c-1d44-4fb2-9f44-b349dd2b806f" />

----------------------------------------------------------------------------------------------------------------

5. Promotion Effectiveness
- Promo vs Non-Promo performance comparison
- Promotion type profitability (B2B, Campaign, Seasonal, etc.)
- Campaign-level profit analysis
- Discount vs profit efficiency insights

<img width="1281" height="700" alt="image" src="https://github.com/user-attachments/assets/c215b372-b568-477a-a9b1-62d178646ab1" />

---------------------------------------------------------------------------------------------------------------

## 💡 Key Insights

- Revenue is strong across the board, but **profitability varies sharply by category** — top-line health hides bottom-line risk.
- Promotions generate revenue comparable to non-promotional sales but at materially lower profit — a sign of **promotional inefficiency**.
- **Returns are a primary driver of profit erosion**, concentrated in specific categories.
- Several products are revenue contributors but **low-margin**, masking weak unit economics.
- Discount-heavy categories consistently show **reduced profit efficiency**.

> **The underlying takeaway: growth without margin discipline is a profit problem disguised as a sales win.**

---

## 🚀 Business Impact

The dashboard equips leadership to:

- Identify **profit leakage drivers** across discounts, returns, and freight
- Evaluate **promotion effectiveness** against actual profit contribution, not just revenue
- Pinpoint **high-risk categories and regions** before they compound
- Inform **product mix and pricing decisions** with margin-grounded evidence
- Shift the operating focus from top-line growth to **sustainable profitability**

**Outcomes the report supports:** sharper strategic decisions, tighter margin control, and an executive view grounded in data rather than intuition.

---

## 🛠️ Technical Foundation

- **Data modeling** aligned to business logic — star schema, single-direction relationships, marked date table
- **DAX measures** for KPI calculations including YoY and MoM time intelligence, staged profit flow, and margin ratios
- **Interactive filtering** with cross-page synced slicers for fluid scenario reading
- **Executive-grade layout** designed for boardroom consumption — clean hierarchy, conditional formatting, drillthrough

---

## 📁 Data

Synthetic dataset created for demonstration. The data is modeled to mirror real-world commerce dynamics across:

- Sales and order activity
- Profit and cost components
- Discounts and promotional behavior
- Returns and return reasons
- Channel and customer segmentation

---

## ▶️ How to Use

- Use the **Year, Month, and Category** slicers to explore trends — they're synced across all pages
- Navigate the six pages using the **left-side navigation rail**
- **Hover over visuals** for additional detail in tooltips
- **Right-click** on products or categories to drill through where enabled

---

## ⚠️ Disclaimer

This dashboard uses **synthetic data created for demonstration purposes**. The data model, DAX, and design choices reflect production-style analytics work.




