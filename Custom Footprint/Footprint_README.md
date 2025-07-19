 Task 2: AMS1117 Custom Footprint (SOT-223 Package)

 🔧 Overview
This folder contains a **custom PCB footprint** designed for the AMS1117 Voltage Regulator (SOT-223 package) using dimensions from its official [Digikey datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/5011/AMS1117.pdf).

 📏 Footprint Details
- Package: SOT-223
- Pad Count: 4 (3 pins + 1 large thermal pad)
- Pin pitch: 2.3 mm
- Total footprint width: 6.5 mm
- Height: 6.8 mm
- Center-to-center thermal gap: ~3.5 mm
- Origin Marker placed at center for alignment

 🧰 Tools Used
- KiCad v9.0 Footprint Editor

 🛠️ Footprint Creation Steps
1. Opened AMS1117 datasheet (Pages 7–8) and noted package dimensions.
2. Laid out 3 signal pads + 1 large pad according to SOT-223 specs.
3. Added silkscreen around body (6.5 x 6.5 mm box).
4. Added courtyard and origin marker.
5. Verified alignment and pin numbering to match the schematic.

 ✅ Output
This footprint is reusable for any AMS1117-based design requiring SOT-223 mounting. Ensures correct soldering and heat dissipation area.

 📁 Files Included
- `AMS1117-SOT223_Custom.kicad_mod`: Custom footprint file.
- `AMS1117-Footprint.png`: Annotated image showing measurements in mm.
- `AMS1117-Footprint-Measured.png`: Screenshot from KiCad with dimensions visible.

---

 📌 Summary
This footprint was designed from scratch based on datasheet values to match AMS1117’s mechanical spec. It ensures compatibility and industry-readiness for custom PCB layouts.
