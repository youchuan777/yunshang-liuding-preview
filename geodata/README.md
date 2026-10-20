# Regional source data

OpenStreetMap-derived roads, water polygons, building footprints and mapped area boundaries: © OpenStreetMap contributors, licensed under the [Open Data Commons Open Database License 1.0](https://opendatacommons.org/licenses/odbl/1-0/). [OSM attribution and copyright](https://www.openstreetmap.org/copyright).

`osm-source.json` is the original public Overpass snapshot; `site.json` records its source timestamp and SHA256, metre-coordinate conversion, clipped geometry, and separate confidence notes for manually estimated visitor targets. OSM-derived data remains available under ODbL. Manual visitor annotations are research estimates, not new surveyed OSM features, and have not been uploaded to OSM.

`terrain.f32` and `context-terrain.f32` are cropped, vertically offset little-endian float32 grids from Mapzen Terrain Tiles' N43E128 tile. Global SRTM/GMTED terrain data courtesy of USGS. See [data sources and attribution](https://github.com/tilezen/joerd/blob/master/docs/attribution.md), [dataset registry](https://registry.opendata.aws/terrain-tiles/), and the original tile URL/SHA256 in `site.json`. These are regional elevation grids; they do not resolve stairs, interiors or exact shore elevation.

The visitor illustration and research photographs are not included here. Estimated building detail, local terrace edits and vegetation placement do not establish survey accuracy. The 24 km backdrop contains only low-resolution terrain, not a full facility inventory.

Version36 corrects the illustrated-map entrance label to 六宝门 and adds a separate estimated 六鼎门／海东之鹰 anchor, for18 unique visitor targets. The latter's exterior is not reconstructed. The scenic-area map labels these separately; the2025 provincial sports report also lists both names. Gate-column reliefs, local scale and landscaping are authored studies. No photo or illustrated-map pixels are embedded in the runtime. The two manual annotations are not surveyed or newly uploaded OSM features.
