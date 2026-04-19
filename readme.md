# Photogrammetry Workflow with UAV Drone Survey Data for Peatland Restoration
 
**Author:** Hugh Martin  
**Date:** 19 April 2026  
**Status:** Working Document
 
---
 
## Introduction

### What is this Document?

This document provides a step-by-step workflow for using drone-mounted cameras to produce detailed maps and 3D models of peatland sites for a more effective restoration. 
 
The process is called **photogrammetry**: the science of making measurements and maps from photographs. When a drone flies a carefully planned grid over a landscape, taking hundreds of overlapping photographs, specialist software can stitch those photos together to reconstruct the landscape in extraordinary detail, producing maps, elevation models, and 3D visualisations that would take weeks and significant cost to achieve by traditional ground survey methods. 
 
This workflow is designed to be accessible to ecologists, land managers, and conservation practitioners who are not specialists in remote sensing or GIS (Geographic Information Systems; the digital tools used to manage and analyse spatial data). Every technical term is explained the first time it appears.

## What You Will Need
 
### Skills and Roles

*Roles | Description* 

*Mission Planner*: Someone who puts together the flight plan 
*GIS Specialist*: Someone who stiches together the photos 
*Drone Pilot*: Have to CAA accreditation 
 
** A single person can fulfil multiple roles.
 
### Equipment
 
- UAV drone with survey-grade camera (do camera specs matter? )
- RTK GNSS module or base station (see Step 7 for explanation?)
- Laptop or workstation with photogrammetry software installed
- Sufficient memory storage (drone surveys produce large files — typically XX)

### Software Dependencies
 
- Google Maps/Earth: free 
- LiDAR? Where does this come from/ free?
- Drone Specs? I assume not all drones are created equal
- WebODM: open-source photogrammetry processing; free (self-hosted)
- Agisoft Metashape: professional photogrammetry processing; paid licence (cost per annum)
- QGIS: open-source GIS software; free
- ArcGIS: professional GIS software; paid licence (cost per annum)
- HecRAS: 

Step 1: Desktop Scoping on Google Maps 

Step 2: Check Publicly Available LiDAR data 

Step 3: Decide on Site Area
- Extent of peatland vegetation
- Assumed hydrological unit
- Evidence of drainage or erosion

Step 4: Create UAV flight plan 

Step 5: Get Landowner Permissions 

Step 6: AirSpace Permissions 

Step 7: Fly Drone (Requires Physical Fitness) 
- Setting up the RTK Module/ Base Station

Step 8: Upload Photo Data 
- Discuss how this is done/ speed, compaction

Step 9: Run Photogrammetry Software (Web ODM, Agisoft Metashape)

Step 10: Download Outputs/ Orthomosaic Map, Digital Surface Model (DSM) 
- 3D Model/ 3D Tile Model

Step 11: Verify Data Visually 
- IF ERRORS, re-run photogrammetry and clean point cloud

Step 12: Create Service Hydrology Map (QGIS/ ArcGIS) 

Step 13: Create Slope Map

Step 14: Create Topographical Wetness Index 

Step 15: Advance Steps 
- Run ML image classification to identify erosion features (presently proprietary)
- Run Storm Event in Hec-ras using DSM

Step 16: Add Relevant Outputs to 3D Model/Digital Twin

Step 17: Use 3D Model/ Digital Twin to design restoration plan 

Step 18: Add publicly available relevant data to digital twin

STEP 19: SAVE SOME PEAT. 



