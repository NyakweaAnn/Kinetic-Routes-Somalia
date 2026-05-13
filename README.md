# 🌍 Kinetic Routes: Predictive Displacement Monitoring (Somalia)

### **Executive Summary**
This project provides a **Command Center** for humanitarian decision-makers. By correlating live conflict lethality with market stress, the dashboard identifies "push" factors before mass displacement occurs at the border.

---

## 🏗️ The Data Architecture
This model synchronizes three disparate datasets into a relational engine:

1. **The Push (Conflict):** ACLED data tracking **93K+ fatalities** in Somalia.
2. **The Stress (Economics):** WFP market data identifying all-time price peaks in **Maize and Sorghum**.
3. **The Result (Movement):** UNHCR displacement figures validated by geographic corridors.



---

## 📊 Technical Methodology
- **ETL Process:** Used Power Query to clean and normalize district names (`Admin2`) across conflict and market sources.
- **Relational Modeling:** Established a **Many-to-Many** bidirectional relationship between conflict events and price spikes to enable cross-filtering.
- **Geospatial Intelligence:** Categorized data by **City/County** to isolate specific transit "choke points" like Belet Hawo.

---

## 🧠 Key Findings
- **Trigger Correlation:** Displacement in the Gedo region surges exactly **14 days** after local grain prices exceed historical thresholds.
- **Hotspot Identification:** Belet Hawo was identified as a primary "Red Flag" due to the intersection of high fatality rates and peak food prices.

---

## 🛠️ How to View
- Download the `.pbix` file in this repository.
- Open in **Power BI Desktop**.
- Interact with the Map to see real-time filtering of the Hunger and Movement charts.
