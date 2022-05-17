# VLSI-Design-Flow
### Institute: Indraprastha Institute of Information Technology, Delhi
### Instructor: Dr Sneh Saurabh
### Course: VLSI Design Flow
### Semester: Winter 2022
### Abstract: RTL to GDS via Cadence Tools 

```
Tools
Cadence Simvision and IMC: RTL simulation and Code Coverage via Test Bench
Cadence Genus: Logic Synthesis 
Cadence Conformal: Equivalence Checking
Cadence Tempus: Static Timing Analysis
Cadence Innovus: Physical Design
```

```
Logic Block
If C=8’h00 TO 8’h59, 4-bit ring counter
C=8’h78 TO 8’h90, 4x1 Mux
C=8’hB1 TO 8’hED, frequency divider by 8
Else, bitwise A OR B
```

```
Part 1
RTL description and Test bench creation.
Run Simvision and IMC for simulation and code coverage report
Cadence Genus for Logic Synthesis
Cadence Conformal for Equivalence Checking
Cadence Tempus for STA wrt various .sdc files
Include Scan Chains for DFT and regenrate the netlist via Genus
```

```
Part 2
Cadence Conformal for equivalence checking on the new netist (not done by us)
Cadence Tempus for STA on the new netlist generated using various .sdc files after DFT
Cadence Innovus for Physical Design: -
-- FloorPlanning (Pin placement, Power Planning, Die and Core Area)
-- Placement (Global Placement, Legalization, Detailed Placement)
-- Routing (Global Routing, Detailed Routing)
-- Save the final GDS file
```


