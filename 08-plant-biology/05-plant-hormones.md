# Plant Hormones

## Why it matters

You have nerves and muscles, so you move. A plant is **sessile**: it cannot chase light, flee a herbivore or walk to wetter soil. It responds instead by **redistributing growth** — elongating one flank of a stem but not the other, opening a pore for ninety seconds, ripening fruit on cue, cutting water loss within minutes of drought. **Movement by a sessile organism is growth made directional, and hormones set the direction.** A plant hormone is therefore a low-concentration signal that is **made in one tissue, moved to another, and perceived there by a dedicated receptor** — source, transport and receptor specificity are what make the chemical carry *information* rather than mere presence.

This belongs in a pre-medical course because the **logic is human endocrinology**: receptor → signal transduction → altered gene expression, **non-linear dose–response curves**, and control by **antagonistic pairs** rather than by any single molecule. The ubiquitin–proteasome step that looks like a plant speciality is conserved in animals. Learn it here, on a seedling you can watch bend over two hours, and you will recognise it for insulin, thyroid hormone and cortisol.

| Constraint | Animal solution | Plant substitute | Consequence |
| --- | --- | --- | --- |
| **No circulation** | blood | PIN transport; xylem/phloem flow | **position** encodes information |
| **No nervous system** | action potentials | fast = ion flux/turgor; slow = transcription | every hormone has two timescales |
| **Rigid cell wall** | muscle | wall loosening, then turgor | "movement" = **differential growth** |
| **No circulating immune cells** | leukocytes | jasmonate, salicylate | defence is hormonal and systemic |

## The shared logic of hormonal control

Every hormone runs the same programme: **signal → receptor → transduction → transcription factor freed → genes on → output**, with transduction in plants usually taking the form of **destruction of a repressor** rather than activation of an enzyme. Nine perception systems carry the point, and five destroy a repressor outright:

| Hormone | Receptor | Core transduction event |
| --- | --- | --- |
| **Auxin (IAA)** | **TIR1/AFB**, an F-box protein of an SCF ligase (nuclear) | Auxin glues **Aux/IAA** repressor to receptor → proteasome → **ARF** free |
| **Gibberellin** | **GID1** (nuclear, soluble) | GA–GID1 captures **DELLA** → SCF ubiquitination → proteasome |
| **Cytokinin** | **AHK** histidine kinases (ER/membrane, bacterial-type) | Phosphorelay (AHP) → **type-B ARR** transcription factors on |
| **Ethylene** | **ETR1** (ER membrane, Cu cofactor) | Receptor is a **negative regulator**; ethylene switches it off → **EIN3** stabilised |
| **Abscisic acid** | **PYR/PYL** (cytosolic) | ABA glues receptor to **PP2C** phosphatase and inhibits it → **SnRK2** on |
| **Jasmonate** | **COI1–JAZ** (SCF) | JA-Ile glues **JAZ** repressor to receptor → proteasome → **MYC2** free |
| **Salicylate** | **NPR1** (cytosol → nucleus) | SA redox change → NPR1 monomers → **TGA** factors → *PR* genes |
| **Brassinosteroid** | **BRI1** receptor-like kinase (membrane) | Relay switches off **BIN2** kinase → **BES1/BZR1** free |
| **Strigolactone** | **D14** α/β-hydrolase | Hormone hydrolysed → **SMXL/D53** repressor routed to SCF |

Two conclusions follow. **Auxin, jasmonate and strigolactone use the identical device** — a small molecule acting as a *molecular glue* between an F-box receptor and a repressor — and every row converges on a transcription factor, the same regulatory layer studied for animal cells in [05 — Gene regulation](../05-molecular-biology/06-gene-regulation.md).

### Dose–response is not linear

```
   response
      ▲      shoot optimum ≈ 10⁻⁵ M
      │     ╱▔▔▔▔╲      supra-optimal → inhibition
      │────╱────────╲─────────────────▶ log [auxin]
      │  root optimum ≈ 10⁻¹⁰ M, already INHIBITED at 10⁻⁶ M
      ▼
```

At 10⁻⁶ M auxin promotes stem elongation and *inhibits* root elongation: **same molecule, same dose, opposite signs, because the tissues have different optima**. Response also depends on **timing** (a pulse versus sustained exposure, since auxin induces its own repressors) and on hormonal context, so "more hormone = more effect" is always wrong.

## The discovery trail: from Darwin to IAA

```
1880  Darwin & Darwin — the coleoptile TIP perceives unilateral light,
      the message travels DOWN, bending happens BELOW it
1913  Boysen-Jensen — it passes through AGAR: a chemical, not an
      electrical signal. Paál — an asymmetric tip bends a seedling
      in complete darkness, so light is only the stimulus
1926  Went — tip on AGAR, agar on a decapitated stump: symmetric
      block → straight growth; asymmetric block → bending AWAY
      from the block → a growth-promoting substance: AUXIN
1931  identified as INDOLE-3-ACETIC ACID (IAA)
```

Three principles survive: **perception is localised to the tip, the message is a diffusible chemical, and it is the asymmetry of the chemical — not of the light — that bends the organ.**

## Auxin: indole-3-acetic acid

**Synthesis:** young leaves, shoot apices and cambium, from tryptophan (TAA/YUC enzymes). **Transport:** *polar*, cell to cell in a fixed direction — basipetal in shoots, acropetal in roots — largely independent of mass flow, so distribution is designed rather than diluted.

### Polar transport: the chemiosmotic model

```
   WALL / apoplast (pH ≈ 5.5)        CYTOSOL (pH ≈ 7.0)
   IAA ⇌ IAA⁻ + H⁺  (pKa 4.75)
   protonated IAAH is lipophilic ──▶ IAA⁻ TRAPPED (anion trapping)
        ▲                                │
        └── PIN EFFLUX carriers ◀────────┘  AUX1/LAX influx helps
               on ONE FACE ONLY
```

**Direction = which membrane face carries the PIN efflux carriers.** Because PIN localisation is set by cell polarity and by auxin itself, flow reinforces its own path (**canalisation**), so **auxin gradients encode the geometry of the plant**: which side, how far from the apex, which way is down.

### TIR1: auxin as molecular glue

```
   auxin sits in a pocket on TIR1, an F-BOX PROTEIN of SCF^TIR1
        ▼
   AUXIN ACTS AS MOLECULAR GLUE: it contacts receptor AND the
   Aux/IAA repressor, so the pair binds only when auxin is present
        ▼
   Aux/IAA polyubiquitinated → 26S PROTEASOME degrades it
        ▼
   ARF TRANSCRIPTION FACTORS released from the clamp
        ▼
   AuxREs → auxin-responsive genes ON: expansins, H⁺-ATPases, PINs
   — and Aux/IAA and GH3, auxin's own brake and inactivation enzyme
```

**Auxin activates nothing: it glues a receptor to its substrate so the repressor can be destroyed.** The default state is repression, and the response needs continuous auxin — which is why *transport*, not synthesis alone, decides the outcome. Because auxin rapidly induces its own repressors, a sustained signal is partly adapted to while a changing one is read cleanly: the same logic as receptor desensitisation in animal endocrinology.

### The acid growth hypothesis: how a hormone becomes a centimetre

```
   auxin perceived at membrane (TMK kinase) and nucleus (TIR1)
        ▼  minutes
   PLASMA-MEMBRANE H⁺-ATPase activated → wall pH 5.5 → ≈ 4.5
        ▼
   EXPANSINS break hydrogen bonds between cellulose and hemicellulose
   tethers — they unglue the wall, they do not digest it
        ▼
   wall CREEP: the same turgor stretches the loosened wall
        ▼
   water follows osmotically → volume ↑ → new wall deposited
```

Two arms run in parallel: **rapid** (minutes, pump phosphorylation, no new protein) and **slow** (hours, new expansins and PINs). The pump is a P-type ATPase ([03 — Active transport](../03-cellular-processes/03-active-transport.md)), the energy is ATP's ([04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md)), and the driving water follows turgor ([04 — Water transport and transpiration](04-water-transport-and-transpiration.md)). Remove turgor, a competent wall or the pump, and auxin does nothing.

### Auxin's other jobs

| Process | Mechanism in outline |
| --- | --- |
| **Apical dominance** | Auxin from the apical meristem suppresses lateral buds *indirectly* — promoting strigolactone and destroying cytokinin in the nodes; remove the apex and buds are released. Meristems: [01 — Plant cells and tissues](01-plant-cells-and-tissues.md) |
| **Phototropism, gravitropism** | Light or gravity re-localises PINs → auxin asymmetric on one flank → **differential elongation** → bending |
| **Root initiation** | High auxin : cytokinin ratio specifies roots — basis of rooting powders (IBA, NAA) |
| **Vascular differentiation** | Auxin flow canalises cambial initials into xylem and phloem strands; [03 — Xylem and phloem](03-xylem-and-phloem.md) |
| **Fruit development** | Seed auxin signals the ovary wall to grow; applied auxin causes **parthenocarpy**; [06 — Plant reproduction](06-plant-reproduction-and-alternation-of-generations.md) |
| **Embryonic patterning** | Auxin maxima and flow direction specify the root–shoot axis |

## Gibberellins

**Discovery:** the *bakanae* ("foolish seedling") disease of rice — tall, pale seedlings that collapse — caused by *Gibberella fujikuroi*, which secretes **gibberellic acid (GA₃)**. Over 130 GAs exist; GA₁, GA₃ and GA₄ are bioactive. **Synthesis:** from geranylgeranyl diphosphate via *ent*-kaurene, starting in the plastid. **Transport:** xylem and phloem, so grafting shows long-distance movement. **Effects:** internode elongation and **bolting**, leaf and fruit growth, **breaking dormancy**, **parthenocarpy**.

### Germination: the aleurone response

```
   embryo makes GA → diffuses to the ALEURONE layer
        ▼
   GID1 binds GA → captures DELLA → SCF ubiquitinates DELLA
   → 26S PROTEASOME destroys it
        ▼
   GAMYB transcription factors released → α-AMYLASE and other
   hydrolase genes ON → endosperm starch → sugar → embryo fed
        ▼
   radicle emerges → DORMANCY BROKEN
```

This is why barley is germinated before brewing — the brewer harvests GA-induced α-amylase — and it is the direct antagonist of ABA in the germination decision. Seeds and dormancy: [06 — Plant reproduction](06-plant-reproduction-and-alternation-of-generations.md).

### Dwarf mutants and the Green Revolution

| Class | Defect | Apply GA | Interpretation |
| --- | --- | --- | --- |
| **GA-responsive dwarf** (*sd1*, maize *d5*) | **Biosynthesis** blocked | grows tall | hormone missing |
| **GA-insensitive dwarf** (*Rht*, *gai*) | **Reception** blocked — DELLA cannot be degraded | stays short | signal unreadable |

The **GA-application test** separates a biosynthetic lesion from a signalling lesion anywhere in biology ([01 — Genes, alleles, genotype, phenotype](../04-genetics/01-genes-alleles-genotype-phenotype.md)). *Rht-B1b*/*Rht-D1b* wheat (from Norin 10) and rice *sd1* (a GA₂₀-oxidase lesion) are the most-planted hormone mutants in history: semi-dwarf stature plus high nitrogen means **no lodging**, so fertiliser can be applied safely, grain rises and straw falls — a higher harvest index, and the **Green Revolution**. Breeding selected for **a hormone that cannot be read**, converting a growth response into a structural limit. GA₃ also lengthens seedless grape bunches and drives malting.

## Cytokinins

**Discovery:** Skoog and Miller's tobacco pith cultures — auxin alone gave unorganised **callus**; auxin plus a factor from autoclaved DNA (**kinetin**; natural form **zeatin**, from *Zea*) gave organised **shoots**. The name comes from the observed promotion of **cytokinesis**. **Synthesis:** mainly **root tips** (IPT enzyme) and developing seeds; moved **acropetally in the xylem** with the transpiration stream ([03 — Xylem and phloem](03-xylem-and-phloem.md); [04 — Water transport](04-water-transport-and-transpiration.md)). **Effects:** cell division (they drive cell-cycle entry by inducing D-type cyclins rather than acting as a mitotic motor), **shoot initiation**, **delay of senescence**, chloroplast development and nutrient mobilisation — cytokinin makes a tissue behave like a sink.

### Mechanism: a bacterial-type two-component system

Plants kept bacterial signalling hardware; animals did not, so this pathway resembles no animal receptor kinase:

```
   cytokinin binds the CHASE domain of an AHK histidine kinase
        ▼
   autophosphorylation on HIS → phosphotransfer to AHP protein
   → nucleus → phosphorylates TYPE-B ARR transcription factors
        ▼
   cytokinin genes ON (type-A ARR are short-lived repressors
                       → negative feedback)
```

### The auxin : cytokinin ratio decides organ identity

| Auxin : cytokinin | Outcome in culture | Applied parallel |
| --- | --- | --- |
| **High auxin, low cytokinin** | **Roots** | Rooting powders (IBA, NAA) for cuttings |
| **Low auxin, high cytokinin** | **Shoots** | Shoot multiplication in micropropagation |
| **Balanced** | **Callus** | Maintenance lines; somatic embryos on adjustment |

The tumour analogy is exact: ***Agrobacterium tumefaciens*** transfers T-DNA encoding **both** an auxin gene (*iaaM/iaaH*) and a cytokinin gene (*ipt*), so the unopposed balanced supply produces a crown gall — hormone autonomy as plant "cancer" ([07 — Microbiology](../07-microbiology/)).

## Ethylene

**The only gaseous hormone** — small, lipophilic, diffusing through air and tissue, so it needs no transport stream. **Synthesis:** methionine → SAM → **ACC** (**ACC synthase, ACS, is rate-limiting**) → ethylene (ACC oxidase, needs O₂), with methionine recycled (Yang cycle). Induced by **wounding, flooding** (ACC made in waterlogged roots travels in the xylem — a drowning signal from below), auxin, pathogens and fruit maturity. **Effects:** ripening, **abscission** of leaves, flowers and fruit, floral senescence, the **triple response**, inhibition of root and stem elongation, root hair initiation, aerenchyma under flooding, defence genes.

### Perception: a negative receptor (the double negative)

```
   NO ETHYLENE: ETR1 ACTIVE → activates CTR1 (Raf-like kinase)
                → CTR1 phosphorylates EIN2 → EIN3 destroyed
                → NO RESPONSE (the receptor suppresses it)
   ETHYLENE BINDS Cu on ETR1 → receptor INACTIVATED
                → CTR1 off → EIN2 C-terminal cleaved → nucleus
                → EIN3/EIL1 stabilised → ERF factors ON
                → ripening, abscission, triple-response genes
```

**The hormone switches off the switch that was switching the response off** — a double negative, exactly parallel to auxin destroying a repressor, and both end in a freed transcription factor. The **triple response** of a dark-grown seedling — (i) inhibited elongation, (ii) radial swelling, (iii) exaggerated **apical hook** — is adaptive for pushing through soil, and the hook itself is maintained by auxin re-distributed under ethylene's influence.

### Ripening: system 1 and system 2

| Phase | Feedback | Where |
| --- | --- | --- |
| **System 1** | **Auto-inhibitory** — ethylene suppresses its own synthesis | Vegetative tissue, and all fruit before ripening |
| **System 2** | **Auto-catalytic** — ethylene induces its own ACS/ACO | **Climacteric fruit** at ripening onset |

System 2 is a **positive-feedback switch**: a small trigger becomes an all-or-none burst that commits the whole fruit to ripening; non-climacteric fruit (strawberry, grape, citrus) never switch it on. The shelf-life mutants map onto it: *rin* and *nor* are transcription factors required for the burst, while *Cnr* ("colourless non-ripening") is an **epigenetically silenced** SBP-box gene with a hypermethylated promoter — plant chromatin control ([05 — Gene regulation](../05-molecular-biology/06-gene-regulation.md)). **Abscission** is likewise an auxin–ethylene balance: while the blade exports plenty of auxin the abscission zone ignores ethylene; when export falls with age, ethylene sensitivity rises and cellulases and pectinases digest the middle lamella.

## Abscisic acid

**The name is a historical trap:** ABA was hunted as an abscission hormone, but abscission is mainly ethylene's job. Its real title is **stress and dormancy hormone** — drought, cold, salinity and seed maturation all raise it. **Synthesis:** from carotenoids in the plastid — violaxanthin/neoxanthin cleaved to xanthoxin (rate-limiting **NCED**, strongly induced by water deficit), then ABA in the cytosol. **Effects:** **stomatal closure** (fast), maintenance of **seed dormancy**, inhibition of germination, LEA/dehydrin and osmolyte gene expression, growth restraint, senescence, deeper rooting under drought.

### Stomatal closure: the guard-cell chain

```
   ABA in guard cell (or delivered in xylem from roots)
        ▼
   PYR/PYL binds ABA and GRABS a PP2C phosphatase (ABI1)
   → the phosphatase is INHIBITED (a brake on a brake)
        ▼
   SnRK2 kinases (OST1) escape dephosphorylation → ACTIVE
        ▼
   phosphorylate SLAC1 anion channel → Cl⁻/malate²⁻ efflux
   + K⁺ efflux through GORK channels
        ▼
   solutes out → water follows → guard cell turgor FALLS
        ▼
   PORE CLOSES → transpiration ↓
```

Opening is the mirror image: blue light activates phototropins, which turn on the same plasma-membrane H⁺-ATPase → hyperpolarisation → K⁺ influx → turgor rises → pore opens. Guard cells, light, CO₂ and ABA belong to [04 — Water transport and transpiration](04-water-transport-and-transpiration.md). **Dormancy** is decided the same way: high ABA : GA keeps the embryo quiescent and the seed dormant through winter, while after-ripening, chilling, light and leaching lower ABA and raise GA until α-amylase releases the radicle — **the seed reads the ratio, not either hormone alone**.

## Secondary and signalling hormones

Beyond the classical five: a steroid growth promoter and a set of defence and architecture signals, all using motifs already met.

### Brassinosteroids

**Brassinolide** and relatives are **steroid hormones** active at nanomolar concentrations — the closest plant analogue to animal steroids, but perceived very differently. They promote **cell elongation, vascular differentiation, pollen viability and photomorphogenesis**, and act synergistically with auxin (their transcription factors bind ARFs):

```
   brassinosteroid + BRI1 (LRR receptor-like KINASE) + BAK1
        ▼
   relay → BSU1 phosphatase → BIN2 (GSK3-like kinase) INACTIVATED,
   ending its inhibition of the transcription factors
        ▼
   BES1/BZR1 dephosphorylated → nucleus → growth genes ON
```

**BRI1 is a kinase receptor**, closer to animal receptor tyrosine kinases than the F-box and histidine-kinase receptors used elsewhere; severe mutants (*det2*, *cpd*) are extreme dwarfs — hormone mutants are how each pathway was found.

### Jasmonic acid and salicylic acid: two defence channels

| | **Jasmonate (JA-Ile)** | **Salicylate (SA)** |
| --- | --- | --- |
| Precursor | **α-Linolenic acid** from membrane lipid (LOX → AOS → AOC), conjugated to isoleucine | **Chorismate** (shikimate pathway) |
| Triggered by | **Wounding, chewing herbivores, necrotrophic** pathogens | **Biotrophic** pathogens, many viruses |
| Perception | **COI1–JAZ**: JA-Ile is the molecular glue, **JAZ** destroyed, **MYC2** released | **NPR1**: cytosolic oligomer → SA redox change → monomers enter nucleus with **TGA** factors |
| Outputs | Proteinase inhibitors, polyphenol oxidase, volatiles that recruit predators of the herbivore | **PR proteins** (chitinases, glucanases); **systemic acquired resistance** |

**JA and SA antagonise each other**, and pathogens exploit this: *Pseudomonas syringae* secretes **coronatine, a molecular mimic of JA-Ile**, switching off the salicylate channel while it kills tissue — choosing the wrong channel costs the infection. **Systemic acquired resistance** works the other way: a local infection releases a mobile signal (methyl salicylate, azelaic acid, pipecolic/N-hydroxypipecolic acid) that **primes the whole plant** for faster, stronger *PR* expression on second attack — plant innate-immune memory, analogous to priming in [07 — Microbiology](../07-microbiology/).

### Strigolactones

Carotenoid-derived hormones made mainly in **roots** (D27, CCD7, CCD8) with a dual role. As an **endocrine signal** they **suppress axillary bud outgrowth**, so deficient mutants become heavily branched or tillered — working with auxin in the bud and against cytokinin. Exuded into soil they stimulate **hyphal branching of arbuscular mycorrhizal fungi** (recruiting a symbiont) and, disastrously, **trigger germination of the parasitic witchweed *Striga***, which then attaches to cereal roots; *Striga hermonthica* devastates sorghum, millet and maize across Africa, so strigolactone biology is a food-security issue. Perception is the third molecular-glue system: **D14** hydrolyses the hormone, changes shape, and recruits the **SMXL/D53** repressor to an SCF ligase for proteasomal destruction. Auxin, jasmonate, strigolactone — same device, three jobs.

## Signal integration: antagonistic pairs and timing

No hormone decides alone: output is a function of **concentration, tissue, timing and context**, and the important decisions are made by **ratios**.

| Decision | Promoting | Opposing | Ratio controls |
| --- | --- | --- | --- |
| **Seed germination** | **GA** — α-amylase, dormancy break | **ABA** — dormancy maintenance | whether germination happens |
| **Organogenesis in culture** | **Auxin** → roots | **Cytokinin** → shoots | root, shoot or callus |
| **Branching** | **Cytokinin** (roots) releases buds | **Auxin** (apex) + **strigolactone** suppress | architecture, tillering |
| **Water stress** | **ABA** — closure, growth restraint | **GA, brassinosteroid, auxin** | survival versus growth |
| **Fruit ripening** | **Ethylene** (System 2) | **Auxin, ABA** earlier | timing of the irreversible switch |
| **Defence** | **Jasmonate** (necrotroph/herbivore) | **Salicylate** (biotroph) | which resistance programme runs |

**Why dose matters mechanically:** receptor capacity is finite, feedback (Aux/IAA, type-A ARR, GH3) adapts to sustained signals, and supra-optimal doses recruit secondary hormones — high auxin induces **ethylene**, which is what actually inhibits root elongation, so the bell curve is a network signature rather than a receptor quirk. **Why timing matters:** a transient auxin pulse patterns the embryo, sustained auxin maintains apical dominance, and the ABA→GA switch decides whether dormancy breaks this season or next. **Why tissue matters:** the same dose is promotional in shoots and inhibitory in roots because the optima differ.

## Tropisms and nastic movements

| | **Tropism** | **Nastic movement** |
| --- | --- | --- |
| Direction | Set by **direction of stimulus** (toward/away) | **Independent** of stimulus direction |
| Mechanism | **Differential growth** — unequal elongation of the two flanks | **Turgor change** in specialised motor cells |
| Reversible | No — growth is irreversible | Yes — turgor can be restored |
| Timescale | Hours to days | Seconds to minutes |
| Examples | Phototropism, gravitropism, thigmotropism | *Mimosa* leaf folding, Venus flytrap, stomata |

**Differential growth is the common mechanism of every tropism**, and since elongation is auxin-driven, **every tropism is an auxin-distribution problem**. In **phototropism** the tip perceives blue light through **phototropins**, PINs re-localise so auxin accumulates on the **shaded side** (Cholodny–Went model), that side elongates faster and the shoot **bends toward the light**; in roots the same asymmetry, read against the root's far lower optimum, gives **negative phototropism**. Tropisms, stems and leaves: [02 — Roots, stems, and leaves](02-roots-stems-and-leaves.md).

### Gravitropism

```
   GRAVITY
        ▼
   AMYLOPLASTS (starch-filled plastids) SEDIMENT in STATOCYTES
   — root cap columella, shoot endodermis — the statolith model
        ▼
   sedimentation re-localises PIN3 → auxin delivered to the
   LOWER side of the organ
        ├─▶ ROOT: lower side ABOVE its optimum → elongation
        │        inhibited below, upper side faster → bends DOWN
        └─▶ SHOOT: lower side still within its promotory range
                 → elongation faster below → bends UP
```

**One asymmetry, opposite outcomes — purely a consequence of the dose–response curves.** Starchless mutants still gravitropise, more slowly, so amyloplast sedimentation is a *statolith* mechanism rather than the sole sensor. Statocytes, amyloplasts and the meristems involved: [01 — Plant cells and tissues](01-plant-cells-and-tissues.md).

**Thigmotropism:** contact (a tendril on a support, a root against a stone) causes Ca²⁺ influx and **rapid auxin redistribution away from the touched side**, so the far side elongates and the organ coils or grows around the obstacle; repeated wind gives **thigmomorphogenesis** — shorter, thicker stems — and touch also primes **jasmonate** defence. **Nastic movements are not tropisms:** *Mimosa pudica* and the Venus flytrap run on **turgor, not growth**, because touch triggers action potentials that open K⁺/Cl⁻ channels in **pulvinus** motor cells, solute and water leave, and movement occurs in seconds and is fully reversible — the flytrap demands **two stimuli within about 20 seconds** before closing, a coincidence detector. It is the same ionic logic as guard cells in [04 — Water transport](04-water-transport-and-transpiration.md).

## Relevance to medicine and agriculture

### Synthetic auxin herbicides: 2,4-D

**2,4-Dichlorophenoxyacetic acid** (with MCPA, dicamba, triclopyr) is among the world's most-used herbicides, and its design follows directly from the mechanism:

```
   NATURAL IAA: made, transported, INACTIVATED within hours by
   GH3 conjugation and oxidation → self-limiting
   2,4-D: same shape at TIR1, but RESISTS conjugation and oxidation
   → accumulates → signalling never switches off
        ▼
   uncontrolled, uncoordinated growth: epinasty, malformed
   vasculature, disorganised roots
        ▼
   growth itself becomes lethal → the weed dies of its own response
```

**Selectivity is not receptor-based — every plant has TIR1.** It rests on **distribution and metabolism**: broad-leaved dicots take 2,4-D up readily, redistribute it through extensively branching veins and broad transpiring leaves, and cannot detoxify it fast enough, whereas cereals have parallel venation, a different cuticle, a sheathed protected meristem and **rapid detoxification** (ring hydroxylation → glucose conjugation). Hence selective broad-leaved weed control in wheat, maize, rice and lawns. The dose lesson in a sentence: IAA at controlled, tissue-specific dose *promotes* growth, while field-dose 2,4-D *overwhelms the feedback* — the herbicide works precisely because the pathway is dose-dependent and feedback-controlled. Low doses induce **somatic embryogenesis** in culture: same compound, inverted outcome.

### The Green Revolution and other GA uses

Semi-dwarf **Rht** wheat and **sd1** rice are the highest-impact hormone mutants ever deployed: short, lodging-resistant straw allowed heavy fertilisation without collapse, raising harvest index and feeding billions. Elsewhere **GA₃** lengthens seedless grape bunches (parthenocarpy), drives **malting** through α-amylase, controls bolting in lettuce, and dwarfs fruit rootstocks.

### Ethylene control: 1-MCP, ripening and sprouting

**1-Methylcyclopropene (1-MCP)** binds the **Cu cofactor of ETR1-type receptors essentially irreversibly** — it blocks *perception*, not synthesis, so the fruit still makes ethylene but cannot read it, CTR1 stays on, EIN3 stays off, the System 2 burst never fires, and climacteric fruit (apple, pear, kiwifruit, tomato) and cut flowers store for months. The mirror image is deliberate **ethylene exposure** (or the releaser **ethephon**) to ripen bananas and tomatoes on schedule, and silver thiosulphate (Ag⁺ replaces receptor Cu) to keep cut flowers fresh. **Sprout control in stored crops** is growth regulation too: **maleic hydrazide**, applied to onion and potato foliage before harvest, translocates to the storage organs and **blocks meristematic mitosis**, while carbamate sprout suppressants such as CIPC act on the same principle — dormancy itself being an ABA-maintained state. Sprouted stores burn stored carbohydrate on unusable shoot growth, so this is food security by hormone chemistry.

### Cytokinins in micropropagation, and salicylic acid → aspirin

**Micropropagation:** one shoot tip becomes **tens of thousands of identical plants** by manipulating the ratio — **high cytokinin** (BAP, kinetin, 2-iP) for shoot multiplication, then **high auxin** (IBA, NAA) for rooting. **Meristem-tip culture** (a 0.2–0.5 mm dome, no vascular connection) is the standard route to **virus-free** potato and strawberry stock, turning the meristems of [01 — Plant cells and tissues](01-plant-cells-and-tissues.md) into a therapeutic tool, and cytokinin's anti-senescence action is exploited in cut-flower and leafy-vegetable handling.

**Aspirin is a plant hormone story.** Willow bark (*Salix*) was used for fever and pain for centuries; its **salicin** metabolises to **salicylic acid**, which turns out to be a **plant defence hormone**. Free salicylic acid irritated the stomach, so at Bayer in 1897 Hoffmann acetylated it to **acetylsalicylic acid** — the name joins **a**-cetyl + **spir**aea (meadowsweet, *Filipendula ulmaria*) + **-in**. In humans it inhibits cyclo-oxygenase and prostaglandin synthesis; the botanical point is that the molecule, the name and the original use are all plant signalling in origin.

### The applied toolkit in one table

| Application | Agent | Mechanism exploited |
| --- | --- | --- |
| Broad-leaved weed control | **2,4-D**, MCPA | Non-metabolisable auxin mimic; monocot detoxification gives selectivity |
| Rooting cuttings | **IBA, NAA** | High auxin : cytokinin → root identity |
| Shoot multiplication, virus-free stock | **BAP, kinetin**, meristem culture | High cytokinin : auxin → shoot identity |
| Semi-dwarf cereals | **Rht / sd1** alleles | Undegradable DELLA / low GA → no lodging |
| Fruit and flower storage | **1-MCP**, silver thiosulphate | Irreversible block of ethylene *perception* |
| Ripening on schedule | **Ethylene, ethephon** | System 2 burst triggered deliberately |
| Sprout suppression in stores | **Maleic hydrazide**, CIPC | Inhibition of storage-organ meristem mitosis |

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Auxin always promotes growth" | It is **dose- and tissue-dependent**: ≈10⁻¹⁰ M promotes roots, ≈10⁻⁵ M promotes shoots, 10⁻⁶ M *inhibits* roots. The curve is bell-shaped. |
| "More hormone → stronger response" | Response **rises to an optimum then falls**; supra-optimal doses recruit secondary hormones (high auxin induces **ethylene**), so the sign can flip. |
| "ABA is the abscission hormone" | The name is a historical accident: ABA is the **stress/dormancy** hormone, while abscission follows the **auxin : ethylene balance**. |
| "Gibberellins maintain dormancy; ABA breaks it" | Exactly reversed: **ABA maintains dormancy, GA breaks it**; germination reads the ABA : GA ratio. |
| "Auxin or cytokinin alone decides organogenesis" | Neither acts alone — the **auxin : cytokinin ratio** decides root versus shoot (likewise ABA : GA in germination, JA : SA in defence). |
| "Tropisms are caused by unequal cell division" | Most tropisms are **differential elongation** of existing cells driven by asymmetric auxin; division matters mainly at meristems. |
| "The statolith is itself the gravity receptor" | Amyloplasts **sediment** and generate the signal, after which PINs re-localise; starchless mutants still respond, so other sensors contribute. |
| "The ethylene receptor activates the response" | **ETR1 is a negative regulator** — active without ethylene, switched off by it; perception removes a brake, just as auxin removes Aux/IAA. |
| "2,4-D poisons weeds directly" | It is a **persistent auxin mimic**: growth becomes uncontrolled and disorganised. Selectivity comes from uptake, distribution and **metabolism**, not a different receptor. |
| "Hormones act only where they are made" | Hormones are **made at sources and perceived at targets**; auxin's *polar* transport means **position**, not just presence, is the signal. |
| "Plant signalling is just simpler animal signalling" | Same logic, different hardware: F-box receptors, histidine-kinase phosphorelays, ER gas receptors, heavy reliance on **proteasomal destruction of repressors**. |
| "Ethylene only ripens fruit" | It also causes the **triple response**, abscission, senescence, hook formation, aerenchyma under flooding and stress defence. |

## Key facts

- Plants are sessile, so responses are **redistributions of growth**; the logic (receptor → transduction → gene expression, non-linear dose–response, antagonistic pairs) mirrors human endocrinology.
- The dominant motif is **removal of a brake**: auxin destroys Aux/IAA, GA destroys DELLA, ABA inhibits PP2C, ethylene inactivates a negative receptor, jasmonate destroys JAZ — all converging on a **freed transcription factor**.
- **Auxin acts as molecular glue**: IAA sits in **TIR1/AFB** (an F-box protein of SCF^TIR1) and contacts the **Aux/IAA repressor**, so ubiquitination and **26S proteasomal degradation** occur only when auxin is present, releasing **ARF** factors.
- **Polar auxin transport** via **PIN efflux carriers** makes gradients a positional signal; light and gravity act by re-localising PINs, not by making more auxin.
- **Acid growth:** auxin activates the membrane **H⁺-ATPase** → wall acidification → **expansins** loosen cross-links → **turgor** drives irreversible expansion.
- **Gibberellins** break dormancy via **α-amylase in the aleurone**, requiring **GID1-mediated DELLA degradation**; **Rht** wheat and **sd1** rice are semi-dwarf **Green Revolution** varieties defective in GA response or synthesis.
- **Cytokinins** promote division, shoot formation and delay of senescence through a **bacterial-type histidine kinase phosphorelay**; the **auxin : cytokinin ratio** gives roots (high auxin) or shoots (high cytokinin).
- **Ethylene** is the only gaseous hormone; **ETR1 is a negative receptor**, and climacteric ripening runs on **autocatalytic System 2** after auto-inhibitory System 1.
- **ABA** closes stomata via **PYR/PYL → PP2C inhibition → SnRK2 → SLAC1**, maintains seed dormancy and antagonises GA.
- Second tier: **brassinosteroids** (BRI1 kinase → BES1/BZR1), **jasmonate** (COI1–JAZ; herbivores and necrotrophs), **salicylate** (NPR1 → *PR* genes → **systemic acquired resistance**), **strigolactones** (D14 → SMXL degradation; branching, mycorrhizae, *Striga*).
- **JA and SA antagonise** each other, so pathogen lifestyle dictates the channel — coronatine mimics JA-Ile to exploit this.
- Every tropism is **differential growth** from asymmetric auxin: **phototropism** (shaded side), **gravitropism** (amyloplast **statoliths** → auxin below), **thigmotropism**; **nastic** movements are the opposite kind — rapid, reversible **turgor** changes.
- Applications: **2,4-D** selective auxin herbicides, **1-MCP** blocking ethylene receptors in storage, **cytokinin-driven micropropagation**, semi-dwarf cereals, and **salicylic acid** as the botanical origin of **aspirin**.

## Practice questions

**1. In the current model of auxin perception, auxin itself functions as**

A. A transcription factor binding auxin response elements directly
B. Molecular glue that increases TIR1's affinity for the Aux/IAA repressor, targeting it for ubiquitin–proteasome degradation
C. A kinase that phosphorylates and activates ARF proteins
D. An inhibitor of the 26S proteasome that stabilises ARF factors

**Answer: B**

Explanation: Auxin sits in a pocket on TIR1/AFB, an F-box protein of an SCF ubiquitin ligase, and contacts the Aux/IAA repressor at the same time, so the repressor is ubiquitinated and destroyed only when auxin is present; freed ARFs then switch on auxin-responsive genes. Auxin does not bind DNA (A), is not a kinase (C), and recruits the proteasome rather than inhibiting it (D).

---

**2. The acid growth hypothesis proposes that auxin promotes stem elongation by**

A. Stimulating cellulase digestion of cellulose microfibrils
B. Activating the plasma-membrane H⁺-ATPase so the wall acidifies, expansins loosen cross-links, and turgor then drives expansion
C. Increasing cell division in the intercalary meristem
D. Depolymerising cutin so water enters the epidermis

**Answer: B**

Explanation: Auxin activates a P-type H⁺-ATPase (the rapid, post-translational arm) → wall pH falls to about 4.5 → **expansins** break the hydrogen bonds holding hemicellulose to cellulose without digesting the wall → existing turgor stretches the loosened wall irreversibly. Digestion by cellulase would destroy rather than loosen the wall (A), elongation is expansion not division (C), and cutin belongs to the cuticle (D).

---

**3. A root placed horizontally bends downward because**

A. Gravity directly activates a growth receptor in the elongation zone
B. Amyloplast statoliths sediment, PIN carriers deliver auxin to the lower side, and that concentration lies above the root's optimum, so elongation is inhibited below while the upper side grows faster
C. The lower side of the root dies while the upper side keeps growing
D. Starch is digested on the lower side, making those cells lighter

**Answer: B**

Explanation: Sedimentation of amyloplasts in columella statocytes re-localises PIN efflux carriers, auxin accumulates on the lower side, and because the root optimum is near 10⁻¹⁰ M that asymmetry *inhibits* lower-side elongation — so the upper side wins and the root curves down. The identical asymmetry in a shoot bends it upward, which is why the answer depends on the dose–response curve rather than a dedicated gravity receptor (A).

---

**4. During cereal germination, gibberellin induces α-amylase in the aleurone layer by**

A. Binding a membrane G-protein-coupled receptor that raises cAMP
B. Acting directly as a transcription factor on the α-amylase promoter
C. Binding GID1 and promoting ubiquitin–proteasome degradation of DELLA repressors, releasing factors such as GAMYB
D. Blocking abscisic acid receptors in the embryo

**Answer: C**

Explanation: GA–GID1 recruits DELLA to an SCF ubiquitin ligase, DELLA is destroyed by the proteasome, and GAMYB-type factors then drive α-amylase so endosperm starch becomes sugar for the embryo. GA is neither a second messenger like cAMP (A) nor a transcription factor itself (B); ABA antagonism is a separate opposing input, not the induction mechanism (D).

---

**5. Semi-dwarf wheat carrying the Green Revolution *Rht-B1b* allele stays short because**

A. It cannot synthesise any gibberellin
B. Its DELLA protein cannot be degraded in response to gibberellin, so applying GA does not restore height
C. Its gibberellin receptors are over-expressed, driving excessive growth
D. It lacks expansins in the stem

**Answer: B**

Explanation: *Rht-B1b* encodes a DELLA protein that still represses growth but is no longer recognised for SCF-mediated degradation, making the plant **gibberellin-insensitive** — the diagnostic test is that applied GA fails to restore height, unlike a biosynthetic dwarf such as rice *sd1* (A). Excess receptor would not produce a dwarf (C), and expansin loss is not the lesion (D).

---

**6. Callus that produces roots rather than shoots in culture is best explained by**

A. A high cytokinin to auxin ratio
B. A high auxin to cytokinin ratio
C. Equal and maximal levels of both hormones
D. Absence of both hormones

**Answer: B**

Explanation: Skoog and Miller showed that the *ratio* specifies organ identity — **high auxin/low cytokinin → roots**, **low auxin/high cytokinin → shoots**, balanced levels maintain undifferentiated **callus**. Option A is the shoot-forming condition (reversed), C gives callus, and D gives no organised development. The same logic explains why *Agrobacterium*, transferring both hormone genes, produces a tumour.

---

**7. 1-Methylcyclopropene extends the storage life of apples because it**

A. Inhibits ACC oxidase so no ethylene is synthesised
B. Degrades ethylene in the storage atmosphere
C. Binds irreversibly to the copper site of ethylene receptors such as ETR1, so the fruit cannot perceive the ethylene it still produces
D. Blocks EIN3 transcription factors in the nucleus

**Answer: C**

Explanation: ETR1 is a *negative* regulator switched off by ethylene; 1-MCP occupies its Cu cofactor permanently, so the receptor stays active, CTR1 keeps EIN2 off, and the autocatalytic System 2 ripening burst never fires — perception, not synthesis, is blocked. The fruit continues producing ethylene, ruling out A and B, and no mechanism involves directly blocking EIN3 (D).

---

**8. Abscisic acid closes stomata during drought by**

A. Opening potassium channels that pump K⁺ into guard cells
B. Binding PYR/PYL receptors that inhibit PP2C phosphatases, allowing SnRK2 kinases to open SLAC1 anion channels so solutes and then water leave the guard cells
C. Stimulating the guard-cell H⁺-ATPase to hyperpolarise the membrane
D. Causing guard cells to divide and seal the pore

**Answer: B**

Explanation: ABA glues PYR/PYL to the PP2C phosphatase ABI1 and inhibits it; with that brake removed, SnRK2 kinases stay active, phosphorylate SLAC1, anions exit followed by K⁺ and water, turgor falls and the pore closes. Option C describes blue-light-induced *opening*, A would raise turgor and open the pore, and guard cells change shape by turgor, never by division.

---

**9. A necrotrophic fungus secreting coronatine, a molecular mimic of jasmonate, is best described as**

A. Activating salicylate-dependent systemic acquired resistance
B. Hijacking the COI1–JAZ pathway to suppress the salicylate defence channel, because jasmonate and salicylate signalling antagonise each other
C. Blocking strigolactone synthesis to increase host branching
D. Inducing ethylene to prevent fruit ripening

**Answer: B**

Explanation: JA-Ile normally glues JAZ repressors to the COI1 F-box receptor for degradation, so a mimic that activates this channel keeps the salicylate arm (NPR1 → *PR* genes, effective against biotrophs) suppressed while the fungus kills tissue. Systemic acquired resistance is precisely what is being avoided (A); nothing here involves strigolactone (C) or ethylene (D).

---

**10. 2,4-D kills broad-leaved weeds selectively in cereal crops because**

A. Cereal receptors do not bind 2,4-D whereas weed receptors do
B. It is a contact poison that volatilises onto adjacent leaves
C. All plants lack auxin receptors except the weeds
D. All plants perceive it, but it resists the GH3-mediated inactivation that limits natural IAA, and cereals take up, redistribute and detoxify it far less effectively than broad-leaved weeds, so dicots die of uncontrolled, disorganised growth

**Answer: D**

Explanation: TIR1 exists in every plant, so selectivity cannot be receptor-based (A, C); it comes from persistence of the mimic relative to IAA, which GH3 enzymes rapidly conjugate, plus differences in uptake, vascular distribution and ring-hydroxylation detoxification. It is not a contact poison (B): the weed dies because sustained, unregulated auxin signalling produces epinasty, malformed vasculature and root proliferation until growth itself becomes lethal.
