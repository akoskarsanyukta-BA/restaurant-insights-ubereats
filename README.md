# 🍽️ Restaurant Insights Dashboard — Uber Eats
### Global Multi-Continent Restaurant Analysis using Power BI

| | |
|---|---|
| **Prepared By** | Sanyukta Akoskar |
| **Tools Used** | Power BI · Power Query · Excel |
| **Dataset** | Uber Eats Global Restaurant Data (6 Continents) |
| **Status** | ✅ Completed |

---

## 📌 Business Problem
Uber Eats operates across multiple continents with thousands of restaurant 
partners globally. Without a unified view of restaurant performance, ratings, 
pricing, and service availability — management lacks the visibility needed 
to make data-driven decisions about market expansion, partner support, 
and regional strategy.

**The goal:** Build a consolidated, interactive Power BI dashboard that gives 
Uber Eats management a single-screen view of global restaurant operations — 
from global overview down to city level.

---

## 🎯 Project Objectives
- Import and merge restaurant data from 8 Excel files across 6 continents
- Build an interactive multi-page Power BI dashboard
- Enable drill-down from global → continent → city level analysis
- Analyze ratings, costs, cuisine types, and service availability by region
- Deliver actionable insights for market strategy and partner management

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation, visualizations, interactive filtering |
| Power Query Editor | Data import, merging 8 Excel files, data transformation |
| Excel | Source data (8 continent/KPI files) |
| Left Outer Join (Merge Queries) | Combining continent tables with KPI fact table via Restaurant ID |

---

## 📁 Project Structure
├── 📂 powerbi     → Dashboard screenshots (all pages)
└── 📂 docs        → Project report (PDF)

---

## 📊 Dashboard Pages & Key Findings

### 🌍 Global Overview
- Interactive world map showing restaurant presence across all 6 continents
- Bubble size represents restaurant concentration per region
- Single-screen view of global Uber Eats operations for management

### 🌍 Africa Dashboard
| Metric | Value |
|---|---|
| Highest Avg Customer Rating | 4.90 |
| Lowest Avg Cost | 110 |
| Restaurants without Table Booking | 96.67% |
| Top Rating Category | "Very Good" (35 restaurants) |
| Key Cities | Cape Town, Johannesburg, Pretoria |

### 🌏 Asia Dashboard
| Metric | Value |
|---|---|
| Highest Avg Customer Rating | 4.90 |
| Total Restaurants in Asia | 8,849 |
| Restaurants without Table Booking | 87.07% |
| Top Cuisine | North Indian (936 restaurants) |
| Most Common Rating | "Average" (3,700 restaurants) |
| Dominant City | New Delhi (~6,000 restaurants) |

### 🏙️ City-Level Analysis
| Continent | Leading Cities |
|---|---|
| Africa | Cape Town & Pretoria (20 each) |
| Europe | Birmingham, Edinburgh, London, Manchester (20 each) |
| Asia | New Delhi dominates (~6,000 restaurants) |
| NAM | Equal distribution across most cities (20 each) |

---

## 💡 Key Business Insights

- **Asia dominates** with 8,849 restaurants — largest market by volume
- **New Delhi alone** accounts for a disproportionate share of Asian restaurants — indicating a concentration risk and expansion opportunity in other Asian cities
- **Table booking is underutilized globally** — 87–97% of restaurants across continents don't offer it — a potential feature adoption opportunity for Uber Eats
- **Ratings are consistently high** across continents (top ratings of 4.90) — indicating strong partner quality globally
- **Africa and Europe show equal city distribution** — suggesting balanced market penetration vs Asia's concentration in one city

---

## 🔧 Technical Highlights
- Merged 8 Excel files using **Power Query Left Outer Join** on Restaurant ID
- Built **continent-specific pages** with consistent KPI cards, map visuals, donut charts, and bar charts
- Added **Cuisine and City slicers** for interactive filtering on each page
- Created a **dedicated city-level page** with bar charts per continent for granular analysis

---

## 📄 Documents
- [Project Report](docs/)
- [Dashboard Screenshots](powerbi/)

---

## 👩‍💼 About the Analyst
**Sanyukta Akoskar** — Business Analyst  
Transitioning from 4+ years in B2B SaaS sales into data-driven BA roles.  
[LinkedIn](https://www.linkedin.com/in/sanyuktaakoskar/) | [Portfolio](/)
