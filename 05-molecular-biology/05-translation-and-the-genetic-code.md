# Translation and the Genetic Code

## Why it matters

Translation is where information changes chemical language: a **nucleotide sequence** becomes an **amino acid sequence**, and a one-dimensional code becomes a folded, functional protein. Everything the genome does ultimately passes through this step — which is why every antibiotic class that targets the ribosome, every toxin that blocks elongation, and every genetic disease caused by a premature stop codon is a translation story.

It is also the step where the **genetic code** is actually read. The code's structure — triplet, non-overlapping, degenerate, nearly universal — determines which mutations are harmless and which are catastrophic, which makes it the bridge between [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) and [07 — Mutations](07-mutations.md).

This chapter assumes the three RNAs of [03 — RNA and its three types](03-rna-and-its-three-types.md) and connects forward to [06 — Gene regulation](06-gene-regulation.md), where translation itself becomes a control point.

## The genetic code: logic before memorisation

The code can be derived from a handful of properties rather than memorised blindly:

| Property | Meaning | Consequence |
| --- | --- | --- |
| **Triplet** | 3 nucleotides = 1 codon | 4³ = **64 codons** for 20 amino acids |
| **Non-overlapping** | Each nucleotide belongs to one codon | Reading frame is fixed from the start |
| **Commaless** | No gaps between codons | One extra/missing base shifts everything downstream |
| **Degenerate** | Most amino acids have >1 codon | Many point mutations are silent |
| **Nearly universal** | Same codons in almost all organisms | Genes can be expressed across species (with exceptions, below) |
| **Unambiguous** | Each codon specifies exactly one amino acid | No codon means two things |

### Reading the table

```
                 2nd base
            U        C        A        G
        ┌────────┬────────┬────────┬────────┐
   U    │ Phe    │ Ser    │ Tyr    │ Cys    │
  1st   │ Phe    │ Ser    │ Tyr    │ Cys    │
   C    │ Leu    │ Ser    │ His    │ Arg    │  ← first two bases
   A    │ Leu    │ Pro    │ Gln    │ Arg    │    narrow it down
   G    │ Val    │ Ala    │ Glu    │ Gly    │
        └────────┴────────┴────────┴────────┘
   3rd base is the wobble position — often interchangeable
```

**Three rules of thumb:**

1. **Codons differing only at the third position usually specify the same amino acid** — the direct fingerprint of degeneracy and wobble.
2. **Chemically similar amino acids often share codon families** (e.g. all six leucine codons start with U or C and end in U/C/A/G in a consistent pattern) — so many substitutions are *conservative*.
3. **The table is read 5′→3′**, exactly the direction RNA is synthesised.

### Start and stop

| Signal | Codons | Meaning |
| --- | --- | --- |
| **Start** | **AUG** (universal) | Begin translation; specifies **methionine** — **fMet (formylmethionine)** in prokaryotes and organelles |
| **Stop** | **UAA (ochre), UAG (amber), UGA (opal)** | No amino acid; binds **release factors**, not tRNA |

**AUG is the only start codon** — but not every AUG *is* a start codon. Context decides: in prokaryotes, a **Shine–Dalgarno** sequence upstream positions the first AUG; in eukaryotes, the ribosome **scans from the 5′ cap** and typically initiates at the first AUG in a favourable **Kozak context**.

**Why there is no tRNA for stop codons:** stop codons are read by **protein release factors** (RF1/RF2 in bacteria; eRF1 in eukaryotes) that mimic tRNA shape and trigger hydrolysis of the finished polypeptide from the P-site tRNA — the ribosome's decoding centre cannot tell the difference until the "tRNA" turns out to carry a protein factor instead of an amino acid.

## The direction of synthesis: 5′→3′ reading, N→C building

Two antiparallel conventions that students routinely cross:

```
   mRNA read:      5′ ──────────────────▶ 3′
   polypeptide made:  N ────────────────▶ C
                      (amino terminus)     (carboxyl terminus)
```

The ribosome moves along mRNA **5′→3′**, and each new amino acid is added to the **C-terminus** of the growing chain. So the N-terminus is synthesised first — the **signal sequence that targets a protein to the ER is at the N-terminus and emerges from the ribosome first**, which is precisely why targeting can be co-translational (see [02 — Protein synthesis and trafficking organelles](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md)).

### Elongation in three repeated steps

```
   CODON READING — one cycle:

   1. DECODING (A site)
      aminoacyl-tRNA arrives as EF-Tu–GTP
            │ correct codon–anticodon match → GTP hydrolysis
            ▼
      tRNA accommodated into A site          (kinetic proofreading)

   2. PEPTIDYL TRANSFER (peptide bond)
      P-site peptidyl chain transferred onto A-site amino acid
      catalysed by 23S/28S rRNA               (ribozyme)
            ▼
      A site holds the lengthened chain; P site holds deacylated tRNA

   3. TRANSLOCATION
      EF-2 (eEF-2)–GTP moves ribosome ONE CODON (5′→3′)
            ▼
      empty tRNA → E site → released; new codon in A site; cycle repeats
```

**Energy per peptide bond:** 4 high-energy phosphate bonds (2 for each aminoacyl-tRNA charging: ATP → AMP + PPᵢ, counted twice as equivalents; plus GTP for delivery and GTP for translocation). Protein synthesis is one of the cell's largest energy expenditures — roughly half of all ATP in a growing bacterium.

## Polysomes: reading a message in parallel

A single mRNA can be simultaneously engaged by **many ribosomes**, spaced ~80 nucleotides apart:

```
   5′ ─▶ ●──▶ ●──▶ ●──▶ ●──▶ 3′
          │    │    │    │
         short medium  long  almost
         chain chain  chain  finished

   ● = ribosome;   each reads the same message independently
   → one mRNA, many copies of the protein, made at once
```

**Polysomes (polyribosomes)** multiply output without waiting for the first ribosome to finish. They are visible in electron micrographs and in sucrose gradients, and their spacing reflects elongation rate. In rough ER, polysomes sit in a characteristic rosette — the visual signature of secretory protein production.

## Initiation: the big prokaryotic vs eukaryotic split

| Feature | **Prokaryotic** | **Eukaryotic** |
| --- | --- | --- |
| **How the ribosome finds the message** | **Shine–Dalgarno sequence** (5′-AGGAGG-3′) base-pairs with 16S rRNA → start AUG positioned in P site | **5′ cap recognised by eIF4E** → ribosome **scans** to first AUG in **Kozak context** |
| **Start tRNA** | **fMet-tRNAᶠᴹᵉᵗ** (formylated) | **Met-tRNAᵢ** (initiator, not formylated) |
| **Start codon placement** | SD–16S pairing docks AUG directly | Scanning delivers AUG to P site |
| **Factors** | IF1, IF2 (GTPase), IF3 | eIFs (eIF2, eIF3, eIF4A/E/G, eIF5…) — ~12+ factors |
| **Subunit joining** | 30S + mRNA + IFs → 50S joins → 70S | 40S + ternary complex → cap-dependent → 60S joins → 80S |
| **Polycistronic messages** | Common (operons) | Rare — usually monocistronic |
| **Coupling to transcription** | Translation starts while mRNA is still being transcribed | Transcription, processing, export, then translation — spatially and temporally separated |

```
PROKARYOTIC INITIATION
   5′─…A G G A G G…─AUG─3′
          │   SD sequence pairs with 16S rRNA
          ▼
   30S binds → fMet-tRNA in P site → 50S joins → 70S start complex

EU KARYOTIC INITIATION
   m⁷G─cap─────────────AUG─3′
      │ eIF4E binds cap
      ▼
   40S SCANS 5′→3′ until first AUG in Kozak context → 60S joins → 80S
```

**Why the difference exists:** bacteria couple transcription and translation, so a ribosome can find the message by local sequence before the RNA is even finished. Eukaryotes export processed mRNA to the cytoplasm, so the message must be found by its **cap** — scanning is the only reliable way to locate the start on a long, structured, monocistronic message.

**Downstream control follows directly:** anything that blocks the cap (a strong 5′ UTR structure, a bound protein, a miRNA–RISC complex) blocks all translation of that message — the lever used by [06 — Gene regulation](06-gene-regulation.md).

## Co-translational targeting: the SRP decision

Proteins bound for the ER, secretion, or membranes are targeted **while still being synthesised**:

```
   ribosome begins on free mRNA
        │
        ▼  N-terminal SIGNAL SEQUENCE emerges
   SRP binds → translation PAUSES → ribosome docks on rough ER translocon
        │
        ▼
   translation RESUMES into the ER lumen; signal cleaved
```

The full mechanism, its folding consequences, and its diseases are in [02 — Protein synthesis and trafficking organelles](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md). The point here is that **the order of synthesis (N first) and the coupling of ribosome to membrane are two consequences of the same fact**: elongation proceeds N→C, so the address label is exposed first.

## Fidelity of translation

Three checkpoints, each analogous to a replication checkpoint:

| Step | Mechanism |
| --- | --- |
| **Aminoacyl-tRNA synthetase** | Selection **plus editing** — the only place amino acid identity is set ([03 — RNA and its three types](03-rna-and-its-three-types.md)) |
| **Codon–anticodon recognition** | Correct match stabilises the tRNA in the A site |
| **Kinetic proofreading (GTPase activation)** | Incorrect tRNAs dissociate before EF-Tu GTP hydrolysis commits accommodation; the ribosome spends GTP to buy time for rejection |

Overall error rate: ~1 wrong amino acid per 1000–10,000 incorporated — **much worse than replication (10⁻¹⁰)**, but far better than transcription. Organisms survive this because most single-residue changes are tolerated by a folded protein (see [03 — Proteins](../01-biochemistry/03-proteins.md) and [07 — Mutations](07-mutations.md)).

## The code's universality — and its exceptions

**Universal in practice:** the same codons mean the same amino acids in bacteria, plants, and humans — the reason a human gene can be expressed in *E. coli*, and a cornerstone of the evidence for common ancestry in [06 — Evolution](../06-evolution/).

**Documented exceptions:**

| Exception | Where | What changes |
| --- | --- | --- |
| **Mitochondrial code** | Human mitochondria | **UGA = Trp** (not stop); AGA/AGG = stop; AUA = Met |
| **Stop-codon reassignment** | *Mycoplasma*, some ciliates | UGA encodes Trp |
| **Selenocysteine** | All domains (humans too) | **UGA read as Sec** when a specific SECIS stem–loop is present in the mRNA + special tRNA |
| **Pyrrolysine** | Some archaea/bacteria | **UAG read as Pyl** with a dedicated tRNA |

**Selenocysteine is the medically relevant one:** human glutathione peroxidases and iodothyronine deiodinases require it; the "21st amino acid" is inserted by recoding a stop codon — proof that the code is *read in context*, not merely matched.

## Central dogma: the recap

```
            transcription                translation
   DNA ──────────────────▶ RNA ─────────────────────▶ PROTEIN
     ▲                        │                         │
     │   (repair, replication) │                         │
     └──────────────────────── ┘                         │
                                        (prions: protein → protein folding change)

   reverse transcription: RNA ──▶ DNA   (retroviruses, telomerase, retrotransposons)
   RNA replication:       RNA ──▶ RNA   (RNA viruses)
```

**The dogma states the allowed general flows of sequence information** — not that every cell uses all of them. Protein→protein (prion propagation) and RNA→DNA (reverse transcriptase) are the famous extensions; nothing encodes information *back* into protein sequence.

## Frameshifts vs substitutions: the two consequences

```
SUBSTITUTION (one base changed)
   …AUG GCU ACU UAA…
      Met Ala Thr Stop      → usually ONE amino acid altered or none

FRAMESHIFT (one base inserted or deleted)
   …AUG GCU ACU UAA…        original
   …AUG GCU AC[?]U AA…      after +1 insertion
      Met Ala ___ ___ ___    EVERYTHING downstream misread until
                             a new stop appears by chance
```

| | Substitution | Frameshift (±1, ±2 indel) |
| --- | --- | --- |
| **Scope** | One codon (or none, if silent) | **Entire downstream reading frame** |
| **Silent possibility** | Yes — especially at third positions | Essentially never |
| **Typical outcome** | Conservative or non-conservative single-residue change | Truncated, non-functional protein |
| **Classic disease** | Sickle cell (Glu→Val) | Cystic fibrosis ΔF508 (in-frame, for contrast), many Tay–Sachs cases (frameshift) |

An **in-frame insertion/deletion** (multiple of 3) adds or removes residues without shifting the frame — a third category that students forget exists.

## Medical relevance

**The ribosome is the most successful antibiotic target in medicine** — because the bacterial 70S machine differs from the eukaryotic 80S machine:

| Drug | Step blocked | Specificity |
| --- | --- | --- |
| **Tetracyclines** | Block aminoacyl-tRNA entry to the **A site** (30S) | Bacterial 30S |
| **Aminoglycosides** (gentamicin, streptomycin) | Cause **misreading** of the genetic code at the 30S decoding centre | Bacterial 30S; can cause ototoxicity via mitochondrial ribosomes |
| **Chloramphenicol** | Blocks **peptidyl transferase** (50S) | Bacterial 50S |
| **Macrolides** (erythromycin, azithromycin) | Block **translocation** / exit tunnel (50S) | Bacterial 50S |
| **Puromycin** | Mimics aminoacyl-tRNA → **premature chain release** | Research tool (all ribosomes) |
| **Cycloheximide, emetine** | Block eukaryotic translocation (60S / 40S) | Research tools; toxic to human cells |
| **Diphtheria toxin** | ADP-ribosylates **eEF-2** → eukaryotic elongation stops | Explains diphtheria's systemic toxicity |

**Read-through therapy:** **ataluren** promotes read-through of premature **nonsense (stop) mutations** in some genetic diseases (e.g. certain muscular dystrophies and cystic fibrosis nonsense variants) — pharmacology applied to the stop-codon logic itself.

**HIV depends on a programmed frameshift:** the *gag-pol* mRNA must be **−1 ribosomal frameshifting** at a specific slippery site to produce the Pol polyprotein at the right ratio. Antiretroviral research directly targets this translational recoding step — a case where a "mutation-like" event is a required, regulated part of a virus's life cycle.

**Prions** represent the only information flow the dogma excludes: misfolded **PrPˢᶜ** converts normal **PrPᶜ** into the pathological form — protein directing protein folding, with no nucleic acid intermediate.

**Mitochondrial translation disorders** (e.g. mutations in mitochondrial rRNAs or tRNAs) present as encephalomyopathy because organellar ribosomes are bacterial-type and uniquely vulnerable — the other side of the antibiotic selectivity coin.

```
CODE LOGIC                    →   CLINICAL MANIFESTATION
degeneracy (3rd base)         →   many SNPs are silent / conservative
premature stop                →   truncated protein → nonsense therapy (ataluren)
reading frame                 →   indels devastating unless in-frame
universal code                →   cross-species gene expression, gene therapy vectors
70S vs 80S                    →   antibiotic selectivity
```

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The ribosome reads DNA" | It reads **mRNA**; DNA never reaches the ribosome. |
| "Every AUG is a start codon" | AUG specifies Met everywhere; only AUG in the correct **initiation context** (Shine–Dalgarno / Kozak) starts translation. |
| "Stop codons code for an amino acid" | They bind **release factors**; no tRNA carries them, and no residue is added. |
| "Degenerate means ambiguous" | **Degenerate** = several codons, one amino acid; **unambiguous** = each codon, exactly one amino acid. Both are true simultaneously. |
| "The code is universal without exception" | Mitochondria, *Mycoplasma*, selenocysteine, and pyrrolysine are documented exceptions. |
| "Wobble allows any tRNA to read any codon" | Wobble is restricted to the **third codon position**; positions 1–2 are stringent. |
| "Proteins are made from the C-terminus" | They are made **N→C**; the ribosome reads mRNA 5′→3′. |
| "A frameshift is just a different spelling of a point mutation" | A point substitution changes one codon; a frameshift rewrites **every codon downstream**. |

## Key facts

- The code has **64 codons**: 61 sense + 3 stops; **AUG** is the start and encodes Met (**fMet** when initiating in prokaryotes/organelles).
- Properties: **triplet, non-overlapping, commaless, degenerate, unambiguous, nearly universal**.
- Codons are read **5′→3′**; the polypeptide grows **N→C**.
- **Degeneracy + wobble** explain why third-position substitutions are often silent and why fewer tRNAs than codons are needed.
- Stops — **UAA, UAG, UGA** — are read by **release factors**, not tRNAs.
- Prokaryotic initiation uses the **Shine–Dalgarno sequence** and **fMet-tRNA**; eukaryotic initiation uses **cap-dependent scanning** and a **Kozak-context AUG**.
- Elongation cycle: **decoding (GTP)** → **peptidyl transfer (rRNA)** → **translocation (GTP)**; ~4 high-energy bonds per peptide bond.
- **Polysomes** let many ribosomes read one mRNA at once.
- SRP targeting is possible **because synthesis proceeds N→C**, exposing the signal sequence first — see [02 — Cell biology](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md).
- Exceptions to universality: **mitochondrial code, selenocysteine (UGA), pyrrolysine (UAG)**.
- Central dogma: DNA → RNA → protein, with reverse transcription and RNA replication as defined exceptions.

## Practice questions

**1. The start codon AUG in prokaryotes specifies which amino acid at initiation?**

A. Methionine only
B. Formylmethionine
C. N-formylalanine
D. Any amino acid, since context determines the residue

**Answer: B**

Explanation: In bacteria and organelles the initiator Met-tRNA carries a formyl group on the amino group, so the first residue is N-formylmethionine (fMet); the formyl group is often removed later by deformylase. Eukaryotic initiation uses unformylated Met-tRNAᵢ, so only methionine is placed. The formyl group is what lets the cell distinguish the initiating residue from internal methionines.

---

**2. Which feature of the genetic code explains why many point mutations have no phenotypic effect?**

A. The code is non-overlapping
B. Degeneracy — most amino acids are specified by more than one codon, often differing at the third position
C. The code is read 5′→3′
D. Stop codons have no tRNA

**Answer: B**

Explanation: Because several codons share one amino acid, a substitution that changes only the third position frequently still specifies the same residue — a silent mutation. Non-overlap (A), reading direction (C), and the absence of stop tRNAs (D) are true properties but do not buffer against base changes.

---

**3. The ribosome reads mRNA in which direction while the polypeptide grows in which direction?**

A. mRNA 3′→5′; polypeptide C→N
B. mRNA 5′→3′; polypeptide N→C
C. mRNA 5′→3′; polypeptide C→N
D. mRNA 3′→5′; polypeptide N→C

**Answer: B**

Explanation: All nucleic acid polymerases and the ribosome's translocation movement follow 5′→3′ along the template, and each new amino acid is added to the carboxyl end of the growing chain — so the N-terminus appears first. This is also why N-terminal signal sequences emerge first and can be recognised by SRP during synthesis.

---

**4. What distinguishes prokaryotic from eukaryotic translation initiation?**

A. Prokaryotes scan from a 5′ cap; eukaryotes use a Shine–Dalgarno sequence
B. Prokaryotes use Shine–Dalgarno base pairing with 16S rRNA; eukaryotes recognise the 5′ cap and scan to the first AUG
C. Both use identical mechanisms; only the ribosome size differs
D. Eukaryotes initiate directly at the 3′ end

**Answer: B**

Explanation: Bacterial messages carry an AGG-rich Shine–Dalgarno sequence that base-pairs with 16S rRNA and positions the start AUG; eukaryotic messages are monocistronic and capped, so the 40S subunit binds the cap and scans 5′→3′ to the first AUG in a Kozak context. Getting the two mechanisms reversed is the classic error — the options are designed to test exactly that.

---

**5. A single nucleotide inserted near the start of a coding sequence is most likely to cause**

A. A silent mutation
B. A conservative amino acid substitution
C. A frameshift altering every downstream codon
D. No change, because the ribosome skips the insertion

**Answer: C**

Explanation: Because the code is non-overlapping and commaless, the reading frame is fixed from the start codon; a +1 insertion shifts every triplet downstream, producing a completely different sequence until a chance stop codon appears — usually yielding a truncated, non-functional protein. Silent changes require substitutions, usually at wobble positions; the ribosome has no mechanism to skip bases.

---

**6. Which of the following is an exception to the universality of the genetic code?**

A. AUG encoding methionine
B. UGA encoding tryptophan in human mitochondria
C. The use of triplets in all organisms
D. Stop codons signalling termination in bacteria

**Answer: B**

Explanation: Human mitochondrial translation reads UGA as tryptophan rather than as a stop, and AGA/AGG serve as stops — a well-documented deviation in an organelle with a reduced genome. AUG (A), triplets (C), and bacterial stop signals (D) are conserved features of the standard code, not exceptions.

---

**7. Release factors are required at termination because**

A. Stop codons cannot base-pair with any tRNA
B. Stop codons require a special amino acid to be added
C. The ribosome must be recycled immediately
D. GTP is needed to remove the mRNA

**Answer: A**

Explanation: No tRNA has an anticodon complementary to UAA, UAG, or UGA, so the decoding site instead accepts protein release factors that mimic tRNA shape; their binding triggers hydrolysis of the polypeptide from the P-site tRNA, releasing the finished chain. No residue is added (B), and while recycling follows, it is not why release factors exist.

---

**8. Why can a human gene be correctly translated in a bacterium?**

A. Bacterial ribosomes read DNA directly
B. The genetic code is nearly universal, and Shine–Dalgarno/Kozak differences can be engineered around
C. Human proteins are identical to bacterial proteins
D. Bacteria splice human introns automatically

**Answer: B**

Explanation: Shared codon meanings let the same triplet specify the same amino acid across domains of life — the practical foundation of recombinant protein production. Expression vectors do need to supply a bacterial promoter and Shine–Dalgarno site, and intron-containing constructs must use cDNA, because bacteria lack the spliceosome (D). Ribosomes read mRNA, not DNA (A).

---

**9. Tetracycline inhibits bacterial protein synthesis by**

A. Blocking peptidyl transferase
B. Blocking aminoacyl-tRNA entry into the A site
C. Inhibiting translocation
D. ADP-ribosylating elongation factor 2

**Answer: B**

Explanation: Tetracyclines bind the 30S subunit and occlude the A site so that aminoacyl-tRNAs cannot be delivered, halting elongation at the decoding step. Peptidyl transferase blockade describes chloramphenicol (A); translocation blockade describes macrolides (C); ADP-ribosylation of eEF-2 is diphtheria toxin (D), which acts on human ribosomes and is not an antibiotic mechanism.

---

**10. Which statement about polysomes is correct?**

A. Several ribosomes translate different mRNAs while sharing one tRNA pool
B. Many ribosomes simultaneously translate the same mRNA, increasing output per message
C. Polysomes form only during translation termination
D. Each polysomal ribosome reads a different region of genetic code unique to it

**Answer: B**

Explanation: A polysome is one mRNA with multiple ribosomes in transit at different points along it, each producing a separate polypeptide — a way of multiplying protein output without making more mRNA. They are most active during elongation, not termination (C); the code each ribosome reads is the same sequence, just at different times (D).
