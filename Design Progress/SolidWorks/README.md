# SolidWorks Design Process

This folder documents the development of the SolidWorks casing for [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0).

The purpose of the enclosure is to house the main PCB and secondary plate, provide clearance for internal wiring, and allow the electronics to remain removable for maintenance.

The design was developed over five main SolidWorks sessions. The original enclosure concept was first explored in AutoCAD before being rebuilt and expanded in SolidWorks.

---

# Day 1 — Main Enclosure and PCB Cavity

The first stage focused on creating the main shape of the metronome casing and the cavity for the main PCB.

### Work Completed

- Created the tapered enclosure profile using a SolidWorks sketch
- Defined the main dimensions using **Smart Dimension**
- Set the enclosure dimensions to:
  - **140 mm bottom width**
  - **100 mm top width**
  - **160 mm height**
- Used **Boss-Extrude** to convert the 2D profile into a 3D solid
- Created a **100 mm × 90 mm** rectangular cavity in the rear of the enclosure for the PCB
- Used **Cut-Extrude** to make the PCB cavity **30 mm deep**
- Reduced the PCB cavity from the original planned depth of 50 mm because another internal plate would occupy a separate section of the casing
- Used Sketch, Smart Dimension, Boss-Extrude, and Cut-Extrude throughout the modelling process

### Progress Images

![Day 1 - Main enclosure](./Solidworks%20Metronome%201.jpg)

![Day 1 - Main PCB cavity](./Solidworks%20Metronome%202.png)

---

# Day 2 — Secondary Plate and Wiring Clearance

The second stage focused on creating the mounting area for the secondary plate and providing enough space for its wiring.

### Work Completed

- Measured the secondary plate and created a **71 mm × 55 mm** recessed slot
- Used **Cut-Extrude** to make the slot **15 mm deep**
- Added a **10 mm × 18 mm** clearance pocket beside the plate slot
- Extended the clearance pocket **21 mm deep**
- Designed this pocket to provide additional space for the plate-side wiring connection
- Added a **14 mm × 10 mm** wiring passage
- Extended the wiring passage through the enclosure so wiring can exit the casing
- Used dimensioned sketches and Cut-Extrude features to control the geometry

### Progress Images

![Day 2 - Secondary plate slot](./Solidworks%20Metronome%203.png)

![Day 2 - Plate slot and dimensions](./Solidworks%20Metronome%204.png)

![Day 2 - Wiring clearance feature](./Solidworks%20Metronome%205.png)

![Day 2 - Wiring passage](./Solidworks%20Metronome%206.png)

---

# Day 3 — Initial PCB Retaining Rail

The third stage focused on designing a removable retaining mechanism so the PCB could be secured inside the rear cavity without permanently enclosing it.

### Work Completed

- Designed the first PCB retaining rail
- Created a **125 mm × 12 mm** rectangular rail
- Used **Boss-Extrude** to make the rail **4 mm thick**
- Added a clearance hole for an M3 screw
- Designed the rail so it could rotate around the screw rather than being permanently fixed
- Created a corresponding pilot hole in the metronome casing
- Used Sketch, Smart Dimension, Rectangle, Circle, Boss-Extrude, and Cut-Extrude

### Pivot Design

- Rail clearance hole: approximately **Ø3.2 mm**
- Casing pilot hole: approximately **Ø2.8 mm**
- Casing pilot-hole depth: **8 mm**
- Pivot positioned approximately **8 mm from the end of the rail**
- Pivot centered across the **12 mm rail width**

### Progress Images

![Day 3 - Retaining rail](./Solidworks%20Metronome%207.png)

![Day 3 - Retaining rail and casing](./Solidworks%20Metronome%208.png)

---

# Day 4 — Assembly Testing and Retention Redesign

The fourth stage focused on testing how the retaining rail interacted with the enclosure and PCB.

A SolidWorks assembly was created so the retaining rail could be positioned and rotated around its pivot.

### Initial Assembly

- Inserted the metronome casing and retaining rail into a SolidWorks assembly
- Used a **Concentric Mate** to align the pivot holes
- Used a **Coincident Mate** to position the rail against the rear surface of the enclosure
- Left rotation unlocked so the retaining rail could swing between open and closed positions

![Day 4 - Initial assembly](./Solidworks%20Metronome%209.png)

### Original Rail Test

The first retention design used a single rail across the PCB.

Assembly testing showed that a rail passing across the center of the PCB would obstruct access to buttons and other components.

![Day 4 - Original single-rail design](./Solidworks%20Metronome%2010.png)

### Retention System Redesign

The retention system was redesigned so the middle of the PCB remained accessible.

- Designed an additional retaining rail
- Secondary rail dimensions:
  - **110 mm long**
  - **12 mm wide**
  - **4 mm thick**
- Added another M3-compatible pivot point
- Repositioned the retaining rails so that they hold the PCB along its **top and bottom edges**
- Kept the center of the PCB clear for access to controls and electrical components

![Day 4 - Revised retaining rail](./Solidworks%20Metronome%2011.png)

![Day 4 - Updated assembly](./Solidworks%20Metronome%2012.png)

![Day 4 - Top and bottom retaining rails](./Solidworks%20Metronome%2013.png)

### Rail Movement Test

The retaining rails were intentionally left rotationally unlocked in the SolidWorks assembly.

This allows each rail to rotate away from the PCB during installation or removal and rotate back into position to retain the board.

[Watch the SolidWorks retaining rail motion test](./SOLIDWORKS%20Design%20Premium%20for%20Students%202026%20SP3.2%20-%20Academic%20Use%20Only%20-%20%5BMetronome%20Casing%20Complete%5D%202026-09-13%2022-09-31.mp4)

---

# Day 5 — Mechanical Stops and Final Assembly

The fifth stage focused on adding mechanical stops to control the retaining rail movement.

### Work Completed

- Created cylindrical stop features for the retaining rails
- Positioned the stops beside the rail travel limits
- Used assembly mates to determine the correct locations
- Designed the stops to prevent the retaining rails from rotating excessively past their intended closed positions
- Completed the final SolidWorks assembly
- Verified the placement of:
  - Main PCB cavity
  - Secondary plate cavity
  - Wiring clearance
  - Wiring passage
  - Top and bottom retaining rails
  - M3 pivot points
  - Mechanical stops

### Progress Image

![Day 5 - Mechanical stops and completed assembly](./Solidworks%20Metronome%2014.png)

---

# Final Product

The completed SolidWorks design combines the enclosure, internal component cavities, wiring clearance, rotating PCB retaining system, and mechanical stops into a single mechanical casing.

The main PCB can be inserted through the rear opening and retained using the rotating top and bottom rails.

The rails can then rotate away from the board when the PCB needs to be installed, removed, or serviced.

![Final SolidWorks Metronome Casing](./Solidworks%20Metronome%2015.png)

[Watch the retaining rail movement test](./SOLIDWORKS%20Design%20Premium%20for%20Students%202026%20SP3.2%20-%20Academic%20Use%20Only%20-%20%5BMetronome%20Casing%20Complete%5D%202026-09-13%2022-09-31.mp4)

---

# Final Dimensions

| Feature | Dimension |
| --- | --- |
| Enclosure height | 160 mm |
| Bottom width | 140 mm |
| Top width | 100 mm |
| Main PCB cavity | 100 mm × 90 mm |
| Main PCB cavity depth | 30 mm |
| Secondary plate slot | 71 mm × 55 mm |
| Secondary plate slot depth | 15 mm |
| Wiring clearance pocket | 10 mm × 18 mm |
| Wiring clearance depth | 21 mm |
| Wiring passage | 14 mm × 10 mm |
| Main retaining rail | 125 mm × 12 mm × 4 mm |
| Secondary retaining rail | 110 mm × 12 mm × 4 mm |
| Rail clearance hole | Approximately Ø3.2 mm |
| Casing pilot hole | Approximately Ø2.8 mm |
| Casing pilot-hole depth | 8 mm |

---

# Design Changes

## PCB Cavity Depth

The original PCB cavity was planned to be approximately **50 mm deep**.

This was reduced to **30 mm** after the secondary plate was separated into its own mounting cavity.

## PCB Retaining System

The original design used a single retaining rail across the PCB.

Assembly testing showed that this rail would block access to PCB buttons and other components.

The final design therefore uses **two separate retaining rails positioned along the top and bottom edges of the PCB**.

This keeps the PCB secure while leaving the center accessible.

## Movable Rails

The retaining rails use M3 screw pivots and are intentionally left free to rotate.

This allows the PCB to be removed without disassembling the entire enclosure.

Mechanical stops were added to limit the movement of the rails in their closed positions.

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

# Download

[Download the complete SolidWorks assembly](./Metronome%20Casing%20Complete.SLDASM)

---

# Related Project

This enclosure was designed for:

## [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0)

Morgan's repository contains the electrical side of the project, including the PCB, KiCad files, firmware, manufacturing files, and electronics documentation.
