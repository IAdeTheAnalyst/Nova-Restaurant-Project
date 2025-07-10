# Nova Restaurant Project

This PostgreSQL project analyzes global fine dining patterns through the lens of **NOVA**, a fictional luxury restaurant brand. The goal was to explore international restaurant data and uncover insights into customer preferences, pricing strategies, and high-end cuisine distribution.

## 📊 Project Overview

- Analyzed **20,000+ restaurant listings** across **21 countries**
- Focused on **pricing tiers**, **customer ratings**, and **delivery availability**
- Explored which **cuisines dominate** in elite markets and where fine dining thrives

## 🧠 Key Insights

- Italian, French, and Japanese cuisines consistently lead in high-end restaurant markets
- Higher price tiers correlate with better customer ratings and greater delivery availability
- Major cities in the US, UK, and UAE host the largest concentration of premium restaurants

## 🛠️ SQL Techniques Used

- `JOIN`s and relational data modeling
- `CASE` statements for tiered categorization
- `STRING_TO_ARRAY` + `UNNEST` for multi-value field processing
- `FILTER`, `GROUP BY`, and aggregation for custom metrics

## 🧼 Data Preparation

- Cleaned inconsistent text and separated multi-value fields (e.g., cuisines, locations)
- Removed null values and grouped sparse categories into "Other"
- Renamed columns for clarity and analysis

## 📁 Dataset Summary

- **Attributes**: Restaurant name, cuisines, pricing, aggregate ratings, delivery, country, city
- Inspired by a Zomato dataset; rebranded to **NOVA** for creative storytelling

## 💼 Business Applications

- Market research for restaurant expansion
- Strategic planning for delivery partnerships
- Customer segmentation by cuisine & budget

---

## 🚀 Related Projects

- [📦 Instacart Orders Project](https://github.com/yourusername/instacart-project)
- [📺 Netflix Titles Project](https://github.com/yourusername/netflix-project)

---

