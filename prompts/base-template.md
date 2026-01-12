# Zoo CAD – Base Prompt Template

Copy this template and fill in the bracketed values.

---

## CONTEXT BLOCK (Always Include)

```
CONTEXT:
You are designing a custom dental grill (decorative jewelry overlay for teeth).
The design must be manufacturable via SLA 3D printing or CNC milling.
All dimensions are in millimeters. Biocompatibility is critical.
No sharp edges on inner surfaces. Output as watertight STL.
```

---

## FULL PROMPT TEMPLATE

```
Design a custom fantasy dental grill for a humanoid character.

ARCHETYPE: {Tusk-base cap | Illusion fang | Jaw crown | Asymmetric fang | Ritual inset}
RACE THEME: {Orc | Troll | Undead | Pandaren | Demon | Hybrid | Custom}
STYLE MOOD: {Warchief | Ritual | Battle-worn | Royal | Corrupted | Ancestral}

GEOMETRY:
- Fit dental scan reference (if imported)
- Target teeth: {upper canines | lower canines | full 6 anterior | specify}
- Max visible shell thickness: 1.4mm
- Min inner shell thickness: 0.6mm
- Inner clearance from tooth: 0.1mm uniform
- No forward extension beyond natural tooth tip

MATERIAL LOOK:
- Primary palette: {name} - Base: {hex}, Accent: {hex}
- Metal accent: {Gold #D4AF37 | Blackened #2C2C2C | Bone #E9E2D0 | None}
- Finish treatment: {Mirror | Satin | Matte | Hammered | Patina}

DETAIL FEATURES:
- Rune voids: {abstract negative space | geometric | none}
- Surface texture: {micro-etch 0.05mm | hammered | smooth}
- Glow veins: {yes - mark channels | no}

COMFORT REQUIREMENTS:
- Zero gum pressure (0.5mm clearance at gumline)
- All inner surface fillets: 0.3mm minimum radius
- Lingual hollowing for weight reduction
- Retention: friction-fit via 0.25mm interproximal undercuts

OUTPUT SPECIFICATION:
- Watertight manifold STL
- Separate STL for each inlay/accent body
- Mesh resolution: minimum 100k triangles
- Include manifest listing all parts
```

---

## QUICK ARCHETYPE SNIPPETS

### Tusk-Base Cap
```
TUSK-BASE CAP DETAILS:
- Wrap around canine root, 4mm below gumline visually
- Leave natural tooth tip exposed (2-3mm)
- Taper: 1.2mm at base to 0.6mm at margins
- Illusion of downward tusk via shading zone
```

### Illusion Fang
```
ILLUSION FANG DETAILS:
- No physical extension beyond tooth tip
- Outer surface angled 15° suggesting extension
- Color gradient zone: mark for anodizing/painting
- Shadow line at 1/3 height to create visual depth
```

### Jaw Crown
```
JAW CROWN DETAILS:
- Full lower anterior coverage (canine to canine)
- Armor-style segmented look
- Aligned to occlusal plane
- 0.2mm chamfer on bite edges
```

### Asymmetric War Fang
```
ASYMMETRIC DETAILS:
- Left canine: Full armored cap with detail
- Right canine: Minimal band (1mm at gumline)
- Creates dramatic visual tension
- Both sides maintain comfort constraints
```

### Ritual Inset
```
RITUAL INSET DETAILS:
- Negative space cutouts (0.4mm min width)
- Ultra-light construction (0.8mm total)
- Abstract rune patterns (non-IP)
- Open framework design
```
