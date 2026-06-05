# MECH0073 — Aerosol Extraction System
*MEng Capstone Group Design Project | UCL Mechanical Engineering 2025–2026*
*In collaboration with Agfa Inkjet Solutions, Cambridge*

Industrial inkjet printers eject droplets at high frequency across a millimetre-scale print gap, 
generating fine airborne satellite ink droplets — a phenomenon known as ink misting. 
Left unmanaged, these aerosols contaminate machine internals and cause print defects. 
This project develops an aerosol extraction system that selectively captures low-inertia satellite droplets via downstream suction, 
without disturbing primary drop placement.

The design is underpinned by Euler–Lagrange CFD simulations in OpenFOAM, 
validated against a scaled experimental rig using high-speed shadowgraphy, 
and realised as a physical prototype compatible with Agfa printers. 

This repository serves as the central handover package for prototype evaluation and future project continuation.

## What's in this repo
- `CFD/` — OpenFOAM solver and post-processing scripts
- `CAD/` — Assembly and part drawings for the experimental rig and extractor prototype
- `Electronics/` — Arduino sensor control code and wiring schematics
- `Documentation/` — Risk assessments, Bill of Materials, Product Design Specification, and end-of-life plan
- `Reports/` — Final project report
