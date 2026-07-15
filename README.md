# 🏆 Play Fly — Sports Analysis Dashboard

🎓 **Final / Advanced Capstone Project — Hadi E-Learning (Advanced Power BI Course)**

An interactive **Power BI** dashboard that analyzes and ranks sports leagues/networks (including **NBA** and **NHL**) based on audience reach across two key demographics: **13+** and **18+** viewers. The report combines high-level KPI summaries with a detailed, sortable ranking table for deep-dive sports analytics.

---

## 📊 Project Overview

This report answers questions like:
- Which sports networks/leagues reach the largest audience?
- How does a network rank within its genre/sub-genre and market?
- What is the average and total audience size (13+ vs 18+) across the board?

The dashboard is built as a **3-page interactive experience** designed for both quick executive overview and detailed analyst-level exploration.

---

## 🗂️ Report Pages

| Page | Purpose |
|------|---------|
| **Home** | Landing page with branded navigation buttons to jump directly into NBA, NHL, and other league views |
| **Leagues** | League-level summary — average rank KPI cards, audience totals, and a logo-based Chiclet Slicer for quick filtering |
| **Detail** | Full ranking table with per-network breakdown: 13+ / 18+ audience (millions), individual ranks, totals, and averages |

---

## ✨ Key Features

- 🔘 **Custom navigation buttons** for smooth page-to-page flow
- 🖼️ **Chiclet Slicer with network/league logos** for a visual, brand-friendly filtering experience
- 🎚️ **Advanced Slicer** for filtering by Genre / Sub-Genre
- 📇 **KPI Cards** showing Average Rank, Total & Average Audience (13+ and 18+)
- 📋 **Detailed ranking table** with sortable columns (Rank 13+, Rank 18+, All Rank)
- 🎨 Clean, dark-themed, brand-consistent design

---

## 🧩 Data Model

| Field | Description |
|-------|--------------|
| `Name` | Network / league name |
| `Logo` | Network/league logo (image URL) |
| `Genre` / `Sub-Genre` | Content classification (e.g., Sports → NBA, NHL, etc.) |
| `Market` | Broadcast/media market |
| `13+ millions` / `Rank 13+` | Audience size and rank for 13+ demographic |
| `18+ millions` / `Rank 18+` | Audience size and rank for 18+ demographic |
| `All` / `All Rank` | Combined audience figure and overall rank |
| `Average of Rank` | Aggregated ranking metric used across cards and slicers |

Data is imported from structured source tables and modeled for fast slicing and aggregation across pages.

---

## 🛠️ Tools & Technology
  **Microsoft Excel**: For Data Cleaning 
- **Power BI Desktop**
- **Power Query (M)** — data shaping and transformation
- **DAX** — measures for averages, totals, and rankings
- **Custom Visuals** — Chiclet Slicer, Advanced Slicer

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Play_fly_final_report.pbix` (Play Fly Sports Analysis Dashboard) in **Power BI Desktop**.
3. If connected to a live data source, click **Refresh** to pull the latest data.
4. Use the **Home** page buttons to navigate between league views.
5. Use the **Chiclet Slicer** and **Advanced Slicer** on each page to filter by league/genre.

---

## 📸 Screenshots

*(Add screenshots of the Home, Leagues, and Detail pages here for a stronger GitHub presentation — export them from Power BI via File → Export → Export to Image, or take screen captures.)*

```
/screenshots
  ├── home.png
  ├── leagues.png
  └── detail.png
```

---

## 📌 Project Status

✅ Completed — ready for review and demonstration.

---

## 👤 Author

Built with a focus on clean UX, brand-consistent visuals, and clear analytical storytelling in Power BI.

**Final Project — Hadi E-Learning (Advanced Power BI Course)**
This dashboard was developed as the capstone/final project for the Advanced Power BI track at **Hadi E-Learning**, showcasing skills in data modeling, DAX, Power Query, custom visuals, and interactive report design.

---

## 📄 License

This project is shared for portfolio and educational purposes. Feel free to explore the structure and design approach.
