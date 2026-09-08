# Design and Development of Open Jet Facility

### 🏆 Best Project Award — 2023

**Awarded for:** *Design and Development of Open Jet Facility*

### Experimental and CFD Investigation of Mach 2.6 Aerospike and Convergent–Divergent (CD) Nozzles

This project involved the **design, development, fabrication, and experimental investigation of an open-jet supersonic facility** for studying aerospike and convergent–divergent (CD) nozzle flows. Analytical nozzle design, CAD, fabrication, instrumentation, Schlieren/Shadowgraph visualization, and CFD simulations were integrated to characterize and validate supersonic flow behavior.

---

## Objectives

- Design a **Mach 2.6 aerospike nozzle** using the **Angelino Method**.
- Design a **Mach 2.6 contoured CD nozzle** using the **Method of Characteristics (MOC)**.
- Develop and fabricate the **nozzles, settling chamber, transition section, and connecting flange**.
- Integrate a **supersonic open-jet experimental facility** with pressure measurement and flow-visualization systems.
- Measure nozzle pressure distributions and visualize **shock waves, expansion waves, shear layers, and shock diamonds**.
- Perform **2D compressible-flow CFD simulations** and validate the numerical results against experiments.

---

## Work Performed

### 1. Nozzle Design

- Designed the **Mach 2.6 aerospike and CD nozzles** based on compressible-flow theory.
- Generated the CD-nozzle contour using the **Method of Characteristics**.
- Developed the aerospike contour using the **Angelino method**.
- Designed the nozzle for a pressure ratio corresponding to a **Mach 2.6 exit condition**.

### 2. CAD & Fabrication

- Developed CAD models of the:
  - Aerospike nozzle
  - CD nozzle
  - Settling chamber
  - Transition flange
  - Connecting flange
- Supported **manufacturing, assembly, and integration** of the experimental hardware.

### 3. Experimental Facility

- Developed the open-jet supersonic test facility with:
  - Settling chamber
  - Pressure regulation and flow-control system
  - Pressure taps and sensors
  - NI-DAQ/LabVIEW-based data-acquisition system
  - Z-type Schlieren system
  - Shadowgraph visualization system

### 4. Experimental Investigation

- Conducted experiments at different reservoir pressures, primarily **5.5 bar and 6.5 bar**.
- Acquired pressure data along the CD nozzle using multiple pressure ports.
- Used Schlieren and Shadowgraph imaging to visualize:
  - Oblique shocks
  - Expansion waves
  - Shock diamonds
  - Shear layers
- Converted measured pressure data into **pressure-ratio and Mach-number distributions**.

### 5. CFD Analysis

- Performed **2D compressible-flow CFD simulations** of the aerospike and CD nozzles using **ANSYS Fluent and SU2**.
- Investigated pressure, Mach-number, and density distributions.
- Compared CFD flow structures with experimental pressure measurements and Schlieren observations.
- Studied the effect of nozzle pressure ratio on shock structure and jet development.

---

## Key Results

- Achieved an experimental exit Mach number of **2.58** at **6.5 bar**, compared with the design value of **Mach 2.6**.
- The measured Mach 2.58 corresponds to approximately **0.7% deviation** from the design value.
- At **5.5 bar**, the measured exit Mach number was approximately **2.338**, corresponding to a strongly over-expanded jet condition.
- Experimental observations captured the formation of **shock diamonds and shear layers** downstream of the nozzle.
- CFD and Schlieren results showed **good qualitative agreement** in the location and development of major shock structures.
- Experimental and CFD pressure/Mach-number distributions showed **good agreement** for the investigated pressure conditions.
- The study demonstrated the influence of **nozzle pressure ratio on shock location, expansion behavior, and exit Mach number**.

The report specifically notes that the 6.5-bar experiment produced an exit Mach number of 2.58 against the designed 2.6, while the 5.5-bar case produced 2.338 because of the strongly over-expanded operating condition. :contentReference[oaicite:0]{index=0}

---

## Conclusion

The project successfully developed an **open-jet supersonic experimental facility** and demonstrated an integrated approach combining **analytical nozzle design, CAD, fabrication, experimentation, optical flow visualization, pressure measurements, and CFD**.

The experimental results successfully captured the major compressible-flow features of the nozzle and over-expanded jet. The measured **Mach 2.58 at 6.5 bar** was close to the **Mach 2.6 design target**, while comparison with CFD showed good agreement in the overall pressure and flow-field characteristics. :contentReference[oaicite:1]{index=1}

The developed facility provides a platform for further investigation of **supersonic nozzle flows, aerospike performance, shock structures, and experimental–CFD validation**.

---

## Tools & Technologies

**Design & Analysis**
- Method of Characteristics (MOC)
- Angelino Method
- Compressible Flow Theory

**CAD**
- Siemens NX

**CFD**
- ANSYS Fluent
- SU2
- RANS
- Spalart–Allmaras

**Programming & Post-Processing**
- Python
- MATLAB

**Experimental**
- NI-DAQ
- LabVIEW
- Pressure Sensors
- Z-type Schlieren
- Shadowgraph

