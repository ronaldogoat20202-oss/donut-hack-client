# BlackVolt SMP downloads

## Latest: 0.1.5

Download **blackvolt-smp-0.1.5.jar** for Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API **1.21.11**, and Java 21. Remove your previous BlackVolt JAR, then put the new JAR in the instance's `mods` folder.

Version 0.1.5 fixes Freecam A/D strafing (A left, D right) and duplicate chest overlays when the same block is selected through multiple ESP lists. Neighboring chest blocks remain distinct.

**Right Shift → right-click a module → Targets**:

- **X-ray → Select blocks:** ores and ore/mineral blocks only. Ordinary blocks, containers, and spawners are excluded. Older profiles reset once to all ore/mineral targets; later chosen subsets save normally.
- **Storage ESP → Select blocks / Select items:** searchable complete registries. Select placed blocks or dropped items to highlight independently of Block ESP and Item ESP. Extra lists start empty.
- **Storage types:** existing container selection, separate from extra blocks/items. Storage Counter counts selected containers.

Settings save automatically. Includes offscreen arrows, General keybind controls, and Visual color sliders. Loaded-world scan/cache/render budgets still apply. Older JARs remain available; install only one version at a time.

Build, 44 core checks, and both helper tests pass. SHA-256 hashes are in `SHA256SUMS`.
