# Nextra Design releases

Download files for **Nextra Design**, structural analysis and design inside Rhino 8 and Grasshopper.
This repository holds release files only; it contains no source code.

## Install

1. In Rhino 8, type `PackageManager`, tick **Include pre-releases**, search for **nextra-design** and click Install. Restart Rhino.
2. Type `NxPanel`. The panel offers to set up the calculation engine: click **Install** (about 390 MB, downloaded once).

No internet on the Rhino computer? Download the engine ZIP from the [Releases](../../releases) page, then click **Install from file** in the panel.

Full guide and documentation: https://nextra.studio/tools/design

## Files

| File | What it is |
|---|---|
| `nextra-runtime-<version>-win_amd64.zip` | The calculation engine (Windows, 64-bit). The plug-in checks its SHA-256 before installing. |
| `nextra-design-<version>-rh8_31-win.yak` | The Rhino package (also on the Rhino Package Manager). |

## Problems

Open an issue here and attach the log (panel: **Copy log**).
