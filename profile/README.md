# Dutchman CAD

Open tools for people who design with CAD and don't want their work locked inside one program.

[![Discord](https://img.shields.io/badge/Discord-Dutchman%20CAD-5865F2?logo=discord&logoColor=white)](https://discord.gg/yTcseBEdeu)

<!-- glance:start -->
## At a glance

- **Dutchman Convert:** v0.2.2 · converts Fusion, Inventor, FreeCAD, SolidWorks parts, CATIA, Rhino, ACIS, Creo View, and STEP to SolidCraft · DM Dutchy a file that fails
- **Install:** `brew install dutchman-cad/tap/dutchman` · Mac app: `brew install --cask dutchman-cad/tap/dutchman-convert` · Windows: Scoop (dutchman-cad bucket)
- **Send us a file:** a CAD file that won't convert? DM Dutchy on the Discord (drag it in, plus its STEP export if you have one) and choose Send privately · bigger than 10 MB: /volunteer
- **Try it in a browser:** <https://dutchman-cad.github.io/demo/> · a converted design open in SolidCraft's web app
- **Self-host:** `docker pull ghcr.io/dutchman-cad/dutchman` · the browser converter and a watched folder on your own server or NAS (amd64 and arm64) · SolidCraft and Dutchman on one address: <https://github.com/dutchman-cad/dutchman/tree/main/examples/compose> · <https://github.com/dutchman-cad/dutchman/blob/main/docs/docker.md>
- **Pilot:** v0.1.0-beta.5 · helps small local AI models drive SolidCraft and SolidCraft 98 · now fills recipe forms for common parts · type /report in the Assistant to report a problem
- **Fixtures:** small, known CAD test files made from short recipes · type /volunteer to help
- **SolidCraft 98:** v1.2 · news in #solidcraft98-updates
- **Discord invite:** <https://discord.gg/yTcseBEdeu>
<!-- glance:end -->

Dutchman CAD is a home for open CAD tools: moving designs between programs, testing that they come through right, and helping more people and tools work with them. Much of it is built around [SolidCraft](https://github.com/tangency-labs/solidcraft), the open-source parametric CAD app, but not all of it, and none of it needs to live inside one app.

## Projects

| Project | What it does | Status |
|---|---|---|
| [**Dutchman Convert**](https://github.com/dutchman-cad/dutchman) | Converts native CAD designs (Fusion, Inventor, SolidWorks parts, FreeCAD, CATIA, Rhino, ACIS, Creo View, and STEP) into SolidCraft designs, keeping feature history, sketches, assemblies, and joints where it can. Also writes FreeCAD documents. | Early development; desktop app and command line for Windows, macOS, and Linux |
| [**Fixtures**](https://dutchman-cad.github.io/fixtures/) | Small, known test files made by volunteers in the real CAD programs, from short recipes, so the readers behind Dutchman Convert can be checked against ground truth. | Collecting; volunteers welcome |
| [**Pilot**](https://github.com/dutchman-cad/pilot) | Helps small local language models drive SolidCraft from outside the app, through SolidCraft's Assistant or any MCP client. Runs as `dutchman pilot`, or on its own. | Early beta; command line for Windows, macOS, and Linux |

## Install

- **Homebrew** (macOS, Linux): `brew install dutchman-cad/tap/dutchman` for Dutchman Convert (with `dutchman pilot`), `brew install dutchman-cad/tap/dutchman-pilot` for Pilot alone.
- **Scoop** (Windows): `scoop bucket add dutchman-cad https://github.com/dutchman-cad/scoop-bucket`, then `scoop install dutchman-cad/dutchman` or `dutchman-cad/dutchman-pilot`.
- **Docker** (self-host, amd64 and arm64): `docker pull ghcr.io/dutchman-cad/dutchman` runs Dutchman Convert's browser converter or a watched folder on your own server or NAS ([Docker guide](https://github.com/dutchman-cad/dutchman/blob/main/docs/docker.md)).
- **Download**: each project's releases page has the desktop app and command-line archives.

## Principles

- **Clean room.** Formats are worked out from files people are entitled to use and from public information, never from vendor SDKs, decompiled programs, or confidential material.
- **Your files stay yours.** Nothing is uploaded unless you choose to share it, and reports never need your file names or paths.
- **Honest output.** Every conversion lists what it could not carry across.

## Get involved

- Try [Dutchman Convert](https://github.com/dutchman-cad/dutchman#download) on your own designs, and [report anything that doesn't convert](https://github.com/dutchman-cad/dutchman/issues/new/choose).
- Make a few [fixture files](https://dutchman-cad.github.io/fixtures/) in the CAD program you use.
- Ask questions, share what you converted, and meet the people building these tools on the [Dutchman CAD Discord](https://discord.gg/yTcseBEdeu).
