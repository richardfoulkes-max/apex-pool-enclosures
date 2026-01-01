# Apex Pool Enclosures - Claude Code Context

## Project Overview
Acoustic enclosures for pool equipment (pumps, filters, chillers). Modular design with 70-80% noise reduction.

## Parent Brand
**Apex Enclosures** - same brand as TV enclosures project

## Product Line: APE Series (Acoustic Pool Equipment)

### Modules
| Model | Dimensions | Purpose | BOM | Retail (AED) |
|-------|-----------|---------|-----|--------------|
| APE-BASE | 600×600×800mm | Single pool pump | $148 | 1,500-2,000 |
| APE-EXT-A | 300×600×800mm | Filter extension | $78 | +800-1,000 |
| APE-EXT-B | 400×600×800mm | Chlorinator/automation | $92 | +1,000-1,200 |
| APE-EXT-C | 600×600×800mm | Double module | $148 | +1,500-2,000 |
| APE-CHILL | 1200×600×1000mm | Pool chiller (louvered) | $252 | 4,000-5,500 |

### Key Design Decisions
- **Modular system:** Tongue-and-groove tool-free connections
- **Acoustic foam:** 25mm sides/top, 50mm rear (closed-cell polyethylene)
- **Noise reduction:** 70-80% (BASE), 50-60% (CHILL - cannot fully enclose)
- **Ventilation:** Passive convection (no fans needed)
- **Materials:** 5052-H32 aluminum, 316 SS fasteners
- **Salt pool compatible:** 316 SS required for salt chlorinator environments

### File Structure
```
website/
├── index.html          ← Main landing page
├── specification.html  ← Full engineering spec (12 sections)
├── designs.html        ← 5 SVG technical drawings
├── bom.html            ← Bill of materials
├── market-research.html ← Competitor analysis

manufacturer-rfq/
└── APE-Specification-v1.md ← Manufacturer RFQ package
```

## Project Location
`/Users/richardfoulkes/Library/CloudStorage/OneDrive-Personal/Documents/Projects/apex-pool-enclosures`

## Related Project
TV Enclosures: `/Users/richardfoulkes/Library/CloudStorage/OneDrive-Personal/Documents/Projects/apex-tv-enclosures`

## Market Opportunity
- 200K+ private pools in UAE
- Zero local competitors
- Australian imports $1,200+ USD
- Pool contractors build custom but without acoustic treatment

## Recent Work History

### Session: 2026-01-01 - APE Series v1.0 Complete

Created complete engineering specification package:
- `specification.html` (~800 lines) - 12 sections
- `designs.html` - 5 SVG drawings (side cross-section, top view, chiller, access panel, front view)
- `bom.html` - Component costing for all modules
- `APE-Specification-v1.md` - Manufacturer RFQ

Split from TV enclosures into standalone project with dedicated navigation.

## Manufacturing
Same supplier network as TV enclosures:
- **Primary:** KDM Steel (Wuxi, China) - sales@kdmsteel.com
- **Alternative:** Hofengfab, SKYT

## Notes
- Passive ventilation = simpler than TV enclosures (no fans, no electronics)
- Better margins than TV enclosures (no glass, no active cooling)
- Chiller module is separate product due to airflow requirements
