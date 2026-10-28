# CIDESI_BChips_2026

**Bajío – Semiconductor Industry Enabler Training Program**

Center for Engineering and Industrial Development (CIDESI)

## Semiconductor Training Roadmap

```mermaid
flowchart LR
    D["D<br/>Microdevice Design"]
    ME["M<br/>Electrical Metrology"]
    MA["M<br/>Applied Metrology"]
    F["F<br/>Chip Fabrication"]
    PI["PI<br/>IP & Product Design"]
    ATP["ATP<br/>Assembly, Testing & Packaging"]

    D --> ME --> MA --> F --> PI --> ATP

    style D fill:#F5A623,color:#fff,stroke:#D68C16
    style ME fill:#7050B8,color:#fff,stroke:#573894
    style MA fill:#17A3A7,color:#fff,stroke:#107E82
    style F fill:#EB3F72,color:#fff,stroke:#C52F5B
    style PI fill:#205E99,color:#fff,stroke:#164675
    style ATP fill:#43A53D,color:#fff,stroke:#2E7D32
```

*The diagram represents the learning roadmap.
Some training periods overlap.*

## Microdevice Design — Learning Modules

```mermaid
flowchart TD
    START(["Microdevice Design"])

    subgraph FOUNDATION["Phase 1 — Foundations"]
        M1["Module 1<br/>Introduction to Integrated Circuits<br/>and Design Flow"]
    end

    subgraph LAYOUT["Phase 2 — Physical Design"]
        M2["Module 2<br/>Basic Physical Design<br/>KLayout / CIDESI_TFS20"]
        M3["Module 3<br/>Design Rule Checking<br/>DRC Verification"]
        M4["Module 4<br/>Analog Block Layout<br/>CIDESI_CM05"]
    end

    subgraph FAB["Phase 3 — Fabrication & Integration"]
        M5["Module 5<br/>Fabrication Preparation"]
        M6["Module 6<br/>Integrated Practical Project<br/>RTD / CIDESI_TFS20"]
    end

    START --> M1 --> M2 --> M3 --> M4 --> M5 --> M6

    style START fill:#D99319,color:#fff,stroke:#B2760A
```

## Module Documentation

### Module 1 — Introduction to Integrated Circuits
Fundamentals of integrated circuits and the semiconductor design flow.

### Module 2 — Basic Physical Design
Introduction to KLayout and the CIDESI_TFS20 technology.

### Module 3 — Design Rule Checking (DRC)
Physical layout verification and design-rule compliance.

### Module 4 — Analog Block Layout
Analog layout development using CIDESI_CM05.

### Module 5 — Fabrication Preparation
Design preparation for semiconductor fabrication.

### Module 6 — Integrated Practical Project
RTD design and integration using CIDESI_TFS20.

## Tools and Technologies

- KLayout
- LTspice
- SPICE Simulation
- DRC Verification
- GDSII
- CIDESI_TFS20
- CIDESI_CM05

## Project Status

Training and technical documentation in progress.
