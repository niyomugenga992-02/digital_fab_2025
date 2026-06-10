# 5. Activity of Day 5: Digital Fabrication I - Laser Cutting & Template Validation

## Introduction

Digital fabrication technologies allow designers to convert digital designs into physical objects using computer-controlled machines. In this session, I used laser cutting to fabricate a 1:1 template of the CO3 nameplate outline.

Laser cutting enables precise manufacturing of parts from various materials such as cardboard, acrylic, plastic, and wood. This session emphasized how digital designs created using CAD software can be directly used to fabricate real-world components and prototypes.

## Laser Cutting

### Overview

Laser cutting uses a focused laser beam to cut or engrave materials with high precision. It is widely used for 2D fabrication and rapid prototyping. Laser cutting works best with vector designs, which can be created using cutting machine software like Lightburn or Inkscape.

The CO3 project uses laser cutting as a validation step: creating a 1:1 cardboard template to verify proportions and dimensions before committing to expensive CNC milling in walnut.

### Preparing Designs for Fabrication

Before sending a design to a fabrication machine, several preparation steps are necessary:

- **File Preparation:** Ensure correct design dimensions and scale. Export from CAD in vector format (DXF, SVG).
- **Machine Settings:** Configure cutting speed, laser power, tool diameter, and cutting depth based on material type and thickness.
- **Vector Setup:** Create closed paths with proper stroke styles (red = cut, blue = engrave) for laser machine interpretation.

Important parameters are cutting speed, laser power, and material thickness. These parameters depend on the material type being cut.

### CO3 Laser Cutting Process

I exported a 2D DXF file from FreeCAD containing the oval outline (150mm × 90mm) without depth data. I imported the design into Lightburn laser software, set the red stroke for cutting, and positioned it at the laser bed center.

**Machine Parameters:**
- Material: 3mm corrugated cardboard
- Laser Power: 60%
- Cutting Speed: 25mm/s
- Air Assist: ON

The laser cut through the cardboard cleanly in approximately 90 seconds. I then measured the result with digital calipers: 149.8mm × 89.9mm, which represents a deviation of only -0.2mm—well within acceptable kerf tolerance for laser cutting.

![Laser Cutting Process](../images/day_5/Carving Letters.png)

### Design Validation & Mockup Testing

Holding the cardboard template at eye level, the proportions looked perfect. I sketched the C, O, 3 letter positions on the template with pencil to verify 5mm letter spacing. No crowding or aesthetic issues were evident. The design validation confirmed that the project is ready to proceed to the 3D printing prototype stage.


![Validation Photo 2](../images/day_5/Photo from Emmanuel(1).jpg)

## Key Learning Points

From this laser cutting session, I learned:

- How digital designs are converted into machine instructions
- How material properties influence fabrication processes
- Basic safety procedures when operating laser cutting equipment
- The importance of rapid prototyping in design validation

!!! info "Safety"
    Ensure proper ventilation during laser cutting and never leave machines unattended while operating. Wear appropriate eye protection and ensure the work area is clear of obstacles.

## Dimensional Verification Results

| Dimension | Target | Measured | Deviation | Status |
|-----------|--------|----------|-----------|--------|
| Width (mm) | 150.0 | 149.8 | -0.2 | ✓ Pass |
| Height (mm) | 90.0 | 89.9 | -0.1 | ✓ Pass |

All measurements are within acceptable tolerance ranges for laser cutting (±0.5mm typical). The design is validated and ready for subsequent fabrication stages.

## Additional Links

- [Previous: 4. Activity of Day 4](day_4.md)
- [6. Activity of Day 6](day_6.md)
- [7. Activity of Day 7](day_7.md)
- [8. Activity of Day 8](day_8.md)
- [9. Activity of Day 9](day_9.md)
- [Next: 6. Activity of Day 6](day_6.md)


