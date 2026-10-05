# Xylem and Phloem

## Why it matters

A plant fifteen metres tall has two distribution problems and no circulation to solve them: water and minerals from the roots must climb against gravity to the leaves, and sugar made in those leaves must reach roots, tubers, fruits, and seeds equally far away in the opposite direction. There is no heart and no contractile vessel wall — plant transport is delivered by **fixed architecture plus physics**, and that architecture is this chapter.

The solution is a split into two tissues with opposite specifications:

```
XYLEM   water + minerals ──▶ UPWARD only (root → shoot)
        DEAD at maturity ── hollow, lignified, reinforced tubes
        under TENSION ── pulled from above by the leaf

PHLOEM  sucrose + signals ──▶ BOTH DIRECTIONS (source → sink)
        LIVING but ENUCLEATE ── sieve tubes serviced by companion cells
        under POSITIVE pressure ── pushed from the loading end
```

Every structural difference below follows from that split. A tube under tension must be rigid, waterproof, and free of anything that could collapse inward — hence **lignin**, reinforced secondary walls, and death of the protoplast. A tube under positive pressure that must gain and lose solute selectively needs membranes, carriers, and ATP — hence a retained plasma membrane, active loading, and a committed partner cell. Learn the specification and the anatomy writes itself.

The split is visible and economic: **wood is dead xylem; bark contains living phloem.** Drought embolises xylem and cuts off water; girdling strips the bark and starves roots of sugar. Crop yield is still largely a question of how efficiently carbon moves from leaf to harvestable organ.

## Why two systems rather than one

The streams run opposite ways along the same axis and occupy **opposite pressure regimes**: a conduit cannot be a pipe under tension and a pipe under positive pressure at once, nor both a passive unloading duct and a selectively loading, membrane-bounded compartment. So xylem is built to tolerate tension — rigid, waterproof, membrane-free, disposable — and phloem is built to make and control positive pressure — living, membrane-bounded, selectively loaded, expendable only at its ends. The two also sit adjacent in every bundle, and that adjacency is functional: **the phloem borrows water from the xylem to build its pressure and returns it when sugar is unloaded.**

## Xylem: hollow tubes under tension

Xylem carries water and minerals upward and, in most species, supports the axis. Its conducting cells — **tracheids**, **vessel elements**, and **xylem fibres** (with **xylem parenchyma** kept alive for storage) — derive from the procambium in primary growth and the vascular cambium in secondary growth. Tissue identities are in [01 — Plant cells and tissues](01-plant-cells-and-tissues.md).

### Tracheids and vessel elements

Both are dead at maturity. Tracheids are long, slender, tapered cells with closed ends; vessel elements are shorter, wider cylinders stacked like pipe lengths. They differ in connection, and therefore in the efficiency-versus-safety trade-off.

| Feature | **Tracheids** | **Vessel elements** |
| --- | --- | --- |
| **End walls** | Closed — water crosses only through **pit pairs** | Joined by **perforation plates** (simple or scalariform) — one open lumen end to end |
| **Diameter** | Narrow (~15–50 µm) | Wide (often 50–500 µm) |
| **Efficiency** | Low — flow scales with the **fourth power of radius** | High — radius gain without end-wall resistance |
| **Safety** | Higher: small trapped volume, redundant paths, bordered pit pairs as check valves | Lower: one embolism disables a long, wide run |
| **Occurrence** | **All vascular plants** — the only conductor in most gymnosperms and ferns | **Characteristic of angiosperms**; rare elsewhere |

**Why vessels are effectively angiosperm-specific:** high photosynthetic rates demand high conductance, and conductance scales as *r*⁴. Wider conduits joined by perforation plates remove the end-wall penalty a tracheid pays at every junction, so a vessel moves far more water per unit of wall built. Angiosperms bought that throughput at the price of safety — wide conduits cavitate more readily — and the trade-off is still readable in wood anatomy.

### Wall thickenings and lignin

A conduit under tension is squeezed inward by the atmosphere pressing on its wall. Cellulose alone would resist only partly, so plants add **lignin** — a hydrophobic, cross-linked phenolic polymer of monolignols (p-coumaryl, coniferyl, sinapyl alcohols) filling the wall matrix. Lignification keeps water inside the lumen, raises compressive strength enormously, and resists decay: the polymer that makes wood durable and paper pulp hard to process.

Secondary wall deposition follows a sequence tracking the organ's growth:

| Order | Pattern | Typical location | Trade-off |
| --- | --- | --- | --- |
| 1 | **Annular** — separate rings | Protoxylem in organs still elongating | Maximally extensible; weakest |
| 2 | **Spiral (helical)** — coil | Protoxylem, elongating stems | Extensible with continuous support |
| 3 | **Reticular** — net | Metaxylem, after elongation | Stronger; little further extension |
| 4 | **Scalariform** — ladder bands | Metaxylem of ferns and angiosperms | Near-complete wall, some porosity |
| 5 | **Pitted / fully lignified** | Secondary xylem (wood) | Maximum strength; zero extensibility |

**The sequence answers the physics.** A lengthening stem cannot afford rigid tubes, so early conduits are ringed or coiled and stretch with the organ; once elongation stops the plant can afford — and needs — a fully lignified, pit-dominated wall. Where lignification fails, conduits collapse under tension and the shoot wilts despite functioning roots.

### Death as a design feature

Programmed cell death in the xylem is the specification being met, not a failure:

```
CAMBIUM / PROCAMBIUM CELL
   │  elongates, deposits SECONDARY WALL (cellulose + lignin)
   ▼
PROGRAMMED CELL DEATH on schedule
   │  membranes and organelles degraded, contents cleared
   ▼
HOLLOW, LIGNIFIED, WATER-FILLED TUBE
   │  no membrane in the path → no osmotic barrier, no respiration
   │  consuming the water it carries, nothing to feed or repair
   ▼
FUNCTIONAL CONDUIT — dead cells doing work
```

**Nothing to maintain:** the conduit spends no ATP, so energy is reserved for leaf and root. **Nothing in the way:** no vacuole or organelles constricting flow. **No compromise on the wall:** a living cell must preserve an intact membrane, which limits how much hydrophobic reinforcement can be packed around it — death removes the constraint. The cost is that **xylem cannot be repaired cell by cell**: damaged conduits are replaced only as the cambium makes new ones, and a cavitated conduit must be refilled at metabolic cost by neighbouring parenchyma or abandoned.

### Pits, pit membranes, and the containment of embolism

Water crosses between conduits through **pits** — thin wall regions lacking secondary wall. In a bordered pit a chambered wall overarches a **pit membrane**, porous enough to pass water yet a physical barrier to air:

```
tension rises in one conduit → bubble forms (CAVITATION)
        │                       → conduit fills with air (EMBOLISM)
        ▼
air–water meniscus pressed against the PIT membrane
        │   surface tension + aperture hold the bubble back
        ▼
spread limited to neighbours — until pressure exceeds threshold
        │
        ▼
AIR SEEDING → adjacent conduit embolises too
```

The pit membrane is a **check valve against air seeding**: it passes water while slowing the spread of an air bubble, so a plant can lose individual conduits without losing the whole column. Conifers add a **torus–margo** membrane whose thickened central disc seals the aperture outright. The physics of cohesion, tension, cavitation, and refilling is in [04 — Water transport and transpiration](04-water-transport-and-transpiration.md); what matters here is structural — **wall architecture decides how badly a conduit fails and how far the failure travels.**

## Phloem: living tubes under pressure

Phloem transports sucrose, amino acids, and signals from where they are made to where they are used, in either direction, driven by osmotically generated pressure. Its conducting system is **sieve tube elements** supported by **companion cells**, with **phloem parenchyma** and **sieve-tube fibres** completing the tissue.

### Sieve tube elements: alive without a nucleus

A mature sieve tube element dismantles its own genome while remaining alive.

| Component | Status | Consequence |
| --- | --- | --- |
| **Nucleus** | Degraded in differentiation | No transcription — proteins supplied from outside |
| **Ribosomes** | Largely lost | No local protein synthesis |
| **Vacuole** | Membrane collapsed | Cytoplasm continuous with the sieve plate pores |
| **Plasma membrane** | **Retained, intact** | Selectively permeable — essential for loading |
| **Mitochondria** | Few, small | Limited respiration of its own |
| **Endoplasmic reticulum** | Stacked **slime bodies** rich in **P-protein** | Rapid sealing on injury |
| **Cytoplasm** | Thin layer against the wall | Low resistance to bulk flow |

**Why losing the nucleus is viable** is division of labour, not degeneration. Protein turnover here is slow and the proteolytic environment is suppressed — had the element kept active proteases alongside active transcription it would digest its own transport machinery. Differentiation removes nucleus and translational apparatus together, leaving a compartment whose only jobs are to hold a membrane, provide a low-resistance lumen, and seal when broken. Everything costly is outsourced to the companion cell, so the tube carries **no maintenance burden and no self-digestion risk**.

### Companion cells: the metabolic twin

Each sieve tube element is served by one or more **companion cells**, derived from the same mother cell and linked by numerous **plasmodesmata**:

```
COMPANION CELL                         SIEVE TUBE ELEMENT
dense cytoplasm, active nucleus        thin cytoplasm, no nucleus
NUMEROUS MITOCHONDRIA ── ATP ────────▶ retained membrane + loading
mRNA and proteins ─── plasmodesmata ─▶ no local synthesis
loading carriers ──── sucrose ────────▶ lumen
```

The mitochondrial density is functional: **loading sucrose against a gradient is ATP-expensive**, and every protein the sieve tube element uses must be synthesised here. Because plasmodesmata link the two cells symmetrically, the pair behaves as one unit — the element conducts, the companion cell lives for both. In minor veins companion cells are specialised as **transfer cells** with wall ingrowths amplifying membrane area, exactly the geometry predicted when surface rather than volume is the bottleneck.

### Sieve plates, P-protein, and plasmodesmata

End walls between sieve tube elements are modified into **sieve plates** — perforated by many pores, cytoplasmically continuous, membrane-lined. They are a compromise: **lower resistance to bulk flow** while providing a surface that can **seal a wound quickly**.

Sealing is the job of **P-protein**, abundant as tubular or fibrillar bodies in the element. When a plate is breached and pressure drops, P-protein is swept to the pores and, with **callose** (β-1,3-glucan) deposited within seconds, plugs the plate and limits sap loss. Since the phloem runs at positive pressure, an unsealed wound would bleed continuously — the plug is a pressure-containment device.

Plasmodesmata extend beyond this pair, connecting sieve elements to companion cells, phloem parenchyma, and mesophyll to form the **symplast**, through which sugar moves without crossing a membrane. Whether a loading or unloading step is **apoplastic** (membrane-crossing, ATP-driven) or **symplastic** (through plasmodesmata) determines whether the plant can regulate it.

### Why sucrose, and why not glucose

Phloem sap is roughly 10–25 % sucrose, and the choice is not incidental:

| Property of sucrose | Why it helps |
| --- | --- |
| **Non-reducing disaccharide** | Does not glycate proteins or damage membranes — a reducing sugar at molar concentration would be destructive in transit |
| **Chemically stable** | Survives long transport and months of vacuolar storage |
| **Twice the carbon per osmotically active particle** | Twice the carbon for the same number of dissolved particles — and since turgor is osmotic, **more carbon per unit of pressure** is what pressure-flow needs |
| **Large, polar, impermeable** | Stays where it is put; movement requires carriers, so loading and unloading are regulated rather than leaking |
| **Direct product of photosynthesis** | Made in the mesophyll — [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md) |

Glucose and fructose appear only in small amounts as intermediates of loading, unloading, or polymerisation into starch at the sink — never as the transport currency.

## Xylem versus phloem at a glance

| Feature | **Xylem** | **Phloem** |
| --- | --- | --- |
| **Direction** | **Upward only** (root → shoot) | **Both directions** — source → sink |
| **Living at maturity?** | **No** — dead (programmed cell death) | **Yes** — living, but sieve tube elements are **enucleate** |
| **Principal cell types** | Tracheids, vessel elements, xylem fibres, xylem parenchyma | Sieve tube elements, companion cells, phloem parenchyma, phloem fibres |
| **Contents** | Water, mineral ions (K⁺, Ca²⁺, NO₃⁻), dilute amino acids | **Sucrose**, amino acids, P-protein, hormones, small RNAs |
| **Driving force** | **Transpiration pull** — tension at the leaf (04 — Water transport and transpiration) | **Hydrostatic pressure gradient** built osmotically at source and sink |
| **Pressure state** | **Negative pressure (tension)** — pulled | **Positive pressure** — pushed |
| **Membranes in the path** | None — no living membrane crosses the lumen | Continuous plasma membrane along every sieve tube |
| **Energy in transit** | None in the conduit | None in the conduit; **ATP at loading and unloading** |
| **Wall** | Cellulose + heavy **lignification**; annular → spiral → reticular → pitted | Cellulose-rich primary wall; callose at sieve plates |
| **Main vulnerability** | **Cavitation/embolism**, air seeding, blockage | Pressure loss through wounding, girdling, pathogens |
| **Origin** | Procambium (primary), vascular cambium (secondary) | Procambium (primary), vascular cambium (secondary) |
| **Secondary product** | **Wood** — secondary xylem, inside the cambium | **Inner bark** — secondary phloem outside it, plus periderm |

The last two rows matter: **both tissues arise from the same meristems and are produced simultaneously in opposite directions by the vascular cambium.** They differ not in origin but in what they differentiate into.

## Phloem transport: the pressure-flow hypothesis

The **pressure-flow (mass flow) hypothesis** — the Münch hypothesis — states that sap moves *en masse* down a hydrostatic pressure gradient built osmotically at the source and dissipated at the sink. Loading uses **secondary active transport** powered by a proton gradient ([03 — Active transport](../03-cellular-processes/03-active-transport.md)), and the water follows by osmosis ([02 — Passive transport](../03-cellular-processes/02-passive-transport.md)):

```
SOURCE (mature photosynthesising leaf)
   │ 1. H⁺-ATPase pumps H⁺ OUT of the companion cell / sieve element
   │    at the cost of ATP → steep proton gradient across the membrane
   │ 2. H⁺ flows back IN through a H⁺/SUCROSE SYMPORTER (SUT/SUC),
   │    dragging sucrose in AGAINST its gradient → sucrose rises
   ▼
3. Water enters OSMOTICALLY from the adjacent xylem → TURGOR RISES
   at the source end
   ▼
4. AT THE SINK sucrose is UNLOADED into storage or growing cells
   → solute falls → water leaves by osmosis BACK into the xylem
   → turgor falls at the sink end
   ▼
5. HYDROSTATIC PRESSURE GRADIENT: high (source) → low (sink)
   → sap flows en masse through the sieve plates, far faster than
   diffusion could deliver
   ▼
6. Water released at the sink re-enters the xylem and is pulled back
   to the leaf — the water loop closes, the carbon loop does not
   ▼
CYCLE CONTINUES while the source photosynthesises
```

### Loading: the only ATP-consuming step

Steps 1–2 are where metabolism enters. The **H⁺-ATPase** spends ATP to acidify the apoplast; the resulting electrochemical gradient powers **H⁺/sucrose symport** — **secondary active transport**, one step removed from ATP. Companion cells are packed with mitochondria because this step, plus protein synthesis for both cells, runs continuously.

Two loading routes feed the same engine. In **apoplastic loading** sucrose crosses the membrane twice via the symporter — the situation in most crop plants. In **symplastic loading** with **polymer trapping**, sucrose plus raffinose-family oligosaccharides move through plasmodesmata; the larger oligosaccharides cannot diffuse back, so sugar is trapped in the sieve tube. The route decides how loading is regulated: a membrane transporter can be switched off, a symplastic channel cannot be closed so easily.

### Why living cytoplasm, but no pump

A common error is to imagine a pump along the sieve tube. **There is none.** Once sucrose is loaded and water has followed, sap moves because pressure differs between the two ends — the physics of any pipe. What requires life is **loading and unloading**, because both demand carriers, membranes, and ATP. Kill the membranes or remove the companion cells and the gradient cannot be built or maintained; the tube stays physically open while transport stops.

This is precisely why the sieve tube element can be enucleate: **the energy and information burden sits at the two ends of the tube, not along it.**

### Why flow is bidirectional: sources and sinks

Direction is not a property of the tissue but of the **pressure gradient**, set by where sugar enters and leaves. A leaf producing more sugar than it consumes is a **source**; anything consuming or storing sugar is a **sink**.

| Organ | Typical status | Reason |
| --- | --- | --- |
| **Mature, sunlit leaf** | **Source** | Photosynthesis exceeds local demand |
| **Young, expanding leaf** | **Sink** | Growth costs more than it fixes |
| **Roots, tubers, root tips** | **Sink** | Respiration and storage; no photosynthesis |
| **Fruit, seed, developing grain** | **Sink** | The strongest sinks in the plant |
| **Storage tissue in spring** | Can become a **Source** | Remobilised reserves feed the new shoot |

Because different sieve tubes connect different sources to different sinks, **one plant moves sap upward in some tubes and downward in others at the same moment** — to growing shoots and fruits, down to roots and storage organs, reversed seasonally when a storage organ becomes a source. The phloem has no fixed polarity; the xylem does, because transpiration only ever removes water from the top.

### What the evidence shows

| Observation | Interpretation |
| --- | --- |
| **Aphid stylet technique**: an aphid's stylet in one sieve tube exudes honeydew passively; cut, it bleeds sap | Sap is **under positive pressure** and can be sampled element by element |
| **¹⁴CO₂** fed to a leaf appears in midrib then sinks at tens of centimetres per hour | Transport is **bulk flow**, far faster than diffusion |
| **Turgor is higher at the source end than the sink end** of one pathway | The required **pressure gradient** exists in the correct direction |

## Secondary growth: wood and bark

In woody plants the vascular cambium is a lateral meristem dividing once and differentiating in two directions:

```
OUTER SIDE                   CAMBIUM                   INNER SIDE
secondary PHLOEM ◀── divides once ──▶ secondary XYLEM
(inner bark)                             (WOOD)
   │ sugar moves outward,                 │ water moves inward,
   │ lives a few seasons, then            │ dead, accumulated
   │ sloughed by the periderm             │ year after year
   ▼                                      ▼
BARK = secondary phloem + periderm   growth RINGS = yearly
        (everything outside cambium) increments of XYLEM
```

Annual rings record **xylem**, not phloem. Because the cambium adds wood inward far faster than bark outward, a trunk is mostly dead tissue with a thin living rind — the structural reason a tree can grow tall (lignified xylem is self-supporting, living parenchyma is not). Bundle anatomy is developed in [02 — Roots, stems, and leaves](02-roots-stems-and-leaves.md).

**Girdling** — removing bark around the circumference — severs the phloem connection to the roots while leaving xylem intact. Water still rises, so leaves do not wilt at first; the roots, deprived of sucrose, exhaust their reserves and die, and the plant follows. The asymmetry of the two tissues is what makes this sequence possible, and it is the standard demonstration that the systems are genuinely separate.

## The phloem as a signalling network

Sugar is only part of the cargo. The phloem carries **hormones** (auxin, cytokinins, abscisic acid, gibberellins), **small RNAs**, and **proteins** from source tissues to distant targets — which is how a shaded or attacked leaf alters growth, stomatal behaviour, and defence in roots and buds it never touches. Floral induction signals and systemic silencing of virus-derived sequences travel in the same stream, so systemic signalling follows the source–sink pattern. Hormone signalling is developed in [05 — Plant hormones](05-plant-hormones.md).

Because viruses and some silencing signals move cell to cell through plasmodesmata and then systemically through sieve tubes, the phloem is also the route of systemic infection — linking this chapter to [07 — Microbiology](../07-microbiology/).

## Relevance to medicine and agriculture

**Crop yield is a source–sink problem.** Grain filling, tuber bulking, and fruit size depend on how much sucrose the phloem loads at the leaf and unloads into the harvestable organ. Raising photosynthesis without raising unloading capacity merely piles sugar in the leaf; strengthening the sink or shortening transport distance improves harvest index. A plant is only as productive as the pressure gradient it can build.

**Drought damages xylem first.** As soil water potential falls, tension rises until conduits cavitate; conductance drops, stomata close, and yield falls before visible wilting. Breeding for narrower, more numerous, better-guarded conduits trades efficiency for safety — the tracheid-versus-vessel trade-off in miniature. The physics is in [04 — Water transport and transpiration](04-water-transport-and-transpiration.md); the anatomical levers are here.

**Pathogens exploit the two systems differently.** *Xylella fastidiosa* and vascular wilt fungi colonise the xylem lumen and block water transport. **Phytoplasmas** — wall-less bacteria of the class Mollicutes — live inside sieve tubes and travel with sap-sucking insects; with no peptidoglycan they are unaffected by β-lactams, the wall-antibiotic logic of [07 — Microbiology](../07-microbiology/). Viruses spread through plasmodesmata and then systemically through the phloem, so symptoms appear first in young sink leaves far from the inoculation site.

**Insects, wounding, and industry follow the same rules.** Aphids tap sieve tubes directly; honeydew is filtered phloem sap, and the aphid stylet technique is the cleanest way to sample one sieve tube and measure its pressure. Cut stems block xylem conduits with air and microbes, which is why flowers are recut under water — an air-filled vessel conducts nothing. Brief ring-barking forces sugar into fruit by interrupting phloem export to the roots. Timber is dead xylem, cork is periderm, maple syrup is xylem sap, latex a phloem exudate.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Xylem and phloem are both dead transport tissue" | **Opposite.** Xylem is dead at functional maturity by design; phloem is living throughout — sieve tube elements are **enucleate**, not dead. |
| "Water is pushed up from the roots" | Root pressure drives guttation in some plants, but the dominant force is **pull from above**: transpiration tension down the cohesive column (04 — Water transport and transpiration). |
| "Phloem flow is always rootward" | Flow follows **source → sink**: upward to shoots and fruits, downward to roots, simultaneously in different sieve tubes. |
| "Glucose is the sugar transported in the phloem" | **Sucrose**: non-reducing, stable, membrane-impermeable, twice the carbon per osmotically active particle — which is what builds pressure efficiently. |
| "No nucleus means the sieve tube element is dead" | Losing the nucleus is a **differentiation step**. Membrane, cytoplasm, and some mitochondria persist; proteins and ATP come from the companion cell. |
| "Companion cells are just packing cells" | They are the **metabolic twin**: their mitochondria power H⁺-ATPase loading and their nucleus supplies every protein the element cannot make. |
| "Sieve plates are holes left when end walls dissolved" | **Designed perforations**: many pores cut resistance to bulk flow, while P-protein and callose seal the plate within seconds if pressure is breached. |
| "Embolism and cavitation are the same event" | **Cavitation** is bubble formation under extreme tension; **embolism** is the resulting air-filled, non-conducting conduit. Pit membranes limit air seeding. |
| "Trees push sap with a pump like a heart" | **No pump exists for bulk flow.** Xylem water is pulled by transpiration, phloem sap pushed by an osmotically generated gradient; ATP is spent only at the ends. |
| "Wood and bark are the same tissue" | **Wood = secondary xylem** (inside the cambium); **bark = secondary phloem + periderm** (everything outside it). Girdling removes bark, not wood. |
| "Signalling uses a separate system" | Hormones, small RNAs, and proteins travel **in the phloem stream itself**, so systemic signals follow the source–sink pattern. |

## Key facts

- Xylem carries **water and minerals upward** and is **dead at maturity**; phloem carries **sucrose and signals in both directions** and is **living but enucleate**. Everything else follows from that split.
- **Tracheids** are narrow, closed-ended, in all vascular plants; **vessel elements** are wide, joined by **perforation plates**, efficient (*flow ∝ r⁴*) and effectively **angiosperm-specific**, but less safe from embolism.
- Wall patterns run **annular → spiral → reticular → scalariform → pitted/fully lignified**, trading extensibility for strength as elongation stops; **lignin** waterproofs and stiffens the wall against collapse.
- **Programmed cell death is a design feature**: nothing to maintain, nothing obstructing the lumen, no limit on lignification.
- **Pit membranes are check valves against air seeding**; cavitation forms the bubble, embolism is the blocked conduit, and spread depends on membrane strength (torus–margo in conifers).
- **Sieve tube elements** lose nucleus, ribosomes, and vacuole but keep plasma membrane; slow turnover plus suppressed proteolysis prevents self-digestion.
- **Companion cells** are dense with mitochondria and linked by plasmodesmata — they supply ATP, proteins, and loading machinery for the pair.
- **Sieve plates** cut resistance to bulk flow; **P-protein** and **callose** seal them within seconds when pressure is lost.
- **Sucrose** is the transport sugar: non-reducing, stable, membrane-impermeable, twice the carbon per osmotically active particle.
- **Pressure-flow chain**: H⁺-ATPase → **H⁺/sucrose symport** loading ([03 — Active transport](../03-cellular-processes/03-active-transport.md)) → osmotic water entry → turgor high at source → hydrostatic gradient → bulk flow → unloading → water back to the xylem.
- Flow is **bidirectional** because direction is set by **source–sink** position: mature leaves are sources; roots, fruits, seeds, tubers, and young leaves are sinks. The conduit is **passive** — only loading and unloading cost ATP.
- **Secondary growth**: the cambium adds **secondary xylem (wood) inward** and **secondary phloem (inner bark) outward**; bark also includes the periderm ([02 — Roots, stems, and leaves](02-roots-stems-and-leaves.md)).
- The phloem also carries **hormones, small RNAs, and proteins** — long-distance signalling ([05 — Plant hormones](05-plant-hormones.md)).

## Practice questions

**1. Which statement correctly contrasts the two vascular tissues?**

A. Xylem is living and carries sugars upward; phloem is dead and carries water downward
B. Xylem carries water and minerals upward and is dead at maturity; phloem carries sugars in both directions and is living but enucleate
C. Both tissues are dead at maturity and both transport under negative pressure
D. Phloem operates under tension while xylem operates under positive turgor pressure

**Answer: B**

Explanation: Xylem is a dead, lignified conduit pulled under tension; phloem is a living, membrane-bounded conduit pushed under positive pressure. C reverses the phloem's living state and D reverses the pressure regimes.

---

**2. Which feature distinguishes a vessel element from a tracheid?**

A. Vessel elements retain a nucleus at functional maturity
B. Vessel elements are joined end to end by perforation plates, forming a continuous open lumen
C. Vessel elements are the only conducting cells in gymnosperm wood
D. Vessel elements transport sugars while tracheids transport water

**Answer: B**

Explanation: Perforation plates remove the end-wall resistance a tracheid imposes at every junction, so vessels conduct far more water, as *r*⁴ predicts. Both are dead and conduct water, and gymnosperm wood is run almost entirely by tracheids.

---

**3. Protoxylem in an elongating stem typically shows annular or spiral thickenings because**

A. rings and coils are cheaper to build than a continuous wall
B. the pattern lets the conduit extend with the organ before the wall fully lignifies
C. lignin can only be deposited after the conduit has been in service
D. rings are the strongest pattern against collapsing tension

**Answer: B**

Explanation: A lengthening organ cannot contain a rigid lignified tube, so rings or a helix let it extend while still resisting collapse. Annular walls are the weakest pattern — strength rises toward the fully pitted, lignified metaxylem and wood.

---

**4. Programmed cell death of xylem conduits is best described as**

A. a failure of the plant to maintain the tissue
B. a design feature that clears the flow path and removes metabolic maintenance from the conduit
C. a necessary step for the conduit to generate positive pressure
D. the mechanism by which lignin is synthesised

**Answer: B**

Explanation: Clearing the protoplast leaves no membrane to impede water, no respiration consuming it, and no limit on lignification — a cheap, low-resistance pipe. C describes phloem, and lignin is laid down before the cell dies.

---

**5. In the pressure-flow hypothesis, mass flow through a sieve tube is driven by**

A. contraction of P-protein along the length of the tube
B. a hydrostatic pressure gradient between source and sink generated osmotically
C. continuous ATP hydrolysis by carriers along the sieve tube wall
D. the tension created by transpiration in the adjacent xylem

**Answer: B**

Explanation: Loading at the source makes water enter osmotically and raises turgor; unloading at the sink reverses it; sap flows en masse down that pressure difference. The tube has no pump — ATP is spent only at the ends.

---

**6. Phloem transports sucrose rather than glucose principally because sucrose**

A. is smaller and diffuses faster through sieve plates
B. is a non-reducing, stable disaccharide carrying twice the carbon per osmotically active particle
C. passes freely through the lipid bilayer, simplifying unloading
D. is the direct product of respiration in the companion cell

**Answer: B**

Explanation: A non-reducing sugar will not glycate proteins in transit, and twice the carbon per dissolved particle gives twice the carbon for the same osmotic cost — precisely how pressure is built efficiently. Sucrose is larger than glucose, its impermeability makes loading controllable, and it comes from photosynthesis.

---

**7. A mature sieve tube element remains functional without a nucleus because**

A. it re-synthesises a nucleus each time the phloem is wounded
B. its companion cell, connected by plasmodesmata, supplies proteins and ATP from numerous mitochondria while protein turnover in the element is slow
C. the nucleus is stored in the vacuole and re-imported when needed
D. sieve tube elements are dead cells that conduct passively like xylem

**Answer: B**

Explanation: The pair acts as one unit — the companion cell's mitochondria power H⁺-ATPase loading and its nucleus transcribes for both cells across shared plasmodesmata, while suppressed proteolysis keeps proteins intact. The element is living and membrane-bounded, not dead.

---

**8. Sap can move simultaneously upward and downward in the phloem because**

A. sieve tubes reverse flow direction every few hours
B. different sieve tubes connect different sources to different sinks, each flowing down its own pressure gradient
C. companion cells pump sap alternately in both directions
D. the phloem has fixed polarity opposite to the xylem

**Answer: B**

Explanation: Direction is a property of source–sink arrangement, not of the tissue, and each tube responds to its own gradient. There is no alternating pump and no tissue-wide reversal — unlike the xylem, whose direction is fixed by transpiration.

---

**9. The vascular cambium produces secondary xylem inward and secondary phloem outward, so**

A. wood is secondary phloem and bark is secondary xylem
B. wood is secondary xylem, while bark comprises secondary phloem plus the periderm
C. wood and bark are both secondary phloem of different ages
D. bark comes from procambium and wood from the cork cambium

**Answer: B**

Explanation: Wood is accumulated dead xylem inside the cambium; bark is everything outside it — secondary phloem plus periderm. That is why girdling removes bark but leaves water transport intact while starving the roots.

---

**10. When one xylem conduit cavitates, the pit membranes between it and its neighbours serve to**

A. accelerate spread of air so the whole xylem embolises at once
B. limit air seeding into adjacent conduits until a pressure threshold is exceeded
C. refill the conduit automatically with sugars from the phloem
D. seal the conduit permanently with lignin so it never conducts again

**Answer: B**

Explanation: The membrane passes water readily but resists the air–water meniscus forced across it, so a single embolism is contained and only that conduit is lost — in conifers the torus–margo disc seals the aperture outright. The conduit can later be refilled or bypassed.
