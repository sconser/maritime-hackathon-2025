# Just-In-Time Arrival and Emission Reduction at Singapore Ports

## Overview
This project was developed for **Maritime Hackathon 2025** under **Category B**, focusing on **Just-In-Time (JIT) Arrival** and **Emission Reduction** in Singapore ports. Our solution aims to minimize waiting times for vessels, optimize port operations, and reduce carbon emissions through data-driven analysis and predictive modeling.

## Problem Statement
Port congestion significantly affects maritime logistics by increasing operational costs and emissions due to prolonged vessel waiting times at anchorage. Our challenge is to:
1. **Determine the waiting times** of vessels before berthing.
2. **Optimize vessel speeds** to ensure timely arrival, reducing fuel consumption and emissions.

## Data Sources
We leveraged the following datasets:
- **AIS data (June-July 2024):** Vessel movements, characteristics, and engine specifications.
- **Port polygons:** Defining port boundaries.
- **Port call data:** Tracking vessel arrivals and departures.
- **Emission factors:** Used to estimate CO2 emissions.
- **JIT Calculation Methodology:** Guidelines to derive Just-In-Time Arrivals.

## Methodology
### 1. Data Processing & Analysis
- Cleaned and preprocessed AIS data.
- Mapped vessel movements to port call records.
- Extracted relevant timestamps for waiting time calculations.

### 2. Linear Regression for JIT Predictions
- Modeled vessel waiting times based on historical data.
- Developed a predictive model to estimate **optimal vessel speeds** for JIT arrival.

### 3. Emission Reduction Estimation
- Computed CO2 emissions **before and after JIT** using provided emission factors.
- Compared anchorage and transit emissions to quantify savings.

## Deliverables
1. **Case Paper:** Documenting our methodology, assumptions, and key findings.
2. **Results (Excel file):**
   - CO2 emissions before/after JIT for anchorage and transit.
   - Time spent in anchorage before/after JIT.
   - Emission savings achieved through JIT implementation.
3. **Source Code:** Jupyter Notebook for data processing, regression modeling, and visualization.

## Conclusion
Implementing **JIT Arrival** can significantly enhance port efficiency and sustainability by reducing congestion, minimizing emissions, and optimizing vessel operations. Our approach provides a **data-driven framework** for improving maritime logistics in Singapore's high-traffic waters.

## Contributors
- Loke Sheng Jun
- Tan Kai El
- Soh Jung Xuan

## Acknowledgements
This project utilizes datasets provided by the **Maritime and Port Authority of Singapore (MPA)** and follows JIT methodologies recommended for maritime logistics.

---
📌 **For more details, check the [project repository](https://github.com/maritime2025).**

