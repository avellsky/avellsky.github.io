# Cometarium User Manual (Free Edition 1.0)

Cometarium shows where a comet is, when it can be seen and how its tails lie on
the sky, for iPhone, iPad and Mac. The stars come from a real catalogue, the
comet's position from an N-body integration started at the NASA/JPL orbit
solution, and the tails from radiation-pressure and solar-wind models.

- The free edition covers **10P/Tempel 2** (perihelion 5 August 2026)
- **Fully offline.** No network, no data collection, no advertising
- Requires iOS/iPadOS 17 or later, macOS 14 or later

---

## 1. The bar at the top

![Sky](img/fig_sky.jpg)

The app icon (a link to the author), the comet menu, **EN** for the language and
the **red dot** for night mode. Then the date and time — type into them if you
like — the clock and its offset from UT, and **Now**. Then the observing site
(capitals and second cities), a pin that fills in where you are, and the
coordinates. On the horizon and night panels a row of fine steps appears with
**Transit** in the middle: the moment the comet crosses the meridian that day.

Drag to move, pinch to zoom, Reset to start again. On the Mac the arrow keys
walk the horizon view.

## 2. Sky

The path among the stars in J2000 equatorial coordinates. Right ascension
increases to the left, as it does facing south. The date ticks subdivide
themselves as you zoom in. Star colour follows the B−V index, size the visual
magnitude. The comet carries the tail set on the Tail panel.

## 3. Horizon

![Horizon](img/fig_horizon.jpg)

Your own sky, centred on the comet: the sky takes its colour from the Sun's
altitude, with the ground, the compass and an altitude scale. Azimuth increases
to the right. The grid follows the field — 10° steps at a 60° field, 1° at 10° —
and the sky is drawn to 20° below the horizon, so what is about to rise can be
seen waiting. When the comet is under the ground the view stops at the horizon.

## 4. Night

![Night](img/fig_night.jpg)

One night of altitudes for the comet, the Sun and the Moon, with rise, transit
and set, the Moon's age and phase, lunar elongation and sky brightness.

## 5. Orbits

![Orbits](img/fig_orbits.jpg)

The Sun, the eight planets and the comet in three dimensions. Drag to turn the
view; centre it on the Sun, the Earth or the comet; add other comets alongside
(220P in the free edition).

## 6. Light

![Light](img/fig_light.jpg)

COBS visual and CCD observations under the fitted light curve and its ±3σ band,
with the fit's own numbers: `m₁ = H₀ + 5 log Δ + 2.5 n log r`, H₀ and n either
side of perihelion, the number of observations and when COBS was read.

## 7. Tail

![Tail](img/fig_tail.jpg)

Position angle from the nucleus, north up and east left. Choose the β grid, how
far back emission is followed (3 to 90 days), the solar wind speed and the
length, and the syndynes, synchrones and plasma tail are computed on the spot —
and drawn on the sky and horizon panels too.

## 8. Details

![Details](img/fig_now.jpg)

Thirty numbers for the instant on show, corrected for light time.

## 9. On iPhone

![iPhone](img/fig_iphone.jpg)

## 10. Free edition and Pro

| | Cometarium (free) | Cometarium Pro |
|---|---|---|
| Comets | 10P/Tempel 2 only | the whole catalogue |
| All seven panels | yes | yes |
| Comparison comets in Orbits | 220P only | any |
| Photograph astrometry, photometry, tail analysis | — | yes |
| Refit the light curve from the newest COBS data | — | yes |
| Bortle survival chart | — | yes |

## 11. Sources

Orbits and ephemerides: NASA/JPL Horizons, SBDB, NAIF SPICE (DE440, sb441).
Integration: ASSIST/REBOUND with planetary and main-belt perturbations and
non-gravitational acceleration. Photometry: COBS. Stars: Bright Star Catalogue;
constellation figures from d3-celestial. Sun, Moon and planets: Meeus,
*Astronomical Algorithms*, and Standish's approximate elements. Tails:
Finson–Probstein, Burns–Lamy–Soter β, solar-wind windsock. Sky brightness:
Krisciunas & Schaefer 1991.

Credit: NASA/JPL-Caltech.
Comet magnitude data courtesy of COBS Comet Observation Database — <https://cobs.si>

---

Contact: avellsky@gmail.com
© Cometarium, Avellsky
