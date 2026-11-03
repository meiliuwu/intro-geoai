# Labs

Every lab is a Google Colab notebook that runs in a web browser: no installation is needed, only a Google account. Click a badge to open a lab, then choose **File → Save a copy in Drive** so your changes are kept.

| Week | Lab | Data and tools | Open |
| --- | --- | --- | --- |
| 1 | [Same data, four architectures](week01-model-architectures/) | California census block groups; scikit-learn, PyTorch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/meiliuwu/intro-geoai/blob/main/labs/week01-model-architectures/week01_lab_same_data_four_architectures.ipynb) |
| 2 | [Seeing land cover from space](week02-remote-sensing/) | EuroSAT; TorchGeo; Prithvi / TerraTorch | In preparation |
| 3 | [Forecasting Scottish river flow](week03-environmental-monitoring/) | CAMELS-GB; PyTorch | In preparation |
| 4 | [Mining Glasgow's digital traces](week04-big-geodata-mining/) | OpenStreetMap via OSMnx; HDBSCAN; MovingPandas and GeoLife | In preparation |
| 5 | [Street-level greenery and deprivation in Glasgow](week05-urban-analytics/) | Mapillary via ZenSVI; semantic segmentation; SIMD 2020 | In preparation |
| 6 | [Generative maps](week06-ai-and-cartography/) | pix2pix *maps* dataset; AI-written mapping code | In preparation |
| 7 | [Auditing GeoAI](week07-ethics/) | GeoLife; Week 5 pipeline; model cards | In preparation |

## Working practices in every lab

- **Pairs.** One driver types, one navigator reads ahead; swap at each part.
- **Core and stretch.** Everyone completes the core steps; stretch tasks are optional.
- **Reproducibility.** Each notebook fixes random seeds, prints library versions and saves its results. Commit your copy to your own GitHub repository with **File → Save a copy in GitHub**.
- **Spatial validation.** Report every score with the kind of split it came from: random, or spatial.
