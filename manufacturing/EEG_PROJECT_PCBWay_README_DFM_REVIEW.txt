EEG_PROJECT - PRELIMINARY PCBWAY DFM / DOUBLE-SIDED PCBA QUOTE ONLY
Generated from user-provided KiCad 10.0.7 fabrication files on 2026-11-08.
The files have NOT been approved for fabrication, assembly, safety, or electrical performance.

BOARD: 4 layers, outline 100.0 x 80.0 mm; job indicates 1.6 mm FR4, 1 oz each copper layer.
Specify desired surface finish (e.g. ENIG) in the PCBWay order form; Gerber job finish = None.

UPLOADS:
- EEG_PROJECT-Fabrication_Gerbers_Drills.zip -> fabrication file upload.
- EEG_PROJECT_PCBWay_BOM_CLEANED.csv -> component sourcing BOM: 38 grouped line items, 129 purchased parts (125 SMT, 4 THT).
- EEG_PROJECT_PCBWay_TOP_SMT_Positions.csv -> 89 top SMT parts.
- EEG_PROJECT_PCBWay_BOTTOM_SMT_Positions.csv -> 36 bottom SMT parts.
- Assembly drawings with pin-1 and polarization indicators: STILL NEEDED from KiCad F.Fab/B.Fab views.
- Provide original KiCad PCB, schematic and local footprint libraries upon engineering request.

BOM / PLACEMENT RECONCILIATION:
- BT1-BT4 are off-board battery cells; exclude from PCB assembly purchasing BOM.
- TP1-TP7 are copper test pads; not separate components and must not be placed.
- J1, J2, J3, SW1 are through-hole parts requiring soldering, not SMT placement.
- This package preserves KiCad XY/rotation values as exported, with negative Y. They match the Gerber coordinate convention. PCBWay must confirm datum and orientations against assembly drawings; do not manually negate one axis in only one file.

ESSENTIAL OPEN DFM QUESTIONS (REQUEST WRITTEN ACCEPTANCE BEFORE FABRICATION):
1. The 0.20 mm plated holes under exposed SMD pads total 30: 9 under U9, 9 under U10 (TPS7A4701), and 12 under U2 (ESP32-S3 WROOM-1 GND pad). Confirm filled/capped or other approved via-in-pad process, cost, paste strategy and suitability of GND pad.
2. Confirm J3 USB4085-GF-A is a through-hole USB connector, to be soldered appropriately (not SMT-only). Check the small plated holes and connector mechanical fit.
3. Confirm 0.15 mm pad clearances and solder-mask openings at U8 LIS3DH and J3; verify D7 TPD1E10B06DPYR tiny pads/orientation and stencil.
4. Confirm C19 tantalum polarity/placement and sourcing of exact MPN T495B107M010ATE350, or request approval of any substitute.
5. Source all exact MPNs from BOM; DO NOT SUBSTITUTE critical EEG filter/AFE, power, input protection or polar components without written engineering approval.
6. Confirm panelization/fiducials, double-sided assembly, 1 assembled prototype, and whether they offer unpowered inspection plus current-limited rail testing with an explicit procedure.

IMPORTANT:
- Assembly drawings are NOT included; required as clear placement and polarity reference, especially if silkscreen designators are hidden.
- The most recent native ERC and PCB-versus-schematic parity report is not supplied in this handoff. Run and attach.
- DFM approval is NOT human electrical-safety approval. No human electrode use until independently safety assessed; no mains-referenced USB/test gear during electrode use.
