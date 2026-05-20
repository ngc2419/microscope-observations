# Microscope Observations — Connecticut River Project Plan

**Site:** Haddam Boat Launch, Connecticut River Blueway, Haddam CT  
**Equipment:** Celestron LCD Digital Microscope II  
**Methodology:** Observe and document first; identify afterward from own images  
**Goal:** Personal exploration and journaling, with working papers on Zenodo as the record develops

---

## Key Facts Shaping This Plan

- **Compound microscope only** — everything must be on a glass slide; no bulk observation of living water
- **Haddam boat launch** — tidal freshwater zone; mix of river and tidal organisms, high biodiversity
- **Method** — observe and document first, identify afterward from your own images
- **No prior lab experience** — each phase builds one new skill only

---

## Phase 0 — Gear Acquisition

**Goal:** Have all equipment in hand before the microscope arrives.

### Slide Preparation (~$20)
| Item | Search Term | Est. Cost |
|------|-------------|-----------|
| Glass slides | "AmScope glass microscope slides 72 pack pre-cleaned" | ~$8 |
| Cover slips | "AmScope cover slips 100 pack #1.5" | ~$8 |

### Sample Collection (~$50)
| Item | Search Term | Est. Cost |
|------|-------------|-----------|
| Pipettes | "disposable plastic transfer pipettes 3ml 100 pack" | ~$8 |
| Sample jars | "Ball 4oz mason jars 12 pack" | ~$12 |
| Dip net | "pond dipping net fine mesh 150 micron" | ~$15–20 |
| Field notebook | "Rite in the Rain all-weather field notebook" | ~$12 |

### Staining & Cleaning (~$16)
| Item | Search Term | Est. Cost |
|------|-------------|-----------|
| Methylene blue stain | "methylene blue stain microscopy 1oz dropper bottle" | ~$8–10 |
| Lens tissue | "lens cleaning tissue microscope 50 sheets" | ~$5–6 |

### From Any Grocery Store
- Distilled water, 1 gallon (~$2)
- Clear nail polish (~$3, for sealing slides later)

**Estimated total: ~$87–$100**

**Status:** Acquisition initiated May 2026.

---

## Phase 1 — Learn the Microscope (No River, No Slides)

**Goal:** Understand what you're seeing before adding biological complexity.

1. Set up the microscope and explore at 40x, 100x, and 400x using household objects: a strand of your own hair, a piece of newspaper, a grain of table salt, a piece of fabric
2. Notice how depth of field collapses as magnification increases — you can only focus on one thin layer at a time
3. Practice saving images to the SD card at each magnification
4. Document each object: magnification used, what surprised you, what you couldn't resolve

**Done when:** You can move between magnifications smoothly and save a labelled image without thinking about it.

---

## Phase 2 — First Field Collection

**Goal:** Collect a river sample and make your first wet mount slide.

### At the Site (Haddam Boat Launch)
1. Collect three separate jars:
   - Surface water from open river
   - Water scooped from the edge near any visible algae or plant growth
   - A small scrape of sediment from a submerged rock or the bank edge, mixed into water
2. Label each jar (masking tape + marker)
3. Note in field notebook: date, time, tide state (incoming/outgoing/slack), weather, water clarity, any visible surface film or algae

### Back at the Microscope (within 2 hours)
1. Use a pipette to draw from the bottom of each jar (organisms concentrate there)
2. Place one small drop on a slide, lower a cover slip slowly at an angle to avoid bubbles
3. Start at 40x — scan the whole slide before touching the focus
4. Do not identify anything yet — just watch and describe in your notebook: shapes, movement, colour, size relative to the field of view
5. Save images of anything that moves or has a distinctive shape

**Done when:** You have images from all three sample types and a written description of what you saw in each.

---

## Phase 3 — Build Your Personal Visual Catalogue

**Goal:** Accumulate enough of your own images to start seeing patterns before naming anything.

Repeat Phase 2 collections on **3–4 separate visits**, varying:
- Time of day (morning vs. afternoon — some organisms migrate vertically)
- Tide state (slack tide concentrates organisms differently than moving water)
- Season (spring/summer will look different)

For each visit, add images to the repo under `pond-water/raw/` labelled by date. Update `docs/species-index.md` with your own informal descriptions — not scientific names yet, just your words: *"spinning disc with lines," "fast green blob," "cluster of spheres."*

**Introduce methylene blue** here: one stained slide per visit. Compare stained vs. unstained — staining kills movement but reveals structure.

---

## Phase 4 — Identification from Your Own Images

**Goal:** Match your catalogue images to known organisms.

By this point you will have 50–100 images of recurring forms. Reverse-engineer:
- Google Image Search your own descriptions: *"freshwater microscope spinning disc lines"*
- iNaturalist — upload images, community will help identify
- The Micropolitan Museum (micropolitan.org) — visual reference, minimal text

### What to Expect in Connecticut River Tidal Freshwater

| Group | What to Look For |
|-------|-----------------|
| Diatoms | Glassy geometric shapes, non-moving; common in sediment |
| Green algae | Chains, spheres, spirals |
| Rotifers | Moving, wheel-like feeding structures |
| Ciliates | Fast-moving single cells, often teardrop shaped |
| Copepods | Visible at 40x, crustacean-like, jerky movement |

Update `docs/species-index.md` with confirmed IDs as you go.

---

## Phase 5 — Structured Seasonal Record

**Goal:** Track the same site over time — this is where publishable data begins.

Once you can reliably identify 8–10 recurring organisms, establish a **monthly sampling protocol:**
- Same site, same three sample types (surface, edge, sediment)
- Same magnifications
- Same documentation format

This builds a time-series record of the tidal Connecticut River with genuine research value — there is very little published citizen science microscopy data for this specific stretch of river.

**Natural publication point:** *"Preliminary Survey of Microbiota at the Haddam Boat Launch, Connecticut River, 2026"* — Zenodo working paper.

---

## Documentation Flow

```
Each visit  →  images to pond-water/raw/YYYY-MM-DD/
               field notes added to docs/species-index.md
Each ID     →  confirmed name + your image added to docs/species-index.md
Publication →  archives/ + CITATION.cff updated with new DOI
```
