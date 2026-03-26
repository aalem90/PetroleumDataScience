## 📂 Dataset

This project utilizes a large-scale dataset (~7 million records) combining both **spatial** and **temporal** data related to oil & gas wells.

---

### 🧭 Data Sources

The dataset is derived from official public data provided by the New York State Department of Environmental Conservation (NYS DEC):

- **Spatial Data (Well Locations & Attributes)**  
  https://dec.ny.gov/environmental-protection/oil-gas/wells-datageographical-information/downloadable-data  

- **Temporal Data (Production Data)**  
  https://dec.ny.gov/environmental-protection/oil-gas/wells-datageographical-information/downloadable-production-data  

---

### 🧩 Dataset Description

#### 1. Spatial Data
Contains static information about wells:
- Well coordinates (latitude, longitude)  
- Well type (gas, oil, etc.)  
- Operator and field information  
- Formation and reservoir details  

#### 2. Temporal Data
Time-series production data:
- Monthly/annual gas production volumes  
- Water production  
- Production timeline per well  
- Operational status over time  

---

### 🔗 Data Integration
The analysis integrates both datasets using:
- **Well Identifier (API / Well ID)** as the primary key  
- Spatial + temporal merging to enable:
  - Asset-level performance tracking  
  - Time-series decline analysis  
  - Water risk monitoring  

---

### ⚙️ Data Processing
Given the dataset size (~7M rows), the following steps were applied:

- Data cleaning and standardization  
- Handling missing and inconsistent records  
- Aggregation for performance optimization (Tableau-ready)  
- Feature engineering:
  - Production decline indicators  
  - Water cut estimation  
  - Asset-level summarization  

---
