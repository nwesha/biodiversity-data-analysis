# biodiversity-data-analysis

**Data-driven assessment of species diversity and at-risk populations across U.S. National Parks.**

---

## 🚨 Why This Matters

America’s national parks are biodiversity strongholds—but climate pressure, habitat loss, and incomplete monitoring threaten their resilience. This project delivers an urgent, data-backed blueprint to:

* Pinpoint conservation hotspots
* Quantify protection gaps across taxonomic groups
* Guide rapid, evidence-based interventions

---

## 🛠️ Tech Stack & Skills Demonstrated

* **Python 3 & Jupyter Notebook** — interactive exploration, reproducible analyses
* **Pandas & NumPy** — data wrangling, missing-value handling, high-performance aggregation
* **Matplotlib** — custom visualizations (bar charts, pie/donut plots, comparative analyses)
* **SciPy Stats** — chi-square test for statistical validation (χ² test, p-value interpretation)
* **NLTK & Regex** — tokenization and word-frequency analysis of common names

---

## 📊 Data Sources

1. **`species_info.csv`**

   * Metadata for 5,541 species: scientific & common names, taxonomic category, conservation status
2. **`observations.csv`**

   * Seven-day sighting counts per species in four parks: Yellowstone, Yosemite, Bryce Canyon, Great Smoky Mountains

> *Note: Datasets are fictional but structured to mirror real-world biodiversity monitoring.*

---

## 🔍 Analysis Workflow

1. **Data Ingestion & Cleaning**

   * Read CSVs with Pandas, inspect for nulls, standardize column types
2. **Exploratory Data Analysis**

   * Summarize species counts, conservation‐status distributions, and sighting volumes
3. **Statistical Testing**

   * χ² test comparing “protected” vs. “not protected” proportions between mammals and reptiles
4. **Natural-Language Processing**

   * Tokenize common names, compute word frequencies to highlight indicator groups (e.g., “Bat”)
5. **Focused Deep Dive**

   * Filter for bat species, merge with observations, aggregate by park and protection status
6. **Visualization & Reporting**

   * Generate publication-quality charts with Matplotlib and annotate key findings

---

## 📈 Key Findings

* **5,541 species** catalogued; **178 at-risk** (Species of Concern, Endangered, Threatened, In Recovery)
* Mammals show a **significantly higher threat rate** than reptiles (χ² = 4.27, *p* = 0.039)
* “Bat” is the most frequent token in common names; Yellowstone leads in bat sightings
* **Great Smoky Mountains** may be under-surveyed—recommend redirecting survey efforts

---

## 🏁 Conclusions & Recommendations

* **Priority Conservation for Mammals:** Elevated protection needs for mammals (especially bats) demand immediate habitat preservation measures and targeted monitoring initiatives.
* **Park-Specific Action Plans:** Direct resources to Yellowstone and Yosemite for high-activity zones; initiate rapid response survey teams in Great Smoky Mountains to address under-reporting.
* **Data Enhancement:** Integrate multi-year datasets and climate projections to forecast species shifts and inform long-term conservation strategies.
* **Stakeholder Engagement:** Share insights with National Park Service, wildlife NGOs, and local conservation bodies to translate data into policy and on-the-ground action.

---

## 🤝 Contributions & Contact

This project is open to enhancements—whether it’s multi-year trend analysis, climate forecasting overlays, or an interactive dashboard.

*Built with rigorous data-engineering, statistical modeling, and visualization best practices.*