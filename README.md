# Nexor_12 client downloads

## Latest: 0.1.8

Download **nexor_12-client-0.1.8.jar** for Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API **1.21.11**, and Java 21. Remove the previous BlackVolt/Nexor JAR before putting this one in the instance's `mods` folder.

- Fixes the 0.1.7 Freecam range regression: spawner/ESP scanning and range now retain both the player area and active camera area.
- Adds **Flight** under Movement. WASD moves your actual player; Space rises, Left Shift descends. Bind a key in General and adjust Flight speed in Targets. It suspends during Freecam and starts disabled after startup/profile/world changes. Servers may reject flight.
- Includes Staff List, ore-only X-ray, full Storage ESP block/item selectors, and previous Freecam/duplicate-label fixes.

Right Shift opens the GUI; right-click modules for settings. Existing profiles carry over. Loaded-world scan/cache/render limits apply; unseen server data is unavailable. The internal mod ID/config folder stays `blackvolt` for compatibility.

The build, 50 core checks and both helper tests pass. Older versions remain available; install only one version. SHA-256 hashes are in `SHA256SUMS`.
