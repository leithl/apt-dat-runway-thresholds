# apt.dat-derived runway thresholds — Australia, New Zealand, Canada

Runway threshold coordinates for airports in Australia, New Zealand and Canada,
derived from the [X-Plane Scenery Gateway](https://gateway.x-plane.com/)
`apt.dat` airport dataset.

The airport data shared via the X-Plane Scenery Gateway is published under the
**GNU General Public License, version 2 or (at your option) any later version**.
This file is a derivative of that data, so it is distributed under the same
license (see [`LICENSE`](LICENSE)). Copyright © the X-Plane Scenery Gateway
contributors. The upstream notice, preserved verbatim from a Gateway scenery
pack's `README.txt`:

> The scenery packs shared via the X-Plane Scenery Gateway are free software; you
> can redistribute it and/or modify it under the terms of the GNU General Public
> License as published by the Free Software Foundation; either version 2 of the
> License, or (at your option) any later version. See the included COPYING file
> for complete terms.

## Contents

`runways_apt_dat.csv` — one row per runway:

| column | meaning |
|---|---|
| `icao` | airport identifier |
| `le_ident` / `he_ident` | the two runway-end designators (e.g. `09` / `27`) |
| `le_lat`, `le_lon`, `he_lat`, `he_lon` | threshold coordinates of each end (WGS-84, decimal degrees) |
| `le_displaced_ft`, `he_displaced_ft` | displaced-threshold distance for each end, in feet (blank where the source carries none) |

Only runways whose threshold coordinates are **apt.dat-sourced** are included.
Coordinates that originate from public-domain or other-licensed datasets are
excluded, so everything here is genuinely covered by the GPL.

## License

GNU General Public License, version 2 — full text in [`LICENSE`](LICENSE).
Upstream source: <https://gateway.x-plane.com/>.
