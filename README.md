# Altar Stone diagnostic toggle map

An interactive leave-one-out screen of candidate source areas for the Stonehenge Altar Stone.
Each layer is a published diagnostic; switch layers on and off to see which areas survive.
Pass, fail and untested are kept distinct: untested is not a fail.

Open `index.html` in a browser (it needs internet access for the Leaflet library and map fonts).

## Layers

- L0–L9: baseline screen (Ba/Rb geochemistry, K-feldspar, zircon, facies, thermal maturity, distance, etc.).
- L10 Sr ceiling and L11 Sr/Ca ratio: analysis by Tim Daw, applied only where rock Sr has been measured.
- U1 chrome spinel (CZi) and U2 illite/smectite expandability: from Pirrie et al. (2026). Off by default.

Not scored: the Lanark Basin, the ORS between the Midland Valley and the Welsh Borders, Carboniferous sandstones such as the Clifton Rock, and the Sr–Nd result of Pirrie et al. (2026), which the paper leaves open or gives no comparison data for.

Strict and relaxed modes, presets and group toggles are described in the "How to read this" panel and the Sources panel in the map.

## Finding places

The search box on the map accepts a map place or site name (for example "Fintona" or "Sarclet"), an Ordnance Survey grid reference (for example HY229241), latitude and longitude (for example 51.18, -1.83), or a UK or Irish place name. Place names that are not on the map are looked up with OpenStreetMap Nominatim, so the text typed is sent to that service only in that case.

## Optional overlays

- BGS 625k Old Red Sandstone underlay, the Latheron–Niandt cool sliver (schematic) and an Irish ORS desk screen.
- Tellus Northern Ireland stream-sediment Ba at or above 1025 ppm (502 samples): regional stream-sediment XRF, not rock, and not lithology-specific. Contains Geological Survey of Northern Ireland data, Open Government Licence v3.0 (https://www.opendatani.gov.uk/dataset/gsni-tellus-regional-stream-sediments).

## Files

- `index.html` – the map (data embedded).
- `places-0/1/2.json`, `meta.json` – the same data split into plain JSON.
- `ors_bgs_625k.js`, `ors_bgs_625k.geojson` – Old Red Sandstone underlay derived from the BGS Geology 625k dataset.
- `tellus_ni_ba.js` – Tellus Northern Ireland stream-sediment samples with Ba at or above 1025 ppm.

## Main sources

- Pirrie, D., Bevins, R.E., Ixer, R.A., Pearce, N.J.G., Turner, P., Power, M.R. et al. (2026). Searching for the origin of the Stonehenge Altar Stone: new sedimentological, petrographical, mineralogical, geochemical and isotopic constraints. Journal of the Geological Society 183, jgs2026-090. https://doi.org/10.1144/jgs2026-090 (https://www.lyellcollection.org/doi/full/10.1144/jgs2026-090). Dataset: https://doi.org/10.6084/m9.figshare.33993488.v1
- Bevins, R.E. et al. (2024). J. Archaeol. Sci. Rep. 58, 104738.
- Clarke, A. et al. (2026). From Highlands to Henge. J. Quaternary Sci., doi:10.1002/jqs.70080.
- Hillier, S. & Marshall, J.E.A. (1992). J. Geol. Soc. 149, 491–502.
- Daw, T. (2026). The Altar Stone – Maybe Not The Orcadian Basin? sarsen.org, 11 July 2026.

Full list: see the Sources panel in the map.

Contains British Geological Survey materials © UKRI. This is a screening tool, not a source claim.
