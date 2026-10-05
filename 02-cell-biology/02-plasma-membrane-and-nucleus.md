# The Plasma Membrane and the Nucleus

## Why it matters

Two structures define the eukaryotic cell: the **plasma membrane**, which decides what gets in and out and what the cell is connected to, and the **nucleus**, which holds the instructions and controls when they are read. Everything a cell *is* flows from what these two structures allow.

This chapter covers them as structures — composition, architecture, and parts. The *mechanisms* of transport across the membrane, and the details of DNA packaging and gene expression, live in [03 — Cellular Processes](../03-cellular-processes/) and [05 — Molecular Biology](../05-molecular-biology/) respectively. Knowing the parts first is what makes those mechanisms readable.

## The problem the membrane solves

A cell must be a distinct chemical compartment while remaining open to exchange. Too sealed and it starves; too leaky and it is not a cell.

```
OUTSIDE                              INSIDE
(high Na⁺, high O₂,               (high K⁺, high proteins,
 near neutral pH)                   slightly negative, pH ~7.2)
              │
              │   PLASMA MEMBRANE
              │   • blocks ions and polar molecules
              │   • admits small nonpolar molecules
              │   • routes everything else through proteins
              ▼
        a boundary that is SELECTIVE, not absolute
```

The membrane maintains **two kinds of difference at once**: a difference in *composition* between cytoplasm and exterior, and a difference in *electrical charge* across the sheet. Both are stored energy, and both are used — the second one drives nerve and muscle function in 10 — Nervous and 10 — Muscular.

## Composition

| Component | Fraction | Role |
| --- | --- | --- |
| **Phospholipids** | ~50% of mass | The barrier itself — the bilayer |
| **Proteins** | ~50% of mass | Pumps, channels, receptors, enzymes, anchors |
| **Cholesterol** | Variable (high in animal cells) | Buffer of fluidity and permeability |
| **Carbohydrates** | Only on the outer face | Recognition, protection, adhesion |

### The phospholipid

```
        polar head ────►  ●━━━━━━━━
                          ●━━━━━━━━   hydrophobic tails
                          ●━━━━━━━━   (fatty acids)
```

**Amphipathic** — hydrophilic head, hydrophobic tails. Placed in water, phospholipids spontaneously form a **bilayer** with heads facing the aqueous sides and tails facing inward. No energy input is required; the structure is the lowest-energy arrangement of an amphipathic molecule in water. This is a direct application of the hydrophobic effect from [05 — Water](../00-foundations/05-water.md).

Two structural facts matter later:

- **Saturation of the tails sets fluidity.** Straight, saturated tails pack tightly; kinked unsaturated tails (cis double bonds) keep the membrane loose. The same structure–function relationship as in [02 — Lipids](../01-biochemistry/02-lipids.md).
- **Cholesterol is the buffer.** At high temperature it restrains tail movement and reduces fluidity and permeability; at low temperature it prevents tight packing and stops the membrane solidifying. Animal membranes without it are either too leaky or too stiff.

### The bilayer is a barrier by exclusion

| Molecule | Crosses freely? | Why |
| --- | --- | --- |
| O₂, CO₂, N₂ | Yes | Small and nonpolar |
| Steroid hormones | Yes | Lipid-soluble |
| Ethanol, urea (partly) | Partially | Small and weakly polar |
| Water | Slowly | Small, but polar — assisted by **aquaporins** |
| Ions (Na⁺, K⁺, Ca²⁺, Cl⁻) | **No** | Charged; dehydration cost is prohibitive |
| Glucose, amino acids | **No** | Large and polar |
| Proteins, DNA | **No** | Far too large |

**The rule:** *the barrier's permeability falls with polarity and with size.* Everything the cell needs that fails this test requires a protein — which is why membrane proteins exist in such number, and why the next two chapters of this curriculum are about the proteins that move things.

## Membrane proteins

| Type | Position | Examples |
| --- | --- | --- |
| **Integral (transmembrane)** | Span the bilayer, one or more times | Ion channels, pumps, G-protein-coupled receptors |
| **Peripheral** | Attached to one face, not inside the core | Cytoskeletal anchors, signalling proteins on the inner face |
| **Lipid-anchored** | Covalently attached to a membrane lipid | Ras, GPI-anchored proteins on the outer face |

Function by function:

- **Transporters** — channels (passive, selective pores) and pumps (active, consume ATP).
- **Enzymes** — membrane-embedded reactions, e.g. adenylyl cyclase.
- **Receptors** — bind a ligand outside, change shape, relay a signal inside. This is **transduction**: information crossing a membrane that the signal molecule itself cannot.
- **Cell adhesion molecules (CAMs)** — hold cells together and to matrix.
- **Identity markers** — especially the **MHC molecules** that mark a cell as "self," which the immune system in 10 — Immune checks continuously.

**The key structural idea:** a transmembrane protein must have hydrophobic residues facing the lipids and hydrophilic residues lining the pore or facing the cytoplasm and exterior. The same amino acid sequence principle from [03 — Proteins](../01-biochemistry/03-proteins.md) applies, with the membrane as the environment determining the fold.

## Asymmetry: the two faces are not equivalent

The membrane has an inside and an outside, and they differ in lipids, proteins, and carbohydrates.

- **Carbohydrates exist only on the outer face**, attached to proteins (**glycoproteins**) and lipids (**glycolipids**) to form the **glycocalyx** — a sugary coat used for recognition, protection, and adhesion. Blood group antigens ABO are glycolipid differences on red blood cell surfaces.
- **Phospholipid asymmetry is actively maintained.** Phosphatidylserine normally faces the cytoplasm. When a cell is doomed, an enzyme **flips it to the outer face**, and that flip is the signal phagocytes use to engulf the corpse without inflammation. Apoptosis is therefore *tagged*, not merely leaked — which prevents the contents of a dying cell from provoking an immune response.

**Medical connection:** this is why, in a population of cells, exposure of phosphatidylserine is read as "clean this up," while rupture is read as "danger." The distinction between orderly cell death and necrosis — one immunologically silent, one inflammatory — begins at the inner leaflet of a membrane.

## The membrane skeleton and cell shape

The lipid bilayer is a fluid sheet; on its own it would form a sphere with no stable shape. Shape comes from a **protein network attached to the cytoplasmic face** — spectrin and actin in red blood cells, general intermediate filaments and actin elsewhere.

```
       extracellular
  ━━━━━━━━━━━━━━━━━━━━━━━━━━   phospholipid bilayer
       │               │
  ━━━━━┿━━━ integral ━━┿━━━━   transmembrane proteins
       │               │
  ─────┴───────────────┴─────   membrane skeleton (spectrin/actin)
       │               │
       ▼               ▼
     cytoskeleton anchors (chapter 05)
```

**Spherocytosis is the illustration.** If spectrin or its anchors are defective, the red cell loses its biconcave shape and its resilience, becomes a fragile sphere, and is trapped and destroyed in the spleen — hereditary spherocytosis presents as anaemia and splenomegaly. The membrane skeleton also lets the red cell **deform to pass through capillaries narrower than itself**; without it, cells jam and lyse. Structure, here, is literally survival under mechanical stress.

## Junctions and surface specialisations

Cells in a tissue are not bags lying near each other. Four junction types connect them, each solving a different problem:

| Junction | What it does | Where it matters |
| --- | --- | --- |
| **Tight junctions (zonula occludens)** | Seal the space between cells; make a sheet impermeable | Gut lining — stops gut contents reaching blood; kidney tubule |
| **Adherens junctions + desmosomes** | Mechanical attachment to neighbours via cadherins and intermediate filaments | Skin under shear; cardiac muscle during contraction |
| **Gap junctions** | Direct cytoplasmic channels (connexons) for ions and small molecules | Cardiac muscle — synchronises contraction; smooth muscle |
| **Hemidesmosomes** | Anchor the cell to the **basement membrane** (matrix), not to a neighbour | Epithelial attachment to underlying tissue |

**The logic is division of labour again:** sealing, mechanical anchoring, and electrical coupling are three different engineering problems and need three different structures.

**Medical relevance, three direct consequences:**

1. **Tight junction failure = leaky epithelium.** Loss of junction integrity allows paracellular passage — the mechanism behind secretory diarrhoea and the increased intestinal permeability discussed in 10 — Digestive.
2. **Desmosome failure = blistering skin disease.** In pemphigus, antibodies attack desmosomal cadherins, cells separate, and blisters form — a disease caused entirely by losing one item from this table.
3. **Gap junction failure = arrhythmia.** If cardiac myocytes cannot couple electrically, conduction is delayed and disorganised. Connexin mutations cause inherited arrhythmias.

## The nucleus

The nucleus is a double-membrane organelle containing essentially the entire genome. Its functions:

1. **Storage** — DNA is protected inside a dedicated compartment.
2. **Controlled access** — DNA polymerase and RNA polymerase work here; nothing else gets in.
3. **Transcription separated from translation** — in eukaryotes, mRNA is processed and checked *before* it meets a ribosome. Prokaryotes cannot do this, which is one reason eukaryotic gene regulation is more elaborate.

### Structure

| Part | Structure | Function |
| --- | --- | --- |
| **Outer nuclear membrane** | Continuous with the rough ER; ribosomes on its cytoplasmic face | Protein import path; links nuclear and ER compartments |
| **Inner nuclear membrane** | Distinct protein set | Contacts the lamina; anchors chromatin at edges |
| **Perinuclear space** | Between the two membranes | Continuous with ER lumen |
| **Nuclear pores** | Large protein complexes (~125 proteins each) | Regulated transport of everything entering or leaving |
| **Nuclear lamina** | Mesh of lamins (intermediate filaments) inside the inner membrane | Mechanical support; chromosome attachment; mitotic disassembly |
| **Chromatin** | DNA + histones | Storage form of the genome (details in 05) |
| **Nucleolus** | Dense, membrane-less, a *region* not an organelle | rRNA synthesis and ribosome subunit assembly |

**The nucleus is therefore not a sealed bag — it is a filter with a structural skeleton.** The lamina gives it mechanical integrity, and its failure produces disease directly.

### Nuclear pores: the gate

The pore is not a hole. It is a **registry**: proteins carry signal sequences (a **nuclear localisation signal**, NLS, for import; a nuclear export signal for export) that are recognised by **importins/exportins**, which then interact with the channel. Small molecules and ions diffuse through passively; everything large is **signal-mediated and energy-dependent (Ran-GTP powered)**.

```
CYTOPLASM                          NUCLEUS
                    ┌────────────┐
   cargo + NLS ───▶ │ importin   │ ──▶ cargo released,
                    │   ──pore── │     Ran-GTP drives
                    │  Ran cycle │     the cycle forward
                    └────────────┘
```

**Why it must be regulated:** transcription factors must be able to enter on demand; DNA repair enzymes must reach damage; histones and replicative machinery must enter during S phase. Conversely, ribosomal subunits, mRNAs, and tRNAs must leave. A cell with an unregulated nuclear envelope would have no way to control which instructions are read — so **the pore is a control point for gene expression**, not just plumbing.

### Chromatin and the nucleolus

- **Chromatin** is DNA wound around histone octamers → nucleosome "beads on a string" → folded further into loops and territories. Loose **euchromatin** is being transcribed; compact **heterochromatin** is silenced. Packaging is *regulation*, and the details belong to [05 — Molecular Biology](../05-molecular-biology/).
- The **nucleolus** forms around the rRNA genes whenever ribosome production is needed and dissolves when it is not. A cell that is secreting heavily will have a large, prominent nucleolus — which is why pathologists use nucleolar size as a marker of a cell's synthetic activity, and one of the features that raises suspicion of malignancy.

**The nucleus in one line:** *DNA stored, controlled access, transcription.*

## Putting them together: how the two structures cooperate

A signal arrives at a receptor on the plasma membrane; the receptor changes shape; a relay reaches the nucleus; a transcription factor enters through a nuclear pore; a gene is transcribed; the mRNA leaves through a pore; a ribosome translates it; and the protein is either used inside, inserted into the plasma membrane, or secreted.

```
PLASMA MEMBRANE ──signal──▶ CYTOPLASM ──▶ NUCLEUS
      ▲                                        │
      │                                        │ mRNA out
      └──── new membrane protein ◀── translate ◀┘
```

Both structures are control points: **the membrane decides what information enters; the nucleus decides what is done with it.** Every chapter in this section is a deeper dive on one arrow of that diagram.

## Medical relevance

**Channelopathies — single-protein membrane diseases.** Because ion flow across the membrane is what produces electrical signals, a defective channel produces a tissue-specific electrical disease:

| Disease | Defective protein | Mechanism |
| --- | --- | --- |
| **Cystic fibrosis** | CFTR Cl⁻ channel | Thick mucus; impaired ion and water movement across epithelia |
| **Long QT syndrome** | Cardiac K⁺/Na⁺ channels | Delayed repolarisation → arrhythmia |
| **Hyperkalaemic periodic paralysis** | Na⁺ channel | Muscle cannot repolarise normally |
| **Myasthenia gravis (autoimmune)** | Antibodies against acetylcholine receptor | Signal cannot cross the postsynaptic membrane |

Each is one item from the protein table. The treatment logic follows: **restore the protein's function, block it, or bypass it.**

**Laminopathies — nuclear envelope diseases.** Mutations in lamin A cause a group of disorders including **progeria (Hutchinson–Gilford syndrome)**, where the nuclear lamina is defective, nuclei deform, and cells age rapidly. This is direct evidence that the lamina is structural, not decorative: **a cell's mechanical integrity depends on the skeleton inside its nucleus.**

**Anchor-dependent survival in cancer.** As noted in chapter 01, loss of anoikis allows metastasis. The membrane proteins involved — integrins and their matrix ligands — are actively studied as therapeutic targets, and the basement membrane's integrity is what a carcinoma must breach to become invasive.

**Osmosis at the membrane — clinical fluid therapy.** The membrane's selective permeability to water is the basis of every IV fluid decision: isotonic saline holds cell volume constant, hypotonic fluid swells cells (dangerous in neurons), hypertonic fluid shrinks them. The reasoning is entirely in this chapter's permeability table.

## Key facts

- The plasma membrane is a **phospholipid bilayer** with ~50% protein; it self-assembles because the tails are hydrophobic.
- **Cholesterol buffers fluidity** — stiffens at high temperature, prevents packing at low temperature.
- Permeability falls with **polarity and size**; ions and large polar molecules require proteins.
- Membrane proteins do transport, catalysis, **signal reception**, adhesion, and identity marking.
- The membrane is **asymmetric**: carbohydrates only outside; phosphatidylserine normally inside, flipped outward as an eat-me signal in apoptosis.
- **Tight junctions seal, desmosomes anchor, gap junctions couple electrically, hemidesmosomes attach to matrix.**
- The nucleus is a **double membrane** continuous with the ER, reinforced by the **lamina**, with **pores** that perform signal-mediated, energy-dependent transport.
- **Nucleolus** = rRNA and ribosome assembly; its prominence reflects synthetic activity.
- Eukaryotes separate **transcription from translation**; prokaryotes do not.
- Membrane defects → channelopathies, blistering skin disease, arrhythmia. Lamina defects → progeria.

## Practice questions

**1. Which molecule crosses the plasma membrane most readily without a transport protein?**

A. Glucose
B. Na⁺
C. O₂
D. Amino acid

**Answer: C**

Explanation: Oxygen is small and nonpolar, so it dissolves in and diffuses through the lipid core. Glucose and amino acids are large and polar; Na⁺ is charged. Both classes require transport proteins. The general rule — permeability decreases with polarity and size — explains the whole table.

---

**2. What is the primary role of cholesterol in an animal cell membrane?**

A. To act as an energy store within the membrane
B. To buffer fluidity and reduce permeability across a range of temperatures
C. To provide attachment points for cytoskeletal filaments
D. To form the aqueous pores of channel proteins

**Answer: B**

Explanation: Cholesterol restrains tail movement at high temperature (reducing fluidity and leakiness) and prevents tight packing at low temperature (preventing solidification). It is a buffer, not a store or a structural anchor. Membrane fluidity is a central concept of the fluid mosaic model, developed properly in 03 — Cellular Processes.

---

**3. Which membrane feature is responsible for identifying a cell as "self" to the immune system?**

A. Phosphatidylserine on the outer leaflet
B. Carbohydrates of the glycocalyx and MHC proteins
C. Cholesterol in the inner leaflet
D. Spectrin in the membrane skeleton

**Answer: B**

Explanation: Glycocalyx carbohydrates and especially MHC molecules are the surface identity markers the immune system inspects. Phosphatidylserine on the outer leaflet means the opposite — it is the "eat me" signal of an apoptotic cell. Spectrin provides shape, and cholesterol is buried in the bilayer with no identity role.

---

**4. A patient has an antibody that attacks desmosomal cadherins. What is the most likely consequence?**

A. Electrical uncoupling of cardiac muscle
B. Epithelial cells separating from one another, causing blisters
C. Failure of the nuclear lamina
D. Loss of the ability to transport glucose

**Answer: B**

Explanation: Desmosomes anchor neighbouring cells to each other via cadherins linked to intermediate filaments. Destroying them removes mechanical adhesion in epithelium, so layers split and blisters form — the mechanism of pemphigus. Gap junction failure causes electrical uncoupling (A); the nuclear lamina is unrelated (C); glucose transport is a transporter function (D).

---

**5. Which statement about nuclear pore transport is correct?**

A. All molecules diffuse freely through pores
B. Large molecules cross only when they carry a signal recognised by transport receptors, and the process requires energy
C. Only DNA can leave the nucleus
D. Pores are formed by phospholipids alone

**Answer: B**

Explanation: Small molecules diffuse passively, but large cargo — transcription factors, ribosomal subunits, mRNAs — is signal-mediated (NLS/NES) via importins/exportins and powered by the Ran-GTP cycle. Unregulated passage would destroy the cell's ability to control which factors reach the genome. DNA does not normally leave (C), and pores are massive protein complexes, not lipid structures (D).

---

**6. The nuclear lamina is a mesh of which protein family?**

A. Actin
B. Tubulin
C. Lamins
D. Keratin only

**Answer: C**

Explanation: The lamina is built of lamins, which are intermediate filaments lining the inner nuclear membrane. They give the nucleus mechanical support and provide chromosome attachment sites. Actin and tubulin belong to the cytoskeleton (chapter 05); keratins are intermediate filaments but are not the lamina's structural component.

---

**7. A cell is actively secreting large amounts of protein. Which nuclear structure would you expect to be prominent?**

A. The nucleolus
B. The perinuclear space
C. Heterochromatin
D. The inner nuclear membrane

**Answer: A**

Explanation: The nucleolus is where rRNA is transcribed and ribosome subunits are assembled, so heavy protein synthesis demands heavy ribosome production. Pathologists use nucleolar prominence as a marker of synthetic activity. Heterochromatin indicates silenced regions, not activity; the other two are not production sites.

---

**8. Which correctly matches a junction with its function?**

A. Tight junction — electrical coupling between cells
B. Gap junction — sealing the paracellular space
C. Desmosome — mechanical attachment between cells via intermediate filaments
D. Hemidesmosome — attachment between neighbouring epithelial cells

**Answer: C**

Explanation: Desmosomes bolt cells to each other through cadherins and intermediate filaments, resisting shear. Tight junctions seal (so A and B are swapped); gap junctions provide electrical and small-molecule coupling. Hemidesmosomes anchor a cell to the basement membrane — the matrix, not a neighbour (D).

---

**9. Why is exposure of phosphatidylserine on the outer membrane leaflet significant?**

A. It makes the cell more rigid
B. It is a signal that phagocytes use to engulf the cell without triggering inflammation
C. It increases the cell's rate of glucose uptake
D. It indicates the cell is dividing

**Answer: B**

Explanation: In a healthy cell phosphatidylserine is actively held on the cytoplasmic leaflet. When apoptosis is triggered, it is flipped outward and phagocytes recognise it as an eat-me signal — allowing the cell to be removed quietly. This is why apoptosis is non-inflammatory while necrosis, which spills contents, is inflammatory.

---

**10. A mutation in the CFTR gene causes cystic fibrosis. CFTR is best described as**

A. A receptor that binds a ligand outside the cell
B. A structural protein of the membrane skeleton
C. An integral membrane protein that functions as a chloride channel
D. A lipid of the outer leaflet

**Answer: C**

Explanation: CFTR is a transmembrane protein that transports chloride (and regulates other channels), so its failure disrupts ion and water movement across epithelia and produces thick mucus. It is a transport protein, not a receptor, a skeleton component, or a lipid — and it is the clearest example in this chapter of a single membrane protein whose failure causes a whole-organ disease.
