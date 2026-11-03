# Week 1 Lab · Same data, four architectures

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/meiliuwu/intro-geoai/blob/main/labs/week01-model-architectures/week01_lab_same_data_four_architectures.ipynb)

Notebook: [week01_lab_same_data_four_architectures.ipynb](week01_lab_same_data_four_architectures.ipynb) · Lecture: [Model architectures for GeoAI](../../lectures/week01-model-architectures/)

Students predict median house value for about 20,000 Californian census block groups and measure what each way of adding location buys.

| Part | What you do | Time |
| --- | --- | --- |
| 0 | Set up a reproducible notebook; load and map the data | 10 min |
| 1 | Linear and random-forest baselines, with and without coordinates | 10 min |
| 2 | Moran's I on residuals; random versus spatial-block cross-validation | 20 min |
| 3 | MLPs with no location, raw longitude and latitude, and a multi-scale sinusoidal encoding | 25 min |
| 4 | Show that a convolution equals a GIS focal filter, then let a CNN learn an edge kernel | 15 min |
| 5 | A GraphSAGE-style graph neural network on a k-nearest-neighbour graph; compare a classic GCN | 25 min |
| 6 | Compare all models on the same unseen region, map residuals, reflect and save | 10 min |

**Stretch tasks:** pretrained SatCLIP location embeddings, graph attention networks, buffered spatial cross-validation.

## Practical details

- **Runtime:** CPU is enough; the whole notebook runs in a few minutes.
- **Data:** Colab's built-in `sample_data/california_housing_*.csv`, derived from the 1990 US Census (Pace and Barry, 1997), so nothing needs downloading. Outside Colab the notebook falls back to scikit-learn's copy.
- **Libraries:** NumPy, pandas, Matplotlib, SciPy, scikit-learn and PyTorch, all preinstalled in Colab.

## Learning outcomes

- Explain why random cross-validation flatters spatial models, and run spatial-block cross-validation.
- Build an MLP with a multi-scale location encoding.
- Show that a CNN filter is a focal (moving-window) operation.
- Train a graph neural network by message passing in plain PyTorch.
