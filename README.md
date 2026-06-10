# 🔬 BioThreat Intelligence Platform
### End-to-End Power BI Dashboard | Drug Discovery × Conservation Biology

[![Live Dashboard](https://img.shields.io/badge/Power%20BI-Live%20Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://app.powerbi.com/reportEmbed?reportId=c900167b-fb93-4cc7-a649-5aac034bb3bb&autoAuth=true&ctid=51a6364a-0466-47d0-b3ba-1517161ddd0d)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Madhav%20Limbasiya-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/madhavlimbasiya)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)](https://github.com/MadhavLimbasiya)

---

## 📌 Project Overview

Marine and terrestrial biodiversity holds enormous untapped potential for next-generation drug discovery — yet many of the most chemically rich species face critical conservation threats.

The **BioThreat Intelligence Platform** is an end-to-end Power BI dashboard that bridges the gap between **conservation biology** and **pharmaceutical drug discovery**. Instead of treating species data and bioactivity screening as separate silos, this platform integrates field expedition records, laboratory processing pipelines, compound extraction profiles, and global occurrence data into a single interactive intelligence system.

By analyzing species bioactivity, pipeline efficiency, and conservation risk in unison, this platform helps researchers and decision-makers identify:

- 🎯 **High-Value Targets** — Which species deliver the highest hit rates and most drug-worthy compounds
- 🌿 **Conservation Urgency** — Which high-value species are simultaneously at the greatest extinction risk
- 🔬 **Pipeline Bottlenecks** — Where the drug discovery funnel loses yield, purity, or efficiency
- 🗺️ **Global Biodiversity Patterns** — Where species occur, at what depth, and under what threat conditions worldwide

---

## 🚀 Live Dashboard

👉 **[Click Here to View the Live Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=c900167b-fb93-4cc7-a649-5aac034bb3bb&autoAuth=true&ctid=51a6364a-0466-47d0-b3ba-1517161ddd0d)**

> No installation required. Open directly in your browser.

---

## 📊 Dashboard Pages

This platform comprises **five interactive pages**, each designed as a standalone analytical module:

| # | Page Name | Purpose |
|---|-----------|---------|
| 🏠 1 | **Executive Overview** | 30-second KPI snapshot — hit rates, IC50, pipeline cost, priority hits |
| 🔬 2 | **Discovery Pipeline** | Full funnel from field expedition → processing → extraction → bioassay → active hit |
| 🌍 3 | **Global Occurrences Map** | Interactive lat/long scatter of species occurrences colored by threat level |
| ⚖️ 4 | **Risk vs Opportunity Matrix** | Scatter quadrant mapping conservation risk against drug discovery value |
| 💊 5 | **Compound Intelligence** | Deep dive into the chemical compound library — stages, targets, patents, value |

---

## 💡 Technical Highlight: Risk vs Opportunity Matrix

A core innovation of this project is the **Risk vs Opportunity Scatter Matrix** on Page 4. This visualization places every species simultaneously across two critical dimensions:

- **X-axis:** Conservation Threat Score (how endangered the species is)
- **Y-axis:** Hit Rate % (how scientifically valuable it is for drug discovery)

This segments species into four strategic quadrants:

| Quadrant | Meaning |
|----------|---------|
| 🔴 **Urgent** | High threat + High value — prioritize for both conservation AND fast-track research |
| 🟡 **Promising** | Low threat + High value — safe to research aggressively |
| 🟠 **Conserve** | High threat + Low value — focus on conservation, deprioritize extraction |
| ⬜ **Monitor** | Low threat + Low value — standard monitoring only |

This quadrant framework enables a **dual mandate decision engine** — optimizing both scientific return and ecological responsibility in a single view.

---

## 📈 Key Metrics Tracked

| Metric | Description |
|--------|-------------|
| **Total Bioassays Run** | All assays across species and therapeutic targets |
| **Hit Rate %** | Ratio of active hits to total assays per species |
| **Median IC50 (nM)** | Compound potency indicator — lower = more potent |
| **Total Pipeline Cost ($)** | End-to-end drug discovery spend |
| **High Priority Hits** | Compounds meeting drug-worthiness criteria |
| **QC Pass Rate** | Laboratory quality control performance |
| **Avg Yield % / Purity %** | Extraction efficiency metrics |
| **Avg Selectivity Index** | Compound safety and targeting precision |
| **Total Occurrences** | Global biodiversity records across 233+ countries |
| **IUCN Category** | Conservation status per species (CR / EN / VU / LC) |
| **ROI Estimate** | Commercial value per pipeline dollar spent |

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **Power BI** | Dashboard development, data modeling, DAX measures, interactive visuals |
| **DAX** | Custom KPI measures, SWITCH/CALCULATE patterns, conditional logic |
| **Star Schema** | FactBioactivity, FactOccurrences, FactExpedition, FactExtraction, FactProcessing |
| **GBIF API** | Global Biodiversity Information Facility — species occurrence data |
| **IUCN Red List** | Conservation status and threat scoring per species |
| **Python** | Data preparation, API extraction, CSV generation |
| **CSV / Excel** | Source data files for all fact and dimension tables |

---

## 🗂️ Data Model

Built on a **Star Schema** with the following tables:

**Fact Tables:**
- `FactBioactivity` — bioassay results, IC50, selectivity, therapeutic targets
- `FactOccurrences` — global species occurrence records with lat/long and habitat
- `FactExpedition` — field collection records
- `FactExtraction` — compound extraction records with yield and purity
- `FactProcessing` — laboratory processing and QC records

**Dimension Tables:**
- `DimSpecies` — species master with IUCN category, threat score, conservation funding
- `DimCompound` — compound library with development stage, patent status, commercial value
- `DimDate` — date dimension for time-series analysis

**Measures Table:**
- `_Measures` — all DAX KPI measures centralized in a dedicated table

---

## 🧬 Species Analyzed

| Species | Domain | IUCN Status |
|---------|--------|-------------|
| *Bothrops jararaca* | Venom / Snake | Vulnerable |
| *Conus geographus* | Marine / Cone Snail | Least Concern |
| *Halichondria okadai* | Marine / Sponge | Data Deficient |
| *Phyllobates terribilis* | Amphibian / Poison Frog | Endangered |
| *Bugula neritina* | Marine / Bryozoan | Least Concern |
| *Salinispora tropica* | Marine / Bacteria | N/A |

---

## 🔑 Project Highlights

- 🧪 **838 total species occurrences** recorded across **233 countries**
- 💊 Multi-stage drug discovery pipeline tracked end-to-end
- 🌊 Average sample collection depth: **110.49 meters**
- 🔬 Full compound library with **patent status**, **development stage**, and **commercial value estimates**
- 🗺️ Global scatter map using real GBIF lat/long coordinates
- ⚖️ Dual-mandate framework balancing **scientific ROI** and **conservation ethics**


---

## 📥 How to Use

**Option 1 — View Live (No Installation):**

👉 Open the **[Live Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=c900167b-fb93-4cc7-a649-5aac034bb3bb&autoAuth=true&ctid=51a6364a-0466-47d0-b3ba-1517161ddd0d)** directly in your browser.

**Option 2 — Explore Data Locally:**

```bash
git clone https://github.com/MadhavLimbasiya/BioThreat-Intelligence-Platform.git
cd BioThreat-Intelligence-Platform
```

Then open any `.csv` file in the `/data/` folder using Excel, Python, or Power BI Desktop.

---

## 👨‍💻 About the Developer

**Madhav Limbasiya** — Data Analyst passionate about building end-to-end analytics solutions that bridge science, business, and impact.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/madhavlimbasiya)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=flat&logo=github)](https://github.com/MadhavLimbasiya)
[![Tableau](https://img.shields.io/badge/Tableau-Public%20Profile-orange?style=flat&logo=tableau)](https://public.tableau.com/app/profile/madhav.limbasiya)

---

*This project was developed as part of a data analytics portfolio demonstrating end-to-end Power BI development, DAX data modeling, and cross-domain data integration across bioinformatics, conservation biology, and pharmaceutical research.*
