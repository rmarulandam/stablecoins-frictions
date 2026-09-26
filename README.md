# Stablecoins & International Trade Review

This directory contains a comprehensive academic critical review evaluating **Chapter 2: "Frictions in international trade and the potential use and limitations of stablecoins"** from the World Trade Organization (WTO) flagship report *Stablecoins and world trade: Emerging role, opportunities and challenges* (2026).

## Overview

The reviewed chapter analyzes how fiat-backed stablecoins (predominantly USD-denominated assets such as USDT and USDC) interact with cross-border payment frictions and global trade finance mechanisms. This critical review investigates the fundamental economic distinction between high-velocity **payment and settlement rails** (atomic 24/7 transfers, smart contracts) and institutional **trade finance functions** (working capital credit, risk mitigation under ICC UCP 600, and legal collateralization of physical goods).

## Authors of the Review

- **Andrés Arias**
- **Catalina Jaramillo**
- **Rafael Marulanda**

*Pontificia Universidad Javeriana*

---

## Directory Contents

| File | Description |
| :--- | :--- |
| [`resena_wto_stablecoins.tex`](file:///d:/repos/master-tesis-economy/Bitcoin-economics/06_stablecoins/resena_wto_stablecoins.tex) | Full academic critical review article in LaTeX format. |
| [`resena_wto_stablecoins.pdf`](file:///d:/repos/master-tesis-economy/Bitcoin-economics/06_stablecoins/resena_wto_stablecoins.pdf) | Compiled PDF of the academic critical review. |
| [`stablecoins_wto_2.pdf`](file:///d:/repos/master-tesis-economy/Bitcoin-economics/06_stablecoins/stablecoins_wto_2.pdf) | Source Chapter 2 extracted from the official WTO report (2026). |
| [`1789575751382.pdf`](file:///d:/repos/master-tesis-economy/Bitcoin-economics/06_stablecoins/1789575751382.pdf) | Full 50-page WTO Flagship Report (*Stablecoins and world trade: Emerging role, opportunities and challenges*). |
| [`.gitignore`](file:///d:/repos/master-tesis-economy/Bitcoin-economics/06_stablecoins/.gitignore) | Local Git ignore rules for LaTeX auxiliary files. |

---

## Key Synthesis & Analytical Highlights

1. **Payment & Settlement Velocity**:
   - **Continuous Availability (24/7/365)**: Near real-time atomic settlement eliminates batch processing cut-offs and multi-day correspondent banking delays ($T+2$ to $T+5$), shortening the corporate cash conversion cycle.
   - **Corridor Efficiencies**: Transferring $500 costs 1–3% ($5–$15) via stablecoin rails versus 4–6% ($20–$30) through legacy banking networks (Adams et al., 2023). In the US–Mexico corridor, remittance costs drop below 1% (Dolev, 2025).

2. **The Structural Boundary with Trade Finance**:
   - **Credit vs. Settlement**: Stablecoins function as base monetary settlement tokens ($M_0$), but do not create endogenous credit or working capital loans ($M_2$).
   - **Risk Mitigation & Legal Title**: Letters of Credit (LCs) governed by ICC UCP 600 rules provide legally enforceable guarantees and cargo collateralization that smart contracts cannot autonomously replicate without legal frameworks (e.g., UK ETDA 2023, UNCITRAL MLETR).
   - **Goods vs. Services Divergence**: Digitally delivered services adopt stablecoin settlement immediately, while physical merchandise trade remains anchored to structured trade credit.

3. **Macroeconomic & Regulatory Constraints**:
   - **Fiat On/Off-Ramp Bottleneck**: Net transaction costs vary from 0.3% to ~9% (Di Iorio et al., 2026), driven primarily by domestic foreign exchange spreads and gateway fees.
   - **Monetary Sovereignty & Dollarization**: Massive adoption of foreign USD-stablecoins in emerging economies threatens domestic monetary transmission, central bank seigniorage, and capital stability.

---

## Compilation Instructions

To recompile the document locally, use `pdflatex` or `latexmk`:

```bash
# Compile the review paper
pdflatex -interaction=nonstopmode resena_wto_stablecoins.tex
```
