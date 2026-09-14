# Jordan's Metronome Casing

A custom SolidWorks enclosure designed for the electronics in [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0).

The goal of this project was to design a casing that securely houses the metronome PCB and secondary plate while providing enough clearance for wiring, access to the PCB controls, and a removable retention system for maintenance.

The enclosure was initially explored in AutoCAD before being redesigned and developed more extensively in SolidWorks.

---

## Final Design

The final enclosure includes:

- Tapered metronome casing
- Dedicated **100 mm × 90 mm PCB cavity**
- Separate **71 mm × 55 mm plate cavity**
- Wiring clearance and pass-through features
- Two movable PCB retaining rails
- M3 screw pivot points
- Mechanical stops for the retaining rails
- Removable access to the PCB and internal components

![Final SolidWorks Design](Design%20Progress/SolidWorks/images/final-15.png)

---

## SolidWorks Design

SolidWorks became the main CAD software used for the final casing because it allowed the enclosure, moving rails, and mounting features to be tested together using assemblies and mates.

### Main Dimensions

| Feature | Dimensions |
| --- | --- |
| Enclosure height | 160 mm |
| Bottom width | 140 mm |
| Top width | 100 mm |
| Main PCB cavity | 100 mm × 90 mm × 30 mm deep |
| Secondary plate slot | 71 mm × 55 mm × 15 mm deep |
| Wiring clearance pocket | 10 mm × 18 mm × 21 mm deep |
| Wiring passage | 14 mm × 10 mm |
| Main retaining rail | 125 mm × 12 mm × 4 mm |
| Secondary retaining rail | 110 mm × 12 mm × 4 mm |
| M3 rail clearance hole | Approximately Ø3.2 mm |
| Casing pilot hole | Approximately Ø2.8 mm × 8 mm deep |

---

## Design Process

The complete SolidWorks design process is documented here:

### [Day 1 — Main Enclosure and PCB Cavity](Design%20Progress/SolidWorks/README.md#day-1--main-enclosure-and-pcb-cavity)

Created the main tapered enclosure and the rear cavity for the PCB.

[View Day 1 Image 1](Design%20Progress/SolidWorks/images/day1-01.png)  
[View Day 1 Image 2](Design%20Progress/SolidWorks/images/day1-02.png)

### [Day 2 — Secondary Plate and Wiring Clearance](Design%20Progress/SolidWorks/README.md#day-2--secondary-plate-and-wiring-clearance)

Added the secondary plate cavity, wiring clearance pocket, and through-enclosure wiring passage.

[View Day 2 Image 1](Design%20Progress/SolidWorks/images/day2-03.png)  
[View Day 2 Image 2](Design%20Progress/SolidWorks/images/day2-04.png)  
[View Day 2 Image 3](Design%20Progress/SolidWorks/images/day2-05.png)  
[View Day 2 Image 4](Design%20Progress/SolidWorks/images/day2-06.png)

### [Day 3 — PCB Retaining Rail](Design%20Progress/SolidWorks/README.md#day-3--initial-pcb-retaining-rail)

Designed the first rotating retaining rail and M3 pivot system.

[View Day 3 Image 1](Design%20Progress/SolidWorks/images/day3-07.png)  
[View Day 3 Image 2](Design%20Progress/SolidWorks/images/day3-08.png)

### [Day 4 — Assembly Testing and Retention Redesign](Design%20Progress/SolidWorks/README.md#day-4--assembly-testing-and-retention-redesign)

Tested the casing and rail in a SolidWorks assembly, identified an accessibility problem, and redesigned the retention system.

[View Day 4 Image 1](Design%20Progress/SolidWorks/images/day4-09.png)  
[View Day 4 Image 2](Design%20Progress/SolidWorks/images/day4-10.png)  
[View Day 4 Image 3](Design%20Progress/SolidWorks/images/day4-11.png)  
[View Day 4 Image 4](Design%20Progress/SolidWorks/images/day4-12.png)  
[View Day 4 Image 5](Design%20Progress/SolidWorks/images/day4-13.png)

[Watch Retaining Rail Motion Test](Design%20Progress/SolidWorks/images/railing-motion.mp4)

### [Day 5 — Mechanical Stops and Final Assembly](Design%20Progress/SolidWorks/README.md#day-5--mechanical-stops-and-final-assembly)

Added mechanical stops and completed the final assembly.

[View Day 5 Image](Design%20Progress/SolidWorks/images/day5-14.png)

### [Final Product](Design%20Progress/SolidWorks/README.md#final-product)

[View Final SolidWorks Design](Design%20Progress/SolidWorks/images/final-15.png)

---

## Full SolidWorks Documentation

[View the complete SolidWorks design process](Design%20Progress/SolidWorks/README.md)

[Download the SolidWorks casing file](Design%20Progress/SolidWorks/Metronome_Casing.SLDPRT)

[Watch the retaining rail movement test](Design%20Progress/SolidWorks/images/railing-motion.mp4)

---

## How the Retaining System Works

The PCB is installed into the rear cavity and held in place using two rotating retaining rails.

The first design used a single rail across the PCB. During assembly testing, this design was found to obstruct access to buttons and other components on the board.

The retention system was therefore redesigned to use separate rails positioned along the top and bottom edges of the PCB.

Each rail rotates around an M3 screw pivot. This allows the rails to swing away from the PCB during installation or removal and rotate back into position to retain the board.

Mechanical stops were later added to help control the closed position of the rails.

[Watch the rail movement demonstration](Design%20Progress/SolidWorks/images/railing-motion.mp4)

---

## SolidWorks Tools Used

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

## Related Electronics Project

This casing was designed around the PCB and internal components developed for:

### [Morgan's Metronome v1.0](https://github.com/morganwang7777-ux/Morgan-s-Metronome-v1.0)

Morgan's repository contains the electrical portion of the project, including:

- Arduino firmware
- PCB design
- KiCad schematic
- PCB layout
- Gerber manufacturing files
- Metronome electronics
- Project documentation

This repository focuses on the **mechanical enclosure and component-retention system** for that project.

---

## AutoCAD Development

AutoCAD was used during the earlier stages of the project to explore the general shape and dimensions of the metronome casing.

The design was later rebuilt in SolidWorks so that the enclosure could be developed using parametric features and tested with moving components in an assembly.

The earlier AutoCAD work has been kept in the repository to document the development of the project.

---

## Future Improvements

- 3D print and physically test the complete enclosure
- Verify PCB and plate tolerances after printing
- Adjust clearances based on the first physical prototype
- Refine wiring channels and connector access
- Add fillets and chamfers where appropriate
- Improve the retaining rail stops
- Consider heat-set inserts for repeated screw removal
- Improve the overall finish of the casing
