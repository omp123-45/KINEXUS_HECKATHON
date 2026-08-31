# Project Overview: Cost-Effective Alternative Catalysts for Industrial Hydrogenation

> **KINEXUS'25 Inter IIT NIT Hackathon — Problem Statement 2**
> In collaboration with **Godrej Industries**

---

## Problem Statement

Traditional industrial hydrogenation of vegetable oils relies on **Nickel (Ni) catalysts** that suffer from several critical drawbacks:

- **High cost** — Nickel is expensive and often requires modification with costly additives or alloying to control its excessive, non-selective activity.
- **Poor selectivity** — Ni catalysts hydrogenate all unsaturated fatty acids (C18:3, C18:2, and C18:1) indiscriminately, leading to over-saturation into stearic acid (C18:0) and excessive *trans*-fat formation (~30%).
- **Inferior cold-flow properties** — Products exhibit high pour points (+7 °C), making them unsuitable for lubricant applications.
- **Environmental concerns** — High metal loading (22 wt.%), rapid deactivation due to poisoning and coking, and hazardous waste generation.

## Proposed Solution

Replace Nickel with a **Supported Copper Catalyst (8 wt.% Cu/SiO₂)** prepared via the **Chemisorption–Hydrolysis (CH) method**, as described by Ravasio et al. (*Applied Catalysis A: General*, 233, 2002, 1–6).

---

## Core Objectives

### 1. Cost Reduction
Copper is significantly cheaper and more abundant than Nickel. The Cu/SiO₂ system eliminates the need for expensive additives or alloying, using only 8 wt.% metal loading versus 22 wt.% for commercial Nickel catalysts.

### 2. Enhanced Selectivity
The CH-prepared Cu/SiO₂ catalyst achieves **precise partial hydrogenation**:
- **Eliminates** the unstable trienic component (C18:3 → 0%)
- **Reduces** the dienic component (C18:2 from 21% → 3–5%)
- **Preserves** the desirable oleic acid (C18:1 up to 88%)
- **Prevents** over-saturation into stearic acid (C18:0 remains at ~2%)
- Limits *trans*-isomerization to ~15–20% (versus ~30% for Nickel)

### 3. Environmental Sustainability
- **Chromium-free** and **non-pyrophoric** system — safer for personnel and simplified waste compliance
- Reduced metal loading (8 wt.% Cu vs. 22 wt.% Ni) generates substantially less spent catalyst waste per metric ton of processed oil
- High catalyst stability and reusability reduces disposal frequency
- Products are biodegradable and suitable for eco-friendly applications

---

## Technical Innovation

### Chemisorption–Hydrolysis (CH) Preparation Method

The CH method produces a fundamentally different copper morphology compared to conventional Incipient Wetness (IW) impregnation:

| Property | CH Method | IW Method |
|---|---|---|
| Cu particle size | ~3.5 nm, well-formed crystallites | Larger, poorly dispersed particles |
| Surface morphology | Abundant "step and edge" sites, (111) microfacets | Almost-isolated copper sites |
| Cu surface area | ~55 m²/g_Cu (on TiO₂) | ~9 m²/g_Cu (on TiO₂) |
| Activity | ~100× higher turnover frequency | Baseline |
| H₂ dissociation | Highly efficient on stepped surfaces | Negligible activity |

The **step and edge sites** on the Cu nanoparticles are up to **100 times more active** for hydrogen dissociation than the isolated copper sites found on IW-prepared catalysts, as confirmed by FTIR spectroscopy of adsorbed CO (Boccuzzi et al., *J. Catal.* 165, 1997).

### Ex Situ Pre-Reduction Treatment

A critical innovation is the **ex situ pre-reduction at 270 °C** under hydrogen, performed in the absence of oil:
- Removes all water formed during the reduction process (Cu²⁺ → Cu⁰)
- Prevents water from trapping in catalyst pores, which would limit activity
- Produces a catalyst active towards both C18:3 and C18:2 hydrogenation while remaining inactive towards C18:1
- Ensures long-term industrial robustness and reusability

---

## Process Design

### Reactor Configuration
**Slurry-phase batch reactor** — the pre-reduced Cu/SiO₂ catalyst is added directly to the oil to form a slurry, maintained in suspension through constant agitation using a magnetic stirring head and stirring rod.

### Process Flow

```
Crude Vegetable Oil
        │
        ▼
┌──────────────────────┐
│  Feedstock Preparation│  Degumming + bleaching earth filter
│  (140–180 °C)        │  → removes phospholipids & impurities
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  Hydrogenation       │  High-purity H₂ at 6–20 bar
│  Reactor             │  Temperature: 150–220 °C (typically 180 °C)
│  (8 wt.% Cu/SiO₂)   │  Catalyst: pre-reduced Cu/SiO₂ slurry
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  Post-Processing     │  Plate & frame press filtration
│  & Recovery          │  Steam/vacuum deodorization
│                      │  Chiller → solidified fat pellets
└──────────────────────┘
```

### Operating Conditions

| Parameter | Value |
|---|---|
| Reaction Temperature | 180 °C (partial); 200–250 °C (complete saturation) |
| Hydrogen Pressure | 6–20 bar (partial); 20–50 bar (complete) |
| Metal Loading | 8 wt.% Cu on SiO₂ |
| Catalyst Pre-reduction | 270 °C under H₂ vacuum, ex situ |
| Reaction Time | 1–3 h (partial hydrogenation); 3–8 h (complete) |

---

## Performance Comparison: Cu/SiO₂ vs. Nickel

| Parameter | Nickel Catalyst | Cu/SiO₂ (CH Method) |
|---|---|---|
| **Cost** | Expensive; requires additives | Cheaper, abundant Cu; no additives |
| **Metal Loading** | 22 wt.% Ni | 8 wt.% Cu |
| **Selectivity** | Poor — hydrogenates C18:1 too | Excellent — preserves C18:1 |
| **C18:1 Content** | ~78% | Up to 88% |
| **C18:0 Formation** | 11% (significant) | ~2% (minimal) |
| ***trans*-Content** | ~30% | ~15–20% |
| **Pour Point** | +7 °C | −12 to −15 °C |
| **Deactivation** | Fast — poisoning, coking, sintering | Slow — stable Cu⁰ sites, water removed |
| **Safety** | Pyrophoric risk | Non-pyrophoric, Cr-free |
| **Waste/MT** | High (22 wt.% loading, fast deactivation) | Low (8 wt.% loading, reusable) |
| **Scalability** | Requires strict control | Efficient at moderate T & P |

---

## Product Quality

The hydrogenated oils produced using Cu/SiO₂ exhibit:

- **High oleic content** (up to 88% C18:1) — excellent oxidation stability
- **Low pour point** (−12 to −15 °C) — maintains fluidity at low temperatures
- **Viscosity characteristics** comparable to genetically modified very high oleic sunflower oil
- **Oxidation stability** maintained even after 4 h oxidation with air at 160 °C (AOM test)

| Oil Type | Viscosity 40 °C (cSt) | Viscosity 100 °C (cSt) | Viscosity Index |
|---|---|---|---|
| Mineral oil (100N) | 20.5 | 4.0 | 89 |
| Rapeseed oil | 36.2 | 8.2 | 211 |
| Cu-hydrogenated rapeseed oil | 45.5 | 9.4 | 196 |
| Cu-hydrogenated (after AOM) | 50.1 | 9.9 | 188 |

These properties make the product ideal for **biodegradable lubricants**, **biodiesel formulations**, and **eco-friendly industrial applications**.

---

## Versatility Across Feedstocks

The Cu/SiO₂ catalyst has been validated on multiple vegetable oil substrates:

- **Rapeseed oil triglycerides** and methylesters
- **Sunflower oil triglycerides**
- **Soyabean oil triglycerides** and methylesters

Consistent high-oleic selectivity was observed across all substrates tested.

---

## Research Foundation

This project is grounded in:

1. **Ravasio, N. et al.** (2002). "Environmental friendly lubricants through selective hydrogenation of rapeseed oil over supported copper catalysts." *Applied Catalysis A: General*, 233, 1–6. [DOI Link](https://www.sciencedirect.com/science/article/pii/S0926860X0200128X)
2. Catalyst characterization studies using TEM, FTIR of adsorbed CO, N₂O titration, and TPR profiling
3. Industrial benchmarking against commercial Nickel catalysts (Calsicat™ E472D, 22 wt.% Ni)

---

## Team

**Group Name:** Smooth Operators
**Unique ID:** A2D4F8F8

| Member |
|---|
| Boggarapu Harshith |
| Arkadip Ghara |
| Om Prakash Meghwal |
| Tanmay Kumar |
| Ayush Raj |
