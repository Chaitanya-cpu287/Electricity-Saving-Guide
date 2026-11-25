# Electricity Consumption Optimization & Energy Saving Guide

An interactive, algorithmic web application designed to help households optimize residential electricity consumption and reduce utility costs by transitioning to lower tariff pricing tiers.

---

## Overview

Residential power utilities commonly employ tiered/slab pricing models where unit costs increase progressively as consumption thresholds are crossed. This project analyzes a household's device inventory, calculates baseline consumption, and models mathematical reduction plans to achieve specific target billing slabs.

---

## Optimization Strategies & Algorithms

The system implements three distinct algorithmic heuristics to recommend reduction targets:

1. **Greedy Optimization Strategy:**
   - Targets the highest wattage appliances (AC units, geysers, microwaves) first to achieve maximum unit reduction with minimum device count adjustments.
2. **Balanced Distribution Strategy:**
   - Evenly distributes runtime adjustments across all active household devices to preserve convenience and routine.
3. **Priority-Based Strategy:**
   - Evaluates device necessity (essential vs. non-essential) against power consumption curves to balance lifestyle impact with financial savings.

---

## Tariff Billing Structure

Modeled after standard residential slab pricing structures:

| Consumption Range (Units/Month) | Rate per Unit (INR) |
| :--- | :--- |
| **0 – 100 Units** | ₹3.00 |
| **101 – 200 Units** | ₹5.00 |
| **201 – 300 Units** | ₹8.00 |
| **301 – 400 Units** | ₹10.00 |
| **401 – 500 Units** | ₹12.00 |
| **Above 500 Units** | ₹15.00 |

---

## Supported Household Appliances

- Air Conditioner (AC)
- Ceiling Fans
- Television
- Water Geyser
- Refrigerator
- Washing Machine
- Microwave Oven
- Electric Iron
- Laptop / Desktop Workstations
- LED & Incandescent Lighting

---

## Tech Stack & Architecture

- **Frontend & UI:** HTML5 Semantic Elements, CSS3 Grid/Flexbox Layouts
- **Computation Engine:** Client-side Vanilla JavaScript (ES6+)
- **Execution:** Zero-dependency standalone browser application

```
Electricity-Saving-Guide/
├── Electricity Saving Guide/
│   ├── index.html       # Single-page web application & computation logic
│   └── README.md        # Legacy directory guide
├── .gitignore           # OS and IDE ignore rules
└── README.md            # Root technical documentation
```

---

## Quickstart

No external build tools or server runtimes are required.

1. Clone repository:
   ```bash
   git clone https://github.com/Chaitanya-cpu287/Electricity-Saving-Guide.git
   cd Electricity-Saving-Guide
   ```
2. Open the application directly in any modern web browser:
   - On Windows: double-click `Electricity Saving Guide/index.html` or run `start "Electricity Saving Guide/index.html"`
   - On Linux/macOS: run `xdg-open "Electricity Saving Guide/index.html"` or `open "Electricity Saving Guide/index.html"`
