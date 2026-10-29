# Nexor_12 client downloads

## Latest: 0.1.10

Download **nexor_12-client-0.1.10.jar** for Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API **1.21.11**, and Java 21. Remove the previous BlackVolt/Nexor JAR before putting this one in the instance's `mods` folder. Saved settings carry over.

This build directly observes successfully rendered monster/trial-spawner block entities. A spawner the client is already drawing can reach ESP independently of chunk queues, crosshair reach, or registry block-state classification. Recent render observations survive background reconciliation.

The live local test used a cobblestone/mossy room with adjacent chests and a nearby spawner. The spawner had a red outline; status confirmed 80 rendered-spawner observations and the actual minecraft:spawner state. This verifies the new render observation path, not the user's exact public-server setup.

Right Shift → right-click Spawner ESP → Targets → Spawner status / rescan shows cached/in-range counts, rendered-spawner checks and rendered state. Spawner ESP must be ON. Includes Flight, Staff List, ore-only X-ray and Storage ESP selectors. Loaded-world/render limits apply; hidden data is not inferred.

Fabric build, 51 core checks and both helper tests pass. Internal ID/config remains `blackvolt`. Older versions remain available; install only one. SHA-256 hashes are in `SHA256SUMS`.
