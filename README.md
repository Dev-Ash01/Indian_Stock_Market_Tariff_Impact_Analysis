# Sector Vulnerability Analysis – Impact of 2025 US Tariffs on Indian Exports

## 1. Project Overview

On 27 August 2025, the US doubled import duties on a wide range of Indian goods, pushing effective tariff rates on several product lines close to ~50–60%. Labour-intensive sectors such as textiles, gems & jewellery, chemicals and parts of auto were hit hardest, while strategic sectors like **pharmaceuticals and semiconductors were exempt**.

This project quantifies the **sector-wise revenue risk** for India’s top export categories to the US and identifies which industries can **absorb the shock** versus which are structurally exposed.

**Core sectors covered:**

- Textiles & Apparel  
- Gems & Jewellery  
- Pharmaceuticals (Exempt)  
- Auto Components  
- Chemicals (tariffed subset: organic, agro, misc. chemicals)

---

## 2. Problem Statement

> “Quantify the potential revenue loss for India’s top 5 export sectors (Textiles, Gems/Jewellery, Pharma, Auto, Chemicals) under the new 2025 tariff regime and identify which sectors have the resilience to absorb the cost.”

We focus on four dimensions:

1. **US dependence** of each sector (share of exports going to the US)  
2. **Change in landed cost** at 10% vs 50% US tariffs compared with competitors (e.g., Vietnam, Bangladesh, Mexico)  
3. **Profit margins and price elasticity**, to determine volume loss and margin compression  
4. Identification of **“exempt” or resilient segments** where investors can reallocate capital (e.g., pharma, semiconductors)

---

## 3. Data & Assumptions

### 3.1 Export exposure

| Sector                    | Global Exports (USD Bn) | Exports to US (USD Bn) | US Share of Sector Exports |
|---------------------------|------------------------:|------------------------:|---------------------------:|
| Textiles & Apparel        | 34.4                   | 10.0                   | ~29%                      |
| Gems & Jewellery          | 28.5                   | 10.0                   | ~30%+                     |
| Pharmaceuticals           | 26.5                   | 9.0                    | ~33–35%                   |
| Auto Components           | 22.9                   | 7.3                    | ~30%+                     |
| Chemicals (tariffed subset)| 63.5 (all chemicals)  | 6.0 (tariffed sub-set) | ~23% (for at-risk portion)|

Values are based on FY23–25 public trade data and rounded for scenario analysis.

### 3.2 Tariff scenarios

We model an **average effective tariff** as:

- **Baseline (pre-2025)**: 10%  
- **New regime (2025)**: 50%  

Pharmaceuticals and semiconductors are treated as **exempt** (no tariff increase).

### 3.3 Margin assumptions

| Sector               | Assumed Export EBIT Margin |
|----------------------|----------------------------|
| Textiles & Apparel   | 10%                        |
| Gems & Jewellery     | 15%                        |
| Pharmaceuticals      | 20%                        |
| Auto Components      | 12%                        |
| Chemicals            | 15%                        |

These are stylised figures used for stress testing, not company-specific margins.

---

## 4. Methodology

### 4.1 Landed cost model

For each sector, landed cost in the US is calculated as:

\[
\text{Landed Cost} = \text{FOB Price} \times (1 + \text{Tariff Rate})
\]

To capture competitiveness vs rival exporters (e.g., Vietnam, Bangladesh, Mexico), we compare:

- **India (Old)**: FOB\_IN × (1 + 10%)  
- **India (New)**: FOB\_IN × (1 + 50%)  
- **Competitor**: FOB\_COMP × (1 + 10%)

Example (Textiles):

- Indian FOB price: 100  
- Competitor FOB price: 95 (slightly cheaper)  

Then:

- India, old tariff: 100 × 1.10 = 110  
- Competitor: 95 × 1.10 = 104.5  
- India, new tariff: 100 × 1.50 = 150  

This moves India from ~5% to ~44% more expensive than the competitor on landed cost.

### 4.2 Revenue-at-risk model

For each sector:

1. Start with **US export value** (USD Bn).  
2. Apply an **assumed volume loss %** under the 50% tariff scenario.  
3. Compute **Revenue-at-Risk**:

\[
\text{Revenue Loss} = \text{US Exports} \times \text{Volume Loss \%}
\]

4. Compute **extra duties** on surviving exports:

\[
\text{Extra Duty} = \text{US Exports} \times (1 - \text{Volume Loss \%}) \times 40\%
\]

(40% = 50% new tariff – 10% old tariff)

### 4.3 Scenario selection

Base-case volume-loss assumptions:

| Sector                | US Exports (USD Bn) | Volume Loss % under 50% Tariff |
|-----------------------|--------------------:|--------------------------------:|
| Textiles & Apparel    | 10.0                | 35%                             |
| Gems & Jewellery      | 10.0                | 50%                             |
| Pharmaceuticals       | 9.0                 | 0% (exempt)                     |
| Auto Components       | 7.3                 | 20%                             |
| Chemicals (tariffed)  | 6.0                 | 25%                             |

These percentages are calibrated to recent observed declines in US-bound exports and are intended as **stress-test scenarios**, not precise forecasts.

---

## 5. Key Results

### 5.1 Revenue-at-risk

| Sector                | US Exports (USD Bn) | Volume Loss % | Revenue-at-Risk (USD Bn) |
|-----------------------|--------------------:|--------------:|--------------------------:|
| Textiles & Apparel    | 10.0                | 35%           | 3.5                       |
| Gems & Jewellery      | 10.0                | 50%           | 5.0                       |
| Pharmaceuticals       | 9.0                 | 0%            | 0.0                       |
| Auto Components       | 7.3                 | 20%           | 1.5                       |
| Chemicals (tariffed)  | 6.0                 | 25%           | 1.5                       |

Total **direct export revenue at risk** across the five sectors is approximately **USD 11.5 billion** in the first-year shock scenario.

### 5.2 Additional duty burden

| Sector                | Surviving US Exports (USD Bn) | Extra Duty at 40% (USD Bn) |
|-----------------------|------------------------------:|----------------------------:|
| Textiles & Apparel    | 6.5                           | 2.6                         |
| Gems & Jewellery      | 5.0                           | 2.0                         |
| Pharmaceuticals       | 9.0                           | 0.0                         |
| Auto Components       | 5.84                          | 2.3                         |
| Chemicals (tariffed)  | 4.5                           | 1.8                         |

Roughly **USD 8.7 billion** in extra duties is levied on surviving exports, which will be partially absorbed in margins and partially passed on to US buyers.

---

## 6. Sector Vulnerability & Resilience

### 6.1 Vulnerability scorecard

| Sector             | US Dependence | Tariff Hit | Volume Loss | Margin Buffer | Overall Risk |
|--------------------|--------------:|-----------:|------------:|--------------:|-------------:|
| Gems & Jewellery   | High          | Very High  | Very High   | Medium        | **High**     |
| Textiles & Apparel | High          | Very High  | High        | Low           | **High**     |
| Chemicals          | Medium        | High       | Medium      | Medium        | **Medium**   |
| Auto Components    | Medium        | High       | Medium      | Medium        | **Medium**   |
| Pharma (Exempt)    | High          | None       | None        | High          | **Low**      |

### 6.2 Exempt / defensive sectors (“Where to hide”)

- **Pharmaceuticals (Generics + Formulations)**
  - Directly **exempt** from 2025 tariff hikes.  
  - US demand is driven by healthcare needs and ANDA pipelines; relatively inelastic.  
  - High IP and regulatory barriers create pricing power and switching costs.  
  - Result: **natural defensive / safe-haven sector** in this tariff shock.

- **Potentially Defensive Niches**
  - **Semiconductor design, IT services, embedded engineering** : mostly services, not goods; outside the scope of these tariffs.  
  - **Specialty chemicals with strong IP/tech content** may retain pricing power even with tariffs.

---


