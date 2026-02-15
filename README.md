# LaneBlocks Official Modpack

How to install:

## Installing with Prism Launcher

### 1) Install Prism Launcher
- download the latest Prism Launcher for your OS from releases and install the app.

### 2) Import the modpack into Prism Launcher (automatic)

1. Open Prism Launcher and click **Add Instance** → **Import** or use the import option from the app menu.
2. Choose `Import from ZIP` (if you have a pack ZIP with a `manifest.json`) or `Import from Folder` and select this pack's folder.
3. Prism will create an instance, download required mods/dependencies (if using a Curse/Modrinth-style manifest), and set the correct loader version.
4. Open the instance settings, allocate at least `4 GB` of RAM under JVM arguments or memory settings, then click **Start**.

### 3) Import the modpack into Prism Launcher (manual)

1. In Prism Launcher click **Add Instance** → create a new instance with the Minecraft and loader version this pack requires.
2. Right-click the new instance and choose **Open Folder** (or **Edit Instance** → **Open Instance Folder**).
3. Copy this pack's `mods/`, `config/`, and `resourcepacks/` folders into the instance folder.
4. Verify the loader version and memory allocation, then **Start** the instance.

### Troubleshooting

- If the instance fails to start, check the instance log in Prism Launcher for missing dependency errors.
- Ensure the mod loader (Fabric/Forge) matches the pack's required loader version.
- If you see crashes, remove recently added mods from `mods/` and retry.
