# Jordan's Metronome Casing

A custom SolidWorks enclosure designed for [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0).

This project focuses on the mechanical design of the metronome enclosure. The casing houses the main PCB and secondary plate, provides clearance for internal wiring, and uses movable retaining rails to keep the electronics secured while still allowing the PCB to be removed for maintenance.

The enclosure was first explored in AutoCAD before being rebuilt and developed more extensively in SolidWorks.

---

# Final Design

The final casing includes:

- Tapered SolidWorks enclosure
- **100 mm × 90 mm × 30 mm** main PCB cavity
- **71 mm × 55 mm × 15 mm** secondary plate slot
- Wiring-clearance pocket
- Through-enclosure wiring passage
- Two movable PCB retaining rails
- M3 screw-compatible pivot points
- Mechanical stops for the retaining rails
- Removable access to the PCB and internal components

![Final SolidWorks Casing](Design%20Progress/SolidWorks/Solidworks%20Metronome%2015.png)

---

# Design Origin

This enclosure was designed specifically for:

## [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0)

Morgan's project contains the electronic portion of the metronome, including:

- Arduino firmware
- KiCad schematic
- PCB layout
- Gerber manufacturing files
- Metronome electronics
- Controls and display
- Supporting project documentation

This repository focuses on the **mechanical casing, internal mounting geometry, wire routing, and PCB retention system** for that project.

---

# SolidWorks Design Process

The final casing was developed over five main SolidWorks design sessions.

## Day 1 — Main Enclosure and PCB Cavity

Created the tapered metronome body and main PCB cavity.

![Day 1 - Enclosure](./Design%20Progress/SolidWorks/Solidworks%201.jpg)

![Day 1 - PCB Cavity](Design%20Progress/SolidWorks/Solidworks%20Metronome%202.png)

---

## Day 2 — Secondary Plate and Wiring Clearance

Added the secondary plate slot, wiring clearance pocket, and through-enclosure wiring passage.

![Day 2 - Plate Cavity](Design%20Progress/SolidWorks/Solidworks%20Metronome%203.png)

![Day 2 - Plate Slot](Design%20Progress/SolidWorks/Solidworks%20Metronome%204.png)

![Day 2 - Wiring Clearance](Design%20Progress/SolidWorks/Solidworks%20Metronome%205.png)

![Day 2 - Wiring Passage](Design%20Progress/SolidWorks/Solidworks%20Metronome%206.png)

---

## Day 3 — Initial PCB Retaining Rail

Designed the original rotating PCB retaining rail and M3 pivot system.

![Day 3 - Retaining Rail](Design%20Progress/SolidWorks/Solidworks%20Metronome%207.png)

![Day 3 - Rail Design](Design%20Progress/SolidWorks/Solidworks%20Metronome%208.png)

---

## Day 4 — Assembly Testing and Retention Redesign

Created a SolidWorks assembly to test the original retaining rail.

Testing showed that placing one rail across the center of the PCB would obstruct access to the PCB controls.

The retention system was redesigned to use separate rails along the **top and bottom edges**, keeping the middle of the PCB accessible.

![Day 4 - Assembly](Design%20Progress/SolidWorks/Solidworks%20Metronome%209.png)

![Day 4 - Initial Rail Test](Design%20Progress/SolidWorks/Solidworks%20Metronome%2010.png)

![Day 4 - Rail Redesign](Design%20Progress/SolidWorks/Solidworks%20Metronome%2011.png)

![Day 4 - Updated Assembly](Design%20Progress/SolidWorks/Solidworks%20Metronome%2012.png)

![Day 4 - Final Rail Positions](Design%20Progress/SolidWorks/Solidworks%20Metronome%2013.png)

---

## Day 5 — Mechanical Stops and Final Assembly

Added cylindrical mechanical stops to limit the rotation of the retaining rails and completed the final assembly.

![Day 5 - Mechanical Stops](Design%20Progress/SolidWorks/Solidworks%20Metronome%2014.png)

---

# Final Product

The final SolidWorks enclosure combines the PCB cavity, secondary plate cavity, wiring features, movable retaining rails, and mechanical stops into a single mechanical design.

![Final Metronome Casing](Design%20Progress/SolidWorks/Solidworks%20Metronome%2015.png)

---

# Main Dimensions

| Feature | Dimension |
| --- | --- |
| Enclosure height | 160 mm |
| Bottom width | 140 mm |
| Top width | 100 mm |
| Main PCB cavity | 100 mm × 90 mm × 30 mm |
| Secondary plate slot | 71 mm × 55 mm × 15 mm |
| Wiring clearance pocket | 10 mm × 18 mm × 21 mm |
| Wiring passage | 14 mm × 10 mm |
| Main retaining rail | 125 mm × 12 mm × 4 mm |
| Secondary retaining rail | 110 mm × 12 mm × 4 mm |
| M3 rail clearance hole | Approximately Ø3.2 mm |
| Casing pilot hole | Approximately Ø2.8 mm × 8 mm |

---

# Retaining System

The PCB is held in the rear cavity using two rotating retaining rails.

The original design used one rail across the center of the PCB. SolidWorks assembly testing showed that this would obstruct access to buttons and other PCB components.

The system was redesigned to use separate **top and bottom rails**.

Each rail rotates around an M3 screw pivot, allowing it to swing away during PCB installation or removal and rotate back into position to retain the board.

Mechanical stops were added to limit the rail movement in the closed position.

---

# SolidWorks Tools Used

- Sketch
- Smart Dimension
- Rectangle
- Circle
- Boss-Extrude
- Cut-Extrude
- Assembly
- Insert Components
- Concentric Mate
- Coincident Mate
- Distance Mate

---

# AutoCAD Development

AutoCAD was used during the initial concept stage to explore the basic shape and dimensions of the casing.

The enclosure was later rebuilt in SolidWorks so that parametric dimensions, feature-based modelling, moving components, and assembly mates could be used.

The original AutoCAD development has been kept in this repository to document the progression of the design.

---

# Future Improvements

- 3D print and physically test the enclosure
- Verify PCB and plate tolerances after printing
- Adjust clearances based on the first prototype
- Refine wire routing and connector access
- Add fillets or chamfers where useful
- Improve the mechanical rail stops
- Consider heat-set inserts for repeated screw removal
- Refine the exterior finish of the enclosure
