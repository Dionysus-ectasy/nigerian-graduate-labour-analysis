# 🎓 Nigerian Graduate Labour Force Analysis
**A 5-page interactive Power BI dashboard exploring graduate employment, skills gaps, and labour market trends across Nigeria**

---

## 📊 Project Overview

This capstone project was developed as part of the **Digital Innovation & Leadership Programme (DILP)** at Cedars. It analyses the Nigerian graduate labour market using survey data from ~4,800 respondents combined with ILO macroeconomic indicators, producing actionable insights across employment, education, sector, and youth dimensions.

The dashboard is designed to help policymakers, educators, and researchers understand where Nigeria's graduate workforce stands — and where intervention is most needed.

---

## 📁 Dashboard Pages

| Page | Focus |
|------|-------|
| **1. National Overview** | Top-level KPIs, employment by gender, age group, geopolitical zone, and ILO LFPR/NEET trends (2010–2025) |
| **2. Education & Skills Gap** | Skills gap by education level and zone, graduate-to-employment pipeline, course group scatter analysis |
| **3. Sector & Salary** | Average salaries by sector, top sectors by employment, salary distribution (well-paid vs low-paid), NYSC completion rates |
| **4. Labour Force Participation** | LFPR vs unemployment trends, employment-to-population ratio, informal employment, working poverty, jobs gap (2010–2025) |
| **5. Youth & Recommendations** | Youth employment vs overall comparison, NEET trend, gender salary gap, top skills among employed youth |

---

## 🔑 Key Findings

- **Employment Rate: 39.7%** — less than 2 in 5 graduates are employed full-time
- **Underemployment: 29.3%** — a large share of workers are in roles below their qualification level
- **Skills Gap Rate: 28.8%** — over 1,200 Bachelor's graduates report a mismatch between training and job demands
- **Aerospace is the highest-paying sector** (₦166K avg/month); Finance employs the most graduates (230)
- **38.6% of employed graduates** found jobs through personal contacts — highlighting the outsized role of networks
- **Male graduates earn 18% more** than female graduates on average among youth
- Federal universities produce the **highest employment rate but also the widest skills gap**, suggesting stronger job placement but weaker curriculum alignment with industry needs

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — data modelling, DAX measures, report design
- **DAX** — 28 custom measures including dynamic KPIs, gap rates, pipeline calculations, and trend comparisons
- **Data Sources** — graduate survey dataset (~4,800 respondents) + ILO macroeconomic indicators (2010–2025)
- **Data Cleaning** — handled in Power Query (type mismatches, filter context issues, relationship modelling)

---

## 📐 Technical Highlights

- Built and resolved **filter context conflicts** across multiple visual layers
- Implemented **conditional formatting** on heatmap tables (Skills Gap Rate by Education Level & Zone)
- Designed a **5-page navigation system** with custom icon-based sidebar
- Integrated **ILO time-series data** alongside survey cross-sectional data in a unified model
- Used **scatter plots** to visualise the skills gap vs employment rate trade-off across course groups

---

## 🚀 Getting Started

### Requirements
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — Windows only
- Minimum 4GB RAM recommended for smooth performance

### How to Use
1. Download or clone this repository
   ```bash
   git clone https://github.com/dionysus-ectasy/nigerian-graduate-labour-analysis.git
   ```
2. Open **Power BI Desktop**
3. Click **File → Open report** and select the `.pbix` file from the downloaded folder
4. Use the **icon-based sidebar** on the left to navigate between the 5 dashboard pages
5. Apply slicers and filters on each page to explore specific segments (gender, zone, education level, etc.)

> ⚠️ **Note:** If the data source prompts a refresh error on open, go to **Home → Transform Data → Data Source Settings** and update the file path to match your local directory.

---

## 👤 About

**Okezie Divine Nwaoha (Icarus)**
Data Analyst | Electrical & Electronics Engineer | DILP Fellow

- 🔗 [LinkedIn](https://linkedin.com/in/divinenwaoha)
- 💼 [Fiverr – @intellidash](https://fiverr.com/intellidash)
- 🐙 [GitHub – dionysus-ectasy](https://github.com/dionysus-ectasy)

---

> *"Data is not just numbers — it's the story of people, systems, and the gaps between them."*
