# HERMES — Halo EaRth Moon rElay Satellites

**Pre-Phase A Mission Report**  
**Master of Science in Space Engineering**  
**University of Pisa** — Academic Year 2023/2024

---

## Mission Overview
![Dashboard Preview](HERMES poster.png)
**HERMES** is a commercial constellation of four satellites in a southern **Halo orbit around the Earth-Moon L2 point (EML2)**. It provides:

- Continuous high-data-rate relay communications between Earth and the **lunar far side**
- Lunar Navigation Satellite System (LNSS) for precise positioning of rovers, landers, and future bases
- Support for upcoming lunar missions (NASA Artemis, CNSA, ISRO, ESA, and private operators)

**Key Features**
- Data rates up to **5 Gbps** (Moon → Spacecraft) and **1 Gbps** (Spacecraft → Earth)
- Constant visibility to both Earth and the lunar far side
- Scalable architecture — easily expandable with northern Halo satellites

---

## Selected Architecture

**4 identical satellites** in a **southern Halo orbit** around EML2 (Z-amplitude ≈ 25 000 km).

**Why this architecture?**
- Minimum number of satellites for reliable LNSS triangulation
- Excellent geometric dilution of precision (GDOP)
- Low station-keeping cost
- Strong heritage from Queqiao and future missions (LUMIO, EQUULEUS)

**Orbit parameters**
- Period: ≈ 15 days
- Designed for central-southern far-side coverage (emphasis on South Pole)

---

## Satellite Design Highlights

Each satellite (~200–290 kg dry mass):

**Telecommunications**
- 9 primary antennas on Earth/Moon-facing panel + 8 redundancy antennas
- COTS patch arrays (S/X/Ka/L bands)
- LNSS navigation signal generation with atomic clocks

**Propulsion**
- Chemical (hydrazine) for halo insertion
- Electric Hall thrusters (Krypton) for station-keeping

**Attitude Determination & Control**
- 4 reaction wheels + 16 × 1 N hydrazine thrusters
- Pointing accuracy ≤ ±5°

**Power & Thermal**
- ~2.5 m² GaAs solar arrays
- 2 × 200 Wh Li-ion batteries with heaters
- Passive thermal control (MLI + Aluminized Kapton)

---

## Mission Budgets (Summary)

| Item                  | Value                          |
|-----------------------|--------------------------------|
| Dry mass (per sat)    | 200–290 kg                     |
| Propellant            | ~76 kg                         |
| Peak power            | 900–1030 W                     |
| Lifetime              | ≥ 7 years (+50% extension)     |
| Launcher              | Falcon 9 (2029)                |
| Estimated total cost  | ~1 B€ (10-year mission)        |

---

## Future Expansion

HERMES is explicitly designed for growth:
- Add 4+ satellites in a **northern Halo orbit** to double coverage and capacity
- Enables lunar GPS, high-bandwidth lunar internet, and permanent base support

---

## Repository Contents

- `Report/` — Full Pre-Phase A PDF + appendices
- `Poster/` — Poster of the Mission



---

*Last updated: May 2024*
