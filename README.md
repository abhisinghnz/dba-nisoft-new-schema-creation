# NISOFT Schema build

Create new schema for G&T Thermal Group: NISOFT_GLBG - Glenbrook BESS Power Station

---

## 🚀 Process
- Create the required tablespace
- Create the NISOFT schema with require permission
- Import the blank schema dump
- UPdate the PREFERENCES table 
    - MULTI_DB_ABBREV --Used for creating users on Multi Database instance 
    - SITE_NAME -- The name of the site to appear on the documsystem and documnet 
    - Configure the user
- Import
    - EQUIPMENT 
    - EQUIPMENT_AREA
    - OPERATIONAL_AREA

---

## 📦 Installation