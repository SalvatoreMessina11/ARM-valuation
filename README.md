# Arm Holdings — valuation research

An academic valuation project combining intrinsic, relative, and simulation-based approaches to examine Arm Holdings plc. The repository contains Jupyter notebooks and supporting analysis.

## Research approaches

| Approach | What is examined |
| --- | --- |
| Intrinsic valuation | Discounted cash-flow projections, including R&D capitalization and amortization assumptions. |
| Simulation | Revenue scenarios modelled with geometric Brownian motion to explore sensitivity to drift and volatility. |
| Relative valuation | Peer-group P/S and EV/S multiples with regression-based comparisons and heteroscedasticity-robust inference. |
| Risk inputs | OLS-based estimation of beta and comparison of model drivers with peer returns. |

## Where to start

- [Intrinsic valuation notebook](arm_intrinsic_valuation_complete.ipynb) — DCF assumptions, projections, and scenario analysis.
- [Relative valuation notebook](ARM_RELATIVE_VALUATION.ipynb) — peer multiples and regression analysis.

The notebooks are research artefacts. Review their assumptions and data dates before interpreting any numerical output; historical model results are not current investment recommendations.

## Context

This work draws on concepts from Aswath Damodaran's Advanced Valuation course (NYU Stern, 2025). The methods illustrate how valuation depends on explicit assumptions, model choice, and uncertainty.
