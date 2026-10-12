# Mechanical CAD Files

This directory contains the individual STEP models for the custom 3D-printed structural parts of the 18-DOF hexapod. The parts were designed in Autodesk Fusion.

The robot has **six identical 3-DOF leg assemblies**. Each leg uses the same seven unique printed-part designs; quantities below refer to the number of physical copies required, not separate STEP files.

## Chassis

| Part | STEP model | Quantity |
|---|---|---:|
| Bottom chassis | [`chassis_bottom.step`](chassis/chassis_bottom.step) | 1 |
| Middle chassis | [`chassis_middle.step`](chassis/chassis_middle.step) | 1 |
| Top chassis | [`chassis_top.step`](chassis/chassis_top.step) | 1 |
| **Chassis total** | **3 unique models** | **3** |

## Legs

| Part | STEP model | Per leg | All six legs |
|---|---|---:|---:|
| Coxa motor mount | [`coxa_motormount.step`](leg/coxa_motormount.step) | 1 | 6 |
| Femur motor mount | [`femur_motormount.step`](leg/femur_motormount.step) | 1 | 6 |
| Tibia motor mount | [`tibia_motormount.step`](leg/tibia_motormount.step) | 1 | 6 |
| Femur shell | [`femur_shell.step`](leg/femur_shell.step) | 1 | 6 |
| Common bearing mount | [`common_bearingmount.step`](leg/common_bearingmount.step) | 3 | 18 |
| Common base | [`common_base.step`](leg/common_base.step) | 2 | 12 |
| Tibia base | [`tibia_base.step`](leg/tibia_base.step) | 1 | 6 |
| **Leg total** | **7 unique models** | **10** | **60** |

**Total: 10 unique STEP models and 63 printed structural pieces** (60 leg pieces plus 3 chassis pieces), excluding servos, bearings, fasteners, and other purchased hardware.

## CAD screenshots

Assembly views are available in [`media/cad/`](../media/cad/), including the complete hexapod, a single leg with and without servos, and the central chassis.

The STEP files contain neutral CAD geometry for the individual printed parts; they are not a complete robot assembly file or the editable Autodesk Fusion design history.
