# Prokaryotic and Eukaryotic Cells

## Core idea

All cells fall into one of two plans. The eukaryotic plan — a nucleus bounded by a membrane, plus internal membrane-bound compartments — is what makes multicellular complexity possible. The prokaryotic plan — no membrane-bound nucleus — is simpler, smaller, and faster to divide. Understanding both here pays off in every later chapter, because eukaryotic organelles are best understood as membrane specialisations performing specific jobs.

## Cell theory

Three statements form cell theory, and all three carry exceptions worth knowing.

1. **All living things are composed of cells.** — Cells are the smallest unit of life.
2. **All cells come from pre-existing cells.** — Cells divide; they do not arise spontaneously.
3. **All cells are fundamentally similar.** — Shared genetic material, a plasma membrane, and similar metabolism.

Two qualifications. **Viruses are not cells** — they lack ribosomes and cannot synthesise protein independently, so statement 3 does not apply to them. And the first prokaryotes arose from non-cellular precursors, but that was in the remote past; no cell arises from non-cellular matter today, which is the basis of biogenesis and of Pasteur's work refuting spontaneous generation.

## The two plans

```
PROKARYOT                                   EUKARYOT
                                            
Bounded cell membrane, no nucleus           Nucleus enclosed in a double membrane
Genetic material free in cytoplasm         Chromosomes enclosed in nucleus
Membrane-bound organelles: ABSENT           Present: mitochondria, ER, Golgi,
   (in the textbook sense — see below)       lysosomes, peroxisomes
Small: typically 0.1–5 μm                   Larger: typically 10–100 μm
Usually unicellular                          Unicellular (yeast, protozoa) or multicellular
Ribosomes 70S                                Ribosomes 80S in cytosol; 70S in mitochondria and chloroplasts
Cell wall: usually present (peptidoglycan)   Plants: cellulose. Fungi: chitin. Animals: none
```

The size difference is not arbitrary. Surface area to volume ratio limits how fast a cell can exchange material with its environment:

$$\frac{\text{surface area}}{\text{volume}} \propto \frac{1}{r}$$

A larger cell has proportionally less membrane surface per unit of cytoplasm that must be supplied. This constrains the maximum viable cell size and is one reason multicellular organisms exist. It is also why the flat, elongated shapes of cells in metabolically active tissue — muscle fibres, the thin sheets of alveolar epithelium, the elongated cells of the kidney tubule — all increase surface area relative to volume. **Cell shape is a transport requirement.**

## Archaea

Archaea are prokaryotic and are prokaryotic in cell plan, but they differ from bacteria substantially:

| Feature | Bacteria | Archaea |
| --- | --- | --- |
| Membrane lipid linkage | Ester linkage | **Ether linkage** |
| Membrane lipid tails | Unbranched fatty acids | **Branched isoprenoid chains** |
| Cell wall | Peptidoglycan | No peptidoglycan; pseudopeptidoglycan, protein, or none |
| Ribosomes | 70S | 70S |
| Sensitivity to penicillin | Sensitive | **Not sensitive** |

The membrane difference is not cosmetic. Ether linkages and branched chains make archaeal membranes far more resistant to hydrolysis and to extremes of heat, pH, and salinity. Many archaea are therefore found in very high temperatures and very high salt — environments where bacterial membranes would fail.

**Why this matters for the rest of the course:** the eukaryotic cell is, in part, an archaeal cell that acquired a bacterium. The mitochondria of a eukaryotic cell have bacterial-type membranes and bacterial-type ribosomes, and they divide by binary fission. Evidence for this is presented in 06 — Evolution. Archaea will appear again in [07 — Microbiology](../07-microbiology/).

## Doing the same jobs without the organelles

Bacteria lack mitochondria, ER, and Golgi — but bacteria are not simple. They perform the equivalent functions using the plasma membrane and specialised internal structures, because their plasma membrane is far more internally differentiated than it first appears:

| Eukaryotic structure | Bacterial equivalent |
| --- | --- |
| Respiratory electron transport | Plasma membrane, often deeply invaginated |
| Photosynthesis | Internal **photosynthetic membranes** |
| Secretion and sorting | Plasma membrane; sometimes **pili** for attachment or DNA transfer |
| DNA organisation | **Nucleoid** region; plasmids |
| Cytoskeleton | FtsZ and MreB homologues of tubulin and actin |

These are structural and functional equivalents, not evolutionary identities, and the terminology is deliberately different to keep that distinction visible.

## Prokaryotic cell structures

| Structure | Description | Function |
| --- | --- | --- |
| **Nucleoid** | Irregular region where the DNA is concentrated; no membrane | Houses the single circular chromosome; transcription and translation happen here simultaneously |
| **Plasmid** | Small separate circular DNA, often carrying accessory genes | Replication independent of the chromosome; often includes antibiotic-resistance genes |
| **Pili / fimbriae** | Short protein filaments on the surface | Attachment to surfaces, host cells, or other bacteria; pili are longer and involved in conjugation |
| **Capsule** | Polysaccharide layer outside the cell wall | Protection against desiccation and phagocytosis; resists immune clearance |
| **Flagellum** | Long rotating filament (prokaryotic flagella differ structurally from eukaryotic ones) | Motility |
| **Cell wall** | Peptidoglycan | Maintains shape, prevents osmotic lysis, confers Gram-stain behaviour |
| **Mesosome** | Infolding of the plasma membrane | Site of respiration and chromosome segregation |

**No mitochondria, yet bacteria still make ATP** — because the electron transport chain and ATP synthase sit in the plasma membrane instead. This is the first example of a recurring principle:

> Function is conserved; location changes.

**Gram staining** distinguishes groups of bacteria by their cell wall: Gram-positive bacteria retain the crystal violet–iodine complex because of a thick peptidoglycan layer, so they stain purple; Gram-negative bacteria have a thin peptidoglycan layer plus an outer membrane, so they lose the violet on decolourisation and take up the counterstain, appearing pink. The Gram stain is still a first-line laboratory step because the wall differences determine which antibiotics can even reach the cell.

## Eukaryotic cell overview

The defining feature is internal compartmentalisation. Compartmentalisation is what allows different, incompatible conditions to exist side by side — a lysosome can maintain an acidic interior while the surrounding cytoplasm remains near neutral; a nucleus can maintain a protected genome while transcription proceeds in a controlled space.

```
NUCLEUS          DNA stored, controlled access, transcription
   │
   ├─→ mRNA ─→ RIBOSOME → protein
   │                    ↓
   │              ROUGH ER → GOLGI → vesicles → lysosome / secretion
   │
   ├─→ mitochondria: oxidation → ATP
   ├─→ peroxisomes: fatty acid oxidation, H₂O₂ breakdown
   └─→ cytoskeleton: shape, transport, division
```

Each organelle is covered in [02 — Cell Biology](../02-cell-biology/), and [10 — Anatomy and Physiology](../10-anatomy-and-physiology/) follows the same structure-to-function logic at organ-system scale.

## Why the distinction is not a ladder

One point is worth making explicitly, because the word *prokaryote* is often heard as meaning "simpler" or "less advanced."

Neither plan is primitive. Prokaryotes are enormously successful: they are the most numerous organisms on Earth by cell count, they have been reproducing continuously for roughly 3.5 billion years, and they occupy environments no eukaryote can tolerate — hot acidic springs, saturated salt lakes, ocean depths with no light, the interior of other organisms. Eukaryotes achieved something different: large size, multicellularity with specialised cell types, and the compartmentalisation that makes complex regulation possible.

Both are outcomes of natural selection on different problems. Eukaryotic features are not "improvements" of the prokaryotic plan; they are a different set of solutions.

## Medical relevance

**Prokaryote vs eukaryote explains why antibiotics work at all.** Most antibiotics target structures that exist only in bacterial cells: peptidoglycan cell walls, the 70S ribosome, or DNA gyrase. Human cells have none of those. This is the entire basis of antibacterial selectivity, and it explains the characteristic **toxicity profiles** of antibiotic classes.

| Antibiotic target | Present in | Human counterpart |
| --- | --- | --- |
| Cell wall (peptidoglycan) | Bacteria | None — humans have no cell wall |
| 70S ribosome | Bacteria, mitochondria, chloroplasts | 80S ribosome |
| Bacterial DNA gyrase | Bacteria | Different enzyme with a different structure |

**The mitochondrial caveat is important.** Human mitochondria have bacterial-type 70S ribosomes and bacterial-like membranes, which is why some antibiotics have mitochondrial toxicity. The usual explanation for this pattern in pharmacology is exactly this shared ancestry. The mechanism of mitochondrial toxicity is discussed in [01 — Enzymes](../01-biochemistry/05-enzymes.md) context and in 06 — Evolution.

**Eukaryotic compartmentalisation creates vulnerabilities.** Because human enzymes are separated into organelles, a drug that reaches the cytoplasm may still be unable to reach its target — and a drug that reaches a target may be unable to reach the compartment where it acts. Blood–brain barrier and gastric pH barriers are the practical versions of this principle, covered in 10 — Nervous and 10 — Digestive.

**Bacterial and viral differences change diagnosis.** Bacteria are cells and can be stained and cultured; viruses cannot be, and their genetic material is not a cell. This is why a Gram stain is a first-line test where a viral infection is suspected to have a bacterial cause, and why viral infection is often a diagnosis of exclusion.

## Key facts

- All cells come from pre-existing cells; **viruses are not cells** and have no ribosomes.
- Prokaryote = no membrane-bound nucleus. Eukaryote = nucleus enclosed by a double membrane, plus membrane-bound organelles.
- Ribosomes: **70S in prokaryotes** and in eukaryotic mitochondria and chloroplasts; **80S in eukaryotic cytosol**.
- Archaea: ether-linked, branched membranes; no peptidoglycan; not sensitive to penicillin.
- Prokaryote size (0.1–5 μm) vs eukaryote (10–100 μm); the constraint is surface area to volume.
- Surface area to volume ratio explains cell shape as well as cell size limits.
- Gram-positive = thick peptidoglycan, stains purple; Gram-negative = thin peptidoglycan plus outer membrane, stains pink.
- Mitochondria have bacterial-type ribosomes and divide by fission — evidence of endosymbiosis.
- Neither cell plan is primitive; they solve different problems.

## Practice questions

**1. Which of the following is present in a prokaryotic cell but absent from a eukaryotic cell?**

A. Peptidoglycan in the cell wall
B. Cytoplasm
C. Ribosomes
D. A plasma membrane

**Answer: A**

Explanation: Bacteria have peptidoglycan cell walls; eukaryotic cells do not. Plasma membranes, ribosomes, and cytoplasm are present in both. Note that not every prokaryote has peptidoglycan — archaea do not — but peptidoglycan is specific to bacteria among organisms with cell walls, and it is the feature the question is testing.

---

**2. Human mitochondria contain 70S ribosomes. What does this most directly indicate?**

A. Ribosomes inside mitochondria are non-functional
B. Mitochondria have bacterial-type ribosomes, consistent with their origin as engulfed bacteria
C. Mitochondria function as ribosome factories
D. Human cells are partly prokaryotic

**Answer: B**

Explanation: 70S ribosomes are the prokaryotic type. Their presence in mitochondria, along with a double membrane, bacterial-type division, and their own DNA, supports the endosymbiotic origin of mitochondria. D does not follow — a human is a eukaryote containing cells whose organelles happen to retain bacterial features. A and C are false: mitochondrial ribosomes are functional and are needed because mitochondria make some of their own proteins.

---

**3. A bacterium needs to make ATP but has no mitochondria. How does it accomplish this?**

A. It uses glycolysis to make more ATP than eukaryotes
B. It cannot make ATP
C. Its respiratory electron transport chain and ATP synthase are located in the plasma membrane
D. It imports ATP from the environment

**Answer: C**

Explanation: Function is conserved even when location changes. Bacteria place the electron transport chain and ATP synthase in their plasma membrane, which is heavily infolded in some species. ATP generation does not require the organelle, only a membrane to hold a proton gradient across. B is false — glycolysis yields far less ATP. D is false; bacteria are net ATP producers.

---

**4. Which combination of features would rule out a bacterium in a clinical sample?**

A. A cell wall and DNA located in a nucleoid region
B. A single circular chromosome and no membrane-bound nucleus
C. Membrane-bound organelles including a nucleus and mitochondria
D. 70S ribosomes and a peptidoglycan cell wall

**Answer: C**

Explanation: Membrane-bound organelles, and in particular a membrane-bound nucleus, are the defining features of a eukaryote. A bacterium lacks them by definition. A, B, and D are all genuine bacterial features — plasmids and nucleoid regions are also typical of bacteria.

---

**5. Why are cells limited in maximum size?**

A. Ribosomes cannot function in large cells
B. As a cell grows, its volume increases faster than its surface area, reducing the surface area available for exchange per unit of cytoplasm
C. DNA cannot fit inside a small nucleus
D. Cell membranes rupture above a certain size

**Answer: B**

Explanation: Surface area grows with the square of radius while volume grows with the cube, so surface area to volume ratio falls as a cell grows. Since all exchange depends on membrane surface, a larger cell cannot service its own volume. This is why cells have an upper size limit, why cells that must exchange a lot of material are flat or elongated, and why multicellularity was an advantageous strategy.

---

**6. Which statement about archaea is correct?**

A. They have membrane lipids joined by ether linkages and branched tails, making their membranes resistant to extremes
B. They are eukaryotic because they lack a nucleus
C. They contain peptidoglycan in their cell walls
D. They have 80S ribosomes

**Answer: A**

Explanation: Archaeal membranes contain ether-linked, branched isoprenoid lipids, which resist hydrolysis and extreme temperature, pH, and salinity — this is why archaea live in hot and highly saline environments. B confuses absence of a nucleus with eukaryote status; absence of a membrane-bound nucleus is what defines a prokaryote. C is false: archaea have no peptidoglycan cell wall, and their resistance to penicillin reflects this. D is false: archaeal ribosomes are 70S, like bacterial rather than human cytoplasmic ribosomes.

---

**7. Gram staining differentiates bacteria based on**

A. Their ability to grow in the presence of oxygen
B. Their DNA sequence
C. Their motility
D. The thickness and structure of the peptidoglycan layer, which determines retention of the crystal violet–iodine complex

**Answer: D**

Explanation: Gram-positive bacteria have a thick peptidoglycan layer that retains the crystal violet–iodine complex on decolourisation, so they remain purple. Gram-negative bacteria have a thin layer plus an outer membrane and lose the violet, taking up the counterstain instead. This is the first-line laboratory distinction and it carries immediate therapeutic implications, since it predicts which antibiotics can reach the target. The other options are not what the stain detects.

---

**8. Which statement best describes why neither the prokaryotic nor the eukaryotic plan can be called 'more advanced'?**

A. Eukaryotic cells are larger and therefore more advanced
B. Both plans arose independently and have no evolutionary relationship
C. Prokaryotes are primitive ancestors of eukaryotes
D. Prokaryotes have been reproducing continuously for billions of years and occupy environments no eukaryote can tolerate

**Answer: D**

Explanation: Prokaryotes are not unfinished eukaryotes; they are a distinct lineage with an equally long evolutionary history, and they succeed in extreme environments that exclude eukaryotes. B is incorrect because eukaryotic mitochondria are derived from an engulfed bacterium, so the lineages are connected by endosymbiosis. A and C express the progressive assumption this chapter is rejecting.

---

**9. A bacterium is isolated from a wound. Which structure must be damaged for lysozyme, an enzyme found in human tears, to have any effect?**

A. The peptidoglycan cell wall
B. The 70S ribosome
C. The plasma membrane
D. The nucleoid

**Answer: A**

Explanation: Lysozyme hydrolyses peptidoglycan, a bond that exists in bacterial cell walls and nowhere in the human body. That absence is precisely why the enzyme does not damage human tissue, and it is a working example of the structure-based selectivity of antibacterial agents described in [01 — Enzymes](../01-biochemistry/05-enzymes.md). It cannot touch the plasma membrane, nucleoid, or ribosome.

---

**10. A patient has an intracellular pathogen that lacks its own ribosomes. What does this imply about the pathogen?**

A. It has no genetic material
B. It cannot synthesise protein independently and must use the host cell's ribosomes
C. It cannot enter host cells
D. It is a bacterium

**Answer: B**

Explanation: Ribosomes are required for translation, so a pathogen lacking them cannot make protein and must rely on host ribosomes — the defining constraint on viruses. This is why antiviral drugs tend to target the pathogen's own replication machinery or its interaction with the host, rather than its protein synthesis. A is false because a virus still carries genetic material, either DNA or RNA. C is false because the stem already places the pathogen inside a cell, so it must be able to enter one. D is false because bacteria carry their own 70S ribosomes.