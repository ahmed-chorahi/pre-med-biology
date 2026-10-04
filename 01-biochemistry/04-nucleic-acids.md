# Nucleic Acids

## Why they matter

Every other macromolecule has a limited range of shapes. Nucleic acids have essentially unlimited informational variety, because the order of four bases can be specified in any sequence. That is what allows a single human genome to specify ~20,000 proteins, and what allows those proteins to be different in each cell despite sharing the same DNA.

The chemical design is elegant: **two strands held together by hydrogen bonds that can be separated and reformed on demand.** Break them for replication, re-form them for storage. That reversibility is what makes the whole system work.

## The nucleotide

**Nucleotides** are the monomers of nucleic acids. Each has three components:

```
        BASE
         │        nitrogen-containing ring
         │
  PHOSPHATE — SUGAR
  (phosphate group) (pentose)
```

| Component | In DNA | In RNA |
| --- | --- | --- |
| Sugar | **Deoxyribose** — 2-deoxyribose | **Ribose** |
| Bases | Adenine, guanine, cytosine, thymine | Adenine, guanine, cytosine, **uracil** |

**The one difference in chemistry that matters most:** deoxyribose is missing the oxygen at the 2′ carbon.

```
RIBOSE                 DEOXYRIBOSE
   OH  ← 2′ carbon        H   ← 2′ carbon
   │                      │
   │                      │
  HO                     HO
```

This single change has three consequences:

1. **DNA is more chemically stable.** The 2′-OH group can attack a neighbouring phosphodiester bond, causing hydrolysis. Without it, DNA can persist for millions of years — a requirement for information storage. RNA, having the 2′-OH, is much more susceptible to alkaline hydrolysis.
2. **DNA is more resistant to damage.** It survives for decades in a cell and indefinitely outside one; RNA degrades within minutes. That difference in stability is the reason DNA can be the archival molecule.
3. **It gives the molecule a slightly different helical geometry**, contributing to DNA's characteristically more compressed, wider helical form.

**Nucleotide vs nucleoside.** A **nucleoside** is the sugar plus the base, with **no phosphate**. Adding phosphate gives a **nucleotide**. This is a real distinction, not pedantry — nucleosides are the products of nucleic acid degradation and cannot be polymerised without phosphorylation.

**ATP is a nucleotide**, and so are the coenzymes NAD⁺, FAD, and CoA. This is not a coincidence: they use nucleotide chemistry to do jobs other than information storage. See [05 — Enzymes](05-enzymes.md).

## Nucleobases

Bases fall into two structural classes, and the distinction is worth knowing because it explains the base-pairing geometry.

| Class | Members | Structure | Pairs with |
| --- | --- | --- | --- |
| **Purine** — two fused rings | Adenine (A), guanine (G) | Larger | Pyrimidines |
| **Pyrimidine** — one ring | Cytosine (C), thymine (T), uracil (U) | Smaller | Purines |

This is **complementary pairing**: a purine always pairs with a pyrimidine.

```
TWO HYDROGEN BONDS                 THREE HYDROGEN BONDS
                                  
A  ═════  T                       G  ════  C
   ║    ║                            ║ ║ ║
     ║ ║                             ║ ║ ║
     ║ ║                             ║ ║ ║
                                    
```

A purine–purine pair would be too wide to fit the uniform helical geometry; a pyrimidine–pyrimidine pair would be too narrow. **The pairing is dictated by geometry as much as by chemistry.**

### DNA vs RNA bases

| | DNA | RNA |
| --- | --- | --- |
| Purines | Adenine, guanine | Adenine, guanine |
| Pyrimidines | **Cytosine, thymine** | **Cytosine, uracil** |
| Unique base | Thymine = 5-methyluracil | Uracil |
| Typical base content | A = T, G = C | A = U, G = C |

**Why uracil instead of thymine?** Cytosine spontaneously deaminates to uracil. Because uracil is not a normal DNA base, cytosine is identifiable as correct when it appears in DNA. Thymine is distinguished from uracil by an extra methyl group, which deamination cannot remove. So uracil in DNA is detectable damage; cytosine→uracil in RNA is not, because uracil belongs there.

**The practical consequence:** uracil in a DNA sample is read as a mutation, whereas the same change in RNA is invisible. See 05 — Mutations.

## DNA structure

**DNA** is a double helix of two **antiparallel** polynucleotide strands, held together by hydrogen bonds between complementary bases.

```
BACKBONE — SUGAR ─ PHOSPHATE ─ SUGAR ─ PHOSPHATE ─   (covalent, strong)
             │                                    │
           BASE                                  BASE
             ║  hydrogen bonds                   ║
             ║                                    │
BACKBONE — SUGAR ─ PHOSPHATE ─ SUGAR ─ PHOSPHATE —
```

Three structural features must all be correct, and they often get conflated:

| Feature | What it means |
| --- | --- |
| **Double-stranded** | Two strands, hydrogen-bonded together |
| **Antiparallel** | One runs 5′→3′, the other 3′→5′ |
| **Complementary** | A pairs with T, G pairs with C, in both strands |

```
    5' ════════ 3'
    ║ ║ ║ ║ ║ ║    the two backbones run in OPPOSITE directions
    3' ════════ 5'
```

### The 5′ and 3′ ends

Each strand has a chemically distinct end, and the distinction is not cosmetic — it determines which enzymes can act.

- **5′ end** — the phosphate is attached to the 5′ carbon of the sugar
- **3′ end** — the free hydroxyl group is on the 3′ carbon

```
    5' — P — SUGAR — P — SUGAR — P — SUGAR — OH — 3'
         ↑                              ↑
    PHOSPHATE                       FREE HYDROXYL
    at 5' carbon                    at 3' carbon
```

Every polymerisation adds a nucleotide to a **3′ end**. That is because a polymerase can only join a free 3′-OH to an incoming 5′ phosphate. The consequence is directional:

```
DNA POLYMERASE CAN ADD NUCLEOTIDES ONLY HERE
                                     ↓
5' ——————————————————————————————————— 3'
                                     ↑
                    5' ————————————————— 3'
    so the lower strand is synthesised ← ← ← (right to left)
```

The enzyme does not need to know which way to point — **the chemistry dictates the direction.** This is why replication forks proceed in one direction and why RNA polymerase reads a template only in one direction.

### Bases project inward

The hydrophilic sugar–phosphate backbones are on the outside; the hydrophobic bases face inward. The same hydrophobic effect that drives protein folding drives DNA's architecture.

### Major and minor grooves

Because the helix is a right-handed spiral, the two backbones do not sit directly opposite each other. They are offset, leaving a wide **major groove** and a narrow **minor groove**.

```
        ┌──────────────┐
        │              │
        │   ║   MAJOR  │
   backbone ──────────  ║     ← wider
        │              │
        │  ║  MINOR  ║ │
        │  ║   ║    ║ │
        └──║────║────║─┘
           ║    ║    ║
```

This is not a curiosity. **Proteins read DNA without unwinding it by inserting recognition helices into the major groove.** The groove carries a different sequence-dependent pattern of chemical groups on each strand, so a groove-reading protein can identify its binding site from the base sequence alone. Transcription factors, and restriction enzymes that cut DNA at specific sites, work this way.

### Stability

| Factor | Contribution |
| --- | --- |
| **Hydrogen bonds** between bases | Hold the two strands together; individually weak, collectively strong |
| **Base stacking** | Overlapping electron clouds of adjacent bases; the **dominant** stabilising force |
| Covalent backbone bonds | Make each strand itself stable |

**Base stacking is more important than hydrogen bonding**, which surprises most students and is worth stating plainly. Packing the hydrophobic base rings together reduces their exposure to water, just as with protein folding. Hydrogen bonding matters for specificity and for reversible separation; stacking matters for overall stability.

**Consequence:** two sequences with the same base composition but different base *order* have different melting temperatures, because stacking depends on which bases are adjacent.

## RNA structure

**RNA** is usually single-stranded. Its variety comes from how a single strand folds back on itself through intramolecular hydrogen bonding and base stacking.

```
SINGLE STRAND
   ↓ folds on itself
HAIRPIN     INTERNAL LOOP     STEM-LOOP

   ╭──╮      ╭──╮                ╭───╮
   │  ╰──╮  ╭─╯  │                │   ╰╮
   │     ╰──╯    │                ╰╮╭─╯
   ╰───────      ╰────────────────  ╰╯
   stem          loop             stem + loop
```

Three structural differences from DNA:

| Feature | DNA | RNA |
| --- | --- | --- |
| Strands | Two, antiparallel | Usually one |
| Sugar | Deoxyribose (no 2′-OH) | Ribose (2′-OH) |
| Chemical stability | Very stable | Less stable; easily hydrolysed |
| Typical length | Extremely long | Short |
| Function | Long-term information storage | Transferring, regulating, and catalysing with that information |

**Why single-stranded is an advantage.** With only one strand, folding creates a complex three-dimensional shape with a region for one molecule to bind and another for it to be released from. This is what makes RNA capable of catalysis and precise recognition — see [05 — Molecular biology](../05-molecular-biology/).

## The three types of RNA

### mRNA — messenger RNA

Carries a copy of a gene's sequence from DNA in the nucleus to a ribosome.

```
GENE IN DNA —TRANSCRIPTION→ mRNA —TRANSLATION→ PROTEIN
```

A processed eukaryotic mRNA has a **5′ cap**, a **5′ untranslated region (UTR)**, the **coding sequence** carrying the codons, a **3′ UTR**, and a **poly-A tail**. The cap and tail protect the molecule from degradation and are used by transport machinery to move it to a ribosome. See 05 — Transcription.

### tRNA — transfer RNA

Delivers the correct amino acid to the ribosome by matching its **anticodon** to the mRNA **codon**.

```
AMINO ACID — C — C — A — A — C — A — C — 3′
             │                        ↑
           anticodon            3′ end;
                             amino acid attaches here
```

The anticodon is at one end of the folded tRNA and the amino acid attachment site is at the other — which is how the ribosome can check that the correct amino acid is present. Some tRNAs carry modified bases that improve codon recognition; these are **wobble** bases, described in 05 — Translation.

### rRNA — ribosomal RNA

The structural and catalytic core of the ribosome, making up the majority of ribosome mass.

**rRNA is a ribozyme.** The peptidyl transferase activity that forms peptide bonds is performed by rRNA, not by protein. This is one of the strongest pieces of evidence that RNA preceded DNA in evolution, and it is developed in 06 — Evolution.

### Summary

| RNA | Function | Where it acts |
| --- | --- | --- |
| **mRNA** | Carries the code | Nucleus → ribosome |
| **tRNA** | Delivers amino acids; decodes the code | Ribosome |
| **rRNA** | Structural and catalytic core of the ribosome | Ribosome |
| Others (snRNA, miRNA, siRNA, lncRNA) | Splicing, regulation, structure, gene control | Nucleus and cytoplasm |

## DNA vs RNA — the comparison to know cold

| Feature | DNA | RNA |
| --- | --- | --- |
| Sugar | Deoxyribose (no 2′-OH) | Ribose (2′-OH) |
| Pyrimidines | Cytosine, **thymine** | Cytosine, **uracil** |
| Strands | Two, antiparallel, complementary | Usually one |
| Location (eukaryote) | Nucleus; mitochondria and chloroplasts | Nucleus and cytoplasm |
| Function | Long-term information storage | Transfer, expression, regulation, catalysis |
| Stability | High; archival | Lower; transient |
| Replication | Yes | No |
| Typical length | Very long | Short |
| Synthesised by | DNA polymerase | RNA polymerase |

## Medical relevance

**Antibiotics exploit differences between bacterial and human nucleic acid machinery.**

| Target | Bacterial | Human | Basis of selectivity |
| --- | --- | --- | --- |
| Ribosome | 70S (50S + 30S) | 80S (60S + 40S) | Different rRNA and proteins |
| DNA gyrase (topoisomerase II) | Present | Absent | Different enzyme |

This is the same structure-based selectivity described in [00 — Prokaryotic and eukaryotic cells](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md), applied at the level of the ribosome. It also explains why some antibiotics have mitochondrial toxicity — mitochondria have bacterial-type ribosomes.

**Antiviral drugs exploit the fact that viruses replicate using host machinery.** Because a virus has no ribosomes and no replication enzymes of its own, any drug acting on viral replication must either target a virus-specific enzyme or inhibit the virus commandeering a host enzyme. That narrowness explains both why antivirals are limited and why resistance develops comparatively quickly.

**Sequencing is possible because hydrogen bonding is reversible.** Sequencing methods use a labelled terminator to stop synthesis, and separate the fragments by size. Only works because the backbone survives and only the hydrogen bonds are disturbed — see 05 — DNA replication.

**Mutations, variants, and disease.** A substitution that changes a base pair changes the protein's primary structure, which changes its shape, which changes its function. The chain is short and each step is well defined:

```
BASE-PAIR CHANGE
   ↓
mRNA CODON CHANGES (or not — silent)
   ↓
AMINO ACID CHANGES (or not)
   ↓
PRIMARY STRUCTURE CHANGES
   ↓
FOLDING MAY CHANGE
   ↓
PROTEIN FUNCTION CHANGES
   ↓
CELLULAR CONSEQUENCE → CLINICAL DISEASE
```

Because the path from base to disease is short and mechanistically defined, it is possible to predict whether a sequence change is likely to matter. See 05 — Mutations.

**Nucleic acids are used therapeutically.** Synthetic oligonucleotides are used to inactivate a gene or a viral genome — for example, an antisense oligonucleotide complementary to a viral or tumour mRNA, which hybridises to it and prevents its translation. This works for exactly the reason sequencing does: complementary base pairing is specific enough to target one sequence.

**Fragile sites and chromosome structure.** Some DNA sequences are prone to breakage — fragile sites on the X chromosome, and regions with repeated trinucleotide sequences. Repetition is the common factor, and these regions are associated with conditions including Huntington's disease and several fragile X syndromes. See 05 — Mutations.

## Key facts

- **Nucleotide** = phosphate + pentose + base. **Nucleoside** = pentose + base, **no phosphate**.
- DNA has **deoxyribose** (no 2′-OH), RNA has **ribose**. That single difference makes DNA far more stable.
- **Purines** (A, G) are double-ringed; **pyrimidines** (C, T, U) are single-ringed. Purines pair with pyrimidines.
- **A=T, G=C** in DNA; **A=U, G=C** in RNA.
- DNA is **double-stranded, antiparallel, complementary**, with **5′ and 3′ ends**.
- Polymerisation adds nucleotides only to a **3′-OH**, so synthesis direction is chemically determined.
- **Base stacking** stabilises the helix more than hydrogen bonding does; hydrogen bonds confer **specificity** and allow **reversible separation**.
- Bases face inward, backbones outward; **major and minor grooves** are read by proteins without unwinding.
- DNA is archival and replicated; RNA is transient, single-stranded, folds into shapes, and includes a **ribozyme**.
- Human cytoplasmic ribosomes are **80S**; bacterial ribosomes are **70S**. Mitochondria contain ribosomes of **bacterial type** — the basis of mitochondrial antibiotic toxicity.

## Practice questions

**1. Which statement correctly compares DNA and RNA?**

A. DNA is synthesized by RNA polymerase
B. DNA has two antiparallel strands; RNA is usually single-stranded
C. RNA is more chemically stable than DNA
D. DNA contains uracil in place of thymine

**Answer: B**

Explanation: DNA is a double helix of two antiparallel complementary strands, while RNA is usually single-stranded and folds on itself. A is wrong because RNA polymerase makes RNA; DNA is made by DNA polymerase. C is wrong because DNA is far more stable — its missing 2'-OH makes it resistant to hydrolysis. D is backwards: it is RNA that contains uracil in place of thymine.

---

**2. Why is uracil not used in DNA?**

A. Uracil cannot be incorporated by any polymerase
B. Uracil arises spontaneously when cytosine deaminates, so its presence in DNA is detectable damage, whereas thymine's extra methyl group distinguishes it from uracil
C. Uracil is too large to fit in the double helix
D. Uracil cannot form hydrogen bonds with adenine

**Answer: B**

Explanation: Cytosine deaminates to uracil at a measurable rate. Since uracil is not a normal DNA base, it is identifiable as a mistake when found in DNA. Thymine is 5-methyluracil, and deamination cannot add a methyl group, so thymine is unambiguously a normal base. The arrangement protects the integrity of the stored sequence. A and C are false — uracil pairs with adenine normally in RNA and is not too large.

---

**3. What determines the direction in which a DNA polymerase can synthesise a new strand?**

A. The temperature of the reaction
B. The presence of a free 3'-OH group to which a nucleotide can be added
C. The concentration of free nucleotides
D. The enzyme's active site shape

**Answer: B**

Explanation: Polymerisation joins a free 3'-OH group to the incoming nucleotide's 5' phosphate, so synthesis can only extend a strand at its 3' end. The chemistry dictates the direction, which is why both strands of a replication fork are made in different physical directions. C and D affect rate rather than direction, and the enzyme's shape accommodates rather than determines the chemistry.

---

**4. Which interaction contributes most to the overall stability of the DNA double helix?**

A. Hydrogen bonds between complementary bases
B. Covalent bonds along the sugar–phosphate backbone
C. Ionic bonds between phosphate groups
D. Base stacking between adjacent bases

**Answer: D**

Explanation: Stacking of adjacent base rings is the major stabilising force, because packing the hydrophobic base rings together reduces their exposure to water — the same hydrophobic effect that drives protein folding. Hydrogen bonds are individually weak and confer specificity and the ability to separate the strands rather than great stability. B holds each strand together but does not hold the two strands together. C is not a feature of the double helix.

---

**5. A protein inserts into the major groove of DNA without unwinding it. What information does it read?**

A. The sequence of bases, which is exposed as a distinct pattern of chemical groups in the groove
B. The hydrogen bonds between the two strands
C. The number of base pairs
D. The covalent bonds of the sugar–phosphate backbone

**Answer: A**

Explanation: Because the helix is a right-handed spiral with offset backbones, the bases of each strand are exposed in a sequence-dependent pattern on the groove surfaces. A protein can therefore identify a binding site from the exposed chemical groups without unwinding the helix. Transcription factors and restriction enzymes work this way. B, C, and D are not exposed in a readable form in the groove.

---

**6. Why is DNA more stable than RNA?**

A. DNA is double-stranded while RNA is single-stranded
B. DNA has a larger diameter
C. DNA lacks the 2'-OH group on its sugar, which in RNA can attack a neighbouring phosphodiester bond and cause hydrolysis
D. DNA contains more hydrogen bonds

**Answer: C**

Explanation: The absence of the 2'-OH group removes the reactive hydroxyl that makes RNA susceptible to alkaline hydrolysis, so DNA can persist for millions of years — a requirement for archival information storage. RNA is transient by design, degrading within minutes in the cell. A is a difference but not the cause of the stability difference; B and D are incorrect or not the mechanism.

---

**7. Which statement about rRNA is correct?**

A. It forms the structural and catalytic core of the ribosome, and it performs the peptidyl transferase reaction
B. It delivers amino acids to the ribosome
C. It is an intermediate copy of a gene
D. It is composed only of nucleotides with no protein

**Answer: A**

Explanation: rRNA makes up the bulk of the ribosome and carries out peptide bond formation — rRNA is a ribozyme. This is central evidence that RNA preceded DNA in evolution. B describes tRNA. C describes mRNA. D is wrong because ribosomes contain proteins as well as rRNA; the proteins are largely structural.

---

**8. A nucleotide consists of phosphate, a pentose sugar, and a nitrogenous base. What is it called if the phosphate group is absent?**

A. A polynucleotide
B. A pyrimidine
C. A nucleoside
D. A nucleobase

**Answer: C**

Explanation: A nucleoside is the base plus the sugar, without the phosphate group; adding a phosphate gives a nucleotide. The distinction matters because nucleosides cannot be polymerised into nucleic acid without phosphorylation, and they are the products of nucleic acid breakdown. B describes the base alone, and D describes one class of base.

---

**9. Why is a gene sequence transcribed into RNA rather than copied directly to protein?**

A. RNA allows separation of transcription from translation, so the same DNA can be used repeatedly and regulation can occur between the two steps
B. Proteins cannot be made in the nucleus
C. RNA is chemically identical to protein
D. DNA cannot leave the nucleus

**Answer: A**

Explanation: Separating the two steps permits a single gene to be transcribed repeatedly, permits regulation between transcription and translation, and — since transcription occurs in the nucleus and translation in the cytoplasm in eukaryotes — keeps the two steps in separate compartments. B is true but is a consequence of compartmentalisation rather than the reason for an RNA intermediate. C is false: RNA and protein are chemically quite different macromolecules. D is wrong because DNA is copied in the nucleus in eukaryotes and in the cytoplasm in prokaryotes.

---

**10. Why do some antibiotics inhibit bacterial protein synthesis but not human protein synthesis?**

A. Human cells lack ribosomes during certain phases
B. Bacterial ribosomes are smaller and therefore easier to inhibit nonspecifically
C. Bacterial ribosomes contain DNA
D. Bacterial ribosomes are structurally different from human cytoplasmic ribosomes — 70S in bacteria, 80S in the human cytoplasm

**Answer: D**

Explanation: Structural difference at the target is the basis of selectivity. The 70S and 80S ribosomes differ in rRNA and protein composition, so agents that bind bacterial ribosomes do not bind human ones. The exception worth knowing is mitochondrial toxicity: mitochondria contain ribosomes of bacterial type, inherited from an endosymbiont, so some antibiotics can interfere with them — which matters in high-dose or prolonged use. A, B, and C are false.