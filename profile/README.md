# Dutchman CAD

Open tools for people who design with CAD and don't want their work locked inside one program.

Dutchman CAD is a home for open CAD tools: moving designs between programs, testing that they come through right, and helping more people and tools work with them. Much of it is built around [SolidCraft](https://github.com/tangency-labs/solidcraft), the open-source parametric CAD app, but not all of it, and none of it needs to live inside one app.

## Projects

| Project | What it does | Status |
|---|---|---|
| [**Dutchman**](https://github.com/dutchman-cad/dutchman) | Converts native CAD designs (Fusion, Inventor, SolidWorks, and FreeCAD) into SolidCraft designs, keeping feature history, sketches, assemblies, and joints where it can. Also writes FreeCAD documents. | Early development; desktop app and command line for Windows, macOS, and Linux |
| [**Fixtures**](https://github.com/dutchman-cad/fixtures) | Small, known test files made by volunteers in the real CAD programs, from short recipes, so the readers behind Dutchman can be checked against ground truth. | Collecting; volunteers welcome |
| **SolidCraft-Pilot** | Helps smaller, local language models drive SolidCraft reliably, from outside the app. | Coming soon |

## Principles

- **Clean room.** Formats are worked out from files people are entitled to use and from public information, never from vendor SDKs, decompiled programs, or confidential material.
- **Your files stay yours.** Nothing is uploaded unless you choose to share it, and reports never need your file names or paths.
- **Honest output.** Every conversion lists what it could not carry across.

## Get involved

- Try [Dutchman](https://github.com/dutchman-cad/dutchman#download) on your own designs, and [report anything that doesn't convert](https://github.com/dutchman-cad/dutchman/issues/new/choose).
- Make a few [fixture files](https://github.com/dutchman-cad/fixtures) in the CAD program you use.
