# RNA and Its Three Types

## Why it matters

If DNA is the archive, **RNA is the working copy**. Every instruction that leaves the genome travels as RNA, every amino acid is delivered by RNA, and the machine that reads the code is built from RNA. Cells that have no DNA at all — mature red cells, and every RNA virus — still run their information flow on RNA, which shows how central the molecule is to *doing* rather than *storing*.

RNA also breaks the assumption that nucleic acids only carry information. Because a single strand folds into complex shapes with pockets, grooves, and catalytic centres, RNA can **recognise, regulate, and catalyse** — jobs normally reserved for proteins. That combination is the foundation of the **RNA world** hypothesis in [06 — Evolution](../06-evolution/) and of an expanding class of RNA-based medicines.

This chapter takes the three canonical RNAs in detail — **mRNA, tRNA, rRNA** — surveys the regulatory RNAs that have been discovered since, and sets up the two chapters that follow: [04 — Transcription](04-transcription.md) (how the message is made) and [05 — Translation and the genetic code](05-translation-and-the-genetic-code.md) (how it is read).

## RNA vs DNA: the differences that have reasons

| Feature | DNA | RNA | Why the difference exists |
| --- | --- | --- | --- |
| Sugar | Deoxyribose (no 2′-OH) | **Ribose (2′-OH)** | RNA must be transient and reactive; DNA must be archival |
| Pyrimidines | C, **T** | C, **U** | Uracil is cheaper; damage in DNA is detectable only because thymine is used there |
| Strands | Two, antiparallel | **Usually one** | Single strands fold into functional shapes |
| Typical length | Very long | Short–moderate | Messages are disposable; genomes are permanent |
| Location (eukaryote) | Nucleus, mitochondria | Nucleus **and** cytoplasm | RNA must travel to ribosomes |
| Synthesis | DNA polymerase | **RNA polymerase** | Different template, different error tolerance |
| Function | Permanent storage | Transfer, expression, regulation, catalysis | — |

**The 2′-OH deserves emphasis:** it makes RNA susceptible to alkaline hydrolysis and to ubiquitous RNases — which is why "RNase-free" technique matters in the lab and why mRNA therapies need chemical modifications. Stability is a *design feature* of DNA and a *limitation* of RNA that medicine has had to engineer around.

## The three canonical RNAs at a glance

```
   DNA ──transcription──▶ mRNA ──carries code──▶ RIBOSOME
                                                        │
                                     rRNA ── catalyses + scaffolds the ribosome
                                                        │
                                     tRNA ── delivers amino acids, decodes codons
                                                        ▼
                                                   POLYPEPTIDE
```

| RNA | Approx. share of cell RNA | Job | Lifetime |
| --- | --- | --- | --- |
| **rRNA** | ~80 % | Structural and catalytic core of the ribosome | Days–weeks (stable) |
| **tRNA** | ~15 % | Adapter: carries amino acids, reads codons | Hours–days (stable, heavily modified) |
| **mRNA** | ~5 % | Carries the code from gene to ribosome | Minutes–hours (deliberately short) |

**The proportions tell you where the cell's RNA budget goes:** almost all of it is machinery, not message. A cell does not stockpile instructions; it stocks up on the readers.

## Messenger RNA (mRNA)

mRNA is a transient copy of one or more genes, exported from the nucleus and read by ribosomes.

**Eukaryotic mature mRNA:**

```
  5′ m⁷G CAP ─ UTR ─ AUG ─ codons ─ ─ ─ stop ─ UTR ─ poly-A tail 3′
       │        │     │                            │       │
    protects   recruit  start           stability /   export /
    + scanning ribosome  codon          localisation  ribosome binding
```

| Feature | Function |
| --- | --- |
| **5′ 7-methylguanosine cap** | Protects from 5′ exonucleases; recognised by the translation initiation machinery |
| **5′ UTR** | Regulatory leader; secondary structures and upstream open reading frames tune translation |
| **Coding sequence** | Read in triplets from AUG to a stop codon |
| **3′ UTR** | Binding sites for miRNAs and stabilising/destabilising proteins — a major control surface |
| **Poly-A tail** | Protects the 3′ end; its shortening is the clock that limits mRNA lifetime |

**Prokaryotic mRNA differs structurally:** often **polycistronic** (one message encoding several proteins, as in operons — see [06 — Gene regulation](06-gene-regulation.md)), no cap, no poly-A tail (or a short, degradation-promoting one), and translation begins **while transcription is still running**. Compartmentalisation is what separates the two processes in eukaryotes.

**Why mRNA is destroyed quickly:** a cell must be able to change its protein output fast. A message with a half-life of minutes can be switched off by stopping transcription; a message lasting days could not. Degradation rates are themselves regulated — see [06 — Gene regulation](06-gene-regulation.md).

The processing that turns a primary transcript into this mature form belongs to [04 — Transcription](04-transcription.md) and is only summarised here.

## Transfer RNA (tRNA): the adapter

tRNA is the physical bridge between a nucleotide sequence and an amino acid — the molecule that makes the genetic code actionable.

### The cloverleaf and the L

```
        SECONDARY STRUCTURE (cloverleaf)

                 acceptor stem
               5′─┐         ┌─3′  ← amino acid attaches
                  │  C C A  │        to the 3′ CCA end
                  └────┬────┘
                       │
            ┌──────────┴──────────┐
            │                     │
        D arm                  TΨC arm
            │                     │
            └──────────┬──────────┘
                       │
                  anticodon arm
                       │
                    anticodon
                 (reads the codon)


        TERTIARY STRUCTURE (L-shape)

        amino acid
             │
             └── acceptor end
                      ╲
                       ╲  (the two arms fold at right angles;
                        ╲   anticodon sits at the far end)
                         ╲
                      anticodon
```

Two ends of one molecule, ~75 nucleotides long, physically separated — that distance is the whole design: the ribosome can check the anticodon and the amino acid simultaneously, because they are held in fixed relation.

### The anticodon and wobble

The anticodon is a **trinucleotide** read 3′→5′ against the mRNA codon 5′→3′. But pairing at the **first position of the anticodon (= third "wobble" position of the codon)** tolerates non-standard geometry:

| Anticodon 5′ position (wobble) | Codon 3′ position it can pair with |
| --- | --- |
| C | A (strict) |
| A | U (strict; often modified to inosine → U, C, A) |
| **G** | **U or C** |
| **I (inosine)** | **U, C, or A** |
| U | A or G (rare, mostly in organelles) |

**Consequences:**

- **Fewer tRNAs than codons are needed** — about 45 tRNAs read 61 sense codons in *E. coli*.
- **Degeneracy is physically explained:** codons differing only at the third position often share one tRNA, which is why many third-position substitutions are **silent** (see [05 — Translation and the genetic code](05-translation-and-the-genetic-code.md) and [07 — Mutations](07-mutations.md)).

### Aminoacyl-tRNA synthetases: the real translators

The ribosome does **not** check that the right amino acid is attached. **That job belongs to the aminoacyl-tRNA synthetase** — one enzyme per amino acid (20 in standard sets), each with:

1. A **synthetic site** that charges the tRNA:
   ```
   amino acid + tRNA + ATP ──▶ aminoacyl-tRNA + AMP + PPᵢ
                              (2 high-energy phosphate bonds spent;
                               PPᵢ hydrolysis drives the reaction forward)
   ```
2. An **editing site** that hydrolyses a wrongly attached amino acid (**proofreading by size** — e.g. isoleucine synthetase rejects valine by steric check; the editing site hydrolyses any amino acid too small to be selected properly).

**The synthetase is the true "translator"**: it, not the ribosome, determines which amino acid a given anticodon will carry. Errors here are permanent — no downstream step can detect them. The fidelity chain for translation is therefore: **synthetase selection and editing → codon–anticodon pairing → ribosomal kinetic proofreading**.

Some tRNAs carry **modified bases** (inosine, pseudouridine, dihydrouridine, methylated bases) — up to 10 % of residues in mature tRNA. These modifications stabilise the L-shape, tune wobble pairing, and are a marker of tRNA maturity.

## Ribosomal RNA (rRNA): the catalyst

Ribosomes are **ribozymes** — the catalytic activity is RNA, not protein.

| Ribosome | Subunits | rRNAs | Where |
| --- | --- | --- | --- |
| **70S** (bacterial type) | 50S + 30S | **23S**, 16S, 5S | Bacteria, **mitochondria, chloroplasts** |
| **80S** (eukaryotic cytosol) | 60S + 40S | **28S**, 18S, 5.8S, 5S | Eukaryotic cytoplasm |

(S values are sedimentation rates, not masses — see [02 — Protein synthesis and trafficking organelles](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md).)

**What the rRNAs do:**

- **16S/18S rRNA** — small subunit: **decoding**. Its bases monitor codon–anticodon geometry; a correct match triggers a conformational change that allows tRNA accommodation. This is where initial selection happens.
- **23S/28S rRNA** — large subunit: **peptidyl transferase**. The peptide bond is formed by nucleophilic attack orchestrated by rRNA functional groups, with no protein residue in the active site.
- rRNA also **positions mRNA and tRNAs**, forms the **GTPase-activating centre** that accelerates factor-driven GTP hydrolysis, and constitutes the bulk of ribosome mass.

**The evidence that RNA does the chemistry:** highly purified ribosomal protein preparations have no peptidyl transferase activity, while rRNA preparations do; and the reaction proceeds with the protein component removed. The proteins are structural — they stabilise the RNA's folding (see [03 — Proteins](../01-biochemistry/03-proteins.md) for why RNA alone often needs help folding).

**Consequence for medicine and evolution:** the ribosome's mechanism is **universal**, which is why translation-inhibiting antibiotics work across bacteria (see [05 — Translation and the genetic code](05-translation-and-the-genetic-code.md)), and why the ribosome is the strongest single piece of evidence that **RNA came before protein** in early evolution.

## Other RNAs: a brief census

| RNA | Size/origin | Function |
| --- | --- | --- |
| **snRNA** (U1, U2, U4, U5, U6) | Small nuclear, with proteins = **snRNPs** | Spliceosome catalysis — see [04 — Transcription](04-transcription.md) |
| **snoRNA** | Small nucleolar | Chemical modification of rRNA in the nucleolus |
| **miRNA** | ~22 nt, transcribed as hairpins | Guides **RISC** to complementary 3′ UTRs → translational repression or mRNA decay |
| **siRNA** | ~21 nt, double-stranded precursor | Perfect complementarity → cleavage of target mRNA (RNAi) |
| **lncRNA** | >200 nt | Chromatin remodelling, X-inactivation (**XIST**), enhancer regulation |
| **Ribozymes** | RNA with catalytic activity | Self-splicing introns, RNase P, the ribosome itself |
| **tmRNA, CRISPR RNA** | Bacterial | Rescuing stalled translation; adaptive immunity |
| **rRNA/tRNA processing enzymes' guides** | Various | Maturation of other RNAs |

**The regulatory layer matters clinically:** miRNA and siRNA pathways are drug targets and drug tools — **patisiran** is an siRNA therapeutic for hereditary transthyretin amyloidosis, and antisense oligonucleotides manipulate splicing (see [07 — Mutations](07-mutations.md) and [06 — Gene regulation](06-gene-regulation.md)).

## Why RNA may have come first

```
RNA WORLD HYPOTHESIS (simplified)

   free nucleotides ──▶ self-replicating RNA
                              │
             ┌────────────────┼─────────────────┐
             ▼                ▼                 ▼
        stores information   CATALYSES        carries amino acids
        (like DNA)           reactions        (like adapter molecules)
             │                │                 │
             └────────────────┴─────────────────┘
                              │
              protein takes over catalysis (ribozyme → enzyme)
              DNA takes over storage (more stable)
                              │
                        DNA → RNA → PROTEIN
```

Three observations support it: **ribozymes exist** (the ribosome, RNase P, self-splicing introns); **cofactors are nucleotides** (ATP, NAD⁺, FAD, CoA, SAM — see [04 — Enzymes](../01-biochemistry/05-enzymes.md)); and **both DNA and protein synthesis depend on RNA** machinery (primers, adapter tRNAs, ribosomes). A system built on RNA could bootstrap itself; a system needing protein first could not. This is developed properly in [06 — Evolution](../06-evolution/).

## Medical relevance

**RNA viruses turn the host's RNA world against it.** Influenza, SARS-CoV-2, hepatitis C, and HIV (after reverse transcription) depend on RNA polymerases or reverse transcriptases that differ enough from host enzymes to be druggable: **ribavirin**, **remdesivir**, **sofosbuvir** (a nucleotide analogue for HCV RNA polymerase), and **zidovudine** (HIV reverse transcriptase). Selectivity is always the same story — hit the viral enzyme.

**tRNA biology in disease:** mutations in mitochondrial tRNAs (e.g. m.8344A>G in **MERRF**) disrupt oxidative phosphorylation because mitochondrial ribosomes must read organelle messages with organellar tRNAs; the resulting myoclonus and ragged-red fibres show what happens when an adapter fails. Mutations in tRNA-modifying enzymes cause pontocerebellar hypoplasia and other encephalopathies.

**RNA therapeutics are the fastest-growing drug class:**

| Approach | Example | Mechanism |
| --- | --- | --- |
| **Antisense oligonucleotide** | Nusinersen (SMA) | Blocks a splicing silencer → more full-length SMN protein |
| **siRNA** | Patisiran | Guides RISC to destroy the disease mRNA |
| **mRNA vaccine** | COVID-19 mRNA vaccines | Delivers modified mRNA encoding spike protein; cap and pseudouridine protect it |
| **Ribozyme/aptamer** | Pegaptanib (VEGF aptamer) | Blocks a protein by folded-RNA binding |

All of them depend on the principles in this chapter: complementarity, folding, transient RNA, and the ability to be degraded on demand.

**Cancer and miRNA:** clusters of miRNAs (the *let-7* family, miR-21, miR-155) are consistently dysregulated — some act as oncogenes, others as tumour suppressors — and circulating miRNAs are being validated as diagnostics because RNA is released into blood and can be detected by RT-PCR.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The ribosome checks that the correct amino acid is attached" | It does not. **Aminoacyl-tRNA synthetases** charge tRNA correctly and edit mistakes; the ribosome checks codon–anticodon pairing. |
| "mRNA is the most abundant RNA" | **rRNA is ~80 %** of cellular RNA; mRNA is only a few per cent. |
| "tRNA and rRNA are translated" | Neither is translated; both are *function* RNAs — one decodes, one catalyses. |
| "Wobble means sloppy reading" | Wobble is a **defined, limited** flexibility at the third codon position that lets fewer tRNAs cover 61 codons — precision is preserved at the first two positions. |
| "RNA has no base pairing because it is single-stranded" | Single-stranded RNA base-pairs **intra**molecularly — that is what creates cloverleaves, hairpins, and catalytic cores. |
| "Poly-A tail is part of the gene" | It is added **post-transcriptionally** by poly-A polymerase; it is not encoded in the DNA template. |

## Key facts

- RNA differs from DNA by **ribose (2′-OH), uracil instead of thymine, single-strandedness, and transience** — each difference follows from RNA's role as a temporary, functional copy.
- Three main types: **mRNA** (code), **tRNA** (adapter), **rRNA** (catalyst/structure) — by mass, rRNA ≈ 80 %, tRNA ≈ 15 %, mRNA ≈ 5 %.
- Eukaryotic mRNA carries a **5′ cap, UTRs, coding sequence, and poly-A tail**; prokaryotic mRNA is often **polycistronic** and untranslated while still being transcribed.
- tRNA folds to a **cloverleaf** secondary structure and an **L-shaped** tertiary structure, with the **anticodon** at one end and the **3′ CCA acceptor** at the other.
- **Wobble** at the third codon position (inosine, G–U pairing) lets ~45 tRNAs read 61 codons and explains many silent third-base substitutions.
- **Aminoacyl-tRNA synthetases** — one per amino acid, with synthetic **and editing** sites — are the true translators; charging costs **ATP → AMP + PPᵢ** (2 equivalents).
- **rRNA is a ribozyme**: 23S/28S rRNA catalyses peptide bond formation; 16S/18S rRNA decodes. Proteins are structural.
- Ribosomes: **70S = 50S + 30S** (bacteria, mitochondria, chloroplasts); **80S = 60S + 40S** (eukaryotic cytosol).
- Regulatory RNAs — **miRNA, siRNA, snRNA, snoRNA, lncRNA** — control splicing, stability, translation, and chromatin.
- The **RNA world** hypothesis rests on catalytic RNA, nucleotide cofactors, and the fact that both replication and translation need RNA machinery.

## Practice questions

**1. Which statement about the ribosome's catalytic activity is correct?**

A. Peptide bonds are formed by an active-site serine on a ribosomal protein
B. Peptidyl transferase is carried out by rRNA, making the ribosome a ribozyme
C. rRNA only provides structural support; proteins do the chemistry
D. Translation requires a separate enzyme to form each peptide bond

**Answer: B**

Explanation: The peptidyl transferase centre of the large subunit is composed entirely of 23S/28S rRNA, with no protein residue in the active site — the defining evidence that RNA can catalyse and that RNA machinery preceded protein machinery. Proteins stabilise rRNA folding (so removing them does abolish activity) but do not catalyse the reaction, and no separate bond-forming enzyme exists.

---

**2. Aminoacyl-tRNA synthetases are essential because they**

A. Add the amino acid to the growing polypeptide
B. Attach the correct amino acid to the correct tRNA, with an editing site that hydrolyses misactivations
C. Degrade mischarged tRNAs at the ribosome
D. Read the mRNA codon directly

**Answer: B**

Explanation: Each synthetase recognises one amino acid and its cognate tRNAs, charges the 3′ CCA end with ATP, and uses a separate editing site to cut off wrongly attached amino acids — the only point at which amino acid identity is established. Peptide bond formation at the ribosome (A) is rRNA-catalysed; the ribosome selects tRNAs by codon–anticodon pairing (D) but cannot verify amino acid identity; nothing degrades charged tRNAs as a check (C).

---

**3. The wobble position refers to**

A. The first base of the mRNA codon pairing with the third base of the anticodon
B. The third base of the mRNA codon pairing with the first (5′) base of the anticodon, where non-standard pairs such as G–U and I–U are tolerated
C. A weak point in the tRNA backbone where it bends
D. The amino acid attachment site

**Answer: B**

Explanation: Wobble pairing occurs at the third codon position, where the anticodon's 5′ base can form non-Watson–Crick pairs. Inosine at that position can read U, C, or A. This is why fewer tRNAs than codons are needed and why changes at the third codon position are frequently silent — the same tRNA still binds.

---

**4. Which RNA makes up the largest fraction of a cell's total RNA?**

A. mRNA
B. tRNA
C. rRNA
D. miRNA

**Answer: C**

Explanation: rRNA is roughly 80 % of cellular RNA because ribosomes are needed continuously and in large numbers, tRNA about 15 %, and mRNA only a few per cent — messages are made and destroyed rapidly rather than stockpiled. miRNA is present in far smaller amounts still. The proportions reflect the cell's investment in reading capacity rather than in stored instructions.

---

**5. In tRNA, the anticodon and the amino acid attachment site are**

A. Adjacent, so the ribosome can compare them directly
B. At opposite ends of the L-shaped molecule, separated by a fixed distance
C. Both located in the D arm
D. On separate molecules

**Answer: B**

Explanation: The cloverleaf folds into an L with the amino acid on the 3′ CCA acceptor stem at one tip and the anticodon at the other. That fixed separation is what lets the ribosome hold codon recognition and peptide bond formation in the same active site. They are not adjacent (A), both are on one molecule (D), and the anticodon is in the anticodon arm, not the D arm (C).

---

**6. Why is mRNA's short half-life functionally important?**

A. It keeps the cytoplasm from becoming too crowded
B. It allows the cell to change its protein output rapidly when transcription stops
C. It prevents mRNA from leaving the nucleus
D. It is required for the poly-A tail to be added

**Answer: B**

Explanation: A message that persists for minutes can be turned off simply by ceasing transcription — the existing pool decays and protein synthesis stops. If messages were stable for days, stopping transcription would have no quick effect and regulation would have to act at the protein level alone. Stability, decay signals in the 3′ UTR, and miRNA binding are all regulated control points, not accidents.

---

**7. Which pairing correctly matches an RNA with its function?**

A. snRNA — splicing catalysis within the spliceosome
B. snoRNA — carrying amino acids
C. miRNA — forming the ribosomal core
D. tRNA — guiding chromatin silencing

**Answer: A**

Explanation: Small nuclear RNAs associate with proteins to form snRNPs, whose snRNAs recognise splice sites and catalyse the splicing reactions. tRNA (B) is the amino acid adapter; rRNA (C) forms the ribosomal core; miRNA (D) silences mRNAs post-transcriptionally rather than acting on chromatin — chromatin-level silencing by RNA is the job of lncRNAs such as XIST.

---

**8. Which observation most directly supports the RNA world hypothesis?**

A. DNA is more stable than RNA
B. Ribozymes can catalyse reactions, and cofactors such as ATP and NAD⁺ are nucleotides
C. Proteins fold more reliably than RNA
D. RNA viruses are common

**Answer: B**

Explanation: If early life needed both information storage and catalysis before proteins existed, RNA must have done both — and catalytic RNA plus nucleotide-derived cofactors show it can. DNA stability (A) explains why DNA later took over storage; protein folding (C) explains why enzymes took over catalysis; RNA virus prevalence (D) says nothing about early evolution.

---

**9. A drug that binds the 23S rRNA of bacterial ribosomes and blocks peptide bond formation would**

A. Be equally toxic to human cytoplasmic ribosomes
B. Selectively inhibit bacterial protein synthesis, because human cytosolic ribosomes use 28S rRNA in a different structural context
C. Have no effect because RNA is not a drug target
D. Inhibit only mitochondrial protein synthesis

**Answer: B**

Explanation: The 70S and 80S ribosomes differ in rRNA sequence and structure, so an agent that fits the bacterial 23S site generally does not fit the human 28S site — the basis of many protein synthesis inhibitors (chloramphenicol, linezolid bind near this region). Human cytoplasmic translation is spared, although mitochondrial ribosomes (bacterial-type 70S) remain a potential source of toxicity, which is why such drugs are monitored for mitochondrial side effects.

---

**10. The statement "the ribosome translates tRNA" is wrong because**

A. tRNA is never present at the ribosome
B. tRNA is an adapter read by the ribosome using codon–anticodon pairing; it is not itself translated into protein
C. Ribosomes only read mRNA and never interact with tRNA
D. tRNA is DNA-dependent

**Answer: B**

Explanation: The ribosome reads the mRNA codon and accepts a tRNA whose anticodon matches; the tRNA's job is to deliver an amino acid, not to be interpreted as a coding sequence. tRNA is transcribed from tRNA genes and processed, never translated. Ribosomes obviously do interact with tRNAs during decoding and peptide bond formation (C), and D is meaningless in this context.
