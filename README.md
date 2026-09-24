# ✈️ Airline Business Performance & Operations Analysis | Power BI

An end-to-end multi-page Power BI reporting suite analyzing fleet operations, flight delays, passenger impact, and route efficiency across 9 relational tables.

---

## 📊 Live Report Previews

### 1. Executive Overview
<img width="1062" height="597" alt="Image" src="https://github.com/user-attachments/assets/cd2b1c27-893e-4db8-9ba6-e1b8126109a2" />

### 2. Operations & Delays
<img width="1060" height="600" alt="Image" src="https://github.com/user-attachments/assets/1125c94d-920b-4a4f-baf6-2733783d585c" />

### 3. Revenue & Route Corridor Analysis
<img width="1065" height="595" alt="Image" src="https://github.com/user-attachments/assets/cdd0e66b-3d9e-46c2-a611-5c02d3bd9fa2" />

---

## 🔑 Key Business Insights
- **Overall OTP:** Maintained an operational On-Time Performance benchmark (~67%).
- **Fleet Delay Impact:** Wide-body aircraft recorded significantly higher delay frequencies compared to narrow-body fleets.
- **Corridor Bottlenecks:** Identified specific route IDs and origin hubs driving disproportionate operational delay hours.

---

## 🛠️ Data Model & DAX Formulas
- **Architecture:** Star Schema with dedicated role-playing dimensions (`Dim_Origin_Airports`, `Dim_Destination_Airports`) and a centralized `_Measures` table.
- **Key DAX Metrics:**
  - `Total Flights`
  - `OTP %`
  - `Severe Delays Count` (>50 Mins)
  - `Passenger Delay Impact`
  - `Total Delay (Hours)`

---

## 💻 How to View the Project
1. Download the `Airline_Analytics_Dashboard.pbix` file from this repository.
2. Open using **Power BI Desktop**.
