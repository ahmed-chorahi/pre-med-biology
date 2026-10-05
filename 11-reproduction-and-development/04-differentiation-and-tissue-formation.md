# Differentiation and Tissue Formation

## Why it matters

You began as one cell. Its descendants now include a few hundred distinct cell types — a motor neuron a metre long, a hepatocyte, an erythrocyte that has ejected its own nucleus — and **not one possesses a gene the others lack**. The difference is *which genes are expressed, not which genes are possessed*. Establishing that difference stably and on schedule is **differentiation**; assembling the results into layers, tubes, and branching structures is **tissue formation**.

This chapter bridges two parts of the book you have built. [05 — Gene regulation](../05-molecular-biology/06-gene-regulation.md) gave you the mechanism of *which genes are on*; [09 — Four tissue types](../09-human-biology/01-four-tissue-types.md) gave you the four finished products. The material below connects them — how lineage restrictions are laid down in the first weeks, which germ layer each tissue descends from, and why no tissue builds an organ alone.

Development is where medicine watches a control system being installed: failed induction causes renal agenesis, conotruncal defects, and neural tube defects; the same programmes, reactivated, drive cancer invasion; and rewinding a differentiated cell to a stem cell now underpins therapy. **Developmental biology is gene regulation written in four dimensions.**

## The central principle: differential gene expression

**Differential gene expression** is the claim that two cells with identical genomes differ because they transcribe different subsets of that genome. It is not an approximation — it is the whole of cell identity, and the reason genotype sets potential while expression sets phenotype ([04 — Genes, alleles, genotype and phenotype](../04-genetics/01-genes-alleles-genotype-phenotype.md)).

```
SAME GENOME (every nucleated cell)
      │
      │  different TRANSCRIPTION FACTOR programmes
      │  different CHROMATIN accessibility
      ↓
DIFFERENT mRNA SET
      │
      ↓
DIFFERENT PROTEIN SET
      │
      ↓
DIFFERENT STRUCTURE + FUNCTION  =  cell type
      │
      │  the protein set maintains the programme
      ↓
STABLE IDENTITY, inherited at every mitosis
```

Three properties make this a developmental mechanism rather than a fleeting response:

| Property | Mechanism | Consequence |
| --- | --- | --- |
| **Combinatorial** | Each enhancer reads a *combination* of transcription factors, never one alone | ~1,500 human transcription factors generate hundreds of cell types |
| **Self-reinforcing** | Terminal factors maintain their own expression and shut down alternatives | Identity outlasts the original signal |
| **Mitotically heritable** | **DNMT1** copies methylation to the new strand; histone marks propagate to neighbouring nucleosomes | A liver cell's daughter is a liver cell |

### Epigenetic commitment: options close progressively

Differentiation is better modelled as a cell **losing options** than as a cell choosing a fate. Each division, each signal, and each transcription factor decision closes chromatin domains that had been available.

```
TOTIPOTENT blastomere          all lineages still available
      │  asymmetric division + signalling
      ↓
INNER CELL MASS / EPIBLAST     embryonic vs extraembryonic choice split off
      │  gastrulation: three germ layers specified
      ↓
GERM-LAYER committed cell      whole-body programmes excluded
      │  local induction from neighbours
      ↓
REGIONAL identity              e.g. forelimb vs hindlimb field
      │  terminal transcription factors switch on
      ↓
COMMITTED PROGENITOR           one lineage, still dividing
      │
      ↓
TERMINALLY DIFFERENTIATED      stable, often permanently post-mitotic
```

The molecular correlate is **progressive chromatin closure**: bivalent domains (H3K4me3 with H3K27me3, keeping embryonic genes *poised*) resolve to one state; CpG-island promoters acquire DNA methylation; heterochromatin spreads over genes inappropriate to the lineage. The logic matches X-inactivation in [05 — Gene regulation](../05-molecular-biology/06-gene-regulation.md): a choice is made once, then copied at every division. Germline and early embryonic cells are the exception — they **erase and rebuild** these marks, so the programme restarts each generation.

**Why commitment must hold:** if identity could drift, a hepatocyte would occasionally become something else and every tissue would lose its specialisation. Differentiation is not a state the cell is in; it is a state the cell *defends*.

## Potency: a shrinking set of possibilities

**Potency** is a statement about how many futures a cell still has — equivalently, how much of the genome remains available. It shrinks monotonically with development.

| Potency | What the cell can produce | Canonical examples | Clinical meaning |
| --- | --- | --- | --- |
| **Totipotent** | Every embryonic *and* extraembryonic cell — a whole organism plus placenta | The zygote; cleavage blastomeres through the **8-cell stage** | Can alone seed an entire pregnancy |
| **Pluripotent** | All body cell types of the embryo proper, **but no placenta** | Inner cell mass (ICM); **embryonic stem cells (ESCs)**; **induced pluripotent stem cells (iPSCs)** | Laboratory source of every body cell type; basis of organoids |
| **Multipotent** | One lineage family — many types, all related | **Haematopoietic stem cell**; mesenchymal stem cell; neural crest; gut crypt stem cell | The regenerative reservoir of adult tissues; transplantable |
| **Unipotent** | One cell type, but still able to divide | Satellite cell of skeletal muscle; committed erythroid progenitor | Local repair only |
| **Terminally differentiated** | Its own type; usually no division at all | Neuron, cardiomyocyte, surface keratinocyte | Loss is effectively permanent |

Two clarifications exams rely on:

- **Potency is not value.** A totipotent blastomere is *less committed*, not better, than a hepatocyte — options are traded for capability, exactly as in [01 — Cell theory and cell types](../02-cell-biology/01-cell-theory-and-cell-types.md).
- **The tested distinction is totipotent versus pluripotent: the placenta.** Totipotent gives embryo *and* placenta; pluripotent gives the embryo only. And adult stem cells are **multipotent, not pluripotent** — a haematopoietic stem cell never becomes a neuron in normal tissue.

### Evidence that potency is expression, not DNA content

| Experiment | Result | What it proved |
| --- | --- | --- |
| Differentiated nucleus into an enucleated frog egg (Gurdon) | Normal tadpoles | The committed nucleus still carries the whole genome |
| Nuclei up to the **8-cell stage** into enucleated eggs | Full mice | Totipotency extends to early blastomeres, then is lost |
| Somatic cell nuclear transfer — **Dolly the sheep** | Adult from an adult mammary nucleus | Mammalian differentiation is reversible genomewide |
| **Yamanaka factors** (Oct4, Sox2, Klf4, c-Myc) forced into a fibroblast | A pluripotent **iPSC** | Cell type is a rewritable expression pattern |

**Four transcription factors undo years of commitment without altering a DNA base** — identity is regulation, not sequence.

## Germ layers: mapping development onto the four tissues

**Gastrulation**, the central event of [03 — Early development and cleavage](03-early-development-and-cleavage.md), creates three **germ layers**; every tissue in [09 — Four tissue types](../09-human-biology/01-four-tissue-types.md) descends from one of them. This table ties section 11 to section 09.

| Germ layer | Derivatives | Notes and high-yield exceptions |
| --- | --- | --- |
| **Ectoderm** | **Surface epidermis** and its keratinised epithelium, hair, nails, glands, lens; **neuroectoderm → the entire nervous system**; **neural crest** | Neural crest, the *fourth germ layer*: peripheral neurons and Schwann glia, melanocytes, smooth muscle of large vessels, **much of the facial cartilage and bone**, tooth dentine, adrenal medulla |
| **Mesoderm** | **All connective tissue** — bone, cartilage, tendon, adipose, dermis — plus **all muscle**, blood and vessels, spleen, **kidneys and ureters**, gonads, adrenal cortex | Exception: connective tissue of the head is largely **neural crest**, hence ectodermal |
| **Endoderm** | Epithelium of the **gut tube and its derivatives**: intestinal and respiratory lining, **liver**, **pancreas**, **thyroid follicular cells**, bladder, thymus and parathyroid | Endoderm supplies the *epithelium*; the connective tissue and muscle of these organs are mesodermal |

### The high-yield generalisation

Students over-learn "ectoderm = outside, mesoderm = middle, endoderm = inside" and then fail the exceptions. Memorise this instead:

```
NERVOUS SYSTEM (CNS + PNS)   →  ECTODERM
                                 (neuroectoderm for CNS, neural crest for most of PNS)
CONNECTIVE TISSUE + MUSCLE   →  MESODERM
                                 (exception: craniofacial = NEURAL CREST)
EPITHELIUM                   →  ALL THREE, depending on location
```

**Epithelia arise from every germ layer.** Epidermis is ectodermal; gut lining, liver, and thyroid follicles are endodermal; kidney tubule and mesothelia are mesodermal. *Epithelial tissue* is therefore a **structural** category, not a **lineage** one — a histological label that deliberately crosses germ-layer boundaries.

The practical rule: given a tissue, ask first **whether it is epithelium**. If not, the answer is usually mesoderm or ectoderm; if so, you need the organ, not the tissue name. The same mapping explains tumours — melanoma comes from melanocytes (neural crest), but **carcinoma is defined by histology, not germ layer**.

## Induction: how one tissue instructs another

**Induction** is when one group of cells (**the inducer**, classically the gastrula *organiser* or the notochord) changes another's fate (**the responder**) through extracellular signals. The central point: **organs are reciprocal constructions, not self-assembling sheets** ([09 — Organs and organ systems](../09-human-biology/02-organs-and-organ-systems.md)) — no epithelium builds an organ alone, only in dialogue with the tissue beneath it.

### The universal arrow chain

```
SIGNAL MOLECULE secreted by the inducer
   (FGF, BMP, Shh, Wnt, retinoic acid — usually a GRADIENT)
        │
        ▼
RECEPTOR on the responder cell surface
        │
        ▼
INTRACELLULAR CASCADE (RTK / SMAD / GPCR / nuclear receptor)
        │
        ▼
TRANSCRIPTION FACTOR SWITCH — one programme off, another on
        │
        ├──▶ altered PROLIFERATION   (bud grows, growth zone advances)
        └──▶ altered DIFFERENTIATION (cell type specified)
        │
        ▼
RESPONDER SENDS A SIGNAL BACK  →  reciprocal induction
```

Gradients matter as much as the molecules: cells read **concentration**, so one morphogen specifies different fates at high, medium, and low dose — how a single field produces ordered structure along an axis without separate instructions for each position.

### Three canonical inductions

| Inducer | Responding tissue | Key signals | Outcome | If it fails |
| --- | --- | --- | --- | --- |
| **Notochord** (and the gastrula **organiser**) | Surface ectoderm | BMP antagonists **noggin, chordin, follistatin**; later **Shh** | Neural plate → folds → **neural tube** | **Anencephaly** (rostral), **spina bifida** (caudal) |
| **Ureteric bud ↔ metanephric mesenchyme** | Reciprocal, repeated | **GDNF → RET**; Wnt, FGF and BMP signals back | Bud branches; mesenchyme condenses into **nephrons** | **Renal agenesis** — no bud, no kidney |
| **Lateral plate mesoderm under surface ectoderm** | Limb field | **FGF10 → FGFR2b → FGF8** from the **apical ectodermal ridge (AER)**; **Shh** from the zone of polarising activity | AER maintains proximo-distal outgrowth; Shh sets digit pattern | Truncated, fused, or extra digits |

The notochord case shows the general motif. Ectoderm's *default* fate is neural; BMP would push it towards epidermis, so the inducer works by **inhibiting an inhibitor**. **Induction is often relief from a default rather than the imposition of a new instruction** — an uncommitted responder needs permission more than it needs orders.

### Branching morphogenesis: the epithelium–mesenchyme dialogue

Lungs, kidneys, mammary glands, and salivary glands grow by one shared logic: an epithelial bud pushes into the underlying **mesenchyme**, the mesenchyme decides where and whether it splits, and the epithelium in turn tells the mesenchyme to condense around it.

| Organ | Epithelial partner | Mesenchymal partner | Reciprocal signals | Result |
| --- | --- | --- | --- | --- |
| **Lung** | Bronchial epithelium | Splanchnic mesenchyme | **FGF10 → FGFR2b** drives outgrowth; **BMP4** restrains it and creates the gap between buds | ~23 generations of branching → ~480 million alveoli |
| **Kidney** | Ureteric bud | Metanephric mesenchyme | **GDNF → RET** repeatedly; **Wnt9b/Wnt4** back | Collecting system + nephrons |
| **Mammary gland** | Ductal epithelium | specialised stroma | FGF, HGF, stromal BMPs and Wnts | Ductal tree at puberty, remodelled in pregnancy |

**Interrupt the dialogue and the organ does not form.** No FGF10 → no lung branching; no GDNF/RET → no kidney. Induction failures are therefore *structural* birth defects: the cells were all present, but the conversation never happened.

## Apoptosis: form built by removal

Development does not only add cells. Some of the most recognisable structures in the body exist because cells were deliberately destroyed. **Apoptosis** — programmed cell death — is a construction tool, not a failure of construction; its molecular machinery is set out in [10 — Cell cycle and checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md).

```
DEVELOPMENTAL DEATH SIGNAL
   (BMP/Wnt members, Fas, TNF, or loss of a survival factor)
        │
        ▼
BCL-2 FAMILY BALANCE tips: BAX/BAK pore outweighs BCL-2/BCL-XL protection
        │
        ▼
MITOCHONDRIAL MEMBRANE PERMEABILISATION → cytochrome c released
        │
        ▼
APOPTOSOME (Apaf-1 + caspase-9) → executioner CASPASES 3 and 7
        │
        ├──▶ cytoskeletal collapse → cell SHRINKS and BLEBS
        ├──▶ DNA cut into nucleosomal fragments
        └──▶ phosphatidylserine flipped out → "eat me" signal
        │
        ▼
CLEAN REMOVAL BY PHAGOCYTES — no inflammation, no scar
```

| Sculpting event | Structure produced by removal | Consequence of failure |
| --- | --- | --- |
| Death of tissue **between the developing digits** | Free, separate fingers and toes | **Syndactyly** — webbed or fused digits |
| Death within the solid early gut tube and gland anlagen | **Hollow gut tube** and gland lumens | Persistent tissue plugs, atretic segments |
| Apoptosis during **neural tube closure** and of surplus neural crest | Closed brain and spinal cord; correctly sized PNS | Neural tube defects; overgrown crest derivatives |
| Involution of larval structures (tadpole tail) | Resorption of structures no longer needed | Retained larval or embryonic tissue |

The rule to carry into exams: **retained tissue after a developmental death programme equals webbed, fused, or plugged structures.** The mirror statement matters too — apoptosis that occurs when it should not produces atrophy, and apoptosis that *fails to occur* is an enabling step of cancer.

## Regeneration: which tissues can rebuild themselves

Regeneration is differentiation **restarted in the adult**, and it depends on whether a tissue retains a stem or progenitor population and whether its cells remain competent to divide. It is the practical payload of the labile/stable/permanent classification in [01 — Cell theory and cell types](../02-cell-biology/01-cell-theory-and-cell-types.md) and of the tissue properties reviewed in [09 — Four tissue types](../09-human-biology/01-four-tissue-types.md).

| Tissue | Regenerative source | Capacity | After serious injury |
| --- | --- | --- | --- |
| **Liver** | Mature **hepatocytes** re-enter the cycle; **oval cells** if that is blocked | Restores full mass from roughly a quarter of the organ | Excellent — but repeated injury replaces parenchyma with scar → cirrhosis |
| **Gut epithelium** | **Crypt stem cells (Lgr5+)** | Whole lining replaced about **every 5 days** | Very rapid; also why chemotherapy hits the gut hard |
| **Skin epidermis** | Basal-layer and hair-follicle stem cells | Days to weeks | Good superficially; deep wounds heal by **scar** |
| **Blood** | **Haematopoietic stem cell (HSC)** in marrow | Lifelong, ~10¹¹ cells per day | Fully replenishable — why HSC transplant works |
| **Skeletal muscle** | **Satellite cells** (unipotent) | Modest; limited by fibrosis | Small tears repair; major loss becomes connective tissue |
| **Neurons (CNS)** | Essentially **none** in adults (limited hippocampal/olfactory neurogenesis only) | — | **Stroke and spinal cord injury are permanent**; myelin inhibitors and glial scar add a second barrier |
| **Cardiac muscle** | Negligible (~1% turnover per year in youth, far less later) | — | **Myocardial infarction leaves a scar**, not new myocardium |

**Why the asymmetry exists:** neurons and cardiac myocytes are **permanent cells** — they exited the cell cycle irreversibly, dismantling the proliferative machinery and locking the exit epigenetically, and their tissues hold no amplifying progenitor pool. Everything else either never left the cycle (labile: gut, skin, marrow) or re-enters it on demand (stable: liver). **Same genome, different cell type, different regenerative capacity** — gene expression converted into a prognosis.

## Medical relevance

### Stem cells and transplantation

| Approach | Cells involved | Principle | Notes and limits |
| --- | --- | --- | --- |
| **HSC transplant (bone marrow transplant)** | Autologous or allogeneic | Replaces the *multipotent* stem cell behind every blood lineage — one cell rebuilds erythroid, myeloid, and lymphoid output | Conditioning first; allogeneic risk of **graft-versus-host disease**; HLA matching |
| **Embryonic stem cells** | Pluripotent cells from the ICM | Differentiate into any body cell type in culture | Ethical constraint (embryo destruction); teratoma risk |
| **iPSCs** | Adult somatic cell + reprogramming factors | Pluripotency without an embryo | Patient-matched; mechanism is gene regulation — see [05 — Gene regulation](../05-molecular-biology/06-gene-regulation.md) |

The transplant row is a potency question in disguise: **the breadth of a graft's effect equals the breadth of the donor cell's potency.** Replace the stem cell and every descendant lineage follows; replace a committed progenitor and one branch is fixed.

### Cancer: dedifferentiation and epithelial–mesenchymal transition

Cancer is a disease of **division**, but equally a disease of **differentiation**:

| Developmental concept | Normal role | Hijacked in cancer |
| --- | --- | --- |
| **Degree of differentiation** | Cells mature into a stable, specialised state | Well-differentiated tumours resemble their tissue of origin; **poorly differentiated (anaplastic)** ones have lost that programme and behave aggressively |
| **Epithelial–mesenchymal transition (EMT)** | Gastrulation, neural crest migration, wound closure | Carcinoma cells downregulate **E-cadherin**, lose polarity, gain motility, and **invade** |
| **Cancer stem cells** | Tissue stem cells self-renew and generate progeny | A slow-cycling, chemoresistant subpopulation regenerates the whole tumour |

EMT is driven by **SNAIL, SLUG, TWIST, and ZEB** — an embryonic tool, not a mutation invented by the tumour. At the distant site the reverse, **mesenchymal–epithelial transition (MET)**, rebuilds a glandular colony. **Metastasis is differentiation-state switching, not merely migration.**

### Birth defects from failed induction

| Defect | Failed step | Mechanism |
| --- | --- | --- |
| **Renal agenesis → Potter sequence** | Ureteric bud–mesenchyme induction | No GDNF/RET → no kidney → no foetal urine → **oligohydramnios** → lung hypoplasia, flattened face, club feet |
| **Conotruncal defects** (tetralogy of Fallot, persistent truncus) | **Neural crest** migration into the outflow tract | Crest fails to septate the truncus → overriding aorta, ventricular septal defect |
| **DiGeorge syndrome (22q11.2 deletion)** | Neural crest survival and migration | Thymic and parathyroid hypoplasia, conotruncal and facial abnormalities |
| **Anencephaly and spina bifida** | Neural plate induction or tube folding | Insufficient BMP antagonism, or failed folding and apoptosis → open neural tube |
| **Limb reduction defects** | AER and ZPA signalling | Disrupted FGF or Shh, or teratogens such as excess **retinoic acid** → truncated or mis-patterned limbs |

The classic chain: **foetal anuria → oligohydramnios → pulmonary hypoplasia** (Potter sequence). The primary fault was inductive — the kidney never received its instruction.

### Tissue engineering and organoids

- **Organoids**: ESCs, iPSCs, or adult stem cells grown in three dimensions on a matrix with a defined signal cocktail **self-organise into mini-organs** with correct germ-layer composition, polarity, and a lumen — intestinal, kidney, liver, and cerebral organoids exist. They work because the inductive signals normally supplied by a neighbour are supplied by the medium.
- **Tissue engineering**: scaffold + cells + mechanical and biochemical cues → living replacement. **Decellularised organs** retain the extracellular matrix's instructive architecture and are reseeded with the patient's own cells.
- **The vascularisation bottleneck**: anything thicker than ~100–200 µm needs a blood supply, so engineered tissue must be built around a preformed capillary bed or fed by host ingrowth.

### Wound healing and fibrosis: when repair overshoots

Healing re-uses developmental signals, and like any programme it can overshoot:

```
INJURY → clot + inflammatory cytokines (PDGF, TGF-β)
        → fibroblasts activated → MYOFIBROBLASTS (α-SMA positive)
        → deposit COLLAGEN and matrix, wound contracts
        ↓  normally: matrix remodelled, myofibroblasts undergo apoptosis
        ↓  if TGF-β signalling persists or injury repeats:
FIBROSIS — excessive, cross-linked collagen replaces functional tissue
        → cirrhosis, pulmonary fibrosis, keloid scars, renal scarring
```

**Fibrosis is not regeneration.** Architecture is not restored, only patched, so the organ loses function even though the wound is closed — repair substituted for induction. The infarcted heart shows both failures at once: cardiac muscle cannot regenerate, so the defect is filled by collagen scar.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Differentiation changes a cell's DNA" | It changes **expression, not sequence** — silencing, not deletion. Cloning and iPSC reprogramming both prove the full genome survives commitment. |
| "Totipotent and pluripotent mean the same" | Totipotent makes embryo **and placenta** (zygote to 8-cell stage); pluripotent makes the embryo only (ICM, ESCs, iPSCs). The placenta is the entire difference. |
| "Adult stem cells are pluripotent" | Adult stem cells are **multipotent** — restricted to one lineage family. A haematopoietic stem cell produces blood, never neurons. |
| "Epithelium is ectodermal, because epidermis is epithelial" | Epithelia arise from **all three germ layers**: epidermis (ectoderm), gut/liver/thyroid (endoderm), kidney tubule and mesothelium (mesoderm). *Epithelial* is a structural label, not a lineage. |
| "All connective tissue is mesodermal" | Almost all of it — but **craniofacial cartilage and much facial bone are neural crest**, hence ectodermal. |
| "Induction means the inducer donates cells to the responder" | Induction is **signalling, not transfer**. The responder changes its own gene expression; the notochord induces without becoming neural tissue. |
| "Induction always instructs a cell what to become" | Many inductions are **permissive**: they remove a default. Noggin and chordin block BMP so ectoderm does what it tends to do — become neural. |
| "Apoptosis during development is damage" | It is a **construction programme**: interdigital death makes separate digits, lumens are hollowed by death. Failure leaves retained tissue (syndactyly, neural tube defects). |
| "The liver regenerates by stem cells building new lobes" | Mostly **existing hepatocytes re-entering the cell cycle** — hypertrophy plus hyperplasia. Oval cells are recruited only when that route is blocked. |
| "Healing replaces the tissue that was lost" | Often it replaces it with **scar**: myofibroblasts and collagen under TGF-β. Repair ≠ regeneration, and the heart is the clearest example. |

## Key facts

- **Differentiation is which genes are expressed, not which genes are possessed** — same genome, different transcription factor programme, stable through mitotic inheritance.
- Commitment is **epigenetic**: DNMT1 copies methylation after replication, histone marks propagate, chromatin closes over inappropriate genes — a liver cell's daughter is a liver cell.
- Potency ladder: **totipotent** (zygote to 8-cell; embryo plus placenta) → **pluripotent** (ICM, ESCs, iPSCs; embryo only) → **multipotent** (HSC and other adult stem cells) → **unipotent** → terminally differentiated. Nuclear transfer, Dolly, and the **Yamanaka factors** show potency is expression, not sequence.
- **Ectoderm** → epidermis, the entire nervous system via neuroectoderm, and neural crest (peripheral neurons and glia, pigment cells, craniofacial cartilage, adrenal medulla).
- **Mesoderm** → all connective tissue and muscle, dermis, blood and vessels, kidneys — except head connective tissue, which is neural crest.
- **Endoderm** → epithelium of the gut tube and its derivatives: respiratory lining, liver, pancreas, thyroid follicles.
- **Epithelium crosses all three germ layers**; connective tissue and muscle are mesodermal; the nervous system is ectodermal — the generalisation that answers most germ-layer questions.
- **Induction** = signal gradient → receptor → cascade → transcription factor switch → proliferation or differentiation, usually with a reciprocal signal back; the notochord works by **inhibiting BMP**.
- **Branching morphogenesis** (lung, kidney, mammary gland) needs reciprocal epithelium–mesenchyme signalling — FGF10/FGFR2b, GDNF/RET — so no dialogue, no organ.
- **Apoptosis sculpts**: interdigital webbing removal, gut hollowing, neural tube closure, larval involution; failure retains tissue (syndactyly, spina bifida).
- Regeneration tracks stem cells and cycle competence: **liver, gut (~5 days), blood, skin** regenerate; **CNS neurons and cardiomyocytes do not**, so their injuries are permanent.
- Cancer reuses developmental machinery (**dedifferentiation, EMT/MET, cancer stem cells**); failed induction causes renal agenesis, conotruncal/DiGeorge and neural tube defects; healing overshoots into **fibrosis**.

## Practice questions

**1. A student claims that a neuron and a hepatocyte must carry different genomes because they perform such different functions. The correct response is**

A. Correct — neurons delete unused chromosomes during differentiation
B. Correct — somatic mutation during development creates tissue-specific DNA
C. Incorrect — both cells carry the same genome; they differ in which genes are expressed
D. Incorrect — neurons have extra DNA from gene duplication, hepatocytes do not

**Answer: C**

Explanation: Cell type is a pattern of gene expression, not a difference in DNA — genes are silenced, never deleted. That a differentiated nucleus can still build a whole organism proves the genome stayed intact.

---

**2. The key difference between a totipotent cell and a pluripotent cell is that only the totipotent cell can produce**

A. Neurons
B. Extraembryonic tissue such as placenta
C. Haematopoietic cells
D. Cells with a diploid genome

**Answer: B**

Explanation: Totipotent cells — zygote and blastomeres to the 8-cell stage — make embryo plus placenta; pluripotent cells (ICM, ESCs, iPSCs) make every body cell type but no extraembryonic tissue. Both are diploid and both can produce neurons and blood cells.

---

**3. Which of the following tissues is derived from mesoderm?**

A. Epidermis of the skin
B. Epithelial lining of the small intestine
C. Dermis of the skin
D. Brain and spinal cord

**Answer: C**

Explanation: The dermis is connective tissue, and connective tissue is mesodermal; epidermis and the whole CNS are ectodermal, and the gut lining is endodermal. The trap is treating skin as one lineage when its two layers differ.

---

**4. Much of the cartilage and bone of the face and skull is an exception to the rule that connective tissue is mesodermal because it derives from**

A. Endoderm of the pharyngeal arches
B. Mesoderm of the head somites
C. The notochord itself
D. Neural crest cells, which are ectodermal

**Answer: D**

Explanation: Neural crest migrates from the closing neural tube and forms much of the craniofacial skeleton — an ectodermal source of connective tissue. Pharyngeal arch epithelium is endodermal, and somitic mesoderm forms vertebrae and muscle, not most facial bone.

---

**5. During neural plate induction, the notochord works mainly by**

A. Secreting BMP antagonists such as noggin and chordin, relieving ectoderm's BMP-imposed epidermal default
B. Directly donating cells that become the neural plate
C. Activating Wnt signalling strongly enough to specify epidermis
D. Methylating the promoters of every ectodermal gene

**Answer: A**

Explanation: Under BMP signalling, ectoderm's default is epidermal; noggin and chordin from the notochord block BMP, so the default resolves to neural tissue — induction by removing an inhibitor, with the notochord not incorporated into what it induces.

---

**6. Branching morphogenesis of the lung depends on mesenchymal FGF10 acting on epithelial FGFR2b to drive budding, while BMP4**

A. Destroys the mesenchyme so the bud can advance
B. Restrains the epithelium and creates the gap between successive buds
C. Converts the epithelium into neural tissue
D. Has no role in lung development

**Answer: B**

Explanation: FGF10–FGFR2b drives budding, but unopposed FGF would give an unbranched tube; BMP4 antagonism positions each new bud, so the result is a branching tree. Induction is graded and reciprocal, not a single on-switch.

---

**7. A child is born with the second and third fingers joined by skin and muscle. The most likely developmental error is**

A. Excessive mesodermal proliferation of the dermis
B. Failure of the apical ectodermal ridge to form
C. Failure of the programmed cell death that normally removes the tissue between the digits
D. Duplication of the Shh signalling centre

**Answer: C**

Explanation: Interdigital tissue is normally eliminated by apoptosis under developmental death signals; if that step fails, the tissue persists and the digits stay fused (syndactyly). Failure of the AER would truncate the limb, and excess Shh typically produces extra or mis-patterned digits rather than simple webbing.

---

**8. After a major liver resection, the remaining liver regrows to its original mass principally by**

A. Mature hepatocytes re-entering the cell cycle
B. Transdifferentiation of endothelial cells into hepatocytes
C. Differentiation of haematopoietic stem cells into hepatocytes
D. New lobes forming from embryonic rests in the capsule

**Answer: A**

Explanation: Hepatocytes are stable (quiescent) cells that leave G₀ and re-enter the cycle on demand — mostly the existing cells proliferating, with oval progenitors recruited only if that route is blocked. That is why the liver restores full mass from about a quarter of the organ.

---

**9. Which event best explains how a carcinoma cell invades through the basement membrane and enters a blood vessel?**

A. Mesenchymal–epithelial transition with restored E-cadherin
B. Increased expression of cytokeratins and tight junctions
C. EMT driven by SNAIL, TWIST, and ZEB with loss of E-cadherin
D. Reprogramming to a pluripotent state by the Yamanaka factors

**Answer: C**

Explanation: EMT is the normal embryonic programme for migration, in which E-cadherin is repressed, polarity is lost, and motility is gained; carcinoma co-opts it for invasion and intravasation. MET then permits colonisation at the distant site, which is the reverse of the step described in A.

---

**10. Why does a myocardial infarction leave a permanent scar rather than new contractile muscle, while a liver resection heals with functional tissue?**

A. Cardiac muscle cells express a different genome than hepatocytes
B. Cardiomyocytes are permanent cells that cannot re-enter the cell cycle and the heart lacks an amplifying progenitor pool, whereas hepatocytes can re-enter the cycle
C. The liver is protected from apoptosis, so no tissue is ever lost
D. Cardiac tissue is ectodermal and therefore cannot regenerate

**Answer: B**

Explanation: Cardiomyocytes have irreversibly exited the cycle and the heart has no resident stem population able to replace them, so fibrosis fills the defect — repair without regeneration. Hepatocytes are stable cells that re-enter the cycle on demand, restoring function; both tissues carry the same genome.
