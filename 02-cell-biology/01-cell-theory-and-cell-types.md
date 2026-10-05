# Cell Theory and Cell Types

## Why it matters

Cell theory is the smallest set of claims in biology with the largest consequences. Everything downstream — why cells divide, why cancer is a disease of division, why an embryo can produce a whole organism from one cell, why antibiotics can target bacteria without harming you — follows from what cell theory says and from where it has exceptions.

[00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md) introduced the two cell plans. This chapter goes deeper on the theory itself: what it claims, what evidence supports it, where it breaks down, and what "cell type" actually means when one genome produces hundreds of different cells.

## What cell theory claims

The classical statements are three:

1. **All living things are composed of one or more cells.**
2. **The cell is the smallest unit that can be called alive.**
3. **All cells arise from pre-existing cells by division.**

A fourth, added later and often omitted:

4. **Cells of an organism carry the same genetic material** (with deliberate exceptions that this chapter covers).

The order matters. Statement 1 makes cells the *building blocks*. Statement 2 makes them the *unit of life* — the boundary below which the word "organism" stops applying. Statement 3 makes them *lineal*: every cell has a parent. Statement 4 explains how one fertilised egg becomes a brain cell and a liver cell without losing genes.

```
NON-LIVING CHEMISTRY
        │
        │  self-replicating molecules concentrate in a compartment
        ↓
   PROTOCELL              ← not yet a cell by statement 1
        │
        │  membranes, metabolism, division
        ↓
     CELL                 ← from here: cells only come from cells
        │
        ├── division ──────────────▶ more cells of the same kind
        │
        └── differential gene expression ──▶ specialised cell types
```

## The evidence

Cell theory was not asserted; it was assembled. Knowing which observation supported which statement makes the theory recallable instead of memorable.

| Observation | Who | What it established |
| --- | --- | --- |
| Cork tissue seen under a microscope, named "cells" | Hooke, 1665 | Statement 1 — organisms are built of small units |
| Living cells in pond water and in animal tissue | Leeuwenhoek, 1670s | Cells are alive, not just plant architecture |
| Cell theory for plants and animals | Schleiden & Schwann, 1838–39 | Statement 1 generalized across kingdoms |
| Cells seen dividing in observation | Purkinje, others | Statement 3, direct observation |
| "Omnis cellula e cellula" — every cell from a cell | Virchow, 1855 | Statement 3 made explicit |
| Germ cells (sperm, egg) identified as cells | 19th century | Continuity of the cell lineage across generations |

Two points are worth noting. First, **Schleiden's original formulation was partly wrong** — he proposed that new cells formed by crystallisation out of a "cellular juice." Schwann extended the theory before anyone had good evidence for statement 3. It took decades of direct observation of mitosis to fix. Second, **Virchow's dictum is the statement that made medicine cellular**: if every cell comes from a pre-existing cell, then a tumour is not a rogue substance but a lineage of cells that has stopped obeying the signals that normally stop division.

## Where cell theory needs qualification

A theory earns trust by surviving its exceptions. These are the ones that appear in exams and in clinical reasoning.

### Viruses are not cells

Viruses have genetic material and a protein coat, but **no ribosomes, no metabolism, and no independent reproduction.** They do not satisfy statement 2 — they are not alive on their own, and they reproduce only inside a host cell using that cell's machinery. This is why the entire antiviral strategy differs from the antibacterial one: antibacterial drugs attack structures the bacterium owns (wall, ribosome, gyrase), while antivirals mostly attack steps in the virus's use of *host* machinery or the virus's own enzymes.

### Some cells lack a nucleus — but are still cells

Mammalian red blood cells and platelets are not exceptions to cell theory; they are exceptions to statement 4's assumption of a complete genome.

| Cell | Lacks | Why | Consequence |
| --- | --- | --- | --- |
| **Mammalian erythrocyte** | Nucleus, mitochondria, most organelles | Ejected during maturation to maximise haemoglobin space | ~27 million O₂ molecules per cell; survives ~120 days; cannot repair itself |
| **Platelet** | Nucleus (a cell fragment, not a whole cell) | Packed from megakaryocyte cytoplasm | Acts for days, then consumed |
| **Skeletal muscle fibre** | Single nucleus per unit volume is insufficient — **multinucleate** | Fusion of many myoblasts into one syncytium | Long fibres can be controlled as one unit |
| **Striated muscle in some invertebrates** | Continuous cytoplasm with many nuclei — a **syncytium** | Developmental fusion | Coordinated contraction over distance |

The red blood cell case is the one to hold onto: it is a cell that has traded **self-maintenance for carrying capacity**, and the trade is only possible because a bone marrow stem cell is continuously making replacements. Loss of that source — aplastic anaemia — is fatal without transplant, precisely because the cell cannot repair itself.

### Syncytia and multinucleation

Where many cells fuse, the "one nucleus per cell" intuition fails. A single skeletal muscle fibre can be several centimetres long and contain hundreds of nuclei near its edge. The practical consequence: **damage to one part of the fibre is not automatically damage to the whole**, because local nuclei can transcribe repair proteins — but the shared cytoplasm also means that a poison entering anywhere reaches everywhere.

### Cells that are not part of an organism

Bacteria and archaea are cells; they are whole organisms. Cell theory statement 1 says living things are *composed of* cells, which is true of a bacterium too (a cell composed of itself). This is not a contradiction, but it is a reminder that **single-celled organisms satisfy every statement of cell theory while having no tissues, organs, or systems** — which is why so much of cell biology can be studied in bacteria, and why the shared machinery of all cells is the target of so many drugs.

## Modern additions to cell theory

The 19th-century statements are necessary but no longer complete. Four additions are standard:

| Addition | Claim | Why it matters |
| --- | --- | --- |
| **Energy transformation** | Cells capture, store, and spend energy | Distinguishes cells from crystals and from heat engines |
| **Homeostasis** | Cells maintain an internal environment | Connects cell biology to [09 — Homeostasis](../00-foundations/09-homeostasis.md) |
| **Reproduction by division** | Growth and repair are cell populations, not cell growth | Explains wound healing and cancer |
| **Heredity** | Cells pass DNA to descendants | Explains why mutations are inherited by cell lineages |

## What "cell type" means

A human body contains on the order of a few hundred distinct cell types — neurons, hepatocytes, podocytes, osteoclasts, platelets — **all carrying essentially the same DNA.** So cell type cannot be defined by genome. It is defined by three things:

```
SAME GENOME
     │
     │  which genes are expressed  ← gene regulation (05 — Molecular Biology)
     ↓
DIFFERENT PROTEIN SET
     │
     │  proteins determine structure and chemistry
     ↓
DIFFERENT SHAPE + DIFFERENT FUNCTION
     │
     │  the state is maintained by feedback
     ↓
STABLE CELL IDENTITY
```

**A cell type is a stable pattern of gene expression.** Two hepatocytes are the same type because they express the same set of genes at comparable levels; a hepatocyte and a neuron are different types because they do not. The genome is the catalogue; the cell type is what has been ordered from it.

### Common confusion: "differentiation changes the DNA?"

Differentiation does not delete genes. It silences most of them and keeps a subset active. The proof is that a differentiated cell still contains the instructions to make every protein it has switched off — and, as [05 — Molecular Biology](../05-molecular-biology/) will show, that fact is what makes cloning and induced pluripotent stem cells possible at all.

## Cell types by division behaviour

Not every cell type divides. This is one of the most clinically important classifications in the body, because **it predicts which tissues can heal and which cannot.**

| Category | Behaviour | Examples | Clinical meaning |
| --- | --- | --- | --- |
| **Labile (continuously dividing)** | Divide throughout life | Gut epithelium, skin epidermis, bone marrow, hair follicles | Rapid healing, but also the source of most cancers — division is frequent, so replication errors accumulate |
| **Stable (quiescent)** | Leave G₀ but re-enter on demand | Liver hepatocytes, kidney tubule, fibroblasts, lymphocytes | Excellent regeneration after injury; the liver can regrow from a fraction of its mass |
| **Permanent (terminally differentiated)** | Never re-enter the cell cycle | Neurons, cardiac myocytes, skeletal muscle fibres, lens fibres | Damage is largely permanent — stroke, myocardial infarction, and spinal cord injury are the practical consequences |

This table explains three facts students otherwise memorize separately: why the gut lining turns over every few days, why the liver regenerates after partial hepatectomy, and why a heart attack leaves a scar instead of new muscle. **Same genome, different cell type, different regenerative capacity.**

## Cell types by potency

Potency describes how many cell types a cell can still become. It is a statement about *how much of the genome remains available*, not about how important the cell is.

```
TOTIPOTENT          can make EVERYTHING, including placenta
    │               (zygote, early blastomeres)
    ↓
PLURIPOTENT         can make every body cell, but not placenta
    │               (embryonic stem cells, iPSCs)
    ↓
MULTIPOTENT         restricted to one lineage
    │               (adult stem cells: haematopoietic, mesenchymal)
    ↓
UNIPOTENT           one cell type only
    │
    ↓
TERMINALLY DIFFERENTIATED   the working cell of a tissue
```

| Term | Can produce | Canonical example |
| --- | --- | --- |
| **Totipotent** | All body cells **plus** extraembryonic tissue (placenta) | Zygote; cells of the 2-cell stage |
| **Pluripotent** | All body cell types, no placenta | Embryonic stem cells; induced pluripotent stem cells (iPSCs) |
| **Multipotent** | A family of related types | Haematopoietic stem cell → red cells, white cells, platelets |
| **Unipotent** | One type, but can still divide | Satellite cell of skeletal muscle |

Two clarifications students commonly need:

- **Potency is not maturity.** A totipotent cell is not "better" than a hepatocyte; it is *less committed*. The trade is exactly the one in the section on division: commitment produces capability.
- **Adult stem cells are not pluripotent in normal tissue.** A haematopoietic stem cell cannot become a neuron. Its output is restricted to the blood lineage. Widespread claims about adult stem cells repairing any tissue blur this boundary.

**Medical connection — why this is examined constantly.** iPSCs, discovered by Yamanaka, are differentiated cells reprogrammed back to pluripotency by forcing expression of four transcription factors. The mechanism — that a stable cell type can be reset without altering the genome — is a direct experimental proof that cell type equals gene expression pattern. Clinically, iPSCs sidestep the embryo-ethics problem and allow a patient's own cells to be turned into the cell type a disease has damaged. The whole concept depends on the definitions in this chapter.

## Cell types by shape and arrangement

Shape follows function, and the shape names are worth fixing early because histology and pathology use them constantly.

| Shape | Description | Where | Functional reason |
| --- | --- | --- | --- |
| **Squamous** | Flat, thin, tile-like | Alveoli, capillary endothelium, skin epidermis | Short diffusion distance |
| **Cuboidal** | Roughly cube-shaped | Kidney tubules, gland acini | Volume for secretion and transport proteins |
| **Columnar** | Tall | Gut lining | Tall cells pack organelles for absorption and secretion |
| **Polygonal** | Many-sided | Hepatocytes | Packing efficiency in a solid organ |
| **Spindle-shaped (fusiform)** | Tapered ends | Smooth muscle | Contraction along one axis |
| **Branched / stellate** | Many processes | Neurons, astrocytes | Connections over distance |
| **Irregular** | No fixed shape | Connective tissue cells, white cells | Amoeboid movement through tissue |

Arrangement matters as much as shape: **simple** (one layer) vs **stratified** (many layers) epithelium is a structure–function statement about whether the tissue is built for exchange or for protection.

## Cell specialization: the trade

Specialization is a bargain. A cell that does one job well gives up the ability to do everything else — including, in permanent cells, the ability to divide.

```
GENERALIST CELL                    SPECIALIST CELL
(small gene set on,                 (large gene set on for one job,
 weak at everything,                strong at that job,
 can divide, can become             cannot easily become
 anything)                          anything else)
```

The gain is **division of labour**, and it is the reason multicellular organisms can exceed the size and complexity limits that constrain every single-celled organism. The cost is **dependence**: a specialised cell cannot survive long without the system supplying it and removing its waste. A neuron outside blood flow dies in minutes. A hepatocyte in isolation loses its identity within days. **Multicellularity trades independence for capability**, and medicine is largely the study of what happens when that trade fails.

## How cells know they are in a tissue

A cell type is only stable in context. Three signals maintain identity:

| Signal | Mechanism | Failure example |
| --- | --- | --- |
| **Anchorage dependence** | Integrins bound to extracellular matrix transmit survival signals | Cell detached from matrix undergoes anoikis (detachment-induced apoptosis) |
| **Contact inhibition** | Neighbouring cells signalling "enough" via surface proteins | Lost in cancer cells — they pile up instead of stopping |
| **Soluble signals** | Growth factors, hormones at specific concentrations | Cells deprived of a required factor atrophy; excess factor drives division |

Anoikis deserves attention because its loss is a hallmark of malignancy: **cancer cells that lose anchorage dependence survive in the bloodstream**, which is a prerequisite for metastasis. The normal cell behaviour — "if you are not where you belong, die" — is a tumour-suppressing mechanism.

## Medical relevance

**Cancer is a disease of the cell theory statements.** Specifically:

| Cell theory element | What goes wrong in cancer |
| --- | --- |
| Cells arise from pre-existing cells | Cancer is clonal — every cancer cell descends from one abnormal ancestor |
| Normal cells stop dividing when contact-inhibited | Cancer cells ignore contact inhibition and growth signals |
| Stable cell identity | Dedifferentiation — cancer cells resemble less specialised ancestors |
| DNA is faithfully inherited | Mutations accumulate; genomic instability accelerates the process |

This is why oncology is taught as cell biology with the checkpoints removed: **tumour progression is the stepwise loss of the controls this chapter describes.**

**Regenerative medicine follows directly from potency.** If a cell type is defined by gene expression and not by an irreversible genome change, then a damaged cell type can in principle be replaced — by transplanting adult stem cells (multipotent, restricted), by using iPSC-derived cells (pluripotent, patient-matched), or by stimulating the tissue's own resident stem cells. Each approach is a different answer to the potency ladder.

**Differentiation is also how some diseases are diagnosed.** A tumour's *degree of differentiation* — how closely its cells resemble the normal cell type — is a major prognostic factor. Well-differentiated tumours behave more like their tissue of origin; poorly differentiated (anaplastic) ones have lost the gene expression pattern of their origin and typically behave more aggressively. The pathologist reading that report is judging how far a cell type has drifted.

## Key facts

- Cell theory: cells compose all life, the cell is the smallest unit of life, **all cells come from pre-existing cells**, and cells of an organism carry the same genetic material (with exceptions).
- **Viruses are not cells** — no ribosomes, no independent metabolism or reproduction.
- Mammalian red blood cells lose their nucleus to maximise haemoglobin capacity; they cannot repair themselves and must be continuously replaced from marrow.
- Multinucleate fibres and syncytia exist — "one nucleus per cell" is a rule, not a law.
- **Cell type = a stable pattern of gene expression from an unchanged genome.**
- Labile cells divide constantly (gut, marrow, skin); stable cells re-enter the cycle on demand (liver); **permanent cells never divide** (neurons, cardiac muscle) — which is why those injuries leave scars.
- Potency ladder: totipotent → pluripotent → multipotent → unipotent → terminally differentiated.
- Specialization trades independence for capability; specialised cells depend on the system supplying them.
- Loss of anchorage dependence, contact inhibition, and differentiation are the hallmarks of cancer.

## Practice questions

**1. Which observation most directly supported the statement "all cells arise from pre-existing cells"?**

A. Hooke's observation of cork cells
B. Schleiden's description of plant tissues as cellular
C. Repeated microscopic observation of cells undergoing division
D. Leeuwenhoek's observation of motile single-celled organisms

**Answer: C**

Explanation: Statement 3 is a claim about *origin*, and only direct observation of division demonstrates it. Hooke and Schleiden establish that organisms are built of cells (statement 1). Leeuwenhoek shows that single-celled organisms exist. None of those speak to where new cells come from — that required watching mitosis and, later, Virchow's explicit dictum.

---

**2. A medical student states that mammalian red blood cells contradict cell theory. Which response is correct?**

A. Correct — a cell without a nucleus cannot be a cell
B. Correct — cell theory requires every cell to have DNA
C. Incorrect — red blood cells are cells that have specialised by discarding organelles, and they are produced from nucleated precursors by division
D. Incorrect — red blood cells do have a nucleus, but it is invisible under a microscope

**Answer: C**

Explanation: Cell theory requires that living things be composed of cells and that cells come from cells — both hold, since erythrocytes are produced by division of nucleated marrow precursors. Statement 4 (same genetic material) is what they appear to violate, and the resolution is that they are a specialised, enucleated state rather than a contradiction of the theory. D is false; enucleation is real and the discarded nucleus is extruded during maturation.

---

**3. Which cell type is most likely to regenerate effectively after injury?**

A. Cardiac myocyte
B. Neuron
C. Hepatocyte
D. Lens fibre of the eye

**Answer: C**

Explanation: Hepatocytes are stable (quiescent) cells — they leave the cell cycle and re-enter it on demand, which is why the liver regenerates after partial hepatectomy. Neurons, cardiac myocytes, and lens fibres are permanently differentiated and do not re-enter the cell cycle, so their damage is largely irreversible. This is the labile/stable/permanent classification applied clinically.

---

**4. A cell is described as pluripotent. What can it produce?**

A. Every cell type including placental tissue
B. Every body cell type but not extraembryonic tissue
C. Only red blood cells and platelets
D. Only the cell type it already is

**Answer: B**

Explanation: Pluripotent means all body cell types are available but the extraembryonic lineages (placenta) are not — that distinction separates pluripotent from totipotent. The zygote is the standard totipotent example; haematopoietic stem cells are multipotent; a terminally differentiated cell can produce only its own type. The ladder is totipotent → pluripotent → multipotent → unipotent.

---

**5. Which statement best explains why two cells with identical genomes can behave completely differently?**

A. Each cell type has a different genome after differentiation
B. Gene expression differs — each cell type activates a different subset of genes
C. One cell has lost most of its DNA
D. The environment alone changes behaviour, with no contribution from the cell's own gene expression

**Answer: B**

Explanation: Cell type is a stable pattern of gene expression, not a difference in DNA content. Differentiation silences most genes and keeps a subset active, producing a different protein set and therefore a different structure and function. A is wrong because differentiation does not alter the genome; C confuses gene silencing with gene loss; D is wrong because the environment sets signals but the response depends on which genes the cell is equipped to read.

---

**6. A tumour is described as "poorly differentiated." What does this indicate about its cells?**

A. They have stopped dividing
B. They resemble their normal cell of origin less, having lost much of its gene expression pattern
C. They are stem cells
D. They contain more DNA than normal cells

**Answer: B**

Explanation: Differentiation is the acquisition of a tissue-specific gene expression pattern. Poor differentiation (anaplasia) means the tumour cells have drifted from that pattern — a sign that the normal controls on gene expression and cell identity have been lost, and typically a marker of more aggressive behaviour. Poorly differentiated tumours are not quiescent (A) and are not necessarily stem cells (C).

---

**7. What is lost when a cancer cell loses contact inhibition?**

A. The ability to undergo apoptosis
B. The ability to stop dividing when crowded by neighbouring cells
C. The requirement for a blood supply
D. Its genome

**Answer: B**

Explanation: Contact inhibition is the signalling that halts division when cells are packed against neighbours — normal epithelium grows to a monolayer and stops. Cancer cells ignore it, so they pile up and form masses. They still require a blood supply beyond a small size (which is why angiogenesis is needed for tumours beyond ~1–2 mm) and they still have a genome, even if it is mutated.

---

**8. Which combination correctly matches a cell shape with its functional advantage?**

A. Squamous epithelium — short diffusion path
B. Columnar epithelium — maximises surface area for a thin barrier
C. Cuboidal epithelium — forms the protective outer layer of skin
D. Neurons — allow rapid bulk flow of fluid

**Answer: A**

Explanation: Flat, thin squamous cells minimise diffusion distance, which is exactly why they line the alveoli and capillaries. Columnar cells are tall and packed with organelles for absorption and secretion, not thin barriers; stratified squamous epithelium (not cuboidal) forms the protective skin layer; neurons transmit signals electrically rather than moving bulk fluid.

---

**9. A cell is detached from the extracellular matrix and survives. What normal mechanism has it escaped?**

A. Osmosis
B. Anoikis — detachment-induced apoptosis
C. Facilitated diffusion
D. Phagocytosis

**Answer: B**

Explanation: Normal cells require integrin-mediated attachment to matrix to receive survival signals; without it they undergo anoikis, a programmed death. Cancer cells that lose this dependence can survive detached in the bloodstream — a prerequisite for metastasis. The other options are transport processes unrelated to attachment.

---

**10. Why is Yamanaka's reprogramming of adult cells to pluripotency considered a proof of the gene-expression model of cell type?**

A. It showed that adult cells can be fused with embryos
B. It changed only gene expression, leaving the genome intact, and the cell's identity was reset
C. It proved that adult cells never lose their DNA
D. It converted cells by changing their environment only

**Answer: B**

Explanation: Reprogramming forces expression of a small set of transcription factors, and the differentiated cell returns to a pluripotent state — without any change to its DNA sequence. If cell type were encoded in the genome itself, forcing a few genes could not undo it. The result therefore demonstrates that cell type is a maintained pattern of gene expression, reversible by changing that pattern.
