# Early Development and Cleavage

## Why it matters

In the first week of human development nothing grows: no heart, no gut, no brain, and no placenta to feed anything. What happens instead is a fixed sequence — **cells divide, then cells sort, then the first fate decision is taken** — and that decision, *embryo or placenta*, is made before the embryo has attached to the uterus.

This chapter is the mechanics of how one diploid cell becomes a structured, implanting **blastocyst**, and then how a disc of apparently identical cells reorganises into the three tissue layers that build the body.

```
1. DIVIDE   cleavage — many cells, no growth, total volume constant
2. SORT     compaction + cavitation — position creates difference
3. COMMIT   embryo vs placenta, then the three germ layers
```

Each step answers a physical or informational problem, so the arrow chains are the argument, not decoration.

## The first week at a glance

Fertilisation — sperm–egg fusion, pronuclear union, restoration of diploidy — is covered in [02 — Fertilization and the Zygote](02-fertilization-and-the-zygote.md); the clock starts when it finishes.

| Day | Stage | Cells | Landmark | Why it matters |
| --- | --- | --- | --- | --- |
| **0** | **Zygote** | 1 | Diploidy restored | Totipotent — embryo *and* placenta |
| **1** | 2-cell | 2 | First cleavage (≈30 h) | Cell size halves; volume unchanged |
| **2** | 4-cell | 4 | Second cleavage | Maternal stores still driving |
| **3** | 8-cell | 8 | **Compaction**; minor genome activation | First difference between cells |
| **4** | **Morula** | 16–32 | Solid ball; outer/inner separate | Must stay small to pass the oviduct |
| **5** | **Blastocyst** | ~70–100 | **Blastocoel** forms; **ICM** vs **trophoblast** | First cell fate decision |
| **6** | Hatching | ~100+ | Escape from the zona pellucida | Cannot implant while enclosed |
| **6–7** | **Implantation begins** | — | Trophoblast invades endometrium | Syncytiotrophoblast erodes it |
| **9–10** | Implantation complete | — | hCG enters maternal blood | Corpus luteum rescued |
| **~15–16** | Bilaminar disc | — | Epiblast + hypoblast | Substrate for gastrulation |
| **~16–21** | **Gastrulation** | — | Primitive streak; three germ layers | Body plan fixed; potency collapses |

```
ZYGOTE (d0) → 2-CELL (d1) → 4-CELL (d2) → 8-CELL COMPACTION (d3)
   → MORULA (d4) → BLASTOCYST (d5) → HATCHING (d6)
   → IMPLANTATION + hCG (d6-7) → GASTRULATION (d16-21)
```

## Cleavage: division without growth

**Cleavage** is a series of rapid mitotic divisions in which cell number rises while the **total volume of the embryo does not change**: a 2-cell embryo is the same size as the zygote, so each blastomere is half its parent's volume and by the 8-cell stage about one eighth of the original. The embryo is not getting bigger — it is getting *partitioned*. The machinery is ordinary **mitosis** and **cytokinesis** ([11 — Mitosis and Cytokinesis](../03-cellular-processes/11-mitosis-and-cytokinesis.md)); what is unusual is the schedule and what is missing from it.

### Why the embryo must not grow

| Constraint | What it demands | How cleavage copes |
| --- | --- | --- |
| **Tube passage** | The oviduct is narrow and muscular | Volume stays at oocyte size, so the embryo travels as a single-cell-sized object |
| **Exchange** | No blood supply — everything crosses the surface | Halving cell volume keeps the surface-area-to-volume ratio high; a growing solid ball would develop a necrotic core |
| **Zona pellucida** | The glycoprotein shell does not stretch | Enlargement is impossible — which is why the embryo must later hatch |
| **Timing** | The lining is receptive a few days each cycle | Fast division delivers a blastocyst by day 5 |

The trade is explicit: **the embryo buys speed and exchange capacity by giving up size.**

### What drives the divisions: maternal stores, then the embryonic genome

A cell cannot divide without making replication and mitosis proteins, yet the new genome is almost transcriptionally silent. The explanation is that the oocyte is pre-stocked: during oogenesis it accumulates huge reserves of **maternal mRNA and protein** — ribosomes, histones, cyclins, CDKs, repair enzymes ([01 — Spermatogenesis and Oogenesis](01-spermatogenesis-and-oogenesis.md)). Cleavage spends a **pre-paid toolkit** packed in during the months of oocyte growth.

That toolkit runs out, so control must be handed over. **Zygotic genome activation (ZGA)** is the handover:

```
MATERNAL mRNA + PROTEINS (stockpiled in the oocyte)
      │  drive cleavage 1, 2, 3 … transcription off, then DEGRADED
      ▼
ZYGOTIC GENOME ACTIVATION
      │  minor wave at the first cleavages; major wave by the
      │  4- to 8-cell stage in humans → embryonic alleles read
      ▼
failure to activate → arrest at the 4- to 8-cell stage
```

This is why **IVF embryos that arrest at the 4- to 8-cell stage are presumed to have failed ZGA**: they exhausted the maternal stock before their own genome took over. It is also the first moment the embryo's own genotype matters, and the regulation involved — timed unmasking and destruction of stored transcripts — is ordinary gene regulation ([06 — Gene Regulation](../05-molecular-biology/06-gene-regulation.md)).

### Checkpoints during cleavage: speed versus fidelity

Somatic cells spend 6–12 h in G1 growing and hours in G2 checking; cleavage embryos compress this so that **S and M alternate with little or no growth phase**, giving cycles of roughly 12–24 h with no increase in mass.

| Feature | Typical somatic cell | Cleavage embryo |
| --- | --- | --- |
| G1 growth | Long; mass increases | Negligible — growth is forbidden |
| Damage checkpoint | Strict (p53 → arrest/apoptosis) | **Relaxed**; repair delegated to stored maternal machinery |
| Spindle checkpoint | Strict | **Must still operate** |
| Drive to divide | Mitogens + restriction point | Maternal cyclin/CDK stores |

The asymmetry is the point ([10 — Cell Cycle and Checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md)). Speed is bought by loosening the G1/S and damage gates, but the spindle checkpoint cannot be relaxed: a mis-segregated chromosome would corrupt every descendant at once. The cost is clinical — errors that would arrest a somatic cell slip through, producing **mosaicism** (cells with different chromosome numbers) and much of the aneuploidy and early miscarriage seen in human pregnancy. Maternal age raises this further, because most aneuploidy originates in the oocyte's own meiosis rather than in cleavage mitosis.

## Morula → blastocyst: compaction and cavitation

Between day 3 and day 5 the embryo performs two operations that convert a heap of similar cells into a structure with an inside, an outside and two distinct populations.

### Compaction: position becomes information

At the 8-cell stage the blastomeres, previously round and loosely associated, **flatten against one another and maximise contact** — the morula becomes smooth and compact, with individual boundaries no longer visible. This is **compaction**, and it is driven by **E-cadherin**, a calcium-dependent adhesion glycoprotein in the plasma membrane ([02 — Plasma Membrane and Nucleus](../02-cell-biology/02-plasma-membrane-and-nucleus.md)).

```
8-CELL (round, loosely associated cells)
      │  E-cadherin zips cells together
      ▼
COMPACTED MORULA
      ├──▶ OUTER cells: exposed to the exterior → polarise,
      │     form TIGHT JUNCTIONS → sealed epithelium → trophoblast
      └──▶ INNER cells: buried, no apical surface → cell cluster → ICM
                    ▼
        FIRST PHYSICAL DIFFERENCE → FIRST FATE DIFFERENCE
```

Why this matters: **before compaction all blastomeres are totipotent and demonstrably equivalent.** Compaction creates the two environments that make the first decision possible — an outer cell senses fluid and shell, an inner cell does not. Position, not lineage, is the instruction. Outer cells activate the **Hippo pathway**, keeping YAP out of the nucleus and permitting **CDX2** (trophoblast genes); inner cells retain **OCT4** and **NANOG**. Identical DNA, different instructions, because the cells sit in different places — gene regulation defining a cell type, as in [01 — Cell Theory and Cell Types](../02-cell-biology/01-cell-theory-and-cell-types.md). The outer tight junctions are also what make cavitation possible: a cavity cannot be held by a leaky epithelium.

### Cavitation: pumping a cavity

The **blastocoel** is not a hole left by dying cells; fluid is pumped in.

```
TROPHECTODERM (outer epithelium, tight junctions sealed)
      │  Na⁺/K⁺-ATPase pumps Na⁺ into the cavity — ATP required
      ▼
HIGH Na⁺ INSIDE THE BLASTOCOEL
      │  water follows osmotically, partly through AQUAPORINS
      ▼
CAVITY EXPANDS → cells squeezed to the rim
      ▼
BLASTOCYST: hollow ball with an ICM at one pole
```

The salt is moved and the water follows — the coupled logic of [03 — Active Transport](../03-cellular-processes/03-active-transport.md). Cavitation is energy-dependent, not passive collapse.

### The blastocyst: two populations, one decision

By day 5 the **blastocyst** holds roughly 70–100 cells:

| Population | Position | Key genes | Fate | Potency |
| --- | --- | --- | --- | --- |
| **Inner cell mass (ICM)** | Packed at one pole, in contact with fluid | **OCT4, SOX2, NANOG** | **Embryo proper** | **Pluripotent** |
| **Trophoblast** | Single epithelium forming the shell | **CDX2, GATA3** | **Embryonic part of the placenta** | Extra-embryonic, lineage-restricted |

This is the **first cell fate decision**: not a choice between two body fates but between *the body* and *the support system for the body*. The potency ladder of [01 — Cell Theory and Cell Types](../02-cell-biology/01-cell-theory-and-cell-types.md) applies exactly — ICM cells are **pluripotent** (every body cell, no placenta), trophoblast cells have left that rung behind. The zygote was **totipotent**; compaction plus Hippo/CDX2 signalling is the mechanism that halves totipotency.

## Implantation

Between days 6 and 10 the blastocyst attaches to and burrows into the uterine wall. This is an act of controlled invasion by the trophoblast, and it succeeds only if the endometrium is prepared.

### The trophoblast differentiates into two layers

| Layer | Structure | Behaviour | Role |
| --- | --- | --- | --- |
| **Cytotrophoblast** | Mononucleated cells, inner layer | Proliferative progenitor compartment | Supplies new cells; core of the villi |
| **Syncytiotrophoblast** | **Multinucleated syncytium**, outer layer | Secretes proteases and hyaluronidase, erodes endometrium, engulfs debris | Embeds the embryo; later the exchange surface |

```
BLASTOCYST contacts receptive endometrium → trophoblast proliferates
      ├──▶ CYTOTROPHOBLAST   mononuclear, dividing (source layer)
      └──▶ SYNCYTIOTROPHOBLAST  cells fuse → one multinucleated mass
                │  proteases digest the endometrial matrix
                ▼
        invasion → lacunae fill with maternal blood
                ▼
        embryo buried; placental exchange begins
```

A continuous syncytium moves as one mass and seals around maternal blood spaces without paracellular leaks — and, like the syncytia of [01 — Cell Theory and Cell Types](../02-cell-biology/01-cell-theory-and-cell-types.md), its many nuclei support a shared cytoplasm. The exchange consequences belong to [05 — Placenta and Maternal–Fetal Exchange](05-placenta-and-maternal-fetal-exchange.md).

### The endometrium must be receptive

- After ovulation the corpus luteum secretes **progesterone**, converting the oestrogen-primed proliferative lining into the **secretory endometrium**: coiled glycogen-rich glands, oedematous stroma, and surface molecules that let the blastocyst attach.
- No fertilisation → corpus luteum regresses → progesterone falls → the functional layer is shed: **menstruation**.
- The hormonal axis involved is [04 — Endocrine System](../10-anatomy-and-physiology/04-endocrine-system.md).

Implantation therefore needs two independent conditions to coincide: **a blastocyst on exactly the right days (≈6–10 post-ovulation) and a progesterone-primed endometrium.** Fail either and there is no pregnancy despite normal fertilisation.

### hCG rescues the corpus luteum

```
NO IMPLANTATION:                      WITH IMPLANTATION:
corpus luteum ages                    trophoblast secretes hCG (day ~6-7)
  → progesterone falls                  → hCG binds LH receptors on the
  → endometrium sheds                     CORPUS LUTEUM
  → MENSTRUATION                          → corpus luteum RESCUED
                                           → progesterone stays high
                                           → NO MENSTRUATION
                                          (placenta takes over ~week 8-12)
```

**Human chorionic gonadotrophin (hCG)** is a glycoprotein made by the syncytiotrophoblast, with an α subunit shared with LH, FSH and TSH and a distinctive **β subunit**. Because it mimics **luteinising hormone**, it acts on the LH receptor of the corpus luteum and prevents regression — a signal from the conceptus that stops the mother's cycle. The shared α subunit is why assays must target the β subunit.

**Mechanism of the pregnancy test.** A home urine test is an immunochromatographic sandwich assay: urine climbs the strip by capillary action; a mobile antibody against the **hCG β subunit**, linked to a coloured particle, binds any hCG; the complex is trapped by a fixed **capture antibody** at the test line, producing a visible band, while a control line must appear regardless, proving flow. Because hCG appears days after implantation, the test reads positive *before* a missed period. Quantitative assays follow **hCG doubling time**, distinguishing an ongoing pregnancy from an ectopic or failing one.

## Gastrulation: the most important event in your life

After implantation the embryo is a **bilaminar disc** — epiblast above, hypoblast below — and around days 16–21 that disc rearranges itself. Lewis Wolpert's line is the standard summary: *it is not birth, marriage or death, but gastrulation which is the most important event in your life.* The reason: this is where the body plan is set and **total potential is exchanged for committed lineage**.

### The primitive streak

A thickened band, the **primitive streak**, appears at the caudal end of the epiblast. Cells there lose epithelial character, detach from their neighbours, undergo an **epithelial-to-mesenchymal transition** and *ingress* between the two existing layers. The movement is one-directional: once through, a cell can never return to the epiblast pool.

```
EPIBLAST (pluripotent sheet — source of every body cell)
      │  primitive streak forms caudally; cells undergo EMT and INGRESS
      ▼
   ┌──────────────┬──────────────────┐
   ▼              ▼                  ▼
move laterally    move deepest       stay ABOVE the streak
between layers    (gut lining)       → remain ECTODERM
   ▼              ▼
MESODERM       DEFINITIVE ENDODERM
```

Two clarifications prevent the commonest errors: **all three layers come from the epiblast** (the hypoblast contributes only extra-embryonic endoderm), and the streak establishes the axes — its position defines anterior–posterior, and ingressed cells spreading laterally define left–right. **Gastrulation is axis formation as well as layer formation.**

### The three germ layers and what they become

| Germ layer | Derivatives | Tissue types produced ([09 — Human Biology](../09-human-biology/01-four-tissue-types.md)) |
| --- | --- | --- |
| **Ectoderm** | Epidermis and its derivatives (hair, nails, sweat glands), **entire nervous system**, lens, **neural crest** | Epithelial + nervous |
| **Mesoderm** | Muscle, bone, cartilage, blood and vessels, **dermis**, kidneys and gonads, spleen, body-cavity linings | Connective + muscle |
| **Endoderm** | Lining of the whole gut tube and its derivatives — **lungs, liver, pancreas, bladder** | Epithelial (glandular) |

Read it as a rule, not a list: **ectoderm = surface and wiring; mesoderm = framework and plumbing; endoderm = the tube and everything budding off it.** The **neural crest** deserves separate notice: cells that delaminate from the edge of the neural plate and migrate widely to give melanocytes, peripheral neurons and glia and much of the craniofacial skeleton. They are ectodermal yet produce connective tissue — which is why examiners use them to blur the neat ectoderm = skin/nerves rule.

### Potential collapses

```
EPIBLAST cell            pluripotent, uncommitted
      │ gastrulation
      ▼
ECTODERM / MESENDODERM / ENDODERM      each sheet = MULTIPOTENT
      │ further restriction
      ▼
lineage progenitors → tissue cells → terminally differentiated
```

**A single cell's potential collapses into three lineage-restricted sheets.** The step is irreversible; everything in [04 — Differentiation and Tissue Formation](04-differentiation-and-tissue-formation.md) elaborates these commitments. No adult cell is pluripotent, because the pluripotent population was spent making decisions in week three.

## Neurulation and axis patterning

### Neurulation: a forward link

Gastrulation sets up the nervous system's raw material at once. The **notochord** — a rod of mesoderm under the midline — **induces** the ectoderm above it to thicken into the **neural plate**; the plate folds, its **neural folds** fuse into the **neural tube**, which separates from the surface ectoderm to become brain and spinal cord.

```
NOTOCHORD (mesoderm) secretes inductive signals
      │  (SHH ventrally; BMP antagonists such as noggin/chordin dorsally)
      ▼
overlying ECTODERM → NEURAL PLATE
      ▼
plate folds → NEURAL GROOVE with rising NEURAL FOLDS
      ▼
folds fuse → NEURAL TUBE  (closure ~days 21–28)
      ├──▶ brain + spinal cord
      └──▶ neural crest cells delaminate from the fold crest
```

Failure of closure is a **neural tube defect** — anencephaly if the cranial end fails, spina bifida if the caudal end fails. Closure occurs in weeks 3–4, before many women know they are pregnant, which is why **periconceptional folate supplementation** targets the mechanism rather than the treatment.

### Organisers and Hox genes: patterning the axis

Layers alone do not make a body; there must be a head end and a tail end.

| Mechanism | What it does | Key feature |
| --- | --- | --- |
| **Embryonic organisers** | A localised signalling centre (Hensen's node, the human equivalent of the Spemann–Mangold organiser) instructing neighbours | Secreted signals acting over a distance — induction |
| **Hox genes** | Four clusters (**HOXA–D**) of homeobox transcription factors specifying regional identity along the anterior–posterior axis | **Collinearity** |

**Collinearity** is the high-yield idea: gene order along the chromosome matches expression order along the body axis (3′ genes → anterior, 5′ genes → posterior) and the order of switching-on in time. It is a positional code read out of gene regulation ([06 — Gene Regulation](../05-molecular-biology/06-gene-regulation.md)), and since each Hox cluster is an ordinary gene set with Mendelian alleles ([04 — Genetics](../04-genetics/01-genes-alleles-genotype-phenotype.md)), mutations give segment-specific limb and vertebral malformations.

```
ANTERIOR                                   POSTERIOR
  head       trunk        limbs        tail
   │           │            │           │
 3' Hox genes ──────────────────────▶ 5' Hox genes
 early expression                   late expression
```

## Medical relevance

### Teratogen timing: vulnerability is a schedule

A **teratogen** is any agent that causes structural malformation. The critical variable is *when* exposure occurs:

| Period | Weeks | What is happening | Effect of a teratogen |
| --- | --- | --- | --- |
| **Pre-implantation** | 1–2 | Cleavage, compaction, ZGA | **All-or-nothing**: embryo dies, or remaining cells compensate — little structural malformation |
| **Organogenesis** | **3–8** | Gastrulation, neurulation, limb and organ formation | **Highest risk of structural malformation** |
| **Fetal period** | 9–40 | Growth and functional maturation | Structural risk **falls sharply**; **functional** defects (growth restriction, CNS and behavioural deficits) remain |

| Teratogen | Critical window | Effect and mechanism |
| --- | --- | --- |
| **Thalidomide** | ~days 20–36 (limb bud) | Phocomelia, ear and hearing defects — binds cereblon, degrading transcription factors needed for limb patterning |
| **Alcohol (FAS)** | **Any time in pregnancy** | Growth restriction, microcephaly, facial dysmorphism, intellectual disability; no safe amount is established |
| **Folate deficiency** | Periconceptional (weeks 3–4) | **Neural tube defects** — spina bifida, anencephaly; impaired methylation and nucleotide supply |

The take-home: **after week 8 structural risk falls but functional risk remains**, which is why alcohol late in pregnancy damages the brain without causing limb defects.

### IVF embryo grading: morphology as a proxy for competence

Culture labs run the same week this chapter describes, so embryologists grade what they can see. At cleavage stage (days 2–3): cell number versus expected timing, **symmetry** and **percentage fragmentation** (extracellular debris that predicts poorer outcome). At blastocyst stage (day 5–6, the Gardner system): degree of expansion plus letter grades for the **ICM** and the **trophectoderm** — this chapter's first fate decision.

Grading is a **morphological proxy, not a measurement of chromosomal status**: a handsome blastocyst can be aneuploid (relaxed cleavage checkpoints permit errors) and an unremarkable embryo can implant. Hence morphology is combined with extended culture and, increasingly, genetic testing — while implantation rates still fall short of fertilisation rates.

### Stem cells and the ICM

**Embryonic stem cells (ESCs)** are derived from the ICM and are **pluripotent**: every body cell type, no placenta — a claim that rests on the potency ladder of [01 — Cell Theory and Cell Types](../02-cell-biology/01-cell-theory-and-cell-types.md). ESC-derived tissue is **not patient-matched**, so rejection is a problem, and deriving it destroys the blastocyst at the stage of the first fate decision, which is where the ethical debate attaches. **Induced pluripotent stem cells** bypass that objection by reprogramming adult cells back to pluripotency.

### Implantation failure: a major cause of infertility

Fertilisation rates in IVF are high; pregnancy rates are not, and much of the gap is **implantation failure**:

```
embryo reaches blastocyst
      ├──▶ aneuploidy (relaxed cleavage checkpoints / maternal meiosis)
      │        → development cannot continue
      ├──▶ failed zygotic genome activation → arrest before day 5
      ├──▶ failure to hatch from the zona pellucida
      └──▶ endometrium not receptive (progesterone timing off,
             thin lining, adhesions, tubal fluid)
                    ▼
        NO IMPLANTATION → negative test despite fertilisation
```

Infertility is therefore not only a gamete or tubal problem: **assessing receptivity and selecting blastocysts attack the two independent requirements** — a competent embryo on the right day, meeting a progesterone-primed lining.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Cleavage is just mitosis, so the embryo grows" | It is mitosis **without growth**: total volume stays at oocyte size while cell number rises and cell size halves. |
| "The morula is a ball of identical cells" | Compaction at the 8-cell stage separates outer from inner cells — different position, different signalling (Hippo/CDX2), different fate. |
| "The blastocoel forms because cells die or pull apart" | It is **pumped**: Na⁺/K⁺-ATPase drives Na⁺ in, water follows osmotically, tight junctions stop it leaking. |
| "ICM and trophoblast are both pluripotent" | ICM is **pluripotent**; trophoblast is extra-embryonic and lineage-restricted — the asymmetry is the first fate decision. |
| "The first fate decision is between body tissues" | It is **embryo versus placenta**, taken at the blastocyst stage, before implantation. |
| "The three germ layers have three different origins" | All three come from the **epiblast** via the primitive streak; the hypoblast makes only extra-embryonic endoderm. |
| "The pregnancy test detects progesterone" | It detects **hCG**, using two antibodies against the β subunit in a sandwich assay. |
| "The corpus luteum maintains itself until the placenta takes over" | It would degenerate by ~day 10 without **hCG**, which rescues it and sustains progesterone. |
| "Cleavage checkpoints are as strict as in adult cells" | Damage and G1 checkpoints are **relaxed** for speed, so errors slip through → mosaicism; the **spindle checkpoint still holds**. |
| "Teratogen risk is constant all pregnancy" | Structural risk peaks in **organogenesis (weeks 3–8)**; earlier it is all-or-nothing, later mainly **functional**. |

## Key facts

- **Cleavage = rapid mitosis without growth**: cell number doubles each round, cell size halves, total volume stays constant until the blastocyst.
- Early divisions run on **maternal mRNA and protein stockpiled during oogenesis**; **zygotic genome activation** (minor wave at the first cleavages, major wave at the 4–8-cell stage) hands control to the embryo — failure arrests it there.
- Cleavage cycles are S and M with little growth phase; **damage checkpoints are relaxed but the spindle checkpoint still operates**, which is why mosaicism and aneuploidy are common.
- **Compaction** (8-cell stage) is **E-cadherin**-mediated; outer cells polarise and form tight junctions, inner cells are buried — position is information.
- **Cavitation**: Na⁺/K⁺-ATPase pumps Na⁺ into the cavity, water follows by osmosis through aquaporins, tight junctions seal it → **blastocoel**.
- The **blastocyst** has **ICM (pluripotent → embryo proper)** and **trophoblast (extra-embryonic → embryonic placenta)** — the **first cell fate decision**.
- **Implantation**: trophoblast → **cytotrophoblast** (progenitor) + **syncytiotrophoblast** (multinucleated, protease-secreting, invasive); the endometrium must be **progesterone-primed**.
- **hCG from the trophoblast rescues the corpus luteum** → progesterone maintained → no menstruation → basis of the **pregnancy test** (β-hCG sandwich assay).
- **Gastrulation**: epiblast → primitive streak → **ingression after EMT** → **ectoderm, mesoderm, endoderm**; pluripotency collapses into three restricted sheets.
- **Ectoderm** → skin surface and entire nervous system (+ neural crest); **mesoderm** → muscle, bone, blood, dermis, kidneys, cavity linings; **endoderm** → gut tube lining and its organs.
- **Neurulation**: notochord induces neural plate → groove → tube (closure days 21–28); failure = neural tube defects, reduced by folate.
- **Hox genes** show **collinearity** — gene order along the chromosome mirrors expression along the anterior–posterior axis.

## Practice questions

**1. The best explanation for why cleavage divisions occur without any increase in embryo volume is that**

A. the zona pellucida inhibits protein synthesis in blastomeres
B. it spends only stored maternal supplies and must stay small for tube passage and exchange, so cell size falls as cell number rises
C. cleavage is meiotic, so no new cytoplasm can be made
D. the embryonic genome is active from fertilisation and simply chooses not to grow

**Answer: B**

Explanation: There is no nutritional supply before implantation and no growth phase, so each division partitions a fixed oocytoplasmic volume. Small blastomeres keep the surface-area-to-volume ratio high and let the embryo reach the uterus in time. Cleavage is mitotic (C) and the genome is silent until ZGA (D).

---

**2. Fluid first appears in the blastocoel because**

A. cells in the centre of the morula undergo apoptosis
B. the zona pellucida is digested from within
C. accumulated protein passively draws water through the bilayer without any pump
D. Na⁺/K⁺-ATPase pumps sodium in, water follows osmotically through aquaporins, and tight junctions prevent leak-back

**Answer: D**

Explanation: Cavitation is active and energy-dependent — the pump builds the sodium gradient, water follows down it, and the tight junctions from compaction seal the epithelium. The cavity is not made by cell death (A) or hatching (B), and passive diffusion cannot hold a gradient (C).

---

**3. The first cell fate decision separates cells that will form**

A. the inner cell mass (embryo proper) from the trophoblast (embryonic part of the placenta)
B. ectoderm from mesoderm
C. epiblast from hypoblast
D. muscle from nerve

**Answer: A**

Explanation: Compaction and Hippo/CDX2 signalling split the blastocyst into a pluripotent ICM and an extra-embryonic trophoblast — embryo versus support structure, decided before implantation. Ectoderm versus mesoderm is a gastrulation decision (B); epiblast/hypoblast is the later bilaminar stage (C); muscle and nerve are tissue-level outcomes (D).

---

**4. The primary physiological role of hCG secreted by the trophoblast is to**

A. stimulate uterine contractions to aid implantation
B. convert the proliferative endometrium into a secretory endometrium
C. act on the corpus luteum to prevent its regression so progesterone production continues
D. supply progesterone directly to the endometrium

**Answer: C**

Explanation: hCG is homologous to LH and binds LH receptors on the corpus luteum, rescuing it from degeneration so progesterone stays high and menstruation does not occur. Progesterone comes from the corpus luteum, not the trophoblast (B, D); contractions are not its function (A).

---

**5. A home urine pregnancy test shows a coloured test line when**

A. urinary progesterone binds a fixed antibody
B. hCG is bound at once by a mobile labelled anti-β-hCG antibody and a fixed capture antibody that traps the coloured particle
C. the α subunit shared with LH, FSH and TSH is detected
D. urine pH changes the colour of an embedded indicator

**Answer: B**

Explanation: It is a sandwich immunoassay — two antibodies against the hCG β subunit must bind the same molecule, localising the coloured conjugate at the test line. The β subunit is targeted because the α subunit is shared with other hormones (C); progesterone and pH are not measured (A, D).

---

**6. Which statement about the origin of the three germ layers is correct?**

A. Ectoderm comes from the hypoblast and endoderm from the epiblast
B. Each germ layer arises from a separate fertilisation event
C. The hypoblast gives rise to the definitive gut lining
D. All three derive from the epiblast — cells ingressing through the primitive streak form mesoderm and endoderm, those staying above form ectoderm

**Answer: D**

Explanation: The epiblast is the sole source of the embryo; the hypoblast contributes only extra-embryonic endoderm (A, C). There is one embryo with one streak, so layers cannot come from separate events (B).

---

**7. Which of the following is derived from mesoderm?**

A. The lining of the trachea
B. The dermis of the skin
C. The epidermis
D. Peripheral nerve sheath cells from the neural crest

**Answer: B**

Explanation: Mesoderm forms the middle-layer derivatives — muscle, bone, cartilage, blood, dermis, kidneys and cavity linings. Tracheal lining is endodermal (A), epidermis ectodermal (C), and neural crest cells ectodermal (D).

---

**8. The notochord is important early in development because it**

A. secretes factors that induce the overlying ectoderm to form the neural plate, which folds into the neural tube
B. becomes the vertebral column directly
C. produces the trophoblast that invades the endometrium
D. generates the definitive endoderm of the gut

**Answer: A**

Explanation: The notochord is an inducing centre — its signals (SHH, BMP antagonists) specify the neural plate, which closes into brain and spinal cord; failure of closure gives neural tube defects. Vertebrae form from sclerotome mesoderm around it (B); trophoblast and endoderm have other origins (C, D).

---

**9. A teratogenic drug is taken at 6 weeks of gestation rather than 14 weeks. Compared with the later exposure, the earlier one is**

A. more likely to cause major structural malformations, the later exposure mainly risking functional or growth effects
B. less harmful because organogenesis has not started
C. equally likely to cause major structural malformations
D. harmless, because the embryo is protected before week 8

**Answer: A**

Explanation: Organogenesis runs from about weeks 3–8, so exposure then can disrupt structures still being built; by 14 weeks the organs exist and residual risk is largely functional — both windows are dangerous, but the type of damage differs.

---

**10. An embryo in IVF culture divides normally to the 4-cell stage and then arrests. Which explanation best fits?**

A. E-cadherin expression failed, since compaction always precedes the 4-cell stage
B. The spindle checkpoint failed to arrest the cells
C. Aquaporins were absent, so no blastocoel could form
D. Zygotic genome activation failed — maternal stores were exhausted before the embryonic genome took over

**Answer: D**

Explanation: The major wave of zygotic genome activation occurs at the 4- to 8-cell stage, so arrest there is the classic signature of failed maternal-to-embryonic handover. Compaction begins at the 8-cell stage (A), checkpoint failure causes errors rather than arrest (B), and cavitation failure would arrest later (C).
