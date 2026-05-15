# 🚉 NSW Train Line Performance Dashboard

> A multi-page Power BI solution analysing Transport for NSW train usage, combining data modelling, spatial analytics, and interactive dashboard design.

---

## 🔗 Live Report

https://app.powerbi.com/view?r=...

---

## 🎯 Project Overview

This project delivers an end-to-end business intelligence solution, transforming Transport for NSW open data into an interactive analytical tool.

The report enables users to explore:

- Train line performance  
- Station-level activity  
- Geographic distribution of infrastructure  
- Passenger behaviour by ticket type  

---

## 🏗️ Data Model

The report is built on a structured and scalable data model.

### Key Components:

- **Fact Tables**
  - Train usage data
  - Entry/exit datasets  

- **Dimension Tables**
  - Stations  
  - Train Lines  
  - Date  

- **Bridge Tables**
  - Stations and Lines (resolves many-to-many relationships)

- **Supporting Tables**
  - Station latitude/longitude data  
  - Colour scheme for dynamic theming  

- **Parameter Tables**
  - Used for report interactivity and user selection  

### Design Approach:

- Star-schema inspired structure  
- Controlled relationships to maintain model clarity  
- Separation of logic and presentation layers  

---

## 📊 Report Pages

### 🚉 1. Line Performance Page

- Total trips KPI (~795M)
- Top-performing months
- Ticket type distribution
- Dynamic filtering by train line
- Colour scheme adapts to selected line

---

### 🗺️ 2. Station Location Page

- Map visual using **latitude/longitude coordinates**
- Displays station entrances across NSW
- Supporting table showing:
  - Street entrance names  
  - Entrance types  

- KPI: Total station entrances  

---

### 📍 3. Station Analysis Page

- Top 10 stations by departures  
- Least-used stations  
- Monthly performance trends  
- Geographic visual of station distribution  

---

## ⚙️ Key Features

### 🎛️ Dynamic Filtering
- Full report responds to line and date selection  

### 🎨 Dynamic Colour Theming
- Report styling updates to match selected train line  

### 🗺️ Spatial Analysis
- Integration of geographic coordinates for mapping  

### 🔗 Multi-Page Navigation
- Seamless navigation across report pages  

### 📊 KPI & Ranking Logic
- Top/least station calculations  
- Monthly performance tracking  

---

## 🧠 Key Insights

- Over **795 million trips** recorded in the dataset  
- Passenger usage heavily concentrated in metropolitan areas  
- Significant variance in station usage across the network  
- Different lines exhibit distinct passenger behaviour patterns  

---

## 🎨 Design Approach

- Layout designed for clarity and usability  
- Strong visual hierarchy (KPIs → insights → detail)  
- Transport for NSW branding applied  
- Minimal clutter to enhance readability  
- Context-aware messaging to guide users  

---

## 🚧 Challenges & Solutions

| Challenge | Solution |
|----------|--------|
| Many-to-many relationships (stations ↔ lines) | Implemented bridge table |
| Large dataset performance | Optimised model structure |
| User navigation | Added multi-page navigation buttons |
| UX clarity | Simplified visuals and layout |

---

## 📈 Outcome

This project demonstrates:

- Advanced Power BI data modelling  
- Practical use of spatial data  
- Strong UX and report design  
- Ability to convert public data into actionable insights  

## 📸 Dashboard Examples

### Line Performance
![Line Page](images/page1.png)

### Station Location
![Station Location](images/page2.png)

### Station Analysis
![Station Analysis](images/page3.png)

``
