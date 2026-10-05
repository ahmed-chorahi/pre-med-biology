# Meiosis

## Why it matters

Mitosis makes two identical daughters; **meiosis makes four genetically different cells with half the chromosome number**. It is the division that makes sexual reproduction possible — and the two problems it solves, *halving the genome* and *creating variation*, both require mechanisms mitosis deliberately avoids.

Every genetic cross, every pedigree, every chromosome disorder in [04 — Genetics](../04-genetics/) assumes this chapter. Learn meiosis as a solution to two problems and the details arrange themselves.

## The two problems

```
PROBLEM 1: EACH PARENT IS DIPLOID (2n)
           fusion of two gametes would give 4n → 4n → 8n...
           SOLUTION: reduce to n in the gamete

PROBLEM 2: IF ALL OFFSPRING WERE CLONES OF PARENTS
           no variation → no raw material for natural selection (06 — Evolution)
           SOLUTION: shuffle genes every generation
```

**Meiosis = one replication followed by TWO divisions:**

```
DNA replicated ONCE (S phase, before meiosis begins)

        MEIOSIS I   →  homologues separate  →  2 cells, each with n chromosomes (each still 2 chromatids)
        MEIOSIS II  →  sister chromatids separate  →  4 cells, n, single chromatids

        2n ──────────────────────────────────────────────▶ n
        4n DNA content → 2n → 1n (halving happens in MEIOSIS I)
```

**The reduction division is meiosis I.** Meiosis II is essentially a mitosis in cells that are already haploid.

## Meiosis I — the reduction

### Prophase I: where nearly all the important events happen

Prophase I is long, complex, and divided into sub-stages (**leptotene, zygotene, pachytene, diplotene, diakinesis**), because it performs the three things that make meiosis meiosis:

**1. Synapsis — homologues find each other**

```
HOMOLOGOUS PAIR (one from mother, one from father)

   ═══╪═══╤═══╪═══   homologue 1
   ═══╪═══╤═══╪═══   homologue 2
      └─┬─┘
   SYNAPTONEMAL COMPLEX holds them together
      pair = BIVALENT = TETRAD (4 chromatids)
```

- **Synaptonemal complex** zips the pair into a **bivalent** (tetrad).
- Only **homologues** pair — sisters do not. This is the fundamental difference from mitosis, where homologues ignore each other.
- Errors here → non-disjunction → aneuploidy (below).

**2. Crossing over — physical exchange**

At **pachytene**, the enzyme **Spo11** makes deliberate double-strand breaks; the repair uses the **homologue** as a template, and in doing so **exchanges segments between non-sister chromatids**.

```
before:     A B C D | E F G H     (maternal)
            a b c d | e f g h     (paternal)

after crossover:

            A B C D | e f G H
            a b c d | E F g h
```

**The consequence:** each chromatid is now a **recombinant chromosome** — a mosaic of the two parental homologues. **New allele combinations that never existed in either parent** are created in a single event.

**3. Independent assortment — the combinatorics**

By metaphase I, bivalents line up at the plate with **each homologue facing a pole at random**, independent of every other pair:

```
human:  23 pairs → 2²³ = 8,388,608 possible alignments
```

**One person produces over 8 million possible gamete chromosome combinations** — *before* counting crossing over, which adds effectively unlimited further variation by reshuffling within chromosomes.

**Segregation** (Mendel's first law) is visible here: the two alleles of a pair separate because the homologues carrying them separate.

### Metaphase I → Anaphase I → Telophase I

| Stage | Event |
| --- | --- |
| **Metaphase I** | **Bivalents** align at the plate (not individual chromosomes — that's metaphase II and mitosis) |
| **Anaphase I** | **Homologues separate**; sisters remain joined at centromeres (cohesin along arms is protected — only **clinging** at centromeres holds sisters together now) |
| **Telophase I / cytokinesis** | Two cells, each **haploid in chromosome number** but with **two chromatids per chromosome** |

**The critical detail:** in anaphase I, **sister chromatids do NOT separate**. Only homologues part. That single fact distinguishes meiosis I from mitosis and from meiosis II, and it is the most common point of confusion.

## Meiosis II — division without replication

```
no S phase between I and II

METAPHASE II     chromosomes (2 chromatids each) align at the plate
ANAPHASE II      SISTER CHROMATIDS SEPARATE  ← like mitosis
TELOPHASE II     four nuclei → cytokinesis → FOUR HAPLOID CELLS
```

Meiosis II is structurally a mitosis — same cohesin cleavage, same kinetochore logic, same checkpoint — performed in cells that are already n. **No DNA replication intervenes**, so the chromosome number stays halved.

## The products

| | Cells | Ploidy | Chromatids per chromosome |
| --- | --- | --- | --- |
| Start (germ cell) | 1 | **2n** | 2 (after S phase) |
| After meiosis I | 2 | **n** | 2 |
| After meiosis II | **4** | **n** | **1** |

**In males:** one primary spermatocyte → **4 functional sperm** (spermatogenesis — continuous, prolific from puberty).

**In females:** one primary oocyte → **1 ovum + 3 polar bodies** (oogenesis — cytoplasm is conserved for the one cell that will face early embryonic demands; the polar bodies degenerate).

```
SPERMATOGENESIS          OOCYTE
1 primary → 4 sperm      1 primary → 1 ovum + 3 polar bodies
   (equal cytokinesis)      (unequal cytokinesis — big cell keeps the cytoplasm)
```

**Unequal division is not an error — it is the design.** The egg needs the ribosomes, mitochondria, and stored mRNA for the first divisions before the embryo can make its own.

## How the three sources of variation combine

| Source | When | Effect |
| --- | --- | --- |
| **Independent assortment** | Metaphase I / anaphase I | Which maternal/paternal homologue goes to which pole — 2²³ combinations in humans |
| **Crossing over** | Prophase I (pachytene) | Recombinant chromatids — shuffles alleles *within* chromosomes |
| **Random fertilisation** | Fusion with any one of millions of sperm | Multiplies the combinations again: (8.4 × 10⁶)² possible zygote genotypes from independent assortment alone |

**Order of magnitude:** 8.4 million gamete types each, ~70 trillion possible zygote combinations from assortment alone — and crossing over makes every one of those figures an underestimate. **Sexual reproduction is a variation machine**, and [06 — Evolution](../06-evolution/) depends on this output as its raw material.

## Nondisjunction: when separation fails

**Nondisjunction** = failure of chromosomes/homologues to separate → one gamete with **n+1**, another with **n−1**.

```
NORMAL:     n   +   n   = 2n

NONDISJUNCTION:
   gamete n+1 + gamete n   = 2n+1   TRISOMY
   gamete n-1 + gamete n   = 2n-1   MONOSOMY
   gamete n+1 + n+1        = 2n+2   (usually inviable)
   gamete n-1 + n-1        = 2n-2   (almost always inviable)
```

**Meiosis I nondisjunction** = homologues fail to separate → *both* homologues go to one pole → gametes have both parental copies (duplicated across homologues).

**Meiosis II nondisjunction** = sisters fail to separate → one gamete gets two copies of the *same* chromosome.

| Condition | Karyotype | Cause | Features |
| --- | --- | --- | --- |
| **Down syndrome** | **47,XX/XY,+21** | Usually meiosis I nondisjunction in the egg; risk rises steeply with maternal age | Intellectual disability, characteristic facies, cardiac defects, **translocation form is inheritable** |
| **Edwards syndrome** | 47,+18 | Nondisjunction | Severe; most die in first year |
| **Patau syndrome** | 47,+13 | Nondisjunction | Severe; multi-organ involvement |
| **Turner syndrome** | **45,X** (monosomy X) | Often post-zygotic or meiotic loss | Female, short stature, gonadal dysgenesis, **only monosomy commonly compatible with life** |
| **Klinefelter syndrome** | 47,XXY | Maternal or paternal nondisjunction | Male, tall, reduced fertility, gynaecomastia |
| **XYY** | 47,XYY | Paternal meiosis II error | Often normal phenotype, tall |

**Why is autosomal monosomy lethal but 45,X survivable?** Dosage compensation: a single X can be partly upregulated (the X-inactivation machinery exists), whereas losing an autosome means losing ~1% of the genome with no compensation — implantation fails. **Triploidy (69) and full trisomies beyond a few chromosomes are almost universally lethal**, which is why most chromosomal abnormalities end as **early miscarriage** — the majority of conceptions with aneuploidy never come to clinical attention.

**Maternal age effect (Down syndrome):** oocytes begin meiosis I before birth and **arrest in prophase I for decades**; the cohesin holding homologues together degrades over time, so separation becomes error-prone with age. **The arrest is the mechanism behind the epidemiology** — a beautiful example of cell biology explaining a population statistic.

**Translocation Down syndrome** — a Robertsonian translocation (e.g. chromosome 21 fused to 14) means a person can have "Down features" with 46 chromosomes, and the condition **is inherited** — the exception to nondisjunction's sporadic pattern, and a standard genetics pedigree question.

## Medical and practical relevance

**Prenatal screening** is meiosis's clinical front line: ultrasound markers plus maternal serum (and now cell-free fetal DNA) screen for trisomies; karyotyping or FISH confirms. **The test exists because nondisjunction is common enough to be worth screening** — roughly 1 in 700 live births has Down syndrome.

**Infertility workups** routinely examine meiotic behaviour: abnormal chromosome segregation in sperm (aneuploidy screening by FISH), failure of synapsis, and meiotic arrest. **Meiotic failure = no gametes = infertility**, and its diagnosis depends on knowing exactly what normal prophase I requires.

**Cancer again:** meiotic recombination enzymes (Spo11 and the repair machinery) are hijacked in some tumours to generate **structural variation** — the same shuffling machinery, in the wrong cell at the wrong time, driving tumour evolution.

**Why the chromosome number must match:** every downstream assumption — dosage, pairing, segregation — rests on gametes being n. Aneuploidy's consequences (this chapter) and Mendel's laws (next section) are two faces of the same halving requirement.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Meiosis I and II are similar" | I separates **homologues** (reduction); II separates **sisters** (like mitosis). |
| "Crossing over happens in metaphase" | It happens in **prophase I (pachytene)** — before alignment. |
| "DNA replicates between meiosis I and II" | **No.** Replication happens once, before meiosis I. |
| "Four gametes are always made" | In oogenesis, **one** ovum and **three polar bodies** result. |
| "Nondisjunction only happens in meiosis II" | Either division can fail; the resulting gametes differ in *which* copies are duplicated. |
| "Down syndrome is always inherited" | Most cases are sporadic nondisjunction; only the **translocation form** is inheritable. |

## Key facts

- Meiosis = **one replication, two divisions** → **4 haploid cells**; reduction occurs in **meiosis I**.
- **Prophase I** does the essential work: **synapsis** (bivalent/tetrad via synaptonemal complex), **crossing over** (Spo11 breaks, exchange between non-sister chromatids → recombinant chromosomes), and preparation for **independent assortment**.
- **Anaphase I separates homologues; sisters stay joined. Anaphase II separates sisters** — no replication between divisions.
- **Independent assortment: 2²³ ≈ 8.4 million** possible gametes in humans (before crossing over).
- Spermatogenesis → **4 sperm**; oogenesis → **1 ovum + 3 polar bodies** (unequal cytokinesis preserves cytoplasm).
- **Nondisjunction → n+1 or n−1 gametes → trisomy (2n+1) or monosomy (2n−1)**; Down (47,+21), Edwards (+18), Patau (+13), Turner (45,X), Klinefelter (47,XXY).
- **Maternal age effect** = decades of prophase I arrest → cohesin degradation → nondisjunction risk rises.
- **Translocation Down syndrome** is the inheritable form; most other aneuploidies are sporadic and many are lethal early.
- Variation = independent assortment + crossing over + random fertilisation — the raw material for evolution.

## Practice questions

**1. During which stage do homologous chromosomes pair and exchange segments?**

A. Prophase I
B. Metaphase II
C. Anaphase of mitosis
D. Prophase II

**Answer: A**

Explanation: Synapsis and crossing over occur in prophase I (pachytene specifically), forming bivalents held by the synaptonemal complex where Spo11-initiated breaks are repaired using the homologue as template. No pairing or exchange happens in meiosis II or mitosis — homologues behave independently there.

---

**2. What separates during anaphase I of meiosis?**

A. Sister chromatids
B. Homologous chromosomes
C. Sister chromatids of one chromosome only
D. Centrioles

**Answer: B**

Explanation: Anaphase I pulls homologues to opposite poles while sister chromatids remain joined at their centromeres — this is the reductional step, halving chromosome number. Sister chromatids separate later, in anaphase II. That distinction between the two anaphases is the core of meiosis.

---

**3. How many cells result from meiosis in a male, and what are they?**

A. 2 diploid cells
B. 4 haploid cells — sperm
C. 1 haploid cell and 2 polar bodies
D. 4 diploid cells

**Answer: B**

Explanation: One primary spermatocyte completes both divisions to yield four functional haploid sperm — cytokinesis is equal. Option C describes oogenesis, where unequal division conserves cytoplasm for the single ovum.

---

**4. Which is a direct source of genetic variation produced by meiosis?**

A. DNA replication during meiosis II
B. Independent assortment of homologues at metaphase I and crossing over in prophase I
C. Mitotic recombination
D. Uniform distribution of parental chromosomes

**Answer: B**

Explanation: Homologues align independently (2²³ combinations in humans) and crossing over creates recombinant chromatids carrying new allele combinations — both occur only in meiosis. There is no replication between the divisions (A), and mitosis produces identical rather than varied products (C).

---

**5. Trisomy 21 most commonly results from**

A. A translocation between chromosomes in every case
B. Nondisjunction during maternal meiosis I
C. Failure of DNA replication
D. Nondisjunction during mitosis after fertilisation

**Answer: B**

Explanation: The majority of Down syndrome cases are sporadic meiotic nondisjunction, most often in oogenesis (meiosis I), with risk increasing with maternal age because oocytes are arrested in prophase I for decades. Only the translocation form (~3-4%) is inherited; post-zygotic mitotic errors cause mosaic forms, not the typical presentation.

---

**6. Why does maternal age increase the risk of Down syndrome?**

A. Older eggs have more chromosomes to begin with
B. Oocytes arrest in prophase I for years and cohesin deteriorates, making homologue separation error-prone
C. Sperm quality determines the chromosome number
D. Hormonal changes force nondisjunction

**Answer: B**

Explanation: The long arrest means the machinery holding homologues together ages — cohesin loss and spindle problems accumulate, so nondisjunction becomes more likely. The egg's starting chromosome number is normal (A); paternal errors exist but the strong age effect is maternal; hormones are not the mechanism.

---

**7. Which statement about crossing over is correct?**

A. It occurs between sister chromatids and increases with mitosis
B. It occurs between non-sister chromatids of a homologous pair in prophase I, producing recombinant chromosomes
C. It doubles the chromosome number
D. It occurs in metaphase I after alignment

**Answer: B**

Explanation: Exchange happens between *non-sister* chromatids of synapsed homologues — one maternal, one paternal — creating chromatids with new allele combinations. It does not change chromosome number (C), does not occur between identical sisters as its meaningful event (A), and is completed before metaphase alignment (D).

---

**8. Turner syndrome (45,X) is characterised by**

A. An extra X in males
B. A single X chromosome in a phenotypic female, often with short stature and gonadal dysgenesis
C. Three copies of chromosome 21
D. An extra Y chromosome

**Answer: B**

Explanation: 45,X monosomy — the only monosomy commonly compatible with life, thanks to partial X-upregulation capacity. Clinical features include short stature, webbed neck, and streak gonads with infertility. A describes Klinefelter (47,XXY), C describes Down syndrome, D describes 47,XYY.

---

**9. Why can oogenesis produce only one functional gamete per meiosis?**

A. The oocyte fails to complete meiosis II
B. Cytokinesis is unequal, conserving cytoplasm, organelles, and stored mRNA in the single ovum while the polar bodies degenerate
C. Only one chromosome is present
D. Polar bodies are functional sperm-like cells

**Answer: B**

Explanation: Unequal cytokinesis packages the limited maternal resources — mitochondria, ribosomes, nutrients, maternal transcripts — into the one cell that must support the earliest embryonic divisions before the genome activates. The polar bodies receive minimal cytoplasm and degenerate. The oocyte completes both divisions (A wrong); chromosome number is not the constraint.

---

**10. Which combination best explains why sexual reproduction generates so much variation?**

A. Mitosis and DNA repair
B. Independent assortment, crossing over, and random fusion of gametes
C. Binary fission and transformation
D. DNA replication alone

**Answer: B**

Explanation: Independent assortment gives ~8.4 million gamete types per person, crossing over reshuffles alleles within chromosomes so that number is a vast underestimate, and the random fusion of two such gamete pools multiplies the possibilities again. Mitosis makes copies, binary fission and transformation are prokaryotic, and replication copies rather than shuffles.
