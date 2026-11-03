# Resources

## Printable class materials

See [teaching-materials](teaching-materials/): the GeoAI design canvas, the architecture matchmaking board and scenario cards used in the Week 1 lecture (and reused in Weeks 3, 5 and 8).

## Open-source tools and data used in the labs

Licences are as stated on each project's page; check them before reusing.

| Resource | What it provides | Weeks | Licence |
| --- | --- | --- | --- |
| [scikit-learn California Housing](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) | 20,640 census block groups with coordinates (also bundled with Colab) | 1 | BSD (library) |
| [PyTorch](https://pytorch.org/) | Deep-learning framework used in every lab | 1–7 | BSD |
| [SatCLIP](https://github.com/microsoft/satclip) | Pretrained global location embeddings | 1 (stretch) | MIT |
| [TorchGeo](https://github.com/torchgeo/torchgeo) | Geospatial datasets (including EuroSAT) and pretrained Sentinel-2 weights | 2 | MIT |
| [EuroSAT](https://github.com/phelber/EuroSAT) | 27,000 labelled Sentinel-2 tiles, 10 classes | 2 | MIT |
| [TerraTorch](https://github.com/torchgeo/terratorch) | Toolkit for fine-tuning geospatial foundation models | 2 | Apache-2.0 |
| [Prithvi-EO-2.0](https://huggingface.co/ibm-nasa-geospatial) | NASA–IBM Earth-observation foundation models | 2 | See model cards |
| [CAMELS-GB](https://catalogue.ceh.ac.uk/documents/8344e4f3-d2ea-44f5-8afa-86d2987543a9) | Daily hydro-meteorology and attributes for 671 catchments in Great Britain | 3 | Open Government Licence |
| [NeuralHydrology](https://github.com/neuralhydrology/neuralhydrology) | LSTM library for rainfall–runoff modelling | 3 (stretch) | BSD-3-Clause |
| [OSMnx](https://github.com/gboeing/osmnx) | Street networks and points of interest from OpenStreetMap | 4 | MIT (OpenStreetMap data: ODbL) |
| [MovingPandas](https://github.com/movingpandas/movingpandas) | Trajectory analysis on GeoPandas | 4, 7 | BSD-3-Clause |
| [GeoLife GPS Trajectories](https://www.microsoft.com/en-us/download/details.aspx?id=52367) | GPS traces of 182 users in Beijing | 4, 7 | Microsoft Research terms |
| [ZenSVI](https://github.com/koito19960406/ZenSVI) | Street-view image download and segmentation | 5 | MIT |
| [SIMD 2020](https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/) | Scottish Index of Multiple Deprivation by data zone | 5, 7 | Open Government Licence v3.0 |
| [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) | pix2pix code, pretrained *sat2map* and *map2sat* models, Colab notebooks | 6 | See repository |
| [segment-geospatial](https://github.com/opengeos/segment-geospatial) and [geoai](https://github.com/opengeos/geoai) | Segment Anything and other GeoAI workflows for geospatial data | 2, 5 (extension) | MIT |

## Further reading

- Gao, S., Hu, Y. and Li, W. (2023) *Handbook of Geospatial Artificial Intelligence*. CRC Press. https://doi.org/10.1201/9781003308423
- Janowicz, K. et al. (2020) GeoAI: spatially explicit artificial intelligence techniques for geographic knowledge discovery and beyond. *IJGIS* 34(4), 625–636. https://doi.org/10.1080/13658816.2019.1684500
- Mai, G. et al. (2024) On the opportunities and challenges of foundation models for GeoAI. *ACM Transactions on Spatial Algorithms and Systems* 10(2). https://doi.org/10.1145/3653070
- Roberts, D.R. et al. (2017) Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure. *Ecography* 40(8), 913–929. https://doi.org/10.1111/ecog.02881
