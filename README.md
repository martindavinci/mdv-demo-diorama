# Borghi in diorama

Four pixel-art villages you can walk around in the browser. There is no 3D model anywhere: every
house, tree and lamp post is a flat sprite, and each of its pixels is given a depth.

**Play them at [martindavinci.github.io/mdv-demo-diorama](https://martindavinci.github.io/mdv-demo-diorama/)**

## The villages

- [Borgo Duepixel](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-duepixel.html) — sunset. Three coloured houses, a shop and a well. Placeholder sprites drawn by code.
- [Borgo delle Lanterne](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-lanterne.html) — sunset. A pagoda, a tea house and a red gate, with stone lanterns along the street.
- [Borgo delle Dune](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-dune.html) — day. A bazaar, a watchtower, a camel and a jetty.
- [Ravenbrook](https://martindavinci.github.io/mdv-demo-diorama/villages/ravenbrook.html) — night. A church, an inn and a bakery, built from three image-model sprite sheets snapped back to a true pixel grid.

For comparison, [the first build of Borgo Duepixel](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-duepixel-unoptimized.html)
uses live point lights for the lamps and a tilt-shift blur.

The interface and the dialogue are in Italian.

## Controls

| | Keyboard | Phone |
| --- | --- | --- |
| Walk | WASD or arrows | stick, bottom left |
| Talk, examine | Z | button, bottom right |
| Rotate the view | Q / E, or drag | drag |
| Time of day | T | toolbar |
| Shadows | O | toolbar |
| Zoom | mouse wheel | |

## What you need

A browser with WebGL. Each village is one HTML page; once it has loaded it needs no network, and
nothing is loaded from outside this site.

## Credits

- [three.js](https://threejs.org) r128, MIT License — `vendor/three/`
- [Pixelify Sans](https://github.com/eifetx/Pixelify-Sans) and [DM Mono](https://github.com/googlefonts/dm-mono), SIL Open Font License 1.1 — `vendor/fonts/`

Everything else is under the MIT License in `LICENSE`.
