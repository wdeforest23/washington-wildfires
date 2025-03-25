# 🔥🌊 Climate Risk Explorer – Washington State

**A climate risk dashboard for Washington State communities, powered by ClimRR, BigQuery, and Natural Language AI.**

![banner image or gif if available]

## 🚀 Project Overview

The Climate Risk Explorer is an interactive web app that helps make climate risk data more accessible and actionable. It focuses on the state of Washington, visualizing hazards such as **wildfires**, **earthquakes**, and **tsunamis**, and identifies the communities most vulnerable to their impacts by combining **ClimRR climate projections** with **demographic and census data**.

The app features:
- An **interactive map** and dashboard highlighting climate risks across counties or census tracts.
- A **natural language interface** that lets users ask questions like “Which Washington counties have the highest wildfire risk by 2050?” and returns results using live SQL queries from BigQuery.
- An emphasis on **accessibility, equity**, and **community-level insight**.

---

## 🧠 Motivation

Environmental disasters like wildfires and earthquakes disproportionately affect vulnerable populations. While high-quality climate projection data exists (such as from ClimRR), it can be difficult for decision-makers and community members to interact with or understand.

This project aims to:
- **Democratize access** to climate risk data
- Help identify **at-risk communities** in Washington State
- Demonstrate how **AI and data tools** can improve public awareness and support climate resilience efforts

---

## ❓ Problem Statement

Despite the availability of robust climate modeling data, insights are often hidden behind technical barriers, such as complex file formats, high volumes of data, or the need for domain expertise.

### Key Challenges:
- Data is difficult to explore interactively
- Policymakers and residents lack tools to query and visualize data in an accessible way
- Climate projections need to be contextualized with **local demographics**

---

## ✅ Solution

Build a web-based, user-friendly platform that allows:
- **Exploring climate hazards** (wildfire, earthquake, tsunami) via map and time-series visualizations
- **Querying BigQuery datasets** using **natural language**
- **Combining ClimRR climate risk data with U.S. Census data** to highlight socially vulnerable communities

---

## 🛠️ Methodology

### 1. **Data Sources**
- **ClimRR**: High-resolution climate projections for various hazards across the U.S.
- **U.S. Census / ACS**: Demographics (e.g., age, income, housing, race/ethnicity)
- Optional: FEMA, NOAA, or WA State open data for earthquake/tsunami historical data

### 2. **Data Engineering**
- Preprocess and upload datasets to **Google BigQuery**
- Join hazard projections with census tract-level demographic data
- Standardize formats and enrich datasets for spatial joins

### 3. **Visualization & Dashboard**
- Built with **Streamlit** or **Flask + Leaflet/Mapbox**
- Map of WA with filters for hazard type, time period, and demographics
- Table and charts with drilldowns by region

### 4. **Natural Language to SQL**
- Use **LangChain + OpenAI or Gemini** to convert user queries into SQL
- Connect to BigQuery using Python API
- Display results and optionally visualize them

---

## 📍 Focus Region

> Washington State, with deep dives into King County and other high-risk or highly populated counties (e.g., Yakima, Spokane, Pierce)

---

## 📊 Example Use Cases

- “Which counties in WA have the highest projected wildfire risk in 2050?”
- “Show tracts in King County with high earthquake risk and a large population of elderly residents.”
- “Where in Seattle is both wildfire risk and low-income population density high?”

---

## 📅 Project Milestones

| Week | Milestone |
|------|-----------|
| 1    | Gather and ingest ClimRR & census data into BigQuery |
| 2    | Perform exploratory analysis and define key metrics |
| 3    | Build map + dashboard frontend |
| 4    | Implement natural language query interface |
| 5    | Refine UI/UX and test use cases |
| 6    | Final deployment, README polish, and portfolio packaging |

---

## 💡 Future Work

- Add ML models to forecast combined climate + demographic vulnerability
- Integrate real-time data feeds (e.g., active wildfire incidents)
- Include policy recommendations or adaptation strategies based on analysis
- Expand to other states or hazards

---

## 🤝 Credits

- Climate Risk data: [ClimRR.org](https://climrr.org)
- Demographic data: [U.S. Census Bureau](https://data.census.gov)
- Natural Language Interface: [LangChain](https://www.langchain.com/) + [OpenAI](https://openai.com/) or [Gemini](https://deepmind.google/technologies/gemini/)

---

## 🌐 Try it Out (coming soon...)

Demo will be hosted on Streamlit Cloud or Google Cloud Run. Stay tuned!

---

## 📬 Contact

Feel free to reach out or connect with me on [LinkedIn](your-link) if you’d like to collaborate or learn more about this project.




