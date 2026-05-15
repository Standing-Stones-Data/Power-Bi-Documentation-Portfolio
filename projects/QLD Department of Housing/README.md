# 🏠 QLD Housing Allocation & Maintenance Analysis

> A multi-page Power BI solution analysing Queensland Department of Housing data, designed to provide insight into allocation patterns, maintenance activity, and vulnerable population support.

---

## 🔗 Live Report
[https://app.powerbi.com/...](https://app.powerbi.com/view?r=eyJrIjoiYmVhODFiZWQtYTc0Yy00OGVjLTk0OTktYWM3YWI2MmI1NDYzIiwidCI6ImZlM2U1ZjNhLWYyZmYtNGRkNS04ZDFjLTE4MDYxNjRmODU0MSJ9)


---

## 🎯 Project Overview

This project transforms Queensland Department of Housing data into an interactive analytical tool, enabling exploration of:

- Housing allocations across regions  
- Maintenance and modification activity  
- Support for vulnerable populations (disability, homelessness risk, Indigenous status)  
- Property characteristics such as bedroom count  

The report is designed to support **policy, operational planning, and resource allocation decisions**.

---

## 🏗️ Data Model

The model integrates multiple datasets to support both allocation and maintenance analysis.

### Key Components:

- **Allocation Data**
  - Application type  
  - Disability indicators  
  - Indigenous application flag  
  - Homelessness risk  

- **Maintenance Data**
  - Property maintenance categories  
  - Modification activity  

- **Dimensions**
  - Location (LGA, service centre, suburb)  
  - Time (financial year)  
  - Property attributes (bedrooms)  

- **Supporting Structures**
  - Measures table for dynamic calculations  
  - Relationship mapping between application types and allocations  

### Design Approach:

- Separation of allocation and maintenance logic  
- Use of dynamic measures to enable flexible analysis  
- Structured relationships to support decomposition and filtering  

---

## 📊 Report Pages

### 🏠 1. Landing Page

- High-level KPIs:
  - Homes allocated  
  - Service centres  
  - Maintenance and modification counts  
  - Spend metrics  

- Entry navigation to:
  - Allocation analysis  
  - Maintenance & modification analysis  

- Designed as a **user-friendly entry point** for stakeholders  

---

### 📊 2. Allocation Analysis

Provides detailed insight into housing allocation patterns:

- Allocations by:
  - Service centre  
  - LGA  
  - Bedroom count  
  - Application type  

- Breakdown by vulnerable groups:
  - Disability status  
  - Indigenous application flag  
  - Homelessness risk  

- Geographic distribution via mapping  

---

### 🔍 Interactive Features (Allocation Page)

- **Decomposition Tree**
  - Enables deep-dive exploration across multiple dimensions  

- **Dynamic Narrative (toggleable)**
  - Automatically updates based on selected filters  
  - Provides contextual insights for users  

- **Breakdown View Toggle**
  - Users can switch between summary and detailed views  

---

### 🛠️ 3. Maintenance & Modification Analysis

Focuses on property upkeep and cost allocation:

- Maintenance activity counts  
- Modification activity counts  
- Financial spend tracking  
- Suburb-level breakdowns  

---

### 🔍 Interactive Features (Maintenance Page)

- **Dynamic narrative**
  - Highlights key maintenance patterns  

- **Filter-driven insights**
  - All visuals update based on:
    - Financial year  
    - Location  
    - Category  

---

## 📸 Dashboard Examples

### 🧠 Data Model

images/model.png

---

### 🏠 Landing Page

images/landing.png

---

### 📊 Allocation Page

images/allocation.png

---

### 🔍 Breakdown View (Allocation)

images/allocation-breakdown.png

---

### 🧾 Narrative View (Allocation)

images/allocation-narrative.png

---

### 🛠️ Maintenance & Modification

images/maintenance.png

---

### 🧾 Narrative (Maintenance)

images/maintenance-narrative.png

---

## ⚙️ Key Features

### 🎛️ Dynamic Filtering
- Analysis adjusts across:
  - Time (financial year)
  - Location
  - Property attributes  

---

### 🔍 Decomposition Tree Analysis
- Enables multi-dimensional exploration  
- Supports deeper analytical questioning  

---

### 🧾 Dynamic Narrative Generation
- Measures drive automated insight text  
- Updates based on user selections  

---

### 🔘 Interactive UX Controls
- Toggle buttons for:
  - Narrative vs visual breakdown  
- Improves usability and exploration  

---

## 🧠 Key Insights

- Allocation patterns vary significantly across regions and service centres  
- Vulnerable populations (disability, homelessness risk) show distinct distribution patterns  
- Property characteristics (e.g. bedroom count) influence allocation trends  
- Maintenance and modification activity highlights operational demand and infrastructure needs  

---

## 💡 Business Recommendations

- Regions with consistently high allocation demand may require additional housing supply investment  
- High concentrations of vulnerable applicants suggest targeted support services are needed  
- Maintenance spend patterns can inform prioritisation of infrastructure upgrades  
- Property mix (bedroom count) should be aligned with observed demand patterns  
- Data-driven insights can support equitable housing allocation strategies  

---

## 🎯 Why This Matters

Housing allocation and maintenance are critical for supporting vulnerable populations and ensuring efficient use of public resources.

This report enables stakeholders to:

- Understand demand drivers for housing  
- Identify regional pressure points  
- Improve planning and allocation strategies  
- Optimise maintenance investment  
- Support evidence-based policy decisions  

---

## 🧪 Technical Highlights

- Use of decomposition trees for advanced analytical exploration  
- Implementation of dynamic narrative measures  
- Integration of multiple datasets into a unified model  
- Interactive UX design using toggle states  
- Flexible filtering across multiple dimensions  
