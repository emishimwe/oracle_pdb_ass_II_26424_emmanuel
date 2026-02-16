# Oracle Pluggable Database Assignment II  
Oracle Database 21c – Multitenant Architecture

## Student Information
- Name: Ishimwe Emmanuel  
- Student ID: 26424  
- Course: Database Development with PL/SQL (INSY 8311)  
- Instructor: Eric Maniraguha  

---

## Assignment Overview

This assignment demonstrates practical implementation of Oracle Multitenant Architecture using Oracle Database 21c.

The objectives of this assignment were to:

- Create and manage a Pluggable Database (PDB)
- Create a local user inside a PDB
- Create and delete a temporary PDB
- Access and verify the environment using Oracle Enterprise Manager (OEM)
- Document all work professionally on GitHub

---

## Oracle Environment Used

- Oracle Database 21c (Multitenant Architecture)
- SQL*Plus
- Oracle Enterprise Manager (OEM) Express
- Windows Operating System

All tasks were performed within a Container Database (CDB) environment containing Pluggable Databases (PDBs).

---

# Task 1: Create a New Pluggable Database

## PDB Created
is_pdb_26424

The PDB was successfully created inside the Container Database and opened in READ WRITE mode.

## User Created Inside the PDB
ishimwe_plsqlauca_26424

## Privileges Granted
- CONNECT
- RESOURCE
- UNLIMITED TABLESPACE

The user was successfully created inside the PDB and configured for future PL/SQL practical sessions.

## Evidence Provided
Screenshots included in the screenshots folder:
- PDB creation command
- PDB open state confirmation (READ WRITE)
- User creation confirmation
- Privilege grants confirmation

---

# Task 2: Create and Delete a Temporary PDB

## Temporary PDB Name
is_to_delete_pdb_26424

## Actions Performed
1. Created the temporary PDB successfully.
2. Verified its existence.
3. Opened the PDB to confirm operational status.
4. Closed the PDB.
5. Dropped the PDB including associated datafiles.
6. Confirmed that it no longer exists.

## Evidence Provided
Screenshots included:
- Temporary PDB creation
- Verification query results
- PDB closure confirmation
- PDB deletion confirmation
- Final verification showing absence

---

# Task 3: Oracle Enterprise Manager (OEM)

OEM was accessed successfully using:

https://127.0.0.1:5500/em

Login Details:
- User: SYS
- Container: CDB$ROOT

The OEM dashboard displayed:
- Oracle database environment
- Container Database information
- Status of is_pdb_26424

A screenshot of the OEM dashboard is included in the repository.

---

# Issues Encountered

- ORA-00904: Invalid identifier – resolved by correcting the data dictionary view.
- ORA-65012: PDB already exists – resolved by verifying existing PDBs before creation.

All issues were resolved through independent troubleshooting.


---


# Integrity Statement

I confirm that this assignment was completed individually. All database operations, configurations, screenshots, and documentation reflect my own practical execution and understanding of Oracle Multitenant Architecture.
