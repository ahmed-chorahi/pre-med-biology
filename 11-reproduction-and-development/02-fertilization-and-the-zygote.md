# Fertilization and the Zygote

## Why it matters

[12 — Meiosis](../03-cellular-processes/12-meiosis.md) ends with a problem it deliberately creates: **every gamete carries only one chromosome of each homologous pair** — a human sperm or oocyte has 23 chromosomes, a *half-genome*. That is excellent for shuffling and useless as a body plan — a haploid cell cannot carry the gene dosage a human needs. **Fertilisation converts two half-genomes back into one diploid genome** in a single cell: the zygote, the only cell ever both formed by fusion and required to divide into everything else.

If two haploid cells must fuse, the cell must guarantee that **exactly two** fuse — not zero, not three. Fertilisation is therefore two engineering problems solved at the membrane, the compartment of [01 — Membrane structure](../03-cellular-processes/01-membrane-structure-and-fluid-mosaic.md):

| Hard problem | Why it is hard | Solution | Timescale |
| --- | --- | --- | --- |
| **Finding and penetrating the egg** | The egg is buried in follicular cells and a glycoprotein shell | **Capacitation** (membrane reorganisation in the female tract) → **acrosome reaction** (enzymatic digestion) → **specific membrane fusion** | Hours; minutes for the acrosome reaction |
| **Blocking polyspermy** | Dozens of other sperm are already attached when the first one fuses | **Fast block** (depolarisation) + **slow block** (cortical reaction → impenetrable zona pellucida) | ~1 minute; then minutes to permanent |

Three ideas organise what follows. First, **fertilisation is a membrane event before it is a genetic event** — receptor binding, vesicle fusion, ion flux and exocytosis do the work. Second, **the two blocks to polyspermy are a belt-and-braces pair**: one fast and temporary, one slow and permanent. Third, **the outcome is genetic uniqueness as well as restored chromosome number** — a third source of variation beside independent assortment and crossing over.

## Journey, capacitation, and the fertile window

### Capacitation: the sperm must be reorganised before it can fertilise

Ejaculated sperm **cannot fertilise an egg**, even if placed directly on it. In the female tract they undergo **capacitation** — membrane and metabolic changes over several hours that make both the acrosome reaction and membrane fusion possible.

```
Sperm enter the female tract (cervix → uterus → fallopian tube)
        ↓
CHOLESTEROL and glycoprotein coat LOST from the sperm plasma membrane
        ↓
membrane fluidity INCREASES (same fluid–mosaic logic as
../03-cellular-processes/01-membrane-structure-and-fluid-mosaic.md)
        ↓
bicarbonate and Ca²⁺ enter; adenylyl cyclase → cAMP → protein kinase A
        ↓
METABOLIC ACTIVATION → HYPERACTIVATED, asymmetric flagellar beating
        ↓
membrane PRIMED: cholesterol-depleted, fusogenic, able to
respond to zona pellucida binding → SPERM IS FERTILISATION-COMPETENT
```

The central step is the **loss of cholesterol from the sperm plasma membrane**. Cholesterol buffers membranes into a liquid-ordered state; removing it raises fluidity, destabilises the bilayer locally and lets it bend and fuse — prerequisites for both acrosomal exocytosis and sperm–oocyte fusion. This is the reasoning of the fluid mosaic chapter: **you cannot fuse a membrane you cannot deform, and you cannot deform a membrane stiffened by cholesterol.**

Two consequences follow. Capacitated sperm show **hyperactivation** — a high-amplitude, asymmetric whip of the flagellum that drives them through cervical mucus and between the cells of the cumulus oophorus. And capacitation leaves the membrane *controlled-unstable*, so a sperm that lingers too long acrosomes prematurely: **the window of competence is narrow on both sides.**

### The arithmetic of the fertile window

Fertility arithmetic is nothing more than adding two survival windows.

| Gamete | Viable for | Where | Notes |
| --- | --- | --- | --- |
| **Sperm** | **~3–5 days** (up to ~7 in favourable mucus) | Cervix, uterus, fallopian tube | Must complete capacitation; function declines with time |
| **Egg (oocyte)** | **~12–24 hours after ovulation** | Fimbriated end of the fallopian tube | Fails rapidly if unfertilised |

```
fertile window ≈ sperm lifespan (≈5 days) + oocyte lifespan (≈1 day)
               ≈ 6 DAYS per cycle
        ↓
intercourse on day 9–14 of a 28-day cycle (ovulation ~day 14)
can yield fertilisation
        ↓
intercourse AFTER ovulation fails: the oocyte is already gone
intercourse MORE THAN ~5–6 DAYS before ovulation fails: sperm dead
```

The asymmetry is the point: **sperm survive several days, the egg survives less than one**, so the fertile window opens *before* ovulation and closes almost immediately after it. This is why "rhythm" or "safe period" contraception is unreliable — it assumes ovulation on day 14 of every cycle, when in fact the follicular phase is the variable one and the luteal phase is fixed.

## The acrosome reaction: opening a path through the coats

An ovulated oocyte is not naked — it is wrapped in layers, and each layer is an obstacle with a specific mechanism of its own.

| Layer | Composition | How it is crossed |
| --- | --- | --- |
| **Corona radiata** | Granulosa cells in a hyaluronic-acid matrix | **Hyaluronidase** dissolves the matrix; sperm push between the cells |
| **Zona pellucida (ZP)** | Three glycoproteins — **ZP1, ZP2, ZP3** — forming a mesh-like shell | **Species-specific binding to ZP3** triggers the acrosome reaction; **acrosin** and other proteases digest a path through |
| **Oolemma** | Fluid mosaic bilayer with species-specific surface proteins | **Direct membrane fusion** with the sperm equatorial segment |

### ZP3 binding and enzyme release

The **acrosome** is a single large secretory vesicle capping the sperm nucleus — structurally a **modified lysosome-like vesicle** full of hydrolytic enzymes and derived from Golgi apparatus (lysosomal hydrolases: [02 — Cell Biology](../02-cell-biology/01-cell-theory-and-cell-types.md)). It is useless until it discharges.

```
Capacitated sperm CONTACTS the zona pellucida
        ↓
sperm surface protein binds ZP3 — the SPECIES-SPECIFIC receptor
(one species' sperm cannot trigger the reaction on another's zona)
        ↓
ZP3 binding → Ca²⁺ influx into the sperm head
        ↓
ACROSOME REACTION: the acrosomal vesicle FUSES with the sperm
plasma membrane (exocytosis — the same SNARE-driven process used
by every secretory cell) → enzyme payload is released
        ↓
HYALURONIDASE degrades the hyaluronic acid of the corona radiata;
ACROSIN (serine protease) and other proteases digest the zona
        ↓
sperm reaches the OOCYTE PLASMA MEMBRANE and its equatorial
segment FUSES with the oolemma
```

The parallel to microbial invasion is deliberate: in [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md), **hyaluronidase is the classic "spreading factor"** and proteases open connective tissue so microbes can move through it. Fertilisation uses the same enzyme families for the same job — liquefy the ground substance, cut the protein mesh. The microbe spreads and damages; the sperm reaches one cell.

Two further marks deserve stating. Binding is **species-specific** — mouse ZP3 will not bind human sperm, so the cross-species barrier sits in the zona, before any fusion. And **only acrosome-reacted sperm can fuse with the oolemma**: the reaction is not merely a tunnel but a required membrane remodelling that exposes the fusion machinery.

## Sperm–egg membrane fusion: the moment of commitment

Penetration ends at the oolemma, where the final specificity step occurs. Fusion requires **complementary surface proteins** on both cells, and the pairing is well characterised: **Izumo1** on the sperm (named after a Japanese shrine where marriages are blessed) must engage **Juno** on the oocyte surface. Both are essential — knockouts of either cause infertility with normal gametes.

```
acrosome-reacted sperm equatorial segment touches the oolemma
        ↓
IZUMO1 (sperm) binds JUNO (egg surface receptor)
        ↓
membrane merger: outer leaflets join, then inner leaflets —
a fusion pore forms (fluid mosaic bilayers are fusogenic)
        ↓
sperm HEAD and CENTRIOLE are drawn into the oocyte cytoplasm
        ↓
oocyte ACTIVATED: Ca²⁺ oscillations begin → the blocks to
polyspermy start, and the second meiotic division is completed
```

Fusion triggers two things at once: **the oocyte completes meiosis II** (expelling the second polar body) and **the blocks to polyspermy begin**. The zygote must now stop every other sperm — and dozens may already be stuck to the zona.

## The blocks to polyspermy

Polyspermy — incorporation of more than one sperm — is not a harmless extra: it produces a **3n (or higher) egg** that cannot divide correctly. Two mechanisms prevent it, on different principles and timescales.

### Fast block: depolarisation of the oolemma

```
FIRST SPERM FUSES with the oocyte plasma membrane
        ↓
Na⁺ permeability rises → oocyte membrane DEPOLARISES
(inside becomes positive; about −70 mV to +10 mV in sea urchin)
        ↓
depolarisation MAINTAINED for roughly 1 MINUTE
        ↓
a depolarised membrane CANNOT SUPPORT FURTHER SPERM FUSION
→ later-arriving sperm are repelled at the membrane step
```

The fast block needs no synthesis and no vesicle traffic — it is a pure **electrical change**, and ions move in milliseconds. Its limitation is clear too: the depolarisation lasts about a minute, then the potential recovers, so it buys time rather than giving the permanent answer. In mammals its contribution is debated relative to the slow block, but it remains the cleanest example of **membrane potential acting as a cell-recognition signal**.

### Slow block: the cortical reaction

```
SPERM FUSION → oscillating rise in INTRACYTOPLASMIC Ca²⁺
        ↓
CORTICAL GRANULES (secretory vesicles docked just under the oolemma)
undergo EXOCYTOSIS — they discharge into the perivitelline space
        ↓
released enzymes (ovoperoxidase, proteases, glycosidases):
  • CLIP the zona pellucida glycoproteins — ZP3 is inactivated
    as a sperm receptor, ZP2 is modified
  • cross-link the ZP mesh → ZONA HARDENING
  • the perivitelline space SWELLS, lifting the zona off the oolemma
        ↓
ZONA PELLUCIDA BECOMES IMPENETRABLE TO SPERM
        ↓
PERMANENT — no new sperm can bind, digest, or fuse, ever
```

The slow block is a **vesicle-exocytosis event driven by a second-messenger calcium signal** — structurally identical to neurotransmitter release at a synapse, to histamine release from a mast cell, and to the acrosome reaction that got the first sperm in. The same machinery opens the door and slams it shut.

### Comparing the two blocks

| Feature | **Fast block** | **Slow block (cortical reaction)** |
| --- | --- | --- |
| Trigger | Sperm–oocyte membrane fusion | Rise in intracellular Ca²⁺ after fusion |
| Mechanism | Na⁺ entry → **depolarisation** of the oolemma | **Exocytosis of cortical granules** → enzymes modify the zona |
| Target | The oocyte plasma membrane itself | The **zona pellucida** and perivitelline space |
| Speed | Seconds; sustained **~1 minute** | Begins in minutes, complete in tens of minutes |
| Duration | **Transient** — the membrane repolarises | **Permanent** — the zona hardens irreversibly |
| Dominant in | Sea urchin and many non-mammalian eggs | **Mammals**, including humans |

### Why polyspermy matters clinically and developmentally

An egg fertilised by two sperm has **three haploid sets** (3n), and segregation assumes pairs (meiosis) or duplicates (mitosis) — never triples. The spindle of [10 — Cell cycle and checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) and [11 — Mitosis](../03-cellular-processes/11-mitosis-and-cytokinesis.md) cannot partition three copies evenly, so daughter cells are unbalanced, aneuploidy compounds each round, and cleavage or placental development fails. **Triploidy is one of the commonest chromosomal causes of early pregnancy loss** — the evolutionary reason the blocks exist.

## The zygote: one diploid genome

### Restoration of diploidy: two pronuclei

After entry the sperm nucleus decondenses (protamines replaced by histones), the oocyte completes meiosis II, and **two pronuclei** form — one maternal, one paternal — each with 23 chromosomes, each replicating its DNA. They do not fuse; they align, their envelopes break down at **syngamy**, and the chromosomes are captured on one spindle at the first mitotic division. The zygote is diploid **(2n = 46)** from that division, and its **first DNA replication precedes first mitosis** as in any somatic cell.

| Step | What happens | Why it matters |
| --- | --- | --- |
| Sperm entry | Paternal genome decondenses; protamines replaced by histones | Paternal DNA must be packaged to be replicated or transcribed |
| Completion of meiosis II | Second polar body expelled | The oocyte becomes a proper haploid with replicated chromatids |
| Pronuclear formation | Two nuclei, each replicating DNA | Both genomes replicate once before the first cleavage |
| **Syngamy** | Envelopes dissolve; chromosomes share one spindle | Diploidy restored — 46 chromosomes, one cell |
| First mitosis | Bipolar spindle with checkpoint control ([10 — Cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md)) | Two diploid cells → cleavage begins ([03 — Early development](03-early-development-and-cleavage.md)) |

### Genetic uniqueness: three independent sources

Sexually produced offspring are unique because **three separate mechanisms** contribute variation, and fertilisation supplies the third:

| Source | Stage | Mechanism |
| --- | --- | --- |
| **Independent assortment** | Meiosis I | Random orientation of homologous pairs at metaphase I → 2²³ ≈ 8.4 million gamete combinations per person |
| **Crossing over** | Meiosis I (pachytene) | Exchange between non-sister chromatids → recombinant chromosomes, breaking linkage |
| **Random fertilisation** | **Fertilisation** | Any of ~8.4 million maternal gametes meets any of ~8.4 million paternal gametes → ~70 × 10¹² possible zygotes per couple |

Random fertilisation multiplies the two meiotic outputs, which with [12 — Meiosis](../03-cellular-processes/12-meiosis.md) and [01 — Genes, alleles, genotype, phenotype](../04-genetics/01-genes-alleles-genotype-phenotype.md) makes two full siblings genomically identical vanishingly unlikely. Monozygotic twins are the exception, because uniqueness is a property of *zygote formation*, not *embryo splitting*.

### Sex determination and the 1:1 sex ratio

Sex in humans is **chromosomal**, and the arithmetic is trivially symmetric:

```
MOTHER (XX) → produces ONLY X-bearing oocytes (100%)
FATHER (XY) → produces X-bearing sperm (~50%) AND Y-bearing sperm (~50%)
        ↓
X egg + X sperm → XX  (female)
X egg + Y sperm → XY  (male)
        ↓
the ratio is fixed by the FATHER's gamete pool → ~1:1 AT CONCEPTION
```

The mother contributes an X in every case; **only the sperm determines the sex**, because only the sperm is dimorphic — a direct consequence of X/Y segregation during spermatogenesis ([01 — Spermatogenesis and oogenesis](01-spermatogenesis-and-oogenesis.md)). Later deviations in the sex ratio reflect differential survival, not biased fertilisation. The **SRY** gene on the Y chromosome switches the indifferent gonad to testis; without it an XX individual develops along the female pathway.

## Twinning

**Twins** are two embryos from one pregnancy, and the two categories have entirely different genetics.

| Feature | **Monozygotic (identical)** | **Dizygotic (fraternal)** |
| --- | --- | --- |
| Origin | **One** fertilised egg that **splits** into two embryos | **Two** eggs, each fertilised by a **different** sperm |
| Genotype | Essentially identical (minus post-zygotic mutation) | Share on average 50% of segregating alleles — like ordinary siblings |
| Sex | Always the same | Can differ |
| Frequency | Fairly constant worldwide (~3–4 per 1000 births) | Rises with maternal age, parity, family history, ancestry and fertility treatment |
| Membranes | Depend on **timing of the split** | Always **dichorionic, diamniotic** |

### Chorionicity depends on when the split happens

The extraembryonic membranes are specified early, so the timing of the split decides how many placentas and sacs result:

| Timing of split | Result | Chorionicity |
| --- | --- | --- |
| **Before day 4** (morula stage) | Two complete packages, each makes its own placenta and sac | **Dichorionic, diamniotic** — indistinguishable from dizygotic twins on ultrasound |
| **Day 4–8** (blastocyst stage) | Shared placenta, separate sacs | **Monochorionic, diamniotic** — the commonest monozygotic pattern |
| After day 8 | Shared sac; risk of conjoined twins if incomplete | Monochorionic, monoamniotic |

Determinants differ by type: **dizygotic** twinning tracks **ovulation rate** (maternal age, family history on the mother's side, higher parity, ancestry, ovulation induction and IVF), whereas **monozygotic** twinning is largely a **stochastic embryonic event** with a frequency constant worldwide. Hence **fertility treatment raises the twin rate by releasing more than one oocyte, not by making embryos split.**

## Implantation preview

The zygote's first week is a holding pattern while the genome takes over and the journey to the uterus completes; the full account belongs to [03 — Early development and cleavage](03-early-development-and-cleavage.md). The fertilisation-relevant handover is this:

```
zygote → cleavage → morula → BLASTOCYST (inner cell mass + trophoblast)
        ↓
blastocyst CONTACTS the endometrium at about DAY 6
        ↓
TROPHOBLAST secretes hCG (human chorionic gonadotrophin)
        ↓
hCG RESCUES the corpus luteum → it keeps producing PROGESTERONE
        ↓
progesterone maintains the endometrium (secretory phase) →
implantation proceeds, and the placenta later takes over steroidogenesis
```

**hCG is what pregnancy tests detect**, and it converts a cyclic endometrium into a maintained one. Until the placenta takes over steroidogenesis (around weeks 8–12) the pregnancy depends on the corpus luteum, and the corpus luteum depends on hCG — so loss of trophoblast function causes miscarriage. Details follow in [05 — Placenta and maternal–foetal exchange](05-placenta-and-maternal-fetal-exchange.md).

## Medical relevance

**IVF and ICSI bypass the steps described above.** In conventional **in vitro fertilisation**, capacitation is induced in culture medium (albumin-mediated cholesterol removal) and sperm must still bind ZP3, acrosome-react and fuse — so unexplained infertility can persist after oocyte retrieval. **Intracytoplasmic sperm injection (ICSI)** deposits a single sperm into the ooplasm with a micropipette, skipping binding, the acrosome reaction and fusion; it is the treatment of choice for severe male-factor infertility. The corollary: **ICSI bypasses natural selection barriers**, so karyotyping and genetic testing of the male are offered where the cause may be genetic.

**Zona manipulation.** Because the blastocyst must shed the zona pellucida to implant, embryologists use **assisted hatching** — mechanical, chemical (acid Tyrode's) or laser breach of the zona — especially for frozen–thawed embryos, and **zona drilling** to facilitate micromanipulation. It exists *because* the modified zona is impenetrable: you cannot let sperm through, but you must eventually let the blastocyst out.

**Contraception targets the fertilisation steps directly.**

| Method | Step targeted | Mechanism |
| --- | --- | --- |
| **Spermicides** (nonoxynol-9, surfactants) | Sperm viability before capacitation | Detergents disrupt the sperm plasma membrane — the same fluid-mosaic vulnerability |
| **Copper IUD** | Sperm transport and viability | Copper ions are toxic to sperm; the endometrium becomes a sterile inflammatory environment hostile to gametes and implantation |
| **Hormonal methods** | Ovulation | Suppress the LH surge — no oocyte, no fertilisation |
| **Barrier methods** | Physical access | Condom, diaphragm — the only methods that also block STI transmission |
| **Antisperm antibodies** | **ZP3 binding and the acrosome reaction** | IgA/IgG on sperm or in cervical mucus immobilises sperm and blocks receptor interaction (a rare *natural* infertility mechanism) |

**Ectopic implantation.** If the blastocyst implants outside the uterine cavity — most often the fallopian tube — the result is an **ectopic pregnancy**. The tube cannot stretch and rupture causes life-threatening haemorrhage, making it a leading cause of first-trimester maternal death. Risk factors include prior pelvic inflammatory disease, previous ectopic, tubal surgery and smoking. Because hCG is still produced, **any positive pregnancy test with pain or bleeding mandates ultrasound to confirm the location.**

**Embryo biopsy and preimplantation genetic testing.** At the blastocyst stage several cells can be removed from the **trophectoderm** (future placenta) without damaging the inner cell mass and tested by PCR or array for single-gene disorders, aneuploidy (PGT-A) or structural rearrangements (PGT-SR) before transfer — the clinical way to avoid passing on Mendelian conditions catalogued in [05 — Human inheritance patterns](../04-genetics/05-human-inheritance-patterns.md).

**When the blocks fail — rare but instructive.** Polyspermy is occasionally seen in human embryos produced in vitro, and triploid conceptions are a documented cause of miscarriage; conversely, **parthenogenesis** — activation of an oocyte with no sperm — is reported only extremely rarely (usually as diploid or haploid ovarian teratomas). Neither is a viable route to a human individual, but both show that **the oocyte already holds the machinery to activate and divide, and what a sperm contributes is not only chromosomes but the activating, block-triggering signal** — absent or excessive, development fails.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Ejaculated sperm can fertilise an egg" | They cannot. **Capacitation in the female tract is mandatory** — cholesterol loss, greater membrane fluidity, hyperactivation. Without it there is no acrosome reaction and no fusion. |
| "The acrosome is just a bag of poison" | It is a **modified lysosome-like vesicle** whose enzymes (acrosin, hyaluronidase) are released by **regulated exocytosis** after ZP3 binding — a secretory event, not lysis. |
| "Fast and slow blocks are two names for one thing" | **Fast block = Na⁺-driven depolarisation of the oolemma, ~1 minute, transient.** **Slow block = Ca²⁺-driven cortical granule exocytosis hardening the zona, permanent** — and it is "slow" only relative to ion flow, since it starts within minutes. |
| "Polyspermy would just make a stronger embryo" | A 3n egg **cannot segregate chromosomes correctly** at mitosis → unbalanced aneuploid cells → cleavage failure or early loss. Triploidy is a major cause of miscarriage. |
| "The two pronuclei fuse to form the zygote's nucleus" | They **break down (syngamy)** and their chromosomes are collected on one spindle; diploidy is restored at the **first mitosis**, not by pronuclear fusion. |
| "Twins are either identical or fraternal and that is all that matters" | For monozygotic twins, **chorionicity depends on when the split occurred** — before day 4 gives dichorionic, later gives monochorionic — and chorionicity, not zygosity, drives obstetric risk. |
| "Fertility drugs cause identical twins" | Fertility treatment mainly causes **dizygotic** twinning by releasing multiple oocytes; the monozygotic rate is nearly constant worldwide. |
| "The father's contribution decides the sex only sometimes" | It decides it **always** — the mother can only give an X, so an X- or Y-bearing sperm alone determines XX or XY, giving ~1:1 at conception. |
| "hCG comes from the endometrium" | **hCG is secreted by the trophoblast**; it maintains the corpus luteum so progesterone continues to support the endometrium until the placenta takes over. |
| "IVF means sperm must do everything naturally" | **ICSI** injects a single sperm past the zona and oolemma, bypassing binding, the acrosome reaction and fusion — which is why genetic testing of the male matters. |

## Key facts

- Fertilisation solves two hard problems — **penetrating the egg** and **blocking polyspermy** — and both are solved by membrane-level mechanisms: receptor binding, exocytosis, ion flux, and membrane fusion.
- **Capacitation** occurs in the female tract: **cholesterol leaves the sperm plasma membrane → fluidity rises → hyperactivation and fusion competence**; uncapacitated sperm cannot fertilise.
- **Fertile window arithmetic**: sperm survive **~3–5 days**, the oocyte **~12–24 hours** after ovulation → about **6 days, opening before ovulation** and closing soon after it.
- The **acrosome** is a **lysosome-like vesicle**; **species-specific ZP3** binding → Ca²⁺ entry → exocytosis of **acrosin** and **hyaluronidase** → a digested path through corona radiata and zona to the oolemma — the same strategy pathogens use to degrade tissue ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)).
- Fusion needs complementary proteins (**Izumo1** on sperm, **Juno** on the oocyte) and triggers both **completion of meiosis II** and the blocks to polyspermy.
- **Fast block**: sperm fusion → **Na⁺ entry → depolarisation of the oocyte membrane lasting ~1 minute** → no further sperm can fuse.
- **Slow block (cortical reaction)**: **Ca²⁺ rise → cortical granules exocytose → ZP proteins clipped, perivitelline space swells → zona pellucida becomes impenetrable — permanent**; polyspermy would give a lethal **3n egg**, which is why both blocks exist.
- The **zygote restores diploidy** via **two pronuclei → syngamy → first mitosis (2n = 46)**, DNA replicated once beforehand.
- Genetic uniqueness has **three sources**: independent assortment, crossing over, and **random fertilisation** — see [12 — Meiosis](../03-cellular-processes/12-meiosis.md) and [01 — Genes and alleles](../04-genetics/01-genes-alleles-genotype-phenotype.md).
- Sex ratio at conception is **~1:1**: the mother always gives an X, the father's sperm pool is 50% X / 50% Y.
- **Monozygotic twins**: one zygote splits (**dichorionic if before day 4**, monochorionic after); **dizygotic twins**: two oocytes, two sperm.
- **Implantation at day 6**: trophoblast secretes **hCG → corpus luteum rescued → progesterone maintains the endometrium** ([03 — Early development](03-early-development-and-cleavage.md)).

## Practice questions

**1. Which statement about capacitation is correct?**

A. It is the fusion of the acrosome with the sperm plasma membrane
B. It involves loss of cholesterol from the sperm membrane, increasing fluidity and rendering the sperm fertilisation-competent
C. It occurs in the testis during spermatogenesis
D. It is triggered by binding to ZP3 on the zona pellucida

**Answer: B**

Explanation: Capacitation occurs in the female tract, and its defining event is **cholesterol efflux from the sperm membrane**, which raises fluidity and permits both the acrosome reaction and fusion. A describes the acrosome reaction; C is false because ejaculated sperm are *not* competent; D triggers the acrosome reaction, which needs a capacitated sperm first.

---

**2. The species-specific trigger for the acrosome reaction is**

A. Hyaluronidase binding to the corona radiata
B. The glycoprotein ZP3 of the zona pellucida
C. Depolarisation of the oocyte membrane
D. Cortical granule contents

**Answer: B**

Explanation: Sperm bind **ZP3** through species-specific molecules, and that binding raises sperm Ca²⁺ and triggers acrosomal exocytosis — so cross-species fertilisation is blocked at the zona, before membrane contact. Hyaluronidase (A) is released *after* the reaction; C is the fast block; D acts after fusion.

---

**3. The enzymes released by the acrosome that digest a path through the coats are most comparable to**

A. Surface capsules that resist phagocytosis
B. Tissue-degrading microbial enzymes such as hyaluronidase and proteases used to spread through connective tissue
C. Exotoxins that act at a distance via A–B subunits
D. Superantigens that activate T cells polyclonally

**Answer: B**

Explanation: Acrosin and hyaluronidase do what microbial **hyaluronidase ("spreading factor") and collagenase** do — hydrolyse extracellular matrix so a cell can move through tissue ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)). A, C and D involve no matrix degradation.

---

**4. The fast block to polyspermy is produced by**

A. Enzymatic clipping of zona pellucida proteins
B. Na⁺ entry that depolarises the oocyte membrane for about one minute
C. Swelling of the perivitelline space
D. Secretion of hCG from the trophoblast

**Answer: B**

Explanation: Fusion of the first sperm raises oocyte permeability to **Na⁺**, depolarising it for roughly a minute, and a depolarised oolemma cannot support further fusion. A and C belong to the slow block; hCG (D) is a later implantation signal with no role in either block.

---

**5. Which correctly describes the slow block to polyspermy?**

A. It is transient and depends on sustained depolarisation
B. It requires cortical granule exocytosis triggered by Ca²⁺ and results in a permanently impenetrable zona pellucida
C. It acts by preventing sperm from completing capacitation
D. It operates only before the sperm reaches the zona pellucida

**Answer: B**

Explanation: The slow block is a **Ca²⁺-driven discharge of cortical granules** whose enzymes clip ZP proteins (inactivating ZP3), harden the zona and swell the perivitelline space — irreversible. A describes neither block; C happens in the female tract long before; D reverses the sequence.

---

**6. A triploid (3n) conceptus fails to develop properly mainly because**

A. It cannot replicate its DNA before the first division
B. Three homologues cannot be segregated evenly at mitosis, producing grossly unbalanced daughter cells
C. It lacks pronuclei entirely
D. It produces no hCG and therefore no progesterone support

**Answer: B**

Explanation: The spindle of [10 — Cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) partitions replicated chromosomes in a bipolar fashion; a third set creates unresolvable multiplicities and serial aneuploidy, so cleavage fails or the pregnancy is lost early — which is why the blocks exist. A, C and D are all normal or secondary events.

---

**7. Monozygotic twins that are dichorionic must have resulted from splitting**

A. After day 8 of development
B. Before day 4, at the morula stage
C. At the blastocyst stage, after day 4
D. During implantation, from a single trophectoderm

**Answer: B**

Explanation: Extraembryonic membranes are specified early, so a split **before day 4 (morula)** lets each half build its own trophoblast — **dichorionic, diamniotic**, indistinguishable on ultrasound from dizygotic twins. A split at day 4–8 gives monochorionic, diamniotic twins; later, monochorionic, monoamniotic.

---

**8. The hormonal chain that maintains the endometrium immediately after implantation is**

A. LH from the anterior pituitary → progesterone from the oocyte
B. hCG from the trophoblast → rescue of the corpus luteum → progesterone
C. FSH from the blastocyst → oestrogen from the myometrium
D. Progesterone from the trophoblast → hCG from the corpus luteum

**Answer: B**

Explanation: At about day 6 the trophoblast secretes **hCG**, which rescues the corpus luteum so it keeps producing **progesterone** and the secretory endometrium persists until the placenta takes over. D inverts the chain; A and C misidentify the source and signal.

---

**9. ICSI is required when binding, the acrosome reaction, and membrane fusion must be bypassed because**

A. The oocyte lacks a zona pellucida
B. Sperm cannot capacitate, bind ZP3, or fuse — as in severe male-factor infertility
C. The embryo must be tested for aneuploidy
D. The patient has an ectopic pregnancy

**Answer: B**

Explanation: **Intracytoplasmic sperm injection** deposits one sperm directly into the ooplasm, skipping capacitation, ZP3 binding, the acrosome reaction and oolemma fusion — exactly what severe male-factor infertility demands. Zona drilling and assisted hatching address the zona; PGT is a separate trophectoderm biopsy; D concerns implantation site.

---

**10. The primary sex ratio at conception is approximately 1:1 because**

A. The oocyte releases X and Y chromosomes in equal numbers
B. The father produces X- and Y-bearing sperm in equal proportions while the mother always contributes an X
C. Meiosis in the mother segregates the Y chromosome randomly
D. Hormonal selection favours X sperm in the fallopian tube

**Answer: B**

Explanation: Females are XX and make only X-bearing oocytes; males make roughly **50% X and 50% Y sperm** by segregation at meiosis, so the outcome is decided entirely at fertilisation. A and C are impossible, since the mother has no Y; D is not a recognised mechanism.
