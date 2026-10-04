# Chemical Bonds

## Core idea

Atoms bond because a filled outer electron shell is a lower-energy arrangement than a partial one. **Bond strength is what determines whether a molecule is stable or is constantly taken apart**, and biology depends on that distinction constantly — a covalent bond in DNA must not break spontaneously, and the hydrogen bonds holding the two strands apart must break easily and repeatedly.

So biology uses a deliberate hierarchy: **covalent bonds to build** permanent structure, and **weak interactions to hold** it together reversibly. Weak does not mean unimportant.

## Valence and bonding

The number of **valence electrons** in the outermost shell determines how many bonds an atom can form.

| Atom | Valence electrons | Covalent bonds formed | Full shell |
| --- | --- | --- | --- |
| Hydrogen | 1 | 1 | 2 |
| Carbon | 4 | 4 | 8 |
| Nitrogen | 5 | 3 | 8 |
| Oxygen | 6 | 2 | 8 |
| Phosphorus | 5 | 3 | 8 |
| Sulfur | 6 | 2 | 8 |
| Sodium | 1 | — (loses 1) | 2 (as Na⁺) |
| Chlorine | 7 | — (gains 1) | 8 (as Cl⁻) |

Carbon, nitrogen, and oxygen follow the octet rule — eight electrons in the outer shell. Hydrogen follows the duet rule — two.

## Covalent bonds

A **covalent bond** is formed when two atoms share a pair of electrons.

```
    ELECTRON CLOUD SHARED BETWEEN NUCLEI
         ↓          ↓          ↓
    H—H          C—H         O=C=O
  (both H        (4 bonds,   (each O
   filled)        tetrahedral  filled)
                  geometry)
```

Characteristics:

- Formed between nonmetals
- Strong — requiring significant energy to break
- Equal sharing if electronegativities are equal; unequal sharing if not
- Hold molecule shape together permanently

### Polar and nonpolar covalent bonds

A bond is **nonpolar** when the two atoms share the electrons equally (H–H, C–C). It is **polar** when one atom pulls the shared electrons toward itself, leaving partial charges ($\delta^+$ and $\delta^-$).

Electronegativity drives this. Oxygen (3.44) and nitrogen (3.04) are more electronegative than carbon (2.55) and hydrogen (2.20). So:

| Bond | Type | Consequence |
| --- | --- | --- |
| C–C, C–H | Nonpolar | Hydrophobic; allows long nonpolar chains |
| C–O, C=N | Polar | Partial charges; sites for hydrogen bonding |
| O–H | Polar, and O is the electronegative end | Hydrogen bonding; the basis of water's behaviour |
| N–H | Polar | Hydrogen bonding in proteins and nucleic acids |
| P–O | Polar | Charged phosphate groups; energy in ATP |

**Functional groups.** A specific arrangement of atoms on a carbon skeleton that behaves consistently, regardless of what surrounds it. Learning the six below pays for itself repeatedly — most organic functional groups you will ever need are on this list.

| Group | Structure | Character |
| --- | --- | --- |
| Hydroxyl | –OH | Polar; hydrogen bonds; makes sugars and alcohols water-soluble |
| Carboxyl | –COOH | Donates a proton to become –COO⁻; acidic; defines amino acids and fatty acids |
| Amino | –NH₂ | Accepts a proton to become –NH₃⁺; basic; defines amino acids |
| Phosphate | –PO₄²⁻ | Charged; repels other charges; carries energy in ATP |
| Carbonyl | C=O | Polar; in sugars and the backbone of proteins |
| Methyl | –CH₃ | Nonpolar; hydrophobic; common in lipids and amino acids |

## Ionic bonds

An **ionic bond** forms when electrons are transferred, not shared. One atom loses electrons and becomes a **cation**; the other gains them and becomes an **anion**. The bond is the electrostatic attraction between the two.

```
Na (1 valence electron) + Cl (7 valence electrons)
      ↓ transfer
Na⁺ + Cl⁻        Na loses 1 → becomes positive
      ↓ attraction
NaCl              full outer shells on both ions
```

In water, ionic bonds are not really bonds at all. The water molecules surround each ion and shield the charges from each other — **hydration** — which is why NaCl dissolves, and why ions in solution can move freely toward and away from a charged membrane surface. This matters directly for membrane potentials in 10 — Nervous.

Note that the transfer is what matters, not attraction itself. Kernels and their electrons attract each other, and that is what holds an atom together — so the term "bond" is used loosely across chemistry. In biology, "ionic bond" specifically means the inter-ion attraction between oppositely charged ions.

## Hydrogen bonds

A **hydrogen bond** forms when a hydrogen atom covalently bonded to an electronegative atom (O or N) is attracted to another electronegative atom nearby.

```
   O—H  ·······  O
    │            
    H   hydrogen bond (dotted line)
    │
    O
```

| Property | Detail |
| --- | --- |
| Strength | Individual bond ≈ 5% the strength of a single covalent bond |
| Range | Short-range; only exists when donor and acceptor are 0.28 nm apart |
| Direction | Attractive only — no repulsion between two H-bond donors |
| Directionality | Roughly linear, because the lone pairs on O and N point in specific directions |

**Individually weak, collectively decisive.** A single protein–water hydrogen bond is far too weak to survive thermal motion. Thousands of them acting together are strong enough to hold a protein's folded shape against agitation at boiling-water temperature. Collagen's triple helix is held almost entirely by interchain hydrogen bonds, which is why boiling collagen in water converts it to gelatin — the hydrogen bonds are disrupted, the covalent backbone is intact.

Hydrogen bonds also allow water to be liquid at room temperature, and they are the reason DNA's two strands separate at about 70–80 °C (the "melting temperature") rather than at the hundreds of degrees needed to break covalent bonds. They are reversible on a timescale of milliseconds, which is exactly what a proofreading enzyme or a replication fork needs.

## Weak interactions at a glance

Both are individually too weak to be called bonds and collectively essential. They differ in directionality and saturation.

| Feature | Hydrogen bond | Van der Waals interaction |
| --- | --- | --- |
| Nature | H attracted to O or N | Temporary dipoles in electron clouds |
| Directional | Yes — determines 3D shape | No — attracts in any orientation |
| Saturating | Yes — an atom has a limited number of H-bond partners | No — each contact adds a small increment |
| Sums over | Distance along a specific direction | Over *all* atom pairs |
| Typical strength | ~20 kJ/mol | ~2–5 kJ/mol |
| Example | Water–water, DNA base pairing | Hydrophobic core of a globular protein |

That last row explains a lot. When a protein folds, the energetically favourable outcome is to bury nonpolar side chains away from water — because that avoids paying the cost of ordering water molecules around each exposed nonpolar surface. Van der Waals contacts in the buried core are what pay for it. Folded stability is not simply "hydrogen bonds holding it together"; it is largely a water-exclusion argument.

## Why the hierarchy matters

| Bond type | Typical strength | Role in biology |
| --- | --- | --- |
| Covalent | 350–1000 kJ/mol | Defines the structure of every biomolecule; permanent |
| Ionic | 400–600 kJ/mol | Crystal structure; ion gradients in solution |
| Hydrogen | ~20 kJ/mol | Shape of proteins and DNA; water's liquid state; reversible processes |
| van der Waals | ~2–5 kJ/mol | Hydrophobic core packing; transient recognition |

**The rule that follows:** to break a covalent bond takes chemical energy. To break a hydrogen bond, just shake it. Biology therefore uses covalent bonds for permanent architecture and weak interactions for everything that needs to be reversible — enzyme-substrate binding, DNA strand separation, proofreading, signal transduction, and membrane fusion.

## Medical relevance

**Weak interactions are weak only one at a time.** Any process that involves thousands of them is a substantial force, and this is why binding drugs and correct pH matter. Drugs bind their targets through weak interactions, so their effect depends on concentration and on competing for the same site — the basis of competitive inhibition, described in [01 — Enzymes](../01-biochemistry/05-enzymes.md#inhibition-and-regulation-in-cells).

**pH works by breaking hydrogen bonds.** Change the proton concentration and you alter the charge on carboxyl and amino groups, which changes hydrogen bonding, which changes shape:

```
ALTERED pH → protonation state of R-groups changes
          → hydrogen bonding changes
          → tertiary structure changes
          → denaturation → loss of function
```

This is the mechanism behind the function of the stomach's low pH on ingested protein (it unfolds it, deliberately, so proteases can digest it), and behind the alkaline conditions in the small intestine that preserve pancreatic enzymes.

**Hydrogen bonds in the extracellular matrix.** Collagen's hydrogen bonds give bone its tensile strength along one axis. It is a weak interaction, but stacked across millions of molecules it holds a body upright. Disorders of collagen hydrogen-bonding and cross-linking produce fragility rather than dramatic failure — which is why conditions such as osteogenesis imperfecta present as a tendency to fracture rather than collapse.

**Heat, pH, and denaturation.** Any physical or chemical disruption that weakens the intramolecular weak interactions holding a protein's shape destroys function, and it does so without necessarily breaking covalent bonds. This is why the same molecules lose function at both extremes, and why they often re-fold correctly when returned to physiological conditions — see [01 — Proteins](../01-biochemistry/03-proteins.md#denaturation).

## Key facts

- **Covalent** = shared electrons, strong, between nonmetals. **Ionic** = transferred electrons, strong attraction between cation and anion.
- Electronegativity differences make bonds **polar**: C–O and C–N are polar, C–C and C–H are not.
- **Hydrogen bonds** need H covalently bonded to O or N, and a nearby O or N to attract it. They are directional, short-range, and reversible.
- **Van der Waals** interactions are non-directional and additive; they are what pack a protein's core.
- Biology uses strong bonds for permanent structure and weak ones for reversible events.
- Denaturation breaks the weak interactions that maintain shape, not the covalent backbone.
- In water, ions are hydrated and their charges are partly shielded.

## Practice questions

**1. Which statement correctly compares the interactions holding a single phospholipid molecule together with those holding phospholipid molecules to each other in a bilayer?**

A. The bonds within a molecule are covalent, while the interactions between molecules are predominantly weak noncovalent interactions
B. Both are hydrogen bonds, because lipids are not polymers
C. Both are covalent; only the strength differs
D. The bonds within a molecule are weak hydrogen bonds, while the interactions between molecules are covalent

**Answer: A**

Explanation: A phospholipid is a defined unit because its atoms are joined by strong covalent bonds — the ester bond to the phosphate and the double bonds along the tails. Between molecules, the dominant interaction is the cumulative effect of van der Waals contacts between the nonpolar tails, with hydrogen bonding at the polar head groups. That combination is fluid enough for the bilayer to self-seal and for proteins to move within it, which is exactly what a membrane has to do. B is wrong because covalent and noncovalent interactions are categorically different, not different strengths of the same thing. C reverses the two. D is wrong because lipids are not polymers, but the reason the molecule holds together is covalent bonds.

---

**2. Which bond is correctly matched with the bond type it forms?**

A. Sodium and chlorine — covalent
B. Hydrogen and oxygen — covalent
C. A water molecule and a dissolved sodium ion — hydrogen bond
D. Two nonpolar carbon atoms — polar covalent

**Answer: B**

Explanation: Two nonmetals share electrons to form a covalent bond, which is what H and O do in water. A is wrong — sodium transfers an electron to chlorine, forming an ionic bond. C is wrong — the sodium ion is hydrated, meaning water molecules orient around it with partial charges toward the charge; this is ion–dipole attraction, not a hydrogen bond. D is wrong — two carbons share electrons almost equally, so the bond is nonpolar.

---

**3. Why is water able to act as a solvent for many ionic and polar substances, while oil is not?**

A. Oil molecules contain hydrogen atoms
B. Water is denser than oil
C. Water molecules are polar and interact electrostatically with other polar and charged molecules
D. Water molecules are smaller than oil molecules

**Answer: C**

Explanation: Water's bent shape and polar O–H bonds give it a dipole with partial charges — oxygen δ⁻ and hydrogens δ⁺. That dipole interacts favourably with ions and other polar molecules, dispersing them. Nonpolar oil molecules have no comparable attraction and do not disperse well. A, B, and D have no bearing on solubility.

---

**4. A protein is boiled in water and unfolds, but its peptide bonds remain intact. Which statement best explains this?**

A. Boiling broke the peptide bonds and new ones formed
B. Hydrogen bonds are stronger than peptide bonds
C. Peptide bonds are held together by the same forces as hydrogen bonds
D. Peptide bonds are stronger than the hydrogen bonds maintaining the folded structure

**Answer: D**

Explanation: Denaturation disrupts the weak interactions — hydrogen bonds and other noncovalent attractions — that maintain three-dimensional shape, while covalent peptide bonds require far more energy and survive. This is the basis of the distinction between denaturation and hydrolysis.

---

**5. Hydrogen bonds are described as weak. What is their biological significance?**

A. They form the backbone of DNA
B. They hold a large number of weak interactions together to determine protein and DNA structure
C. They provide most of the energy in cellular respiration
D. They attach amino acids together in translation

**Answer: B**

Explanation: Individual hydrogen bonds are far below the energy required to survive thermal motion, but thousands of them acting cooperatively determine and stabilize three-dimensional structure. C is wrong — the DNA backbone is held by covalent phosphodiester bonds. D is wrong — peptide bonds are covalent and form during translation. A is wrong — energy yields come from chemical bonds being broken and reformed, not from hydrogen bonds.

---

**6. Which of the following best explains why DNA strands separate at a temperature far below that required to break covalent bonds?**

A. DNA contains no covalent bonds
B. Water weakens covalent bonds at high temperature
C. The two strands are held together by hydrogen bonds between the bases, which are individually weak and numerous
D. DNA is shorter than most proteins

**Answer: C**

Explanation: Each base pair contributes two or three hydrogen bonds. None is individually strong, but the cumulative effect across thousands of base pairs is enough to hold the double helix together below 100 °C. Heating raises molecular motion until these weak interactions fail. When the strands re-anneal, hydrogen bonds reform in the correct register, which is why complementarity directs assembly.

---

**7. Why is ice less dense than liquid water?**

A. Ice has more hydrogen bonds per molecule, forcing an open hexagonal lattice
B. Ice has fewer hydrogen bonds per molecule, so molecules pack further apart
C. Ice molecules are larger than liquid water molecules
D. Ice contains less oxygen than water

**Answer: A**

Explanation: In ice, each water molecule forms four hydrogen bonds in a rigid open hexagonal arrangement. That lattice contains more empty space than the disordered arrangement in liquid water, so the same mass occupies more volume. This is why ice floats and why lakes freeze from the top down, which allows aquatic life to survive beneath the surface.

---

**8. A cell is placed in a solution. Which observation best indicates that an ionic bond between two ions has been disrupted?**

A. The ions become covalently bonded
B. Both ions remain in fixed positions in a crystal
C. The solution changes colour
D. Both ions move freely and independently away from one another

**Answer: D**

Explanation: In an ionic crystal, cation and anion are held in fixed positions by electrostatic attraction. Dispersing them in water means each ion is surrounded by an oriented hydration shell, shielding it from the other ion, so they move independently. A describes the intact crystal, and ions in solution do not form new covalent bonds to each other.