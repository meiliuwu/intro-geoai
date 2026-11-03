# Week 2 Lab · Seeing land cover from space

**Status:** in preparation. Lecture: [Remote sensing and Earth observation](../../lectures/week02-remote-sensing/)

## Planned outline

1. Load EuroSAT (27,000 Sentinel-2 tiles, 64 × 64 pixels, 10 land-cover classes) with [TorchGeo](https://github.com/torchgeo/torchgeo); view true and false colour.
2. Train a small CNN from scratch on RGB.
3. Fine-tune ResNet-18 with Sentinel-2 pretrained weights on all 13 bands and compare.
4. Inspect the confusion matrix and Grad-CAM saliency maps on misclassified tiles.
5. Few-label learning: k-nearest neighbours on frozen foundation-model embeddings with 10 labels per class.

**Stretch:** fine-tune a [Prithvi-EO-2.0](https://huggingface.co/ibm-nasa-geospatial) model for flood mapping with [TerraTorch](https://github.com/torchgeo/terratorch).

**Runtime:** Colab GPU recommended.
