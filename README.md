# Oracle Database Practical Assignment

## Overview
This assignment involves creating, managing, and monitoring Oracle Pluggable Databases (PDBs) using both SQL*Plus and Oracle Enterprise Manager (OEM).  
The objective is to demonstrate understanding of Oracle Database 21c PDB operations, including database creation, deletion, and dashboard configuration.

---

## Tasks

### **Task 1: Create a New Pluggable Database (PDB)**
- Created a PDB with the format:  
  **`AG_pdb_27464`**  
  Example: `er_pdb_2024101`
- Created a username following the format:  
  **`AGAPE_plsqlauca_27464`**
- Used a simple password for class-related operations.
- Verified successful creation via SQL*Plus and captured screenshots.

---

### **Task 2: Create and Delete a PDB**
- Created a second PDB with the format:  
  **`AG_to_delete_pdb_27464`**  
  
- Verified creation, then deleted the PDB.
- Captured screenshots for both creation and deletion steps.

---

### **Task 3: Oracle Enterprise Manager (OEM)**
- Configured Oracle Enterprise Manager for monitoring and administration.
- Accessed the OEM dashboard and verified visibility of the created PDB.
- Captured a screenshot of the dashboard clearly showing the username.

---

## Screenshots
Screenshots include:
- PDB creation confirmation  
- PDB deletion confirmation  
- OEM dashboard view

*(All screenshots are saved in the `/screenshots` folder of this repository.)*

---

## Issues and Solutions
- **Issue:** Connection error during PDB creation due to missing listener.  
  **Solution:** Restarted `OracleServiceORCL` and listener service, then re-ran the command.
- **Issue:** OEM not loading.  
  **Solution:** Reconfigured the port and verified using `emctl status dbconsole`.

---
**Author:** Ineza Agape  
**Student ID:** 27464  
**Course:** Oracle Database Administration  
![alt](https://)