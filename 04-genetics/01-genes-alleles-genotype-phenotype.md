# Genes, Alleles, Genotype and Phenotype

## Why it matters

Every chapter that follows in [04 — Genetics](../04-genetics/) — crosses, pedigrees, human disease patterns, population genetics — is written in a small, exact vocabulary. **Gene, locus, allele, genotype, phenotype** are not interchangeable words for "something genetic", and an exam that catches you using them loosely will catch you again in counselling questions where the precise term *is* the answer. A few minutes spent fixing the vocabulary now saves whole chapters of confusion later.

Three ideas do most of the work:

1. A **gene** is a position; an **allele** is a version of what sits at that position.
2. A **genotype** is what the DNA says; a **phenotype** is what follows from it — after the DNA has been read, translated into protein, and filtered through an environment.
3. **Dominance is not a property of an allele.** It is a description of what happens when *two particular alleles meet in one particular individual*.

The whole discipline can be sketched in one line:

```
DNA (genotype) ──read──▶ RNA ──built──▶ protein ──acts──▶ trait (phenotype)
     ▲                                          │
     └──── mutation creates a NEW allele ───────┘   (environment shapes the end result)
```

This chapter lays the vocabulary, the road from gene to trait, and the notation for crosses. The next chapter applies them to Mendel's laws.

## Gene, locus, allele, chromosome

```
CHROMOSOME = one double-stranded DNA molecule wound around histones

  ├─ LOCUS 1 ─── allele A   ─┐  two versions of the SAME gene,
  │              allele a   ─┘  occupying the SAME position
  ├─ LOCUS 2 ─── allele B / b
  ├─ LOCUS 3 ─── allele C / c
  └─ ...
```

| Term | Definition | What it is **not** |
| --- | --- | --- |
| **Chromosome** | One DNA molecule + associated proteins; the physical carrier of many genes | Not a gene — humans carry ~20,000 genes on 46 chromosomes |
| **Gene** | A defined **locus** (position) on a chromosome that specifies a functional product, usually a polypeptide or functional RNA | Not a "piece of DNA that codes for a trait" — one gene usually feeds into many traits and one trait into many genes |
| **Locus** (pl. loci) | The physical address of a gene on a chromosome | Not the variant itself — it is where the variant sits |
| **Allele** | One of the alternative DNA sequences found at a locus | Not a chromosome, and not a synonym for "gene" — *every* allele is a form of some gene |
| **Genotype** | The combination of alleles an individual carries at a locus (or across loci) | Not visible; may be known by sequencing long before any phenotype appears |
| **Phenotype** | The observable expression of a genotype — morphological, biochemical, physiological, or behavioural | Not identical to "appearance": a biochemical phenotype (blood group, enzyme activity) counts |

**The gene–allele distinction is the single most examined point in this chapter.** "Tall" is not an allele and not a gene — it is a phenotype. The gene is the locus that specifies a growth-related protein; *T* and *t* are two alleles of it; TT, Tt, and tt are three genotypes; and tall versus dwarf are the two phenotypic classes those genotypes produce.

One gene does not map neatly onto one trait. A single gene product often sits in a pathway with dozens of others (**pleiotropy** when one gene affects several traits, as in sickle cell anaemia), and most visible traits are built by several genes at once (**polygenic** inheritance — see [03 — Non-Mendelian patterns](03-non-mendelian-patterns.md)). The clean one-gene version is a teaching model, and it is worth knowing *why* it is a model.

## From genotype to phenotype

The genotype becomes the phenotype through a chain of causal steps — and each step is a place where the chain can be interrupted, modified, or rescued.

```
ALLELE (DNA sequence at a locus)
   │   transcription
   ▼
pre-mRNA ──splicing──▶ mature mRNA
   │   translation at the ribosome
   ▼
POLYPEPTIDE (amino acid sequence set by codons)
   │   folding, assembly, post-translational modification
   ▼
FUNCTIONAL PROTEIN (enzyme, channel, receptor, structural protein...)
   │   amount + activity
   ▼
BIOCHEMICAL PATHWAY OUTPUT
   │
   ▼
PHENOTYPE (observable trait)
```

A concrete version, using albinism:

```
non-functional tyrosinase allele
        │
        ▼
no active enzyme converting tyrosine → melanin precursors
        │
        ▼
no melanin deposited in skin, hair, and iris
        │
        ▼
pale pigmentation (the phenotype)
```

Everything needed to understand the chemistry of the middle boxes is in [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) (codons, the genetic code) and [03 — Protein synthesis](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md) (reading that code into a polypeptide); folding and structure–function belong to [03 — Proteins](../01-biochemistry/03-proteins.md).

Four consequences of the chain:

1. **An allele is a difference in sequence, so it produces a difference in protein** — or in the *amount* of protein, or in *when* and *where* it is made. Not every sequence difference changes the protein (silent variants, synonymous codons).
2. **Phenotype = genotype + environment.** Nutrition modifies height, sun exposure modifies pigmentation, and a working gene is useless without its substrate. The equation is multiplicative, not additive: a favourable genotype expressed in a hostile environment can still give a poor phenotype.
3. **Dominance is decided at the protein step** — see the next section.
4. **The chain runs one way causally**, but it runs *backwards* diagnostically: clinicians observe phenotype, then infer genotype. Pedigree analysis ([04 — Pedigree analysis](04-pedigree-analysis.md)) is entirely this reverse inference.

## Dominance is a relationship, not a property

For a locus with two alleles, *A* and *a*, the definitions are strictly about the **heterozygote**:

```
AA      → phenotype 1
Aa      → phenotype 1     ← THIS comparison defines dominance
aa      → phenotype 2

A is DOMINANT to a   because Aa looks like AA
a is RECESSIVE to A  because a is not expressed when A is present
```

- **Dominant** = the heterozygote's phenotype matches the *A* homozygote.
- **Recessive** = the allele's effect is masked in the heterozygote and appears only in *aa*.

What dominance does **not** mean:

| Claim | Why it is wrong |
| --- | --- |
| "Dominant = more common" | Many dominant disease alleles are rare (achondroplasia ≈ 1 in 15,000 births); many recessive alleles are common (blood group *i*) |
| "Dominant = beneficial / normal" | Huntington's disease is dominant; many recessive alleles are entirely harmless |
| "Dominant = stronger gene" | The allele produces a product that does the job alone; *strength* is not a property being compared |
| "Dominance tells you the molecular mechanism" | Dominance says nothing about *how* the protein works — only about the heterozygote's phenotype |

**Why most loss-of-function alleles are recessive — haplosufficiency:**

```
one functional copy → ~50% of normal protein → enough to run the pathway at full speed
                     → phenotype normal → the mutant allele is RECESSIVE
```

Enzymes are usually made in excess: halving the amount changes nothing observable. So a **null allele** (no product) is typically recessive. Dominance arises when one copy is *not* enough (**haploinsufficiency**, as in many transcription-factor disorders), when the mutant product actively interferes with the normal one (**dominant negative**), or when the allele is a **gain of function** (a receptor that fires without its ligand). Same genetics, completely different molecular stories — which is why dominance can never be read off the allele alone.

## Zygosity: homozygous, heterozygous, hemizygous

| Term | Genotype | Meaning |
| --- | --- | --- |
| **Homozygous** | *AA* or *aa* | Both copies at the locus are the same allele ("homozygous **dominant**" / "homozygous **recessive**") |
| **Heterozygous** | *Aa* | The two copies are different alleles; usually phenotypically normal if *A* is dominant |
| **Hemizygous** | *XᴬY* | Only **one** copy of the locus exists — the standard condition for X-linked genes in genetic males, and for most Y-linked genes |
| **Compound heterozygote** | *a₁a₂* | Two *different* pathogenic alleles at the same locus — genetically not homozygous, but functionally equivalent to *aa* |

**Compound heterozygosity matters clinically.** Roughly two-thirds of cystic fibrosis patients carry two *different* CFTR mutations rather than the same one twice; sequencing one allele is not enough, which is why panels test both copies.

**Hemizygosity explains the whole pattern of X-linked inheritance** in [05 — Human inheritance patterns](05-human-inheritance-patterns.md): a male has no second X allele to mask a recessive variant, so every X-linked recessive allele he carries is expressed. That single fact — one copy, no backup — generates the "more males affected" signature used in pedigree analysis.

## True-breeding (pure lines)

**True-breeding** means an individual is **homozygous for the trait under discussion**, so that crossing it with others of the same phenotype, or self-fertilising it, gives only that phenotype.

```
true-breeding tall × true-breeding tall  →  all tall   (no segregation)
heterozygous tall × heterozygous tall    →  3 tall : 1 dwarf   (segregation appears)
```

Two cautions:

- True-breeding is **relative to one trait**. A pea plant can be true-breeding for tallness and simultaneously heterozygous for flower colour.
- Mendel's P generation had to be true-breeding; otherwise the F1 would not have been uniform, and the ratios that built genetics would never have appeared.

Purity is enforced in practice by repeated selfing (plants), sib-mating, or selecting matings that never produce a variant offspring.

## Mutation: the only source of new alleles

All existing alleles descend from earlier alleles. The appearance of a genuinely **new** allele requires a **mutation — a heritable change in DNA sequence**, most importantly in the germ line so it can be passed on.

```
germ-line mutation in one chromosome
        │
        ▼
new allele at that locus (created at random, not in response to need)
        │  meiosis: segregation and independent assortment
        ▼
allele transmitted to some gametes → to some offspring
        │
        ▼
new genotype → (possibly) new phenotype → raw material for selection
```

| Mutation type | Effect on the allele | Example consequence |
| --- | --- | --- |
| **Substitution** | Missense (one amino acid changed), nonsense (stop codon), or silent | Sickle cell: a single GAG→GTG change, Glu→Val |
| **Insertion / deletion** not a multiple of 3 | **Frameshift** — every codon downstream altered | Many CFTR mutations |
| **Trinucleotide repeat expansion** | Protein with an expanded polyglutamine tract | Huntington's disease (CAG repeats) |
| **Duplication / deletion of a whole gene** | Gene dosage change | Copy-number variants |
| **Aneuploidy** (whole chromosome) | Not allelic — a *chromosomal* gain/loss | Down syndrome; see [12 — Meiosis](../03-cellular-processes/12-meiosis.md) |

Two properties of mutation are worth internalising: it is **rare**, and it is **not directed** — organisms do not mutate *because* they need an allele. That makes mutation the ultimate source of genetic variation and selection its filter, a pairing developed in [06 — Evolution](../06-evolution/). The mechanisms of DNA damage and repair, and how exactly a sequence change becomes a protein change, belong to [05 — Molecular Biology](../05-molecular-biology/).

## Cross notation: P, F1, F2, and the test cross

Mendelian crosses are written as a compact shorthand, and reading it fluently is half of any genetics exam.

```
P    parental generation:   ♀ TT (tall, true-breeding)  ×  ♂ tt (dwarf, true-breeding)
                                  │
                                  ▼
F1   first filial:                Tt   — 100% tall; genotype is uniform, phenotype hides t
                                  │  allow self-fertilisation / intercross
                                  ▼
F2   second filial:   3 tall : 1 dwarf          ← PHENOTYPE ratio
                      1 TT : 2 Tt : 1 tt        ← GENOTYPE ratio
```

- **P** = parents (chosen true-breeding); **F1** = their offspring; **F2** = F1 × F1. (An F3 can be produced the same way.)
- The **×** means a controlled cross; the sex symbols show which parent contributed which gamete.
- Ratios are **probabilities**, not promises — a single F2 family may deviate; the ratios describe large samples.

**Test cross — interrogating an unknown genotype.** An individual showing the dominant phenotype is either *AA* or *Aa*, and no amount of looking at it will tell you which. Cross it to a **homozygous recessive tester**:

```
unknown (A?) × aa

if A? = AA   →  all offspring Aa  →  every offspring dominant  →  parent was homozygous
if A? = Aa   →  ½ Aa : ½ aa      →  ~half the offspring show the recessive phenotype
                                     →  parent was heterozygous
```

The tester is transparent: it contributes only recessive alleles, so **each offspring's phenotype is a direct report of the unknown parent's gamete**. Recessive offspring could only have come from an *a* gamete, so the unknown must carry *a*.

A **back cross** is any cross to one of the original parental genotypes; a test cross is the special back cross to a homozygous recessive. The terms are close, and exams use them precisely.

## Medical relevance

**Genotype before phenotype.** Modern diagnosis reads the DNA directly: a person at risk for Huntington's disease can be told they carry the pathogenic HTT expansion decades before any symptom — a genotype with no current phenotype at all. Predictive and presymptomatic testing raise consent and psychological issues that follow directly from this separation.

**Recessive carriers are healthy because of haplosufficiency, not luck.** About 1 in 25 people of Northern European descent carries a cystic fibrosis allele; each carrier has one working CFTR copy, makes enough functional chloride channel, and is clinically normal. The allele is hidden in the phenotype and revealed only in an *aa* offspring — which is exactly why recessive conditions "skip generations", and why carrier screening exists ([05 — Human inheritance patterns](05-human-inheritance-patterns.md)).

**Dominant disease alleles need only one copy** — one mutant receptor or enzyme is enough to cause the disease because the mechanism is gain of function or haploinsufficiency. Achondroplasia (FGFR3) is the standard example, and its homozygous form is lethal: dominance in the heterozygote, lethality in the homozygote, two facts about the same allele.

**Phenocopy — the assumption that can break.** Pedigree logic assumes *phenotype reflects genotype*. An environmental event that mimics a genetic phenotype is a **phenocopy** — a drug-induced birth defect resembling an inherited syndrome, or nutritional stunting that looks like a genetic short stature. Phenocopies are rare enough that the logic still works, but recognising them is the difference between a correct and an overconfident genetic conclusion.

**Molecular phenotypes count.** Blood groups, enzyme levels, and drug-metaboliser status are phenotypes you cannot see but can measure — and they are often the phenotypes medicine cares about.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| Gene and allele used interchangeably | The gene is the **locus**; alleles are the **variants** at it. *T* is an allele of the tall/dwarf gene, not a gene itself. |
| "Dominant" means common, normal, or beneficial | It means only: **the heterozygote shows this phenotype**. Huntington's is dominant and catastrophic; blood group *i* is recessive and harmless. |
| "Recessive" means harmful or rare | Recessive describes masking in the heterozygote. Most recessive alleles are neutral; some (HbS heterozygotes) are advantageous. |
| Phenotype = what something looks like | It includes biochemical, physiological, and behavioural traits — blood group A is a phenotype. |
| Carriers "don't have the gene" | They have the allele; one functional copy keeps the phenotype normal. Genotype ≠ phenotype. |
| Homozygous means "has two genes" | It means two copies of the **same allele at one locus**. |
| New alleles appear when they are needed | Mutation is undirected and rare; selection acts on variation that arises regardless of need. |

## Key facts

- **Gene = locus; allele = variant at that locus; genotype = alleles carried; phenotype = observable expression.** These four words are never interchangeable.
- A chromosome carries many genes; one trait usually involves many genes, and one gene often affects several traits (pleiotropy).
- The chain genotype → phenotype runs **DNA → mRNA → polypeptide → protein function → pathway output → trait**, with the environment acting at every step after DNA.
- **Dominance is a relationship between two alleles in a heterozygote**, not a property of an allele: *A* is dominant if *Aa* phenocopies *AA*.
- Most loss-of-function alleles are recess because **one functional copy produces enough protein (haplosufficiency)**; dominant alleles are typically haploinsufficient, dominant-negative, or gain-of-function.
- **Homozygous** = same allele twice; **heterozygous** = different alleles; **hemizygous** = one copy only (X-linked genes in males); **compound heterozygote** = two different pathogenic alleles at one locus.
- **True-breeding = homozygous for the trait in question**; Mendel's P generation had to be pure for the F1 to be uniform.
- **Mutation is the only source of new alleles**; mechanisms range from single-base substitution to frameshift to repeat expansion; chromosomal change (aneuploidy) is a separate category.
- Cross notation: **P → F1 → F2**; the F2 of a monohybrid cross gives a 3:1 phenotype ratio and a 1:2:1 genotype ratio.
- A **test cross** is a cross to a homozygous recessive: any recessive offspring proves the unknown dominant-phenotype parent was heterozygous.
- A **back cross** is a cross to a parent genotype; a test cross is the specific back cross to *aa*.
- A **phenocopy** is an environmental mimic of a genetic phenotype — the exception that pedigree reasoning must allow for.

## Practice questions

**1. Which statement correctly distinguishes a gene from an allele?**

A. A gene is the dominant version; a recessive allele is not a gene
B. A gene is a locus on a chromosome; an allele is one of the alternative sequences at that locus
C. An allele is a chromosome; a gene is a segment of DNA coding for one trait
D. Genes and alleles are two words for the same unit of inheritance

**Answer: B**

Explanation: The gene names the *position* — a defined locus — while alleles are the alternative DNA sequences found there (conventionally *A* and *a*). Every allele is a form of some gene, so D is wrong; alleles are not chromosomes (C), and both dominant and recessive variants are alleles of the same gene, so A misuses the terms. The distinction matters because genotype questions ask about alleles at loci, not about "genes being dominant".

---

**2. A person is heterozygous for a recessive allele yet shows no sign of the condition. Which concept best explains this?**

A. The recessive allele is not present in the phenotype under any circumstance
B. One functional copy produces enough normal protein for the full wild-type phenotype (haplosufficiency)
C. The environment suppresses the allele permanently
D. Recessive alleles are never transcribed

**Answer: B**

Explanation: With a typical enzyme made in excess, 50% of normal protein activity is sufficient to run the pathway at full speed, so the phenotype is normal and the allele is described as recessive. The allele is present and transcribed (A and D are false) — it is simply not rate-limiting. Environmental suppression (C) would make the phenotype contingent on circumstance, not a fixed property of the genotype.

---

**3. "Dominant" is properly defined as which of the following?**

A. An allele that is more frequent in the population than the recessive allele
B. An allele that codes for a superior or normal protein
C. An allele whose phenotype is expressed in the heterozygote, which therefore resembles the corresponding homozygote
D. Any allele causing disease

**Answer: C**

Explanation: Dominance is strictly a statement about the heterozygote: *A* is dominant to *a* if *Aa* looks like *AA*. Frequency (A), molecular quality (B), and pathogenicity (D) are all independent of dominance — rare dominant disease alleles (Huntington's) and common harmless recessive alleles (blood group *i*) both exist.

---

**4. Which individual is hemizygous for an X-linked gene?**

A. A genetic female, XX
B. A genetic male, XY
C. A homozygous recessive female
D. A person with Turner syndrome (45,X) for an autosomal gene

**Answer: B**

Explanation: Hemizygous means having only one copy of a locus. A genetic male has a single X, so every X-linked gene — recessive or not — is present in one copy only, and there is no second allele to mask its effect. Females have two X copies (A, C), and autosomal genes are present in two copies in 45,X individuals (D).

---

**5. Two plants with the dominant phenotype are crossed and produce offspring of both phenotypes. What does this demonstrate?**

A. The parents were true-breeding
B. At least one parent carried the recessive allele
C. The recessive allele arose by mutation in the F1
D. Dominance has been reversed

**Answer: B**

Explanation: A recessive phenotype (*aa*) requires one *a* allele from each parent, so neither parent could have been true-breeding (*AA*); both were *Aa*, and segregation in their gametes produced the *aa* offspring. True-breeding parents would give only the dominant phenotype (A), alleles are not created on demand (C), and nothing about dominance has changed (D).

---

**6. In a test cross, an individual of unknown genotype but dominant phenotype is crossed with *aa*. Half the offspring show the recessive phenotype. The unknown parent is**

A. *AA*
B. *Aa*
C. *aa*
D. Impossible to determine

**Answer: B**

Explanation: The tester contributes only *a*, so each offspring's phenotype reports the unknown parent's gamete. Recessive (*aa*) offspring must have received an *a* from the unknown parent — proof it carries the recessive allele, so it is *Aa*. Had it been *AA*, every offspring would be *Aa* and dominant; *aa* is excluded by the dominant phenotype of the parent itself.

---

**7. Which is the only ultimate source of new alleles?**

A. Independent assortment
B. Crossing over
C. Mutation
D. Dominance

**Answer: C**

Explanation: Independent assortment and crossing over are powerful — but they only *recombine* alleles that already exist. Dominance is a relationship between alleles, not a source of anything. Only mutation alters DNA sequence to create a genuinely new allele, which is why mutation supplies raw material and meiosis shuffles it.

---

**8. Which sequence correctly traces a genotype to a phenotype?**

A. Phenotype → protein → mRNA → DNA
B. DNA → mRNA → polypeptide → protein function → trait
C. DNA → protein → chromosome → allele → trait
D. Ribosome → DNA → nucleus → phenotype

**Answer: B**

Explanation: The causal chain runs from the allele's DNA sequence through transcription to mRNA, translation to a polypeptide, folding into a functional protein, its effect on a biochemical pathway, and finally the observable trait. Option A reverses causality; C mixes levels (chromosomes carry genes, they are not steps after proteins); D has the ribosome acting on DNA and omits transcription entirely.

---

**9. In the F2 generation of a monohybrid cross between two true-breeding parents, what is the genotype ratio?**

A. 3:1
B. 1:2:1
C. 9:3:3:1
D. 1:1

**Answer: B**

Explanation: *TT* × *tt* gives an all-*Tt* F1; crossing F1 × F1 yields 1 *TT* : 2 *Tt* : 1 *tt*, the 1:2:1 genotype ratio. Because *T* is dominant, the two genotypes sharing the dominant phenotype merge phenotypically to give the 3:1 ratio (A) — the classic trap of quoting a phenotype ratio when a genotype ratio is asked for. D is the test-cross ratio; C is the dihybrid phenotype ratio.

---

**10. Which of the following is NOT implied by an allele being described as recessive?**

A. The heterozygote has the other allele's phenotype
B. The allele is rare in the population
C. Two copies of it are needed for its phenotype to appear
D. It may be entirely harmless

**Answer: B**

Explanation: Recessive means only that the allele's effect is masked in the heterozygote and expressed in the homozygote (A and C) — and recessiveness says nothing about harm, since many recessive alleles are neutral or even advantageous (D). Rarity is a population-frequency property completely independent of dominance: common recessive alleles such as blood group *i* and rare dominant alleles such as the Huntington's expansion both exist.
