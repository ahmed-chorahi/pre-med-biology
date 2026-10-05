# Roots, Stems, and Leaves

## Why it matters

A plant cannot go looking for what it needs: no limbs, no circulation, no thermostat, no escape from hostile soil or a week of drought. It must solve **three separate engineering problems at once**, in two media it cannot control — with three organs.

| Organ | The problem | The anatomical answer | The price it pays |
| --- | --- | --- | --- |
| **Root** | Anchor a top-heavy body in shifting soil; extract dilute water and minerals from films around soil particles; decide what enters the vascular system | Huge surface area (root hairs), concentric layers, a **selective checkpoint** (endodermis) guarding a central pipeline | Grows blind through abrasive grit, and must rupture its own tissues to branch |
| **Stem** | Lift water metres against gravity, carry sugars down, hold leaves in the light, resist wind with no skeleton | Two separate pipelines (xylem, phloem) in a ring or scattered; **secondary growth** thickens from within | Must keep the pipelines separate, uncrushed, joined root tip to leaf |
| **Leaf** | Capture light and absorb CO2 while losing as little water as possible — two goals that **directly oppose each other** | Transparent chloroplast-rich tissue; connected air spaces; a sealed waxy surface with **metered pores** | Must open its interior to the atmosphere, which is how it loses water and pathogens |

Anatomy is only memorable when read as engineering:

```
ROOT  soil films hold water in tiny pores
        -> huge surface area (ROOT HAIRS)
        -> bulk flow through the APOPLAST (cell walls)
        -> a WAXY BAND (Casparian strip) seals that route
        -> water is forced across selectively permeable membranes
        -> a central pipeline (xylem) carries it upward
STEM  a water column is pulled up a dead, hollow, reinforced
      pipe (xylem = WOOD); sugars are pushed down a living pipe
      (phloem); bundles lie in a RING (dicot) or SCATTERED
      (monocot); a lateral meristem thickens the axis
LEAF  light from above -> chloroplasts stacked near the top
      (PALISADE); CO2 reaches every cell through loose SPONGY
      tissue of connected air spaces entered via a STOMA, while
      water escapes by the same pore, so CUTICLE seals the rest
      and GUARD CELLS meter the opening
```

Three design rules recur in all three organs and make the detail predictable: **(1) where exchange happens, surface area is amplified** — root hairs, broad cortex, spongy air spaces, vein density; **(2) every sealed barrier is broken in exactly one controlled place** — cuticle broken only by stomata, porous apoplast broken only by the endodermal suberin band; **(3) substances moving in opposite directions need separate conduits** — xylem (dead, under tension) beside phloem (alive, under pressure).

The building blocks — **parenchyma**, **collenchyma**, **sclerenchyma**, **xylem**, **phloem**, and the primary and lateral meristems — are defined in [01 — Plant cells and tissues](01-plant-cells-and-tissues.md); this chapter assembles them into organs. The physics they exploit (diffusion, osmosis, water potential) is [02 — Passive transport](../03-cellular-processes/02-passive-transport.md), and tissue-level conduction is deferred to [03 — Xylem and phloem](03-xylem-and-phloem.md).

## Root: anchorage and absorption

### Zones of the root tip

The root tip is a **developmental assembly line**: cells are made at one end, pushed forward, stretched, then specialised. Each zone exists because the previous job must finish before the next can start.

| Zone | What happens | Why it must happen there |
| --- | --- | --- |
| **Root cap (calyptra)** | Sacrificial shield, sloughed and replaced continuously; secretes **mucigel**; contains **statocytes** whose starch-filled **amyloplasts sediment** downward | The meristem would be shredded by grit; gravity sensing tells the root where water and anchorage are |
| **Cell division (meristematic)** | Small cells, dense cytoplasm, thin walls, no large vacuole, dividing actively | New cells must be made behind the shield so the axis keeps advancing |
| **Elongation** | Cells expand **10–100-fold in length** as water enters the enlarging vacuole and walls loosen | The only zone that generates **thrust** — what drives the root through soil |
| **Maturation** | Walls thicken; vascular tissues differentiate; epidermal cells grow **root hairs** | Absorption needs mature, thin-walled epidermis, not dividing cells |

Two consequences follow. **Absorption happens behind the tip, not at it**, so a root racing through dry soil is temporarily a poor absorber. And **root hairs are single-celled extensions of epidermal cells** (trichoblasts), not tiny branches: one cell pushes out a long tube for one cell's cytoplasm, and since hairs last only days the maturation zone replaces them continuously.

Gravitropic bending is an **auxin** response: sedimented amyloplasts trigger lateral auxin redistribution, and because root cells are highly auxin-sensitive the higher-auxin side elongates more slowly, curving the root downward. Hormone signalling is covered in [05 — Plant hormones](05-plant-hormones.md).

### Epidermis, cortex, endodermis, pericycle

Moving inward from the soil, a young root is concentric layers, each with one job:

| Layer | Composition | Job and rationale |
| --- | --- | --- |
| **Epidermis (rhizodermis)** | One layer of thin-walled cells, many with root hairs | Absorption; thin unpigmented walls shorten the diffusion path |
| **Cortex** | Many layers of **parenchyma** with large air spaces; stores starch | The loose **apoplast** (cell-wall continuum) lets water flow with almost no resistance |
| **Endodermis** | Innermost cortex; every radial and transverse wall banded with **suberin** — the **Casparian strip** | The one place the wall-to-wall route is sealed, so all must cross a membrane |
| **Pericycle** | Just inside the endodermis; parenchyma keeping meristematic capacity | Origin of **lateral roots**; in dicots it also feeds the vascular and cork cambia |
| **Vascular cylinder (stele)** | Xylem and phloem, pith in many monocots | The protected central pipeline |

### The Casparian strip: the plant's selective checkpoint

Three routes exist for water and solutes crossing a root:

| Route | Pathway | Selectivity |
| --- | --- | --- |
| **Apoplast** | Cell walls and air spaces — a continuous **non-living** phase | **None**: solutes ride with bulk flow because no membrane is crossed |
| **Symplast** | Cytoplasm linked by **plasmodesmata** (plus the crossing of each wall) | **Total**: every step crosses a selectively permeable membrane |

```
water + dissolved ions arrive from the soil
        |
cortex: APOPLAST - bulk flow through porous walls,
        NO MEMBRANE CROSSED, so nothing is selected
        |
ENDODERMIS: walls banded with SUBERIN (waxy, hydrophobic)
        -> apoplast SEALED; water and solutes must pass THROUGH
           the plasma membrane of the endodermal cell
        -> transporters decide: K+, nitrate, phosphate pass;
           excess Na+, heavy metals, pathogens are excluded
        v
symplast resumes inside the stele -> XYLEM
        |
the vetted stream enters the transpiration pull described in
[04 — Water transport and transpiration](04-water-transport-and-transpiration.md)
```

**Why this is the plant's kidney.** Just as a renal tubule reclaims what the body needs by forcing fluid across an epithelium of transporters, the endodermis converts an unselective bulk flow into a **vetted symplastic stream**; without the strip a root would equilibrate with the soil solution. Salt and metal exclusion are concentrated here; toxic analogues such as **arsenate (mimics phosphate)** and **selenate (mimics sulphate)** still slip through by impersonating nutrients; older roots add a second gasket, the **exodermis**; and thin-walled **passage cells** opposite the protoxylem let bulk flow through when the stream is strong, so the checkpoint is regulated, not absolute.

### The two root blueprints, and root bark

The arrangement of xylem and phloem in the stele separates the two great angiosperm lineages:

| Feature | Dicot root | Monocot root |
| --- | --- | --- |
| **Xylem** | **Diarch–tetrarch**: 2–4 arms converging at the centre (X, Y or star) | **Polyarch**: many arms in a ring |
| **Pith** | Absent — xylem fills the centre | Present — a core of parenchyma |
| **Phloem** | Patches between the xylem arms | Patches between the xylem arms |
| **Cambium** | Arises later from pericycle and phloem margin | Usually absent |
| **Secondary growth** | Common — roots thicken and become woody | Rare; a few monocots form an anomalous meristem |
| **Older roots** | Periderm (**root bark**) replaces epidermis and cortex | Epidermis often persists |

```
DICOT ROOT - transverse section (tetrarch)

======== epidermis + ROOT HAIRS ========
|| CORTEX: parenchyma, air spaces, starch ||
||   water moves here in the APOPLAST     ||
||  .---------------------------------.   ||
||  | ENDODERMIS: suberin (Casparian)  |   ||
||  |  .---------------------------.   |   ||
||  |  | PERICYCLE (lateral roots)  |   |   ||
||  |  |   phloem  *     *  phloem   |   |   ||
||  |  |        \   XYLEM   /        |   |   ||
||  |  |         \  arms   /  proto- |   |   ||
||  |  |          \______/  xylem at |   |   ||
||  |  |           \    /   arm tips |   |   ||
||  |  +---------------------------+   |   ||
||  +---------------------------------+   ||
==========================================

 DICOT: 2-4 arms meeting at the centre, NO pith
 MONOCOT: many arms in a ring around a central PITH
```

**Lateral roots are endogenous.** **Pericycle** cells resume division, form a primordium, and *force their way out* through cortex and epidermis — unlike a stem branch, which grows outward from surface tissues without rupturing anything. The wound left behind is one reason root-borne pathogens gain entry.

**Root bark.** As a dicot root ages it stops absorbing and becomes a pure conduit and anchor: cortex and epidermis are sloughed, and a **cork cambium** arising largely from the pericycle produces a **periderm** of suberised, dead **cork cells**. Young root tissue absorbs; old root tissue conducts and protects.

## Stem: conduction and support

### The ground plan

| Tissue | Position | Job and rationale |
| --- | --- | --- |
| **Epidermis + cuticle** | Outermost | Waterproofs the aerial surface — the solution the leaf also uses |
| **Collenchyma** | Beneath the epidermis of young dicot stems, in strands | Living, extensible walls support the stem while it elongates; sclerenchyma would lock it in place |
| **Cortex** | Outside the vascular ring | Storage and radial transport; often photosynthetic |
| **Vascular bundles** | Ring (dicot) or scattered (monocot) | Conduction plus tensile reinforcement — their fibres act as embedded cables |
| **Pith** | Centre | Stores water and starch; the core the bundles wrap around |

### Eustele versus atactostele: the two stem blueprints

| Feature | Dicot stem — **eustele** | Monocot stem — **atactostele** |
| --- | --- | --- |
| **Bundles** | A tidy **ring** | **Scattered** through the ground tissue, denser near the edge |
| **Ground tissue** | Distinct **cortex** and **pith** | One continuous ground tissue; no cortex–pith boundary |
| **Bundle type** | **Open**: xylem within, phloem without, **fascicular cambium** between | **Closed**: no cambium; xylem arcs with a **protoxylem lacuna**, capped by sclerenchyma |
| **Support** | Collenchyma strands under the bundles | Sclerenchyma **bundle caps** as embedded rods |
| **Secondary growth** | Yes — a complete cambial ring forms | Generally no |
| **Mechanical logic** | A hollow tube: material at the circumference resists bending efficiently | Reinforced concrete: rods throughout resist force from any direction |

The eustele is a **dissected protostele**: the ancestral solid vascular cylinder split into bundles around a parenchymatous pith. A peripheral ring leaves continuous meristem available for thickening; scattered bundles give up that ring but stiffen the whole section — a good solution for a plant that will never thicken.

**Primary growth** is the work of the **apical meristems**: it produces the entire primary body — epidermis, ground tissue, primary xylem and phloem, leaves and lateral buds — from leaf primordia at the shoot apex. Every organ here begins as primary tissue.

### Secondary growth: how a stem becomes woody

```
fascicular + interfascicular cambium (ray parenchyma
de-differentiates between bundles) = a continuous RING of
VASCULAR CAMBIUM, which divides tangentially:
        +-> INWARD  : SECONDARY XYLEM = WOOD
        +-> OUTWARD : SECONDARY PHLOEM = inner bark
cork cambium (phellogen):
        +-> outward : CORK (phellem), suberised and dead
        +-> inward  : phelloderm
   = PERIDERM = outer BARK
```

Three points separate understanding from memorisation:

1. **The cambium adds inward and outward in fixed proportions.** It sits between xylem and phloem and stays there, so each tangential division sends one cell to the pith and one to the cortex. Diameter increases **from the inside**: the oldest xylem ends up at the core, the oldest phloem crushed against the cortex.
2. **Wood is secondary xylem, nothing else.** Older phloem and cortex are crushed and shed as the periderm expands, which is why bark splits and shows **lenticels**. **Bark is everything outside the vascular cambium** — secondary phloem, cortex, and periderm together.
3. **The inner xylem stops conducting.** Outer **sapwood** has functioning vessels; inner **heartwood** is blocked by **tyloses** and filled with tannins and resins — a working pipe turned pillar.

### Annual rings: a dated record of cambial activity

| | **Earlywood (springwood)** | **Latewood (summerwood)** |
| --- | --- | --- |
| **When** | Early season, water abundant, auxin high from expanding shoots | Late summer to autumn, growth slowing |
| **Cells** | Large-diameter vessels and tracheids, **thin walls** — pale, low density | Narrow cells, **thick walls** — dark, high density |
| **Dominant job** | **Conduction** — maximum cross-section for flow | **Support and safety** — resistance to collapse and air embolism |

**One ring equals one year in a seasonal climate**, which turns a trunk into a dated archive: **dendrochronology** dates timber, fires, floods, and droughts and calibrates radiocarbon dating. Two cautions: tropical trees without a strong dry season may produce **no rings**, and ring width records **resources, not the calendar** — a narrow ring means a bad year, not a short one. Rings are not bark: they are successive crops of **secondary xylem**.

## Leaf: gas exchange and light capture

The leaf faces one unresolvable conflict: photosynthesis needs the interior open to air, while transpiration requires it sealed from air. The answer is a **sealed surface (cuticle) with a metered breach (stoma)**, plus an interior that delivers CO2 to every cell over the shortest possible liquid-phase path.

### Cuticle and epidermis: sealed and transparent

| Feature | Structure | Function and rationale |
| --- | --- | --- |
| **Cuticle** | **Cutin** impregnated with **waxes**, secreted by the epidermis | Cuts **cuticular transpiration** to near zero; without it a leaf would desiccate in hours and evaporation could not be regulated |
| **Epidermis** | One layer of tightly fitted transparent cells, **without chloroplasts** (guard cells excepted) | Light passes unhindered to the mesophyll; pigment-free cells do not waste photons |

Because the cuticle is impermeable to gases, **all CO2 entry and all water loss must pass through pores**, which makes the stoma the most consequential structure in plant physiology.

### Stomata and guard cells: the metering valve

A **stoma** is a pore flanked by two **guard cells**. In dicots they are kidney-shaped, with **walls thickened on the pore side and thin on the far side**; in grasses they are dumb-bell shaped with subsidiary cells. Guard cells are the only epidermal cells with chloroplasts, and they are packed with mitochondria — a cell that spends energy to regulate a pore.

**Opening is osmotic, not mechanical:**

```
blue light sensed by the guard cell, or CO2 falling inside it
        |
H+-ATPase pumps PROTONS OUT -> membrane hyperpolarises
        -> inward K+ channels open; K+ floods in, with Cl- and
           malate2- to balance the charge
        v
water potential falls -> water enters by OSMOSIS
        (02 — Passive transport); turgor rises; radial
        microfibrils restrict sideways swelling, so the cells
        lengthen more than they widen and BOW APART
        -> STOMA OPENS
```

**Closing** reverses the sequence and is driven mainly by **abscisic acid (ABA)** in drought: anion channels open, ions leave, water follows, the cells go flaccid — hormonal control in [05 — Plant hormones](05-plant-hormones.md). The trade-off is unavoidable: every CO2 molecule admitted costs water vapour escaping, so stomata balance **carbon gain against water loss**, the ratio called **water-use efficiency**.

### Mesophyll: why the interior is layered

Light arrives directionally; gases diffuse freely in air but roughly **10,000 times more slowly in water**. The two mesophyll layers answer those two facts.

| | **Palisade mesophyll** | **Spongy mesophyll** |
| --- | --- | --- |
| **Cells** | Columnar, tightly packed, perpendicular to the upper surface | Irregular, loosely packed |
| **Position** | Upper (adaxial), under the transparent epidermis | Lower (abaxial) |
| **Chloroplasts** | Very many per cell | Fewer |
| **Air spaces** | Minimal | Large, interconnected, continuous with the **substomatal cavity** |
| **Job** | **Intercept light** where photons first arrive (light drops steeply with depth); chloroplasts move to periclinal walls in strong light, spread in dim light | **Gas exchange** — CO2 reaches every cell over a short, branched path, travelling as gas and crossing water only at the last cell surface |

The **substomatal cavity**, the humid pocket beneath each stoma, is a saturated reservoir: evaporation occurs from a limited surface rather than from every mesophyll cell, and the path from pore to first cell stays short.

### Veins, bundle sheath, and the C4 variant

Each vein has **xylem above** (water from the root) and **phloem below** (sugar to the rest of the plant), wrapped in a **bundle sheath**.

| Structure | Function and rationale |
| --- | --- |
| **Vein** | Water to every photosynthesising cell; sugar away, or feedback stops photosynthesis |
| **Bundle sheath** | Regulates symplastic movement between vein and mesophyll — a controlled interface, not a leak; sclerenchyma extensions to the epidermis add support and a water route past mesophyll |
| **Vein density** | Higher density shortens the liquid-phase path for CO2 and correlates with maximum photosynthetic rate |

**C4 (Kranz) anatomy.** C3 plants lose productivity because Rubisco also fixes O2 (**photorespiration**) when stomata partly close on a hot day. C4 plants — maize, sorghum, sugarcane, millet — solve this *anatomically*:

```
MESOPHYLL CELL: CO2 + PEP --(PEP carboxylase)--> 4-carbon acid
        | plasmodesmatal transfer
        v
BUNDLE SHEATH CELL (large, thick-walled, chloroplast-rich)
        4-carbon acid DECARBOXYLATED -> high [CO2] around Rubisco
        -> photorespiration suppressed; stomata can partly close
        -> WATER USE EFFICIENCY RISES
```

The two stages are split between two cell types in two anatomical compartments — which is why Kranz anatomy is a **leaf** feature, not a biochemistry footnote. The Calvin cycle itself is in [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md).

### Monocot versus dicot leaf

| Feature | Dicot leaf (**dorsiventral**) | Monocot leaf (**isobilateral**) |
| --- | --- | --- |
| **Venation** | Reticulate | Parallel |
| **Mesophyll** | Differentiated into palisade and spongy | Often undifferentiated, similar on both faces |
| **Stomata** | Mainly the **lower** surface | Roughly equal on **both** surfaces |
| **Why** | The upper face takes direct sun and would transpire fastest, so shading the pores cuts loss | The blade is vertical, so neither face is consistently the hot one |
| **Bulliform cells** | Absent | Large water-storage epidermal cells in grasses; losing turgor **rolls the leaf inward**, trapping humid air |
| **Bundle sheath** | Present, extensions often to the lower epidermis | Prominent; extensions often reach both epidermes |

```
LEAF - transverse section (dorsiventral dicot)

 sunlight  v  v  v  v  v
================================================
|| cuticle: cutin + wax - waterproof,        ||
|--------------------------------------------|
| upper epidermis - transparent, no plastids |
|--------------------------------------------|
| || || || || || || || || || || || || ||     | PALISADE
| || || || || || || || || || || || || ||     | MESOPHYLL
|--------------------------------------------|
| .  .   .  .   AIR SPACES ~~~~~~~~~~~~~~~  | SPONGY
|  (CO2 travels as a gas to every cell)     | MESOPHYLL
|  below it the SUBSTOMATAL cavity (humid)  | reservoir
|--------------------------------------------|
| lower epidermis _________                  |
|                \ STOMA /  <- most pores   |
'---------------\_______/--------------------'
                 guard cells (turgid = open)

```

## Relevance to medicine and agriculture

| Area | Why the anatomy decides the outcome |
| --- | --- |
| **Contaminated soil and the food chain** | Cadmium, arsenic, lead and selenium enter crops through the root transporters behind the Casparian strip, because toxic analogues impersonate phosphate and sulphate; the checkpoint reduces but cannot abolish uptake |
| **Plant toxins and drug sources** | The organ holding a compound decides which part is poisonous: solanine in potato skin, cyanogenic glycosides in cassava roots (grated, fermented, dried), oxalate in rhubarb leaves, cardiac glycosides in *Digitalis* leaves, nicotine made in roots but stored in leaves. Paclitaxel, vinca alkaloids and artemisinin are organ-specific harvests |
| **Stomata as a portal** | Pathogens such as *Pseudomonas syringae* force stomata open or block their closing, and the plant responds by shutting them — **stomatal immunity**. Cuticle and epidermis do the job your skin and mucosa do; see [07 — Microbiology](../07-microbiology/) |
| **Agriculture and drought** | Irrigation, mulching and deep-root breeding keep supply ahead of stomatal demand; **C4 crops** (maize, sorghum, sugarcane) use Kranz anatomy to tolerate heat and partial closure; sunken stomata, wax and bulliform leaf rolling feed breeding |
| **Forestry and horticulture** | Ring width dates timber, fires, floods and droughts (**dendrochronology**); heartwood versus sapwood sets durability; **grafting** works only when the **vascular cambia of scion and stock align**. Floral organs are modified leaves — [06 — Plant reproduction and alternation of generations](06-plant-reproduction-and-alternation-of-generations.md) — and the sugars loaded here come from [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md) |

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Root hairs are tiny roots" | Each is a **single-celled extension of one epidermal cell** (trichoblast), not a branch |
| "Water travels only through the symplast" | In the cortex it moves mainly through the **apoplast**; the strip then **forces** the symplastic route — sequential, not alternative |
| "The Casparian strip is cellulose or lignin" | It is a band of **suberin**, a waxy hydrophobic polyester; that chemistry blocks wall-borne water |
| "Lateral roots branch off the outside" | They are **endogenous**, arising from the **pericycle** inside the stele and pushing out through cortex and epidermis |
| "Monocot and dicot roots look alike" | Dicot: **diarch–tetrarch**, arms meeting at the centre, **no pith**. Monocot: **polyarch**, arms around a **central pith** |
| "Bundles are scattered in dicots" | The reverse: dicot stem = **eustele** (ring), monocot stem = **atactostele** (scattered) |
| "Wood is made by the cork cambium" | **Wood is secondary xylem from the vascular cambium**; the cork cambium makes **periderm (bark)** |
| "Annual rings are bark" | Bark lies **outside** the vascular cambium; rings are successive yearly crops of **secondary xylem** |
| "Guard cells open because water arrives" | Solutes first: **proton pumping and K+ uptake** lower water potential, water follows by osmosis, uneven wall thickening bows the cells apart |
| "The cuticle lets gases in and out" | The cuticle is a **gas-impermeable waterproof seal**; all gas exchange is through **stomata**, the metered exception |

## Key facts

- Three organs, three problems: **root = anchorage and selective absorption**, **stem = conduction and support**, **leaf = gas exchange and light capture** under a water-loss constraint.
- Root zones run **root cap → cell division → elongation → maturation**: thrust is made in **elongation**, absorption occurs in **maturation** where **root hairs** form.
- The **Casparian strip of suberin** in the **endodermis** seals the apoplast and forces water and solutes across **selectively permeable membranes** — the kidney-like checkpoint and first regulated step of the stream in [04 — Water transport and transpiration](04-water-transport-and-transpiration.md).
- The **pericycle** gives rise to **lateral roots** (endogenous) and, in dicots, contributes to the vascular and cork cambia.
- Dicot root = **diarch–tetrarch, no pith**; monocot root = **polyarch with central pith**; older dicot roots develop **root bark (periderm)**.
- Dicot stem = **eustele** (ring, open bundles, cortex and pith); monocot stem = **atactostele** (scattered, closed, continuous ground tissue).
- **Primary growth** comes from apical meristems; **secondary growth** from the **vascular cambium** (secondary xylem inward = **wood**, secondary phloem outward) and the **cork cambium** (periderm = **bark**).
- **Bark is everything outside the vascular cambium**; **heartwood** is non-conducting xylem blocked by **tyloses**, surrounded by conducting **sapwood**.
- **Annual rings** record seasonal cambial activity: large thin-walled **earlywood** for conduction, small thick-walled **latewood** for support.
- The leaf pairs a **waxy cuticle** with **stomata**: guard cells open by accumulating **K+ and counter-ions**, taking up water by osmosis and bowing apart; **ABA** closes them in drought.
- **Palisade mesophyll** maximises light capture near the upper surface; **spongy mesophyll and substomatal spaces** maximise CO2 diffusion, ~10,000 times faster in air than in water.
- **C4 (Kranz) anatomy** splits carbon fixation between mesophyll and **bundle-sheath cells**, concentrating CO2 around Rubisco to suppress photorespiration.

## Practice questions

**1. The Casparian strip is physiologically important because it**

A. Increases water absorption by the root hairs
B. Blocks the apoplastic route, forcing water and solutes across the selectively permeable membranes of endodermal cells
C. Lets all dissolved ions pass freely into the xylem
D. Seals the xylem against air embolism

**Answer: B**

Explanation: Suberin in the radial and transverse walls of the endodermis seals the cell-wall continuum, so solutes that moved with no membrane crossed must enter the symplast through transporters — a selective checkpoint. It does not speed absorption (A), free passage is the opposite of the point (C), and embolism sealing belongs to xylem pit membranes (D).

---

**2. A lateral root originates from the**

A. Epidermis, growing outward like a stem branch
B. Cortex, by division of parenchyma cells
C. Pericycle, growing outward through the cortex and epidermis
D. Xylem, by differentiation of tracheary elements

**Answer: C**

Explanation: Lateral roots are **endogenous**: pericycle cells resume division and push through cortex and epidermis, leaving a wound. Stem branches arise from surface meristems, which is why A is the common misconception; cortex and xylem lack meristematic capacity for root branching (B, D).

---

**3. A root section shows many xylem arms in a ring around a central core of parenchyma. This is**

A. A monocot root with a polyarch stele and pith
B. A dicot root in diarch arrangement
C. A young dicot stem showing a eustele
D. A leaf midrib in transverse section

**Answer: A**

Explanation: Many arms (polyarch) around a parenchymatous pith is the monocot root blueprint; dicot roots are diarch–tetrarch with xylem meeting at the centre and no pith (B). A eustele is a stem arrangement of bundles in a ring (C), and a midrib holds one collateral bundle, xylem above phloem (D).

---

**4. Vascular bundles are arranged in a ring in a dicot stem mainly because this layout**

A. Allows the stem to float on water
B. Concentrates support at the circumference and lets fascicular and interfascicular cambia join into one ring for thickening
C. Prevents the phloem from functioning
D. Is required for parallel venation

**Answer: B**

Explanation: A peripheral ring of strong tissue resists bending and leaves a continuous band of meristem for producing wood and inner bark. Scattered bundles stiffen the section but give no continuous cambium; phloem functions normally (C) and parallel venation belongs to monocot leaves (D).

---

**5. In a woody dicot stem the vascular cambium produces**

A. Secondary xylem outward and secondary phloem inward
B. Secondary phloem inward and periderm outward
C. Cork only, which becomes the annual rings
D. Secondary xylem inward (wood) and secondary phloem outward

**Answer: D**

Explanation: The cambium lies between xylem and phloem and divides tangentially, sending derivatives toward the pith (secondary xylem = wood) and toward the cortex (secondary phloem). The other options reverse those directions (A), mix in the separate cork cambium (B), or attribute rings to cork rather than xylem (C).

---

**6. The visible annual ring in a temperate tree is formed by**

A. Alternating layers of bark laid down each year
B. The difference in cell size and wall thickness between earlywood and latewood from one cambium in one year
C. A new cork cambium arising every spring
D. Outward growth of the pith into the wood

**Answer: B**

Explanation: The cambium lays down large, thin-walled conductive cells in spring (earlywood) and small, thick-walled dense cells in late summer (latewood); the abrupt change back to large cells next spring is the visible boundary — one ring per year. Bark lies outside the cambium (A), the cork cambium makes periderm (C), and the pith does not grow outward (D).

---

**7. Guard cells open a stoma by**

A. Losing water and becoming flaccid
B. Accumulating K+ and counter-ions, taking up water by osmosis, and bowing apart because of uneven wall thickening
C. Absorbing CO2, which inflates them
D. Dividing to create a pore between the daughter cells

**Answer: B**

Explanation: Blue light drives H+-ATPase proton export, the membrane hyperpolarises, K+ with Cl− and malate enters, water follows by osmosis, and rising turgor curves the cells outward because radial microfibrils and thickened pore-side walls restrict swelling. Flaccidity closes stomata (A); CO2 does not inflate them (C); guard cells do not divide to open (D).

---

**8. The loose, air-filled spongy mesophyll exists chiefly to**

A. Let CO2 diffuse rapidly as a gas toward every photosynthesising cell over a short path
B. Store starch for the whole plant
C. Provide mechanical rigidity to the leaf
D. Reflect excess light away from the leaf

**Answer: A**

Explanation: CO2 diffuses about 10,000 times faster in air than in water, so a continuous gas-phase network joined to the substomatal cavity delivers CO2 to every mesophyll cell with little liquid-phase resistance. Rigidity comes from collenchyma and sclerenchyma (C), storage is secondary (B), and reflection belongs to trichomes and wax (D).

---

**9. The bundle-sheath cells of a C4 leaf are enlarged and packed with chloroplasts because they must**

A. Absorb light the mesophyll misses
B. Produce the cuticle for the whole leaf
C. Receive the 4-carbon acid from mesophyll and release CO2 around Rubisco, suppressing photorespiration
D. Generate the tension that pulls water from the roots

**Answer: C**

Explanation: C4 plants separate initial fixation (mesophyll, PEP carboxylase) from the Calvin cycle (bundle sheath), so CO2 is concentrated where Rubisco sits and oxygen fixation is minimised — Kranz anatomy. Light capture is mainly palisade mesophyll (A), the cuticle comes from the epidermis (B), and the pull arises in the xylem (D).

---

**10. Most dicot leaves place the majority of their stomata on the lower epidermis because**

A. The lower surface is where light enters the leaf
B. The upper surface has no epidermis
C. Stomata are needed to anchor the leaf to the stem
D. The shaded lower surface is cooler, so pores there admit CO2 with far less water loss than pores in sun

**Answer: D**

Explanation: The upper face takes direct radiation and would transpire heavily if pores were opened there; keeping most stomata on the cooler, shaded lower face maintains gas exchange while cutting water loss. Light enters through the transparent upper epidermis (A is backwards), both faces have epidermis (B), and stomata do not anchor the leaf (C).
