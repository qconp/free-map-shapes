# Free precise vector map shapes (SVG)

Five map outlines as clean, editable SVG. No watermark, no sign-up, no email.

| Shape | File | Outline points |
|---|---|---|
| Manhattan, New York | [`manhattan-island.svg`](manhattan-island.svg) | 675 |
| San Francisco Bay, California | [`san-francisco-bay.svg`](san-francisco-bay.svg) | 578 |
| Lake Tahoe, USA | [`lake-tahoe.svg`](lake-tahoe.svg) | 2,504 |
| Santorini, Greece | [`santorini.svg`](santorini.svg) | 1,574 |
| Yakushima, Japan | [`yakushima.svg`](yakushima.svg) | 3,183 |

## What makes these different from a screenshot of a map

- **Solid single-path silhouettes.** One `<path>`, no labels, no roads, no tiles. Drop it into Illustrator, Figma, Inkscape or Affinity and it behaves like any other shape.
- **Clipped to the real coastline.** Bays and inlets are cut out from the administrative boundary, so the water is actually water.
- **No projection distortion.** Each shape is reprojected onto a transverse Mercator centred on that area, rather than stretched into Web Mercator. Islands at high latitude keep their real proportions.
- **Holes filled.** Inland lakes and rivers inside a boundary are closed, so the outline is a usable solid, not a doughnut.

## Licence

Map data © OpenStreetMap contributors, [ODbL](https://opendatacommons.org/licenses/odbl/).
These SVGs are a Produced Work, so you may use them freely, including commercially.

Keep a visible credit where practical:

```html
<a href="https://mapcut.qconp.com">Map Shape Cutout</a> ·
Map data © <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors
```

## Also on Figma

The same five shapes are published as a Figma Community file, ready to duplicate:
https://www.figma.com/community/file/1677846755124311575/free-vector-map-shapes-svg

## Any other area

These five are samples. The same generator covers any boundary that exists in
OpenStreetMap — countries, prefectures, cities, wards, islands, lakes,
national parks — anywhere in the world, at
[mapcut.qconp.com](https://mapcut.qconp.com).

A paid area is delivered as a ZIP with the full-precision SVG, a 2600px
transparent PNG, and one separate SVG per island or detached part.
The five files here are produced by that same pipeline at the same precision,
so what you see is exactly what you would get.
