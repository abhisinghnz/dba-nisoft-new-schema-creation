# NISOFT Schema build

Create new schema for G&T Thermal Group: NISOFT_GLBG - Glenbrook BESS Power Station

---

## 🚀 Process
- Create the required tablespace
- Create the NISOFT_XXXX schema with require permission 
- Import the blank schema dump
- cleanup tables that are copied from old schema 
- Update the PREFERENCES table 
    - MULTI_DB_ABBREV --Used for creating users on Multi Database instance 
    - SITE_NAME -- The name of the site to appear on the documsystem and documnet 
    - Configure the user
- Load New data to the schema 
    - EQUIPMENT 
    - EQUIPMENT_AREA
    - OPERATIONAL_AREA

---

## 📦 Please use the dump under dumpfile folder to import
- imp commnd to user 

`impdp sc_export/pasword PARFILE=imp.par` (place the par file into the export/import folder)

