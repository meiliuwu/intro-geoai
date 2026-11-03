# Week 5 Lab · Street-level greenery and deprivation in Glasgow

**Status:** in preparation. Lecture: [Urban analytics](../../lectures/week05-urban-analytics/)

## Planned outline

1. Download Mapillary images along a sample of Glasgow streets with [ZenSVI](https://github.com/koito19960406/ZenSVI).
2. Segment the images with a street-scene segmentation model and compute the Green View Index (Li et al., 2015).
3. Aggregate to [SIMD 2020](https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/) data zones and map the result.
4. Correlate greenery with deprivation rank, and test the residuals for spatial autocorrelation with Moran's I (from Week 1).
5. Audit segmentation errors on Glasgow tenements against the European city scenes the model was trained on.

**Stretch:** compare street-level greenery with Sentinel-2 NDVI from Week 2.

**Data note:** Mapillary images are CC BY-SA; images for the class will be downloaded in advance to avoid API limits. SIMD data are published by the Scottish Government under the Open Government Licence.
