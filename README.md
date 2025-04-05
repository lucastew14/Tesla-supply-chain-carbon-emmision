# 🔋 Tesla Supply Chain Carbon Emissions Analysis (2025)

A data-driven SQL project evaluating **Tesla's supply chain carbon emissions** by analyzing raw materials, vehicle assembly, and transportation logistics. This project provides actionable insights into which vehicle models, components, factories, and delivery methods contribute the most to CO₂ output.

---

## 📈 Project Overview

With sustainability at the forefront of innovation, Tesla has committed to reducing its environmental impact — not just through electric vehicles, but across its entire supply chain. This SQL project simulates emissions data to analyze:

- Emissions from critical EV components (e.g., battery packs, frames)
- Delivery emissions from various transportation methods
- Factory-level emissions tied to energy source and production output
- Average emissions per model (Model 3, Model Y, Cybertruck)

---

## 🛠️ Tech Stack

- **SQL (PostgreSQL syntax)**
- Simulated production, logistics, and emissions data
- Analytical queries for supply chain evaluation

---

## 🗂️ Database Structure

| Table | Description |
|-------|-------------|
| `TeslaFactories` | Tesla gigafactory data (location, energy mix, capacity) |
| `TeslaVehicles` | Vehicles produced at each facility |
| `ComponentEmissions` | CO₂ impact of individual components used in each car |
| `TransportEmissions` | Emissions caused by delivering vehicles via truck, rail, or ship |

---

## 📊 Key Analyses

1. **Total emissions per Tesla vehicle**
2. **Average carbon footprint per vehicle model**
3. **Factory-wise emissions by location and energy profile**
4. **Emissions comparison across transportation methods**
5. **Highest-emitting vehicle components**
6. **Most efficient factory by emissions per vehicle**

---

## 🧠 Insights & Takeaways

- Factories powered by renewables (e.g., Berlin-Brandenburg) consistently result in lower total emissions per unit.
- Battery Packs remain the largest contributor to CO₂ emissions across all Tesla models.
- Cargo shipping contributes significantly more to delivery emissions than rail or trucking.
- The Cybertruck has the highest combined supply chain emissions due to its battery and steel frame.

---

## 🚀 How to Run

1. Load the SQL script into any SQL environment that supports standard syntax (e.g., PostgreSQL, SQLite with minor tweaks).
2. Execute the schema and insert statements to simulate Tesla's supply chain dataset.
3. Run the analytical queries at the bottom of the script to explore insights.

---

## 📚 Use Case

This project can be used to demonstrate:

- Data analysis skills using SQL
- Real-world environmental and sustainability insights
- Supply chain and manufacturing analytics

---

## 🧾 Author

**Tewolde**  
[LinkedIn](#) • [Portfolio](#) • [GitHub](#)

---

> *Disclaimer: This project uses fictional data for educational purposes and is not affiliated with Tesla Inc.*
