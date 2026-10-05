# Gene Regulation

## Why it matters

Every nucleated cell in your body carries the same genome, yet a hepatocyte and a motor neuron share almost nothing in their protein output. **Differential gene regulation is the mechanism of cell identity** — development, differentiation, immune responses, and metabolic adaptation are all changes in *which genes are on*, not changes in which genes exist.

Regulation is also where control fails in disease. **Cancer is best described as a disease of regulatory collapse**: the accelerators are stuck on, the brakes are gone, and the chromatin that kept dangerous genes silent is remodelled. Almost every chapter in this section has already pointed here — replication fidelity, cell-cycle checkpoints, transcription, and translation each feed a control layer that this chapter assembles into one system.

The design principle that unifies every level is simple: **the cell controls the abundance of a molecule by controlling every step at which that molecule's abundance can change** — chromatin, transcription, processing, export, stability, translation, and degradation.

## The levels of control

```
   DNA level        chromatin opening/closing, DNA methylation
        ↓
   TRANSCRIPTION    activators, repressors, enhancers, promoters      ← biggest lever
        ↓
   RNA PROCESSING   capping, splicing choice, polyadenylation, export
        ↓
   mRNA STABILITY   poly-A shortening, miRNA/RNAi targeting
        ↓
   TRANSLATION      initiation control, polysome recruitment
        ↓
   PROTEIN          folding, modification, targeted degradation
        ↓
   CELL RESPONSE    secretion, translocation (e.g. GLUT4), activity
```

**Not every gene uses every layer.** A transcription factor gene is usually controlled at the top; a storage protein like ferritin is controlled at the bottom (translation and stability); a hormone receptor sits in the middle. The art of regulation questions is identifying *which layer a given signal acts on*.

## Prokaryotic regulation: the operon

Bacteria organise functionally related genes into an **operon** — one promoter, one switch, a **polycistronic** mRNA, and coordinated output.

### The *lac* operon: negative control with positive override

```
   CAP site   PROMOTER   lacZ    lacY    lacA
      │          │       (β-gal) (permease) (transacetylase)
      ▼          ▼
   ┌─────────────────────────────────────────────
   │  no lactose:  REPRESSOR bound to OPERATOR → polymerase blocked
   │
   │  + lactose:   allolactose (inducer) binds repressor
   │               → repressor changes shape, leaves operator
   │               → transcription PERMITS (but slow without CAP)
   │
   │  + lactose AND low glucose: cAMP HIGH
   │               → cAMP binds CAP → CAP binds CAP site
   │               → STRONG transcription
   │
   └─ + lactose AND high glucose: cAMP low → CAP inactive → weak transcription
```

| Component | Type | Effect |
| --- | --- | --- |
| **Lac repressor (*lacI*)** | Negative regulator, **inducible** | Bound = OFF; allolactose removes it = ON |
| **Operator** | DNA site | Repressor docking point |
| **CAP–cAMP** | Positive regulator | Senses **energy status**: low glucose → high cAMP → boost transcription |

**The logic that examiners want:** the operon answers two questions at once — *is the substrate present?* (lactose → derepress) and *can the cell afford to burn it?* (glucose status → CAP). It is switched on only when both conditions are met. This is **negative inducible** control: a repressor is the default, and the inducer removes it.

### The *trp* operon: repressible control plus attenuation

```
   tryptophan ABUNDANT
        │
        ▼
   trp repressor + tryptophan (corepressor) → ACTIVE complex
        │
        ▼
   binds operator → transcription OFF          (tryptophan switches off its own synthesis)

   tryptophan SCARCE → repressor inactive → transcription ON
```

**Repressible vs inducible** is the cleanest distinction in prokaryotic regulation:

| | *lac* (inducible) | *trp* (repressible) |
| --- | --- | --- |
| **Default state** | OFF | ON |
| **Effector** | Inducer (allolactose) removes repressor | Corepressor (tryptophan) activates repressor |
| **Biological logic** | Catabolic pathway — make the enzyme only when the food exists | Biosynthetic pathway — make the enzyme only when the product is scarce |

**Attenuation** adds a second, faster layer: in the *trp* leader, ribosome speed through a short peptide determines which of two mutually exclusive hairpins forms. High tryptophan → ribosome translates leader rapidly → terminator hairpin → transcription aborts early. Low tryptophan → ribosome stalls at Trp codons → anti-terminator hairpin → full transcription. Termination is thereby tuned *after* initiation has begun — the mechanism summarised in [04 — Transcription](04-transcription.md).

## Eukaryotic regulation at the chromatin level

Eukaryotic DNA is packaged as **nucleosomes**: ~147 bp of DNA wound around an octamer of histones (two each of H2A, H2B, H3, H4) with **H1** linking neighbours.

```
   CLOSED (heterochromatin)          OPEN (euchromatin)
   DNA tightly wrapped               DNA accessible
   genes SILENT                      genes AVAILABLE for transcription
        ▲                                  ▲
   deacetylation,                       ACETATION (HATs),
   repressive methylation,              activating methylation,
   compaction                           remodelling complexes
```

| Modification | Enzyme (write) | Erase | Effect |
| --- | --- | --- | --- |
| **Histone acetylation** | **HATs** (histone acetyltransferases) | **HDACs** | Neutralises lysine charges → looser DNA–histone contact → **activation** |
| **Histone methylation** | HMTs | Demethylases | **Context-dependent**: H3K4me3 activation; **H3K9me3 and H3K27me3 repression** |
| **ATP-dependent remodelling** | SWI/SNF and relatives | — | Slides, ejects, or restructures nucleosomes to expose promoters |
| **DNA methylation** | **DNMTs** (5-methylcytosine at **CpG**) | TET enzymes (demethylation) | Usually **silencing**, especially at CpG-island promoters |

**Why acetylation works mechanically:** lysines on histone tails are positively charged and grip DNA's negative backbone. Acetyl groups neutralise that charge, weakening the grip. Deacetylation restores it. **The same gene can be switched on and off within minutes by adding or removing acetyl groups** — no new proteins required.

**DNA methylation is the durable mark.** CpG islands at promoters, when methylated, recruit methyl-CpG-binding proteins that bring in HDACs — **the two systems reinforce each other**: methylation recruits deacetylation, which compacts chromatin, which protects against remodelling.

## Cis-elements and transcription factors: the logic of switches

| Element | Position | Effect |
| --- | --- | --- |
| **Promoter** | Core, at the gene | basal transcription machinery docking site |
| **Enhancer** | Upstream, downstream, or far away (even on another chromosome) | **Activates**; works in either orientation; loops to contact the promoter |
| **Silencer** | Variable | **Represses**; bound by repressor proteins |
| **Insulator / boundary** (e.g. **CTCF** sites) | Between domains | Prevents an enhancer from acting on the wrong promoter; defines **topologically associating domains (TADs)** |

```
   ENHANCER ──┐
              │  DNA loops (mediator complex bridges)
              ▼
   ───── PROMOTER ── GENE ────
              ▲
   SILENCER ──┘   (opposing inputs decide the outcome)

   INSULATOR ──┤  blocks enhancer action beyond the boundary
```

**Combinatorial logic:** most promoters are not driven by one factor but by **combinations** — activators AND-bound (all required), OR-bound (any sufficient), and repressors that veto. This is how 1,500 human transcription factors generate the specificity of hundreds of cell types: *no gene reads a single switch; it reads a combination.*

## Post-transcriptional control

### mRNA stability and RNA interference

```
   Dicer chops dsRNA / pre-miRNA hairpin ──▶ ~21 nt duplex
                                                  │
                                                  ▼
                              ONE strand loaded into RISC (with Argonaute)
                                                  │
              ┌───────────────────────────────────┤
              ▼                                   ▼
   PERFECT complementarity              IMPERFECT complementarity (3′ UTR)
        → mRNA CLEAVAGE                      → TRANSLATIONAL REPRESSION
          and degradation                     + deadenylation → decay
```

- **miRNAs** are endogenous (~2000 in humans) and tune whole programmes: *let-7* suppresses developmental genes; **miR-21** is consistently upregulated in tumours.
- **siRNAs** are usually exogenous or experimental — the basis of **RNAi** technology and of the siRNA drug **patisiran**.
- RNAi is also a **defence**: plants and fungi use it to destroy viral genomes; *C. elegans* discovered it.

### Alternative splicing (recap)

Controlled inclusion or skipping of exons multiplies protein output per gene — see [04 — Transcription](04-transcription.md). Regulated splicing decisions are tissue-specific, and their disruption causes disease (spinal muscular atrophy is a splicing-quantity disorder — see [07 — Mutations](07-mutations.md)).

### Translational control

| Mechanism | Example |
| --- | --- |
| **4E-BP binding eIF4E** | Phosphorylation releases eIF4E → cap-dependent translation ON when growth signalling is active |
| **Iron response elements (IRE/IRP)** | Low iron → IRP binds the 5′ IRE of **ferritin** mRNA → translation blocked; low iron → IRP binds the 3′ IRE of **transferrin receptor** mRNA → stabilises it. One signal, two opposite outcomes |
| **uORFs** | Upstream open reading frames sequester ribosomes from the main ORF |
| **miRNA-mediated repression** | Silencing without destroying the message (above) |
| **Polysome recruitment** | Stored mRNAs in oocytes are translated only on fertilisation |

## From cell surface to nucleus: signal-dependent transcription

Most eukaryotic regulation is ultimately **extracellular signals converted into transcription factor activity**. The pattern:

```
   ligand binds receptor
        │
        ▼
   intracellular signalling cascade (kinases, second messengers)
        │
        ▼
   TRANSCRIPTION FACTOR PHOSPHORYLATED (or cleaved, or released from inhibitor)
        │
        ▼
   enters nucleus / binds DNA / changes partner
        │
        ▼
   target genes ON or OFF
```

**The insulin → GLUT4 story**, introduced in [02 — Passive transport](../03-cellular-processes/02-passive-transport.md), has both a fast and a slow arm:

| Arm | Mechanism | Timescale |
| --- | --- | --- |
| **Fast (post-translational)** | Insulin receptor → IRS → **PI3K/Akt** → GLUT4 vesicles translocate to membrane → glucose uptake ↑ | Minutes |
| **Slow (transcriptional)** | Akt and other kinases phosphorylate transcription factors (e.g. **SREBP**, **FOXO**) → metabolic gene programme changes | Hours |

**This is the generalisable point:** a single hormone acts at the protein level immediately and at the gene level slowly — and *both* are forms of gene regulation. Insulin resistance can fail at either arm.

Other canonical cascades, briefly:

| Pathway | Final transcription event |
| --- | --- |
| **JAK–STAT** | Cytokine receptor → JAK phosphorylates **STAT** → STAT dimerises, enters nucleus — direct and fast |
| **MAPK/ERK** | Growth factor → Ras → Raf → MEK → ERK → phosphorylates **Elk-1/CREB** |
| **cAMP–PKA** | GPCR → adenylyl cyclase → cAMP → PKA enters nucleus and phosphorylates **CREB**, which switches on CRE-containing genes |
| **Steroid/thyroid hormones** | Lipid-soluble → cross membrane → bind **nuclear receptors** that *are* transcription factors (oestrogen receptor, glucocorticoid receptor) |

**Steroid receptors deserve a note:** because the ligand itself enters the nucleus, there is no surface-receptor cascade — the hormone–receptor complex binds hormone response elements directly. It is why steroid effects are slow but long-lasting and why they are so often transcriptional.

## X-inactivation: regulation written large

In female mammals, one X chromosome per cell is condensed into a **Barr body** — a whole-chromosome silencing event directed by the **XIST** long non-coding RNA, which coats the chromosome to be inactivated and recruits silencing machinery.

- It is **developmental**: which X is chosen is random and then **clonally inherited** (all daughter cells keep the same choice).
- It is **epigenetic**: the DNA sequence is unchanged, and the choice is propagated through cell divisions.
- It produces **X-linked mosaicism** — the patchy expression of X-linked conditions, and the reason heterozygous carriers can be mildly affected.

The genetics of X-linked inheritance belong to [04 — Genetics](../04-genetics/); the mechanism belongs here.

## Epigenetics: heritable without changing the sequence

**Definition:** *a heritable change in gene expression that is not caused by a change in DNA sequence.*

```
   DNA methylation pattern ──DNMT1 (recognises hemimethylated CpG after replication)──▶ copied to new strand
   Histone modification marks ──propagated by "readers" that copy the mark onto neighbouring nucleosomes
   XIST coating ──maintained clonally through cell division
```

**Two kinds of inheritance:**

| Type | Example |
| --- | --- |
| **Mitotic (somatic)** | A liver cell's methylation pattern maintained through 100 divisions — cell memory |
| **Transgenerational** | Imprinted genes (parent-of-origin marks survive the erasure and re-establishment cycles of gametogenesis); possible environmental effects under active study |

**Imprinting** is the clearest case: **Prader–Willi syndrome** (paternal 15q11 deletion or maternal uniparental disomy) and **Angelman syndrome** (maternal *UBE3A* deletion or paternal uniparental disomy) are *the same chromosomal region* with opposite outcomes because **different genes are active depending on which parent contributed them**. The DNA is identical; the marks are not.

## Medical relevance

**Cancer as regulatory failure — the consolidated view:**

| Control layer | Failure in cancer | Example |
| --- | --- | --- |
| Chromatin | Silencing marks lost or wrongly placed | **DNMT3A** mutations in AML; **EZH2** (H3K27 methyltransferase) mutations |
| Transcription factors | Constitutively active or lost | *MYC* amplification; **p53** mutation ([10 — Cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md)) |
| Signal transduction | Receptor/kinase stuck on | *RAS* mutation; HER2 amplification |
| Post-transcriptional | miRNA programmes inverted | *let-7* lost, miR-21 gained |
| Chromosome-wide | XIST/TAD boundaries breached | CTCF site mutation → enhancer hijacking |
| Immortality | Telomerase reactivated | see [02 — DNA replication](02-dna-replication.md) |

**Epigenetic drugs are now standard care:**

| Drug | Class | Use |
| --- | --- | --- |
| **Azacitidine, decitabine** | DNMT inhibitors (hypomethylating agents) | Myelodysplastic syndromes, AML |
| **Vorinostat, romidepsin, belinostat** | **HDAC inhibitors** | Cutaneous T-cell lymphoma, peripheral T-cell lymphoma |
| **Tazemetostat** | EZH2 inhibitor | Epithelioid sarcoma, follicular lymphoma |

The rationale is precise: **reverse the aberrant silencing and let the cell's own differentiation programme resume** — re-expression of silenced tumour suppressors, of differentiation genes, and of endogenous retroviral elements that stimulate immunity.

**Fragile X syndrome** is the clearest single-gene epigenetic disease: CGG repeat expansion in the *FMR1* 5′ UTR → **hypermethylation of the promoter** → transcriptional silencing → absent FMRP protein → intellectual disability. Note the chain: a *genetic* change (repeat expansion) causes an *epigenetic* consequence (methylation) that causes a regulatory failure.

**Imprinting disorders** (Prader–Willi, Angelman, Beckwith–Wiedemann) show that some marks must survive the global erasure that occurs in gametes — a regulated exception to reprogramming.

**Toxins and pathogens act at these layers too:** diphtheria toxin blocks translation elongation (eEF-2), while *Helicobacter pylori* CagA and human papillomavirus E6/E7 hijack transcriptional and cell-cycle control — pathogens disrupt regulation before they disrupt structure.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "An inducible operon is normally ON" | **Inducible = normally OFF**, switched on by an inducer (*lac*). Repressible = normally ON, switched off by a corepressor (*trp*). |
| "Enhancers must be upstream of the gene" | They work **upstream, downstream, or thousands of base pairs away** — orientation and distance are flexible; looping brings them to the promoter. |
| "Acetylation and methylation always do the same thing" | **Acetylation almost always activates**; methylation is **context-dependent** — H3K4me3 activates, H3K9me3/H3K27me3 repress. |
| "Epigenetic means inherited from your grandparents" | Epigenetic = **heritable change in expression without sequence change** — it may be mitotic only. Transgenerational inheritance is a subset, not the definition. |
| "Gene regulation is only transcription" | It operates at chromatin, transcription, RNA processing, stability, translation, and protein fate — each is a distinct control layer. |
| "X-inactivation is genetic" | The choice is **epigenetic**; it does not alter DNA sequence and is reversible in the germline — though the *locus* is genetic. |
| "Repressors always block RNA polymerase directly" | Some bind the operator and block; others recruit chromatin modifiers or quench activators — the outcome is repression by different means. |

## Key facts

- **One genome, many cell types** — differential gene expression is the mechanism of differentiation; control operates at **chromatin → transcription → processing → stability → translation → protein fate**.
- *lac* operon = **negative inducible** (repressor default OFF; allolactose removes it) plus **positive CAP–cAMP** control by glucose level.
- *trp* operon = **negative repressible** (corepressor tryptophan activates the repressor) plus **attenuation**, which tunes termination based on ribosome speed.
- Chromatin: **nucleosomes** → **acetylation (HAT/HDAC) opens**, **H3K4me3 activates**, **H3K9/H3K27me3 repress**, **ATP-dependent remodellers** move nucleosomes.
- **DNA methylation at CpG islands** silences promoters; **DNMT1** copies the pattern to the new strand after replication — the maintenance mechanism of epigenetic memory.
- **Enhancers, silencers, insulators (CTCF)** and TADs set the regulatory domain; transcription factors act **combinatorially**.
- **miRNA/RISC** represses or cleaves target mRNAs; **alternative splicing** and **translational control** (IRE/IRP, 4E-BP) are additional layers.
- Signals reach genes via **kinase cascades that phosphorylate transcription factors** (insulin/Akt/FOXO, JAK–STAT, MAPK, CREB); steroid hormones bind **nuclear receptors** directly.
- **X-inactivation** is chromosomal epigenetics directed by **XIST**, clonally maintained → mosaicism.
- **Epigenetics** = heritable expression change without sequence change; **imprinting disorders** and **fragile X** are the classic human examples.
- **Cancer consolidates failures at every layer**; epigenetic drugs (DNMT and HDAC inhibitors) reverse aberrant silencing.

## Practice questions

**1. The *lac* operon is normally OFF and is switched on by the presence of lactose. This is called**

A. Negative repressible control
B. Positive inducible control
C. Negative inducible control
D. Constitutive expression

**Answer: C**

Explanation: A repressor protein keeps the operon off by default, and the inducer (allolactose) inactivates the repressor so transcription can begin — the definition of negative inducible control. *trp* is the repressible counterpart (A). CAP–cAMP is positive control, but the defining switch here is the repressor, not the activator (B), and the genes are clearly not always on (D).

---

**2. Tryptophan acts in the *trp* operon as**

A. An inducer that removes the repressor
B. A corepressor that activates the repressor
C. A substrate that inhibits RNA polymerase directly
D. An activator that binds the operator

**Answer: B**

Explanation: Tryptophan binds the trp repressor and completes its DNA-binding shape, so the complex sits on the operator and shuts transcription — the pathway switches off when its product is plentiful. This is repressible, negative control. An inducer removes a repressor (*lac*, A); tryptophan does not act on polymerase (C) or act as an activator (D).

---

**3. Histone acetylation is associated with gene activation because it**

A. Adds a phosphate to DNA
B. Neutralises positive charges on histone tails, loosening DNA–histone contacts
C. Methylates CpG islands
D. Removes nucleosomes permanently

**Answer: B**

Explanation: Lysine residues on histone tails carry positive charges that grip the DNA backbone; acetyl groups neutralise them, weakening the interaction and opening chromatin to transcription factors and polymerase. HATs write the mark and HDACs remove it — a rapidly reversible switch. DNA methylation (C) generally silences; phosphorylation (A) is not the activating tail mark in question; remodelling can move nucleosomes but acetylation alone does not eject them permanently (D).

---

**4. Which statement about enhancers is correct?**

A. They must lie immediately upstream of the promoter
B. They function only in the orientation in which they were discovered
C. They can act at a distance and in either orientation by looping to contact the promoter
D. They are transcribed into mRNA

**Answer: C**

Explanation: Enhancers may be upstream, downstream, or tens of kilobases away, work flipped, and still drive transcription — DNA loops so the bound activators contact the general machinery via mediator. They are DNA regulatory elements, not transcribed units (D), and both position and orientation independence define them (A, B).

---

**5. Insulin increases glucose uptake in muscle within minutes by stimulating GLUT4 vesicle translocation. This is an example of**

A. Transcriptional regulation of the GLUT4 gene
B. Post-translational regulation acting on pre-existing GLUT4 protein
C. Alternative splicing of the insulin receptor
D. RNA interference

**Answer: B**

Explanation: The rapid arm of insulin action repositions GLUT4-containing vesicles already present in the cell — a signalling-cascade effect on existing protein, not new gene expression. Insulin *also* alters transcription over hours, but the minutes-timescale effect described is post-translational. Nothing in this step involves splicing (C) or miRNA (D), and it does not require making more GLUT4 mRNA (A).

---

**6. Which pair correctly matches a histone modification with its typical effect?**

A. H3K4 trimethylation — repression
B. H3K27 trimethylation — activation
C. H3K9 trimethylation — repression; acetylation — activation
D. Acetylation — tighter DNA binding

**Answer: C**

Explanation: H3K9me3 and H3K27me3 are the classic repressive marks (recruiting HP1 or Polycomb machinery), while acetylation loosens chromatin and activates. H3K4me3 is an *activating* mark (A is reversed), H3K27me3 is repressive (B is reversed), and acetylation weakens rather than tightens histone–DNA contacts (D).

---

**7. Fragile X syndrome results from a CGG repeat expansion because**

A. The repeat directly changes the amino acid sequence of FMRP
B. The expansion leads to promoter hypermethylation and transcriptional silencing of *FMR1*
C. The repeat is spliced out and the mRNA is degraded by RNAi
D. The repeat activates an enhancer

**Answer: B**

Explanation: Beyond ~200 repeats the CpG-rich region becomes methylated, chromatin condenses, and *FMR1* transcription stops — so FMRP, an RNA-binding protein needed for synaptic plasticity, is not made. It is the textbook case of a genetic change causing an *epigenetic* silencing event. The repeat lies in the 5′ UTR, so it does not alter the coding sequence (A), and splicing/RNAi are not the mechanism (C).

---

**8. Prader–Willi and Angelman syndromes involve the same chromosomal region but differ because**

A. Different genes are deleted in each
B. The region is imprinted — different parental alleles are active, so loss of the paternal versus maternal contribution has opposite effects
C. One is caused by a point mutation and the other by a trinucleotide repeat
D. One affects the X chromosome

**Answer: B**

Explanation: Genes in 15q11–q13 are imprinted: the paternal copy of some genes and the maternal copy of others are active. Losing the active paternal contribution gives Prader–Willi; losing the active maternal *UBE3A* gives Angelman. The DNA region is the same — the epigenetic marks differ, which is why imprinting disorders are the clearest demonstration that identical sequence can have different consequences depending on parent of origin.

---

**9. The clearest definition of an epigenetic change is**

A. Any mutation that does not change the amino acid
B. A heritable change in gene expression that occurs without a change in DNA sequence
C. A change that can never be reversed
D. A change caused only by environmental toxins

**Answer: B**

Explanation: Epigenetic marks — DNA methylation, histone modifications, chromatin states — alter expression and are propagated through cell division while the underlying sequence stays the same. They can be reversible (which is precisely why HDAC and DNMT inhibitors work), and they need not have any environmental cause (C, D). Silent mutations (A) are genetic, not epigenetic.

---

**10. Why is cancer properly described as a disease of gene regulation?**

A. Cancer cells have no mutations
B. Multiple regulatory layers fail — checkpoint control, transcription, chromatin, and telomere maintenance — so growth proceeds without permission
C. Only one gene ever needs to change
D. Cancer is exclusively caused by viral insertion into a promoter

**Answer: B**

Explanation: Malignancy requires accumulated failures: an activated oncogene, lost tumour-suppressor and checkpoint function (often p53), remodelling of chromatin, silencing of repair genes, and telomerase reactivation — regulatory collapses at every layer described in this chapter. Single mutations are tolerated (C) because controls are redundant; mutations are central (A); and although viruses contribute to some cancers (D), most are not virally driven.
