# Mutations

## Why it matters

A mutation is a **change in the nucleotide sequence of DNA** — nothing more. Whether it destroys a protein, does nothing at all, or drives a leukaemia depends entirely on *where* it lands and *what kind* of change it is. That is why mutations sit at the centre of three different subjects at once: **genetics** (variation and inheritance), **molecular biology** (how sequence becomes protein), and **medicine** (cancer, inherited disease, drug response).

Mutations are also the raw material of [06 — Evolution](../06-evolution/) — without them there is no heritable variation for selection to act on. The same process that causes disease is the process that makes adaptation possible; only the outcome differs.

This chapter connects back to [02 — DNA replication](../05-molecular-biology/02-dna-replication.md), where the error rate is set and the repair systems are first implied, and forward to [04 — Genetics](../04-genetics/) and the cell-cycle chapter's account of cancer.

## Where mutations come from

### Endogenous sources

| Source | Mechanism | Frequency |
| --- | --- | --- |
| **Replication errors** | Mispairing despite proofreading and mismatch repair — a residual **~10⁻¹⁰ per bp per division** | Base-substitution background |
| **Spontaneous deamination** | Cytosine → **uracil**; 5-methylcytosine → **thymine** (the C→T "hotspot" at methylated CpGs) | Very common; handled by base excision repair |
| **Depurination** | Loss of a purine base → **AP site** | Thousands per cell per day |
| **Oxidative damage** | Reactive oxygen species modify bases (8-oxoguanine pairs with A) | Continuous, higher with inflammation and ageing |
| **Tautomeric shifts** | Rare forms of bases pair incorrectly during replication | Rare but real source of transitions |

```
   replication error surviving all three fidelity layers
              +
   spontaneous chemical damage not repaired
              +
   exogenous mutagen exposure
              ↓
        MUTATION FIXED IN DNA
              ↓
   ┌──────────┴──────────┐
   GERMLINE              SOMATIC
   (heritable)           (not inherited)
   → [04 — Genetics]     → mosaicism, cancer
```

### Exogenous mutagens

| Class | Agent | Lesion caused | Repair pathway needed |
| --- | --- | --- | --- |
| **Ultraviolet light** | Sunlight, tanning lamps | **Cyclobutane pyrimidine dimers** and 6–4 photoproducts between adjacent pyrimidines | **Nucleotide excision repair** |
| **Base analogues** | 5-bromouracil, 2-aminopurine | Incorporated during replication, then mispair → transition | Mismatch repair / BER |
| **Intercalating agents** | Ethidium bromide, acridine orange, aflatoxin metabolites (some) | Slide between base pairs → **insertion/deletion during replication** → frameshift | NER; sometimes error-prone bypass |
| **Alkylating agents** | Nitrogen mustards, ethyl methanesulfonate, nitrosoguanidine; chemotherapy agents | Add alkyl groups (e.g. **O⁶-methylguanine**) → mispairing | Direct reversal, BER, NER |
| **Ionising radiation** | X-rays, γ-rays, radioactive isotopes | **Single- and double-strand breaks**, clustered base damage, ROS | DSB repair (HR/NHEJ) |
| **Bulky chemical adducts** | Aflatoxin B1, benzo[a]pyrene | Bulky groups covalently bound to bases | NER; if missed → transversion (classic p53 codon 249 in liver cancer) |

**UV is the cleanest example to reason through:**

```
   adjacent thymines + UV photon
        │
        ▼
   CYCLOBUTANE PYRIMIDINE DIMER (two thymines covalently fused)
        │
        ▼
   helix distorted → replication fork stalls or misreads
        │
        ├── repaired correctly → nothing happens
        │
        └── not repaired → misincorporation opposite the dimer
                            → C→T transition signature at dipyrimidines
                            → basal cell carcinoma, melanoma risk
```

That **C→T transition at dipyrimidine sites** is the molecular fingerprint of UV damage — examiners love it because it links mechanism to mutational signature.

## Classifying mutations: point changes

### Transition vs transversion

| Type | Change | Example |
| --- | --- | --- |
| **Transition** | Purine ↔ purine or pyrimidine ↔ pyrimidine | **A→G, C→T** (more common — chemically easier) |
| **Transversion** | Purine ↔ pyrimidine | **A→T, G→C** (chemically more disruptive) |

Mutagens leave characteristic signatures: UV and deamination favour **transitions**; oxidative damage and bulky adducts produce more **transversions**.

### Consequences for the protein

```
   …G A A G A A C T C…
      Glu Glu ...

   SILENT      GAA → GAG          Glu → Glu          (often 3rd base)
   MISSENSE    GAA → GUA          Glu → Val          (amino acid changed)
   NOSENSE     GAA → TAA          Glu → STOP         (chain truncated)
   READTHROUGH stop → amino acid  (opposite of nonsense)
```

| Class | Effect on protein | Example |
| --- | --- | --- |
| **Silent (synonymous)** | None — degeneracy absorbs it | Most third-position substitutions |
| **Missense — conservative** | Similar residue substituted | Often tolerated (see [03 — Proteins](../01-biochemistry/03-proteins.md)) |
| **Missense — non-conservative** | Chemically different residue at a critical position | **Sickle cell: GAG→GTG, Glu→Val in β-globin** |
| **Nonsense** | Premature stop → truncated protein, usually destroyed by **nonsense-mediated decay** | Many β-thalassaemia alleles; Duchenne muscular dystrophy |
| **Splice-site** | Exon skipped or intron retained | Widespread; many cancers and β-thalassaemia variants |
| **Regulatory** | Alters promoter/enhancer strength without changing protein | Increases or decreases expression only |

**Sickle cell is the canonical missense chain:** one base change → one codon change → one amino acid changed (hydrophobic Val replaces Glu) → haemoglobin polymerises when deoxygenated → red cell sickles → anaemia and vaso-occlusion. Note that the *same* allele in one copy confers **malaria resistance** — a mutation's fitness effect depends on context (see [06 — Evolution](../06-evolution/)).

## Frameshifts: the most damaging point-level change

Insertions or deletions that are **not multiples of three** shift the reading frame:

```
   original   …AUG GCU ACU UAA…     Met Ala Thr Stop
   +1 insert  …AUG GCU [C]AC UUA…   Met Ala His Leu …  (all downstream wrong)
   −1 delete  …AUG GC  UAC UUA…     Met …             (all downstream wrong)
   +3 insert  …AUG GCU [AAA] ACU…   Met Ala Lys Thr   (in-frame: one residue added)
```

| | Frameshift | In-frame indel | Substitution |
| --- | --- | --- | --- |
| Scope | Entire downstream frame | Local insertion/deletion of residues | One codon |
| Severity | Usually catastrophic | Variable | Variable |
| Typical outcome | Premature stop, non-functional protein, mRNA decay | Domain disruption or tolerance | Silent to severe |

**Why +3 is different from +1:** the code is read in triplets, so adding or removing exactly three nucleotides preserves the frame — only the local region changes. This distinction explains why **ΔF508 in cystic fibrosis** (a three-base deletion removing one phenylalanine) leaves a mostly functional but misfolded CFTR, whereas a single-base deletion in the same gene would destroy it entirely.

## Trinucleotide repeat expansions and anticipation

Some loci contain short tandem repeats that **expand** during gametogenesis, especially when repeats exceed a threshold:

| Disease | Repeat | Gene | Threshold effect |
| --- | --- | --- | --- |
| **Huntington's disease** | **CAG** (polyQ) | *HTT* | ≥36 CAG → expanded protein aggregates in neurons; ≥40 fully penetrant |
| **Fragile X syndrome** | **CGG** | *FMR1* | ≥200 repeats → **promoter hypermethylation → gene silencing** (epigenetic consequence of a genetic change) |
| **Myotonic dystrophy** | **CTG** | *DMPK* | RNA gain-of-function: expanded transcript sequesters splicing factors |
| **Friedreich ataxia** | **GAA** | *FXN* | Repeat forms a triple helix → transcriptional silencing |

**Anticipation:** the tendency for a repeat disorder to appear **earlier and more severely in successive generations**, because repeat length tends to **expand** during gametogenesis (more dramatically through the paternal germline for Huntington's). Anticipation is therefore a *genetic* phenomenon with a *mechanistic* explanation in replication slippage.

**Mechanism:** the nascent strand slippes on the repetitive template during replication, forming a loop that, if not removed, becomes an inserted repeat copy — the same slippage that makes repeat loci mutation-prone in the first place.

## Chromosomal-level mutations: the pointer

Beyond single genes, whole chromosomes and large segments are altered — **aneuploidy, translocations, inversions, deletions, duplications**. Their origin is almost always **meiotic error**: nondisjunction, or crossing over between misplaced repeated sequences.

Those mechanisms are covered in [12 — Meiosis](../03-cellular-processes/12-meiosis.md) (nondisjunction and its aneuploidies), with mitotic equivalents in [11 — Mitosis and cytokinesis](../03-cellular-processes/11-mitosis-and-cytokinesis.md). This chapter stays at the sequence level; the pointer exists so the classification is not silently incomplete.

## Mutagenesis vs teratogenicity: a distinction worth defending

| | **Mutagen** | **Teratogen** |
| --- | --- | --- |
| **Definition** | Agent that damages DNA and thereby increases mutation rate | Agent that disrupts embryonic development, causing structural abnormality |
| **Molecular target** | DNA sequence or its repair | Cell signalling, proliferation, migration, apoptosis — *often not DNA at all* |
| **Heritable?** | Only if it hits **germline** cells | Usually **not** heritable — the damage is to the embryo's development |
| **Timing** | Any time | Critical **windows of organogenesis** |
| **Examples** | UV, benzopyrene, nitrosoguanidine, ionising radiation | **Thalidomide**, alcohol (fetal alcohol syndrome), rubella virus, isotretinoin, warfarin |

**The key logical point:** an agent can be profoundly damaging to a fetus without being mutagenic, and an agent can be mutagenic without being teratogenic. **Thalidomide** is the textbook teratogen — it disrupts angiogenic signalling and causes limb defects, not point mutations. Confusing the two categories leads directly to wrong exam answers and wrong risk counselling.

**Carcinogen vs mutagen** is a related pair: most true carcinogens are mutagens, but some promote cancer by driving proliferation or inflammation without directly altering DNA — a distinction modern carcinogen classification (IARC categories) makes explicit.

## DNA repair: the systems that keep the mutation rate low

| Pathway | Lesion handled | Mechanism | Failure disease |
| --- | --- | --- | --- |
| **Direct reversal** | O⁶-methylguanine | **MGMT** transfers the methyl group to itself (suicide enzyme) | — (silencing of MGMT occurs in tumours) |
| | Pyrimidine dimers | **Photolyase** (photoreactivation) — absent in placental mammals | — |
| **Base excision repair (BER)** | Small, non-helix-distorting: deaminated/oxidised bases, AP sites | **DNA glycosylase** removes the base → AP endonuclease → short-patch resynthesis → ligase | Some cancers; mutator phenotypes |
| **Nucleotide excision repair (NER)** | **Bulky, helix-distorting**: dimers, adducts | ~24–32 nt oligomer excised by XP proteins → resynthesis → ligation | **Xeroderma pigmentosum** |
| **Mismatch repair (MMR)** | Replication mismatches and small indels | MutS/MutL/MutH (bacteria); MSH2/MLH1 (humans); strand-directed excision | **Lynch syndrome** (HNPCC) |
| **Homologous recombination (HR)** | Double-strand breaks, template available | Uses the sister chromatid as template — **error-free** | **BRCA1/BRCA2** → breast/ovarian cancer |
| **Non-homologous end joining (NHEJ)** | Double-strand breaks, no template | Religates ends directly — **error-prone** (small indels) | Immunodeficiency (SCID-type defects) |
| **Translesion / error-prone (SOS)** | Blocked forks | Specialised polymerases bypass the lesion, **accurately sacrificing fidelity for survival** | Elevated mutation rate |

### Xeroderma pigmentosum: repair failure written on the skin

```
   UV → pyrimidine dimer
        │
        ├──▶ NER intact → dimer excised → no mutation
        │
        └──▶ NER defective (XP gene) → dimer persists
                    │
                    ▼
             replication inserts wrong bases
                    │
                    ▼
             UV-signature C→T mutations accumulate
                    │
                    ▼
        >1000-fold increase in skin cancer; severe photosensitivity
```

XP proves the whole framework: **without repair, the mutagen's effect is essentially unopposed**, and the clinical picture localises precisely to the tissue with the highest mutagen exposure.

**Transcription-coupled NER** explains another layer: genes being actively transcribed are repaired first, because the stalled RNA polymerase recruits repair factors — so non-dividing, highly transcriptional cells (neurons) still get protected.

### Error-prone repair and the survival trade-off

When a lesion cannot be removed, cells face a choice: stall (die) or bypass (mutate). The **SOS response** in bacteria induces translesion polymerases that replicate past the damage with relaxed checking. **Survival is purchased at the price of mutations** — the origin of antibiotic resistance under sub-inhibitory drug concentrations, and the reason chronic inflammation (persistent damage + high turnover) raises cancer risk.

## Mutational load

**Mutational load** is the accumulated burden of deleterious mutations in a genome or population. Each generation adds roughly 70 new mutations per human genome; purifying selection removes most strongly deleterious ones, while mildly deleterious variants persist. In an individual it expresses as **somatic clonal haematopoiesis** with age — detectable mutations in the blood cells of healthy older adults, a preview of cancer risk.

## Somatic vs germline

| | **Germline** | **Somatic** |
| --- | --- | --- |
| **Cells** | Egg, sperm, their precursors | All other cells |
| **Inherited?** | **Yes** — present in every cell of the offspring | **No** — confined to the individual |
| **Origin** | Arises in parent's germline or inherited | Arises in a body cell during life |
| **Consequences** | Mendelian disease, variation for selection | Mosaicism, **cancer** |
| **Study** | [04 — Genetics](../04-genetics/) | Oncology, mosaic disorders |

A mutation in one skin cell may produce a benign clone; the same mutation in a sperm cell is passed to every cell of a future child. **Location determines heritability** — a point that resolves most student confusion about "genetic disease".

## Cancer as accumulated mutation

Cancer is not one mutation but a **sequence of them**, and the cell-cycle framework in [10 — The cell cycle and its checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) supplies the functional categories:

```
   normal cell
      ↓  mutation 1: growth signalling ON (e.g. RAS)          — oncogene
      ↓  mutation 2: checkpoint lost (p53)                    — brake failure
      ↓  mutation 3: repair defective (MLH1) → mutation rate ↑ — mutator phenotype
      ↓  mutation 4: apoptosis resistance (BCL2)
      ↓  mutation 5: telomerase reactivated                   — immortality
      ↓  mutation 6: angiogenesis, invasion
   MALIGNANT CLONE
```

**Three principles the sequence teaches:**

1. **Order matters more than count** — a p53 loss early accelerates everything downstream by raising the mutation rate.
2. **Repair defects are accelerators** — Lynch syndrome doesn't break one gene; it breaks the *fidelity system*, so mutations accumulate genome-wide.
3. **Cancer is clonal** — every cell in a tumour descends from one cell that acquired the full set; tumour heterogeneity is the record of ongoing mutation.

## Medical relevance

Germline variants that alter drug metabolism, targets, or transporters are the basis of **pharmacogenomics** — genotype predicts toxicity or failure *before the first dose*:

| Gene | Variant effect | Drug | Clinical action |
| --- | --- | --- | --- |
| **CYP2D6** | Poor metaboliser → no morphine from codeine; ultra-rapid → toxicity | **Codeine** | Avoid in poor/ultra-rapid metabolisers |
| **CYP2C19** | Poor metaboliser → no active metabolite | **Clopidogrel** | Switch to ticagrelor/prasugrel |
| **TPMT / NUDT15** | Reduced detoxification → severe myelosuppression | **6-mercaptopurine, azathioprine** | **Pre-treatment genotype testing; dose reduction** |
| **DPYD** | Reduced breakdown → life-threatening toxicity | **5-fluorouracil** | Test before treatment; dose adjust or avoid |
| **UGT1A1** | Slower conjugation → severe diarrhoea/neutropenia | **Irinotecan** | Dose reduction |
| **VKORC1** | Altered target sensitivity | **Warfarin** | Dose prediction algorithms |
| **HLA-B*57:01** | Hypersensitivity | **Abacavir** | **Mandatory screening** before HIV therapy |
| **HLA-B*15:02** | Severe cutaneous reactions (Stevens–Johnson) | **Carbamazepine** | Screen in at-risk populations |

**The logic of each is identical:** the variant changes the amount of active drug (metabolism) or the tissue's reaction to it (HLA). This is mutation knowledge turned into prescribing rules — the clearest "why do I need to know this" in the chapter.

**Other clinically central mutations:**

- **BRCA1/2** — homologous recombination defect → high breast/ovarian cancer risk; **PARP inhibitors** block the backup pathway (**synthetic lethality**).
- **HER2 amplification** → trastuzumab; **somatic EGFR mutations** → gefitinib in lung adenocarcinoma.
- **BCR–ABL fusion** (translocation) → imatinib in chronic myeloid leukaemia — a chromosomal-level mutation with a targeted drug.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Mutations are always harmful" | Many are **silent**, some neutral, occasionally beneficial — effect depends on position, protein tolerance, and environment. |
| "Mutagens cause mutations directly in the offspring" | Only **germline** exposure produces heritable mutations; somatic damage stays with the individual. |
| "A teratogen is a mutagen" | No — teratogens disrupt **development** (signalling, proliferation); thalidomide is teratogenic without being mutagenic. |
| "Missense is worse than nonsense" | Usually the reverse: **nonsense** truncates the whole protein; missense may be conservative or even silent-functionally. |
| "Frameshift and in-frame deletion are equivalent" | In-frame indels preserve the reading frame (multiples of 3); frameshifts rewrite everything downstream. |
| "Repair always restores the original sequence" | NER/MMR/BER restore sequence; **translesion bypass and NHEJ** may not — error-prone repair trades fidelity for survival. |
| "Somatic mutations can be passed to children" | Only **germline** mutations are transmitted; a tumour mutation is never inherited. |
| "Anticipation is psychological" | In genetics it means **earlier onset/more severe disease in successive generations**, caused by repeat expansion. |

## Key facts

- A mutation is any **heritable change in DNA sequence**; sources are **replication errors, spontaneous damage (deamination, depurination, oxidation), and mutagens**.
- **UV** causes **pyrimidine dimers** → signature **C→T transitions** at dipyrimidines; repaired by **nucleotide excision repair**.
- Mutagen classes: **UV, base analogues, intercalating agents, alkylating agents, ionising radiation** — each with a distinct lesion and repair pathway.
- **Point mutations**: transitions vs transversions; **silent, missense (sickle cell: Glu→Val), nonsense, splice-site, regulatory** consequences.
- **Frameshifts** = non-multiple-of-3 indels → whole downstream frame rewritten; **in-frame indels** change only local residues.
- **Trinucleotide repeats** expand on transmission → **anticipation**; fragile X links repeat expansion to **epigenetic silencing**.
- **Mutagen ≠ teratogen**: mutagens damage DNA; teratogens disrupt development (thalidomide) and are usually not heritable.
- Repair systems: **BER** (small lesions), **NER** (bulky adducts — **xeroderma pigmentosum**), **MMR** (mismatches — **Lynch syndrome**), **HR/NHEJ** (double-strand breaks — **BRCA**), **direct reversal** (MGMT); **error-prone translesion repair** trades accuracy for survival.
- **Somatic vs germline** determines whether a mutation can be inherited; cancer is **somatic, clonal, and cumulative**.
- **Pharmacogenomics**: CYP2D6/codeine, TPMT/6-MP, DPYD/5-FU, HLA-B*57:01/abacavir — genotype guides dosing before treatment.

## Practice questions

**1. UV light causes mutations primarily by**

A. Inserting base analogues during replication
B. Forming pyrimidine dimers that distort the helix and mispair if unrepaired
C. Methylating guanine at the O⁶ position
D. Causing double-strand breaks at telomeres

**Answer: B**

Explanation: UV photons fuse adjacent pyrimidines into cyclobutane dimers (and 6–4 adducts), bulging the helix; if nucleotide excision repair fails, replication opposite the dimer inserts wrong bases, producing the characteristic C→T transition at dipyrimidine sites. Base analogues are a different mutagen class (A), alkylation (C) is the action of alkylating agents, and double-strand breaks are the signature of ionising radiation (D).

---

**2. A mutation changing GGG to GGA, so that glycine is still encoded, is best described as**

A. Nonsense
B. Missense
C. Silent (synonymous)
D. Frameshift

**Answer: C**

Explanation: The codon changed but the amino acid did not — the definition of a silent or synonymous mutation, made possible by degeneracy, especially at the third position. Nonsense creates a stop, missense changes the residue, and a frameshift requires an insertion or deletion that is not a multiple of three.

---

**3. Which type of mutation is most likely to destroy protein function entirely?**

A. A third-codon-position transversion that is silent
B. A single-base deletion that shifts the reading frame near the start
C. A conservative missense substitution in a flexible loop
D. A three-base in-frame deletion of one residue

**Answer: B**

Explanation: A frameshift near the 5′ end rewrites every downstream codon, almost always producing a premature stop and a non-functional transcript degraded by nonsense-mediated decay. Silent changes (A) leave the protein untouched, conservative substitutions (C) are often tolerated, and in-frame indels (D) preserve the frame entirely.

---

**4. Fragile X syndrome results from CGG repeat expansion because the expansion**

A. Directly changes the FMRP amino acid sequence
B. Triggers promoter hypermethylation and silencing of *FMR1*
C. Creates a frameshift in the coding region
D. Activates an alternative splice site

**Answer: B**

Explanation: Above ~200 repeats the CpG-rich 5′ region becomes methylated and the gene is transcriptionally silenced, so FMRP is absent — a genetic change causing an epigenetic consequence. The repeat lies in the 5′ UTR so no protein sequence changes (A), no reading frame runs through it (C), and splicing is not the mechanism (D).

---

**5. Xeroderma pigmentosum demonstrates that**

A. UV light only damages RNA
B. Defective nucleotide excision repair allows UV-induced lesions to become permanent mutations, producing extreme skin cancer susceptibility
C. Melanoma is caused exclusively by alkylating agents
D. Base excision repair handles pyrimidine dimers

**Answer: B**

Explanation: XP cells cannot excise bulky UV lesions, so dimers persist through replication and fix as mutations — hence >1000-fold cancer risk in sun-exposed tissue. Dimers are handled by NER, not BER (D); UV damages DNA directly (A); and the point is repair failure, not a specific agent class (C).

---

**6. The clearest difference between a mutagen and a teratogen is that**

A. Mutagens are always teratogenic
B. Teratogens damage developing tissue architecture via signalling/proliferation and need not alter DNA
C. Teratogens act only on germ cells
D. Mutagens act only during organogenesis

**Answer: B**

Explanation: A teratogen disrupts the developmental programme — thalidomide alters angiogenic signalling and causes limb defects without being mutagenic; alcohol damages the fetus by multiple non-mutational routes. Mutagens alter DNA sequence and matter for heredity only in the germline; neither category is defined by the other's target or timing.

---

**7. Which repair pathway uses the undamaged sister chromatid as a template and is therefore error-free?**

A. Non-homologous end joining
B. Base excision repair
C. Homologous recombination
D. Translesion synthesis

**Answer: C**

Explanation: Homologous recombination repairs double-strand breaks by invading the sister chromatid and copying the correct sequence — accurate because a template exists. NHEJ ligates broken ends without a template and often introduces small indels; BER handles single damaged bases; translesion synthesis deliberately bypasses lesions with reduced accuracy.

---

**8. A patient homozygous for a TPMT loss-of-function variant given standard-dose azathioprine would most likely develop**

A. No effect, because TPMT is not involved in purine metabolism
B. Severe, potentially fatal myelosuppression
C. Increased drug resistance
D. Teratogenicity

**Answer: B**

Explanation: TPMT inactivates the thiopurine drugs; without it, excessive active metabolite accumulates and suppresses marrow — the classic pharmacogenomic adverse reaction, preventable by pre-treatment genotyping or dose reduction. It is not an efficacy problem (C), TPMT is exactly the relevant enzyme (A), and the risk is toxicity to the patient rather than teratogenesis (D) — though the drug is also teratogenic, that is a separate property.

---

**9. Why can a somatic mutation cause cancer but never be inherited?**

A. Somatic mutations are always lethal to gametes
B. They occur in body cells, not in the egg or sperm lineage, so they are not present in the gametes that form the next generation
C. Somatic mutations are repaired before meiosis
D. Somatic mutations are not real genetic changes

**Answer: B**

Explanation: Inheritance requires a mutation to be present in the germline cells that contribute DNA to the offspring. A mutation confined to a liver or skin cell cannot appear in sperm or eggs, so it dies with the individual — which is why cancer is not inherited even though it is genetic in origin. Germline mutations in a tumour-suppressor gene, by contrast, are present in every cell and are passed on.

---

**10. The main reason cancer develops only after decades is that**

A. Mutagens take decades to enter the body
B. Multiple regulatory mutations must accumulate, each conferring a selective advantage, and repair/checkpoint systems remove most damaged cells before that happens
C. Cells cannot mutate before adulthood
D. Telomerase is only active in old age

**Answer: B**

Explanation: Redundant controls mean one mutation is tolerated or eliminated (senescence, apoptosis, repair); malignancy requires a rare sequence of hits — proliferative signalling, checkpoint loss, repair failure, immortality — which takes time and is probabilistic. That is why cancer incidence rises steeply with age. Mutagens act throughout life (A), younger cells mutate fine (C), and telomerase reactivation is a late event in tumour progression, not an age-related activation (D).
