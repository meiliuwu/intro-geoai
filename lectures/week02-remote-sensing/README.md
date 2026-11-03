# Week 2 · Remote sensing and Earth observation

**Big question:** can a model see land use from space, and where does it fail?

**Slides:** in preparation · **Pre-reading:** [Week 2 readings](../../readings/week02-remote-sensing.md) · **Lab:** [Seeing land cover from space](../../labs/week02-remote-sensing/)

## Learning outcomes

1. Explain how CNNs, U-Nets and vision transformers process multispectral imagery.
2. Fine-tune a pretrained network on Sentinel-2 tiles and compare RGB with all 13 bands.
3. Use foundation-model embeddings when labels are scarce, and diagnose errors with saliency maps.

## Lecture highlights

- **Hook:** the same farmland in true colour and false colour (near-infrared). Poll: which field is healthier?
- **Concept bursts:** from pixels to patches (classification, segmentation, detection); why 13 bands are not 3 channels; self-supervised and foundation models.
- **Signature activity, error gallery:** printed EuroSAT misclassifications on the walls (river or highway? pasture or herbaceous vegetation?). Groups diagnose each error as label noise, ambiguity, scale or spectral confusion.
- **Ethics minute:** poverty mapping from space helps target aid, but the same pipeline can serve surveillance. Where is the line?
