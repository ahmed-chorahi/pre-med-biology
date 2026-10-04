# Proteins

## Why they matter

Every function a cell performs is carried out by a protein or by a molecule built from one. Enzymes, receptors, transporters, antibodies, contractile elements, and structural components are all proteins. The reason is a single structural idea: **a protein is a polymer whose shape is specified by its sequence.** Change the sequence and you change the shape; change the shape and you change the function.

This chapter is the longest in the repository, and deliberately so. Almost every later chapter is an application of what is set out here.

## Amino acids

Proteins are polymers of **amino acids**. There are **20** standard amino acids used by all ordinary protein synthesis.

The structure that makes everything work:

```
        CARBOXYL GROUP  —COOH
             |
    H — α-CARBON — R GROUP
             |           ↑
        AMINO GROUP    SIDE CHAIN
           —NH₂         (variable)
```

Two features of the central carbon:

**It is bonded to four different groups.** That makes it a **stereocentre**, and there are two possible arrangements that cannot be superimposed. All amino acids in natural proteins are **L-configured** — a specific three-dimensional arrangement that the enzymes which make proteins are built to recognise. Glycine is the exception: its side chain is a single hydrogen, so it is not a stereocentre and is achiral.

**The R group is what makes each amino acid distinct.** Everything that follows — how a protein folds, whether an amino acid ends up buried or exposed, how a protein behaves — is determined by the chemistry of this side chain.

### Classifying the 20 amino acids

By the properties of the R group, because that is what predicts behaviour:

| Class | R group character | Amino acids | Where they end up in a folded protein |
| --- | --- | --- | --- |
| **Nonpolar (hydrophobic)** | Hydrocarbon; no charge, no polarity | Glycine, alanine, valine, leucine, isoleucine, proline, methionine, phenylalanine, tryptophan | **Buried** in the interior |
| **Polar uncharged** | Polar; H-bonding but no charge | Serine, threonine, cysteine, tyrosine, asparagine, glutamine | On the surface, at interfaces |
| **Acidic** | Negatively charged at physiological pH | Aspartate, glutamate | Surface; metal ion coordination |
| **Basic** | Positively charged at physiological pH | Lysine, arginine, histidine | Surface; nucleic acid binding; pH-sensitive site |

**The single most useful idea in this chapter** is the last column. In a protein folded in water, hydrophobic side chains cluster in the interior away from water, while polar and charged side chains remain on the surface in contact with water. This is not a tendency — it is a major driving force of folding. See [05 — Water](../00-foundations/05-water.md#solubility-and-the-hydrophobic-effect).

### Acidic and basic side chains, and pH dependence

Two R groups carry the ionisable groups covered in [00 — Acids, bases, and pH](../00-foundations/06-acids-bases-and-ph.md):

| Group | pK_a | State at physiological pH |
| --- | --- | --- |
| Aspartate / glutamate carboxyl (–COOH) | ~2.1 / ~4.3 | Deprotonated — **negative** |
| Lysine amino (–NH₃⁺) | ~10.5 | Protonated — **positive** |
| Histidine imidazole | ~6.0 | Roughly half protonated near pH 7.4 |
| Cysteine thiol (–SH) | ~8.3 | Mostly uncharged |

**Histidine is the pH-sensitive one**, and this is why it is disproportionately important in enzyme active sites. Its side-chain pK_a is about 6.0, so at pH 7.4 roughly 96% of histidine residues are unprotonated — but because the pK_a is close to physiological pH, a small local shift in the environment, or a change in pH toward 6, shifts the protonated fraction substantially. That is exactly what catalytic acid–base chemistry requires. Many enzymes position a histidine to donate a proton in one step of a reaction and accept one in the next.

### Non-standard residues

Cysteine and proline are worth separate attention because they are structurally exceptional.

**Cysteine** — the only amino acid with a free thiol (–SH) group. Two cysteines can oxidise to form a **disulfide bond (–S–S–)**:

```
Cysteine —SH  +  HS — Cysteine  +  loss of 2H⁺ and 2e⁻
      ↓ oxidation
Cysteine — S — S — Cysteine      disulfide bridge
```

Disulfide bonds are **covalent**, and they are strong. They occur in proteins that function outside the cell — in connective tissue and in secreted proteins — where reducing conditions do not exist. Inside the cytoplasm, where the reducing environment would break them, proteins use other interactions instead.

**Proline** — its R group loops back to the backbone nitrogen, forming a rigid ring. Consequences:

- It restricts rotation, so proline introduces a **bend or kink** into a polypeptide chain.
- It cannot donate a backbone hydrogen bond, because its nitrogen carries no hydrogen.
- At the start of a chain, an N-terminal proline prevents cleavage, because cleavage requires a free amino group.

Proline is why alpha-helices terminate. It is also a frequent finding in collagen: roughly one in every three residues of the collagen triple helix is a proline, and the repeating pro-rich pattern is what produces collagen's distinctive helical geometry.

### Essential amino acids

The body cannot synthesise all twenty. Those that must be obtained from the diet are **essential amino acids**:

| Class | Essential amino acids |
| --- | --- |
| **Necessary** | Histidine, isoleucine, leucine, lysine, methionine, phenylalanine, threonine, tryptophan, valine |
| **Conditionally essential** | Arginine, cysteine, glutamine, tyrosine — synthesised normally, but may become essential under illness, stress, or growth |

A dietary deficiency limits protein synthesis to the availability of the limiting amino acid — a concept developed further in 08 — Plant Biology and relevant here because it explains why a diet must supply all nine.

## Peptide bonds and the polypeptide chain

A **peptide bond** joins the carboxyl group of one amino acid to the amino group of the next:

```
AMINO ACID — COOH   +   H₂N — AMINO ACID
        ↓ condensation, releases H₂O
AMINO ACID — C(=O) — NH — AMINO ACID
                ↑
          PEPTIDE BOND
```

Properties:

- **Covalent**, and far stronger than the hydrogen bonds that maintain shape — see [04 — Chemical bonds](../00-foundations/04-chemical-bonds.md)
- Formed by **dehydration synthesis**, releasing water
- **Planar and rigid** — the six atoms of the peptide group lie in one plane, because the bond has partial double-bond character from resonance

```
        O
        ║
    — C —            all six atoms coplanar
        |
        N — H         resonance delocalisation
        |
    — Cα —
```

That rigidity is significant. Because the peptide bond itself cannot rotate freely, the only conformational freedom is rotation about the bonds on either side of the central carbon — so a polypeptide is a chain of rigid units joined by hinges. This determines which secondary structures are even possible.

A chain of a few amino acids is a **peptide**; long chains are **polypeptides**; the term **protein** is usually reserved for a folded, functional polypeptide.

## The four levels of structure

This is the standard framework, and it is worth understanding as a *hierarchy of increasing stabilisation* rather than as a list.

| Level | What it is | Main stabilisers |
| --- | --- | --- |
| **Primary** | The amino acid sequence | Covalent peptide bonds |
| **Secondary** | Local regular arrangements — α-helix, β-pleated sheet | Hydrogen bonds between backbone groups |
| **Tertiary** | The overall 3D shape of a single polypeptide | Side-chain interactions: hydrophobic effect, hydrogen bonds, ionic bonds, van der Waals contacts, disulfide bonds |
| **Quaternary** | Assembly of multiple polypeptide chains | Same interactions, between chains |

### Primary structure

The **sequence** of amino acids, specified by the gene. It contains all the information needed for everything above it, which is why a single-base change in a gene can produce a clinically significant protein defect — see 05 — Molecular Biology.

Primary structure also determines where a chain will be cleaved. Trypsin cleaves on the C-terminal side of lysine and arginine; pepsin cleaves in the middle of aromatic-containing sequences and works optimally at pH ~2. That specificity is what makes selective digestion possible.

### Secondary structure

Local arrangements stabilised by **hydrogen bonds between backbone C=O and N–H groups** — never between side chains.

**α-helix:**

```
     H   R           R   H
     |   |           |   |
 — N — Cα —     — Cα — N —
     ║   |           |   ║
     C   |           |   C
     |   |           |   |
     H   |           |   H
      H-bond to i+4
```

- Right-handed in proteins
- **3.6 residues per turn**; each hydrogen bond runs from residue $i$ to residue $i+4$
- Side chains project outward from the helix core
- **Terminated by proline** (which cannot donate a backbone hydrogen bond) or by adjacent charged residues that repel
- Common in proteins that must be fibrous and elongated — keratin in hair, myosin in muscle — as well as in most globular proteins

**β-pleated sheet:**

```
    — Cα —              — Cα —
       |    H-bond        |
    — N —                — N —
            H-bond      |
    — Cα —              — Cα —
       |                   |
    — N —               — N —
```

- Backbone zigzags into pleated planes
- Hydrogen bonds run **perpendicular** to the chain, between adjacent strands
- Strands may be **parallel** (same direction) or **antiparallel** (opposite directions); antiparallel sheets are individually more stable
- Side chains alternate above and below the plane
- Common in **fibrous** proteins: silk fibroin (β-keratin), and the amyloid fibrils involved in protein misfolding diseases

The functional difference matters more than the structural difference:

```
α-HELIX          →  elongated, flexible, rod-like      →  structural + moving
β-PLEATED SHEET  →  flat, pleated, can stack into       →  sheets, fibrils, amyloid
                    sheets and fibres
```

**Collagen has neither.** It is a distinct triple helix of three chains, with glycine every third residue, and each chain is held to the others by hydrogen bonds. That geometry is what gives tensile strength — see 09 — Human Biology.

### Tertiary structure

The three-dimensional fold of a single polypeptide — the shape that makes the protein a specific machine with a specific job.

Stabilising forces, in rough order of importance:

| Interaction | Character |
| --- | --- |
| **Hydrophobic effect** | Nonpolar side chains buried in the interior — usually the dominant driving force |
| Hydrogen bonds | Between polar side chains, and between polar side chains and water |
| Ionic bonds (salt bridges) | Between negatively and positively charged R groups |
| van der Waals contacts | Summed over many close contacts, they are substantial |
| **Disulfide bonds** | Covalent; occur mainly in extracellular proteins |

#### Denaturation

**Denaturation** is the loss of tertiary structure — the unfolding of the protein and consequent loss of function — **without** breaking the primary structure. It is caused by heat, extreme pH, heavy metals, organic solvents, or mechanical disruption, and it is usually reversible. Breaking the peptide bonds instead is **hydrolysis** or **proteolysis**, which is not denaturation and is not reversible. The distinction is a frequent exam target.

#### Misfolding

**Misfolding** is a third possibility and deserves separate mention, because it is medically important and not covered by the simple framework. A protein with the correct sequence can still fold incorrectly. Misfolded proteins can aggregate, and in some cases the aggregates themselves are harmful — the mechanism underlying prion disease and several neurodegenerative conditions, described in 10 — Nervous. Defects in folding quality control are involved in cystic fibrosis and in several inherited disorders.

### Quaternary structure

The arrangement of **multiple polypeptide chains** (subunits) into one functional protein.

| Protein | Subunits |
| --- | --- |
| Haemoglobin | 4 (2 α, 2 β) |
| Immunoglobulin (antibody) | 4 (2 heavy, 2 light) |
| ATP synthase | Multiple, with membrane-embedded and catalytic portions |
| Collagen | 3 chains in a triple helix |

Quaternary structure has three practical consequences:

**1. It increases functional capability.** Haemoglobin's four subunits give it far better oxygen handling than a single chain could manage.

**2. It allows cooperative binding.** This is the important one. In haemoglobin, binding of one oxygen molecule increases the affinity of the remaining subunits for oxygen. The consequence is visible in the oxygen–haemoglobin dissociation curve:

```
WITHOUT COOPERATIVITY         WITH COOPERATIVITY
                              
O₂ saturation                  O₂ saturation
    │        ______               │      _______
    │     __/                     │    _/
    │  __/                        │  _/     ← steep in the middle range
    │_/                           │_/          = efficient loading & unloading
    └────────── PO₂                └────────── PO₂
```

The sigmoidal shape means haemoglobin loads oxygen efficiently at the high partial pressures of the lungs and releases it readily at the lower partial pressures of tissues. A protein that bound oxygen independently would be much less effective. It is also why **fetal haemoglobin**, which binds 2,3-BPG more weakly and therefore has a left-shifted curve, can obtain oxygen from maternal blood across the placenta.

**3. It allows allosteric regulation.** Molecules bind at a site away from the active site and change the protein's activity. This is how enzymes are regulated, and how 2,3-BPG, CO₂, and H⁺ all shift haemoglobin's curve.

**Common confusion:** haemoglobin has quaternary structure; a single myoglobin chain does not. Myoglobin is a monomer, which is why it has a hyperbolic curve rather than a sigmoidal one, and why it is found in muscle as an oxygen store rather than as a transporter.

## Protein folding and chaperones

Folding is not random, but it is not a simple one-pass process either. The chain explores conformations, and the folded state is usually the lowest-energy one — but hydrophobic residues can become trapped, and chains can tangle or aggregate.

**Molecular chaperones** assist without becoming part of the final structure. They prevent inappropriate aggregation, provide a temporary hydrophobic chamber for a chain that must fold in isolation, and help a misfolded protein refold or be destroyed.

This matters clinically because folding disorders are a distinct disease class:

| Mechanism | Example |
| --- | --- |
| Misfolding due to a mutated sequence | Cystic fibrosis — a misfolded channel protein retained and degraded rather than reaching the membrane |
| Misfolding/aggregation | Prion disease, Alzheimer's, Parkinson's |
| Failure of post-translational modification | Several inherited disorders |

## Functions

| Function | Example |
| --- | --- |
| **Enzymatic** | Nearly all biological catalysis — see [05 — Enzymes](05-enzymes.md) |
| **Structural** | Collagen, keratin, elastin |
| **Transport** | Haemoglobin, transferrin, membrane carriers |
| **Signalling** | Insulin, growth hormone; many membrane receptors |
| **Immune** | Antibodies |
| **Contractile** | Actin, myosin |
| **Receptor** | Membrane and nuclear receptors |
| **Defensive** | Clotting proteins, complement |
| **Regulatory** | Transcription factors; 2,3-BPG in haemoglobin |

## Medical relevance

**Protein shape is where most drug targets and most diseases live.** A drug binds a specific three-dimensional pocket with non-covalent interactions. It works because its shape and charge complement the target's. Two consequences:

- **Enzymes and drugs are chiral.** A drug's enantiomer may fit the target or not, so the same molecule can have very different effects as different stereoisomers. See [05 — Enzymes](05-enzymes.md#chiral-molecules-and-enantiomers).
- **Changing a protein's shape changes what can bind.** This is the mechanistic basis of a large number of drug actions.

**Sickle cell disease is a primary structure defect with a structural consequence.** A single amino acid substitution in the β-globin chain (glutamate → valine at position 6) alters the surface of haemoglobin. The hydrophobic valine creates a patch on the deoxygenated form that fits a hydrophobic pocket on another haemoglobin molecule:

```
NORMAL Hb                    MUTANT Hb (sickle)
surface is hydrophilic        one valine creates a hydrophobic patch
  ↓                             ↓ freely soluble            ↓ polymerises into fibres
                                ↓ polymerises → sickling
```

The fibres distort the red cell into a sickle shape, which impairs deformability and blocks capillaries. Note the causal chain: **gene → amino acid → surface chemistry → protein assembly → cell shape → vessel occlusion.** Each arrow is a different level of organisation from [00 — Biological organization](../00-foundations/02-biological-organization.md).

**Fibrinogen to fibrin.** Fibrinogen is a soluble plasma protein. When clotting is triggered, thrombin cleaves a short peptide from each fibrinogen molecule, exposing a binding site, and the molecules polymerise into insoluble fibrin threads that stabilise the clot. The defect that makes fibrinogen soluble is the same cleavage that makes fibrin polymerise — see 10 — Immune.

**Collagen provides tensile strength.** Its triple helix, with glycine every third residue, allows the three chains to pack tightly, and hydrogen bonds between chains give tensile strength along one axis. The main collagen disorders — osteogenesis imperfecta (type I collagen), Alport syndrome (type IV collagen), and the Ehlers–Danlos syndromes (defects in collagen structure or processing) — are all faults in collagen or its handling, which is why they present as fragility of skin, bone, blood vessels, and ligaments simultaneously. See 09 — Human Biology.

**Protein shape is pH-dependent.** Changing pH alters the ionisation of acidic and basic side chains, changing charge, changing hydrogen bonding, changing shape, changing function. The mechanism behind denaturation, and behind why enzymes have pH optima, is the same. See [06 — Acids, bases, and pH](../00-foundations/06-acids-bases-and-ph.md).

**Denaturation versus proteolysis — the distinction that matters.** Denaturation preserves the primary structure and is usually reversible; proteolysis breaks peptide bonds and destroys it. This is why boiled collagen becomes gelatin and can be re-formed, while acid plus a protease produces absorbable peptides and cannot be re-formed.

## Key facts

- **20 standard amino acids**, all **L-configuration**, each with a central **stereocentre** and a variable **R group**.
- Nonpolar R groups → buried in the protein interior. Polar and charged → surface. **This drives folding.**
- Acidic side chains (Asp, Glu) → negative at pH 7.4. Basic (Lys, Arg, His) → positive. **Histidine** is the pH-sensitive one, which is why it features in active sites.
- **Peptide bond** = covalent, formed by dehydration, **planar and rigid**.
- **Primary** = sequence. **Secondary** = α-helix, β-sheet, stabilised by *backbone* hydrogen bonds. **Tertiary** = 3D fold, stabilised by side-chain interactions + the hydrophobic effect. **Quaternary** = assembly of multiple chains.
- α-helix: **3.6 residues/turn**, H-bond $i \to i+4$. β-sheet: strands H-bonded perpendicular to the chain, parallel or antiparallel.
- **Proline** kinks chains and terminates helices; **cysteine** forms covalent **disulfide bridges** outside the cell.
- **Denaturation** = loss of shape, peptide bonds intact, usually reversible. **Proteolysis** = bonds broken.
- **Cooperativity** in haemoglobin produces a sigmoidal dissociation curve.
- **Nine essential amino acids**; arginine, cysteine, glutamine, tyrosine are conditionally essential.

## Practice questions

**1. Which statement about the α-helix is correct?**

A. It is broken by proline, which can form a backbone hydrogen bond
B. It is stabilised by hydrogen bonds between adjacent amino acid side chains
C. It is stabilised by hydrogen bonds between backbone C=O and N–H groups four residues apart
D. It is found only in fibrous proteins

**Answer: C**

Explanation: α-helix backbone hydrogen bonds run from the C=O of residue $i$ to the N–H of residue $i+4$, forming about 3.6 residues per turn. B is wrong because hydrogen bonding in secondary structure involves backbone groups, never side chains. A is backwards: proline *breaks* helices because its ring nitrogen carries no hydrogen to donate. D is wrong — α-helices are abundant in globular and soluble proteins as well as in fibrous ones.

---

**2. A protein's amino acid sequence is normal, but it fails to fold into its functional shape and aggregates instead. What is the most accurate description?**

A. The protein has been denatured by a change in pH
B. The protein has been hydrolysed
C. The protein has lost its quaternary structure
D. The protein has undergone misfolding, since the primary structure is intact but the tertiary structure is incorrect

**Answer: D**

Explanation: Misfolding is a failure of folding, distinct from denaturation. The sequence — the primary structure — is normal, but the chain adopts an incorrect conformation and may aggregate. This distinction matters because misfolding disorders involve proteins that are chemically correct yet functionally wrong, which is a different therapeutic problem from a damaged molecule. B describes proteolysis, which breaks covalent bonds. A is possible but is a different mechanism that should be supported by a specific denaturant. C presupposes a multimeric protein, which is not stated.

---

**3. Why do nonpolar amino acid side chains tend to be found in the interior of a folded globular protein?**

A. Nonpolar side chains are heavier and therefore sink
B. Nonpolar side chains carry a charge that is neutralised in the interior
C. Nonpolar side chains bond covalently to the backbone
D. Nonpolar side chains cannot hydrogen-bond with water, so clustering them in the interior minimises the disruption of surrounding water

**Answer: D**

Explanation: Clustering nonpolar groups together is the hydrophobic effect: it minimises the region of nonpolar surface exposed to water, which minimises the ordered water molecules required around nonpolar surfaces. This is the major driving force of folding. A is wrong — mass is not the mechanism and it is not negligible. B and C misdescribe the side chains, which are nonpolar and uncharged.

---

**4. Which pair of statements correctly contrasts denaturation with proteolysis?**

A. Denaturation changes shape with peptide bonds intact; proteolysis breaks peptide bonds
B. Both destroy the primary structure
C. Both are caused by heat
D. Denaturation breaks peptide bonds; proteolysis changes protein shape

**Answer: A**

Explanation: Denaturation disrupts the noncovalent interactions maintaining tertiary structure — the primary structure survives, which is why it is often reversible. Proteolysis hydrolyses peptide bonds, changing the primary structure and irreversibly altering the protein. C is wrong because heat can cause either, depending on conditions. D is wrong because denaturation preserves the primary structure by definition.

---

**5. Haemoglobin has four subunits while myoglobin has one. What is the functional advantage of haemoglobin's quaternary structure?**

A. Four subunits bind more oxygen molecules, and binding of one increases the affinity of the others
B. Four subunits make haemoglobin less prone to pH changes
C. Myoglobin cannot bind oxygen at all
D. Haemoglobin can carry carbon dioxide because it has four chains

**Answer: A**

Explanation: Four binding sites allow more oxygen to be carried, and cooperativity means the first binding event increases the affinity of the remaining sites — producing the sigmoidal dissociation curve that makes loading in the lungs and unloading in tissues both efficient. This is also why fetal haemoglobin, which binds 2,3-BPG less weakly, has a left-shifted curve and can extract oxygen from maternal blood. C is false — myoglobin does bind oxygen and serves as a muscle oxygen store. B and D misdescribe the mechanism.

---

**6. A protein denatures when the pH changes. Which explanation is correct?**

A. Protonation states of acidic and basic side chains change, altering charge and hydrogen bonding, which alters three-dimensional structure
B. The disulfide bonds break
C. The peptide bonds break at extreme pH
D. The protein gains or loses amino acids

**Answer: A**

Explanation: Altered pH changes the ionisation of acidic and basic side chains, which changes their charge, their hydrogen bonding, and therefore the protein's shape and function. Peptide bonds are not broken by pH change; that is proteolysis. D is wrong because denaturation does not add or remove amino acids. B is wrong because disulfide bonds are covalent and comparatively stable at mild pH changes.

---

**7. In sickle cell disease, a single amino acid substitution causes haemoglobin molecules to polymerise and red cells to sickle. Which sequence of levels is correctly stated?**

A. Organelle → tissue → organ → cell
B. Gene → amino acid → protein surface → protein assembly → cell shape
C. Tissue → gene → protein → cell shape
D. Cell → protein → gene → tissue

**Answer: B**

Explanation: The causal chain runs from the molecular level upward: a mutated base changes an amino acid, which changes the protein's surface chemistry, which changes how it assembles with itself, which changes the shape of the red cell. Each step is a different level of organisation, which is exactly why a one-base molecular change produces a clinical disease. The other options have the direction of causation reversed.

---

**8. Collagen has a triple helix with glycine at every third position and hydrogen bonds between the chains. Why does this arrangement give great tensile strength?**

A. Glycine's side chain is large, packing the chains closely
B. Glycine contains disulfide bonds linking the chains
C. The tightly packed chains are held together by many hydrogen bonds acting in parallel along the axis of tension
D. Collagen contains unusually high numbers of charged residues

**Answer: C**

Explanation: Glycine is the smallest amino acid, so it allows the three chains to pack tightly. Many hydrogen bonds running in parallel along the fibre axis resist pulling apart, so individual weak bonds sum to high tensile strength. A is wrong because glycine has the smallest side chain of all — a single hydrogen. B is wrong because glycine contains no sulfur, and the interchain links here are hydrogen bonds, not disulfides. D is not the basis of collagen's properties.

---

**9. Which statement about essential amino acids is correct?**

A. They are amino acids used only to make enzymes
B. They are amino acids the body cannot synthesise and must obtain from the diet, including lysine, methionine, and tryptophan
C. They are amino acids produced during protein digestion
D. The body synthesises all twenty, so none are dietary requirements

**Answer: B**

Explanation: Essential amino acids cannot be synthesised in sufficient quantity and must be obtained from the diet — nine are required, including lysine, methionine, and tryptophan. Limiting one limits protein synthesis regardless of how much of the others are available. A is false. C and D misdescribe what they are; essentiality is defined by the body's capacity to synthesise them, not by function or origin.

---

**10. A patient has a prolonged clotting time and a normal platelet count. Which protein class is most directly implicated?**

A. Structural protein
B. Transport protein
C. Defensive protein involved in a cascade that converts a soluble precursor to an insoluble product
D. Contractile protein

**Answer: C**

Explanation: Fibrinogen is a defensive plasma protein: thrombin cleaves a short peptide from it, exposing a binding site, and the molecules polymerise into insoluble fibrin that stabilises the clot. A defect in this conversion or in a factor upstream in the cascade prolongs clotting without changing the platelet count. Structural, transport, and contractile proteins are not what form the clot.

---

**11. Why does proline introduce a bend into a polypeptide chain?**

A. It is the only amino acid with a thiol group
B. Its ring structure loops back to the backbone nitrogen, restricting rotation
C. Its side chain is bulky
D. It forms disulfide bridges

**Answer: B**

Explanation: Proline's side chain bonds to its own backbone nitrogen, forming a five-membered ring that restricts rotation and imposes a kink. This is why proline terminates α-helices — its backbone nitrogen has no hydrogen to donate — and why proline-rich repeating sequences produce the collagen helix. C and D describe cysteine.