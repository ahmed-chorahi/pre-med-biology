# Mendelian Inheritance and Punnett Squares

## Why it matters

Mendel's two laws are the grammar of genetics: everything before them is vocabulary ([01 — Genes, alleles, genotype, phenotype](01-genes-alleles-genotype-phenotype.md)), everything after them — pedigrees, human disease patterns, population genetics — is a sentence built with them. They are also **mechanistic laws**: each one is a direct consequence of a physical event you have already met in [12 — Meiosis](../03-cellular-processes/12-meiosis.md), and any exam that asks "state the law" is really asking "what happens at which stage of meiosis, and what ratio follows".

```
LAW OF SEGREGATION        the two alleles of a locus separate      →  3:1 in a monohybrid cross
                          because homologues separate in anaphase I

LAW OF INDEPENDENT        alleles at different loci separate       →  9:3:3:1 in a dihybrid cross
ASSORTMENT                independently because different chromosome
                          pairs line up independently at metaphase I
```

The Punnett square is not the biology — it is a **probability grid** that makes the biology countable. Learn when the predicted ratios hold, how to compute them with the sum and product rules, and — just as important — when they break. Ratios that fail are how geneticists discover linkage, lethality, and epistasis.

## The two laws and their meiotic basis

### Law of segregation

> **The two alleles of a single gene separate during gamete formation, so each gamete receives exactly one.**

| Element | Detail |
| --- | --- |
| **Physical basis** | Homologous chromosomes pair in prophase I and **separate in anaphase I** |
| **What separates** | The two homologues — and with them, the two alleles at the locus |
| **Result** | Each gamete is **monogenic** for the locus: one allele, no more |
| **Chance per gamete** | Each allele goes to half the gametes → ½ : ½ |

```
diploid cell:   ──A── ──a──     homologous pair, one allele each
                    │
        meiosis I (anaphase I: homologues part)
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
      ──A──                   ──a──        two gamete types, ½ each
        │                       │
        ▼                       ▼
   (fusion with a random gamete restores 2n — see F1)
```

**Why alleles do not "blend".** If the products of the two alleles mixed permanently in the parent, the recessive form could never reappear intact — and yet 25% of an F2 from two heterozygotes are pure recessive. The F2's 1:2:1 genotype ratio is itself the evidence for particulate inheritance.

### Law of independent assortment

> **Alleles at different loci segregate independently of one another.**

| Element | Detail |
| --- | --- |
| **Physical basis** | Each bivalent aligns at the metaphase I plate **independently of every other bivalent**; each homologue faces a pole at random |
| **Consequence** | The allele you get at locus 1 tells you nothing about the allele you get at locus 2 |
| **Scope** | True for loci on **different chromosomes** (and for far-apart loci on the same chromosome). Genes on the same chromosome are **linked** and do not obey it — the great exception |
| **Scale in humans** | 2²³ ≈ 8.4 million chromosome combinations per parent, before crossing over |

```
METAPHASE I — two independent pairs:

   alignment 1          alignment 2          alignment 3          alignment 4
   A ─    ─ a           A ─    ─ a           A ─    ─ a           A ─    ─ a
   B ─    ─ b           b ─    ─ B           B ─    ─ a...        b ─    ─ B
   → AB, ab             → Ab, aB             → AB, ab             → Ab, aB

each of the 4 alignments is equally likely → gametes AB : Ab : aB : ab = 1:1:1:1
```

The full mechanics — pairing, crossing over, alignment, segregation — are in [12 — Meiosis](../03-cellular-processes/12-meiosis.md); what this chapter adds is the *arithmetic those mechanics produce*.

## The monohybrid cross: 3:1

A **monohybrid cross** tracks one locus: two true-breeding contrasting parents, then F1 × F1.

```
P:    ♀ TT  ×  ♂ tt        true-breeding
            │
            ▼  (gametes T and t; each parent makes one type)
F1:         Tt             100% dominant phenotype
            │  self / intercross (each parent makes T and t gametes, ½ each)
            ▼
PUNNETT SQUARE (F1 × F1)

          egg T        egg t
sperm T │   TT    │    Tt    │
        │         │         │
sperm t │   Tt    │    tt    │
        └─────────┴─────────┘

genotypes:  1 TT : 2 Tt : 1 tt          = 1 : 2 : 1
phenotypes: 3 dominant : 1 recessive    = 3 : 1
```

Reading the grid:

- Four squares of **equal probability** (each = ¼), because each parental gamete is equally likely and fertilisation is random.
- The two heterozygote squares merge phenotypically because dominance hides the *t* — so **genotype ratio 1:2:1, phenotype ratio 3:1**, from the same four squares.

**The product rule already visible here:** *aa* requires an *a* egg (½) *and* an *a* sperm (½) → ½ × ½ = ¼.

## Test cross and back cross

| Cross | Definition | Purpose | Expected ratio |
| --- | --- | --- | --- |
| **Test cross** | Unknown dominant phenotype × **homozygous recessive (*aa*)** | Read out the unknown genotype | *AA* × *aa* → all dominant; ***Aa* × *aa* → 1 dominant : 1 recessive** |
| **Back cross** | Unknown × **one of the original parental genotypes** | Restore or confirm a parental genotype | Depends which parent |

```
A?  ×  aa

A? = AA  →  100% Aa               →  phenotype alone could not have told you
A? = Aa  →  ½ Aa  +  ½ aa         →  each offspring reports one of the parent's gametes
```

**Why it works:** the tester donates only recessive alleles, so every offspring that shows the recessive phenotype is *aa* and must have received an *a* from the unknown parent. Any single recessive offspring proves heterozygosity; all-dominant offspring over a large sample supports (but, over a small sample, does not prove) homozygosity.

For a **dihybrid** unknown (*A?B?*) the tester is *aabb*, and a dihybrid gives **1:1:1:1** — the standard exam follow-up.

## The dihybrid cross: 9:3:3:1

Two true-breeding parents differing at **two** loci (*AABB* × *aabb*):

```
P:    AABB × aabb
              ▼
F1:            AaBb        (both loci heterozygous; dominant at both)
              │  self
              ▼
gametes of F1:  AB   Ab   aB   ab        (each ¼ — independent assortment)

F1 × F1 — 4 × 4 = 16 equally likely squares:

        ┌──────┬──────┬──────┬──────┐
   AB   │ TTYY │ TTYy │ TtYY │ TtYy │
        ├──────┼──────┼──────┼──────┤
   Ab   │ TTYy │ TTyy │ TtYy │ Ttyy │
        ├──────┼──────┼──────┼──────┤
   aB   │ TtYY │ TtYy │ ttYY │ ttYy │
        ├──────┼──────┼──────┼──────┤
   ab   │ TtYy │ Ttyy │ ttYy │ ttyy │
        └──────┴──────┴──────┴──────┘

phenotype classes:   9  T_Y_  (round, yellow — both dominant)
                     3  T_yy  (round, green)
                     3  ttY_  (wrinkled, yellow)
                     1  ttyy  (wrinkled, green)
```

**Where 9:3:3:1 comes from — a shortcut you should use instead of counting squares:**

```
at locus T:  3 dominant : 1 recessive
at locus Y:  3 dominant : 1 recessive
independent events → multiply:

  (3/4 × 3/4) = 9/16     (3/4 × 1/4) = 3/16
  (1/4 × 3/4) = 3/16     (1/4 × 1/4) = 1/16
                     → 9 : 3 : 3 : 1
```

Every dihybrid ratio is a **monohybrid ratio multiplied by another monohybrid ratio** — because independent assortment says the loci are independent events. The genotype ratio, by the same logic, is 1:2:1 squared: **1:2:1:2:4:2:1:2:1** across the nine genotype classes.

## Probability rules for genetics

Punnett squares and probability are two routes to the same answer. The rules are:

**Sum rule — mutually exclusive events: add their probabilities.**

```
P(A or B) = P(A) + P(B)     when A and B cannot both happen

Two Aa parents: a child cannot be both AA and aa.

P(dominant phenotype) = P(AA) + P(Aa) = ¼ + ½ = ¾      (two mutually exclusive routes
                                                          to the same phenotype)
```

**Product rule — independent events: multiply their probabilities.**

```
P(A and B) = P(A) × P(B)     when the events do not influence each other

Two Aa parents:
   P(aa child) = P(a from mother) × P(a from father) = ½ × ½ = ¼

   P(child is aa AND male)      = ¼ × ½ = 1/8
   P(three children all Aa)     = ½ × ½ × ½ = 1/8
   P(first two unaffected, third affected)
                               = ¾ × ¾ × ¼ = 9/64
   P(at least one aa among three)
                               = 1 − P(none) = 1 − (¾)³ = 1 − 27/64 = 37/64
```

**Working conventions worth memorising:**

- "At least one" → use the **complement**: 1 − P(none).
- The **sex of each child** is an independent event (½ each), so P(three boys) = ⅛ — combinations multiply across sex and genotype alike.
- Each conception is **independent of the last**: after three unaffected children, the risk for the next is still ¼.

## When the ratios change

The classic ratios are conditional — they assume Mendelian segregation, independent assortment, no selection, full penetrance, and plenty of offspring. Break an assumption and the ratio moves in a *diagnosable* way.

| Situation | What changes | Observed ratio (F2 or cross) | Why |
| --- | --- | --- | --- |
| **Recessive lethal / dominant homozygous lethal** | One genotype dies before counting | **2 : 1** instead of 1:2:1 (phenotypes 2 dominant : 1 recessive where *AA* dies) | e.g. yellow mouse homozygotes; achondroplasia homozygotes die |
| **Incomplete dominance** | Heterozygote has its own phenotype | **1 : 2 : 1 phenotype** (as well as genotype) | Heterozygote no longer merges with a homozygote — [03 — Non-Mendelian patterns](03-non-mendelian-patterns.md) |
| **Codominance** | Both alleles expressed | 1:2:1 phenotype, two components visible | Blood groups, roan coat |
| **Sex linkage** | Ratio differs between males and females | e.g. all sons affected from a carrier mother | Locus on X — hemizygous males — [05 — Human inheritance patterns](05-human-inheritance-patterns.md) |
| **Epistasis** | One locus masks another | 9:3:**4**, 9:**7**, 12:3:1… | Pathway logic — [03 — Non-Mendelian patterns](03-non-mendelian-patterns.md) |
| **Linkage** | Loci on the same chromosome co-segregate | Parental overrepresented, recombinants underrepresented | Independent assortment fails; basis of gene mapping |
| **Non-penetrance** | Genotype present, phenotype absent | Fewer affected than predicted | Genotype → phenotype chain interrupted |
| **Small samples** | Random deviation | Anything close to the ratio | Ratios are *probabilities*; χ² testing asks if deviation exceeds chance |

**Linkage is the one to hold onto:** independent assortment is a statement about *chromosomes*, so genes riding the same chromosome tend to travel together. Recombination frequency becomes a measure of distance — the foundation of genetic mapping, and the reason a deviation from 9:3:3:1 is informative rather than an error.

## Medical relevance

**Recurrence risk is the everyday use of these ratios.** Two carrier parents for an autosomal recessive condition have, for *every* pregnancy, an independent ¼ chance of an affected child, ½ chance of a carrier, ¼ chance of neither — a risk, not a schedule. The commonest counselling error is treating an affected first child as "using up" the ¼: each conception resets the dice.

**Screening arithmetic uses the product and sum rules directly.** If carrier frequency is 1 in 25 for cystic fibrosis, the chance a random couple are both carriers is (1/25) × (1/25), and the chance their child is affected multiplies by ¼ — the calculation behind population carrier-screening programmes and prenatal testing decisions.

**Why ratios are the diagnostic evidence for a mode of inheritance.** "Unaffected parents, affected child" (¼ expected) is the signature of a recessive allele; "affected in every generation, affected × unaffected gives ~½ affected" is the signature of a dominant one. Pedigree analysis ([04 — Pedigree analysis](04-pedigree-analysis.md)) is this logic applied to real families rather than Punnett grids.

**Deviation from expected ratios has clinical meaning.** A family that repeatedly produces only dominant-phenotype offspring at a locus where ¼ recessive is expected may be looking at linkage (useful for mapping a disease gene), non-penetrance (important for counselling a "healthy" carrier of a dominant allele), or a phenocopy. Ratios are not decoration — they are data.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| 3:1 quoted where 1:2:1 is asked | 3:1 is **phenotypic**; 1:2:1 is **genotypic**. Both come from the same four squares. |
| "The F1 is always dominant" | Only if the P generation was true-breeding for contrasting traits — otherwise the F1 segregates. |
| A Punnett square predicts a family's actual children | It gives **probabilities per birth**. A family of four will often not be 3:1; small samples deviate by chance. |
| Test cross = back cross | A back cross is to *any* parental genotype; a test cross is specifically to the **homozygous recessive**. |
| Independent assortment applies to all genes | Only to genes on **different chromosomes** (or far apart on one). Same-chromosome genes are linked. |
| "Three healthy children, so the fourth must be affected" | Each conception is independent — the risk stays ¼ every time. |
| Ratios must be exact to be correct | Ratios are expectations for **large samples**; statistically insignificant deviation is normal. |

## Key facts

- **Law of segregation**: the two alleles at a locus separate into different gametes — the physical event is **separation of homologues in anaphase I** of meiosis.
- **Law of independent assortment**: alleles at different loci segregate independently — the physical event is **independent alignment of bivalents at metaphase I**; it fails for linked genes on the same chromosome.
- Monohybrid cross of two heterozygotes: **genotype 1:2:1, phenotype 3:1**; the four Punnett squares each represent probability ¼.
- Dihybrid cross (*AaBb* × *AaBb*): **9:3:3:1 phenotype**, obtained by multiplying the two independent monohybrid ratios (¾ and ¼), not by counting squares.
- **Test cross** (*A?* × *aa*): all dominant → probably *AA*; **1:1** → *Aa*. For two unknown loci, use *aabb* → 1:1:1:1.
- **Back cross** = cross to a parental genotype; a test cross is the special case using the homozygous recessive.
- **Sum rule**: mutually exclusive outcomes → add (e.g. P(dominant) = P(*AA*) + P(*Aa*) = ¾).
- **Product rule**: independent outcomes → multiply (e.g. P(*aa* child) = ½ × ½ = ¼); "at least one" = 1 − P(none).
- Every pregnancy is an **independent trial** — risks do not change because of previous outcomes.
- Ratios shift in **diagnosable** ways: **2:1** (lethality), **1:2:1 phenotype** (incomplete dominance), **9:3:4** (epistasis), sex-specific ratios (X-linkage), skewed classes (linkage).
- Punnett squares are probability grids, not predictions for a specific small family.

## Practice questions

**1. The law of segregation is best described by which meiotic event?**

A. Independent alignment of bivalents at metaphase II
B. Separation of homologous chromosomes at anaphase I, taking the two alleles with them
C. Crossing over between non-sister chromatids at pachytene
D. Separation of sister chromatids at anaphase II

**Answer: B**

Explanation: The two alleles occupy the two homologues of a pair, so when homologues part in anaphase I, the alleles part with them — each gamete ends up with one allele. Metaphase I alignment (A) is the basis of the *second* law, crossing over (C) reshuffles alleles without separating them, and anaphase II (D) separates identical sisters, which does not move alleles apart.

---

**2. Independent assortment of two loci on different chromosome pairs produces which gamete ratio from *AaBb*?**

A. 1 *AB* : 1 *ab*
B. 1 *AB* : 1 *Ab* : 1 *aB* : 1 *ab*
C. 3 *AB* : 1 *ab*
D. 9:3:3:1

**Answer: B**

Explanation: Each bivalent aligns independently, so allele *A* or *a* combines with allele *B* or *b* with equal probability — four equally frequent gamete types. Option A is the result for *complete linkage* (only parental combinations), C is a skewed segregation, and D is a four-gamete *phenotype* ratio in an F2, not a gamete ratio.

---

**3. In the F2 of a monohybrid cross, what is the genotype ratio?**

A. 3:1
B. 1:2:1
C. 9:3:3:1
D. 1:1

**Answer: B**

Explanation: *Aa* × *Aa* yields ¼ *AA*, ½ *Aa*, ¼ *aa* — the 1:2:1 genotype ratio. Because the heterozygote shares the dominant phenotype with *AA*, the phenotypic ratio collapses to 3:1 (A). C is the dihybrid phenotype ratio and D the test-cross ratio, so quoting the wrong one of these three classic ratios is the commonest slip.

---

**4. Two true-breeding plants, one tall and one dwarf, are crossed. The F1 are all tall. This shows that**

A. Dwarfness is dominant
B. The F1 has been genetically silenced
C. Tallness is dominant and the parents were homozygous
D. The parents were both heterozygous

**Answer: C**

Explanation: A uniform F1 showing one parental phenotype means the contrasting alleles were pure in the P generation and one is dominant — true-breeding parents can only be homozygous (so D is excluded). If dwarfness were dominant (A), the F1 would be dwarf; no silencing is involved (B), since the heterozygote genuinely makes the dominant phenotype.

---

**5. A dihybrid *AaBb* is test-crossed with *aabb*. What phenotypic ratio is expected if the loci assort independently?**

A. 9:3:3:1
B. 3:1
C. 1:1:1:1
D. 1:2:1

**Answer: C**

Explanation: The tester *aabb* produces only *ab* gametes, so offspring phenotypes directly mirror the four equally frequent gametes *AB*, *Ab*, *aB*, *ab* of the dihybrid — each giving a distinct phenotype class in equal numbers. A is the dihybrid intercross ratio, B the monohybrid intercross phenotype ratio, and D the monohybrid genotype ratio.

---

**6. Two carriers (*Aa* × *Aa*) have three children, none affected. What is the probability that the fourth child is affected?**

A. ¼, because one affected child is "due"
B. ¾
C. ¼, because each conception is an independent event
D. 0, since three unaffected children prove the parents are not carriers

**Answer: C**

Explanation: Every fertilisation is an independent trial with the same ¼ chance of an *aa* zygote — previous births neither use up nor adjust that probability. The assumption "one is due" is the gambler's fallacy applied to genetics. Option A gives the right number for the wrong reason, and D is impossible since the couple's carrier status is fixed by their genotypes, not by their offspring.

---

**7. Two heterozygous parents plan three children. What is the probability that all three are unaffected by the recessive condition?**

A. ¾
B. 27/64
C. 1/64
D. 9/64

**Answer: B**

Explanation: An unaffected child has probability ¾ (any genotype except *aa*), and the three births are independent, so the product rule gives ¾ × ¾ × ¾ = 27/64. Option A is the probability for one child, C would be three *affected* children, and D is the probability of two unaffected followed by one affected — a different, ordered event.

---

**8. In a cross of two heterozygotes, one homozygous dominant genotype dies before birth. What phenotypic ratio is observed among surviving offspring?**

A. 3:1
B. 1:2:1
C. 2:1
D. 9:3:3:1

**Answer: C**

Explanation: The expected 1 *AA* : 2 *Aa* : 1 *aa* becomes 2 *Aa* : 1 *aa* once the *AA* class is removed, so only two phenotypic classes survive in a 2:1 ratio — the classic signature of a dominant homozygous lethal allele (as in the yellow mouse or achondroplasia). The heterozygote's survival is what keeps the dominant phenotype present at all.

---

**9. Which situation would cause a dihybrid cross to deviate from 9:3:3:1 because the law of independent assortment does not apply?**

A. The two loci are on the same chromosome and close together
B. Both loci show complete dominance
C. The parents are true-breeding
D. The F1 is heterozygous at both loci

**Answer: A**

Explanation: Independent assortment is a statement about chromosome pairs aligning independently; alleles physically on the same chromosome travel together, so their combinations are non-random and the 9:3:3:1 expectation fails (the basis of linkage mapping). Complete dominance (B), true-breeding parents (C), and a doubly heterozygous F1 (D) are all standard *assumptions* under which 9:3:3:1 is produced.

---

**10. Two carrier parents have an affected child. What is the chance their next child is a carrier rather than affected?**

A. ¼
B. ½
C. ¾
D. ⅛

**Answer: B**

Explanation: From *Aa* × *Aa*, each child independently has ¼ *AA*, ½ *Aa*, and ¼ *aa* — so a carrier (heterozygous, unaffected) has probability ½. ¾ (C) is the chance of being *unaffected by any genotype* (carrier or *AA*), ¼ (A) the chance of being affected or of *AA*, and ⅛ would require an additional independent event such as also being male.
