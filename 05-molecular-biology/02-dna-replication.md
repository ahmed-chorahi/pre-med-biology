# DNA Replication

## Why it matters

A human cell must copy roughly **6 × 10⁹ base pairs** once per division — and copy them almost perfectly, because every cell in the body carries the same instruction set and a copied error becomes permanent. Replication is therefore not merely a duplication event; it is the **highest-volume, highest-fidelity chemical process in the body**, and its machinery sets the error rate that everything downstream (mutation, cancer, evolution) inherits.

The mechanism also explains the first permanent question of genetics: how two identical daughter cells arise from one parent. That question is answered at the molecular level here and at the chromosomal level in [10 — The cell cycle and its checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) and [13 — Mitosis vs meiosis](../03-cellular-processes/13-mitosis-vs-meiosis.md).

This chapter builds directly on [01 — DNA structure](01-dna-structure.md): complementary pairing makes each strand a template, and the 5′→3′ chemistry of the backbone forces the entire architecture of the fork.

## Semiconservative replication: the Meselson–Stahl experiment

Three models were conceivable in 1958:

```
CONSERVATIVE              SEMICONSERVATIVE           DISPERSIVE
(old duplex kept,          each daughter duplex       both strands patched
 new duplex made)          = one old + one new strand with old/new mix
                                                  
 parent:  ═══             parent:  ═══              parent:  ═══
          ═══                       ═══                       ═══
                 ──▶                          ──▶
 gen 1:  ═══    ═══               ═══  ═══              ┌──╂──┐
          ═══    ═══               ═══  ═══              └──╂──┘
                                                            
```

**Meselson and Stahl** grew *E. coli* for many generations in heavy nitrogen (¹⁵N), shifted them to normal ¹⁴N, and separated DNA by caesium chloride density-gradient centrifugation.

| Generation | Predicted if semiconservative | Observed |
| --- | --- | --- |
| **0 (all ¹⁵N)** | One heavy band | One heavy band — matches |
| **1 (one round in ¹⁴N)** | One **hybrid** band (intermediate density) | One intermediate band — matches; eliminates conservative |
| **2** | **Half hybrid, half light** | Two bands, 1 : 2 ratio of hybrid : light — matches; eliminates dispersive |

**Why generation 2 was decisive:** conservative replication would have produced a heavy band and a light band at generation 1 — two bands, not one. Dispersive replication would have produced a single band that got progressively lighter forever, never a discrete hybrid. Only semiconservative replication predicts exactly what was seen.

**The experimental logic is worth holding onto:** *density labelling turns a molecular question into a physical-separation question.* The same trick — isotopes plus separation — is used throughout biochemistry.

## Origins, replicons, and the fork

| Feature | Prokaryote (e.g. *E. coli*) | Eukaryote |
| --- | --- | --- |
| **Origin** | Single **oriC** | **Thousands** of origins, licensed in G1 |
| **Unit of replication** | The whole circular chromosome = one replicon | Each origin fires its own **replicon** |
| **Forks per origin** | Two, **bidirectional** | Two, bidirectional |
| **Completion** | Forks meet opposite the origin | Forks meet neighbouring replicons and **fuse** |
| **Topology** | Circular — no ends problem | Linear — **telomere problem** |
| **Speed** | ~1000 bases/s | ~50 bases/s (hence the need for many origins) |

```
                      ◀── fork            fork ──▶
                   (lagging)           (leading)
       ═══════════════╪════════════════╪═══════════════
                      │    ORIGIN      │
       ═══════════════╪════════════════╪═══════════════
                   (leading)          (lagging)
                      ◀── fork            fork ──▶

     one origin → two forks moving apart → the replicon is copied from the middle out
```

## The machinery of the fork

| Enzyme / factor | Job | Why it is needed |
| --- | --- | --- |
| **Helicase** | Unwinds the duplex at the fork, using ATP | The two strands must be separated before they can be read |
| **Single-strand binding proteins (SSB)** | Coat the exposed single strands | Prevent re-annealing and protect from nucleases; keep the template extended |
| **Topoisomerase** | Relieves **supercoiling** ahead of the fork (gyrase = topoisomerase II in bacteria) | Unwinding one part overwinds the next; without relief the fork would stall |
| **Primase** | Lays down a short **RNA primer** (5′→3′) | DNA polymerase cannot start a strand from nothing — it needs a pre-existing 3′-OH |
| **DNA polymerase III** | The main replicative polymerase: extends primers 5′→3′ using the template | Bulk synthesis of both strands |
| **DNA polymerase I** | Removes RNA primers (**5′→3′ exonuclease**) and fills the gaps with DNA | Primers must be replaced before the strand is a continuous DNA molecule |
| **DNA ligase** | Seals the remaining **nick** with a phosphodiester bond | Okazaki fragments must be joined into one strand |
| **Sliding clamp (β clamp / PCNA)** | Tethers the polymerase to the template | Raises processivity — thousands of nucleotides added without falling off |

**The division of labour is the point:** unwinding, stabilising, relaxing, priming, polymerising, gap-filling, and sealing are separate jobs done by separate enzymes. A defect in any one of them produces a distinct clinical picture.

## The 5′→3′ problem: why one strand is copied backwards

DNA polymerase adds nucleotides **only to a free 3′-OH** — it therefore synthesises strictly **5′→3′**. But the two template strands are antiparallel, so at a fork moving in one direction, only one new strand can be made continuously.

```
                 fork moves →
       ┌──────────────────────────────────┐
       │                                  │
5′ ════╪════════════════════════════ 3′   │  template (3′→5′ read)
       │                                  │
3′ ════╪════════════════════════════ 5′   │  template (5′→3′ read)
       └──────────────────────────────────┘

LEADING STRAND:  new strand made 5′→3′ toward the fork — ONE continuous piece

LAGGING STRAND:  new strand must grow AWAY from the fork,
                 so it is built backwards in pieces:

   5′ ←─── Okazaki ─── [RNA primer] ←─── Okazaki ─── [RNA primer] ←── 3′
             fragment                      fragment
```

| | Leading strand | Lagging strand |
| --- | --- | --- |
| **Direction of growth** | Toward the fork (5′→3′) | Away from the fork (5′→3′), in pieces |
| **Continuity** | **Continuous** | **Discontinuous** — Okazaki fragments (~1000–2000 nt in eukaryotes, ~1000–2000 in bacteria) |
| **Primers needed** | One, at the origin | One per fragment |
| **Clean-up** | Minimal | **Pol I removes primers; ligase seals nicks** |

**Why not synthesise 3′→5′?** A polymerase extending 3′→5′ would have to release a pyrophosphate from the **growing** end; any mistake would place an already-committed, unstable 3′-diphosphate at the terminus and the strand would fall off. Evolution kept 5′→3′ synthesis plus editing instead — the geometry is safe, the proofreading corrects errors. This asymmetry is the single most common source of exam questions on replication.

**Lagging-strand synthesis cycles:** primer → extend → release → next primer → extend → remove previous primer → ligate. The polymerase that finishes one Okazaki fragment physically transfers to the next primer — in bacteria this handoff is organised by the **trombone model**, looping the lagging strand so both polymerases in the replisome move together.

## Fidelity: how the cell gets to ~10⁻¹⁰

Three successive filters reduce the error rate at each stage:

| Step | Mechanism | Error rate contribution |
| --- | --- | --- |
| **1. Base selection** | Polymerase active site checks **geometry and hydrogen-bonding pattern** before catalysis | ~1 wrong base per 10⁵ |
| **2. Proofreading** | **3′→5′ exonuclease** activity of the replicative polymerase excises a mispaired nucleotide immediately after insertion | ×10⁻² improvement → ~10⁻⁷ |
| **3. Mismatch repair** | Post-replicative scan detects and excises mismatches the polymerase missed | ×10⁻² to 10⁻³ → **~10⁻⁹ to 10⁻¹⁰ per base pair per division** |

```
mismatch inserted
      │
      ▼
polymerase stalls (distorted primer–template)
      │
      ▼
3′→5′ EXONUCLEASE removes the wrong nucleotide  ← proofreading
      │
      ▼
correct nucleotide inserted, synthesis resumes
      │
      ▼
any mismatch that escapes ──▶ MISMATCH REPAIR excises a patch
                              around the error and resynthesises
```

**Strand discrimination in mismatch repair.** The repair system must know which strand is wrong — editing the template instead of the new strand would make the error permanent. In bacteria, the parental strand is **methylated at GATC** while the newly synthesised strand is briefly unmethylated, so the system cuts the *unmethylated* strand. In eukaryotes, strand discrimination is thought to use nicks and strand breaks associated with the unreplicated state of the new strand. Failure of this system (**Lynch syndrome / hereditary nonpolyposis colorectal cancer**, MLH1 and MSH2 mutations) is a leading inherited cancer-predisposition cause — repair, not replication, is what fails.

**Numbers worth memorising:** polymerase alone ≈ 10⁻⁵; with proofreading ≈ 10⁻⁷; with mismatch repair ≈ **10⁻¹⁰ per base pair per genome replication** — roughly one error per 10 billion nucleotides copied, or about one error per human genome per cell division.

## Telomeres and the end-replication problem

The lagging strand cannot be finished all the way to the 5′ end of the newly made strand: **there is nowhere left to put an RNA primer** once the terminal Okazaki fragment would run off the end.

```
round 1:  5′─────────────────────────TTAGGGTTAGGG 3′
          3′──────────────────────────────────────5′

round 2:  primer placed inward → gap at the very end
          5′─────────────TTAGGGTTAGGG   ← shortened

each division: ~50–200 nt lost from each linear end
```

**Telomerase** solves this — and it is a remarkable enzyme:

| Feature | Detail |
| --- | --- |
| **Composition** | **TERT** (protein, reverse transcriptase) + **TERC** (RNA template, carries **AAUCCC**) |
| **Action** | Extends the 3′ G-rich overhang using its own RNA as template; primase/polymerase then fills in the complementary strand |
| **Expression** | Active in **germ cells, stem cells, and lymphocytes**; **silenced in most somatic cells**; reactivated in ~85–90 % of cancers |

**The two-faced role of telomeres:**

```
shortening telomeres in normal somatic cells
        │
        ▼
after ~50–70 divisions (Hayflick limit) → SENESCENCE or APOPTOSIS
        │
        └── a tumour SUPPRESSOR mechanism: cells are counted out of the cycle

telomerase reactivated in cancer cells
        │
        ▼
shortening prevented → REPLICATIVE IMMORTALISATION → unlimited divisions
```

That loop closes exactly on [10 — The cell cycle and its checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md): telomere shortening is a counting device that cancer must defeat, and telomerase reactivation is one of the recognised hallmarks of malignant transformation. **Aplastic anaemia, dyskeratosis congenita, and some forms of pulmonary fibrosis** are diseases of *insufficient* telomere maintenance — the opposite failure with equally logical consequences.

## Where replication is allowed to be wrong: antibiotic targets

The best selective antibiotics attack machinery bacteria have and humans lack:

| Drug | Target | Consequence for the bacterium |
| --- | --- | --- |
| **Quinolones (ciprofloxacin, levofloxacin)** | **DNA gyrase / topoisomerase IV** — traps the enzyme-DNA complex | Supercoiling cannot be managed; double-strand breaks accumulate |
| **Rifampicin** | Bacterial **RNA polymerase** (see [04 — Transcription](04-transcription.md)) | Transcription blocked — listed here because it is often grouped with antimicrobial nucleic-acid drugs |
| **Hydroxyurea** | Ribonucleotide reductase → **depletes dNTPs** | Not selective — used in sickle cell disease and cancer; slows replication in all cells |
| **Nucleoside analogues (acyclovir, AZT, ganciclovir)** | Incorporated by viral (and cellular) polymerases | Chain termination — selectivity comes from *activation by a viral kinase* (see below) |
| **Trimethoprim / sulfonamides** | Folate pathway → starve the **primer/nucleotide** supply | Bacteria cannot synthesise folate; humans import it |

**Why acyclovir is selective:** it is a guanine analogue phosphorylated to high levels only by **herpesvirus thymidine kinase**, so only infected cells accumulate the active triphosphate. The viral enzyme is the selectivity window — the same principle as targeting a bacterial-only enzyme.

## Medical relevance

**Cancer is a replication-and-repair disease.** Two distinct failures combine: (1) proofreading/mismatch-repair defects raise the mutation rate genome-wide (**mutator phenotype**), and (2) telomerase reactivation removes the division limit. Both are covered from the cell's perspective in [10 — The cell cycle and its checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) and from the sequence's perspective in [07 — Mutations](07-mutations.md).

**Lynch syndrome** (mismatch-repair mutation) and **familial adenomatous polyposis** illustrate the principle: the replication machinery is intact; it is the **verification** layer that fails, so errors that would normally be corrected persist and accumulate in the colon.

**Antimetabolite chemotherapy** targets the S phase directly: **5-fluorouracil** (thymidylate synthase inhibition), **methotrexate** (folate → dTMP starvation), **gemcitabine** (a nucleoside analogue with a masked chain terminator), and **hydroxyurea** (dNTP depletion). Their dose-limiting toxicities — marrow suppression and gut mucositis — come from the same mechanism acting on normal labile tissue.

**Antivirals are replication inhibitors with a twist:** because viruses use the host polymerase, a useful drug must hit a **virus-specific enzyme** — reverse transcriptase (HIV), viral DNA polymerase activated by viral kinase (herpes), or the neuraminidase/other non-replication targets. That constraint explains why antiviral chemistry is narrow and why resistance appears quickly.

**Mitochondrial DNA is replicated differently** — a separate polymerase (Pol γ), no telomerase (mtDNA is circular), and maternal inheritance. Pol γ mutations cause mitochondrial depletion syndromes; the overlap between nuclear replication errors and organellar genomes is an increasingly common exam theme.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Both new strands are made continuously" | Only the **leading** strand is continuous; the lagging strand is made as **Okazaki fragments** because synthesis is exclusively 5′→3′. |
| "DNA polymerase can start a strand de novo" | It **cannot** — it needs a free 3′-OH, which is why **primase** lays RNA primers first. |
| "Proofreading is 5′→3′" | Proofreading is **3′→5′ exonuclease** — it backs up. (RNA polymerase's related activity is distinct.) |
| "Ligase joins the two strands of the helix" | Ligase seals **nicks in the sugar–phosphate backbone** of one strand — Okazaki fragments, not the two strands of DNA. |
| "Telomeres prevent all shortening" | Telomeres **absorb** shortening by providing expendable repeats; they slow but do not stop it — telomerase is what lengthens them again. |
| "Meselson–Stahl proved semiconservative replication in eukaryotes specifically" | It proved the **mechanism in bacteria**; the same mode applies to eukaryotes, demonstrated separately. |
| "More origins would make replication faster per fork" | Fork speed is roughly fixed; more origins mean **more forks working in parallel**, which is how a large genome is copied in one S phase. |

## Key facts

- **Meselson–Stahl** proved **semiconservative** replication: one parental strand + one new strand in every daughter duplex; density-gradient centrifugation separated the generations.
- A **replicon** is one origin plus the DNA it serves; bacteria have **one origin**, eukaryotes **thousands**, all firing bidirectionally in S phase.
- Fork machinery: **helicase** unwinds, **SSB** stabilises, **topoisomerase** relieves supercoiling, **primase** lays RNA primers, **pol III** synthesises, **pol I** removes primers and fills gaps, **ligase** seals nicks, the **sliding clamp** adds processivity.
- DNA polymerase synthesises **only 5′→3′ and only onto a pre-existing 3′-OH** — hence one continuous **leading** strand and one discontinuous **lagging** strand built as **Okazaki fragments**.
- Fidelity: base selection (~10⁻⁵) → **3′→5′ proofreading** (~10⁻⁷) → **mismatch repair** (~10⁻¹⁰ overall per bp per division).
- Mismatch repair needs **strand discrimination** (GATC methylation in bacteria); its failure causes **Lynch syndrome**.
- The **end-replication problem** shortens linear chromosome ends each division; **telomerase** (TERT + TERC RNA template) extends the G-rich overhang and is active in germ/stem cells and most cancers.
- Telomere shortening is a **tumour suppressor** (senescence after ~50–70 divisions); telomerase reactivation gives **replicative immortality**.
- **Quinolones** inhibit bacterial gyrase/topoisomerase IV; nucleoside analogues terminate chains, with selectivity from virus-specific activation.
- Linear chromosomes also need **telomeres as end caps**; centromeres provide kinetochore attachment — see [10 — The cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md).

## Practice questions

**1. In the Meselson–Stahl experiment, generation 2 in ¹⁴N medium showed two bands — one hybrid and one light. This result eliminates**

A. Semiconservative replication only
B. Conservative and dispersive replication
C. The use of caesium chloride
D. The possibility that replication is bidirectional

**Answer: B**

Explanation: A single hybrid band at generation 1 already eliminated conservative replication (which would have given one heavy and one light band). At generation 2, semiconservative predicts half hybrid (one old + one new strand) and half light (two new strands) — exactly what was seen. Dispersive replication would have given a single band of intermediate-light density that never resolved into two discrete bands. Bidirectionality and the centrifugation method are unrelated to the banding pattern's logic.

---

**2. Which enzyme removes RNA primers during lagging-strand synthesis in *E. coli*?**

A. DNA ligase
B. DNA polymerase I
C. DNA polymerase III
D. Primase

**Answer: B**

Explanation: DNA polymerase I has a unique **5′→3′ exonuclease** activity that degrades the RNA primer ahead of it while simultaneously filling the gap with DNA — a process called nick translation. DNA polymerase III is the bulk replicative enzyme but cannot remove primers; ligase seals the remaining nick but does not degrade RNA; primase makes primers rather than removing them.

---

**3. The lagging strand is synthesised discontinuously because**

A. Its template is degraded during replication
B. DNA polymerase can only synthesise 5′→3′, so growth must point away from the fork
C. Primase can only work on one strand
D. Ligase is required before synthesis can begin

**Answer: B**

Explanation: The strands are antiparallel and the polymerase is strictly 5′→3′, so only the strand whose growing end faces the fork can be extended continuously. The other must be built backwards in Okazaki fragments, each started by a primer. Nothing about the template (A), primase specificity (C), or ligase timing (D) creates the discontinuity — it is the directionality of the chemistry itself.

---

**4. Which step of replication contributes the largest single improvement in fidelity?**

A. Initial base selection by the polymerase active site
B. 3′→5′ proofreading exonuclease activity
C. Mismatch repair
D. Sliding clamp processivity

**Answer: C**

Explanation: Base selection gives about 10⁻⁵ accuracy, proofreading improves that roughly a hundredfold to 10⁻⁷, and mismatch repair provides the final hundred- to thousandfold improvement to ~10⁻¹⁰ — the largest single gain. Processivity (D) affects speed and completeness, not accuracy. All three layers matter, which is why a defect in mismatch repair alone (Lynch syndrome) dramatically raises cancer risk.

---

**5. In bacterial mismatch repair, the new strand is identified because**

A. It is richer in guanine
B. It is transiently unmethylated at GATC sequences
C. It contains RNA primers throughout
D. It has more nicks than the parental strand

**Answer: B**

Explanation: The parental strand is methylated at GATC; the newly synthesised strand is not yet methylated for a short period, so the repair machinery excises the unmethylated (new) strand opposite a mismatch and resynthesises it — guaranteeing the parental sequence is preserved. Persistent RNA primers (C) are already removed by the time mismatch repair acts, and nick frequency (D) is not the signal in bacteria.

---

**6. The end-replication problem exists because**

A. Telomeres are chemically unstable
B. There is no room to place an RNA primer beyond the very 5′ end of the final Okazaki fragment
C. DNA polymerase cannot replicate the ends of linear molecules at all
D. Helicase cannot open terminal DNA

**Answer: B**

Explanation: Each Okazaki fragment needs an RNA primer; at the extreme end of the lagging strand's template there is no further DNA for a primer to sit on, so the final segment is never copied and the chromosome shortens with each division. Synthesis does occur at the ends (C is too strong), and neither instability (A) nor unwinding (D) is the issue — it is a primer-placement geometry problem.

---

**7. Telomerase is best described as**

A. A DNA-dependent DNA polymerase that fills gaps
B. A reverse transcriptase with its own RNA template that extends chromosome ends
C. A nuclease that trims damaged telomeres
D. A helicase that opens telomeric repeats

**Answer: B**

Explanation: Telomerase carries TERT, a reverse transcriptase, and TERC, an RNA template complementary to the telomeric repeat. It lengthens the 3′ overhang directly, after which conventional polymerase and primase complete the complementary strand. It is not gap-filling by a DNA-dependent enzyme (A), not a nuclease (C), and it does not unwind DNA (D).

---

**8. Ciprofloxacin inhibits bacterial growth by targeting**

A. Bacterial 70S ribosomes
B. DNA gyrase and topoisomerase IV
C. The sliding clamp
D. Human-like telomerase

**Answer: B**

Explanation: Quinolones trap the covalent gyrase–DNA complex, preventing the relief of supercoiling and causing double-strand breaks during replication — a bacterial-specific target because the enzyme's structure differs from human topoisomerases and humans have no equivalent need for the bacterial form of the enzyme. Ribosomes (A) are the target of aminoglycosides and macrolides; the clamp (C) has no major antibiotic target; telomerase (D) is not a bacterial target.

---

**9. A proofreading-deficient polymerase that still has intact mismatch repair would produce**

A. A mutation rate unchanged, because mismatch repair compensates fully
B. A modestly elevated mutation rate — the second layer is intact but the first defence is lost
C. Immediate cell death
D. Chromosome loss

**Answer: B**

Explanation: Fidelity is layered, and losing proofreading raises the raw error rate from about 10⁻⁷ toward 10⁻⁵; mismatch repair still removes most surviving errors, so the final rate is elevated rather than catastrophic. Each layer reduces what the previous one let through, so removing any one produces a graded increase in mutations — exactly the "mutator phenotype" that predisposes to cancer when mismatch repair is the layer that fails.

---

**10. Cancer cells that reactivate telomerase gain which specific advantage?**

A. Faster fork movement
B. Escape from the division limit imposed by progressive telomere shortening
C. Increased mismatch repair activity
D. Resistance to all chemotherapy

**Answer: B**

Explanation: Progressive shortening drives normal somatic cells into senescence after roughly 50–70 divisions — a built-in brake. Telomerase maintains telomere length, so the brake never engages and the cell becomes replicatively immortal, a requirement for full malignancy. Fork speed (A), repair fidelity (C), and drug response (D) are independent properties; telomerase alone confers only the removal of the replicative limit.
