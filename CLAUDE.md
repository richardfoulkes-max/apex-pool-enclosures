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
├── index.html              ← Main landing page
├── specification.html      ← Full engineering spec (12 sections, IP55 rain-proof)
├── designs.html            ← 5 SVG drawings + heater/chiller physics section
├── bom.html                ← Bill of materials
├── market-research.html    ← GCC + Global market analysis
├── uae-pool-directory.html ← 120+ UAE pool companies (B2B targets)

manufacturer-rfq/
└── APE-Specification-v1.md ← Manufacturer RFQ package
```

## Project Location
`/Users/richardfoulkes/Library/CloudStorage/OneDrive-Personal/Documents/Projects/apex-pool-enclosures`

## Related Projects
- TV Enclosures: `/Users/richardfoulkes/Library/CloudStorage/OneDrive-Personal/Documents/Projects/apex-tv-enclosures`
- EV Enclosures: `/Users/richardfoulkes/Library/CloudStorage/OneDrive-Personal/Documents/Projects/apex-ev-enclosures`

## Market Opportunity
- **GCC Total:** 500-650K private pools (UAE 200K, Saudi 150-250K, Qatar 40-60K, Kuwait 50-80K)
- **Global:** 28M+ pools worldwide, zero global acoustic enclosure brand
- **Southern Europe:** France 3M, Spain 1.3M, Germany 2.2M - no competitors identified
- Zero GCC competitors, Australian brands don't ship internationally
- Pool contractors build custom but without acoustic treatment
- **Year 5 Target:** $5.9M revenue across GCC + Europe + USA

## Recent Work History

### Session: 2026-01-01 (PM) - Global Market Analysis + Rain-Proof Design

**Major updates to market-research.html:**
- Added "GCC Market Expansion" section with country-by-country breakdown
- Saudi Arabia analysis: Vision 2030, +47% growth, megaprojects (NEOM, Red Sea)
- Added "Global Market Opportunity" section with worldwide pool statistics
- Southern Europe focus: France (3M), Spain (1.3M) as untapped markets
- Revenue projections: GCC $1.4M + Europe $2.5M + USA $2M = $5.9M Year 5
- Phased expansion strategy: UAE → Saudi → Spain/France → Scale

**Specification updates (IP55 rain-proof):**
- Upgraded IP54 → IP55 (rain-proof, hose cleanable)
- Added louvered intake vents (30° downward angle, double-layer with drip edges)
- Added louvered exhaust (45° angle, 75mm overlap)
- New section: "Why Louvers, Not Open Gaps" comparison table
- Updated rain & humidity management with IP55 protection features

**New pages created:**
- `uae-pool-directory.html` - 120+ UAE pool companies organized by category
- Priority B2B targets, existing global products, industry directories

**Engineering additions (designs.html):**
- "Engineering Deep Dive: Enclosing Heat-Generating Equipment" section
- Heat pump thermodynamics SVG diagram
- Critical numbers table (CFM requirements, temperatures)
- Correct vs Wrong enclosure design comparison
- Manufacturer clearance requirements (Zodiac, Pentair, Astral, etc.)

**Navigation updates:**
- Added UAE Pool Directory link to all 6 website pages

---

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
