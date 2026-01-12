# Zoo CAD – Capabilities & Workflow

*Last Updated: 2026-01-11*

## Overview
Zoo Design Studio (zoo.dev) is an AI-powered CAD platform combining:
- Text-to-CAD generation via natural language
- Traditional parametric modeling
- KCL (KittyCAD Language) code backend

## Key Capabilities
- **Text-to-CAD:** Generate 3D models from prompts
- **Export:** STL, PLY, OBJ, STEP, glTF, GLB, FBX
- **Import:** STEP, glTF, OBJ, STL
- **Parametric:** Sketching, extrusion, fillets, chamfers

## Limitations for Grillz
- No dental-specific tools
- No jewelry libraries (stones, settings)
- Better at mechanical than organic shapes
- May need Blender for finishing details

## Workflow
1. Prep scan in Meshmixer
2. Generate base in Zoo CAD
3. Detail work in Blender (if needed)
4. Validate mesh
5. Export STL for production

## Prompt Tips
- Be specific with dimensions (mm)
- Include all constraints
- Request fillets, thickness limits
- Specify watertight STL output
