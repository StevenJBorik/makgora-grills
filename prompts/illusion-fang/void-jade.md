# Illusion Fang × Void Jade

**Archetype:** Illusion Fang
**Palette:** Void Jade (UV Reactive)
**Mood:** Corrupted

---

## Visual Reference

| Role | Color | Hex |
|------|-------|-----|
| Base | Near black | #050B09 |
| Glow Vein | Neon green | #1FFF8B |

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

ARCHETYPE: Illusion Fang
PALETTE: Void Jade
STYLE MOOD: Corrupted

ILLUSION FANG DETAILS:
- No physical extension beyond tooth tip
- Outer surface angled 15° suggesting downward extension
- Color gradient zone: dark at tip, glow veins emerge upward
- Shadow line at 1/3 height creates visual depth illusion
- The darkness makes the form seem to extend into void

GEOMETRY:
- Target teeth: Upper canines only
- Max visible shell thickness: 1.2mm (minimal for void effect)
- Min inner shell thickness: 0.6mm
- Inner clearance from tooth: 0.1mm uniform
- Outer taper: 15° angle from vertical at outer face

MATERIAL LOOK:
- Primary: Near-black #050B09
- Glow veins: Neon green #1FFF8B (UV reactive channels)
- Finish: High gloss (void depth effect)
- Glow material: Inlay channels for phosphorescent resin

DETAIL FEATURES:
- Vein channels: 0.4mm wide, 0.3mm deep grooves
- Pattern: Corrupted organic flow, bottom-to-top
- Vein density: Sparse at tip, dense at gumline
- UV reactive: Channels filled with glow-in-dark resin

COMFORT REQUIREMENTS:
- Zero gum pressure (0.5mm clearance at gumline)
- All inner surface fillets: 0.3mm minimum radius
- Lingual hollowing for weight reduction
- Retention: friction-fit via 0.25mm interproximal undercuts

OUTPUT SPECIFICATION:
- Main body: Black material STL
- Vein channels: Marked as separate mesh group
- Mesh resolution: minimum 100k triangles
- Notes: Vein channels to be filled with UV resin post-print
```

---

## Manufacturing Notes

- **Primary material:** Black SLA resin (SprintRay Black)
- **Glow veins:** Phosphorescent resin inlay (Glow Inc. or similar)
- **UV reactive:** Charges under UV, glows in dark
- **Finish:** High-gloss clear coat over black, matte in vein channels
