# Energy and Containment Organelles: Mitochondria and Chloroplasts

## Why it matters

Two organelles convert usable energy into forms a cell can spend: **mitochondria** make ATP from food, **chloroplasts** make ATP and sugar from light. Both are **double-membrane, self-replicating, and carry their own DNA** — a combination found nowhere else in the cell, and the reason both are understood as descendants of once-free-living bacteria.

That origin explains everything unusual about them: their two membranes, their 70S ribosomes, their division by fission, their maternal inheritance, and the specific way antibiotics can harm them. This chapter is structure and identity; the reaction pathways themselves are in [03 — Cellular Processes](../03-cellular-processes/).

## Why these two belong together

| Feature | Mitochondrion | Chloroplast |
| --- | --- | --- |
| **Membranes** | Two — outer smooth, inner folded | Two — outer smooth, inner forms **thylakoids** |
| **Own DNA** | Yes — circular, compact | Yes — circular, compact |
| **Own ribosomes** | **70S** (bacterial type) | **70S** (bacterial type) |
| **Division** | Binary fission | Binary fission |
| **Imported proteins** | Via translocases, N-terminal targeting sequences | Via translocases, N-terminal targeting sequences |
| **Energy conversion** | Chemical → chemical (ATP) | Light → chemical (ATP + sugar) |
| **Found in** | Essentially all eukaryotic cells | Plants, algae |
| **Quantity per cell** | Hundreds to thousands | Dozens to hundreds (in mesophyll) |

The right-hand column of that table is the argument: **a plant cell runs both** — chloroplasts make sugar, mitochondria burn it for ATP. Photosynthesis does not power a plant's cellular work directly; glucose does, and mitochondria process it. A leaf still consumes O₂ and releases CO₂ at night, and continuously in non-photosynthetic cells.

## Mitochondrion

### Structure → function

```
OUTER MEMBRANE          smooth; porins; freely permeable to small molecules
     │
INTERMEMBRANE SPACE     proton reservoir — the GRADIENT lives here
     │
INNER MEMBRANE           folded into CRISTAE
     │                   • electron transport chain + ATP synthase embedded
     │                   • impermeable to H⁺ — this is why the gradient holds
     │                   • cardiolipin-rich, bacterial-style lipid
     │
MATRIX                  • Krebs cycle enzymes
                        • mitochondrial DNA, 70S ribosomes
                        • pyruvate oxidation
```

**Cristae are surface area, and surface area is ATP capacity.** Cardiac myocytes — which spend ATP continuously — are packed with densely packed cristae; a cell with low energy demand has fewer. The fold is not decoration; it is the same surface-area-to-volume argument from [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md) applied inside an organelle.

**The inner membrane is the actual machine.** Its impermeability to protons is what makes the gradient storable at all; every property of the chain, the pumps, and ATP synthase in [03 — Cellular Processes](../03-cellular-processes/) depends on that one characteristic. The outer membrane's porins make it the easy layer; the inner membrane is the selective one.

### The division of labour

| Location | Work done |
| --- | --- |
| **Pyruvate oxidation** (matrix) | Pyruvate → acetyl-CoA + CO₂ + NADH |
| **Krebs cycle** (matrix) | Acetyl-CoA → CO₂; loads NADH and FADH₂ |
| **Electron transport chain** (inner membrane) | Electrons passed along carriers; H⁺ pumped into intermembrane space |
| **ATP synthase** (inner membrane) | H⁺ flows back; ATP made from ADP + Pᵢ |
| **β-oxidation** (matrix) | Fatty acids cut to acetyl-CoA |

So the matrix catabolises fuel to electrons, and the inner membrane converts those electrons into a proton gradient into ATP. **Substrate → electrons → gradient → ATP** is the whole energy story in four words, and each step is in a different compartment of the same organelle.

### Mitochondrial DNA

| Property | Detail |
| --- | --- |
| **Genome** | Circular, ~16,500 bp — tiny compared with nuclear DNA |
| **Genes** | 13 ETC subunits, 22 tRNAs, 2 rRNAs — about 37 genes |
| **Copy number** | Tens to thousands per mitochondrion; thousands per cell |
| **Inheritance** | **Maternal** — the sperm's mitochondria are destroyed after fertilisation |
| **Repair** | Limited compared with nuclear DNA; no histones, closer to bacterial packaging |
| **Code** | Slightly different genetic code from the nucleus (a bacterial legacy) |

**The consequences are directly clinical:**

- **Maternal inheritance.** A mitochondrial mutation passes to every child of an affected mother, and to none of an affected father's children. Pedigrees of mitochondrial disease look distinctive — *every child of an affected woman is affected* — which is a pattern-recognition question on every genetics paper.
- **Heteroplasmy.** One cell holds thousands of mtDNA copies. A mutation may be present in some copies and not others, and symptoms appear only when the **proportion of mutant copies crosses a threshold** — typically well above 50%. This explains why mitochondrial diseases vary so much in severity even within one family.
- **High mutation rate.** mtDNA sits near the ETC (the main source of reactive oxygen species) with limited repair. Damage accumulates with age, which is a leading component of the **mitochondrial theory of aging**.
- **Bottleneck in oocytes.** Only a few hundred mtDNA molecules seed an embryo, so a low-level mutation in a mother can reach high levels in a child by drift — genetic drift, literally, at organelle scale.

### Mitochondrial diseases

Because the ETC is the shared final pathway, defects produce **energy-hungry tissue failure**:

| Disease | Defect | Main features |
| --- | --- | --- |
| **MELAS** | mtDNA mutation (tRNA Leu) | Myopathy, encephalopathy, lactic acidosis, stroke-like episodes |
| **MERRF** | mtDNA mutation (tRNA Lys) | Myoclonic epilepsy, ragged-red fibres |
| **Leber hereditary optic neuropathy** | Complex I subunit | Acute vision loss, young adults, maternal pattern |
| **Kearns–Sayre** | Large mtDNA deletion | Progressive external ophthalmoplegia, cardiac conduction defects |

**"Ragged red fibres"** is the histology signature: muscle cells compensating for failed mitochondria proliferate them at the cell periphery, giving a ragged, red appearance under Gomori trichrome stain. The cell *tries to fix an energy deficit by building more organelles* — visible evidence of the compensation mechanism.

**Lactic acidosis is the common thread.** With oxidative phosphorylation impaired, cells fall back on anaerobic glycolysis and produce lactate — the same chemistry as 03 — Cellular Processes, running as a rescue pathway instead of an emergency one.

### The mitochondrial apoptotic switch

Mitochondria are not only energy organelles. When a cell is irreversibly damaged, the **mitochondrial outer membrane becomes permeable**, **cytochrome c** is released into the cytoplasm, and it activates the **caspase cascade** that executes apoptosis.

```
irreversible damage
      ↓
BAX/BAK form pores in the OUTER mitochondrial membrane
      ↓
cytochrome c leaks into cytosol
      ↓
apoptosome forms → caspase-9 → caspase-3/7
      ↓
ORDERLY CELL DEATH
```

**Why release from the mitochondrion?** Cytochrome c normally sits in the intermembrane space shuttling electrons in the ETC — it is already there in high concentration, already compatible with the cytoplasm's chemistry, and inaccessible unless the membrane fails. The cell uses a component of its own energy machinery as the death trigger, which makes the switch fast and hard to fire accidentally.

BCL-2 family proteins set the threshold: **BCL-2 itself blocks the pores and is anti-apoptotic**; when a cell overproduces BCL-2 it refuses to die — a mechanism exploited by many cancers. Conversely, damaged DNA stabilises **p53**, which pushes the pro-apoptotic side. The oncology/tumour-suppressor story runs straight through this organelle.

## Chloroplast

### Structure → function

```
OUTER MEMBRANE            freely permeable
     │
INNER MEMBRANE            selective; surrounds the stroma
     │
STROMA                    • Calvin cycle enzymes (RuBisCO here)
                          • chloroplast DNA, 70S ribosomes
                          • starch granules stored here
     │
THYLAKOID MEMBRANE        • photosystems, ETC, ATP synthase
     │                    • LIGHT REACTIONS happen here
     ▼
GRANA (stacks of thylakoids)   surface area for light capture
STROMA LAMELLAE               connecting grana
```

**The compartmental split mirrors the mitochondrion exactly** — but the two membranes' energy chemistry is reversed in direction:

| | Mitochondrion | Chloroplast |
| --- | --- | --- |
| **Gradient across** | Inner membrane (matrix → intermembrane space) | Thylakoid membrane (stroma → thylakoid lumen) |
| **H⁺ pumped into** | Intermembrane space | **Thylakoid lumen** |
| **Electrons come from** | Food (NADH, FADH₂) | **Water (photolysis)** — O₂ is the by-product |
| **ATP synthase faces** | H⁺ flows from intermembrane space to matrix | H⁺ flows from lumen to stroma |
| **Carbon fixated?** | No — carbon is released as CO₂ | **Yes — CO₂ → sugar in the stroma** |

Hold onto the water line: **the O₂ in the atmosphere is a waste product of splitting water at photosystem II.** Every breath is borrowing electrons that a chloroplast pulled off a water molecule.

### Chloroplast pigments and light

| Pigment | Absorbs | Appears |
| --- | --- | --- |
| **Chlorophyll a** | Blue-violet and red | Green (reflects green) |
| **Chlorophyll b** | Blue and orange-red | Green |
| **Carotenoids** | Blue-green | Yellow-orange |

Accessory pigments **extend the usable spectrum** — the same antenna-complex logic as widening a collector's range. Chlorophyll alone would waste most of sunlight's energy. In autumn, chlorophyll degrades and the carotenoids already present are unmasked — the colour change is the unmasking of pigments that were there all along.

**Why plants look green is a mismatch, not a design:** green light is largely *reflected*, not used. Photosynthesis runs on the wavelengths either side of green.

### Plastid family

All plastids interconvert and share the double membrane, own DNA, and 70S ribosomes:

| Plastid | Contents | Function | Found where |
| --- | --- | --- | --- |
| **Chloroplast** | Chlorophyll + carotenoids | Photosynthesis | Green tissue |
| **Chromoplast** | Carotenoids only | Colour for attraction | Petals, ripe fruit |
| **Leucoplast** | No pigment | Storage (starch, oil, protein) | Roots, seeds |
| **Proplastid** | Undifferentiated | Divides and becomes any of the above | Meristems, young tissue |

Ripening tomato is chloroplast → chromoplast conversion in real time: the green plastids lose chlorophyll and accumulate lycopene. **Same organelle family, different pigment programme** — again, cell state as gene expression pattern.

### Why chloroplasts matter to the rest of this course

- **Stomata** guard leaf gas exchange, and the guard cells that open them run on chloroplast ATP — structure in [05 — Structure and movement](05-structure-and-movement.md) and transport in [08 — Plant Biology](../08-plant-biology/).
- **C4 and CAM photosynthesis** are carbon-concentrating solutions to RuBisCO's oxygenase problem — evolution's fix for an imperfect enzyme, covered in 06 — Evolution and 08 — Plant Biology.
- **Photorespiration** is the cost of that imperfection, and it is a clear example of a biochemical constraint shaping whole-organ anatomy.

## Endosymbiosis: where the idea comes from

The theory that mitochondria and chloroplasts were once free-living bacteria explains every unusual feature in one stroke:

| Observation | Explanation under endosymbiosis |
| --- | --- |
| Two membranes | Outer = host's phagocytic vesicle; inner = the engulfed bacterium's own membrane |
| 70S ribosomes, circular DNA | Bacterial-type machinery retained |
| Binary fission | Bacterial division |
| Cannot be built from scratch | Imported proteins required — the organelle has lost most genes to the nucleus |
| Antibiotics targeting 70S ribosomes affect them | Shared ancestry with bacteria |

**The gene transfer is the reason they are now organelles.** Over evolutionary time most of the endosymbiont's genes moved to the host nucleus. What remains is a *minimal* genome — only the genes whose products are hard to import or needed locally — which is why mitochondrial DNA codes for only 13 proteins while thousands of mitochondrial proteins are encoded in the nucleus and imported.

**The clinical echo of that history:** antibiotics that target bacterial 70S ribosomes or bacterial membranes can **also hit mitochondrial ribosomes**, producing the mitochondrial toxicities seen with chloramphenicol, aminoglycosides, and tetracyclines. The rule from [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md) — *function conserved, location changes* — carries a price tag.

## Containment: what these organelles keep in

Both organelles are, at bottom, **containment vessels for chemistry that must not happen in the cytoplasm**:

| Organelle | What is contained | Why it must be |
| --- | --- | --- |
| **Mitochondrion** | Proton gradient; partially reduced oxygen species | A gradient across open cytoplasm would dissipate instantly; leaked radicals would damage the cell |
| **Chloroplast** | High-energy electrons from water splitting; reactive intermediates | Uncontrolled photochemistry would generate radicals throughout the cell |

**A gradient is only as good as its insulation.** The entire ATP economy of a eukaryotic cell rests on the inner mitochondrial membrane's refusal to pass protons. Remove that containment and you do not get less ATP — you get reactive oxygen species, heat, and death. This is the same logic as the lysosome's pH and the peroxisome's catalase: **compartmentalisation is what makes dangerous chemistry safe to use.**

## Medical relevance

**Mitochondria are the usual suspect in energy failure.** Any presentation with lactic acidosis, myopathy, and neurological involvement in a young patient raises mitochondrial disease — and the maternal inheritance pattern in the family history is the clue that confirms it.

**Cardiac and skeletal muscle are vulnerable first** because their ATP demand is highest and their cristae are densest. That is why mitochondrial cardiomyopathy and progressive external ophthalmoplegia dominate the phenotype: *the tissues with the least tolerance for energy failure are the first to show it.*

**Aging, neurodegeneration, and ROS.** Neurons are long-lived, post-mitotic (chapter 01), and extremely energy-demanding — they accumulate mtDNA damage with no way to dilute it by division. Mitochondrial dysfunction is therefore central to the biology of Parkinson's and Alzheimer's diseases, and the reason **oxidative stress** features in nearly every account of aging.

**Apoptosis failure = cancer; apoptosis overdrive = degeneration.** BCL-2 overexpression lets damaged cells survive — the mechanism behind follicular lymphoma, where the *t*-*BCL2* translocation places the gene under a heavy promoter. The same switch, if fired wrongly, kills neurons. **The organelle's containment of cytochrome c is therefore a therapeutic target in both directions.**

**Plant-side medicine:** chloroplast engineering is used to produce vaccines and therapeutic proteins in plants, because the organelle's own genome and high expression capacity make it a practical production compartment. A different kind of medicine, built on the same organelle biology.

## Key facts

- Both mitochondria and chloroplasts: **double membrane, own circular DNA, 70S ribosomes, binary fission, imported proteins** — the endosymbiosis signature.
- Mitochondrion: outer membrane (porins), intermembrane space (H⁺ reservoir), inner membrane (**cristae**, ETC + ATP synthase, impermeable to H⁺), matrix (Krebs cycle, β-oxidation, mtDNA).
- **Cristae = surface area = ATP capacity**; cardiac muscle has the densest cristae.
- Chloroplast: outer/inner envelope, **stroma** (Calvin cycle), **thylakoids** (light reactions) stacked into **grana**; H⁺ accumulates in the thylakoid lumen.
- **The O₂ released is from splitting water.** Plants burn their own sugars in mitochondria — photosynthesis makes fuel, mitochondria spend it.
- mtDNA: ~37 genes, **maternal inheritance**, **heteroplasmy with a threshold**, high mutation rate, limited repair.
- Mitochondrial disease = ETC failure → **lactic acidosis**, myopathy, neurological signs; ragged-red fibres = compensatory proliferation.
- **Cytochrome c release** through the outer membrane triggers the caspase cascade; **BCL-2 blocks it**.
- Plastids: chloroplast, chromoplast, leucoplast, proplastid — interconvertible, pigment programmes switched by gene expression.
- Antibiotics aimed at bacterial 70S ribosomes/mitochondria can cause **mitochondrial toxicity** because of shared ancestry.

## Practice questions

**1. Which feature of the inner mitochondrial membrane is essential for ATP production?**

A. Its porins allow free passage of protons
B. It is impermeable to H⁺, so the pumped proton gradient can be stored
C. It contains ribosomes for protein synthesis
D. It is continuous with the plasma membrane

**Answer: B**

Explanation: The electron transport chain pumps protons into the intermembrane space, and ATP synthase harvests the return flow. If the inner membrane leaked protons, the gradient would dissipate and no ATP would be made — containment *is* the mechanism. Porins are in the outer membrane (A), and ribosomes are in the matrix, not the membrane (C).

---

**2. A woman with a mitochondrial mutation passes the mutation to**

A. All her children
B. Half her children, independent of sex
C. None of her children
D. Only her sons

**Answer: A**

Explanation: Mitochondria in the zygote come almost entirely from the egg, because the sperm's mitochondria are destroyed after fertilisation. An affected mother therefore transmits the mutation to all her children; an affected father transmits to none. This maternal pattern in a pedigree is the standard identifier for mitochondrial inheritance.

---

**3. Why do antibiotics that target bacterial 70S ribosomes sometimes cause toxicity in human patients?**

A. Human cytoplasmic ribosomes are also 70S
B. Mitochondria contain bacterial-type 70S ribosomes, so the drug can impair mitochondrial translation
C. Human cells have no ribosomes of their own
D. The antibiotics bind DNA rather than ribosomes

**Answer: B**

Explanation: Mitochondria retained bacterial-type 70S ribosomes from their endosymbiotic ancestor, and drugs that distinguish 70S from 80S can therefore hit them too. Human cytosolic ribosomes are 80S — which is why these drugs are antibacterial in the first place — but the mitochondrial exception produces the observed toxicities. C and D are factually wrong.

---

**4. In a chloroplast, the light reactions and the Calvin cycle occur in which compartments?**

A. Light reactions in the stroma; Calvin cycle in the thylakoid lumen
B. Light reactions in the thylakoid membranes; Calvin cycle in the stroma
C. Both in the outer membrane
D. Both in the intermembrane space

**Answer: B**

Explanation: Photosystems and the electron transport chain are embedded in the thylakoid membrane, where water is split and the proton gradient is built across the lumen. The Calvin cycle enzymes, including RuBisCO, are soluble in the stroma. The spatial separation is what allows each set of reactions to have its own conditions — the same compartmentalisation logic as the mitochondrion.

---

**5. The oxygen released by a photosynthesising cell comes from**

A. Carbon dioxide
B. Glucose
C. Water
D. Chlorophyll

**Answer: C**

Explanation: Photosystem II splits water (photolysis) to replace electrons it loses, releasing O₂ as a by-product. CO₂ is reduced into sugar; glucose is a product, not the oxygen source; chlorophyll absorbs light but is not consumed. The entire atmospheric O₂ supply derives from this reaction.

---

**6. A muscle biopsy shows "ragged red fibres." What does this most likely indicate?**

A. Bacterial infection of muscle
B. Excessive glycogen storage
C. Compensatory proliferation of mitochondria in response to defective oxidative phosphorylation
D. Degradation of the sarcoplasmic reticulum

**Answer: C**

Explanation: Gomori trichrome stains mitochondria red; when ETC function fails, cells proliferate mitochondria at the fibre periphery in an attempt to compensate, giving a ragged red appearance under the stain. It is the histological signature of a mitochondrial myopathy, not infection, glycogen storage, or SR damage.

---

**7. Which statement about the two membranes of a mitochondrion is correct?**

A. The outer membrane is the selectively impermeable one; the inner membrane has porins
B. The outer membrane has porins and is relatively permeable; the inner membrane is folded into cristae and is impermeable to protons
C. Both membranes are identical in protein composition
D. Only the outer membrane carries electron transport proteins

**Answer: B**

Explanation: The outer membrane contains porins and passes small molecules freely; the inner membrane is the folded, impermeable, protein-dense layer carrying the ETC and ATP synthase. Their differences are functional: the inner membrane's impermeability is what lets the gradient exist, and cristae maximise the area available for it.

---

**8. Cytochrome c is released from mitochondria during**

A. ATP synthesis
B. The Krebs cycle
C. Apoptosis, after pores form in the outer mitochondrial membrane
D. The light reactions of photosynthesis

**Answer: C**

Explanation: Cytochrome c normally shuttles electrons within the intermembrane space. When BAX/BAK pores open in the outer membrane during apoptosis, it escapes into the cytosol and nucleates the apoptosome, activating caspases. Its normal role is respiratory; its released role is death signalling — one protein, two contexts.

---

**9. Which combination is characteristic of both mitochondria and chloroplasts?**

A. Single membrane and no DNA
B. Double membrane, own circular DNA, 70S ribosomes, and division by fission
C. Their own nucleus and linear chromosomes
D. Absence of any imported proteins

**Answer: B**

Explanation: The shared package — double membrane, circular genome, bacterial-type ribosomes, binary fission — is the evidence set for endosymbiotic origin. Neither has a nucleus (C), both import most of their proteins (D), and both are double-membraned (A is wrong).

---

**10. Why does a plant cell contain both chloroplasts and mitochondria?**

A. Chloroplasts make ATP for all cellular work; mitochondria are redundant in plants
B. Chloroplasts produce sugar and O₂; mitochondria oxidise that sugar to make ATP for cellular work
C. Mitochondria photosynthesise at night and chloroplasts respire during the day
D. The two organelles are the same organelle in different tissues

**Answer: B**

Explanation: Photosynthesis stores light energy in sugar; it does not directly power the cell's ATP-consuming processes. Mitochondria oxidise that sugar (and release CO₂) to generate ATP for everything from transport to division — which is why plant cells respire continuously. A is wrong because chloroplast ATP is used mainly within the chloroplast's own carbon fixation.
