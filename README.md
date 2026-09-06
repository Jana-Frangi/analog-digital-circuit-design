# Analog & Digital Circuit Design

A collection of analog and digital electronics design projects completed as part of **EECE 311 – Electronic Circuits** at the **American University of Beirut (AUB)**.

The projects progress from transistor-level MOSFET analysis and amplifier design to operational amplifiers, active filters, CMOS digital logic, and arithmetic circuits. Designs were analyzed theoretically and verified through circuit simulation.

---

## 🔬 Project Overview

### 1. Common-Source PMOS Amplifier
**Report:** [`HW1_CS_PMOS_Amplifier.pdf`](HW1_CS_PMOS_Amplifier.pdf)

Design and analysis of a common-source PMOS amplifier using the **GF180MCU CMOS technology**.

Key work included:
- MOSFET parameter extraction
- DC operating-point analysis
- Transistor sizing
- Small-signal gain analysis
- LTspice simulation and verification
- Comparison between theoretical and simulated behavior

---

### 2. High-Frequency Common-Source Analysis
**Report:** [`HW_2_High_Frequency_CS_Analysis.pdf`](HW_2_High_Frequency_CS_Analysis.pdf)

High-frequency analysis of MOS amplifier circuits with emphasis on parasitic capacitances and frequency response.

Key concepts:
- Small-signal MOSFET modeling
- High-frequency transistor behavior
- Open-circuit time constant (OCTC) analysis
- Dominant poles
- Bandwidth estimation
- LTspice AC simulation

---

### 3. Cascoded Common-Source Amplifier
**Report:** [`HW_3_Cascoded_CS_Amplifier.pdf`](HW_3_Cascoded_CS_Amplifier.pdf)

Design and analysis of a **cascoded common-source amplifier** to improve voltage gain and output resistance.

Key work included:
- Cascode transistor configuration
- Biasing and operating-point design
- Small-signal gain derivation
- Output resistance analysis
- Frequency-response analysis
- Simulation-based verification

---

### 4. Two-Stage CMOS Operational Amplifier
**Report:** [`HW4_Two_Stage_CMOS_OpAmp.pdf`](HW4_Two_Stage_CMOS_OpAmp.pdf)

Design of a **two-stage CMOS operational amplifier** with frequency compensation.

The project explores:
- Differential input stages
- Active loads and current mirrors
- Second-stage amplification
- Transistor sizing and biasing
- Open-loop voltage gain
- Frequency compensation
- Stability and phase margin
- Gain-bandwidth behavior
- LTspice verification

---

### 5. Active RC Filters
**Report:** [`HW5_Active_RC_Filters.pdf`](HW5_Active_RC_Filters.pdf)

Design and analysis of **active RC filter circuits** using operational amplifiers.

Topics include:
- Transfer-function analysis
- Frequency-response design
- Active filter topologies
- Pole and zero behavior
- Stability considerations
- Bode plots
- Simulation and theoretical verification

---

### 6. CMOS Digital Logic & Ripple-Carry Adder
**Report:** [`HW6_CMOS_Logic_Adder.pdf`](HW6_CMOS_Logic_Adder.pdf)

Transistor-level design of **CMOS digital logic circuits**, progressing toward a multi-bit arithmetic system.

The project includes:
- CMOS transistor-level logic design
- Logic gate implementation
- Combinational circuit design
- Full-adder architecture
- Propagation through cascaded stages
- 4-bit ripple-carry adder
- Functional simulation and verification

---

## 🛠️ Technologies & Tools

- **GF180MCU CMOS Technology**
- **LTspice**
- **KiCad**
- CMOS transistor-level design
- Analog circuit analysis
- Small-signal modeling
- Frequency-response analysis
- Operational amplifier design
- Active filter design
- Digital logic design

---

## 📚 Engineering Concepts

This project collection demonstrates practical experience with:

**Analog Electronics**
- MOSFET device modeling
- Biasing and transistor sizing
- Common-source amplifiers
- Cascode architectures
- Small-signal analysis
- Frequency response and bandwidth
- Operational amplifier design
- Feedback and stability
- Active filters

**Digital Electronics**
- CMOS logic
- Transistor-level digital design
- Combinational logic
- Full adders
- Ripple-carry arithmetic circuits

---

## 📂 Repository Structure

```text
analog-digital-circuit-design/
│
├── HW1_CS_PMOS_Amplifier.pdf
├── HW_2_High_Frequency_CS_Analysis.pdf
├── HW_3_Cascoded_CS_Amplifier.pdf
├── HW4_Two_Stage_CMOS_OpAmp.pdf
├── HW5_Active_RC_Filters.pdf
├── HW6_CMOS_Logic_Adder.pdf
└── README.md
