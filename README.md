# Living Streets

An interactive information session on funding nature-based solutions for climate-ready Jamaican towns (J-USE Call 2 Site Explorer, Environmental Foundation of Jamaica).

Live site: https://rasheneclarkerandall-git.github.io/living-streets/

## Pages

- `index.html`: the information session (3D site explorer).
- `charette/`: the design charette tool, at https://rasheneclarkerandall-git.github.io/living-streets/charette/

## Design charette tool

Teams trace their site, place Living Streets features and check the design against the call as they go.

1. **Site.** Find the site on the satellite map, or upload a site photo or plan and set its scale from one known length. Trace the boundary, the paved area that drains to the site, roofs, existing trees and the low point. Enter who uses the site, and edit the three-line climate case.
2. **Design.** Place features from the concept-note library (only those offered for the chosen site type). Build up to three options.
3. **Check.** Live red/green checks for the design rules (60% planted, half the runoff through living media, planting floor, keep existing trees, no food in the runoff path, plus three the team confirms), people reached against 1,000 / 5,000, and a cost estimate against the JMD 15m / 30m ceiling.
4. **Compare options** side by side, then press **Design draft** for a one-page plan to print or save as a PDF.

Work is kept in the browser automatically. Use **File › Save design file** to move a design between devices or keep a copy.

### Updating rates and rules

Planning rates, ceilings, thresholds and the budget split sit in the `CALL DATA` block at the top of the script in `charette/index.html` (`STREAMS`, `BUDGET`, `TOOLS`, `TREE_PIT`, `TANK_RATE`).

### Planning assumptions

- One m² of planted drain, rain garden or rain park treats about 3 m² of paving, from the concept-note quantities. Teams can change it under Check › Assumptions.
- Design, inclusion, monitoring, management and contingency are added in the same proportions as the concept-note budget for the stream.
- Planting spend is estimated as the concept-note share of works (about 20%).
- Pocket rain parks are priced at the rain-garden rate, and green roofs are left unpriced until the charette bill of quantities.

### Third-party code

`charette/vendor/` contains [Leaflet](https://leafletjs.com) 1.9.4 and [Leaflet-Geoman](https://geoman.io) 2.17.0 (both MIT; licences included). Map imagery comes from Esri World Imagery and OpenStreetMap, and place search from OpenStreetMap Nominatim.
