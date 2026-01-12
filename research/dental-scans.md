# Dental Scan Acquisition – Requirements & Methods

*Last Updated: 2026-01-11*

This document defines how customers provide dental data for grillz manufacturing.

---

## Overview

Accurate dental capture is **critical** for comfort-first grillz. An inaccurate impression leads to:
- Poor fit
- Gum irritation
- Pressure points
- Customer returns

OrcGrills™ should support multiple capture methods to serve different customer segments.

---

## Capture Methods Comparison

| Method | Accuracy | Customer Ease | Cost to Customer | Our Cost |
|--------|----------|---------------|------------------|----------|
| **Digital Intraoral Scan** | ★★★★★ (50μm) | Low (needs dentist) | $50-150 | $0 |
| **Professional Mold** | ★★★★☆ | Low (needs dentist) | $50-100 | Mold processing |
| **At-Home Kit (PVS)** | ★★★☆☆ | Medium | $20-40 (included) | $5-15 shipping |
| **At-Home Kit (Alginate)** | ★★☆☆☆ | Medium | $15-25 | Not recommended |

---

## Method 1: Digital Intraoral Scan (Preferred)

### Description
Customer visits a dentist or orthodontist with an intraoral scanner and receives a digital file.

### Compatible Scanners
| Scanner | Manufacturer | File Format | Notes |
|---------|--------------|-------------|-------|
| iTero Element | Align Technology | STL, PLY | Common at orthodontists |
| 3Shape TRIOS | 3Shape | STL, PLY, OBJ | Common at general dentists |
| Carestream CS 3600 | Carestream | STL | Budget-friendly |
| Primescan | Dentsply Sirona | STL | Premium |

### What to Tell Customers
```
Request a "digital intraoral scan" from your dentist.
Ask for the file in STL or PLY format.
Request ONLY the arch you want grillz for:
  - Upper arch only
  - Lower arch only
  - Or both
  
Typical cost: $50-150 (insurance rarely covers cosmetic)
```

### File Requirements
- **Format:** STL (preferred), PLY, or OBJ
- **Resolution:** 50 micron or better
- **Scope:** Single arch minimum, full mouth optional
- **Artifacts:** No voids, no missing teeth surfaces
- **Alignment:** Standard dental orientation

### Advantages
- ✅ Highest accuracy (50μm)
- ✅ No physical shipping
- ✅ Instant delivery (customer emails file)
- ✅ Can re-use for future orders
- ✅ Professional quality assurance

### Disadvantages
- ❌ Requires dentist visit
- ❌ Not all customers have access
- ❌ Cost ($50-150)

---

## Method 2: At-Home Impression Kit

### Description
We mail customer a kit with impression trays and putty. Customer takes their own impression and mails it back.

### Kit Contents (Recommended)
| Item | Purpose | Qty |
|------|---------|-----|
| Impression trays (S, M, L) | Holds putty in mouth | 3 sets |
| PVS putty base (blue) | Impression material | 2 scoops |
| PVS putty catalyst (white) | Activates base | 2 scoops |
| Practice putty | Customer can practice | 1 scoop |
| Instruction card | Step-by-step guide | 1 |
| Return mailer (prepaid) | Ship back to us | 1 |
| Video QR code | Links to tutorial video | 1 |

### Material: Polyvinyl Siloxane (PVS)
**Why PVS over Alginate:**
- ✅ Dimensionally stable (won't distort in shipping)
- ✅ Sets in 2-3 minutes
- ✅ High detail capture
- ✅ Ships well in any temperature
- ❌ Alginate distorts within hours – NOT suitable for mail

### Step-by-Step Instructions (For Customer Card)
```
1. SELECT TRAY
   Try each tray size (S/M/L) in your mouth.
   Choose the one that covers your teeth comfortably
   without touching your lips excessively.

2. MIX PUTTY
   Knead blue + white putty together until uniform color.
   You have 30 seconds before it starts setting.

3. LOAD TRAY
   Press mixed putty into tray, filling evenly.
   Create a slight mound in the center.

4. INSERT & HOLD
   Place tray over teeth, pressing up (upper) or down (lower).
   Hold completely still for 3 minutes.
   DO NOT talk, clench, or move.

5. REMOVE
   Gently pull straight down (upper) or up (lower).
   Do not twist or rock.

6. INSPECT
   You should see clear imprints of each tooth.
   Gumline should be visible.
   No bubbles or voids in tooth areas.

7. REPEAT IF NEEDED (you have extra putty)

8. SHIP BACK
   Place impressions in mailer.
   Drop at any UPS/USPS location.
```

### Quality Checklist (For Us)
Upon receiving impressions, verify:
- [ ] All target teeth visible (usually canines + 2 adjacent)
- [ ] Gumline captured 3mm+ below tooth margin
- [ ] No bubbles in occlusal (biting) surface
- [ ] No tears or distortions
- [ ] Interproximal (between-teeth) detail present
- [ ] Impression is not crushed from shipping

### Digitization Process
1. Receive physical impression
2. Pour dental stone to create positive model
3. Scan model with desktop scanner (e.g., Revopoint, Einscan)
4. OR use impression scanner directly (3Shape E4)
5. Clean up STL in mesh software
6. Import to Zoo CAD

### Kit Suppliers
| Supplier | Product | Cost/Kit | Notes |
|----------|---------|----------|-------|
| Keystone Industries | Silginat PVS | $2-4/impression | Dental industry standard |
| GC America | EXA'lence | $3-5/impression | High detail |
| Patterson Dental | Flexitime | $4-6/impression | Premium |
| Amazon (bulk) | Generic PVS | $1-2/impression | Test quality first |

### Kit Cost Estimate
| Component | Unit Cost |
|-----------|-----------|
| PVS Putty (2 impressions) | $4 |
| Trays (3 sizes) | $2 |
| Practice putty | $1 |
| Instruction card | $0.50 |
| Shipping supplies | $1.50 |
| Outbound shipping | $5 |
| Return shipping (prepaid) | $5 |
| **Total** | **~$19** |

**Recommendation:** Include kit cost in product price OR charge $25-35 separately.

---

## Method 3: Partner Dental Network (Future)

### Concept
Partner with dental offices to offer scans at discounted rate.

### Implementation
1. Identify orthodontists in major metros
2. Negotiate flat-rate for OrcGrills™ customers ($40-60)
3. Customer books via our site, visits local partner
4. Dentist sends scan directly to us
5. We pay dentist, customer sees single price

### Benefits
- ✅ Professional quality
- ✅ Convenient for customer
- ✅ No mail logistics
- ✅ Upsell opportunity for dentists

### Phase: Future (requires volume to negotiate)

---

## File Handling Specifications

### Accepted Formats
| Format | Extension | Color Data | Recommended |
|--------|-----------|------------|-------------|
| STL (Binary) | .stl | No | ✅ Yes |
| STL (ASCII) | .stl | No | ✅ Yes |
| PLY | .ply | Optional | ✅ Yes |
| OBJ | .obj | With MTL | ⚠️ Acceptable |
| 3MF | .3mf | Optional | ⚠️ Acceptable |

### File Quality Validation
Before importing to Zoo CAD, run:
```
1. MESH INTEGRITY
   - Watertight (manifold)
   - No holes > 0.5mm
   - No inverted normals
   
2. RESOLUTION CHECK
   - Minimum 50,000 triangles for single arch
   - Optimal 100,000-500,000 triangles
   
3. SCALE VERIFICATION
   - Units: millimeters
   - Arch width should be 50-70mm (adult)
   - Canine height should be 8-12mm
   
4. ORIENTATION
   - Teeth facing "up" (positive Z for upper arch)
   - Midline roughly centered
```

### Software for Validation
- **Meshmixer** (free) – Repair, analyze
- **MeshLab** (free) – Inspection, conversion
- **Blender** (free) – General 3D manipulation
- **3Shape Dental Manager** – Industry standard

---

## Customer Communication Templates

### Upload Instructions (For Digital Scan Customers)
```
Subject: How to upload your dental scan

Thanks for ordering from OrcGrills™!

Please upload your digital dental scan:

ACCEPTED FORMATS: STL, PLY, OBJ
MAX FILE SIZE: 50MB
UPLOAD LINK: [secure upload portal]

If your dentist gave you a CD or USB:
- Look for files ending in .stl or .ply
- Upload the file for the arch you ordered

Need help? Reply to this email with your file attached.

LOK'TAR OGAR,
The OrcGrills™ Team
```

### Kit Shipping Confirmation
```
Subject: Your impression kit is on the way! 📦

Your OrcGrills™ impression kit has shipped!

TRACKING: [number]
ESTIMATED ARRIVAL: [date]

WHAT'S INSIDE:
✓ 3 impression tray sizes (S, M, L)
✓ Blue + white impression putty
✓ Practice putty (to get the hang of it)
✓ Step-by-step instructions
✓ Prepaid return mailer

⚡ PRO TIPS:
1. Watch our video tutorial first: [link]
2. Do a practice run with the practice putty
3. Have a timer ready (3 minutes)
4. Ship back within 48 hours of making impression

Problems? We include enough material for 2 attempts.

FOR THE HORDE,
The OrcGrills™ Team
```

### Poor Impression Notice
```
Subject: We need a new impression (no worries!)

Hey [Name],

We received your impression, but we can't use it to make 
your grillz – and we want your grillz to fit perfectly.

THE ISSUE:
[X] Bubbles in the tooth area
[X] Gumline not captured
[X] Impression distorted/crushed
[X] Missing teeth detail

WHAT'S NEXT:
We're sending you a FREE replacement kit today.
No action needed – it'll arrive in [X] days.

Check out our video for tips: [link]

Don't worry – this happens to about 20% of first attempts.
We'll get it right!

ZUG ZUG,
The OrcGrills™ Team
```

---

## Quality Metrics to Track

| Metric | Target | Action if Below |
|--------|--------|-----------------|
| First-attempt success rate | >80% | Improve instructions |
| Digital scan upload issues | <5% | Better file handling |
| Impression transit damage | <3% | Better packaging |
| Time to digitization | <48 hours | Streamline workflow |
| Customer re-do requests | <10% | Quality check before prod |

---

## Zoo CAD Integration

### Scan Prep Workflow
```
1. Receive STL
2. Import to Meshmixer
3. Clean (remove artifacts, fill small holes)
4. Isolate target teeth (trim to canines +2)
5. Export cleaned STL
6. Upload to Zoo CAD as reference geometry
7. Use prompt: "Fit design to imported dental scan..."
```

### Naming Convention
```
[order-id]_[customer-initials]_[arch]_[version].stl

Examples:
OG-2026-0142_JSM_upper_v1.stl
OG-2026-0142_JSM_upper_v2_cleaned.stl
```

---

## Next Steps

1. ☐ Order PVS putty samples from 3 suppliers
2. ☐ Test impression kit process internally
3. ☐ Create video tutorial script
4. ☐ Design instruction card (visual heavy)
5. ☐ Set up secure file upload portal
6. ☐ Acquire desktop scanner (Revopoint MINI recommended: $700)
7. ☐ Test Zoo CAD import with sample STL
