# BlackVolt SMP downloads

## Latest: 0.1.3

Download **blackvolt-smp-0.1.3.jar**. Requires Minecraft Java **1.21.11**, Fabric Loader **0.17.3 or compatible newer**, Fabric API for **1.21.11**, and Java 21. Remove the old BlackVolt JAR and put this JAR in the instance's `mods` folder.

Press **Right Shift**, right-click a module, then open **Targets**:

- **X-ray / Block ESP → Select blocks:** search all registered blocks, toggle targets, or click **Add all ores**.
- **Item ESP → Select items:** search all registered items. Turn on **Selected items only** to apply the chosen list; off shows all dropped items.
- Pickers support All entries / Selected only, Add/Remove matches, pagination, and Clear selection. Include installed mod entries. Settings save automatically.
- ESP targets remain during background rescans and have offscreen arrows when you look away. Arrows can be disabled in target settings.

General still has enable/keybind controls; Visual has color sliders. Old profiles remain compatible. Old JAR versions remain available; install only one BlackVolt version at a time.

The Fabric build, 40 core checks, and two helper tests pass. Registry search, ore selection, and ESP turning were checked in Minecraft. Scan/cache/render limits still apply, and only loaded-world data is used. SHA-256 hashes are in `SHA256SUMS`.
