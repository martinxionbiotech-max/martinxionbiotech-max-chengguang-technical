---
title: "C20 Capacity (Ampere-Hour) — Complete Guide"
---

# C20 Capacity (Ampere-Hour)

## What Is C20?

C20 measures a battery's energy storage capacity in **ampere-hours (Ah)** when discharged at a constant current over **20 hours** at **25degC**, until voltage reaches 10.5V. Example: a 65Ah (C20) battery delivers 3.25A for 20 hours.

C20 is the industry standard capacity rating — it represents steady, long-duration discharge rather than the short-burst power that CCA measures.

## Test Method (IEC 60095-1)

1. Battery is fully charged and stabilized at 25degC +/- 2degC
2. Discharge at C20 current = Rated Ah / 20 (e.g., 65Ah battery = 3.25A)
3. Voltage is monitored throughout the 20-hour period
4. Test ends when voltage reaches 10.5V or 20 hours elapse
5. **Pass:** Actual capacity >= 95% of rated capacity
6. Result is calculated as: C20 = Discharge current (A) x Discharge time (hours)

## Why C20 Matters

- **Energy storage:** How long can the battery run accessories with the engine off?
- **System sizing:** Does the battery capacity match the vehicle's electrical demand?
- **Deep cycle suitability:** Higher C20 = better tolerance for repeated discharge
- **Market specification:** Many markets specify battery requirements in Ah, not CCA

## Capacity vs. Discharge Rate

| Discharge Rate | Typical Capacity (% of C20) | Usage |
|:---:|:---:|---|
| C20 (20-hour) | 100% | Industry standard rating |
| C10 (10-hour) | ~93% | UPS/telecom rating |
| C5 (5-hour) | ~85% | Faster discharge — used for traction batteries |
| C1 (1-hour) | ~65% | High-rate discharge |

Batteries deliver less total energy at higher discharge rates due to internal resistance and electrolyte diffusion limitations (Peukert's Law).

## Chengguang Model Capacity Reference

| Model | C20 (Ah) | Vehicle Class |
|-------|:---:|---|
| 55B24 | 45 | Compact cars |
| 65D26 | 55-70 | Mid-large sedans, SUVs |
| 105D31 | 90 | Large SUVs, pickups |
| 95E41 | 100 | Large SUVs, diesel |
| 145G51 | 120-135 | Medium trucks |
| 190H52 | 200 | Heavy trucks, equipment |
| 60038 | 100 | European luxury/large |

[Browse All Models](https://data.chengguangenergy.com/battery-models/)

---

*Author: Chengguang Power Tech Engineering Team | Reference: IEC 60095-1*
