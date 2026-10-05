# Pedigree Analysis

## Why it matters

A pedigree is a **probability problem written in symbols**. Clinicians take one because it is the fastest, cheapest genetic test there is: three generations of family history can point to the mode of inheritance before a single sample is sent, and it tells you *which* test to order and *what result to expect*. For exams, pedigrees are the standard way of testing whether you actually understand dominance, segregation, and hemizygosity — everything in [01 — Genes, alleles](01-genes-alleles-genotype-phenotype.md), [02 — Mendelian inheritance](02-mendelian-inheritance-and-punnett-squares.md), and [03 — Non-Mendelian patterns](03-non-mendelian-patterns.md) applied to real people.

The logic is always the same **reverse inference**:

```
observed pattern in the chart
        │   apply 3 questions
        ▼
mode of inheritance (autosomal dominant / recessive / X-linked / other)
        │   assign genotypes to obligate carriers and at-risk individuals
        ▼
recurrence risk for the next pregnancy
```

The rules below reduce the whole procedure to three questions, one decision table, and the arithmetic of conditional probability.

## The symbols

```
  □ male            ○ female            ? unknown sex / undetermined

  ■ affected male   ● affected female   ▨ sex-unknown affected

  ──── mating       ════ consanguineous mating (double line)

         │
    ─────┴─────    sibship (vertical line drops from the mating)

  □    ●    ○      siblings left → right in order of birth

  □̸  (diagonal through symbol) = deceased

  ▷  arrow = PROBAND (the person who brought the family to attention)

  generation numbering:  I, II, III (Roman) down the side
  individual numbering:  1, 2, 3 (Arabic) within each generation
```

Reading convention: **I-1** = first individual of generation I. A horizontal line is a mating (not a blood relationship); a vertical line below it leads to offspring; symbols under a bracket are siblings.

## The three-question method

Ask these in order — most exam pedigrees resolve in one or two.

```
QUESTION 1: DOES THE TRAIT SKIP GENERATIONS?
   (an affected individual with two UNAFFECTED parents)
        │
   YES ─┴─▶  RECESSIVE   (autosomal recessive, or X-linked recessive — go to Q3)
   NO  ─┴─▶  DOMINANT    (affected people have affected parents; go to Q2)

QUESTION 2: DO AFFECTED FATHERS PASS THE TRAIT TO ALL DAUGHTERS AND NO SONS?
        │
   YES ─┴─▶  X-LINKED DOMINANT
   NO  ─┴─▶  AUTOSOMAL DOMINANT   (males and females equally; father → son possible)

QUESTION 3: ARE FAR MORE MALES AFFECTED, AND IS THERE NEVER MALE-TO-MALE TRANSMISSION?
        │
   YES ─┴─▶  X-LINKED RECESSIVE
   NO  ─┴─▶  AUTOSOMAL RECESSIVE  (both sexes affected, roughly equally)
```

**Why skipping means recessive:** an affected child needs two copies (or, on the X, a pattern masked in carriers). With rare dominant alleles, both parents being affected is expected — so an affected child of unaffected parents points to two silent carriers.

**Why never male-to-male matters:** a father gives his **Y** to his sons and his **X** to his daughters. A father-to-son transmission therefore *excludes* the X chromosome — the single most reliable observation in pedigree questions.

## The full decision table

| Observation in the chart | Most likely mode | Reasoning |
| --- | --- | --- |
| Every generation affected; affected × unaffected → ~½ affected; **father-to-son transmission present** | **Autosomal dominant** | One copy suffices; both sexes pass it |
| Trait skips generations; unaffected parents have affected children of **both** sexes; often consanguinity | **Autosomal recessive** | Two carriers needed; no sex bias |
| Mostly males; **never male-to-male**; affected grandfather → carrier daughter → affected grandson | **X-linked recessive** | Hemizygous males express; females shuttle the allele |
| Both sexes affected **equally**; affected father → **all daughters, no sons**; every generation | **X-linked dominant** | Heterozygous females affected; father's X goes only to daughters |
| **Only males, every generation**, father → **all sons** | **Y-linked** | The gene is on the Y; no female can ever be affected |
| **Mother** passes to all children (sons and daughters); father **never** passes; variable severity | **Mitochondrial** | mtDNA comes only from the egg — see [02 — Cell Biology](../02-cell-biology/04-energy-and-containment-organelles.md) |
| Affected only one sex but an autosomal-looking pattern | **Sex-limited / sex-influenced** | e.g. pattern baldness — autosomal, hormonal expression |
| Unaffected parents + affected child **for a known dominant condition** | **New mutation / germline mosaicism** | e.g. most achondroplasia arises anew; recurrence risk is low but not zero |

## Worked pedigree 1 — unaffected parents, affected daughter

```
PEDIGREE A

   I        □───────○
                     │
   II    ○───────●───□
                     │
   III               ○

   ● = affected female (the proband), reported by arrow in the real chart
```

**Words:** Generation I is an unaffected couple. They have three children — an unaffected daughter, an **affected daughter**, and an unaffected son. The affected daughter mates with an unaffected male, and they have an unaffected daughter in generation III.

**Step-by-step:**

1. **Does it skip?** Yes — II-2 is affected but both her parents are not. → **Recessive.**
2. **Which recessive?** Look at the affected *female*: her father is **unaffected**, so he has no pathogenic allele to give her — **X-linked recessive is excluded** (an affected female needs an affected father). Both sexes are represented among the children. → **Autosomal recessive.**
3. **Assign genotypes:** both parents of the affected woman are *Aa*; she is *aa*; her unaffected siblings are *Aa* or *AA*; her unaffected daughter (III-1) is an **obligate carrier** (*Aa*), because her mother can only pass *a* and her father gives *A*.

**Recurrence:** each pregnancy of the generation-I couple had a ¼ chance of being affected. Their unaffected children have a **2/3** chance of being carriers (below).

## Worked pedigree 2 — vertical pattern through males and females

```
PEDIGREE B

   I        ■───────○
                     │
   II       ●───□    ■───○
              │
   III   □────●

   ■ ● = affected
```

**Words:** An affected man in generation I has an affected daughter and an affected son among his children. The affected daughter has an affected daughter of her own.

**Step-by-step:**

1. **Does it skip?** No — every affected person has an affected parent, and the trait appears in every generation. → **Dominant.**
2. **Father-to-son?** Yes: I-1 (affected) → his affected *son* in generation II. The father gives sons the Y chromosome, so **the gene cannot be on the X** → **autosomal dominant.**
3. **Sanity checks:** both sexes affected; affected × unaffected matings give roughly ½ affected; no unaffected person transmits the trait. Consistent.

**Genotype bookkeeping:** every affected person is *Aa* (homozygous *AA* being typically lethal or vanishingly rare for dominant disease alleles); every unaffected person is *aa*; each child of an affected parent independently has a **½** chance of inheriting *A*.

## Worked pedigree 3 — male-skewed, through unaffected females

```
PEDIGREE C

   I            □───────○
                          │
   II            ●───□    □───■
                              │
   III                   □   ●?  ■

   ●? = the question mark individual: does the trait appear here?
```

**Words:** The trait appears in a male of generation II (his parents, generation I, are unaffected). He has no children. His **unaffected sister** has children, among whom a son is affected. There is never a male-to-male transmission anywhere, and three of four affected individuals are male.

**Step-by-step:**

1. **Does it skip?** Yes — the affected man in generation II has unaffected parents. → **Recessive.**
2. **Sex distribution?** Almost all male, and **no father-to-son transmission anywhere** in the chart. → **X-linked recessive.**
3. **Assign genotypes:** the affected man's mother (I-2) is an **obligate carrier** *X^H X^h* — she gave him *X^h*, which her own father could have supplied. His unaffected sisters each have a 50% chance of carrying it. He is *X^h Y* and passed *X^h* to his daughters only.

**Contrast with pedigree A:** both skip a generation, but A has an affected *female* with an unaffected father (autosomal) while C is male-skewed with no male-to-male transmission (X-linked). **Sex counts discriminate.**

## Obligate carriers

An **obligate carrier** is someone who *must* carry a pathogenic allele, deduced from relatives' phenotypes without testing.

| Pattern | Who is obligate | Why |
| --- | --- | --- |
| Autosomal recessive | **Both parents** of an affected child | The child is *aa*, so one *a* came from each |
| Autosomal recessive | **Unaffected sibling** of an affected child | Not obligate — conditional: **2/3 chance** (below) |
| X-linked recessive | **Mother of an affected male** | She passed *X^h* to him (new mutation excepted) |
| X-linked recessive | **All daughters of an affected male** | They receive his only X |
| Autosomal dominant | Affected individuals are *obligate* heterozygotes | One copy causes the phenotype |
| Autosomal dominant | Unaffected people **do not carry** the allele (with full penetrance) | Why reduced penetrance is such a common trap |

**The 2/3 calculation, worked:** two carriers (*Aa* × *Aa*) have an unaffected child. What is the chance the child is a carrier?

```
possible genotypes:  AA (¼)   Aa (½)   aa (¼)
the child is NOT aa, so the sample space shrinks to AA + Aa = ¾

P(carrier | unaffected) = P(Aa) / P(not aa) = (½) / (¾) = 2/3
```

**Clinically:** 2/3 is quoted for siblings of an affected child until that sibling is genotyped, when the answer becomes 0 or 1. Conditional probability is the arithmetic of genetic counselling.

## Consanguinity

A **consanguineous mating** (double horizontal line) means the partners are relatives — first cousins being the classic exam example.

```
shared ancestors
       │
       ▼
both partners inherit the SAME ancestral allele by descent
       │
       ▼
recessive allele now meets itself  →  aa child (homozygous by inheritance)
```

- First cousins share, on average, **1/8 of their segregating genes** (coefficient of relationship *r* = 1/8).
- The chance their child is homozygous *for a particular allele* carried by a common ancestor = **1/16** (inbreeding coefficient *F*) — versus a much smaller population-wide chance.
- **Diagnostic use in pedigrees:** consanguinity + an autosomal-recessive-looking pattern is the strongest single combination pointing to AR inheritance.
- Rare recessive diseases then appear more often and often at **earlier onset and greater severity**; an affected person mating with a carrier gives the trait in consecutive generations — *pseudo-dominance*, which mimics a dominant pattern.

## Recurrence risk calculation

Risks are per pregnancy, independent, and stated for relatives of the proband, not just parents.

| Mating | Risk to each child of being **affected** | Risk an **unaffected** sibling is a carrier |
| --- | --- | --- |
| *Aa* × *Aa* (AR) | ¼ | 2/3 |
| *Aa* × *aa* (AR) | ½ | n/a — all children are *Aa* or *aa* |
| *AA* × *aa* | 0 (all *Aa*) | 100% carriers |
| Affected (*Aa*) × unaffected (*aa*) — AD | ½ | n/a |
| Carrier mother × unaffected father (XLR) | ½ of **sons**, ½ of **daughters** are carriers → **1/4 of all children affected** | Each daughter: ½ |
| Affected father × unaffected mother (XLR) | 0 affected; **all daughters carriers** | All daughters obligate |
| Mitochondrial, affected mother | all children (variable expression); affected father → **none** | n/a |

**Worked risk problems:**

1. *Two carriers, one affected child already.* Next pregnancy: **¼ affected, ½ carrier, ¼ non-carrier** — unchanged by the previous outcome; an unaffected next child is a carrier with probability 2/3.
2. *From screening to incidence:* if carrier frequency is 1 in 25, the chance a random couple are both carriers is (1/25)² = 1/625, and multiplying by ¼ gives an incidence of **1 in 2,500** — the arithmetic behind carrier-screening policy ([05 — Human inheritance patterns](05-human-inheritance-patterns.md)).
3. *X-linked:* carrier woman × unaffected man → risk of an affected child overall = ½ (son) × ½ (gets *X^h*) = **1/8**, but the risk **given the child is male** is ½. Always state which denominator you are using.

## Common confusions

| Trap | The correct move |
| --- | --- |
| "Rare dominant disease — probably recessive in this family" | Rarity in the *population* says nothing about the mode; the *chart* decides. |
| Affected child of unaffected parents → immediately "autosomal" | Check the child's sex: an affected **daughter** with an unaffected father excludes XLR; otherwise count the sexes across the sibship. |
| Assuming no male-to-male transmission proves X-linkage | Only if the trait also skips and is male-skewed; a dominant male-only trait passed father-to-son is Y-linked. |
| Invoking non-penetrance first | A "healthy" parent of an autosomal dominant child may be non-penetrant — but use this *after* recessive models are excluded. |
| Missing a new mutation | Unaffected parents are consistent with a dominant condition such as achondroplasia: most cases are new mutations, and germline mosaicism keeps recurrence low but non-zero. |
| Treating sibling risk as ½ | Carrier probabilities are **conditional**: an unaffected sibling of an *aa* child is a carrier with probability **2/3**, not ½. |
| Misreading the double line | **Double line = consanguineous mating** — a deliberate pointer to recessive inheritance. |
| Forgetting the arrow | The **arrow marks the proband** — their phenotype anchors the genotypes of relatives. |

## Medical relevance

**Genetic counselling runs on this chapter.** The core deliverable is a recurrence risk stated in words — "each pregnancy has a one-in-four chance" is the product rule from [02 — Mendelian inheritance](02-mendelian-inheritance-and-punnett-squares.md) applied to a family — followed by conditional risks for unaffected siblings (2/3) and relatives who are obligate versus at-risk carriers.

**Carrier testing follows the pedigree, not the other way round.** A three-generation history decides whom to test: sisters of an affected boy for Duchenne/haemophilia carrier status (now molecular), adult relatives of a cystic fibrosis proband, and both partners before pregnancy when the history suggests a recessive allele. Consanguineous couples are offered preconception screening, since shared ancestry raises autosomal recessive risk (the 1/16 figure for first cousins).

**Cancer genetics is pedigree work in practice.** Early-onset breast and ovarian cancer in several generations triggers *BRCA1/2* testing — where **penetrance is quoted, not certainty** ([03 — Non-Mendelian patterns](03-non-mendelian-patterns.md)) — and an unaffected test-positive relative is offered surveillance rather than a diagnosis.

**Pattern recognition also shortens diagnosis and saves testing.** The "only males, never father-to-son" signature of X-linked recessive inheritance points the clinician straight at the X chromosome, so the right molecular panel is ordered the first time.

## Key facts

- Symbols: **square = male, circle = female, shaded = affected, double line = consanguinity, arrow = proband, diagonal = deceased**; generations are Roman numerals, individuals Arabic.
- **Three-question method:** does it skip? → recessive vs dominant; affected father → all daughters and no sons? → X-linked dominant; mostly males with no male-to-male transmission? → X-linked recessive.
- **Father-to-son transmission excludes X-linkage** — the father contributes a Y to sons.
- **Unaffected parents + affected child ⇒ recessive** (barring a new mutation); an affected *daughter* with an unaffected father **excludes** X-linked recessive.
- Autosomal dominant: every affected person has an affected parent; affected individuals are heterozygotes; each child of an affected parent has ½ risk; unaffected individuals do not transmit (with full penetrance).
- **Obligate carriers:** both parents of an *aa* child; the mother of an affected male and all daughters of an affected male (XLR).
- **Unaffected sibling of an affected child has a 2/3 chance of being a carrier** — (½)/(¾) conditional probability.
- **Consanguinity** (double line) → shared ancestry → same recessive allele by descent; first cousins *r* = 1/8, *F* = 1/16; look for AR patterns.
- Recurrence risks are **per pregnancy and independent** — previous children do not change the next risk.
- **Mitochondrial** traits pass from mothers to all children and never through fathers; **Y-linked** traits appear only in males, father to every son.
- **Reduced penetrance** can mimic skipping in a dominant trait — consider it only after recessive explanations are excluded.

## Practice questions

**1. In a pedigree, two unaffected parents have an affected son. What is the most likely mode of inheritance?**

A. Autosomal dominant
B. Autosomal recessive
C. Y-linked
D. X-linked dominant

**Answer: B**

Explanation: Two unaffected parents cannot both carry a dominant pathogenic allele (they would be affected), so the trait is skipping a generation — the definition of recessive. The son could be autosomal or X-linked recessive at this point; Y-linked (C) and X-linked dominant (D) both require an affected father, and dominance (A) is excluded by the unaffected parents.

---

**2. Two unaffected parents have an affected daughter. Which mode of inheritance is excluded?**

A. Autosomal recessive
B. X-linked recessive
C. Both A and B are possible
D. Neither — both remain possible

**Answer: B**

Explanation: An X-linked recessive female (*X^h X^h*) must receive an *X^h* from her father, which would make him affected — but he is unaffected, so X-linked recessive is impossible. Autosomal recessive fits perfectly: both unaffected parents are heterozygous carriers and each contributed *a*.

---

**3. A pedigree shows the trait in every generation, affecting males and females equally, with affected fathers passing it to both sons and daughters. The mode is**

A. X-linked recessive
B. Y-linked
C. Autosomal dominant
D. Mitochondrial

**Answer: C**

Explanation: Vertical transmission with affected × unaffected matings giving ~½ affected indicates dominance, and father-to-son transmission is only possible for a gene on an autosome (or the Y, but Y-linked traits never affect females and never pass through daughters). X-linked transmission (A) would give affected fathers only affected daughters; mitochondrial inheritance (D) transmits through mothers only.

---

**4. In a large pedigree, only males are affected and there is no male-to-male transmission anywhere. The pattern indicates**

A. Autosomal recessive
B. X-linked recessive
C. Y-linked
D. Sex-limited autosomal dominant

**Answer: B**

Explanation: Hemizygous males express X-linked recessive alleles while heterozygous females remain unaffected carriers — a male-skewed pedigree transmitted through females (criss-cross inheritance) and never father-to-son, since a father gives his Y to sons. Y-linked (C) would show father-to-son transmission in every generation, and autosomal recessive (A) affects both sexes roughly equally.

---

**5. A couple have a child with an autosomal recessive condition. Their unaffected daughter has what probability of being a carrier?**

A. ½
B. ¼
C. 2/3
D. 1

**Answer: C**

Explanation: Both parents are obligate carriers (*Aa* × *Aa*). Among *all* their children the carrier probability is ½, but conditioning on the daughter being unaffected removes the *aa* (¼) class from consideration, leaving ½ carrier out of ¾ unaffected = 2/3. This conditional figure — not ½ — is the one quoted in genetic counselling.

---

**6. A pedigree includes a double horizontal line between first cousins, and an affected child born to that couple. This strongly suggests**

A. A new dominant mutation
B. Autosomal recessive inheritance with homozygosity by descent
C. Y-linked inheritance
D. Mitochondrial inheritance

**Answer: B**

Explanation: The double line denotes consanguinity; relatives are more likely to carry the same ancestral allele, so two copies can meet in their child — the classic route to rare autosomal recessive disorders (first cousins: *F* = 1/16 for a specific ancestral allele). Dominant conditions do not need consanguinity, Y-linked traits never appear in females, and mitochondrial traits follow maternal lines irrespective of relatedness.

---

**7. A man with an X-linked recessive condition has children with an unaffected, non-carrier woman. What is expected among the offspring?**

A. All children affected
B. All daughters carriers, no sons affected
C. All sons affected, daughters unaffected
D. Half of each sex affected

**Answer: B**

Explanation: He passes his only X — carrying the variant — to every daughter, and each daughter also receives a normal X from her mother, so all daughters are unaffected carriers. Sons receive his Y, not his X, and get a normal X from their mother, so no son is affected — the variant resurfaces in the next generation through the carrier daughters.

---

**8. An unaffected couple have a child with a condition known to be autosomal dominant. The best explanation is**

A. Both parents are carriers for a recessive allele
B. A new germline mutation (or germline mosaicism in a parent)
C. The child is unaffected and misdiagnosed
D. The condition must actually be autosomal recessive

**Answer: B**

Explanation: A fully penetrant dominant allele requires an affected parent, so genuinely unaffected parents imply a *de novo* mutation or mosaicism confined to a parent's germ cells — how most achondroplasia arises. Recurrence risk is therefore low but not zero. Option A describes a recessive model already excluded by the stated mode.

---

**9. A pedigree shows a trait passed only from mothers to all of their children; no father ever transmits it. The mode is**

A. Autosomal recessive
B. X-linked dominant
C. Mitochondrial (maternal) inheritance
D. Y-linked

**Answer: C**

Explanation: Mitochondrial DNA is inherited almost exclusively from the egg, so an affected mother passes the variant to all her children while an affected father passes it to none — exactly the observed pattern, often with variable severity because of heteroplasmy. X-linked dominant (B) would let affected fathers transmit to all daughters; Y-linked (D) affects only males; autosomal transmission (A) does not follow the mother's line so strictly.

---

**10. Which single observation best excludes autosomal recessive inheritance in a pedigree where the trait appears in every generation?**

A. The trait appears in both sexes
B. Every affected individual has an affected parent and affected × unaffected matings give ~½ affected
C. The trait is rare
D. Consanguinity is present

**Answer: B**

Explanation: One affected parent per affected individual, every generation, and ~½ affected offspring of an affected × unaffected mating is the transmission signature of dominance; recessive traits require two copies and skip generations (pseudo-dominance from consanguinity can mimic the pattern, which is why D points *towards* recessive). Equal sex distribution (A) and rarity (C) fit either mode.
