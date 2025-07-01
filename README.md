# 🏥 Papollo Healthcare Dashboard

An interactive and data-driven healthcare analytics dashboard built using **Power BI**, designed to empower hospitals and healthcare administrators with real-time insights into operations, patient care, departmental performance, and financial metrics.

---

## 📌 Overview

**Papollo Healthcare Dashboard** leverages data visualization to help healthcare institutions:

- Monitor patient flow, admissions, and discharges
- Evaluate departmental performance
- Track KPIs like revenue, occupancy rate, and treatment outcomes
- Enable data-driven decision-making across the organization

Built as a Power BI Template (`.pbit`), this project allows for seamless integration with your own healthcare data sources.

---

## ✨ Key Features

✅ **Real-Time KPIs**  
Track critical metrics including Total Patients, Bed Occupancy Rate, Revenue, and Average Treatment Cost.

✅ **Departmental Insights**  
Breakdown of performance across departments (e.g., Cardiology, Orthopedics, Emergency).

✅ **Time Series Analysis**  
Monthly, quarterly, and yearly trend analytics for admissions and discharges.

✅ **Doctor & Treatment Metrics**  
Insights into doctor workloads, treatment success rates, and patient recovery metrics.

✅ **Interactive Filters**  
Drill-down functionality by date, department, doctor, and region for personalized insights.

✅ **Customizable & Reusable**  
Use this `.pbit` template with your data schema and extend it as needed.

---

## 🛠️ Getting Started

### 1. Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

### 2. How to Use

1. **Clone or Download** this repository.
2. **Open** the `Papollo Healthcare Dashboard.pbit` file using Power BI Desktop.
3. **Connect** your data when prompted (Excel, SQL Server, CSV, etc.).
4. **Map fields** to match required columns (see below).
5. **Customize visuals** as per your needs (optional).

---

## 🗃️ Data Requirements

To function properly, the dashboard expects your data to include fields such as:

| Field Name       | Description                        |
|------------------|------------------------------------|
| `PatientID`      | Unique identifier for each patient |
| `AdmissionDate`  | Date of hospital admission         |
| `DischargeDate`  | Date of discharge (if any)         |
| `Department`     | Hospital department name           |
| `Doctor`         | Attending physician name           |
| `TreatmentType`  | Type/category of treatment         |
| `Cost`           | Treatment or admission cost        |
| `Outcome`        | Outcome of treatment (e.g., Recovered, Under Treatment) |
| `Region`         | Location or branch (if applicable) |

> 🔒 **Privacy Note:** Ensure your data is anonymized and HIPAA/GDPR-compliant if working with real patient data.
# Healthcare-Dashborad
