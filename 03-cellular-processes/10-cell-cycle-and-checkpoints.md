# The Cell Cycle and Its Checkpoints

## Why it matters

Everything up to this point has been about how a cell *works*. This chapter and the next two are about how a cell **duplicates and divides** — growth, tissue renewal, reproduction, and the failures that produce cancer.

The organising idea is that division is a **regulated process with gates**: the cell does not simply grow and split, it **pauses at checkpoints, verifies that the previous stage completed correctly, and only then proceeds**. Cancer, in the language of this chapter, is what happens when the checkpoints stop working.

## The cycle at a glance

```
                    ┌───────────── MITOTIC PHASE (M) ─────────────┐
                    │  mitosis (chromosomes separate)             │
                    │  + cytokinesis (cell splits)                │
                    └──────────────┬──────────────────────────────-┘
                                   │
       ┌───────────────────────────┴────────────────────────────┐
       │                                                        │
   G1 (growth, prepare)  ──▶  S (DNA replication)  ──▶  G2 (growth, check)
       │                                                        │
       └──────────────── INTERPHASE (the cell "lives") ──────────┘

   G0 — a resting state out of the cycle, entered from G1
```

| Phase | What happens | Duration (typical human cell) |
| --- | --- | --- |
| **G1** | Growth, protein synthesis, organelle duplication; **decision point** | ~6–12 h (highly variable) |
| **S** | **DNA replication** — every chromosome copied | ~6–8 h |
| **G2** | Further growth; **damage check**; spindle preparation | ~4 h |
| **M** | Mitosis + cytokinesis | ~30–60 min |
| **G0** | Non-dividing, functional state | Indefinite (years) |

**Interphase = G1 + S + G2** — the cell is *not* idle; it is growing, copying, and checking. The old picture of interphase as "rest" is the most common textbook error about the cycle.

## The three (four) checkpoints

| Checkpoint | Position | What it verifies | Gatekeeper |
| --- | --- | --- | --- |
| **G1 (restriction point)** | End of G1 | Is the cell the right size? Is the environment right (growth factors)? Is DNA undamaged? | **p53, Rb** |
| **Intra-S** | During S | Is replication proceeding correctly? Are there damaged templates? | ATR/Chk1 |
| **G2** | End of G2 | Is DNA fully replicated? Is any damage repaired? | **p53**, ATM/ATR |
| **M (spindle checkpoint)** | Metaphase | Is **every** chromosome attached to spindle microtubules from both poles? | Mad/Bub proteins → inhibit **anaphase-promoting complex** |

**The logic of each:**

```
G1:   "Should I divide?"   size · nutrients · growth factors · DNA intact?
S:    "Is copying going well?"  replication fork stalling · lesions
G2:   "Is copying finished and correct?"  replicate completely · repair damage
M:    "Is every chromosome properly attached?"  wait at metaphase until all attached
```

**The spindle checkpoint is a pure counting problem:** one unattached kinetochore holds the whole cell at metaphase, because releasing anaphase with a lagging chromosome guarantees aneuploidy in one daughter. The cell waits for **100% attachment** — an all-or-nothing gate.

### What happens when a checkpoint detects a problem

**Option 1: repair and resume.** p53 upregulates repair enzymes; if damage is fixed, the cycle continues.

**Option 2: permanent exit.** Irreparable damage → **senescence** (cells leave the cycle permanently but stay alive and metabolically active) or **apoptosis** (programmed death — the cytochrome c mechanism from 02 — Cell Biology).

```
DNA damage detected
      │
      ▼
ATM/ATR kinases ──▶ stabilise p53
      │
      ├──▶ p21 inhibits cyclin-CDK ──▶ CYCLE HALTS at G1/S
      │
      ├──▶ repair genes ON ──▶ if fixed: resume
      │
      └──▶ if irreparable: BAX ↑ → APOPTOSIS
                          or senescence (permanent arrest)
```

**This is why p53 is the most commonly mutated gene in human cancer** — remove the referee and damaged cells keep dividing, accumulating mutations each cycle. p53 is called *the guardian of the genome*; its loss converts a repair system into a permissive one.

## Cyclins and CDKs: the engine

A cell cannot simply "decide" to divide — it needs an **oscillator** driving it irreversibly through the phases. The engine is built from two parts:

| Component | Behaviour |
| --- | --- |
| **Cyclins** | Proteins whose concentration **oscillates** — synthesised and destroyed each cycle (destruction by **ubiquitin tagging**, via the anaphase-promoting complex and SCF) |
| **CDKs** (cyclin-dependent kinases) | Kinases **always present** but **inactive** — they phosphorylate target proteins only when bound to the right cyclin |

**Cyclin is the variable; CDK is the constant.** The cycle's direction comes from cyclin levels: rising cyclin activates a CDK wave, which drives a phase transition, then the cyclin is destroyed and that wave passes.

| Cyclin–CDK complex | Phase | Drives |
| --- | --- | --- |
| **Cyclin D–CDK4/6** | G1 | Response to mitogens; starts Rb phosphorylation |
| **Cyclin E–CDK2** | G1/S | **Commits to replication** — passes restriction point |
| **Cyclin A–CDK2** | S | Replication fork progression |
| **Cyclin A–CDK1** | G2 | Preparation for mitosis |
| **Cyclin B–CDK1** ("maturation/MPF") | M | **Entry into mitosis** — chromosome condensation, nuclear envelope breakdown, spindle assembly |

**MPF (maturation-promoting factor)** = cyclin B + CDK1. Its discovery — in frog oocytes that could be induced to divide by injection from an already-dividing cell — proved that the cycle is driven by a diffusible chemical signal, not by some property of the cell's age.

### Two themes the examiners repeat

**1. Mitogens set the pace; checkpoints veto.** Growth factors (mitogens) push Cyclin D–CDK4/6 to begin Rb phosphorylation — but the checkpoint can still veto on damage. **Stimulation and approval are separate systems**, which is why both an oncogene (stuck accelerator) *and* a tumour-suppressor loss (failed brake) can cause cancer — and why cancers usually need both.

**2. Rb is the gate.** Unphosphorylated **Rb protein binds E2F**, a transcription factor, and blocks S-phase gene expression. Sequential phosphorylation by cyclin D- then E-CDKs releases E2F → replication genes switch on → the cell commits.

```
G1:      Rb—E2F (blocked)        no S-phase genes
            │ cyclin D/E-CDK phosphorylate Rb
            ▼
S entry: Rb released ──▶ E2F free ──▶ replication genes ON

Rb LOST (as in many cancers): E2F free even without signal → division with no permission
```

**Retinoblastoma — the disease that named the gene.** Children with one mutated *RB1* allele develop retinal tumours when the remaining allele is lost in a retinal cell: **"two hits"** (Knudson's hypothesis), the founding model of tumour-suppressor genetics.

## G0 and cell classes

Recall chapter 01's classification, now in cycle terms:

| Class | Cycle behaviour | Examples | Clinical meaning |
| --- | --- | --- | --- |
| **Labile** | Cycle continuously, short G1 | Gut epithelium, marrow, skin | Rapid renewal; targets for chemo (high division rate) |
| **Stable** | Remain in **G0**, re-enter on signal | Liver, lymphocytes, fibroblasts | Regeneration on demand |
| **Permanent** | Terminal G0 — **never re-enter** | Neurons, cardiac myocytes | Damage is lasting |

**G0 is a state, not a decay.** A cell in G0 is fully functional; the question is only whether it can be *triggered back in* — which depends on whether its cyclin machinery is intact and licensed.

**Contact inhibition and anchorage dependence** (02 — Cell Biology) are **G1 controls**: crowded cells receive signals that keep Cyclin D–CDK4/6 inactive. Cancer cells lose both — they divide in a pile, detached from matrix — because the G1 gate ignores external context.

## What failure looks like: cancer as a cycle disease

| Normal control | What fails in cancer | Genetic example |
| --- | --- | --- |
| Growth factor requirement | **Self-sufficient signalling** | *RAS* mutation (oncogene — stuck "on") |
| Contact inhibition | **Density-independent growth** | Loss of cadherin/Rb pathway control |
| G1 checkpoint on damage | **Checkpoint bypass** | **p53 mutation** (most common in human cancer) |
| Rb gate | **Constitutive E2F release** | *RB1* loss |
| Spindle checkpoint | **Aneuploidy tolerance** | Mad2/BubR1 alterations |
| Apoptosis on irreparable damage | **Death resistance** | BCL-2 overexpression (02 — Cell Biology) |
| Telomere shortening limits divisions | **Immortalisation** | **Telomerase reactivation** |

**Telomere biology closes the loop:** chromosomes lose a little DNA each division (the end-replication problem), and after ~50–70 divisions cells senesce — a built-in counting mechanism. **Cancer cells reactivate telomerase**, removing the limit. Telomere shortening is a tumour *suppressor* that cancer must defeat to become malignant — the "immortalisation" step in the multi-hit model.

**Tumour progression = accumulating checkpoint failures.** No single mutation causes cancer; the cycle's controls are **redundant**, so several must fail. That redundancy is why cancer is predominantly a **disease of aging** — time is needed for the mutations to accumulate.

## Medical relevance

**Chemotherapy exploits cycle position.** Agents are classified by where they act:

| Target | Drugs | Phase |
| --- | --- | --- |
| DNA synthesis | 5-fluorouracil, methotrexate, gemcitabine | **S phase** |
| Microtubules (spindle) | vincristine, taxol, colchicine | **M phase** (arrest at spindle checkpoint) |
| DNA crosslinking | cisplatin, cyclophosphamide | Cell-cycle-independent but **damage-dependent** (p53 decides fate) |
| CDK4/6 inhibitors | **palbociclib, ribociclib** | **G1** — used in breast cancer |

**The therapeutic window:** cancer cells cycle more often than most normal cells, so they meet the drug's phase more frequently — but labile normal tissue (marrow, gut) cycles often too, which is exactly why **myelosuppression and mucositis** are the classic dose-limiting toxicities. The cure and the side effect have the same mechanism.

**Checkpoint-aware therapy:** a tumour with **mutant p53** cannot arrest or apoptose in response to DNA damage — it responds differently from p53-wild-type tumours, and the p53 status is now a standard reportable marker. **Loss of the checkpoint changes the treatment, not just the prognosis.**

**Why most cancers occur in older people:** the multi-hit requirement plus telomere limits plus declining DNA repair means the probability rises with decades of mutation accumulation — the epidemiology follows the biology of this chapter.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Interphase is resting" | It is **growth, replication, and checking** — the longest and most active part of the cycle. |
| "Mitosis and cell division are the same" | Mitosis = **nuclear division**; cell division = mitosis **+ cytokinesis**. |
| "Cyclins drive the cycle by being always present" | Cyclins **oscillate**; CDKs are constant. Cyclin *destruction* ends each phase. |
| "Checkpoint failure immediately causes cancer" | One failure is usually tolerated (senescence/apoptosis still work); **multiple** must accumulate. |
| "G0 means the cell is dying" | G0 is a **functional, stable state** — liver and neurons live there for years. |

## Key facts

- Cycle = **G1 → S → G2 → M** (interphase = G1+S+G2); **G0** is the resting state out of the cycle.
- **Four checkpoints**: G1 (size, growth factors, DNA), intra-S (replication), G2 (completeness, damage), **M (all chromosomes attached — all-or-nothing)**.
- Engine: **cyclins oscillate, CDKs are constant** — cyclin-CDK pairs drive each transition; cyclins are destroyed by ubiquitin-mediated proteolysis.
- **Rb–E2F** is the G1 gate: phosphorylation by cyclin D/E-CDKs releases E2F → S-phase genes on.
- **p53** = damage sensor → p21 halts cycle; irreparable → apoptosis or senescence. **Most mutated gene in cancer.**
- Cancer requires **multiple control failures** — accelerator (oncogene) + failed brakes (tumour suppressors) + immortalisation (**telomerase**) — hence a disease of aging.
- Labile/stable/permanent cells differ in **whether they leave and re-enter the cycle**.
- Chemotherapy targets phases: **S-phase agents, M-phase spindle poisons, CDK4/6 inhibitors at G1**; marrow and gut toxicity follows from their high cycling rate.

## Practice questions

**1. Which phase of the cell cycle is DNA replicated?**

A. G1
B. S
C. G2
D. M

**Answer: B**

Explanation: S = synthesis; each chromosome is duplicated so each will have two sister chromatids. G1 is growth before replication, G2 is growth and checking after it, and M is chromosome segregation. Interphase covers all three non-mitotic phases.

---

**2. The spindle checkpoint (M checkpoint) verifies that**

A. DNA has been completely replicated
B. Every chromosome is properly attached to spindle microtubules from both poles before anaphase proceeds
C. The cell has reached sufficient size
D. No mutations are present in the genome

**Answer: B**

Explanation: The M checkpoint holds the cell at metaphase until every kinetochore is correctly bi-oriented — even one unattached kinetochore blocks the anaphase-promoting complex. A and C are G2 and G1 functions respectively; no checkpoint can verify the entire genome for mutations (D), only for damage or attachment status.

---

**3. What is the normal function of the Rb protein?**

A. To repair damaged DNA directly
B. To bind E2F and prevent expression of S-phase genes until the cell receives mitogenic signal and Rb is phosphorylated
C. To degrade cyclins
D. To form the spindle microtubules

**Answer: B**

Explanation: Rb is the gatekeeper of the restriction point: while bound to E2F, replication genes stay silent. Cyclin D/E-CDK activity phosphorylates Rb progressively, releasing E2F and committing the cell to S phase. Loss of Rb leaves E2F constitutively free — division without permission, as in retinoblastoma.

---

**4. A cell detects irreparable DNA damage at the G1 checkpoint. Which outcome is most appropriate?**

A. Immediate entry into S phase
B. Bypassing G2 to divide anyway
C. Permanent cell-cycle arrest (senescence) or apoptosis
D. Replicating the damaged DNA without repair

**Answer: C**

Explanation: p53 activation leads either to p21-mediated arrest with repair attempts, or — if damage is beyond repair — to senescence or programmed cell death. This prevents propagation of mutations. Options A, B, and D describe exactly what a defective checkpoint permits, which is the mechanism of tumour progression.

---

**5. Which statement about cyclins is correct?**

A. Their concentrations oscillate through the cycle, and they activate CDK partners only when bound
B. They are constitutively active kinases
C. They are structural proteins of the spindle
D. They are degraded during G1 to stop the cycle permanently

**Answer: A**

Explanation: Cyclins are synthesised and destroyed in a cycle-specific pattern; CDKs are always present but need cyclin binding to become active. Their destruction by ubiquitin-mediated proteolysis is what *ends* each phase — making the transitions irreversible. Kinase activity belongs to CDKs, not cyclins (B).

---

**6. Which pairing of drug class with cell-cycle target is correct?**

A. Taxol and vincristine — arrest cells at G1
B. 5-Fluorouracil — inhibits DNA synthesis in S phase
C. CDK4/6 inhibitors — block metaphase attachment
D. Colchicine — prevents DNA replication directly

**Answer: B**

Explanation: 5-FU is an antimetabolite interfering with thymidine synthesis, so it acts in S phase. Taxol, vincristine, and colchicine target microtubules and arrest cells in **M phase** at the spindle checkpoint — A and D are wrong; CDK4/6 inhibitors act at **G1** (C is wrong).

---

**7. Why is cancer predominantly a disease of older age?**

A. Older cells have more cytoplasm
B. Multiple independent checkpoint and tumour-suppressor failures must accumulate, which takes time, and telomere shortening must be overcome
C. Young cells do not undergo mitosis
D. Mutations only occur after age 50

**Answer: B**

Explanation: Redundant controls mean a single mutation is usually countered by senescence or apoptosis; malignancy requires several hits — oncogene activation, tumour-suppressor loss, telomerase reactivation — which accumulate over decades. Cells divide throughout life (C wrong) and mutations occur at all ages (D wrong), just with less time to compound.

---

**8. A cell in G0 is best described as**

A. Dead or dying
B. Functionally active but not progressing through the cycle, and able to re-enter on an appropriate signal (if stable)
C. In the process of replicating DNA
D. Permanently unable to synthesise proteins

**Answer: B**

Explanation: G0 is a resting, non-cycling state — neurons and cardiomyocytes live there permanently (permanent cells), while hepatocytes and lymphocytes re-enter on demand (stable cells). G0 cells are metabolically active and fully functional; they are simply not scheduled to divide.

---

**9. What happens at the restriction point in late G1?**

A. The cell irreversibly commits to a full division cycle if conditions are adequate
B. DNA begins unwinding for replication
C. Chromosomes align at the metaphase plate
D. Cytokinesis begins

**Answer: A**

Explanation: The restriction point is the commitment step — past it, the cell will complete S, G2, and M regardless of growth factor withdrawal, because cyclin E-CDK2 has phosphorylated Rb and activated E2F. Before it, mitogens are still required. B describes S phase, C and D describe M phase.

---

**10. Why does loss of p53 make a tumour more dangerous?**

A. p53 directly repairs all DNA mutations
B. Without p53, damaged cells cannot halt the cycle or undergo apoptosis, so mutations are propagated and accumulate
C. p53 is required for cell survival; its loss kills the cell
D. p53 prevents telomere shortening

**Answer: B**

Explanation: p53 is the checkpoint's decision-maker — it induces p21 for arrest and BAX for apoptosis when damage is irreparable. Remove it and damaged cells keep cycling, fixing nothing and killing nothing, so genomic instability accelerates. It does not itself repair DNA (A), its loss promotes survival of damaged cells rather than killing them (C), and telomerase is a separate mechanism (D).
