# Plant Cells and Tissues

## Why it matters

A plant cell is an animal cell **plus a wall, chloroplasts, and a large central vacuole**. That looks like a list of spare organelles, but it is a list of three solved engineering problems: support without a skeleton, carbon fixation instead of ingestion, and water moved by pressure instead of a pump. Every structural difference below derives from one of those mechanisms — derive the structure from the problem and you stop memorising.

```
problem                    mechanism                    consequence
─────────────────────────────────────────────────────────────────────────────
no muscles, no bones  →  rigid wall + outward turgor →  upright body, support
                                                         bought with water
no gut, no ingestion  →  chloroplasts + sunlight     →  autotrophic, sessile
no heart, no vessels  →  evaporation at the leaf     →  water PULLED from the
                              (see 04)                     roots, mass flow in
                                                           dead tubes (see 03)
```

Second, plants are **modular and indeterminate**: a plant is a repeating unit — meristem plus the organs it makes — added for as long as it lives, so regrowth after damage and rooting of a fallen branch are normal, and there is no clean plant equivalent of cancer (loss of one organism-wide growth brake). Hormonal control is in [05 — Plant hormones](05-plant-hormones.md); the organs are in [02 — Roots, stems, and leaves](02-roots-stems-and-leaves.md).

Third, this chapter is the vocabulary for everything downstream: you cannot understand water movement until you know that xylem conduits are **dead hollow cells**, that the endodermis forces water out of the wall pathway, and that a stomatal pore opens by osmotic water uptake — the subjects of [03 — Xylem and phloem](03-xylem-and-phloem.md) and [04 — Water transport and transpiration](04-water-transport-and-transpiration.md).

## Plant cell structures

### The cell wall: a tensile skeleton round a pressure vessel

The wall is a **composite material** — stiff fibres in a hydrated gel — and each component has a mechanical job:

| Component | Job in the wall | Why its chemistry fits |
| --- | --- | --- |
| **Cellulose microfibrils** (β-1,4-glucan, crystalline bundles) | **Tensile reinforcement** — resists the outward pull of turgor | Hydrogen bonding packs glucan tighter than any other biological polymer, so the wall carries the load rather than the cytoplasm |
| **Hemicellulose** (xyloglucan, xylan) | **Tethers** fibrils to each other and to wall proteins | Unlinked fibrils slide under load; cross-linking makes a sheet, and loosening these tethers is how the wall yields during growth |
| **Pectin** (homogalacturonan) | **Charged hydrating gel** — porosity, wall water, adhesion | Carboxyls bind Ca²⁺ in "egg-box" junctions and hold water; de-esterified pectin in the middle lamella glues cells together |

**The wall exists to contain turgor.** A plant builds pressure from within and strength from without:

```
vacuole accumulates K+, Cl-, NO3-, sugars, organic acids
        │
        ▼
solute potential Ψs becomes very negative → water follows by osmosis
        │
        ▼
the wall cannot hold the solutes → water is TRAPPED → pressure Ψp rises
        │
        ▼
protoplast presses out, wall presses back → TURGOR (0.3–1.0 MPa)
        │
        ▼
turgor = hydrostatic skeleton; turgor lost = wilting, stomata shut
```

Holding turgor costs only the ATP for ion pumping, not the cost of moving contractile protein — why a tree can be large, upright and cheap to run. **The wall must also yield:** growth is wall **creep**, in which acidification of the wall space activates **expansins** that loosen hemicellulose tethers, turgor drags the fibrils apart, and new cellulose is laid down in the new configuration. Auxin promotes this sequence (the acid-growth mechanism) — one entry point into [05 — Plant hormones](05-plant-hormones.md).

### Primary wall, secondary wall, lignification

| Feature | **Middle lamella** | **Primary wall** | **Secondary wall** |
| --- | --- | --- | --- |
| Timing | First; shared by two cells | While the cell is **still growing** | **After** growth stops, inside the primary wall |
| Composition | **Pectin** glue | Cellulose + hemicellulose + pectin, thin and flexible | Cellulose + hemicellulose + **lignin**, thick (S1–S3 layers), little pectin |
| Function | Cell adhesion; plane of abscission | Shape and controlled expansion | Compressive strength, waterproofing, rigidity |

**Lignification** is the decisive upgrade: **lignin** is a hydrophobic, cross-linked phenylpropanoid polymer infiltrated after the cellulose is placed. It **waterproofs** the wall, so a conduit can carry water under tension without leaking sideways — the basis of xylem transport ([03 — Xylem and phloem](03-xylem-and-phloem.md)); it adds **compressive strength and hardness**, which cellulose (a tensile material) cannot give — cellulose is the rebar, lignin the concrete; and it resists microbial enzymes, which is why only specialised fungi rot wood. A lignified cell has usually stopped growing and, in tracheids and vessel elements, stopped living: the protoplast degrades and leaves a hollow lignified **pressure vessel**.

### The plasma membrane: the wall is outside it

The wall is a **porous, non-selective mesh** — water, ions and small solutes diffuse through freely — so the **plasma membrane remains the only selective barrier**; every nutrient, signal and waste product still crosses it. Its fluid-mosaic architecture is in [01 — Membrane structure and fluid mosaic](../03-cellular-processes/01-membrane-structure-and-fluid-mosaic.md), its water and solute movements in [02 — Passive transport](../03-cellular-processes/02-passive-transport.md). Three wall-specific consequences follow. The **H⁺-ATPase** exports protons, making the interior negative and the wall space acidic, which drives K⁺ and NO₃⁻ uptake by secondary active transport and activates expansins — so uptake stays **energy-requiring and membrane-controlled** even though the solute sits micrometres away in the wall. Pectin carboxyls make the wall a **cation-exchange reservoir** holding Ca²⁺, K⁺ and Mg²⁺ instead of letting them wash away. And the wall can be **sealed**: in the root endodermis, **suberin** forms the **Casparian strip**, blocking the wall pathway so every solute must cross a membrane — what makes root uptake selective rather than bulk-flow filtration.

### Plasmodesmata: symplast versus apoplast

Adjacent cells are perforated by **plasmodesmata** — channels traversed by an endoplasmic-reticulum strand (the **desmotubule**), lined by plasma membrane, with a **cytoplasmic sleeve** through which small molecules move. This creates three transport domains:

| Pathway | What is crossed | Selectivity and role |
| --- | --- | --- |
| **Apoplast** | Walls and intercellular spaces — **no membrane** | No selectivity; bulk flow driven by evaporation and pressure — water and minerals to the endodermis |
| **Symplast** | Cytoplasm joined by plasmodesmata — one continuous symplasm | Gated by a size-exclusion limit (often ~1 kDa) — coordinated allocation of sugars, hormones and signals |
| **Transmembrane** | In and out of each membrane in turn | Selective at every step — the route wherever channels are absent or the apoplast is sealed |

ROOT WATER PATH: soil → apoplast in cortex → **BLOCKED at Casparian strip** → membrane → stele → xylem.

The **symplasm is functionally one compartment**: sugars, amino acids, small RNAs and even transcription factors move cell to cell — how a plant coordinates development without a nervous system. And **viruses exploit plasmodesmata**: they encode **movement proteins** that dilate the channels and thread their genome through, so systemic infection spreads cell to cell before it spreads through the vasculature (first met in [07 — Microbiology](../07-microbiology/)). Because the channels are gated, the plant can **callose-seal** them to wall off infection.

### Chloroplasts: why the plant never eats

Chloroplasts are the **double-membrane, 70S-ribosome, own-DNA** organelles of photosynthesis — the endosymbiotic signature covered in [04 — Energy and containment organelles](../02-cell-biology/04-energy-and-containment-organelles.md); light reactions run on **thylakoid membranes** (stacked into grana), carbon fixation in the **stroma**, mechanism in [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md). Fixed carbon arrives from the air, so the plant's problems become light capture, gas exchange and water — what epidermis, stomata and vasculature solve. **Not every cell has them:** all plastids differentiate from **proplastids** and become chloroplasts only where light permits, so root and pith cells are colourless.

### The large central vacuole

The **vacuole** is a single membrane-bound sac bounded by the **tonoplast**, and it can occupy up to ~90 % of cell volume. It does four jobs at once:

| Function | Mechanism | Consequence |
| --- | --- | --- |
| **Turgor** | Tonoplast **H⁺-ATPase** and **H⁺-pyrophosphatase** pump protons in, driving K⁺ and anion accumulation; water follows osmotically and the wall prevents further expansion | Hydrostatic skeleton and the force behind cell and organ expansion |
| **Storage** | Ions (K⁺, NO₃⁻), sugars and reserves held apart from cytoplasmic metabolism | Bulk reserves without cluttering the cytosol; **anthocyanins** at vacuolar pH give red and blue flower colour |
| **Defence** | Sequestered **alkaloids, tannins, glucosinolates**, sometimes latex, at concentrations toxic to herbivores | Released only when the cell is broken |
| **Lytic (lysosomal)** | **Acid hydrolases** — proteases, nucleases, glycosidases — at pH ~5, plus autophagic delivery of worn organelles | The plant's **lysosome**: same enzymes as an animal cell, different address tag |

Because water is cheap and the wall is stiff, **growth is mostly vacuolar expansion** — a cell multiplies its volume by filling one sac rather than synthesising cytoplasm. Losing turgor is a hydraulic failure, not a metabolic one, which is why wilting reverses as soon as water potential is restored.

### Leucoplasts, amyloplasts, gravity sensing

**Leucoplasts** are colourless plastids; the best known is the **amyloplast**, which makes and stores **starch** as dense granules. Because starch is dense, amyloplasts **sediment** — and the plant uses that as its gravity sensor.

| Plastid | Contents | Function |
| --- | --- | --- |
| **Chloroplast** | Chlorophyll a/b, carotenoids | Photosynthesis |
| **Chromoplast** | Carotenoids | Colour for pollinators and dispersers; ripening |
| **Amyloplast** (leucoplast) | Starch granules | Long-term storage — potato tuber, seed endosperm |

**Statoliths** — amyloplasts settling at the floor of root-cap **columella cells** — drive gravitropism:

```
amyloplasts sediment onto the lower ER/cortex
        │
        ▼
contact is transduced into an asymmetric AUXIN signal
        │
        ├─→ ROOT: high auxin below INHIBITS elongation → root bends DOWN
        └─→ SHOOT: high auxin below PROMOTES elongation → shoot bends UP
```

Same hormone, opposite responses in two organs — a preview of [05 — Plant hormones](05-plant-hormones.md).

### No centrioles

Higher plant cells have **no centrioles and no centrosome**. Microtubules are nucleated by **γ-tubulin ring complexes** at the nuclear envelope and at dispersed cytoplasmic sites, enough to organise a bipolar, **anastral** spindle. Because centrioles also template flagellar basal bodies, most plant sperm are **non-motile** and delivered by a pollen tube — see [06 — Plant reproduction and alternation of generations](06-plant-reproduction-and-alternation-of-generations.md).

### Cytokinesis: build a wall outward, or pinch a cell inward

Because each daughter must receive a **wall**, plant cytokinesis cannot constrict the equator; the machinery is assembled at the former spindle midzone instead.

```
ANIMAL CELL                              PLANT CELL
telophase                                telophase
   │                                        │
   ▼                                        ▼
actin–myosin II ring assembles           PHRAGMOPLAST array builds between
at the cortex round the equator          the daughter nuclei
   │                                        │
   ▼                                        ▼
ring contracts → CLEAVAGE FURROW         Golgi VESICLES of wall material
pinches membrane INWARD                  travel the phragmoplast, fuse at the
(no wall to make)                        CENTRE → CELL PLATE grows OUTWARD
   │                                        │
   ▼                                        ▼
daughters sealed by new plasma           plate fuses with the parental wall →
membrane                                 new wall + middle lamella completed
```

**Furrow inward where no wall must be made; grow outward from the centre where a wall must be constructed.** Upstream mitosis is in [11 — Mitosis and cytokinesis](../03-cellular-processes/11-mitosis-and-cytokinesis.md).

### Plant cell versus animal cell

| Feature | Plant cell | Animal cell | Mechanism behind the difference |
| --- | --- | --- | --- |
| **Cell wall** | Cellulose wall **outside** the membrane | Absent | Support by containing turgor |
| **Chloroplasts** | In green tissue | Absent | Autotrophy; plastids from an engulfed cyanobacterium |
| **Central vacuole** | Large, up to ~90 % of volume | Small transient vesicles only | Cheap expansion, storage, turgor |
| **Lysosomal digestion** | Delivered to the **vacuole** | Distinct M6P-targeted lysosomes | Same hydrolases, different address tag |
| **Centrioles** | Absent | Present | Dispersed γ-TuRC nucleation suffices in plants |
| **Cytokinesis** | **Cell plate** grows outward | **Cleavage furrow** pinches inward | A wall must be built between daughters |

## Plant tissues

### Meristematic cells versus permanent cells

A **tissue** is a group of cells with a shared structure and function; in plants the first division is between cells that divide and cells that have stopped.

| Property | **Meristematic cell** | **Permanent cell** |
| --- | --- | --- |
| Division | Divides continuously; small, cube-shaped, thin-walled | Has exited the cell cycle (may re-enter) |
| Vacuole | Many small vacuoles, no central one | **One large central vacuole** dominating volume |
| Cytoplasm and plastids | Dense, ribosome-rich; **proplastids** only | Thin peripheral layer; chloroplast, amyloplast or chromoplast |
| Wall | **Primary wall only**, flexible | May add **secondary wall** and lignify |
| Location and role | Shoot and root tips, cambia; high respiration, heterotrophic in the dark apex | Everywhere else; specialised for photosynthesis, conduction, storage or protection |

The meristem is the plant's **perpetual embryo** — it self-renews and never differentiates away, which is why growth is indeterminate. Cells leaving it **expand** far more than they divide (most growth is water entering the vacuole and stretching an existing wall) before taking one of the fates below.

**Simple versus complex tissues.** A **simple** tissue has **one** cell type (parenchyma, collenchyma, sclerenchyma, epidermis). A **complex** tissue has **two or more** cell types working as a unit — xylem (tracheids, vessels, fibres, parenchyma) and phloem (sieve elements, companion cells, fibres, parenchyma).

### The dermal system: the plant's skin

The **dermal tissue system** is a single outer layer of **epidermis** covered on aerial surfaces by a **cuticle** — **cutin** (a hydrophobic polyester) and wax secreted onto the outer wall. In dry air water would otherwise be lost across every square millimetre, so the cuticle makes the epidermis waterproof and **forces all gas exchange and water loss through regulated pores** — a valve rather than a leak — while screening UV. Thickness is a direct drought adaptation.

**Stomata and guard cells.** A **stoma** is a pore flanked by two **guard cells**, the variable valve for CO₂ in and water out:

```
light / low CO₂ / circadian signal reaches the guard cell
        │
        ▼
H⁺-ATPase activated → H⁺ pumped out → membrane hyperpolarises
        │
        ▼
inward K⁺ channels open; K+, Cl⁻ and malate²⁻ accumulate → Ψs falls
        │
        ▼
water enters by osmosis → guard cells TURGID
        │
        ▼
radial microfibrils make swelling circumferential:
cells BOW APART → PORE OPENS
```

Closure reverses the sequence: the stress hormone **abscisic acid (ABA)** opens anion efflux channels, depolarisation closes K⁺ influx and opens K⁺ efflux, solutes and then water leave, and turgor collapses — the plant's drought response, see [05 — Plant hormones](05-plant-hormones.md). Stomatal density and behaviour set the transpiration trade-off of [04 — Water transport and transpiration](04-water-transport-and-transpiration.md).

**Trichomes** are epidermal outgrowths with defensive or hydrodynamic functions: glandular ones secrete **resins, essential oils and sticky exudates** that poison or trap insects; non-glandular ones trap still air to cut transpiration, reflect light and obstruct small herbivores. **Cork cells** of the periderm are a specialised derivative — suberised, dead, and replacing the epidermis in woody stems.

### The ground system: filler, factory, framework

Ground tissue lies between dermal and vascular systems and is subdivided by wall behaviour — really by **mechanical strategy**.

| | **Parenchyma** | **Collenchyma** | **Sclerenchyma** |
| --- | --- | --- | --- |
| Wall | Thin, **primary only** | Unevenly thickened **primary** wall (cellulose + pectin, no lignin) | Thick **secondary** wall, usually **lignified** |
| Living at maturity? | **Living** | **Living** | **Dead** |
| Why that status | Needs cytoplasm to photosynthesise, store and **divide again** for repair | Must stay alive to keep depositing wall as the organ elongates | Lignified wall is complete before death; a hollow fibre needs no metabolism |
| Main jobs | **Photosynthesis** (mesophyll), storage, secretion, regeneration | **Flexible, extendable support** in petioles, veins, young stems | **Rigidity and tensile strength**: fibres, sclereids (grit in pear, seed coats) |
| Key point | **Dedifferentiates** — basis of callus and totipotency | The living guywire | Structure outlives the cell |

The living/dead distinction is mechanical, not accidental: **support that must keep pace with a growing organ has to be laid down by a living cell; support for an organ that has finished growing can be a dead, lignified skeleton.** The vascular system takes this to its extreme.

### The vascular system

**Xylem** carries water and minerals upward under tension; **phloem** moves sugar solution in both directions under positive pressure. Xylem tracheids and vessel elements are **dead at maturity** — hollow, lignified pressure tubes — while phloem sieve elements stay alive but enucleate, depending on companion cells. Anatomy and physiology are the subject of [03 — Xylem and phloem](03-xylem-and-phloem.md).

## Meristems: where growth comes from

### Apical versus lateral meristems

| | **Apical meristems** | **Lateral meristems** |
| --- | --- | --- |
| Position | **Shoot apex and root apex** — the tip of every axis | In the axis: **vascular cambium** and **cork cambium** (phellogen) |
| Direction added | **Lengthwise** — primary growth | **Radially** — girth, secondary growth |
| Produced | Protoderm → epidermis; ground meristem → cortex/pith; procambium → primary xylem and phloem | Vascular cambium → **secondary xylem (wood)** inward, secondary phloem outward; cork cambium → **periderm** outward |
| Result | The **primary body**: roots, stems, leaves | The **secondary body**: wood, bark, annual rings |

### Primary growth → lateral meristems → secondary growth

```
APICAL MERISTEM (shoot tip + root tip)
        │  division + elongation = PRIMARY GROWTH
        │  protoderm ─────────► EPIDERMIS
        │  ground meristem ───► CORTEX, PITH
        │  procambium ────────► PRIMARY XYLEM + PRIMARY PHLOEM
        ▼
PRIMARY PLANT BODY — length established
        │  fascicular + interfascicular cambium fuse into a RING
        ▼
LATERAL MERISTEMS ESTABLISHED
        ├── VASCULAR CAMBIUM → secondary xylem inward,
        │                      secondary phloem outward
        └── CORK CAMBIUM ────→ CORK + PHELLODERM = PERIDERM
                               (an epidermis cannot stretch over a
                                widening axis, so it is replaced)
        ▼
SECONDARY GROWTH — girth, wood, bark, ANNUAL RINGS
```

**Annual rings** read out cambial seasonality: wide, thin-walled **early wood** from spring, narrow, thick-walled **late wood** from autumn — one boundary, one year.

### Why plant growth is indeterminate

| Reason | Mechanism |
| --- | --- |
| **The meristem never differentiates away** | Apical meristems self-renew through a stem-cell niche that continuously regenerates dividing cells, and growth continues only while resources allow |
| **Growth is modular** | Node, internode, leaf and axillary bud repeat indefinitely — a list of repeats, not a finished shape |
| **Cells can dedifferentiate** | Mature parenchyma re-enters the cell cycle to rebuild meristems (cambium, wound callus) — the basis of totipotency |
| **No sequestered germline** | Gametes arise late from meristems, so vegetative and reproductive fates stay interchangeable (see [06 — Plant reproduction and alternation of generations](06-plant-reproduction-and-alternation-of-generations.md)) |

The practical consequence is regeneration: one somatic cell in a wound can rebuild a whole plant, which underpins callus culture, micropropagation and grafting.

## Relevance to medicine and agriculture

**Plant-derived medicines are not a quaint aside.** Secondary metabolites made for defence are borrowed as drugs: **morphine** and **codeine**, **quinine**, **atropine**, **colchicine** (binds tubulin — a mitotic poison precisely because plant and animal microtubules are the same machine), **digoxin**, **paclitaxel** (yew, microtubule stabiliser) and **vincristine/vinblastine** (periwinkle, used in leukaemia). Toxicology and therapy are two faces of one molecule.

**Humans cannot digest cellulose** — we lack cellulase, so β-1,4-glucan passes as **dietary fibre**, fermented by gut microbiota to short-chain fatty acids. "Why is fibre not energy-yielding for us?" is answered entirely by the wall chemistry above.

**Herbicide selectivity mirrors antibiotic selectivity.** **Glyphosate** inhibits **EPSP synthase** of the shikimate pathway, which plants and bacteria have and **animals lack**; synthetic auxins such as **2,4-D** exploit the differential auxin response of broadleaf dicots versus grasses. Target-site resistance in weeds is the agricultural analogue of antibiotic resistance.

**Agriculture is applied cell biology:**

| Practice | Principle from this chapter |
| --- | --- |
| **Meristem-tip culture** | Meristems are typically **virus-free** (no vascular connection yet, plus strong RNA silencing) → virus-indexed stock plants |
| **Micropropagation** | **Totipotency** of parenchyma: a somatic cell can be reset and regenerated — clonal propagation at scale |
| **Grafting** | Scion and rootstock **cambia** must align so their layers fuse and restore continuous xylem and phloem |
| **Drought-tolerant lines** | Selection on **stomatal density and aperture**, cuticle thickness, vacuolar osmotic adjustment |
| **Timber, cork, fibre** | Wood = **secondary xylem**; cork = **cork cambium** product; linen = phloem **sclerenchyma fibres**; cotton = epidermal **trichomes** |
| **Post-harvest losses** | Cuticle damage, wound **periderm** formation, browning when vacuolar phenolics meet oxidases |

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The wall is outside the membrane, so nutrients cross the wall instead of the membrane" | The wall is **porous and non-selective**; the **plasma membrane is still the only selective barrier**, and every solute crosses it. |
| "Plant cells have no lysosomes" | Acid hydrolysis runs in the **vacuole** (tonoplast + hydrolases at low pH). Same chemistry, different compartment name. |
| "All plant cells contain chloroplasts" | Only light-exposed cells do; roots, pith and storage tissue hold **amyloplasts/leucoplasts** or proplastids. |
| "Collenchyma and sclerenchyma are the same" | **Collenchyma** = living, unevenly thickened **primary** wall, supports growing organs; **sclerenchyma** = **dead**, lignified **secondary** wall, supports finished organs. |
| "Turgor pressure is the same as osmotic pressure" | Ψs is the *tendency to take up* water; Ψp is the *wall's push back*. **Ψ = Ψs + Ψp**; turgor is the positive Ψp produced when water is trapped. |
| "Plasmodesmata are gap junctions" | Both are cytoplasmic channels, but plasmodesmata contain an **ER-derived desmotubule** and cross a wall; gap junctions are pure protein. |
| "Plants grow mainly by dividing cells" | Most volume increase is **cell EXPANSION** — water entering the vacuole and stretching the wall. Division sets cell number, expansion sets size. |
| "Stomata open simply because guard cells swell" | They swell **because solutes are pumped in first** (H⁺-ATPase → K⁺ influx → osmotic water entry). No active step, no turgor, no opening. |
| "Secondary growth happens in every plant" | It needs **lateral meristems** (vascular and cork cambia); grasses and most herbs grow almost entirely by primary growth. |

## Key facts

- A plant cell differs from an animal cell by **wall, chloroplasts, and a large central vacuole** — each a mechanism: turgor instead of a skeleton, photosynthesis instead of ingestion, pressure instead of pumps.
- The wall is a composite: **cellulose microfibrils** (tension), **hemicellulose** (cross-links), **pectin** (charged gel and cellular glue) — a tensile skeleton around an internal pressure vessel.
- **Primary wall** is laid down during growth; **secondary wall** is thick and lignified, laid down after; **lignin** adds compressive strength and waterproofing, which lets xylem hold water under tension.
- **Turgor** follows osmotic water influx trapped by the wall: **Ψ = Ψs + Ψp**; losing it causes wilting and stomatal closure.
- The wall lies **outside** the plasma membrane and is non-selective, so the membrane remains the sole gate, energised by the **H⁺-ATPase**; the **Casparian strip** seals the apoplast in the endodermis.
- **Plasmodesmata** join cytoplasm into a continuous **symplast**; the **apoplast** is the wall route; viruses spread by dilating these channels, and the plant answers by depositing **callose**.
- All plastids derive from **proplastids**: **chloroplasts** only in light-exposed cells, **amyloplasts** for starch storage, and sedimented **statoliths** for gravity sensing.
- The **vacuole** generates turgor, stores ions, sugars, pigments and defence compounds, and performs the **lysosomal** hydrolytic function at low pH.
- Higher plants have **no centrioles** (the spindle is anastral), and cytokinesis builds a **cell plate outward** from a phragmoplast rather than pinching inward — because a wall must be constructed.
- Three tissue systems: **dermal** (epidermis, cuticle, stomata, trichomes), **ground** (parenchyma living, collenchyma living, sclerenchyma dead), **vascular** (xylem and phloem — [03 — Xylem and phloem](03-xylem-and-phloem.md)). **Simple** tissue = one cell type; **complex** = several acting as a unit.
- **Apical meristems** give primary growth (length); **lateral meristems** — vascular and cork cambia — give secondary growth (girth); growth stays **indeterminate** because meristems self-renew and organs repeat modularly.
- Meristems are hormonally controlled ([05 — Plant hormones](05-plant-hormones.md)) and build the organs detailed in [02 — Roots, stems, and leaves](02-roots-stems-and-leaves.md).

## Practice questions

**1. The mechanical logic of the plant cell wall is best summarised by which statement?**

A. Cellulose resists compression while pectin resists tension, so the two are interchangeable
B. Crystalline cellulose microfibrils resist the tension generated by turgor, while lignin supplies compressive strength after growth
C. The wall is a passive skeleton requiring no metabolic input to maintain
D. Pectin provides the tensile strength holding the cell together during wilting

**Answer: B**

Explanation: Turgor creates an outward tensile load, and hydrogen-bonded crystalline cellulose resists stretching while lignin supplies compressive resistance after growth. Pectin is a hydration gel controlling porosity and adhesion, not the tensile element (A, D), and wall loosening and lignification are energy-consuming (C).

---

**2. Lignification matters so much for the plant because it**

A. Makes the wall permeable so water can enter the cell
B. Allows continued rapid elongation of young cells
C. Waterproofs and stiffens the wall, letting conduits withstand negative pressure and giving wood compressive strength
D. Is required for plasmodesmata to function

**Answer: C**

Explanation: Lignin makes the wall hydrophobic and rigid — necessary if a xylem element is to carry water under tension without leaking or collapsing, and the source of wood's hardness. Lignification follows the end of growth, so it opposes elongation (B), reduces permeability (A), and is unrelated to plasmodesmata (D).

---

**3. A solute moving exclusively through the apoplast crosses**

A. The plasma membrane of every cell it passes
B. Only cell walls and intercellular spaces, never crossing a membrane until it is blocked or absorbed
C. The vacuole of each cell
D. Plasmodesmata and their desmotubules

**Answer: B**

Explanation: The apoplast is the continuum of walls and intercellular air spaces — bulk movement with no membrane crossing and no selectivity — which is why the suberised Casparian strip can force solutes back across a membrane. Crossing a membrane at every cell is the transmembrane route (A), and passing through plasmodesmata is the symplast (D); vacuoles belong to neither (C).

---

**4. Plant viruses spread cell to cell primarily by**

A. Being excreted into the xylem and re-entering cells at a distance
B. Encoding movement proteins that dilate plasmodesmata and thread viral nucleic acid through
C. Budding through the cuticle into adjacent epidermal cells
D. Being taken up by phagocytosis

**Answer: B**

Explanation: Because plant cells are wall-bound and joined by plasmodesmata, viruses widen the cytoplasmic sleeve and move genome complexes symplastically — which is why callose sealing defends the plant. Vascular spread depends on this step; plants do not phagocytose (D), and cuticular budding (C) is not how they propagate.

---

**5. The large central vacuole contributes to plant growth mainly by**

A. Dividing repeatedly to increase cell number
B. Accumulating solutes so water enters osmotically, expanding the cell by stretching the existing wall with little new cytoplasm
C. Synthesising cellulose for the wall
D. Replacing the nucleus in mature cells

**Answer: B**

Explanation: Vacuolar solutes draw in water and the resulting pressure stretches the wall, so most volume increase is expansion rather than new biomass. Cellulose is synthesised at the plasma membrane by cellulose synthase complexes (C); vacuoles do not create cells (A) and never replace the nucleus (D).---

**6. Sedimentation of amyloplasts in the root cap is significant because it**

A. Anchors the root to soil particles
B. Breaks the wall to release growth inhibitors
C. Provides the gravity-sensing step that triggers asymmetric auxin distribution and downward root bending
D. Triggers immediate cell division at the root tip

**Answer: C**

Explanation: Dense starch-filled amyloplasts (statoliths) settle on the lower side of columella cells, and that sedimentation is transduced into an asymmetric auxin signal; in roots the higher auxin below inhibits elongation, so the root curves downward. Their role is storage and sensing, not anchoring (A); they rupture nothing (B) and redirect growth rather than initiating division (D).

---

**7. Guard cells open a stomatal pore by**

A. Losing solutes and water so they collapse toward each other
B. Pumping protons out, taking up potassium and anions, then entering osmotically and bowing apart
C. Contracting an actin ring round the pore
D. Secreting wax into the pore to widen it

**Answer: B**

Explanation: Activation of the H⁺-ATPase hyperpolarises the membrane and opens inward K⁺ channels; Cl⁻ and malate²⁻ follow, water enters osmotically, and radial microfibrils convert swelling into outward bowing that opens the pore. A describes closure; guard cells have no contractile ring (C — that is animal cytokinesis), and wax secretion (D) belongs to the cuticle.

---

**8. The difference between plant cell plate formation and an animal cleavage furrow is best explained by**

A. Plants dividing more slowly than animals
B. The need to construct a new wall between plant daughter cells, so Golgi vesicles fuse outward, whereas animal cells with no wall to build pinch inward
C. Animal cells lacking a Golgi apparatus
D. The absence of microtubules in plant cells

**Answer: B**

Explanation: Direction follows function — a wall must be fabricated from the centre outward, so phragmoplast-guided vesicles build a plate that fuses with the parental wall, while an actin–myosin ring simply constricts the membrane when nothing must be built. Speed is irrelevant (A), animal cells have abundant Golgi (C), and plant cells use microtubules extensively (D).

---

**9. Which tissue is correctly matched with its living status and function?**

A. Parenchyma — dead at maturity — conducts water
B. Collenchyma — living — flexible support of elongating organs
C. Sclerenchyma — living — stores starch in the seed
D. Vessel element — living — maintains cytoplasmic streaming

**Answer: B**

Explanation: Collenchyma stays alive because it must keep depositing primary wall material while the organ it supports elongates. Parenchyma is living and serves storage, photosynthesis and regeneration rather than conduction (A); sclerenchyma is dead with a lignified secondary wall (C); vessel elements are dead hollow tubes (D).

---

**10. A woody stem increases in girth because of**

A. Continued activity of apical meristems producing wider leaves
B. Intercalary meristems adding a layer to each internode
C. Lateral meristems — the vascular cambium adding secondary xylem inward and secondary phloem outward, plus the cork cambium producing periderm
D. Epidermal cells dividing laterally beneath the cuticle

**Answer: C**

Explanation: Girth is secondary growth, produced by the vascular cambium (wood inward, secondary phloem outward) and the cork cambium, whose periderm replaces an epidermis that cannot stretch over a widening axis. Apical meristems add length only (A), intercalary meristems add length at grass internode bases (B), and the epidermis has no meristematic activity (D).
