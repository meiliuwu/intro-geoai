# Week 3 · Environmental monitoring

**Big question:** can we trust a data-driven model where we have no observations?

**Slides:** in preparation · **Pre-reading:** [Week 3 readings](../../readings/week03-environmental-monitoring.md) · **Lab:** [Forecasting Scottish river flow](../../labs/week03-environmental-monitoring/)

## Learning outcomes

1. Explain how deep learning complements process-based environmental models (hybrid modelling).
2. Train an LSTM rainfall–runoff model and evaluate it with hydrological skill scores such as Nash–Sutcliffe efficiency.
3. Evaluate spatial generalisation with leave-catchments-out validation and an area of applicability.

## Lecture highlights

- **Hook:** a flood-warning map beside a river with no gauge. Poll: would you trust an AI flood warning here?
- **Concept bursts:** detect, map and forecast as the three monitoring tasks; LSTMs for environmental time series; hybrid physics–ML models; extrapolation and the area of applicability.
- **Signature activity, "ungauged challenge":** groups design a monitoring system for one variable (river flow, air quality, peatland condition, forest loss) with sparse sensors, and state how they would validate it in unseen places.
- **Ethics minute:** who is accountable when an AI warning is wrong, and what is the carbon cost of training large Earth-system models?
