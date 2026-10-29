# Nexor_12 client downloads

## Latest: 0.1.7

Download **nexor_12-client-0.1.7.jar** for Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API **1.21.11**, and Java 21. Remove your previous BlackVolt/Nexor JAR before putting this one in the instance's `mods` folder. Existing profiles carry over.

This update gives spawners/containers a separate bounded fast refresh, schedules nearby chunks first, makes scan/ESP range follow the Freecam camera, and keeps partly visible boxes when they cross screen edges. It addresses code paths that can delay or suppress nearby spawner markers; it does not claim reproduction of every server-specific missing target.

Includes Staff List, ore-only X-ray, full Storage ESP block/item selectors, corrected Freecam strafing and duplicate-overlay fixes. Right Shift opens the GUI; right-click modules for settings. Only loaded-world data is available; scan/cache/render limits apply. Staff List cannot detect hidden staff.

The Fabric build, 48 core checks and both helper tests pass. Internal mod ID/config folder remains `blackvolt` for compatibility. Older versions remain available; install only one version. SHA-256 hashes are in `SHA256SUMS`.
