# Week 4 Lab · Mining Glasgow's digital traces

**Status:** in preparation. Lecture: [Big geodata mining](../../lectures/week04-big-geodata-mining/)

## Planned outline

1. Download Glasgow points of interest and the street network with [OSMnx](https://github.com/gboeing/osmnx).
2. Find activity hotspots with HDBSCAN and compare with DBSCAN.
3. Learn Place2Vec-style embeddings of place types from their spatial co-occurrence, then cluster neighbourhoods by function.
4. Load [GeoLife](https://www.microsoft.com/en-us/download/details.aspx?id=52367) GPS trajectories into [MovingPandas](https://github.com/movingpandas/movingpandas); detect stops, split trips and map flows.

**Stretch:** predict a neighbourhood's dominant function from its embedding.

**Data note:** GeoLife (182 users in Beijing, Microsoft Research) is used because no comparable open trajectory data exist for Glasgow. OpenStreetMap data © OpenStreetMap contributors, ODbL.
