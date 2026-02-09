# Walmart Sales Performance Dashboard (Power BI)

##  Project Overview
This project is an end-to-end **Business Intelligence and Business Analysis dashboard** built using **Power BI** to analyze Walmart’s sales performance.  
The dashboard is designed for **executive leadership and sales managers** to track KPIs, monitor target achievement, and evaluate salesperson performance across regions.

The solution follows **business analysis best practices**, including data modeling, KPI definition, stakeholder-focused visuals, and consistent UI/UX design.

---

##  Business Objectives
- Track overall sales performance using executive KPIs
- Compare **actual sales vs sales targets**
- Identify **top and underperforming salespersons**
- Analyze regional sales contribution
- Enable quick decision-making using interactive filters

---

##  Dashboard Pages

### 1️⃣ Home (Executive Overview)
Provides a high-level snapshot of business performance:
- Total Sales
- Total Orders
- Quantity Sold
- Target Achievement %
- Average Customer Rating
- Sales by Region
- Sales by Product Category
- Sales Trend by Month
- Sales by City (Map)

**Purpose:** Executive-level monitoring and trend analysis.

---

### 2️⃣ Performance (Target vs Actual)
Focuses on performance management:
- Top 5 Salespersons by Sales
- Bottom 5 Salespersons by Target Difference
- Sales vs Target comparison by Region
- Salesperson performance summary table with conditional formatting

**Purpose:** Identify performance gaps and opportunities.

---

### 3️⃣ Salesperson Deep-Dive
Analyzes individual salesperson performance:
- Regional sales comparison using **Small Multiples**
- Salesperson-wise target achievement table
- Clear visibility into regional strengths and weaknesses

**Purpose:** Support sales managers in coaching and planning.

---

## 🧱 Data Model
- **Fact Table:** Sales
- **Dimension Tables:** Product Category, Salesperson, Supplier
- Clean **star schema** with one-to-many relationships
- Technical columns hidden to improve report usability

---

## 🧮 Key DAX Measures
- Total Sales
- Total Orders
- Total Quantity Sold
- Target Sales
- Target Achieved %
- Target Difference
- Average Rating

All calculations are created using **explicit DAX measures** to ensure accuracy and reusability.

---

## 🎨 Design & Formatting
- Custom color palette with consistent dark-blue branding
- Beige canvas for visual clarity
- Minimal gridlines and clean typography
- Role-based page design (Executive → Manager → Analyst)
- Interactive slicers synced across all pages

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX
- Power Query
- Data Modeling (Star Schema)
- Business Analysis & Visualization Best Practices

---

## 🚀 Key Skills Demonstrated
- Business requirement understanding
- KPI definition and performance tracking
- Data cleaning and transformation
- DAX-based calculations
- Dashboard UX/UI design
- Stakeholder-focused reporting

---

## 📎 How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use slicers to filter by region, product, or salesperson
4. Navigate pages using buttons

