# Human Inheritance Patterns

## Why it matters

Human genetics is where the previous four chapters stop being abstract. Mendel's ratios become recurrence risks, dominance decides whether a condition appears in every generation, hemizygosity decides who gets sick, and a population's allele frequencies decide who needs screening. Almost every question a clinician answers about inheritance — *"could my child have it?"*, *"am I a carrier?"*, *"why did it skip my brother?"* — is one of the patterns in this chapter recognised and quantified.

The patterns divide along two axes: **where the gene sits** (autosome, X, Y, mitochondrion) and **how many genes and factors are involved** (single gene with large effect, or many genes plus environment).

```
SINGLE GENE                 AUTOSOMAL      dominant (achondroplasia, Huntington)
                            recessive      (cystic fibrosis, sickle cell)
                            X-linked       recessive (haemophilia) / dominant (rickets)
                            Y-linked       (male infertility factors)
                            MITOCHONDRIAL  (maternal line only)

MANY GENES + ENVIRONMENT    multifactorial  (type 2 diabetes, hypertension)
```

Then there is the population question: given that a disease exists, **how many people silently carry the allele?** Hardy–Weinberg equilibrium answers that with one equation, and — read in reverse — tells you when evolution is happening.

## Autosomal dominant inheritance

**The rule:** one copy of the pathogenic allele is enough. Affected individuals are almost always heterozygous (*Aa*); each of their children has an independent **½ risk**; the trait appears in every generation.

| Condition | Gene and mechanism | Clinical notes |
| --- | --- | --- |
| **Achondroplasia** | *FGFR3* — **gain-of-function**; the receptor permanently inhibits cartilage/bone growth | Most common form of disproportionate short-limbed dwarfism; adult height ~120–130 cm; **~80% are new mutations** (paternal age effect); **homozygous *FF* is lethal** |
| **Huntington disease** | *HTT* — **CAG trinucleotide repeat expansion** → toxic polyglutamine tract in the protein | Onset typically 30–50 years, progressive chorea, cognitive and psychiatric features; **near-complete penetrance above ~40 repeats**; no effective cure |

**Why achondroplasia illustrates dominance and lethality in one allele:**

```
FgA = pathogenic FGFR3 allele      Fgn = normal

FgA Fgn × FgA Fgn
        │
        ▼
1/4 FgA FgA   → dies before birth (homozygous lethal)
2/4 FgA Fgn   → achondroplasia
1/4 Fgn Fgn   → typical stature

among LIVE births: 2 affected : 1 unaffected
P(affected | live birth) = 2/3
```

That **2/3** figure is a favourite exam calculation — it is a 2:1 ratio conditional on survival.

**Huntington disease is dominant but *delayed*.** The allele is fully expressed decades before symptoms, so carriers reproduce before they know — which is why the dominant pattern looks unbroken in pedigrees while the disease only appears in mid-life. Long repeats tend to **expand on transmission (anticipation)**, especially through the father, making earlier onset in the next generation.

## Autosomal recessive inheritance

**The rule:** two copies required. Unaffected carriers are heterozygous; affected individuals are homozygous (or compound heterozygous); the trait **skips generations**; consanguinity raises risk.

| Condition | Gene and mechanism | Clinical notes |
| --- | --- | --- |
| **Cystic fibrosis** | *CFTR* — a chloride/bicarbonate channel; ~70% of alleles are **ΔF508** (misfolded, degraded) | Thick, dehydrated mucus in lungs, pancreas, gut; pancreatic insufficiency; progressive lung disease; carrier frequency ~1 in 25 in Northern Europeans |
| **Sickle cell disease** | *HBB* — **Glu6Val** missense → **HbS** polymerises when deoxygenated → red cells sickle | Vaso-occlusive crises, haemolysis, stroke, organ damage; **HbAS (trait) is protected against *Plasmodium falciparum* malaria** |

**The cystic fibrosis arithmetic, end to end:**

```
carrier frequency 2pq ≈ 1/25   →   incidence q² ≈ (1/25 ÷ 2)² ≈ 1/2,500   (check: 4 × incidence ≈ carrier freq)

two carriers:   ¼ affected   ½ carrier   ¼ non-carrier   — every pregnancy, independently
sibling of an affected child, unaffected:  2/3 chance of being a carrier
```

Note the genotype wording from [01 — Genes, alleles](01-genes-alleles-genotype-phenotype.md): many CF patients are **compound heterozygotes** (*a₁a₂*), carrying two *different* CFTR mutations — recessive in effect, but not homozygous in sequence.

**Sickle cell — the textbook case of heterozygote advantage.** In malarial regions, the *HbS* allele persists at high frequency because **heterozygotes have higher overall fitness than either homozygote**:

```
fitness by genotype in a malarial region:

HbAA   →  susceptible to severe malaria         fitness ↓
HbAS   →  reduced severe malaria; no sickling   fitness ↑↑   ← favoured
HbSS   →  sickle cell disease                   fitness ↓↓↓

average fitness is maximised by an INTERMEDIATE allele frequency
→ BALANCING SELECTION maintains a "harmful" allele in the population
```

Mechanisms of protection include enhanced sickling and clearance of infected red cells, impaired parasite growth in the low-oxygen sickled cell, and enhanced phagocytosis. The same allele that is lethal homozygous is advantageous heterozygous — the clearest demonstration that **fitness belongs to a genotype in an environment, not to an allele in isolation** (see [06 — Evolution](../06-evolution/)).

## X-linked recessive inheritance

**The rule:** males are hemizygous and express every variant; females need two copies and are usually carriers; **no male-to-male transmission**; the trait skips generations through carrier women.

| Condition | Gene | Notes |
| --- | --- | --- |
| **Haemophilia A** | *F8* (factor VIII) | ~1 in 5,000 males; spontaneous bleeding into joints and muscle; severity tracks residual factor activity; carriers usually have ~50% activity and are clinically normal (occasionally mildly low) |
| **Red–green colour blindness** | Opsin genes on Xq | ~8% of males, ~0.5% of females; crossover between opsin genes creates anomalous pigment alleles |

**Inheritance through three generations:**

```
I     affected grandfather (X^h Y)
              │ X^h to every daughter
II    carrier daughter (X^H X^h)   — phenotypically normal
              │ each son: 50% chance of X^h
III   affected grandson (X^h Y)    ← "criss-cross": grandfather → grandson via a female

carrier mother (X^H X^h) × unaffected father (X^H Y)
      each pregnancy:  ¼ affected son   ¼ normal son
                       ¼ carrier daughter   ¼ non-carrier daughter
      → 1/8 of ALL children affected; 1/2 of SONS affected
```

An affected father's daughters are **all obligate carriers**, and his sons are all unaffected — the observation that identifies the pattern in a pedigree ([04 — Pedigree analysis](04-pedigree-analysis.md)). Carrier females are occasionally symptomatic through **skewed X-inactivation** (manifesting carriers), a direct consequence of the mechanism in [03 — Non-Mendelian patterns](03-non-mendelian-patterns.md).

## X-linked dominant inheritance

**The rule:** heterozygous females are affected; the allele never "skips"; **affected father → all daughters, no sons**.

- **Hypophosphataemic rickets** (*PHEX*) — impaired phosphate reabsorption, rickets and bone deformity — is the standard example.
- An affected man transmits the allele to **every daughter** (his only X) and to **no son** (he gives the Y).
- An affected heterozygous woman transmits to **½ of sons and ½ of daughters**.
- Males with the allele can be more severely affected when the condition is poorly tolerated with one X, and some X-linked dominant genotypes are **male-lethal** (e.g. typical incontinentia pigmenti), which is why such pedigrees show predominantly affected females with miscarriages.

## Y-linked inheritance

**The rule:** only males have a Y, so only males are affected, **father → every son**, with no female carriers anywhere.

- **SRY** (sex-determining region Y) — the switch that initiates male development; its translocation can produce XX males or XY females.
- **AZF (azoospermia factor) regions** on Yq — deletions cause severe oligozoospermia or azoospermia; a genuine, clinically important Y-linked trait (male infertility), and a common exam answer for "father-to-son transmission in every generation".
- "Hairy ear rims" appears in older question banks as Y-linked; the evidence is weak — use AZF.

**Diagnostic discipline:** a male-limited trait is Y-linked *only* if there is unbroken father-to-son transmission and **no affected female is ever possible**. Male-skewed pedigrees with a female transmitter are X-linked recessive, not Y-linked.

## Mitochondrial inheritance

Mitochondria carry their own small genome (37 genes, including 13 electron transport chain subunits), inherited **exclusively from the egg** — the sperm contributes essentially no mitochondria at fertilisation.

```
affected MOTHER ──▶ ALL children at risk (but variable severity)
affected FATHER  ──▶ NO children affected

severity depends on HETEROPLASMY: the proportion of mutant vs normal mtDNA per cell
threshold effect: symptoms appear only when mutant load exceeds a tissue-specific threshold
```

- Transmission is **maternal-line only**: an affected woman passes the variant to all her children; an affected man passes it to none.
- **Heteroplasmy** — a mixture of mutant and wild-type mtDNA — plus the bottleneck during oogenesis explains why siblings range from unaffected to severely affected. This is dosage at the level of organelle genomes, and the mitochondrion's role as the cell's energy plant is in [04 — Energy and containment organelles](../02-cell-biology/04-energy-and-containment-organelles.md).
- **Examples:** **MELAS** (mitochondrial encephalomyopathy, lactic acidosis, stroke-like episodes) and **LHON** (Leber hereditary optic neuropathy — sudden central vision loss in young adults, male-predominant because of modifier genes and heteroplasmy).
- Counselling message: an affected mother's children are all at risk but not equally affected; an affected father's children are not at risk at all.

## Multifactorial and polygenic disease

Most common adult disease is **not** Mendelian. It arises from many susceptibility alleles (each small) plus environment, reaching a threshold of liability before the diagnosis appears.

| Condition | Genetic contribution | Environmental contribution |
| --- | --- | --- |
| **Type 2 diabetes** | Dozens of common variants (e.g. *TCF7L2*) each raising risk modestly | Diet, activity, obesity, age |
| **Hypertension** | Polygenic blood-pressure set point; rare Mendelian forms exist (e.g. *ENaC* in Liddle syndrome) | Salt intake, weight, alcohol, stress |
| Obesity, coronary disease, asthma, neural tube defects | Similar polygenic architecture | As above, plus foetal and early-life exposures |

```
liability (genetic + environmental load)

        ──────── threshold ────────▶  DISEASE
   ▁▃▅▇█▇▅▃▁  most people stay below; high genetic load + adverse environment crosses it
```

**Practical consequences:**

- **Family history shifts risk in degrees, not in ratios** — first-degree relative with type 2 diabetes roughly triples risk; there is no 3:1 to quote.
- **Recurrence risk for a congenital multifactorial trait** (e.g. cleft lip, neural tube defects) rises with the number of affected relatives — the empirical rule used in counselling.
- Rare monogenic mimics exist within every "multifactorial" diagnosis, which is why severe, atypical, or very early cases get sequenced first.

## Carrier screening and cascade testing

| Approach | What happens | Where it fits |
| --- | --- | --- |
| **Population/preconception carrier screening** | Test healthy adults for common recessive alleles before pregnancy | Cystic fibrosis (1/25), sickle cell and thalassaemia (Mediterranean, African, South Asian, Middle Eastern ancestry), Tay–Sachs (Ashkenazi Jewish) |
| **Cascade (family) testing** | Once a pathogenic variant is found in a proband, test relatives in descending order of risk | Dominant conditions (Huntington, *BRCA*), and relatives of a recessive proband |
| **Newborn screening** | Heel-prick blood test at birth | Phenylketonuria, cystic fibrosis, sickle cell disease, congenital hypothyroidism — treat **before** the phenotype appears |
| **Prenatal diagnosis** | Chorionic villus sampling or amniocentesis → genotype | Known carrier couple; plus preimplantation genetic testing in IVF |
| **Predictive testing** | Genotype in an asymptomatic adult | Dominant late-onset conditions (Huntington) — requires genetic counselling and consent protocols |

**Why screening numbers come from populations:** if you know incidence (*q²*), Hardy–Weinberg gives the carrier frequency (2*pq*) — which tells a health service how many people to counsel, and a couple how their joint risk multiplies.

## Hardy–Weinberg equilibrium

Hardy–Weinberg (H-W) is a **null model for populations**: if allele frequencies do not change from generation to generation, genotype frequencies follow a predictable equation — and the population is, by definition, not evolving.

### The equation

For a locus with two alleles, *A* (frequency ***p***) and *a* (frequency ***q***):

```
ALLELE FREQUENCIES        p + q = 1

GENOTYPE FREQUENCIES      p² + 2pq + q² = 1

   p² = frequency of AA        2pq = frequency of Aa (carriers)        q² = frequency of aa
```

Where does it come from? If gametes unite **at random**, the chance of an *a* egg is *q* and of an *a* sperm is *q*, so *aa* zygotes form at *q* × *q* = *q²* (the product rule from [02 — Mendelian inheritance](02-mendelian-inheritance-and-punnett-squares.md)). Every zygote genotype is a random gamete pair.

### The five assumptions

| Assumption | If violated, what happens |
| --- | --- |
| 1. **No mutation** | New alleles enter; frequencies drift upward |
| 2. **Random mating** | Assortative mating or inbreeding → excess homozygotes |
| 3. **No natural selection** — all genotypes equally viable and fertile | Differential survival changes *p* and *q* (e.g. balancing selection on *HbS*) |
| 4. **No gene flow** (no migration) | Immigrants change local allele frequencies |
| 5. **Effectively infinite population** — no genetic drift | Small populations fluctuate randomly (founder effect, bottlenecks) |

**All five together define evolutionary equilibrium.** H-W holds only when *none* of them is violated.

### Worked example 1 — incidence to carrier frequency

*A recessive condition occurs in 1 in 4,000 newborns. Assume H-W. Find q, p, and the carrier frequency, then the risk that two random partners are both carriers.*

```
step 1   q² = 1/4,000 = 0.00025
step 2   q = √0.00025 = 0.0158
step 3   p = 1 − q = 0.9842
step 4   2pq = 2 × 0.9842 × 0.0158 = 0.0311  →  ≈ 1 in 32 people are carriers
step 5   both partners carriers: (0.0311)² = 0.00097  →  ≈ 1 in 1,035 random couples
         and if both are carriers, ¼ of their children are affected
```

Useful shortcut when *q* is small: *p* ≈ 1, so **2*pq* ≈ 2*q*** — carrier frequency ≈ 2 × √(incidence). Here 2 × 0.0158 = 0.0316, within rounding of the exact value.

### Worked example 2 — from incidence to carriers among the unaffected

*4% of newborns in a population have an autosomal recessive disease. What are the allele frequency, the carrier frequency, and what proportion of unaffected people are carriers?*

```
step 1   q² = 0.04        →   q = 0.2   (1 in 5 alleles in the population)
step 2   p = 1 − 0.2 = 0.8
step 3   p² = 0.64   2pq = 0.32   q² = 0.04        (check: 0.64 + 0.32 + 0.04 = 1 ✓)
step 4   carriers among the UNAFFECTED:

            2pq / (p² + 2pq)  =  0.32 / (0.64 + 0.32)  =  0.32/0.96  =  1/3
```

So **one third of unaffected people in this population are carriers** — the conditional-probability logic of the pedigree "2/3" result, now derived from population data rather than family data. Both worked examples are the arithmetic behind carrier-screening policy: incidence gives *q*, *q* gives 2*pq*, and 2*pq* tells you how many apparently healthy people to counsel.

### Departure from equilibrium means evolution

H-W genotype frequencies are observed and compared with expected ones; a statistically significant mismatch means at least one assumption fails — and each failure is a mechanism of evolution:

```
observed ≠ expected  (χ² test)
        │
        ├─ excess homozygotes  → inbreeding / consanguinity
        ├─ allele frequency shifts between generations → SELECTION (e.g. HbS maintained by malaria)
        ├─ sudden frequency change in a small population → GENETIC DRIFT (founder effect)
        ├─ new or altered frequencies with migration   → GENE FLOW
        └─ novel alleles appearing                    → MUTATION
```

**An evolving population is a population in H-W *disequilibrium*.** The equation is therefore simultaneously a population-genetics calculator and the null hypothesis of [06 — Evolution](../06-evolution/) — which takes each of those departures and develops it into the theory of how species change.

## Medical relevance

**Therapy now targets the gene product, not just the phenotype.** **Cystic fibrosis:** CFTR modulators (elexacaftor/tezacaftor/ivacaftor) correct folding or open the channel, transforming prognosis in eligible genotypes — a direct therapy for a misfolded protein. **Sickle cell disease:** hydroxyurea raises foetal haemoglobin (HbF) and reduces crises; voxelotor and crizanlizumab target sickling and adhesion; curative gene therapy and autologous stem-cell approaches now exist. **Haemophilia A:** recombinant or plasma-derived factor VIII, extended-half-life products, and **emicizumab** (a bispecific antibody mimicking factor VIIIa) have moved patients to near-normal bleeding rates; **desmopressin** releases stored factor VIII in mild cases. **Huntington disease:** no cure, but tetrabenazine/deutetrabenazine suppress chorea and presymptomatic testing is offered under strict counselling protocols.

**Screening saves function that cannot be recovered.** Newborn screening detects phenylketonuria, cystic fibrosis, and sickle cell disease before symptoms — dietary control in PKU prevents intellectual disability entirely, because the intervention happens at the environmental step of the genotype → phenotype chain.

**Risk communication is the practical product of these patterns.** A couple who both test as CF carriers are told ¼ per pregnancy (independent each time), that an unaffected sibling's carrier chance is 2/3 until genotyped, and that prenatal testing or IVF with preimplantation genetic testing are options. A family with X-linked haemophilia is told ½ of sons of a carrier are affected and that all daughters of an affected man are carriers — the pattern, not a vague "genetic risk".

**Population genetics sets screening policy.** H-W converts disease incidence into carrier frequency: a 1-in-2,500 incidence implies ~1-in-25 carriers, which is exactly the order of frequency that justifies offering carrier screening to whole populations or to defined ancestry groups. Founder populations (Ashkenazi Jewish, Finnish, Sardinian) have elevated frequencies of specific recessive alleles through drift — departures from H-W that were detected by screening data.

**Heterozygote advantage complicates genetic advice and is a treatment clue.** Sickle cell trait is not a disease to be "cured" out of a population — it protects against malaria — while the same molecular insight (HbF switching) underlies hydroxyurea therapy.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Dominant" = always present in every generation | True only with full penetrance; **late onset** (Huntington) and non-penetrance make a dominant trait appear to skip |
| Recessive = rare and harmful | Recession says nothing about frequency or fitness — *HbS* is maintained by selection, and thousands of recessive alleles are neutral |
| A healthy parent of an affected recessive child is "not a carrier" | They are **obligate heterozygotes** — unaffected *because* the trait is recessive |
| Carrier = unaffected = unaffected genotype | Carriers have the pathogenic allele; only the phenotype is normal |
| Male-predominant = Y-linked | Y-linked means father → **all** sons with no female carriers ever; male-skewed with female transmitters = X-linked recessive |
| Sex-linked = sex-influenced | Location (X chromosome) versus hormonal modulation of an autosomal gene |
| Mitochondrial traits can come from the father | No — mtDNA comes from the egg; an affected father passes it to no one |
| Multifactorial means "not genetic" | It means **polygenic plus environment**; genetic contribution is real, just not Mendelian |
| Incidence equals carrier frequency | Incidence ≈ *q²*; carriers ≈ 2*pq*. Carrier frequency is roughly **twice the square root** of incidence (when *q* is small) |
| Hardy–Weinberg proves populations are static | It is a **null model**: departures from H-W are how evolution is *detected* |

## Key facts

- **Autosomal dominant**: one copy suffices, affected are heterozygotes, ½ risk per child, no skipping (with full penetrance); **achondroplasia** is *FGFR3* gain-of-function with a **homozygous lethal** genotype → 2/3 of live births from two affected parents are affected.
- **Huntington disease**: CAG repeat expansion, dominant, **onset 30–50**, anticipation (repeats expand, especially paternally), predictive testing possible decades before symptoms.
- **Autosomal recessive**: two copies required, skips generations, consanguinity raises risk; **cystic fibrosis** = *CFTR* (ΔF508 most common), carrier ≈ 1/25, incidence ≈ 1/2,500; unaffected sibling of an affected child is a carrier with probability **2/3**.
- **Sickle cell**: *HBB* Glu6Val → HbS polymerisation on deoxygenation; **heterozygote advantage** against *P. falciparum* malaria maintains the allele — balancing selection.
- **X-linked recessive**: hemizygous males express, females usually carriers, **no male-to-male transmission**, criss-cross grandfather → grandson via carrier daughters; **haemophilia A** (*F8*) and red–green colour blindness; carrier mother → ½ of sons affected (¼ of all children).
- **X-linked dominant**: heterozygous females affected; **affected father → all daughters, no sons**; e.g. hypophosphataemic rickets (*PHEX*).
- **Y-linked**: father → all sons only; *SRY* (sex determination) and *AZF* deletions (male infertility) are the real examples.
- **Mitochondrial**: maternal transmission only; **heteroplasmy** with a threshold effect explains variable severity; MELAS and LHON; affected father transmits to no one.
- **Multifactorial disease** (type 2 diabetes, hypertension) = many small-effect alleles + environment beyond a liability threshold; risk rises with family history but no single ratio applies.
- **Carrier screening** targets common recessive alleles by ancestry; **newborn screening** treats before phenotype (PKU); **cascade testing** follows a proband's variant.
- **Hardy–Weinberg**: *p* + *q* = 1 and *p²* + 2*pq* + *q²* = 1, assuming no mutation, random mating, no selection, no gene flow, and an effectively infinite population.
- **Departure from H-W = evidence that evolution is occurring** — selection, drift, gene flow, mutation, or non-random mating have changed the frequencies.

## Practice questions

**1. Two people with achondroplasia (autosomal dominant, homozygous lethal) have children. Among live-born children, what proportion will have achondroplasia?**

A. ¼
B. ½
C. 2/3
D. ¾

**Answer: C**

Explanation: *FgA Fgn* × *FgA Fgn* gives ¼ *FgA FgA* (lethal, lost before birth), ½ *FgA Fgn* (achondroplasia), and ¼ *Fgn Fgn* (typical). Conditioning on live birth removes the lethal quarter, leaving 2 affected out of 3 survivors = 2/3. Option ¼ is the raw conception probability of the lethal homozygote, not the affected proportion.

---

**2. Huntington disease is described as autosomal dominant, yet a person's grandparents were all unaffected. The best explanation is**

A. The disease is actually autosomal recessive
B. Onset in mid-life means the allele was present but unexpressed until after reproduction; some cases are new repeat expansions
C. Grandparents are obligate carriers who were never tested
D. Dominant traits do not transmit through males

**Answer: B**

Explanation: Dominance governs the phenotype, not the timing — with onset typically between 30 and 50, an affected grandparent could have transmitted the allele before symptoms appeared, and the unaffected "grandparents" may simply predate any clinical recognition. Longer CAG repeats expanding on transmission (anticipation) can also create the allele's apparent appearance in a new generation. Reclassifying it as recessive (A) contradicts the heterozygote phenotype, and D has no basis.

---

**3. Cystic fibrosis has an incidence of about 1 in 2,500 in a Northern European population under Hardy–Weinberg assumptions. Approximately what fraction of people are carriers?**

A. 1 in 2,500
B. 1 in 50
C. 1 in 25
D. 1 in 4

**Answer: C**

Explanation: Incidence = *q²* = 1/2,500, so *q* = 1/50 = 0.02 and *p* ≈ 0.98. Carrier frequency = 2*pq* = 2 × 0.98 × 0.02 ≈ 0.039 ≈ 1 in 25 — the well-known screening figure, and the reason random couples face a calculable risk. 1 in 50 would be *q* itself (the allele frequency, B); 1 in 2,500 is the affected homozygote frequency (A).

---

**4. Why does the sickle cell allele remain common in malarial regions despite causing disease in homozygotes?**

A. Most affected individuals reproduce normally, so the allele is neutral
B. Heterozygotes (HbAS) have increased fitness against severe malaria, so balancing selection favours an intermediate allele frequency
C. The allele is dominant, so it is expressed in most of the population
D. Mutation continuously recreates the allele at a high rate

**Answer: B**

Explanation: HbAS red cells resist *Plasmodium falciparum* through several mechanisms (impaired parasite growth, enhanced sickling and clearance of infected cells), so heterozygotes outperform both homozygotes in malarial environments. Selection therefore maintains an intermediate frequency — balancing selection — rather than eliminating a harmful allele. Fitness is not neutral (A), dominance (C) does not determine allele frequency, and mutation rates are far too low (D) to account for frequencies of 10–20%.

---

**5. A woman is a carrier for an X-linked recessive condition and her partner is unaffected. What is the probability that a child is affected?**

A. ½
B. ¼
C. ⅛
D. 1/16

**Answer: C**

Explanation: Only sons can be affected, and each son has a ½ chance of inheriting the variant X: ½ (chance of a son) × ½ (chance he receives *X^h*) = 1/8 of all children. The risk *given the child is a son* is ½ (A) — always state which denominator applies. Daughters cannot be affected because they receive a normal X from their father.

---

**6. In a pedigree, an affected father has an affected daughter but an unaffected son with an unaffected mother. The pattern indicates**

A. Autosomal recessive inheritance
B. Y-linked inheritance
C. X-linked dominant inheritance
D. Mitochondrial inheritance

**Answer: C**

Explanation: He passes his only X — carrying the dominant variant — to his daughter, making her heterozygous and affected, while his son receives his Y and a normal X from the mother. This father-to-daughter, not-to-son transmission is the signature of X-linked dominant inheritance. Y-linked (B) could only affect the son; autosomal recessive (A) would require the unaffected mother to be a carrier and would not predict sex-specific outcomes; mitochondrial (D) transmits through mothers.

---

**7. A man has a mitochondrial disorder. Which statement about his children is correct?**

A. All children will be affected
B. Half the children will be affected
C. None of the children will be affected through him
D. Only his sons will be affected

**Answer: C**

Explanation: Mitochondrial DNA is inherited from the egg — sperm mitochondria are excluded at fertilisation — so an affected father transmits no pathogenic mtDNA to any child. An affected *mother* would put all her children at risk, with severity varying by heteroplasmy. Nothing about the X or Y chromosomes is involved, so options A, B, and D have no basis.

---

**8. A population has a recessive disease frequency of 4% of newborns. What is the carrier frequency, assuming Hardy–Weinberg equilibrium?**

A. 4%
B. 16%
C. 32%
D. 64%

**Answer: C**

Explanation: *q²* = 0.04, so *q* = 0.2 and *p* = 0.8. Then 2*pq* = 2 × 0.8 × 0.2 = 0.32 = 32% — and since 0.64 + 0.32 + 0.04 = 1, the three genotype classes account for the whole population. 4% is *q²* (affected homozygotes), 64% is *p²* (non-carrier homozygotes), and 16% is *q²* of a *different* quantity — a distractor built from *q* × *q* applied to *p*.

---

**9. Which set represents the five assumptions of Hardy–Weinberg equilibrium?**

A. No mutation, random mating, no selection, no gene flow, and an effectively infinite population
B. No mutation, assortative mating, natural selection, gene flow, and small population
C. Random mating, mitosis, crossing over, dominance, and segregation
D. No recombination, no dominance, fixed allele frequencies, clonal reproduction, and no environment

**Answer: A**

Explanation: H-W holds only if allele frequencies are left untouched: no new alleles (mutation), no pairing bias (random mating), no differential fitness (selection), no immigration/emigration (gene flow), and no sampling error (effectively infinite population). Option B contains three violations in place of assumptions; C lists cell-biological processes irrelevant to population frequencies; D describes asexual, static systems.

---

**10. Genotype frequencies in a real population deviate significantly from Hardy–Weinberg expectations. What can you conclude?**

A. The population is not evolving, and the deviation is measurement error
B. At least one H-W assumption is violated — evidence of a mechanism of evolution
C. Mendel's laws have failed in this population
D. The population must be inbred, whatever the pattern of deviation

**Answer: B**

Explanation: H-W is the null model of evolutionary equilibrium; a significant departure means allele frequencies are being reshaped by selection, non-random mating, drift, gene flow, or mutation — the very mechanisms that constitute evolution. Deviation does not mean Mendel's laws failed at the level of meiosis (C), it is not dismissed as error (A), and excess homozygosity is only *one* possible pattern — a heterozygote excess points instead to mechanisms such as disassortative mating or balancing selection (D).
