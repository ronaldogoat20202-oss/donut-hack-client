# Nexor_12 client downloads

## Latest: 0.1.9

Download **nexor_12-client-0.1.9.jar** for Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API **1.21.11**, and Java 21. Remove the previous BlackVolt/Nexor JAR before installing it in the instance's `mods` folder. Existing settings carry over.

This patch protects spawner observations from dense block-target cache eviction and draws spawner overlays first. The actual loaded block under the crosshair is checked independently of chunk block-entity lists.

If a spawner is missing, aim directly at it, then open **Right Shift → right-click Spawner ESP → Targets → Spawner status / rescan**. Ensure **Spawner ESP: ON**. The screen shows cached/in-range counts and actual targeted block ID, can rescan nearby chunks, and has **Copy status** for reporting. Spawner Notifier alone does not enable the overlay. The exact reported public-server issue is not yet confirmed.

Includes Flight, Staff List, ore-only X-ray, full Storage ESP selectors and player-plus-Freecam scan areas. Servers may reject Flight; hidden staff/blocks cannot be inferred. Scan/cache/render limits apply.

The build, 51 core checks and both helper tests pass. Internal mod ID/config stays `blackvolt`. Older versions remain available; install only one. SHA-256 hashes are in `SHA256SUMS`.
