# Non-Mendelian Patterns

## Why it matters

Mendel's ratios are a special case — and medicine is not special-case territory. Real traits frequently refuse the tidy 3:1 mould: pink flowers from red and white parents, blood groups with three alleles in one population, haemophilia passing mother to son, calico coats appearing almost exclusively in females, and height varying continuously rather than sorting into "tall" and "short". Every one of these still obeys the two laws at the level of chromosomes and gametes; what changes is what happens **after** fertilisation — how alleles interact, where the gene sits, which sex carries it, how many genes are involved, and whether the phenotype appears at all.

```
MENDELIAN BASELINE:   1 locus  2 alleles  full dominance  autosomal  1 gene = 1 discrete trait

DEVIATIONS ADD:       incomplete dominance / codominance
                      more than 2 alleles in the population (ABO)
                      a chromosome with a sex (X-linked)
                      hormonal context (sex-influenced)
                      genotype that dies (lethal alleles)
                      gene that masks another (epistasis)
                      many genes + environment (polygenic)
                      genotype present, phenotype absent or variable (penetrance / expressivity)
```

Read the list as a set of **modifications layered on unchanged Mendelian mechanics**, and the patterns become predictable rather than miscellaneous.

## Incomplete dominance and codominance

| | Incomplete dominance | Codominance |
| --- | --- | --- |
| **Heterozygote phenotype** | An **intermediate** of the two homozygotes | **Both alleles expressed fully and simultaneously** — neither masks the other |
| **Classic example** | Snapdragon (antirrhinum) red × white → **pink**; Japanese four o'clock red × white → **rose** | Roan cattle (red **and** white hairs side by side); ABO blood groups |
| **Molecular reading** | Heterozygote makes ~50% of each gene product → intermediate amount of pigment | Two structurally distinct products coexist, each doing its own thing |
| **F2 phenotype ratio** | 1 red : 2 pink : 1 white | 1 : 2 : 1 with both components visible in the double heterozygote |

```
INCOMPLETE DOMINANCE
   RR (red)   ×   rr (white)
              │
              ▼
          Rr = PINK          ← not red, not white: an intermediate
              │  self
              ▼
   1 RR : 2 Rr : 1 rr  →  1 red : 2 pink : 1 white     (phenotype ratio = genotype ratio)

CODOMINANCE (roan cattle)
   RR (red)   ×   rr (white)
              │
              ▼
          Rr = red hairs AND white hairs — both visible, unblended
```

**The decisive distinction:** in incomplete dominance the heterozygote's *product* is intermediate in quantity or activity; in codominance the heterozygote's *products are both detectable in the same individual at the same time* (in ABO, the same red cell carries both A and B antigen). A blended intermediate is not the same as two components coexisting.

**Neither is "blending inheritance"** — the discredited 19th-century idea that heredity smears parental types together forever. The F2 regenerates the pure parental phenotypes in a 1:2:1 ratio, proving the factors stayed particulate. Incomplete dominance changes the *ratio you record*, not the *behaviour of the alleles*.

## Multiple alleles: the ABO blood group worked in full

Mendel dealt with two alleles because he bred true-breeding lines. **Within a population, any locus may have many alleles** — but **each individual still carries at most two**.

The ABO locus (chromosome 9) has three common alleles:

```
I^A   →  adds A antigen to the red cell surface        (dominant to i)
I^B   →  adds B antigen                                (dominant to i)
i     →  no antigen added                              (recessive to both)

I^A and I^B are CODOMINANT to each other
```

| Genotype | Phenotype (ABO group) | Antigen on RBC | Antibodies in plasma |
| --- | --- | --- | --- |
| *I^A I^A* or *I^A i* | **A** | A | Anti-B |
| *I^B I^B* or *I^B i* | **B** | B | Anti-A |
| *I^A I^B* | **AB** | A **and** B | Neither (no anti-A, no anti-B) |
| *ii* | **O** | Neither | Anti-A **and** anti-B |

**The immunology follows from the table:** the body makes antibodies against antigens it lacks. That is why a type A person given type B blood destroys the donated cells — anti-B was already waiting.

### Transfusion logic

```
DONOR RBCs must carry no antigen the recipient has antibody against

O red cells:  no A, no B antigen  →  can be given to A, B, AB, O   →  UNIVERSAL DONOR
AB plasma:    no anti-A, no anti-B →  can receive from anyone        →  UNIVERSAL RECEIVER
```

- **Universal donor = group O** (red cells) because there is nothing on the cell for recipient antibodies to attack.
- **Universal receiver = group AB** because its plasma contains neither antibody.
- Whole plasma obeys the reverse logic (group AB plasma has no antibodies; group O plasma has both) — modern transfusion services still cross-match, but the antigen/antibody principle is the examinable core.

### The Bombay phenotype — genotype and phenotype can diverge

A rare variant (genotype *hh*) **cannot build the H substance** from which the A and B antigens are made. Consequences:

```
person is  hh  I^A I^A     →  no H → no A antigen → SEROLOGICALLY TYPE O
                              but makes anti-A, anti-B, AND anti-H
                              → can receive red cells only from another Bombay donor
```

So a person whose *I* genotype says "type A" tests as type O — and a parent who appears type O can have a child whose ABO group "doesn't fit" the family. The Bombay phenotype is the standard demonstration that **serological phenotype, I-locus genotype, and clinical compatibility are three different statements**, and it is the classic trap in blood-group inheritance questions.

## Sex-linked inheritance

Most genes are autosomal (on the 22 pairs of non-sex chromosomes) and behave exactly as in [02 — Mendelian inheritance](02-mendelian-inheritance-and-punnett-squares.md). Genes on the **X chromosome** follow different arithmetic because genetic males are **hemizygous** — one X, no second allele to mask anything.

### X-linked recessive — the common pattern (haemophilia, colour blindness)

```
notation:   X^H = normal    X^h = recessive variant

female:   X^H X^H  normal          X^H X^h  CARRIER (usually unaffected)
          X^h X^h  AFFECTED        ← needs two copies

male:     X^H Y    normal          X^h Y    AFFECTED  ← needs only one copy
```

**Transmission rules that answer most pedigree questions:**

| Situation | Outcome |
| --- | --- |
| Carrier mother × unaffected father | **Each son: ½ affected, ½ normal.** Each daughter: ½ carrier, ½ homozygous normal |
| Affected father × unaffected mother | **All daughters are carriers; no sons affected** (sons get his Y, not his X) |
| Affected father × carrier mother | Daughters: ½ affected; sons: ½ affected |
| Affected mother × any father | **All sons affected** (they receive her only X) |

**Criss-cross inheritance** — the signature of X-linked recessive traits:

```
I    affected grandfather (X^h Y)
        │  passes X^h to ALL daughters (who are phenotypically normal)
        ▼
II   daughter = CARRIER (X^H X^h)
        │  passes X^h to half her sons
        ▼
III  grandson affected          ← skip-the-male generation, appear through a female
```

**Why males are more often affected:** one copy is enough. Affected females are rare because they require an affected father *and* a carrier or affected mother — but when they occur, they prove the trait is X-linked (an affected daughter from an unaffected father rules X-linkage out).

### X-linked dominant

Same location, different dominance relationship — heterozygous females are affected. Three-way diagnostic:

```
AFFECTED FATHER (X^D Y) × unaffected mother
        │
        ▼
ALL daughters affected (they all receive his X^D)
NO sons affected (they receive his Y)          ← the textbook signature
```

Heterozygous affected mother × unaffected father → ½ of sons and ½ of daughters affected. The trait appears in **every generation**, roughly equally in both sexes, and **father → daughter transmission skips no generation**.

## X-inactivation: Barr bodies and calico cats

Genetic females have two X chromosomes; males have one. **Dosage compensation** is achieved by silencing one X in each female cell, early in embryonic development.

```
early embryo, female (XX)
        │  random choice: WHICH X to shut off (maternal or paternal)
        ▼
X^A  ACTIVE ────────────────▶ daughter cell lineage → all cells express this X
X^B  INACTIVE (condensed)   ─▶ daughter cell lineage → all cells express this X
        │
        ▼
adult female = MOSAIC of two cell populations, in patches
```

- The inactive X condenses into a dense lump visible at the nucleus edge — a **Barr body**.
- **Number of Barr bodies = number of X chromosomes − 1** (female: 1; male: 0; Klinefelter 47,XXY: 1; 47,XXX: 2).
- Inactivation is **random** per cell and **permanent** in that cell's descendants — a beautiful mechanism-level extension of the cell-lineage ideas in [11 — Mitosis and cytokinesis](../03-cellular-processes/11-mitosis-and-cytokinesis.md).

**Calico and tortoiseshell cats — the visible proof.** Coat colour in cats has an X-linked allele: *X^O* = orange, *X^o* = black (these are codominant at the level of the patch, because each patch is one cell's single active X):

```
X^O X^o  female, random X-inactivation → patches of orange AND black (+ white from a separate gene)
X^O X^O  orange female        X^o X^o  black female        X^O Y  orange male

CALICO (orange + black patches) requires both alleles → requires TWO X chromosomes
→ essentially always female.  A calico male is almost always XXY (Klinefelter) or a chimera.
```

**Clinical echo:** a female carrier of an X-linked recessive condition is a mosaic — roughly half her cells express the normal allele and half the variant. If inactivation is unusually skewed, or the variant is not fully recessive, she can show mild symptoms — called a **manifesting carrier**. This is why X-linked conditions are *usually* male-predominant but *not exclusively* male.

## Sex-influenced traits

An **autosomal** gene whose phenotypic effect depends on the individual's **hormonal environment** — same genotype, different phenotype by sex.

| Trait | In males | In females |
| --- | --- | --- |
| **Pattern baldness (androgen-dependent hair loss)** | Dominant — one allele suffices (testosterone drives follicle sensitivity) | Recessive — usually needs both copies |
| **Polled (hornless) status in some sheep** | Horned allele dominant | Horned allele recessive |

This is **not** sex-linkage: the gene sits on an autosome and segregates normally. It is dominance that has been redefined by physiology — a reminder that dominance is a relationship involving *the whole organism's context*, not the DNA alone ([01 — Genes, alleles](01-genes-alleles-genotype-phenotype.md)).

## Lethal alleles

Some genotypes are **not viable**. The allele still segregates normally; the ratio changes because a class is missing from the count.

| Type | Genotype dies | Cross *Aa* × *Aa* gives |
| --- | --- | --- |
| **Recessive lethal** (e.g. Tay–Sachs allele) | *aa* | Survivors: 1 *AA* : 2 *Aa* — all phenotypically normal |
| **Dominant homozygous lethal** (e.g. yellow mouse *Aʸ*, achondroplasia *FGFR3*) | *AA* (both copies) | Survivors: **2 *Aa* : 1 *aa* → 2 : 1 phenotype ratio** |

```
AyAy dies (homozygous lethal)
AyA × AyA → 1 AyAy (dies) : 2 AyA (yellow) : 1 AA (non-yellow)
                          observed at birth:  2 yellow : 1 non-yellow
```

**A 2:1 ratio where 3:1 is expected is the fingerprint of a homozygous lethal dominant allele.** Dominance and lethality are separable properties: achondroplasia is dominant *and* its homozygous form is lethal — two facts about one allele, both examinable.

## Epistasis: one locus masks another

**Epistasis** = interaction between loci, where one gene's product affects whether another gene's product can act. In the coat-colour example, the **E locus controls whether pigment is deposited at all**; **B controls which pigment (black or brown)**.

```
E_  B_  → BLACK           (enzyme present, black pigment)
E_  bb  → BROWN/chocolate (enzyme present, brown pigment)
ee  B_  → YELLOW          ┐
ee  bb  → YELLOW          ┘  ee = no deposition → B/b invisible
```

Dihybrid cross *EeBb* × *EeBb*, expected 9:3:3:1, becomes:

```
9  E_B_  black
3  E_bb  brown          →  9 : 3 : 4
4  ee__  yellow  (both ee classes merge)
```

**Reading a modified ratio:** **9:3:4** is 9:3:3:1 with the last two classes combined — the signature of **recessive epistasis**, because the recessive homozygote at one locus (*ee*) masks both classes at the other. Ratios of **9:7** (both dominant needed), **12:3:1** (dominant epistasis), and **13:3** follow from the same combinatorial logic.

## Polygenic inheritance and continuous variation

Some traits do not sort into classes at all — **height, skin pigmentation, grain size, blood pressure** vary continuously in a bell-shaped distribution.

```
ONE gene, two alleles:     |██|      discrete classes

MANY genes, additive:      ▁▃▅▇█▇▅▃▁   continuous, roughly normal
      (each "risk" allele adds a little effect, environment shifts the curve)
```

| Feature | Detail |
| --- | --- |
| **Basis** | Several (often dozens) loci, each with small additive effects, plus environment |
| **Pattern** | Continuous variation; most individuals near the mean, few at the extremes |
| **Evidence of Mendelianism** | The F2 from a cross of extremes is *more variable*, not intermediate-blended — each underlying locus still segregates |
| **Threshold traits** | A continuous "liability" that produces a discrete diagnosis only past a cut-off (e.g. cleft lip) — looks non-Mendelian but is polygenic underneath |
| **Why it matters clinically** | Common diseases (type 2 diabetes, hypertension) are largely this — see [05 — Human inheritance patterns](05-human-inheritance-patterns.md) |

**Polygenic does not mean "non-genetic"** — it means one gene does not determine it, so no single cross ratio exists, and family history shifts the distribution rather than guaranteeing the trait.

## Penetrance and expressivity

The genotype–phenotype chain can be interrupted or graded. These two words describe different failures:

| Term | Question it answers | Measurement |
| --- | --- | --- |
| **Penetrance** | *Does* a person with the genotype show **any** phenotype? | Proportion of carriers affected (%) |
| **Expressivity** | **How much**, in what severity and which tissues, do affected people show it? | Range of severity among those affected |

```
genotype present in 100 people
        │
        ├─▶ 80 show the trait        → penetrance = 80%
        │        ├─▶ 5 mild          → expressivity: VARIABLE
        │        ├─▶ 30 moderate
        │        └─▶ 45 severe
        └─▶ 20 clinically normal     → non-penetrant
```

- **Variable expressivity:** neurofibromatosis type 1 — one family, the same *NF1* mutation, anything from a few café-au-lait spots to disabling tumours; polydactyly with different numbers of extra digits.
- **Incomplete penetrance:** *BRCA1* pathogenic variants confer a lifetime breast-cancer risk well under 100% — carriers can die of other causes never having developed cancer; short-repeat Huntington alleles can fail to manifest.
- **Pedigree consequence:** a dominant trait with reduced penetrance can appear to **skip a generation**, which is the commonest way a supposedly "obvious" autosomal dominant diagnosis goes wrong in an exam pedigree ([04 — Pedigree analysis](04-pedigree-analysis.md)).

## Medical relevance

**Blood groups are transfusion medicine.** ABO compatibility (above) plus the **Rh system** prevents haemolytic disease of the newborn: an Rh− mother carrying an Rh+ fetus can make **anti-D** antibodies that destroy a subsequent Rh+ fetus's red cells — prevented by **anti-D immunoglobulin (RhoGAM)** given during and after pregnancy. ABO incompatibility between mother and infant causes a milder, more common version.

**X-linked recessive arithmetic drives genetic counselling.** For a carrier mother and unaffected father of haemophilia A: each son independently has a 50% chance of being affected, each daughter a 50% chance of being a carrier — and an affected father's daughters are all obligate carriers who may transmit to grandchildren. Pedigree clues ("only males, never male-to-male") identify the pattern before any testing.

**X-inactivation explains variable severity in female carriers** of Duchenne muscular dystrophy and other X-linked conditions — skewing toward the mutant X can produce a manifesting carrier with myopathy. It also explains Klinefelter males who show features of X-linked dominant traits.

**Blood-group genetics beyond transfusion:** the ABO system influences susceptibility to some infections and thrombotic risk; Bombay phenotype patients need specially matched blood and are a recurrent clinical-alert case. Tissue typing and antibody screens follow the same antigen logic.

**Penetrance and expressivity are the reason "genotype positive" ≠ "will get the disease".** Predictive testing for hereditary cancer syndromes is quoted as a *risk range*, never a certainty — and family history matters even in known mutation-negative families, because penetrance describes populations, not individuals.

**Epistasis and polygenic architecture explain why common disease does not follow 3:1.** Mendelian single-gene disorders give clean ratios; hypertension and type 2 diabetes give distributions and odds ratios — the distinction between a rare variant with large effect and many common variants with small effect.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| Incomplete dominance = codominance | **Intermediate blend** vs **both products visible at once** (pink vs roan hairs / A and B antigens together). |
| Incomplete dominance = blending inheritance | No — the F2 restores the parental phenotypes (1:2:1), proving factors stayed particulate. |
| "Multiple alleles" means one person has >2 alleles | The *population* has many; an *individual* still carries at most two. |
| Sex-linked = sex-influenced | Sex-linked genes are **on a sex chromosome**; sex-influenced genes are **autosomal** but expressed differently by hormonal context. |
| Barr body = Y chromosome or extra X that adds genes | It is the **condensed inactive X** — count = X chromosomes − 1; it exists for dosage compensation. |
| Calico cats are a breed / always female by chance | Colour patches are **X-inactivation of an X-linked allele**; two alleles are required, so calicos are almost always XX. |
| Lethal allele = always harmful | Only a specific genotype dies (usually the homozygote); heterozygotes are typically normal. |
| A dominant trait must appear every generation | Not with incomplete penetrance — non-penetrant carriers make it skip generations. |
| Continuous variation is non-Mendelian | It is **many Mendelian loci plus environment** — no single ratio, but segregation still applies. |
| 9:3:4 is a random deviation | It is 9:3:3:1 with two classes merged by masking — read ratios as combinations of independent events. |

## Key facts

- **Incomplete dominance**: heterozygote is intermediate (red × white → pink); **F2 phenotype 1:2:1**, equal to the genotype ratio.
- **Codominance**: both alleles fully expressed together — roan coat, and ABO *I^A* with *I^B* giving group AB.
- **ABO**: three alleles (*I^A*, *I^B*, *i*); *I^A*/*I^B* codominant, both dominant to *i*; **O = universal donor (red cells), AB = universal receiver**; plasma antibodies are made against absent antigens.
- **Bombay phenotype (*hh*)**: no H substance → serologically type O regardless of *I* genotype; can receive only from other Bombay donors — genotype and serological phenotype can disagree.
- **X-linked recessive**: males hemizygous and thus more often affected; carrier mother → ½ sons affected; affected father → all daughters carriers, no sons; **criss-cross transmission** through unaffected females.
- **X-linked dominant**: affected father → **all daughters, no sons**; every generation; roughly equal sex ratio.
- **X-inactivation (Lyonisation)**: one X silenced at random early in development → female mosaic; condensed X = **Barr body (X − 1)**; calico/tortoiseshell cats are heterozygous females (calico males are usually XXY).
- **Sex-influenced traits** are autosomal with sex-dependent dominance (pattern baldness: dominant in males, recessive in females).
- **Lethal alleles**: homozygous lethal dominant → **2:1** survivors; recessive lethal → affected class absent before birth.
- **Epistasis**: one locus masks another — recessive epistasis gives **9:3:4** from a dihybrid cross (coat colour: *ee* hides black/brown).
- **Polygenic traits** show continuous, roughly normal variation from many additive loci plus environment; "threshold" traits look discrete but are polygenic underneath.
- **Penetrance** = proportion of carriers showing any phenotype; **expressivity** = severity range among those affected; both can make a dominant trait appear to skip generations.

## Practice questions

**1. Red-flowered snapdragons are crossed with white-flowered ones and all offspring are pink. When the pink plants self-fertilise, the F2 gives 1 red : 2 pink : 1 white. This is best explained by**

A. Blending inheritance of the flower colour factor
B. Codominance, with red and white both fully visible in the pink petal
C. Incomplete dominance, with the heterozygote intermediate in pigment amount
D. A recessive lethal allele removing one class

**Answer: C**

Explanation: The heterozygote produces about half the pigment of the homozygote, giving an intermediate pink phenotype — incomplete dominance — and because no allele is fully dominant, the F2 phenotypic ratio equals the 1:2:1 genotype ratio. It is not blending (A), because red and white reappear intact in the F2, proving the factors remained discrete. The petals are uniformly pink rather than showing two distinct components (which would be codominance, B), and no class is missing (D).

---

**2. A roan cow has a mixture of red and white hairs, each hair a solid colour. This demonstrates**

A. Incomplete dominance producing a uniform intermediate hair colour
B. Codominance — both alleles expressed fully in different cells
C. A recessive lethal genotype
D. Polygenic inheritance of coat colour

**Answer: B**

Explanation: Each hair follicle expresses either the red allele or the white allele completely, so both phenotypes are visible simultaneously in one animal — the definition of codominance (the ABO *I^A I^B* genotype is the equivalent at the molecular level). An intermediate pink-coloured hair would indicate incomplete dominance (A); nothing about viability (C) or multiple loci (D) is involved.

---

**3. A mother of blood group A and a father of blood group B have a child of blood group O. What are the parents' genotypes?**

A. *I^A I^A* and *I^B I^B*
B. *I^A i* and *I^B i*
C. *I^A I^B* and *ii*
D. *I^A i* and *I^B I^B*

**Answer: B**

Explanation: Group O is *ii*, so the child must have received one *i* from each parent — therefore both parents must be heterozygous (*I^A i* and *I^B i*). Homozygous parents (A) could never transmit *i*; a parent of genotype *I^A I^B* is group AB, not A (C); and D leaves no source of a second *i* if the father is homozygous *I^B I^B*.

---

**4. Why can group O red cells be given to a recipient of any ABO group?**

A. Group O plasma contains anti-A and anti-B antibodies
B. Group O red cells carry neither A nor B antigen for recipient antibodies to attack
C. Group O individuals have no immune system response to blood groups
D. Group O cells are larger and resist lysis

**Answer: B**

Explanation: Transfusion reactions occur when recipient antibodies bind antigens on donated red cells; group O cells display neither A nor B antigen, so no anti-A or anti-B in the recipient can bind them. The statement in A is true but is exactly why group O *plasma* is not universal — it contains both antibodies. Options C and D describe no real mechanism.

---

**5. A woman is a carrier for an X-linked recessive condition (*X^H X^h*) and her partner is unaffected. What are the expected outcomes for their children?**

A. Half of all children affected, regardless of sex
B. Half the sons affected; no daughters affected (half become carriers)
C. All sons affected; all daughters carriers
D. All children unaffected because the mother is unaffected

**Answer: B**

Explanation: Each son receives either *X^H* or *X^h* from his mother and a Y from his father, so half are affected; each daughter receives a normal *X^H* from her father, so none is affected, but half inherit *X^h* and become carriers. C would require the father to be affected (so no *X^H* to give daughters), and D ignores segregation in the mother's gametes.

---

**6. In a pedigree, an affected father has four children with an unaffected mother: every daughter is affected and no son is. The pattern is most consistent with**

A. Autosomal recessive inheritance
B. X-linked recessive inheritance
C. X-linked dominant inheritance
D. Y-linked inheritance

**Answer: C**

Explanation: A father passes his only X to all his daughters and his Y to all his sons, so an X-linked dominant allele gives affected daughters and unaffected sons — precisely the observed pattern. Autosomal recessive (A) would require the mother to be a carrier and would not give an all-daughters result; X-linked recessive (B) would leave daughters as unaffected carriers; Y-linked (D) could only affect sons.

---

**7. Calico cats (patches of orange and black fur) are almost always female. The best explanation is**

A. The orange and black alleles are autosomal and female-limited
B. Two X chromosomes with random X-inactivation create patches of cells expressing one allele each
C. Females inherit two coat-colour genes, males only one
D. Hormones switch the allele on and off during development

**Answer: B**

Explanation: The orange/black locus is X-linked, so two different alleles — and therefore two X chromosomes — are needed; early random silencing of one X in each cell lineage makes each patch a clone expressing the other. This gives mosaicism in heterozygous females. The rare calico male is almost always XXY, supporting the chromosome-dosage explanation; the gene is not female-limited (A), and hormonal switching (D) would not produce clonal patches.

---

**8. A dihybrid cross produces 2 dominant-phenotype : 1 recessive-phenotype offspring instead of 3:1 at one locus. The most likely explanation is**

A. Incomplete dominance
B. The homozygous dominant genotype is lethal
C. The two genes are linked
D. The recessive allele is sex-linked

**Answer: B**

Explanation: A 2:1 ratio is the classic signature of a dominant allele whose homozygous form dies before the ratio is counted — the expected 1 *AA* : 2 *Aa* : 1 *aa* loses the *AA* class, leaving 2 dominant to 1 recessive (as with the yellow mouse or achondroplasia). Incomplete dominance (A) gives a third, intermediate phenotype; linkage (C) skews dihybrid ratios rather than deleting a monohybrid class; sex-linkage (D) produces sex-specific rather than overall 2:1 ratios.

---

**9. In Labrador retrievers, dogs with the epistatic genotype *ee* are yellow regardless of whether their B alleles specify black or brown. A dihybrid × dihybrid cross gives which ratio?**

A. 9:3:3:1
B. 9:7
C. 9:3:4
D. 1:2:1

**Answer: C**

Explanation: The standard 9:3:3:1 classes are 9 *E_B_* (black), 3 *E_bb* (brown), 3 *eeB_* (yellow), 1 *eebb* (yellow) — but *ee* masks the B locus, merging the last two classes into 4, giving 9 black : 3 brown : 4 yellow. This is recessive epistasis. Option A would apply with no interaction, 9:7 arises when both dominant genes are needed for any pigment, and D is a monohybrid genotype ratio.

---

**10. A genetic condition is described as "80% penetrant with variable expressivity". Which statement is correct?**

A. 80% of carriers show some sign, and those who show signs differ in severity
B. 80% of affected individuals are severe cases
C. The gene is present in only 80% of cells
D. Expressivity of 80% means 80% of carriers are unaffected

**Answer: A**

Explanation: Penetrance is the proportion of carriers who express *any* phenotype — here 80%, with 20% clinically normal despite carrying the genotype. Expressivity describes variation *among those who express it* — mild through severe — so the same mutation can look very different within one family. Options B and D swap the two definitions, and C confuses organism-level penetrance with cellular mosaicism (X-inactivation).
