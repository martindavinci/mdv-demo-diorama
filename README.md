# Borghi in diorama

Sixteen pixel-art villages you can walk around in the browser. There is no 3D model anywhere: every
house, tree and lamp post is a flat sprite, and each of its pixels is given a depth.

**Play them at [martindavinci.github.io/mdv-demo-diorama](https://martindavinci.github.io/mdv-demo-diorama/)**

## The villages

- [Borgo Duepixel](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-duepixel.html) — sunset. Three coloured houses, a shop and a well. Placeholder sprites drawn by code.
- [Borgo delle Lanterne](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-lanterne.html) — sunset. A pagoda, a tea house and a red gate, with stone lanterns along the street.
- [Borgo delle Dune](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-dune.html) — day. A bazaar, a watchtower, a camel and a jetty.
- [Ravenbrook](https://martindavinci.github.io/mdv-demo-diorama/villages/ravenbrook.html) — night. A church, an inn and a bakery, built from three image-model sprite sheets snapped back to a true pixel grid.
- [Borgo di Leonardo](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-di-leonardo.html) — day. A ribbed cathedral dome, Leonardo's workshop with the flying machine on its terrace, and a covered bridge lined with shops.
- [Borgo dei Trulli](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-dei-trulli.html) — day. Whitewashed trulli with painted cones, a little church, a masseria and an old olive grove.
- [Borgo di Mare](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-di-mare.html) — sunset. Tall narrow coloured houses, a lighthouse on the breakwater, boats on the beach and nets drying.
- [Borgo della Laguna](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-della-laguna.html) — night. Canals, stepped bridges, a Gothic palazzo with an arcade on the water, a campanile and gondolas.
- [Borgo delle Nevi](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-nevi.html) — night. An onion-domed bell tower, an inn, chalets under snow and a frozen pond.
- [Borgo del Castello](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-del-castello.html) — sunset. A keep, a church with a rose window and three tall towers inside battlemented walls, vineyards outside.
- [Borgo delle Rovine](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-delle-rovine.html) — day. A six-column temple, a broken aqueduct, half an amphitheatre and a mosaic in the dig.
- [Borgo dei Funghi](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-dei-funghi.html) — night. Mushroom houses, a tavern in a tree stump and glowing mushrooms around a pond.
- [Borgo dei Mulini](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-dei-mulini.html) — early morning. Two windmills, stepped-gable houses along a canal, a white drawbridge and tulip fields.
- [Borgo del Faro](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-del-faro.html) — misty morning. Fishing huts on stilts, a striped lighthouse and cod drying on racks.
- [Borgo della Miniera](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-della-miniera.html) — sunset. A mine cut into the rock, a headframe over the shaft, ore carts on rails and a smoking smelter.
- [Borgo degli Igloo](https://martindavinci.github.io/mdv-demo-diorama/villages/borgo-degli-igloo.html) — night. A camp on the sea ice under the aurora: igloos, a hide tent, dogs and a sled.

From Borgo di Leonardo on, every sprite and every ground tile is drawn by code at load.

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
