# Performance-and-Backlog-Simulation
A Google Sheets tool to simulate 3PL performance and backlog risk under different volume for mitigrate action 

# Objective
This model simulates and forecasts outbound **capacity (CAP)** at each SOC during **Campaign Peak (CP)** and **Business-As-Usual (BAU)** days. It leverages historical CAP data and assumes a **normal distribution** to generate realistic capacity scenarios.

# Scope
- Uses statistical measures: **Average**, **Standard Deviation**, and **High case/Low case Levels** (e.g., 70%, 90%) to simulate future capacity behavior.
- Applicable for:
  - Estimating expected CAP during sales campaigns
  - Daily capacity planning under BAU
  - Analyzing CAP gaps between BAU vs CP vs Spike to support resource planning

# Use Cases
- Operational planning for 3PL partners
- 3PL SOC resource allocation and shift planning
- Early identification of risk (e.g., overload, underutilization) during CP events

# Note
This model does **not** rely on parcel volume but uses **actual historical outbound CAP** per SOC, after outlier removal (e.g., extremely low CAP days). It provides a more accurate reflection of operational capacity and stress under real-world conditions.
