# Jaw Crown × Grave Silver

**Archetype:** Jaw Crown
**Palette:** Grave Silver
**Mood:** Ritual

---

## Visual Reference

| Role | Color | Hex |
|------|-------|-----|
| Base | Steel gray | #6B7076 |
| Shadow | Dark iron | #2B2E33 |
| Highlight | Polished silver | #9FA6AD |

---

## Zoo CAD Prompt

```
CONTEXT:
You are designing a custom dental grill (decorative jewelry overlay for teeth).
The design must be manufacturable via SLA 3D printing or CNC milling.
All dimensions are in millimeters. Biocompatibility is critical.
No sharp edges on inner surfaces. Output as watertight STL.

---

Design a custom fantasy dental grill.

ARCHETYPE: Jaw Crown
PALETTE: Grave Silver
STYLE MOOD: Ritual

JAW CROWN DETAILS:
- Full lower anterior coverage (canine to canine, 6 teeth)
- Armor-style segmented look with divisions between teeth
- Aligned to occlusal plane (follows bite line)
- 0.2mm chamfer on all bite-contact edges
- Ceremonial death knight aesthetic

GEOMETRY:
- Target teeth: Lower 6 anterior (canine to canine)
- Max visible shell thickness: 1.4mm
- Min inner shell thickness: 0.6mm
- Inner clearance from tooth: 0.1mm uniform
- Segmentation: Visual grooves between each tooth (0.3mm)

MATERIAL LOOK:
- Primary: Steel gray #6B7076
- Recesses: Dark iron #2B2E33
- Raised edges: Polished silver #9FA6AD
- Finish: Brushed metal with polished highlights

DETAIL FEATURES:
- Segmentation grooves: 0.3mm wide, 0.2mm deep between teeth
- Rune insets: Abstract geometric patterns, negative space
- Edge treatment: Chamfered for safety, polished
- Texture: Brushed horizontal grain on main surfaces

COMFORT REQUIREMENTS:
- Zero gum pressure (0.5mm clearance at gumline)
- All inner surface fillets: 0.3mm minimum radius
- Even weight distribution across all 6 teeth
- Retention: friction-fit via 0.25mm undercuts at interproximals

OUTPUT SPECIFICATION:
- Single unified body STL (segments are visual only)
- Mesh resolution: minimum 150k triangles (larger piece)
- Include rune voids as through-cuts where appropriate
- Mark occlusal edges for chamfer verification
```

---

## Manufacturing Notes

- **Primary material:** Surgical Steel 316L (perfect for silver look)
- **Alternative:** Titanium with steel-gray anodization
- **Finish:** Brushed steel with polished edge highlights
- **Lower jaw note:** Must clear bite - verify occlusion!
