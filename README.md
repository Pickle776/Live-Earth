# Realistic Earth Wallpaper

A real-time WebGL Earth wallpaper with live sun, moon, and planet positions, featuring dynamic cloud data synchronized every few hours.

## How to Install (Lively Wallpaper)

Since this wallpaper uses local textures and live data fetching, it needs to be run through a local web server or a wallpaper engine. The easiest method is using Lively:

1. Download the ZIP of this repository and extract it to a permanent folder.
2. Open Lively
3. Drag and drop the index_FOSS.html file directly into a new wallpaper instance.

## Credits & Licensing

* **Development:** Jurgen Schmidt
* **Live Cloud Data:** Raw satellite data provided by **EUMETSAT**, with image processing and hosting by **Matt Eason** (CC0 1.0).

*Note: The live cloud synchronization relies on the availability of the external pipeline. If it goes down, the wallpaper will fall back to cached or default local cloud textures.*
