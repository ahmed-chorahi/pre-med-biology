# Mitosis and Cytokinesis

## Why it matters

The cell cycle's M phase has two jobs: **separate the copied chromosomes exactly evenly** (mitosis) and **split the cytoplasm** (cytokinesis). Both jobs are executed by the cytoskeleton — the machinery from [05 — Structure and movement](../02-cell-biology/05-structure-and-movement.md) — recruited into the most precise physical task a cell performs.

"Exactly evenly" is the whole point. A daughter cell with an extra chromosome or a missing one is usually dead, and if it survives it is a step toward cancer or a spontaneous miscarriage. **The machinery's error rate is among the lowest of any cellular process**, and the checkpoint from the previous chapter stands behind it.

## Mitosis: nuclear division

Five stages. The names are descriptive — learn what *changes* in each rather than the label alone.

```
INTERPHASE          nucleus intact, chromatin decondensed, DNA replicated
    │
    ▼
PROPHASE            chromosomes condense (visible sister chromatids joined at centromere)
    │               spindle begins to form; centrosomes move apart
    ▼
PROMETAPHASE        nuclear envelope BREAKS DOWN; microtubules capture kinetochores
    │
    ▼
METAPHASE           chromosomes align at the METAPHASE PLATE (equator)
    │               spindle checkpoint waits until every kinetochore is attached
    ▼
ANAPHASE            SISTER CHROMATIDS SEPARATE and move to opposite poles
    │
    ▼
TELOPHASE           chromosomes arrive; nuclear envelopes REFORM; chromatin decondenses
    │
    ▼
CYTOKINESIS         cytoplasm divides → two daughter cells
```

### Prophase — condensing and assembling

- **Chromatin condenses** via **condensin** into the familiar chromosome shapes. Condensation is essential: an unwound chromatin fibre would **tangle** when pulled apart. This is packaging as a mechanical requirement, not a cosmetic one.
- Each chromosome is **two identical sister chromatids** joined at the **centromere** — joined by **cohesin** rings.
- The two centrosomes (duplicated in S/G2) migrate to opposite poles, **nucleating the spindle**.

### Prometaphase — the envelope goes, the capture begins

- **Nuclear envelope breaks down** (lamina phosphorylated and disassembled — the lamin machinery from 02 — Cell Biology, dismantled on cue).
- Microtubules from each pole now access the chromosomes.
- Each centromere has a **kinetochore** — a multi-layer protein structure that **captures microtubules**.
- Chromosomes are pulled and jostled until **bi-oriented**: one kinetochore attached to one pole, the sister's to the other.

### Metaphase — alignment and the checkpoint

Chromosomes sit at the **metaphase plate**, held in a tense equilibrium between the two poles' pulls.

**This is where the spindle checkpoint operates** (chapter 10): the cell will not proceed until **every** chromosome is bi-oriented. The reason alignment is stable: **equal and opposite tension** from both poles. Attachment without tension (both kinetochores to one pole) is detected and corrected — error correction by **Aurora B kinase**, which detaches wrongly attached microtubules.

### Anaphase — the irreversible moment

**Two distinct events, separated by timing:**

| | **Anaphase A** | **Anaphase B** |
| --- | --- | --- |
| Event | Chromatids move **toward poles** | Poles move **farther apart** |
| Mechanism | Kinetochore microtubules **shorten** (depolymerise at the kinetochore) | **Polar microtubules slide** — kinesin motors push them apart; dynein at poles |
| Result | Chromatids delivered | Spindle elongates |

**The trigger:** the anaphase-promoting complex (APC/C) — released from checkpoint inhibition — **ubiquitinates securin**, which is destroyed, releasing **separase**, which **cleaves the cohesin rings** holding the sister chromatids together.

```
checkpoint satisfied
   → APC/C active
     → securin destroyed
       → separase free
         → COHESIN CLEAVED
           → sisters separate → ANAPHASE
```

**One proteolytic cut, and the anaphase is irreversible.** Because the trigger is *destruction* of an inhibitor, the transition cannot be reversed — the cycle's directionality, like cyclin destruction in chapter 10, is enforced by making steps **one-way through proteolysis**.

**Separation is driven from the kinetochore, not by pulling chromatids apart from behind:** depolymerising microtubules at the kinetochore generate force (the "pac-man" model) while the poleward flux of tubulin also shortens them. The chromatids are *released* by cohesin cleavage and *guided* by the spindle.

### Telophase — rebuilding

- Chromatids arrive and decondense (condensin removed).
- **Nuclear envelope reassembles** from ER membranes around the two chromosome masses — lamins dephosphorylated and repolymerised.
- Nucleoli reappear (rRNA genes active again).
- The spindle disassembles.

Two nuclei now exist inside one cell — which is why cytokinesis is not optional.

## Cytokinesis — splitting the cytoplasm

Different machinery in animals and plants, dictated by whether there is a wall to build.

### Animal cells: the contractile ring

```
        position specified by the SPINDLE (central spindle + astral signals)
                         │
                         ▼
        ACTIN + MYOSIN II form a RING at the cell equator
                         │
                         ▼
        myosin contracts → ring tightens → CLEAVAGE FURROW deepens
                         │
                         ▼
        abscission → two separate cells
```

- The **position is not guessed**: signals from the central spindle and astral microtubules mark the equator, so the cut happens **exactly between the two nuclei**.
- The machinery is **actin–myosin II** — the same contractile system as muscle, deployed as a purse string.
- Failure of positioning = **binucleate cell** (two nuclei, one cytoplasm) — a common feature of cancer cells, and a route to aneuploidy.

### Plant cells: the cell plate

```
Golgi-derived vesicles carried along MICROTUBULES to the centre
        → align at the equator → fuse → CELL PLATE grows OUTWARD
        → vesicles' contents become the new CELL WALL
        → plate reaches the parent wall → two cells separated
```

**Direction of growth is the deep difference:** animal cytokinesis **pinches inward** from the outside; plant cytokinesis **builds outward** from the inside — because the rigid wall cannot be pinched. The vesicle traffic runs on microtubule tracks (chapter 05), delivered by motors, fusing by SNAREs (chapter 03 of this section / 02 — Cell Biology).

### What if cytokinesis fails?

The cell becomes **binucleate**. Binucleate cells can later attempt division with a doubled centrosome number → **multipolar spindles** → unequal chromosome distribution → **aneuploidy**. Failure of cytokinesis is therefore not benign — it is one route by which genomic instability begins.

## The relationship to the spindle

Consolidating chapter 05's parts into their mitotic role:

| Structure | Composition | Role in mitosis |
| --- | --- | --- |
| **Kinetochore microtubules** | Dynamic, attached to kinetochores | Capture, align, and segregate chromosomes |
| **Polar (interpolar) microtubules** | Overlap at centre, pushed apart by kinesin | Elongate the spindle (anaphase B) |
| **Astral microtubules** | Radiate to cortex | Position the spindle; specify the cleavage plane |
| **Actin–myosin ring** | Cortical | Cytokinesis in animals |

**Dynamic instability is the working principle:** a growing microtubule *searches* the cytoplasm, and a kinetochore *captures* it when it hits — **search and capture**. Errors are corrected by tension-sensing enzymes. The system is stochastic at the level of individual attachments but deterministic in outcome because of correction plus checkpoint.

## Errors and their consequences

| Error | Result | Consequence |
| --- | --- | --- |
| **Nondisjunction** (chromatids or homologues fail to separate) | One cell with **n+1**, one with **n−1** | **Aneuploidy**; in meiosis → trisomy/monosomy (chapter 12) |
| **Multipolar spindle** (extra centrosomes) | Chromosomes split three or four ways | Severe aneuploidy — common in cancer |
| **Cytokinesis failure** | Binucleate cell | Route to multipolar division |
| **Spindle checkpoint failure** | Premature anaphase | Lagging chromosomes, micronuclei |
| **Chromosome breakage** | Fragments without kinetochores | Lost or unevenly inherited material |

**Aneuploidy is the currency of cancer genomics.** Tumour cells characteristically carry abnormal chromosome numbers — sometimes near-tetraploid — because checkpoint and centrosome controls failed. **Genomic instability is both a cause and an accelerator of malignancy**: more instability → more mutations → faster evolution of drug resistance.

## Medical relevance

**Antimitotic drugs** — the drug table from chapter 05, now in context: **vincristine, vinblastine, paclitaxel, colchicine** all arrest cells at the spindle checkpoint or during spindle function, and cells die in mitosis (mitotic catastrophe). Because they target division, their toxicity follows the labile-cell pattern: **marrow suppression, gut epithelial loss, alopecia** — and, notably, **neuropathy** for the vinca alkaloids, since neurons depend on axonal microtubule transport.

**Spindle poisons in anaesthesia:** colchicine's anti-inflammatory effect (gout) is neutrophil migration arrest, not mitosis — a reminder that a drug's clinical use and its molecular target are not always the obvious pairing.

**Fetal cells in maternal circulation** — trophoblasts shed during pregnancy cross into maternal blood and can be detected for **non-invasive prenatal testing**: a direct clinical application of the fact that dividing cells and their products enter the circulation.

**Binucleation and tumour grade:** pathologists note multinucleated giant cells in tumours — visible evidence of failed cytokinesis, used as a histological marker of abnormal division.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Sister chromatids are chromosomes" | Before anaphase, each duplicated structure = **2 chromatids = 1 chromosome**; after separation each chromatid is its own chromosome. Count centromeres. |
| "Mitosis is cell division" | Mitosis is **nuclear division**; cytokinesis is separate and not always successful. |
| "Chromosomes are pulled apart by something grabbing them from the pole" | Separation is triggered by **cohesin cleavage**; movement comes from **kinetochore microtubule dynamics** and motor proteins. |
| "Metaphase alignment is random" | It is tension-checked and corrected before the checkpoint releases anaphase. |
| "Plant cells pinch like animal cells" | Plants **build a plate outward** — no furrow is possible with a wall. |

## Key facts

- Stages: **prophase** (condensation via condensin, spindle forms) → **prometaphase** (envelope breaks, kinetochores captured) → **metaphase** (plate alignment, checkpoint) → **anaphase** (cohesin cleaved, chromatids separate; A = kinetochore shortening, B = poles slide apart) → **telophase** (envelopes reform, decondense).
- **Anaphase trigger: APC/C → securin destroyed → separase → cohesin cleaved** — irreversible because it is proteolytic.
- **Cytokinesis:** animal = **actin–myosin ring**, position set by spindle signals; plant = **cell plate grows outward** from Golgi vesicles on microtubules.
- Cytokinesis failure → binucleate cells → multipolar spindles → aneuploidy.
- **Search and capture** plus Aurora B error correction plus the spindle checkpoint guarantee even segregation.
- Errors (nondisjunction, extra centrosomes, checkpoint failure) produce aneuploidy — a hallmark and accelerator of cancer.
- Antimitotics (vincristine, taxol, colchicine) arrest mitosis; toxicity hits the fastest-dividing tissues and nerves.

## Practice questions

**1. During which stage do sister chromatids separate?**

A. Metaphase
B. Anaphase
C. Prophase
D. Telophase

**Answer: B**

Explanation: Anaphase begins when separase cleaves cohesin; the sisters, now independent chromosomes, move to opposite poles (anaphase A) while the spindle elongates (anaphase B). Metaphase holds them aligned; prophase makes them visible; telophase rebuilds nuclei around the arrived chromosomes.

---

**2. What triggers the onset of anaphase?**

A. Accumulation of cyclin D
B. Degradation of securin by the APC/C, releasing separase to cleave cohesin
C. Reformation of the nuclear envelope
D. Dephosphorylation of lamins

**Answer: B**

Explanation: Once the spindle checkpoint is satisfied, APC/C ubiquitinates securin; its destruction frees separase, which cuts the cohesin rings holding sisters together. The step is irreversible because it relies on proteolysis. Cyclin D acts at G1; envelope reformation and lamin dephosphorylation are telophase events.

---

**3. How does cytokinesis in an animal cell differ from that in a plant cell?**

A. Animal cells build a cell plate; plant cells form a furrow
B. Animal cells use an actin–myosin contractile ring to pinch inward; plant cells assemble a cell plate outward from Golgi-derived vesicles
C. Animal cells use microtubules exclusively; plant cells use only actin
D. There is no difference

**Answer: B**

Explanation: The animal cell's cortex contracts like a purse string, guided by signals from the spindle; the plant's rigid wall cannot be pinched, so vesicles carrying wall material are delivered along microtubules to the centre and fuse outward. Option A reverses the two; both cell types use both cytoskeletal systems in different roles.

---

**4. The kinetochore is best described as**

A. The site where the nuclear envelope reassembles
B. A protein structure at the centromere that captures spindle microtubules
C. The enzyme that condenses chromosomes
D. The microtubule-organising centre of the cell

**Answer: B**

Explanation: The kinetochore is the multi-layered plate assembled on centromeric DNA where microtubules attach and where depolymerisation generates poleward force. The centrosome is the MTOC (D); condensin does the condensing (C); the envelope reassembles at telophase (A).

---

**5. If the spindle checkpoint fails, the most likely consequence is**

A. Premature anaphase with missegregated chromosomes
B. Permanent arrest of the cell in G1
C. Failure of DNA replication
D. Increased apoptosis

**Answer: A**

Explanation: The checkpoint exists to delay anaphase until all chromosomes are properly attached; removing it releases the cell with lagging or unattached chromosomes, producing daughter cells with the wrong chromosome numbers. The checkpoint *prevents* death by ensuring accuracy; its failure causes aneuploidy, not arrest.

---

**6. Why must chromosomes condense before mitosis?**

A. Condensation activates their genes
B. Uncondensed chromatin would tangle when pulled apart; compact fibres segregate cleanly
C. Condensation doubles the DNA content
D. Condensation is required for transcription during division

**Answer: B**

Explanation: A mitotic cell must physically move long, thread-like DNA molecules to opposite poles without breaking or entangling them. Condensin compacts each chromosome into a discrete, manageable body — packaging as a mechanical necessity. Gene expression is *suspended* during mitosis (A, D wrong), and DNA content was already doubled in S phase (C).

---

**7. During anaphase B, spindle poles move apart because**

A. Chromatids drag them by direct attachment
B. Polar microtubules slide past one another, pushed by kinesin motors
C. The nuclear envelope pushes them
D. Actin filaments contract at the poles

**Answer: B**

Explanation: Interpolar (polar) microtubules overlap at the spindle centre; kinesin motors walk between them, sliding the antiparallel filaments and forcing the poles apart — while dynein at the cortex contributes. Anaphase A (sisters moving poleward) is separate and driven by kinetochore microtubule dynamics.

---

**8. A cell with two nuclei in one cytoplasm most likely experienced**

A. Failed DNA replication
B. Successful mitosis with failed cytokinesis
C. Meiosis without crossing over
D. Excessive nuclear envelope breakdown

**Answer: B**

Explanation: Nuclear division completed (two envelopes reformed) but the cytoplasm did not split — cytokinesis failure, usually from a defective contractile ring or positioning signal. Such binucleate cells often re-enter the cycle with extra centrosomes, producing multipolar spindles and the aneuploidy characteristic of tumours.

---

**9. Which structure determines the position of the cleavage furrow in an animal cell?**

A. The nucleolus
B. Signals from the central spindle and astral microtubules marking the cell equator
C. The Golgi apparatus
D. Random cortical contraction

**Answer: B**

Explanation: The spindle itself specifies where the ring forms — central spindle and astral microtubule signalling activates RhoA at the equator, assembling actin–myosin there. This guarantees the cut lies between the two new nuclei. Random or misplaced contraction (D) would risk severing a nucleus.

---

**10. Why are antimitotic cancer drugs particularly toxic to bone marrow and gut lining?**

A. Those tissues have the most DNA to replicate
B. Those tissues are labile — they divide continuously, so they encounter the spindle-poisoning drug far more often than permanent cells do
C. Marrow and gut express unique tubulin found nowhere else
D. The drugs are absorbed only in the gut

**Answer: B**

Explanation: Toxicity of phase-specific drugs tracks cycling frequency: labile tissues (marrow, intestinal epithelium, hair follicles) pass through mitosis constantly, so they are hit disproportionately; permanent cells (neurons, cardiac muscle) largely escape the mitotic effect — though neuropathy from vinca alkaloids occurs through a separate effect on axonal microtubule transport. Nothing unique about their tubulin or DNA amount explains it.
