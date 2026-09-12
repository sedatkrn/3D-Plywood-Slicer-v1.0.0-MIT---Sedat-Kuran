# 3D Plywood Slicer for FreeCAD

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![FreeCAD](https://img.shields.io/badge/FreeCAD-1.0%2B-blue)

A FreeCAD macro that slices 3D solid models into 2D plywood/CNC profiles.

**Author:** Sedat Kuran  
**Version:** 1.0.0  
**License:** MIT

## ✨ Features

- Slice along X, Y, or Z axes
- Preserve inner holes (multi-level nesting)
- Automatic hole detection
- Side-by-side 2D layout via Shape2DView
- DXF export ready
- ShapeString labels (D01, D02, ...)
- HTML report generation
- Proportional spacing based on shape size
- Automatic system font detection

## 🚀 Installation

1. Download `slice-makro.FCMacro`
2. Copy to your FreeCAD macro folder:
   - **Linux:** `~/.FreeCAD/Macro/`
   - **Windows:** `%APPDATA%\FreeCAD\Macro\`
   - **Mac:** `~/Library/Preferences/FreeCAD/Macro/`
3. In FreeCAD: `Macro → Macros → slice-makro → Execute`

## 📖 Usage

1. Select a 3D solid or Body
2. Run the macro
3. Configure slicing axis, thickness, output options
4. Click SLICE
5. Three groups appear:
   - `Solid Slices` — 3D preview
   - `DXF Views (XY, Side by Side)` — 2D profiles
   - `Temp (hidden)` — internal temporary solids
6. Select DXF Views group → `File → Export → DXF`
<img width="1443" height="1057" alt="resim" src="https://github.com/user-attachments/assets/54b741b8-e67c-49dd-b1df-928df003d339" />

## 🔧 Requirements

- FreeCAD 1.0+
- Draft workbench
- Python 3.x

## 📜 License

MIT License — see [LICENSE](LICENSE) file.

## 🙏 Credits

Developed by Sedat Kuran.
<img width="2560" height="1440" alt="resim" src="https://github.com/user-attachments/assets/dc6601bf-51c8-4562-848a-b70bd6b6af9a" />

## 📞 Contact

- GitHub: [@sedatkuran](https://github.com/sedatkuran)
