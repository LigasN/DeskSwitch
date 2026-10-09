# Desk Switch Enclosure Dimensions

## Wall Widths
* Base Plate: 3.6 mm
* Front Wall: 2.6 mm
* Side Walls: 2.6 mm
* Back Wall: 2.6 mm

## Base Plate Slide Track
* Height: 1.8 mm
* Depth: 3.4 mm

## Side Wall Slider
* Height: 1.6 mm
* Depth: 3.2 mm

## Gaps
* For the cables connected to the switch: 9 mm
* Gap from the walls to the switch mounting: 1 mm

## Seating step (Slider and Slide Track)
* Height: 0.2 mm (equal to margin between slider and slide track)
* Length: 3 mm

## Under-Desk Mounting
* Screw Type: Pan head wood screws
* Quantity: 4 (corners)
### Measured Screw Specs
* Thread Diameter: 3.8 mm
* Root Diameter: 2.5 mm
* Head Diameter: 7.5 mm
* Head Height: 2.8 mm
* Neck Expansion: 4.0 mm (height: 1.5 mm)
* Screw Length: 15.5 mm
### Base Plate Clearance Holes
* Hole Diameter: 4.5 mm
* Head Seating Surface: Flat
* Min Wall Width Around Hole: 1.2 mm
* Min Clearance to Screw Head Edge: 0.5 mm
### Desk Pilot Holes & Engagement
* Pilot Hole Diameter: 2.5 mm
* Pilot Hole Depth: 12.0 mm

## Mounting Standoffs
* Height: 5 mm
* Width: 11 mm
* Depth: 11 mm
### Corner Brackets
* Width: 1 mm
* Height: 2 mm
### Pilot Holes
* Diameter: 1.8 mm (screw root diameter: 1.9 mm, screw thread diameter: 2.9 mm)
* Depth: 4.5 mm (screw thread length: 9.6 mm, meanwell clearance hole depth: 3.4 mm, screw depth: 6.2 mm)
* Perimeters: 4-5

## Enclosure Boss
### Screw
* Length: 9.1 mm
* Head length: 1.5 mm
* Thread length: 7.6 mm
* Thread diameter: 2.44 mm
* Root diameter: 1.9 mm
* Head diameter: 4.24 mm

### Screw Boss
* Height: 4.4 mm (part of the screw will go through the base plate, with its width it gives 8 mm)
* Width: 8 mm (edit: +1 mm to the opposite side to cable clamp to make it harder to break)
* Depth: 10 mm (required length = pilot hole depth + margin)

### Screw Hole
* Opening in the enclosure diameter: 2.6 mm
* Head counterbore diameter: 4.4 mm
* Head counterbore length: 1.6 mm
  
### Pilot Hole
* Diameter: 2.2 mm
* Depth: 7.6 mm (screw root length - (wall width - head counterbore length) + margin (1 mm))
* Perimeters: 4-5

## Faceplate
* Wall thickness: 1 mm
* Flange depth (sides & bottom): Core body wall thickness (2.6 mm)
* Flange width: 2.8 mm
* Top Flange: Designed as a pair of alignment ribs extending along the flange depth behind the front wall.
* Perimeters: 4–5
* Orientation: Printed flat on the print bed for a pristine surface finish.

## Ventilation & Cooling Grids (Dual-Color Hex Grid)

### Print Specification (0.2 mm Nozzle)
| Parameter                          | Value       | Notes / Calculation                                                          |
| :--------------------------------- | :---------- | :--------------------------------------------------------------------------- |
| **Nozzle Profile**                 | `0.2 mm`    | Line width: `0.20 mm` – `0.22 mm`                                            |
| **Total Panel Thickness**          | `2.6 mm`    | Aligned with main enclosure wall thickness                                   |
| **Main Hexagon (Frame - Color A)** | `Ø 10.0 mm` | Outer hexagon diameter                                                       |
| **Frame A Rib Thickness**          | `1.8 mm`    | Exactly 9 full wall lines for 0.2 mm nozzle (updated)                        |
| **Micro-mesh (Infill - Color B)**  | `Ø 1.2 mm`  | Hexagonal mesh cell size                                                     |
| **Micro-mesh Rib Thickness B**     | `0.6 mm`    | Exactly 3 full wall lines for 0.2 mm nozzle                                  |
| **Material Overlap (MMU/AMS)**     | `0.6 mm`    | Exactly 3 wall lines per side; ensures robust mechanical interlock (updated) |

### Z-Axis Layout (2.6 mm Wall Cross-Section)
* **0.0 mm – 0.6 mm (Exterior):** Front protective lip (Frame A) – Recessed micro-mesh for aesthetics and mechanical protection.
* **0.6 mm – 1.8 mm (Core):** Main micro-mesh structure (Color B) with a height of `1.2 mm`.
* **1.8 mm – 2.6 mm (Interior):** Rear stiffening lip (Frame A) at `0.8 mm` thick, reinforcing the enclosure structure from inside.

### Technical Rationale & Decisions
* **100% Solid Wall Alignment:** The `0.6 mm` micro-rib width and `1.8 mm` frame thickness divide cleanly into 3 and 9 perimeter paths for a `0.2 mm` nozzle, resulting in 100% solid wall density with continuous extrusion loops.
* **Passive Convection:** The ratio of cell size (`1.2 mm`) to rib thickness (`0.6 mm`) maintains high airflow permeability for passive cooling while ensuring high structural rigidity.
* **Robust Mechanical Interlock:** Utilizing a `0.6 mm` material overlap provides a solid 3-wall connection per side, completely eliminating fractional toolpaths and securely locking the micro-mesh into the main frame while maintaining structural continuity in Z.

## Cable clamp
* Minimal wall width: 2 mm
* Minimal height of the top guide rail: 1.6 mm
* Cable radious: 4 mm - 7 mm
* Base wall min width: 3 mm

### Screw M2:
* Thread length: 20 mm
* Thread diameter: 2 mm
* Opening diameter: 2.2 mm

#### Head
* Diameter: 3.7 mm
* Height: 1.9 mm

#### Nut
* Width across corners: 4.5 mm
* Thickness: 1.5 mm

#### Flat Washer
* Outer Diameter: 4.9 mm
* Thickness: 0.2 mm

### Cable Clamp Retention Rib

* **Feature:** Internal circular retention rib (strain relief) inside the cable clamp channel.
* **Height:** 0.4 mm (optimized to bite securely into the external rubber/PVC cable jacket without risking damage to internal live wire insulation).
* **Base Width:** 0.8 mm

## LW26 Mounting
I have decided not to use the dimensions from the LW26 model (https://www.thingiverse.com/thing:3611525/files) as it is not exactly the same as the one I bought. However, it still remains in the project as a visual model of the future part.

### Main Shaft / Central Opening
* Diameter: 16.0 mm (clearance for the main rotary shaft/axis of the LW26 switch)

### Knob
* Width: 5 mm
* Cylinder: 15 mm
* Opening: 16 mm

### Screw
* Thread diameter: max 3.88 mm
* Clearance Opening: 5.0 mm (0.5 mm tolerance/clearance; rotation locking and positioning handled entirely by alignment ribs, screws serve clamping function only)
* Opening edge distance to the center of knob opening: 17.92 mm

### Anti-Rotation Alignment Blocks
* **Design Type:** Point-contact wall ribs (replacing continuous walls) to allow easy manual post-processing and filing if necessary.
* **Placement:** Two ribs per wall, positioned at approximately 1/3 and 2/3 of each wall's length (total of 8 ribs across 4 walls).
* **Rib Width:** 1.6 mm
* **Rib Length (Span along wall):** 8.0 mm
* **Height:** 4.0 mm
