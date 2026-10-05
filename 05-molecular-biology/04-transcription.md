# Transcription

## Why it matters

Replication copies the **whole genome** for the next generation; transcription copies **one gene, on demand, in one cell**. A liver cell and a neuron carry identical DNA — every difference between them is a difference in **which genes are transcribed, when, and how much**. Transcription is therefore the step at which an identical genome produces genuinely different biology, and its control is the subject of [06 — Gene regulation](06-gene-regulation.md).

Transcription also creates the substrate for the entire post-transcriptional layer: splicing, capping, and polyadenylation happen here, and alternative splicing is why ~20,000 human genes can specify far more than 20,000 proteins.

Mechanistically, this chapter hinges on one comparison — RNA polymerase does almost everything DNA polymerase does, but **without a primer, without a separate template-opening machine, and with much lower fidelity**. Each of those differences has a consequence you can predict.

## RNA polymerase vs DNA polymerase

| Property | DNA polymerase | RNA polymerase |
| --- | --- | --- |
| **Primer required** | **Yes** — needs a free 3′-OH from RNA primase | **No** — can start *de novo* |
| **Template opening** | Requires helicase and SSB | **Opens ~12–14 bp of DNA itself** (transcription bubble) |
| **Direction of synthesis** | 5′→3′ | **5′→3′** (the one thing they share) |
| **Product** | DNA, permanent | RNA, disposable |
| **Fidelity** | ~10⁻¹⁰ with proofreading and mismatch repair | **~10⁻⁴ to 10⁻⁵** — little or no proofreading |
| **Proofreading** | 3′→5′ exonuclease, plus mismatch repair | Limited; errors are tolerable because transcripts are transient and many copies are made |
| **Product removed/finished** | Primers removed, fragments ligated | RNA released; DNA re-anneals behind the enzyme |
| **On a double-stranded template** | Both strands copied | **Only one strand (the template strand) read for a given gene** |

**Why lower fidelity is acceptable:** one gene is transcribed hundreds to thousands of times, so an occasional wrong nucleotide is diluted by many correct copies. DNA, copied once and copied again, has no such buffer. **Error tolerance is proportional to redundancy** — a principle that shows up again in immune diversification and in RNA virus mutation rates.

## The gene, as a unit

A transcribed unit is defined by more than the protein-coding stretch:

```
        PROMOTER           TRANSCRIBED REGION                 TERMINATOR
   ┌─────────────────┐  5′UTR ─ EXON ─ INTRON ─ EXON ─ 3′UTR  ────────
   │ −35  −10   +1   │    │                                  │
   └─────────────────┘    └── untranslated but transcribed ───┘
                     ↑
                start site (+1)
```

| Element | What it is |
| --- | --- |
| **Promoter** | Where the machinery assembles; sets **which strand** and **which direction** |
| **Transcribed region** | Everything copied into RNA — exons, introns, and UTRs |
| **Exon / Intron** | Exon retained in the mature RNA; intron spliced out |
| **5′/3′ UTR** | Transcribed and (in mRNA) untranslated, with regulatory roles |
| **Terminator** | Sequence that signals release of the transcript |

**Which strand is which:** only one strand is copied per gene — the **template strand** (read 3′→5′, so RNA is made 5′→3′). The other is the **coding strand**, whose sequence matches the RNA (except T/U). The promoter determines which strand is used, so genes on opposite strands can overlap.

## Prokaryotic promoters and initiation

Bacterial RNA polymerase is a **holoenzyme**: core enzyme (α₂ββ′ω) + **sigma (σ) factor**. Sigma is what recognises the promoter; without it the core enzyme binds DNA anywhere and transcribes indiscriminately.

| Element | Consensus (E. coli) | Function |
| --- | --- | --- |
| **−35 region** | **TTGACA** | Initial recognition by σ⁷⁰ |
| **−10 region (Pribnow box)** | **TATAAT** | **AT-rich** → base pairs melt easily → open complex forms |

```
 −35        −10                +1
 TTGACA … TATAAT ──────────── AUG…
   │         │
 sigma binds │  DNA melts here (A–T rich)
             ▼
 CLOSED complex ──▶ OPEN complex (transcription bubble ~12–14 bp)
                        │
                        ▼
                  first phosphodiester bonds made
                        │
                        ▼
                  σ FACTOR RELEASED → elongation
                        │
                        ▼
                  core enzyme continues; σ recycled for more initiations
```

**Three properties of the promoter are worth noting:**

1. **Numbers run upstream as negative** — −10 and −35 are ten and thirty-five bases *before* the +1 start site.
2. **A–T richness is functional**, exactly as in replication origins ([01 — DNA structure](01-dna-structure.md)): weaker base pairing lets the strands separate at physiological temperature.
3. **Sigma is released after initiation** — it can be reused at another promoter, and **promoter strength (how often initiation occurs) is the primary control point in bacteria**.

## Eukaryotic promoters and the general transcription factors

Eukaryotic RNA polymerases come in three main forms:

| Polymerase | Product | Sensitivity to **α-amanitin** |
| --- | --- | --- |
| **RNA polymerase I** | rRNA (28S, 18S, 5.8S) | Resistant |
| **RNA polymerase II** | **mRNA precursor**, plus most snRNAs | **Strongly inhibited** (low dose) |
| **RNA polymerase III** | tRNA, 5S rRNA | Inhibited at high dose |

Polymerase II is the mRNA machine, and its promoter logic is built from a **core promoter** plus **general transcription factors (GTFs)**:

```
     ENHANCER (far away, either direction)
           │  DNA loops so the enhancer contacts the promoter
           ▼
   ─── 50–200 bp upstream ─── TATA BOX (~ −25) ── +1 ───
                                   │
                          TBP (subunit of TFIID) bends DNA
                                   │
                  TFIIA, TFIIB, TFIIF+Pol II, TFIIE, TFIIH assemble
                                   │
                          PRE-INITIATION COMPLEX (PIC)
                                   │
             TFIIH helicase opens DNA; Pol II escapes → elongation
                                   │
                          Pol II CTD is phosphorylated (Ser5)
```

| Component | Role |
| --- | --- |
| **TATA box** (consensus TATAAA, ~−25) | Bends and melts DNA; bound by **TBP** (TATA-binding protein, a subunit of TFIID) |
| **TFIID / TBP** | First factor bound; positions the machinery on the start site |
| **TFIIH** | Has **helicase** activity (opens DNA) and **kinase** activity (phosphorylates the Pol II CTD) — the release trigger |
| **C-terminal domain (CTD)** of Pol II | Phosphorylation state determines which processing enzymes are recruited — unphosphorylated for initiation, Ser5-phosphorylated for capping, Ser2-phosphorylated for elongation and polyadenylation |
| **Enhancers/silencers** | Distant regulatory sequences that loop in — see [06 — Gene regulation](06-gene-regulation.md) |

**Not every gene has a TATA box**; many rely on CpG islands and other core elements. TATA-containing promoters tend to be developmentally regulated, precisely regulated, and tissue-restricted.

## Elongation

Once initiated, elongation is conceptually simple and mechanically demanding:

```
        polymerase →
   5′ ════════════╗
                  ║  transcription bubble (~12–14 bp)
   3′ ════════════╝
                  │
        behind: reannealed DNA
        ahead:  positive supercoils build up → TOPISOMERASE relieves them
```

- The enzyme unwinds ahead and DNA re-anneals behind — no permanent separation, no SSB needed.
- The RNA transcript peels off as it emerges; the RNA–DNA hybrid exists only within the bubble.
- **Topoisomerases** relieve the positive supercoils transcription generates — the same problem, and the same solution, as at the replication fork.
- Rate: ~40–80 nt/s in bacteria; slower in eukaryotes, which must traverse nucleosomes.

## Termination: two prokaryotic mechanisms, one eukaryotic logic

### Rho-independent (intrinsic) termination

```
   …GC-rich sequence with an internal palindrome ── followed by a run of Us…
                       │
                       ▼
   RNA folds into a STEM–LOOP (hairpin), then
   rU · dA hybrid (very weak, 2 H-bonds, non-standard geometry)
                       │
                       ▼
   polymerase pauses → hybrid melts → transcript and enzyme released
```

### Rho-dependent termination

**Rho (ρ) factor**, a ring-shaped ATP-dependent helicase, binds **rut** (rho utilization) sites on the nascent RNA, translocates 5′→3′, and when the polymerase pauses, **unwinds the RNA–DNA hybrid** to release the transcript.

### Attenuation — regulation disguised as termination

In the *trp* leader, ribosome position decides which of two hairpins forms, so the polymerase either terminates early or reads through — a **regulatory** use of termination, covered in [06 — Gene regulation](06-gene-regulation.md).

### Eukaryotic termination: coupled to polyadenylation

Termination signals are **within the transcript**, not in the DNA:

```
   …A A U A A A (polyadenylation signal) → cleavage site → GU-rich
                     │
                     ▼
        CPSF and CstF bind the pre-mRNA
                     │
                     ▼
        transcript CLEAVED ~10–30 nt downstream
                     │
                     ├──▶ upstream piece: POLY-A POLYMERASE adds ~200 A
                     │
                     └──▶ polymerase still transcribing until
                          "torpedo" 5′→3′ exonuclease (Xrn2) catches up
                          (or allosteric change) → RELEASE
```

So in eukaryotes **cleavage and polyadenylation are the termination signal**; the polymerase is not told to stop by a DNA sequence directly.

## RNA processing: primary transcript → mature mRNA

Eukaryotic **primary transcript (pre-mRNA, also called hnRNA)** must be processed before export. Three modifications:

### 1. 5′ cap

A **7-methylguanosine** linked by an unusual 5′→5′ triphosphate bridge, added when the transcript is ~20–30 nt long (recruited by the phosphorylated Pol II CTD).

**Functions:** protects from 5′ exonuclease; required for **nuclear export**; required for **ribosome recognition and scanning** (see [05 — Translation and the genetic code](05-translation-and-the-genetic-code.md)); required for efficient splicing of the first intron.

### 2. 3′ poly-A tail

Added by **poly-A polymerase** after cleavage at the AAUAAA-driven site. Functions: export, stability, translation initiation; **tail shortening is the timer for mRNA decay**.

### 3. Splicing

```
   EXON1 ──GU────AG── EXON2 ──GU────AG── EXON3
            │ intron │        │ intron │
            ▼
        SPLICEOSOME (U1, U2, U4, U5, U6 snRNPs + proteins)
            │
            ├── U1 base-pairs with 5′ splice site (GU)
            ├── U2 binds the branch-point A
            ├── snRNPs catalyse TWO transesterifications:
            │      step 1: branch-point A attacks 5′ site → LARIAT
            │      step 2: 5′ exon attacks 3′ site (AG) → exons joined
            ▼
        EXON1─EXON2─EXON3   +   free lariat (degraded)
```

| Feature | Detail |
| --- | --- |
| **Signals** | **GU at the 5′ splice site, AG at the 3′ site** — nearly universal (the "GU–AG rule") |
| **Branch point** | An adenine ~18–40 nt upstream of the 3′ site, nucleophile for the first step |
| **Catalyst** | **RNA** — snRNPs make the spliceosome another ribozyme machine |
| **Lariat** | The excised intron forms a loop; it is debranched and degraded |

**Self-splicing introns** (Group I and II) catalyse their own removal with no protein machinery — the evolutionary ancestors of the spliceosome and further evidence for the RNA world (see [06 — Evolution](../06-evolution/)).

### Alternative splicing: one gene, many proteins

```
                     ┌─ EXON 1 + 2 + 3 + 4 ─▶ isoform A (full length)
   same pre-mRNA ────┼─ EXON 1 + 2 + 4 ─────▶ isoform B (skips exon 3)
                     ├─ EXON 1 + 3 + 4 ─────▶ isoform C (skips exon 2)
                     └─ alternative start / 3′ UTR ─▶ tissue-specific variants
```

- ~95 % of human multi-exon genes are alternatively spliced.
- **Calcitonin vs CGRP** — one gene, a thyroid hormone in one tissue and a neuropeptide in another.
- **Drosophila Dscam** — one gene, >38,000 mRNA variants.
- Disease link: **spinal muscular atrophy** — survival depends on including exon 7 of *SMN2*; **nusinersen** is an antisense oligonucleotide that increases its inclusion (see Medical relevance).

## Transcription vs replication: the contrast to hold

| Feature | Replication | Transcription |
| --- | --- | --- |
| **Purpose** | Duplicate the genome | Copy one gene for use |
| **When** | S phase only | Continuously, gene-specific |
| **Template** | **Both** strands, entire molecule | **One strand**, one gene at a time |
| **Enzyme** | DNA polymerase (+ primase, helicase…) | RNA polymerase |
| **Primer** | Required (RNA) | **Not required** |
| **Fidelity** | ~10⁻¹⁰ | ~10⁻⁴–10⁻⁵ |
| **Product** | Permanent DNA | **Disposable RNA** |
| **Base pairing** | A–T, G–C (DNA) | A–U, T–A, G–C, C–G |
| **Outcome** | Two identical duplexes | mRNA precursor → processed mRNA |

**Both share:** 5′→3′ synthesis and a need for topoisomerase relief — polymerases colliding on the same DNA are resolved by prioritisation.

## Transcription in organelles: the RNA world still running

Mitochondria and chloroplasts have their own genomes, transcribed by machinery that is **bacterial in character**:

| Feature | Chloroplast | Mitochondrion |
| --- | --- | --- |
| **RNA polymerase** | Bacterial-type multi-subunit enzyme plus a phage-like single-subunit enzyme; **σ factors** required | **Phage-like single-subunit polymerase** (TEF subunit supplied by the nucleus) |
| **Transcription units** | Operon-like, polycistronic | Operon-like, polycistronic (heavy and light strands) |
| **Translation of products** | **70S ribosomes**, bacterial-type | **70S ribosomes**, bacterial-type |

This is the endosymbiotic legacy: transcription and translation inside these organelles look like a bacterium's, which is why antibiotics targeting 70S ribosomes or bacterial polymerases can have mitochondrial side effects (see [04 — Energy and containment organelles](../02-cell-biology/04-energy-and-containment-organelles.md)).

## Medical relevance

**Rifampicin (rifampin)** binds the **β subunit of bacterial RNA polymerase**, blocking the elongation path — the backbone of tuberculosis therapy, with resistance mapping to *rpoB* mutations. Human polymerases are unaffected.

| Drug | Target | Use / toxicity |
| --- | --- | --- |
| **Rifampicin** | Bacterial RNA polymerase β | Tuberculosis, leprosy; induces hepatic enzymes (drug interactions) |
| **Actinomycin D** | Intercalates DNA, blocks elongation | Childhood cancers; toxic everywhere — blocks transcription in all cells |
| **α-Amanitin** (death cap) | **RNA polymerase II** | Fatal liver failure, no antidote — explains *Amanita* poisoning |
| **Cordycepin** | 3′-deoxyadenosine — chain terminator | Research tool showing why a missing 3′-OH stops synthesis |
| **Fludarabine, 5-azacytidine** | Nucleoside analogues | Cancer; azacytidine also inhibits methyltransferases → an *epigenetic* drug |

**Splicing is a drug target in its own right.** **Nusinersen** for spinal muscular atrophy acts by blocking an intronic splicing silencer so that exon 7 of *SMN2* is included — a splicing decision turned into a therapy. Mis-splicing also underlies many cancers and **β-thalassaemia** variants that create or destroy splice sites.

**Why α-amanitin poisoning is "a liver disease":** the toxin is absorbed from the gut, and hepatocyte RNA polymerase II cannot be replaced fast enough — so the picture is acute hepatic necrosis. The organ affected is the one whose cells depend most on the blocked process.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "RNA polymerase needs a primer" | It does not — it initiates **de novo**, which is why primase is only needed for DNA replication. |
| "Both strands are transcribed" | For a given gene, **one strand is the template**; the other is the coding strand. Different genes may use either strand. |
| "−10 and −35 are positions within the gene" | They are **upstream** of the +1 start site, in the promoter. |
| "Introns are junk" | They are removed but enable **alternative splicing**, regulation, and evolution of new exon combinations. |
| "The poly-A tail is encoded in DNA" | It is added enzymatically after cleavage; **no DNA template encodes it** (same for the 5′ cap). |
| "Eukaryotic termination works like the bacterial hairpin" | Eukaryotic Pol II termination is triggered by **cleavage/polyadenylation** of the transcript, often with torpedo exonuclease catch-up. |
| "Transcription is as accurate as replication" | It is **10⁵–10⁶ times less accurate** — acceptable because transcripts are disposable and made in many copies. |
| "The spliceosome is a protein machine" | It is an **RNA machine** (snRNPs) with associated proteins — catalysis is RNA-based. |

## Key facts

- **RNA polymerase needs no primer**, opens its own transcription bubble, synthesises **5′→3′**, and has **low fidelity (~10⁻⁴–10⁻⁵)** — acceptable because transcripts are transient and numerous.
- Bacterial initiation: **σ factor** recognises **−35 (TTGACA)** and **−10 (TATAAT, Pribnow)**; A–T richness lets DNA melt; σ is released after initiation.
- Eukaryotic mRNA synthesis uses **RNA polymerase II**; the **TATA box (~−25)** is bound by **TBP/TFIID**, general factors assemble the pre-initiation complex, and **TFIIH** opens DNA and phosphorylates the **CTD**.
- The **gene unit** = promoter + transcribed region (exons, introns, UTRs) + terminator; only the **template strand** is copied.
- Prokaryotic termination: **rho-independent hairpin + rU·dA hybrid** or **rho-dependent** unwinding; attenuation uses hairpin choice as a regulatory switch.
- Eukaryotic termination is triggered by the **AAUAAA polyadenylation signal → cleavage → poly-A addition**, with polymerase released afterwards.
- Processing of pre-mRNA: **5′ 7-methylguanosine cap**, **3′ poly-A tail**, and **splicing** (GU–AG rule, lariat intermediates, RNA-catalysed spliceosome).
- **Alternative splicing** allows one gene to produce multiple protein isoforms — the main reason protein diversity exceeds gene number.
- Transcription vs replication: one vs both strands, no primer vs primer, low vs extreme fidelity, disposable vs permanent product.
- Organelle transcription is **bacterial/phage-like** and their ribosomes are **70S** — the structural basis of antibiotic mitochondrial toxicity.

## Practice questions

**1. Which of the following is TRUE of RNA polymerase but NOT of DNA polymerase?**

A. Synthesises in the 5′→3′ direction
B. Requires an RNA primer to begin
C. Can initiate synthesis de novo without a primer
D. Uses base pairing to read the template

**Answer: C**

Explanation: RNA polymerase starts from nothing, laying the first nucleotides onto the DNA directly; DNA polymerase strictly requires a pre-existing 3′-OH supplied by primase. Both enzymes synthesise 5′→3′ (A), both read their template by base pairing (D), and only DNA polymerase needs a primer (B). The ability to initiate de novo is exactly why primers are needed for DNA replication and not for transcription.

---

**2. The −10 (Pribnow) region of a bacterial promoter is functionally important because it is**

A. Where the RNA polymerase binds most tightly after initiation
B. A–T rich, so the two DNA strands separate readily to form the open complex
C. The site of the 5′ cap addition
D. Where the terminator hairpin forms

**Answer: B**

Explanation: The consensus TATAAT is adenine–thymine rich, and A–T pairs have only two hydrogen bonds, so this region melts at physiological temperature — the nucleation point for the transcription bubble. Sigma factor initially contacts both −35 and −10, but melting initiates at −10. Caps are added to RNA (C) and terminators act far downstream (D).

---

**3. In eukaryotes, which event directly triggers release of RNA polymerase II from the gene?**

A. Binding of sigma factor
B. Formation of a GC-rich hairpin in the DNA template
C. Cleavage of the pre-mRNA at the polyadenylation signal followed by poly-A addition, with polymerase release (often by a torpedo exonuclease)
D. Base pairing of the transcript with the template strand throughout the gene

**Answer: C**

Explanation: Eukaryotic Pol II reads through the polyadenylation signal (AAUAAA); the transcript is then cleaved, poly-A polymerase extends the upstream fragment, and termination follows — frequently because the 5′→3′ exonuclease Xrn2 degrades the remaining downstream RNA and catches the polymerase. Bacterial hairpins (B) and sigma release (A) belong to prokaryotic mechanisms.

---

**4. Which statement best explains why RNA polymerase can have much lower fidelity than DNA polymerase?**

A. RNA is chemically stronger than DNA
B. Transcripts are made repeatedly and are disposable, so individual errors are diluted
C. RNA polymerase has superior proofreading
D. Errors in RNA can be repaired by mismatch repair

**Answer: B**

Explanation: A gene is transcribed hundreds to thousands of times, and each transcript has a short life, so a rare misincorporation has little effect on total protein output. DNA is copied once per division and must persist, so errors become permanent — hence the three-layer fidelity system. RNA polymerase has limited proofreading (C) and RNA errors are not repaired by mismatch repair (D); chemical strength (A) favours DNA, not RNA.

---

**5. The spliceosome removes introns by**

A. Hydrolysing the intron with a protein nuclease
B. Two transesterification reactions catalysed by snRNAs, forming a lariat intermediate
C. Cutting the DNA before transcription
D. Degrading the transcript and rebuilding it

**Answer: B**

Explanation: U1 recognises the 5′ GU site, U2 binds the branch-point adenine, and the snRNPs catalyse two RNA-based transesterifications — first forming a lariat, then joining the exons. No protein nuclease cuts the RNA (A), the DNA is untouched (C), and the transcript is not rebuilt (D). The chemistry confirms that the spliceosome is a ribozyme machine.

---

**6. A gene contains four exons. Tissue A includes all four; tissue B skips exon 3. This phenomenon is called**

A. Alternative splicing
B. Frameshift mutation
C. RNA editing
D. Attenuation

**Answer: A**

Explanation: One primary transcript yielding different mature mRNAs by including or skipping exons is alternative splicing — the main mechanism by which ~20,000 human genes produce far more protein isoforms. A frameshift (B) results from insertions/deletions in the coding sequence; RNA editing changes individual bases; attenuation (D) is a prokaryotic transcription-attenuation mechanism.

---

**7. Which RNA polymerase synthesises mRNA precursors in eukaryotes and is strongly inhibited by α-amanitin?**

A. RNA polymerase I
B. RNA polymerase II
C. RNA polymerase III
D. Mitochondrial RNA polymerase

**Answer: B**

Explanation: Pol II transcribes protein-coding genes (and most snRNAs) and is the enzyme blocked at low α-amanitin concentrations — which is why death-cap mushroom poisoning presents as catastrophic liver failure. Pol I makes the large rRNAs and is resistant; Pol III makes tRNA and 5S rRNA and is affected only at high doses.

---

**8. Why is the A–T rich −10 region functionally significant rather than merely a sequence It recruits mismatch repair

**Answer: B**

Explanation: A–T pairs have two hydrogen bonds versus three for G–C, so this region denatures at physiological temperature — providing the nucleation site for the transcription bubble without requiring a separate helicase. It lies upstream of the coding sequence so it codes for nothing (A), capping happens on the RNA (C), and repair is irrelevant here (D).

---

**9. Rifampicin treats tuberculosis because it**

A. Inhibits bacterial 70S ribosomes
B. Binds bacterial RNA polymerase and blocks elongation, sparing human polymerases
C. Intercalates into DNA and prevents unwinding
D. Prevents mRNA splicing in bacteria

**Answer: B**

Explanation: Rifampicin fits a pocket in the β subunit of bacterial RNA polymerase and physically blocks the exit path of the emerging transcript, arresting elongation. Human RNA polymerases have a different structure and are not affected — the selectivity principle again. Bacteria have no spliceosome (D); ribosome inhibition describes aminoglycosides and macrolides (A); intercalation describes actinomycin D (C).

---

**10. The 5′ cap and poly-A tail on a eukaryotic mRNA are important because they**

A. Increase the coding sequence length
B. Protect the message from exonucleases and are required for export and translation initiation
C. Are needed for splicing of every intron
D. Determine the amino acid sequence

**Answer: B**

Explanation: The cap blocks 5′ exonucleases and is recognised by initiation factors for cap-dependent scanning; the poly-A tail blocks 3′ exonucleases and, through PABP interacting with the cap, promotes circularisation and translation. Both promote nuclear export. Neither is encoded by the gene (A), neither determines codons (D), and although the cap helps splice the first intron, they are not required for every intron (C).
