# Week 3 Lab · Forecasting Scottish river flow

**Status:** in preparation. Lecture: [Environmental monitoring](../../lectures/week03-environmental-monitoring/)

## Planned outline

1. Load a prepared subset of [CAMELS-GB](https://doi.org/10.5194/essd-12-2459-2020) (about 50 catchments: daily rainfall, temperature, potential evapotranspiration and river flow, plus catchment attributes).
2. Fit persistence and linear baselines.
3. Train one LSTM across all catchments, with catchment attributes as extra inputs.
4. Evaluate in time (held-out years) and in space (held-out catchments) with Nash–Sutcliffe efficiency.
5. Map skill per catchment and discuss where the model fails, such as groundwater-fed rivers.

**Stretch:** rerun the experiment with [NeuralHydrology](https://github.com/neuralhydrology/neuralhydrology).

**Data note:** CAMELS-GB (Coxon et al., 2020) is published under the Open Government Licence through the [UKCEH Environmental Information Data Centre](https://catalogue.ceh.ac.uk/documents/8344e4f3-d2ea-44f5-8afa-86d2987543a9). A small, attributed subset will be stored in this repository so the lab loads quickly.
