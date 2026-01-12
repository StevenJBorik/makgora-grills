# Manufacturing Tolerances – OrcGrills™

*Last Updated: 2026-01-11*

## SLA 3D Printing Tolerances

| Spec | Standard | Precision |
|------|----------|-----------|
| XY accuracy | ±0.1mm | ±0.05mm |
| Z accuracy | ±0.15mm | ±0.05mm |
| Min wall | 0.6mm | 0.4mm |
| Min detail | 0.3mm | 0.2mm |
| Fit clearance | 0.15mm | 0.1mm |

**Best for:** Prototypes, resin production line

## CNC Milling Tolerances

| Spec | Standard | Precision |
|------|----------|-----------|
| Linear | ±0.1mm | ±0.05mm |
| High precision | ±0.05mm | ±0.01mm |
| Min wall (metal) | 0.3mm | 0.2mm |
| Surface finish | Ra 1.6μm | Ra 0.8μm |

**Best for:** Titanium, gold, final production

## OrcGrills™ Design Specs

| Parameter | Value | Rationale |
|-----------|-------|-----------|
| Visible shell | 0.8-1.4mm | Illusion + durability |
| Inner shell | 0.6mm min | Strength |
| Tooth gap | 0.1-0.15mm | Friction fit |
| Undercut depth | 0.2-0.3mm | Retention |
| Gum clearance | 0.5mm min | Comfort |
| Fillet (inner) | 0.3mm min | No sharp edges |
| Draft angle | 0-2° | CNC release |

## Zoo CAD Prompt Constraints

Include in prompts:
```
- Max outer thickness: 1.4mm
- Min inner thickness: 0.6mm  
- Inner clearance: 0.1mm uniform
- All inner fillets: 0.3mm radius
- Watertight, manifold mesh output
```
