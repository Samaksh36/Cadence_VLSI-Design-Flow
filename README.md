# VLSI-Design-Flow
### Institute: Indraprastha Institute of Information Technology, Delhi
### Instructor: Dr Sneh Saurabh
### Course: VLSI Design Flow
### Semester: Winter 2022
### Abstract: RTL to GDS via Cadence Tools 

bash```
### Tools
Cadence Simvision and IMC: RTL simulation and Code Coverage via Test Bench<br />
Cadence Genus: Logic Synthesis <br />
Cadence Conformal: Equivalence Checking<br />
Cadence Tempus: Static Timing Analysis<br />
Cadence Innovus: Physical Design<br />
end```

The idea is to begin with a logic block, and write its equivalent RTL module. We are using Verilog to describe the hardware.

We would be implementing the following logic block: -<br />
If C=8’h00 TO 8’h59, 4-bit ring counter<br />
C=8’h78 TO 8’h90, 4x1 Mux<br />
C=8’hB1 TO 8’hED, frequency divider by 8<br />
Else, bitwise A OR B<br />




