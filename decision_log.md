# Desk Switch Enclosure Dimensions

## Wall Widths
* Base Plate: 3.6 mm
* Front wall: 2.6 mm
* Side walls: 2.6 mm
* Back wall: 2.6 mm

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
* Height: 4.4 mm (part of the screw will go through the base plate, with its width it gives 8 mm)
* Width: 8 mm
* Depth: 10 mm (required length = screw length - enclosure wall width: 9 mm - 2.6 mm = 6.4 mm)
* Screw thread diameter: 2.4 mm
* Screw root diameter: 1.9 mm
* Screw diameter: 4.1 mm
* Screw head height: 1.6 mm
* Screw opening in the enclosure diameter: 2 mm
### Pilot Hole
* Diameter: 1.8 mm
* Depth: 6.5 mm (screw insertion depth plus margin)
* Perimeters: 4-5

## Ventilation & Cooling Grids (Dual-Color Hex Grid)

### Print Specification (0.2 mm Nozzle)
| Parameter | Value | Notes / Calculation |
| :--- | :--- | :--- |
| **Nozzle Profile** | `0.2 mm` | Line width: `0.20 mm` – `0.22 mm` |
| **Total Panel Thickness** | `2.6 mm` | Aligned with main enclosure wall thickness |
| **Main Hexagon (Frame - Color A)** | `Ø 10.0 mm` | Outer hexagon diameter |
| **Frame A Rib Thickness** | `1.8 mm` | Exactly 9 full wall lines for 0.2 mm nozzle (updated) |
| **Micro-mesh (Infill - Color B)** | `Ø 1.2 mm` | Hexagonal mesh cell size |
| **Micro-mesh Rib Thickness B** | `0.6 mm` | Exactly 3 full wall lines for 0.2 mm nozzle |
| **Material Overlap (MMU/AMS)** | `0.6 mm` | Exactly 3 wall lines per side; ensures robust mechanical interlock (updated) |

### Z-Axis Layout (2.6 mm Wall Cross-Section)
* **0.0 mm – 0.6 mm (Exterior):** Front protective lip (Frame A) – Recessed micro-mesh for aesthetics and mechanical protection.
* **0.6 mm – 1.8 mm (Core):** Main micro-mesh structure (Color B) with a height of `1.2 mm`.
* **1.8 mm – 2.6 mm (Interior):** Rear stiffening lip (Frame A) at `0.8 mm` thick, reinforcing the enclosure structure from inside.

### Technical Rationale & Decisions
* **100% Solid Wall Alignment:** The `0.6 mm` micro-rib width and `1.8 mm` frame thickness divide cleanly into 3 and 9 perimeter paths for a `0.2 mm` nozzle, resulting in 100% solid wall density with continuous extrusion loops.
* **Passive Convection:** The ratio of cell size (`1.2 mm`) to rib thickness (`0.6 mm`) maintains high airflow permeability for passive cooling while ensuring high structural rigidity.
* **Robust Mechanical Interlock:** Utilizing a `0.6 mm` material overlap provides a solid 3-wall connection per side, completely eliminating fractional toolpaths and securely locking the micro-mesh into the main frame while maintaining structural continuity in Z.