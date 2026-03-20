# GRA4154: BioNutrient Supply Chain Optimization 🚢

## 🎯 Executive Summary
This project provides an end-to-end optimization solution for the BioNutrient supply chain competition. The model minimizes total yearly costs across production, storage, and complex maritime logistics.

**Key Performance Indicator:**
* **Total Yearly Cost:** 1,006,501,083 NOK

## 🛠 Features & Methodology
- **Linear Programming:** Implemented using **AMPL** with a focus on multi-period inventory and fleet assignment.
- **Strategic Stockpiling:** The model identifies a critical "Build-up" phase in Q2 at the Central Warehouse to handle the Q3 demand peak.
- **Fleet Optimization:** Uses binary decision variables to handle full-year vs. partial-year vessel rentals (*Anna* and *Emma*).

## 📊 Interactive Dashboard
The final output is a self-contained HTML dashboard (`SCOMPHESol.html`) featuring:
* **Sankey Diagrams:** Visualizing the flow of 180,000+ tons of feed.
* **Warehouse Heartbeat:** Monitoring capacity constraints (70k ton limit).
* **Cost Waterfall:** Breaking down the 1B NOK expenditure.
* **Fleet Heatmap:** Showing the quarterly schedule for each vessel.

## 🚀 How to Run
1. Ensure `amplpy` and `plotly` are installed in your environment.
2. Open `SCOMPHESol.ipynb` in VS Code or Jupyter.
3. Run all cells to solve the model and regenerate the interactive plots.
Or just download the html it works great, probably.
