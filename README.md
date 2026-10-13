# Climate Profile Cambodia

**[Open the live dashboard →](https://sustainableos.international/app/climate_profile_cambodia.html)**

*A mirror of this dashboard is also available on
[GitHub Pages](https://richardtc.github.io/climate_profile_cambodia/climate_profile_cambodia.html) — the
version above is the primary, actively maintained site; the GitHub Pages
copy may occasionally lag behind if the two aren't updated together.*

An interactive, open-source climate dashboard for Cambodia, presenting historical
climate baselines and future projections as ready-to-use maps and charts. Built
for climate practitioners and non-specialist stakeholders — government agencies,
development partners, and communities — as an accessible alternative to static
technical reports.

## What's in it

- **Map viewer** — historical and projected temperature/precipitation, across
  multiple SSP scenarios (SSP2-4.5, SSP5-8.5) and future periods (2041–2060,
  2061–2080), plus a digital elevation model and road network as reference layers
- **National metrics** and **seasonal patterns** — summary statistics and charts
- **Province data** — ADM1-level climate summaries and choropleth maps
- **GCM ensembles** — comparison across the underlying climate model ensemble
- **Heat threshold** — exceedance-day analysis

## How it works

Built entirely on free, open-source tools — R, Quarto, and Leaflet — with no
proprietary licenses or dedicated map server required. Large raster and vector
layers (Cloud-Optimized GeoTIFFs and PMTiles) stream on demand directly to the
browser via HTTP range requests, so only the data actually needed for the
current view is ever downloaded.

## Data sources

| Data | Source |
|---|---|
| Historical/future climate | WorldClim v2.1, CMIP6 GCM ensemble |
| Administrative boundaries | GADM |
| Elevation | SRTM, hole-filled V4 (CGIAR-CSI) |
| Roads | OpenStreetMap contributors (via Geofabrik) |

## Citation

When referring to this tool or the maps it produces, please cite:

> Cooper, R.T. (2026). *Climate Profile Cambodia: An accessible, open-source
> tool for communicating climate information to practitioners*. Sustainable OS
> International. https://sustainableos.international

The tool citation above is separate from the underlying climate/elevation/roads
data sources — please cite those directly wherever specific figures or values
from the dashboard are used in a publication.

## License

This repository is dual-licensed:

| What | Licence |
|---|---|
| **Code** — R scripts, Quarto/QMD source, SCSS, JavaScript and other software files | [MIT License](https://opensource.org/license/mit) |
| **Content** — text, documentation, figures, tables, maps and derived data products created by the author | [Creative Commons Attribution 4.0 International (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0/) |

Under MIT, you may use, copy, modify and redistribute the code freely, provided
the copyright notice and licence text are kept with it. Under CC BY 4.0, you are
free to share and adapt the content for any purpose, provided you give
appropriate credit to Richard T. Cooper, link to the licence, and indicate if
changes were made. See [LICENSE](LICENSE) for the full notice.

Third-party input data (WorldClim, CMIP6, GADM, SRTM, OpenStreetMap) are **not**
covered by this licence and remain subject to their own terms — see
[Data sources](#data-sources).

## About

Developed by [Richard Cooper](https://www.linkedin.com/in/richardtcooper/),
Sustainable OS International.
