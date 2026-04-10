# HERMES: Halo EaRth Moon rElay Satellites

**Pre-Phase A Mission Report**  
**Master of Science in Space Engineering**  
**University of Pisa**  Academic Year 2023/2024  

---

## Mission Overview

![Dashboard Preview](HERMES_poster.png)

**HERMES** is a commercial constellation of four satellites operating in a **southern Halo orbit around the Earth–Moon L2 point (EML2)**. The mission provides:

- Continuous, high-data-rate relay communications between Earth and the **lunar far side**
- A **Lunar Navigation Satellite System (LNSS)** for precise positioning of rovers, landers, and future infrastructure
- Support for upcoming lunar missions (NASA Artemis, CNSA, ISRO, ESA, and private operators)

### Key Features

- Data rates up to **5 Gbps** (Moon → spacecraft) and **1 Gbps** (spacecraft → Earth)  
- Continuous visibility of both Earth and the lunar far side  
- Scalable architecture with potential for expansion  

---

## Selected Architecture

The system consists of **four identical satellites** placed in a **southern Halo orbit around EML2**, with a Z-amplitude of approximately **25,000 km**.

### Why this architecture?

- Minimum number of satellites required for reliable LNSS triangulation  
- Excellent geometric dilution of precision (GDOP)  
- Reduced station-keeping requirements  
- Heritage from missions such as *Queqiao*, *LUMIO*, and *EQUULEUS*  

### Orbit Characteristics

- Orbital period: ~15 days  
- Optimized for **central and southern far-side coverage**, with emphasis on the lunar South Pole  

---

## Satellite Design Highlights

Each satellite has a dry mass of approximately **200–290 kg** and includes:

### Telecommunications

- 9 primary antennas (Earth- and Moon-facing panels) + 8 redundant antennas  
- COTS patch arrays (S, X, Ka, and L bands)  
- LNSS navigation signal generation using atomic clock technology  

### Propulsion

- Chemical propulsion (hydrazine) for halo orbit insertion  
- Electric propulsion (Krypton Hall thrusters) for station-keeping  

### Attitude Determination & Control System (ADCS)

- 4 reaction wheels  
- 16 × 1 N hydrazine thrusters  
- Pointing accuracy: ≤ ±5°  

### Power & Thermal Control

- ~2.5 m² GaAs solar arrays  
- Two 200 Wh Li-ion batteries with thermal heaters  
- Passive thermal control using MLI and aluminized Kapton  

---

## Mission Budgets (Summary)

| Parameter                | Value                          |
|--------------------------|--------------------------------|
| Dry mass (per satellite) | 200–290 kg                     |
| Propellant               | ~76 kg                         |
| Peak power               | 900–1030 W                     |
| Lifetime                 | ≥ 7 years (+50% extension)     |
| Launcher                 | Falcon 9 (2029)                |
| Estimated total cost     | ~1 billion € (10-year mission)  |

---

## Future Expansion

The HERMES architecture is designed for scalability:

- Addition of **4+ satellites** in a **northern Halo orbit**  
- Increased coverage and redundancy  
- Enables:
  - Lunar GPS-like navigation  
  - High-bandwidth lunar communications network  
  - Continuous support for lunar bases  

---

## Repository Contents

- `Report/` — Full Pre-Phase A report (PDF + appendices)  
- `Poster/` — Mission poster  

---

*Last updated: May 2024*
