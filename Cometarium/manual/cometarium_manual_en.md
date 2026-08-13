# Cometarium User Manual (Free Edition 1.0)

Cometarium shows where a comet is, when it can be seen and how its tails lie on
the sky, for iPhone, iPad and Mac. The background stars come from a real star
catalogue, the comet's position from an N-body integration started at the
NASA/JPL orbit solution, and the tails from radiation-pressure and solar-wind
models.

- The free edition covers **10P/Tempel 2** (perihelion 5 August 2026, closest to
  Earth at 0.4 au)
- **Fully offline.** No network, no data collection, no advertising
- Requires iOS/iPadOS 17 or later, macOS 14 or later

---

## 1. The screen

![The screen](img/fig_overview.jpg)

| No. | Item | What it is |
|---|---|---|
| ① | App and comet | The comet on show |
| ② | Date slider | Any instant inside the bundled span; opens at today |
| ③ | Controls | Reset, zoom out −, zoom in ＋, and six display layers |
| ④ | Sky path | The comet's track across the sky (cyan) |
| ⑤ | Date ticks | Dates along the path; large dots are the first of a month |
| ⑥ | Perihelion | Closest approach to the Sun, with its date |
| ⑦ | Outburst | An observed sudden brightening: place, date and amplitude |
| ⑧ | The comet now | The comet at the chosen instant, with dust and plasma tails |
| ⑨ | Ephemeris | The numbers for that instant |

Star colour follows the B−V colour index (blue-white is hot, orange is cool) and
star size follows visual magnitude.

## 2. Controls

| To do this | Mac | iPhone / iPad |
|---|---|---|
| Change the date | Drag the slider | Drag the slider |
| Back to today | 今日 button | 今日 button |
| Zoom | ＋ / − | ＋ / −, or pinch |
| Move the field | Drag the chart | Drag the chart |
| Fit the whole path | リセット | リセット |
| Move a label | Drag the label | Drag the label |

Zoom works **about the comet**, so it never escapes the frame. Zoomed all the way
out the chart holds the full 24 hours of right ascension and goes no wider.

**Labels can be dragged.** Around perihelion the comet name, the perihelion
caption and an outburst caption can land on one another; pull them apart.
リセット puts them back.

### Display layers

| Button | Shows |
|---|---|
| 星名 | Bayer designations of the brighter stars (e.g. α CMa) |
| 星座線 | Constellation figures |
| 星座名 | Constellation names, thinned where they would collide |
| 彗星名 | The comet's name beside its marker |
| 近日点 | Perihelion mark and date |
| バースト | Outburst mark, date and amplitude |

## 3. Reading the chart

Right ascension runs along the bottom and **increases to the left**, as the sky
does when you face south; declination runs up the side. Both are J2000.0.

The orange fan at the comet is the dust tail — a family of syndynes, the curves
traced by grains of one size, swept back by the Sun's radiation pressure. The
cyan line is the plasma tail, which follows the solar wind almost straight. At
full-path scale they are smaller than the marker, so zoom in to see them.

## 4. What zooming changes

![Zoomed in](img/fig_zoom.jpg)

The spacing of the date ticks follows how fast the comet moves **on screen**, so
zooming in turns months into halves of months and then into ten-day steps (here
8/16, 8/31, 9/15, 9/30). Fainter stars appear and more of them are named. Where
labels would collide they move to the other side of the path, and if that is
crowded too only the dot is kept.

## 5. The numbers

| Field | Meaning |
|---|---|
| 赤経 / 赤緯 (J2000) | Right ascension and declination, geocentric apparent place |
| 日心距離 r | Sun–comet distance (au; 1 au ≈ 149.6 million km) |
| 地心距離 Δ | Earth–comet distance (au) |
| 太陽離角 | Solar elongation (0° towards the Sun, 180° opposite it) |
| 位相角 | Phase angle, Sun–comet–Earth |
| 予測等級 m₁ | Predicted total magnitude, from a light curve fitted to COBS observations |
| 日心位置 (黄道) | Heliocentric ecliptic x, y, z (au) |

Distances and positions are corrected for light time: they describe the comet at
the moment the light now reaching Earth left it.

## 6. On iPhone and iPad

![iPhone](img/fig_iphone.jpg)

![iPad](img/fig_ipad.jpg)

Every device draws the same content. The iPad's wider field fits more star and
constellation names. On narrow screens the row of control buttons scrolls
sideways.

## 7. Free edition and Pro

| | Cometarium (free) | Cometarium Pro |
|---|---|---|
| Comets | 10P/Tempel 2 only | The whole catalogue |
| Sky path and ephemeris | yes | yes |
| Light curve, tail shape, observability, solar-system 3D | yes | yes |
| Comparison comets in 3D | 220P only | any |
| Photograph overlay, photometry, FITS/WCS, plate solving | — | yes |
| Bortle survival chart | — | yes |

Version 1.0 ships the sky path and the ephemeris readout; the other panels
arrive in updates.

## 8. Sources

| | |
|---|---|
| Orbits and ephemerides | NASA/JPL Horizons, SBDB, NAIF SPICE (DE440, sb441) |
| Integration | ASSIST/REBOUND N-body, with planetary and main-belt perturbations and non-gravitational acceleration |
| Photometry | COBS (Comet Observation Database) |
| Stars | Bright Star Catalogue (V ≤ 6.5) |
| Tails | Finson–Probstein syndynes and synchrones, Burns–Lamy–Soter β, solar-wind windsock model |

Credit: NASA/JPL-Caltech.
Comet magnitude data courtesy of COBS Comet Observation Database — <https://cobs.si>

## 9. Questions

**Does it work offline?** Yes. Positions and the star chart are computed inside
the app; it never contacts a server.

**What span can I show?** Each comet is bundled with a span covering its
apparition. The ends of the slider are the ends of that span.

**How accurate is it?** Positions come from an N-body integration started at the
JPL orbit solution and match observation closely. A comet's **brightness**,
however, is inherently hard to predict and can depart from what is observed.

**The labels overlap.** Drag them apart; リセット restores them.

**Can I add comets?** The free edition follows 10P/Tempel 2 only. Cometarium Pro
carries the whole catalogue.

---

Contact: avellsky@gmail.com
© Cometarium, Avellsky
