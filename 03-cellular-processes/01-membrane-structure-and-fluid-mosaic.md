# Membrane Structure and the Fluid Mosaic Model

## Why it matters

[02 — Cell Biology](../02-cell-biology/02-plasma-membrane-and-nucleus.md) gave you the parts list: phospholipids, cholesterol, proteins, carbohydrates. This chapter gives you the **model** — what kind of structure a membrane actually is — and the evidence that produced it. The model matters because every mechanism that follows in this section assumes it: transport proteins must be able to *move*, signals must be able to *cluster*, and vesicles must be able to *bend and fuse*. Those behaviours are only possible if the membrane is a **fluid solvent with floating machines**, not a rigid wall.

## The problem a membrane model must solve

Any acceptable model has to explain four observations at once:

1. **The membrane is a barrier** that nevertheless admits specific molecules.
2. **It is thin** — about 7–10 nm under an electron microscope, consistent with a lipid bilayer.
3. **It is flexible** — cells deform, vesicles bud and fuse, red blood cells fold to cross capillaries.
4. **It contains proteins** that perform everything the lipid cannot.

## How the models evolved

| Model | Year | Claim | Why it failed |
| --- | --- | --- | --- |
| **Lipid bilayer** (Gorter & Grendel) | 1925 | Membrane lipids form a bilayer | Correct core, but said nothing about proteins |
| **Sandwich (Davson–Danielli)** | 1935 | Protein layers coat both sides of a lipid bilayer | Held for decades — but contradicted by new evidence |
| **Fluid mosaic** (Singer & Nicolson) | 1972 | Bilayer is a **fluid solvent**; proteins float in and through it as a **mosaic** | Current model |

The Davson–Danielli sandwich was finally rejected by three findings:

- **Freeze-fracture electron microscopy** split membranes down the middle of the bilayer and revealed **globular particles embedded inside** — proteins sitting *within* the bilayer, not smeared over it.
- **Membrane proteins are not uniform coats.** If they were, every membrane would have the same protein content; instead proteins vary widely by membrane, and integral proteins show the hydrophobic regions needed to sit *in* the lipids.
- **FRAP and cell fusion** showed that membrane components **move laterally** — an outer surface of one kind of cell mixed with another's within minutes of fusion. A protein coat does not do that.

## The fluid mosaic model, stated properly

> A membrane is a **two-dimensional fluid** of lipid molecules in which **proteins are dissolved as a mosaic**, some floating freely, some anchored, all free to move laterally unless held.

Three words carry the whole model:

### "Fluid"

```
lateral movement (fast)      ← proteins and lipids diffuse in the plane
        ↕
flip-flop (essentially never spontaneously)   ← enzymes (flippases) do it
        ↕
transverse asymmetry is MAINTAINED — inner and outer leaflets differ
```

- **Lipids move laterally freely** — millions of times per second.
- **Lipid flip-flop across the bilayer does not happen spontaneously** — a polar head cannot pass through the hydrophobic core. Flippases, floppases, and scramblases do it enzymatically, which is why the asymmetry described in [02 — Cell Biology](../02-cell-biology/02-plasma-membrane-and-nucleus.md) exists at all: **the asymmetry is actively maintained, not accidental.**
- **Proteins diffuse laterally** but are often **temporarily anchored** by the cytoskeleton or by interactions with neighbours — so they are mobile, not random.

**Cholesterol sets the fluidity range**, as covered in 02: it restrains movement at high temperature and blocks packing at low temperature. The membrane is kept in a **liquid-ordered state** — neither oil nor solid.

### "Mosaic"

A patchwork of different proteins of different shapes doing different jobs — transporters, receptors, enzymes, anchors. Not a uniform layer: **areas rich in protein sit beside areas nearly pure lipid.**

### The proteins: integral and peripheral

| Type | Association | Removal | Example |
| --- | --- | --- | --- |
| **Integral (transmembrane)** | Hydrophobic regions buried in the core; often several passes | Detergents required | Ion channels, GPCRs |
| **Peripheral** | Electrostatic attachment to integral proteins or lipid heads | High salt / pH changes | Cytoskeletal linkers, inner-face signalling proteins |
| **Lipid-anchored** | Covalent lipid tail embedded in one leaflet | Cleavage of the anchor | Ras, GPI-linked proteins outside |

**A transmembrane segment has a specific signature:** ~20–25 hydrophobic amino acids per pass — typically an α-helix, since the helix's backbone H-bonds are satisfied internally and its outward face is uniformly hydrophobic. Number of passes predicts topology: a channel might cross seven times (GPCRs) or twelve times (transporters), and the *number* of passes is part of how the protein works.

## Evidence for fluidity — the experiments

| Technique | What it showed |
| --- | --- |
| **Cell fusion** (frye & Edidin) | Membrane proteins of two fused cells intermix within minutes |
| **FRAP** (fluorescence recovery after photobleaching) | Bleached spot recovers — mobile proteins diffuse back in; immobile fraction = anchored |
| **Freeze-fracture** | Intramembranous particles = embedded proteins; rejects the sandwich model |
| **Single-particle tracking** | Individual proteins diffuse, sometimes confined to "corrals" by the cytoskeleton |

**The corral finding is the refinement:** the membrane is fluid *within patches* — the cytoskeleton fences proteins into compartments, and proteins hop between corrals rarely. This explains why a receptor can be concentrated where it is needed instead of being smeared uniformly across the whole surface.

## Lipid rafts

Some lipids associate preferentially: **sphingolipids and cholesterol** form thicker, more ordered **microdomains** — "rafts" — that float in the sea of ordinary phospholipid.

```
     ═══╤═══╤═══╤═══╤═══   ordinary bilayer: unsaturated tails, disordered
        │   │   │   │
   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓     RAFT: sphingolipid + cholesterol,
        │   │   │           thicker, more ordered
        ▼   ▼   ▼
   signalling proteins sort into rafts
```

**Function:** rafts concentrate specific proteins — GPI-anchored proteins, certain receptors, Src-family kinases — so that a signal starts **where the right molecules already are**. Rafts are involved in T-cell receptor activation, viral entry (HIV and influenza exploit them), and polarised sorting in the Golgi.

They remain partly controversial in fine detail, but their functional claim is straightforward: **the membrane is not homogeneous in the third dimension either — it has thicker and thinner patches, and cells use that.**

## The glycocalyx — the outside is different

Carbohydrates extend only from the outer leaflet, forming a sugar coat. It carries blood group antigens, protects against mechanical and chemical damage, mediates cell–cell recognition, and is where many pathogens attach. **A virus binding your airway is usually binding a carbohydrate, not a protein.**

## Why the model makes the next chapters possible

| Property of the fluid mosaic | What it enables |
| --- | --- |
| Lateral fluidity | Receptors cluster after binding a ligand; vesicles **bend** and **fuse** |
| Integral proteins mobile | Transport proteins meet their substrates without being embedded at fixed points |
| Asymmetric leaflets | Distinguishable inside from outside; apoptosis signalling |
| Rafts | Pre-assembled signalling platforms |
| Self-sealing bilayer | Any tear closes spontaneously — no repair enzyme needed, because the energetics of the bilayer favour closure |

That last point deserves emphasis: **the bilayer self-seals because exposing hydrophobic edges to water is unfavourable.** The same hydrophobic effect that builds the membrane also repairs it — which is why a cut membrane does not leave a permanent hole the way a torn protein sheet would.

## Common confusion: "the membrane is permeable because it is fluid"

Fluidity and permeability are different properties. The membrane is fluid **laterally** (components slide sideways) while remaining a strong barrier **transversely** (nothing crosses without help). A fluid membrane is still impermeable to ions. Permeability is decided by polarity and size, as in [02 — Cell Biology](../02-cell-biology/02-plasma-membrane-and-nucleus.md); fluidity is decided by lipid composition and temperature. Both change with cholesterol — but in different senses.

## Medical relevance

**Membrane fluidity and anaesthesia.** One theory of general anaesthetic action holds that small nonpolar molecules dissolve in the lipid bilayer, alter fluidity and the behaviour of embedded proteins (especially ion channels), and thereby suppress neural signalling. The debate continues, but it rests entirely on the fluid mosaic model's claim that **lipids are a solvent that proteins function within**.

**Cholesterol content is a drug and disease variable.** Cells with more cholesterol have stiffer membranes; statins alter cholesterol availability; and oxidised LDL changes the lipid environment in which vascular receptors operate — a step in atherogenesis.

**Lipid rafts in infection and immunity.** HIV exploits raft domains to assemble and bud; T-cell activation requires receptor clustering in rafts. Drugs targeting raft-dependent entry are an active area of antiviral research.

**Fragility of red cell membranes.** The spectrin skeleton anchoring the membrane (02 — Cell Biology) turns the fluid sheet into an elastic, deformable sac. Defects in the skeleton or its anchors — hereditary spherocytosis, elliptocytosis — produce cells that cannot deform, are trapped in the spleen, and lyse: **fluidity plus anchoring is what a red cell needs, and losing either is a disease.**

## Key facts

- Model history: **bilayer (1925) → Davson–Danielli sandwich (1935, rejected) → fluid mosaic (Singer & Nicolson, 1972).**
- Evidence against the sandwich: **freeze-fracture particles, protein variability, FRAP and cell-fusion mixing.**
- **Fluid** = rapid lateral diffusion; **flip-flop is spontaneous essentially never** — flippases/scramblases do it, which is why asymmetry is actively maintained.
- **Mosaic** = a patchwork of mobile proteins; lateral movement is often confined to cytoskeletal "corrals."
- **Cholesterol buffers the fluid state; sphingolipid–cholesterol rafts are thicker ordered microdomains that concentrate signalling proteins.**
- Transmembrane segments are ~20–25 hydrophobic residues, usually α-helical.
- The bilayer **self-seals** because exposing hydrophobic edges to water is energetically unfavourable.
- Fluidity (lateral movement) ≠ permeability (crossing the membrane); both matter, neither substitutes for the other.

## Practice questions

**1. Which experiment provided the most direct evidence that membrane proteins can move laterally within the plane of the membrane?**

A. Measurement of membrane thickness by electron microscopy
B. Fusion of two cells with different surface proteins followed by mixing of those proteins within minutes
C. Extraction of lipids and measurement of their fatty acid composition
D. Titration of membrane phospholipid content

**Answer: B**

Explanation: In the Frye–Edidin experiment, human and mouse cells were fused and their distinct surface antigens were tracked; the markers intermixed within about 40 minutes, demonstrating lateral diffusion. Static measurements (A, C, D) can show composition and structure but cannot show movement — and the sandwich model was compatible with a static picture until mobility was measured.

---

**2. Why does spontaneous flip-flop of phospholipids between leaflets essentially not occur?**

A. The membrane is too fluid to allow it
B. The polar head group cannot pass through the hydrophobic core of the bilayer
C. Proteins actively prevent it in both directions at all times
D. The tails are too short to let a head group pass

**Answer: B**

Explanation: Translocation requires dragging a charged, hydrated head group through a nonpolar interior — a large energetic barrier. Flip-flop therefore happens only enzymatically, via flippases, floppases, and scramblases. That is exactly why the membrane's asymmetry persists: it is not an accident of formation but a maintained state. Fluidity concerns lateral motion, not transverse motion (A).

---

**3. Freeze-fracture electron microscopy was important because it**

A. Showed membranes are made of proteins only
B. Revealed globular particles embedded within the interior of the bilayer, contradicting the idea of smooth protein coats on both surfaces
C. Proved the Davson–Danielli model
D. Demonstrated that cholesterol is absent from membranes

**Answer: B**

Explanation: Fracturing splits the bilayer down its hydrophobic midline, exposing the internal face; the particles seen there are integral proteins sitting inside the lipid — inconsistent with extrinsic protein layers coating the outside. That observation, together with protein variability and mobility data, killed the sandwich model.

---

**4. A transmembrane protein is predicted to have a membrane-spanning region of 23 hydrophobic amino acids. What structure is it most likely to adopt there?**

A. A β-barrel exposed to water
B. An α-helix whose outward-facing surface is uniformly hydrophobic
C. An unstructured loop
D. A disulfide-bonded sheet

**Answer: B**

Explanation: A single α-helix of roughly 20–25 residues spans the ~3 nm hydrophobic core; its backbone hydrogen bonds are satisfied internally and its exterior presents only nonpolar side chains to the lipids. β-barrels do occur — but in outer membranes of bacteria and mitochondria, typically with many more strands — and an unstructured stretch would expose backbone groups to the hydrophobic interior.

---

**5. What is the correct interpretation of FRAP showing partial recovery of fluorescence after photobleaching?**

A. The bleached proteins were destroyed
B. Some membrane proteins are mobile and diffuse back into the bleached area, while an immobile fraction is anchored
C. The membrane is impermeable to fluorescent dyes only
D. Recovery proves the membrane is solid

**Answer: B**

Explanation: FRAP bleaches a spot and watches unbleached, fluorescent neighbours diffuse in. The rate of recovery reports lateral mobility; the plateau below 100% reports an immobile fraction tethered by cytoskeleton or junctions. Fluidity is partial and regulated — neither fully free nor fixed (D).

---

**6. Sphingolipid- and cholesterol-rich membrane microdomains are called**

A. Translocons
B. Lipid rafts
C. Glycocalyx
D. Flippases

**Answer: B**

Explanation: Rafts are thicker, more ordered domains that sort and concentrate certain receptors and signalling proteins, facilitating rapid signal assembly. The glycocalyx is the outer carbohydrate coat; flippases move lipids between leaflets; translocons are protein-conducting channels.

---

**7. Which property of the lipid bilayer allows a punctured plasma membrane to reseal without enzymatic repair?**

A. Covalent crosslinking of lipids after injury
B. The energetic unfavourability of exposing hydrophobic edges to water, so the bilayer closes spontaneously
C. Immediate synthesis of new phospholipids at the wound site
D. Protein plugs that always cover membrane holes

**Answer: B**

Explanation: Exposed lipid tails contact water only at the edge of a tear, and the hydrophobic effect drives those tails to bury themselves again — the sheet closes like a fluid film. This is a property of the bilayer's physics, not of repair enzymes (C) or built-in plugs (D).

---

**8. A protein is removed from a membrane by changing pH and ionic strength, without detergents. It is most likely**

A. An integral transmembrane protein
B. A peripheral protein attached electrostatically
C. A lipid-anchored protein
D. A cholesterol molecule

**Answer: B**

Explanation: Peripheral proteins sit on a surface held by electrostatic and hydrogen bonds, so salt or pH changes disrupt the attachment. Integral proteins require detergents to extract them from the hydrophobic core; lipid anchors need cleavage of the covalent lipid; cholesterol is a lipid, not a protein.

---

**9. The Davson–Danielli "sandwich" model proposed that membranes consisted of**

A. A single layer of phospholipid with proteins inside
B. Protein layers coating both surfaces of a lipid bilayer
C. Pure lipid with no protein
D. Two protein layers with lipid in between

**Answer: B**

Explanation: The sandwich model kept the bilayer but added continuous protein films on each face — a static, uniform picture. Freeze-fracture showing particles *within* the bilayer, variable protein content, and observed lateral mobility of surface markers were the findings that displaced it in favour of the fluid mosaic model.

---

**10. Why does the fluid mosaic model require membrane proteins to be mobile for vesicle formation to work?**

A. Vesicles are made entirely of protein
B. Budding requires lipids and proteins to rearrange laterally so the membrane can curve and pinch without tearing
C. Fixed proteins would make the membrane too rigid to exist
D. Proteins must be synthesized at the site of every bud

**Answer: B**

Explanation: Curving a flat sheet requires components to flow into and away from the budding region — lipids sliding, coat proteins assembling and deforming the membrane, then disassembly after fission. A static mosaic could not bend. New synthesis (D) is not required per vesicle; existing components are recycled.
