# Realistic Earth Wallpaper

A real-time WebGL Earth wallpaper with live sun, moon, and planet positions, featuring dynamic cloud data synchronized every few hours. The wallpaper can be rotated by double clicking anywhere on the desktop and moving your mouse. No dragging required.

## Recommended: JWall

The easiest and most stable way to run this wallpaper is using [JWall](https://github.com/Pickle776/JWall). 

In fact, this wallpaper comes preloaded with JWall out of the box with zero setup needed:

1. Download `JWall.exe` from the [JWall Releases](https://github.com/Pickle776/JWall/releases).
2. Place it in any empty folder and run it.
3. It will automatically download and start this Earth wallpaper for you.

JWall is lightweight (1.2 MB), auto-pauses when other apps are active to keep CPU usage near zero, and handles desktop sleep/wake cleanly without crashing.

## Alternative: Lively Wallpaper

If you prefer to use Lively Wallpaper, you can still load it there, but be aware that Lively can occasionally be buggy or crash when waking your PC from sleep:

1. Download the ZIP of this repository and extract it to a folder.
2. Open Lively Wallpaper.
3. Drag and drop the `index_FOSS.html` file directly into Lively.
4. Name the wallpaper whatever you want and save.
5. In Lively, go to **Settings** -> **Performance** -> **System**, and turn on **Restart wallpaper when returning from lock screen** to help prevent crashes.

## Credits & Licensing

- Development: Jurgen Schmidt
- Live Cloud Data: Raw satellite data provided by EUMETSAT, with image processing and hosting by Matt Eason.

*Note: Live cloud synchronization relies on the external satellite data pipeline. If it is ever unavailable, the wallpaper automatically falls back to cached or local cloud textures.*

<img width="1853" height="899" alt="image" src="https://github.com/user-attachments/assets/00603925-648e-4cde-b51f-6b9e9d0346e4" />
<img width="1745" height="842" alt="image" src="https://github.com/user-attachments/assets/a4d99210-974d-4104-b839-d4028ff812cd" />
