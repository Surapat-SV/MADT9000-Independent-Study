# MADT9000-Independent-Study
Independent Study: Multi-Agent system Boosting Efficiency in search engine marketing (SEM), 1st Semester, 2024

# 🤖 Multi-Agent System: Boosting Efficiency in Search Engine Marketing (SEM)

This project is part of the independent study for the **Master's in Advanced Data Analytics and Business Administration** at NIDA. It showcases how **Generative AI** and **Multi-Agent Systems** can significantly reduce the time and inconsistencies in Search Engine Marketing (SEM) workflows by automating key tasks such as business analysis, keyword planning, website analysis, and ad copywriting.

---

## 🎯 Project Objective

To develop an AI-powered SEM Planner that streamlines and automates the campaign creation process using a modular, multi-agent architecture integrated with Google BigQuery, generative AI models (e.g., Gemini), and a web-based user interface via Streamlit.

---

## 🧠 System Overview

The SEM Planner consists of four intelligent agents:

| Agent Role         | Input Type                    | Output                                      |
|--------------------|-------------------------------|---------------------------------------------|
| Business Analyst   | Business Requirements         | Structured summary stored in memory         |
| Web Scraper        | URLs (own & competitor sites) | Keyword comparison, cosine similarity score |
| Keyword Planner    | Keyword ideas                 | Keyword plan via BigQuery Text-to-SQL       |
| Ads Copywriter     | Structured keyword info       | Ad headlines + descriptions (formal/informal) |

Each agent operates modularly and feeds output into a main controller for final report generation.

---

## 💡 Key Features

- **Multi-agent architecture** using role-based AI agents
- **Text-to-SQL Querying** from Google BigQuery for real-time keyword data
- **Web Scraping** and semantic comparison with cosine similarity
- **AI Copywriting** for ad text creation in different tones
- **Modular UI** designed for usability and scalability
- **Structured Outputs** validated with Pydantic models

---

## 🧪 Evaluation

Conducted a focus group with 5 SEM professionals. Key outcomes:

| Task             | Old Time (min) | New Time (min) | Time Saved (%) |
|------------------|----------------|----------------|----------------|
| Business Analyst | 402            | 5.4            | 98.66%         |
| Web Analyst      | 132            | 6.2            | 95.30%         |
| Keyword Planner  | 522            | 7              | 98.66%         |
| Ad Copywriter    | 228            | 1.8            | 99.21%         |

> ✅ Consistency of keyword usage increased across the SEM plan and ad copy  
> ✅ Overall time savings: **4–5 days**

---

## 📈 Tools & Libraries

- **Streamlit** – UI Framework
- **Google Generative AI (Gemini)** – Content generation
- **Pandas / PandasAI** – Data processing
- **BigQuery** – Data warehouse querying via Text-to-SQL
- **BeautifulSoup** – Web scraping
- **Pydantic** – JSON schema validation
- **Matplotlib** – Optional visualization
- **FPDF / Base64** – Export reports to PDF

---

## 🔮 Future Development

- 🔄 Google Ads API integration for real ad deployment
- 🧠 Negative keyword automation & ad tone control
- 📈 Keyword trend forecasting
- 🌐 Expand to support SEO automation
- 🧩 Add a Smart Chatbot Assistant using LangChain

---

## 📬 Contact

**Surapat Verawudh**   
📧 surapatpine@gmail.com  

---

## 📎 Related Files

- 📄 Final Report (PDF): [`MULTI-AGENT SYSTEM BOOSTING EFFICIENCY IN SEARCH ENGINE MARKETING`]
---
