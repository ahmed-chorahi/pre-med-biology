# Genetic Drift and Gene Flow

## Why it matters

Natural selection is not the only force that changes allele frequencies. **Genetic drift** — random change in allele frequency from one generation to the next — is the opposite of selection in one crucial respect: it has **no direction.** It can make an allele more common or less common regardless of its effect on fitness, and in small populations it can overwhelm selection entirely.

This matters clinically more than it first appears. Drift explains why certain rare diseases cluster in specific populations — **Tay–Sachs in Ashkenazi Jews, a whole catalogue of recessive disorders in Finns, porphyria variegata in South Africa** — and why whole populations can be founded by a handful of individuals carrying an unusual allele set. It also explains why a cheetah is immunologically fragile and why conservation programmes fail when population size collapses. The medical term for these patterns is the **founder effect**, and it is drift wearing a diagnostic coat.

Drift must also be understood against its null model. **Hardy–Weinberg equilibrium** states the conditions under which allele frequencies do *not* change — five assumptions, every one of which is violated in real populations by some force. Drift is what happens when you violate the infinite-population assumption alone. Pair it with **gene flow**, the movement of alleles between populations, and you have the two great equalisers: drift makes populations *differ* by chance, gene flow makes them *resemble* each other by mixing.

## Drift: random sampling of gametes

Every generation, each individual contributes a **sample** of its alleles to the gamete pool, and gametes are drawn roughly at random. In a finite population, a random sample never perfectly reproduces the proportions of the source — this is sampling error, and it is the entire mechanism of drift.

```
population of 6 individuals, allele p = 0.5
   → each produces gametes, fertilisation is random
      → next generation happens to contain p = 0.67
         → sampling error this generation: +0.17, purely by chance
            → repeat over generations → p drifts unpredictably
               → eventually p reaches 1.0 (fixation) or 0.0 (loss)
                  with no regard to the allele's effect on fitness
```

Three properties define drift:

| Property | Statement |
| --- | --- |
| **Directionless** | Allele frequency moves up or down with equal probability, whatever the allele does |
| **Stronger when N is small** | Sampling error scales with 1/N — a population of 10 drifts violently, a population of 10 million barely at all |
| **Irreversible in effect** | Once an allele is fixed or lost (and mutation aside), the change is permanent |

Drift is therefore **most powerful in exactly the situations where selection is weakest**: small populations, new populations, and populations passing through a crisis. In large populations, selection with even a tiny advantage wins; in small ones, a genuinely useful allele can be lost by bad luck, and a useless one can fix.

## The founder effect and the bottleneck

Two special cases of drift produce medically recognisable patterns because both start with a **sudden, drastic reduction in genetic diversity**.

### The founder effect

A new population is established by a small number of individuals whose allele frequencies are a random, unrepresentative sample of the source population.

```
large source population (rare allele at 0.1%)
      │
      │  a few individuals colonise an island / found a community
      ▼
founding sample of 8 people — by chance 3 carry the allele (37.5%)
      │
      ▼  drift + small Ne + often endogamy (marriage within the group)
founding population with an ENRICHED rare allele
      → descendants show unusually high rates of the associated disorder
```

**Human examples:**

| Population | Enriched allele / condition | Why |
| --- | --- | --- |
| **Ashkenazi Jews** | Tay–Sachs, Canavan, familial dysautonomia, Niemann–Pick type A, and several BRCA1/BRCA2 founder mutations | Medieval founder population, centuries of endogamy, repeated bottlenecks; several distinct founder haplotypes |
| **Finnish population** | ~40 "Finnish Heritage Diseases" — e.g. infantile neuronal ceroid lipofuscinosis, distal renal tubular acidosis, lactic acidosis (MERRF) | Settlement by a small founding group, internal geographic isolation, local marriages |
| **Amish** | Ellis–van Creveld syndrome, maple syrup urine disease (specific communities) | Small founding number, strict endogamy |
| **Afrikaners** | Porphyria variegata | Small Dutch founding community |
| **Montreal's French Canadians** | Certain recessive disorders at elevated frequency | Founder effect of a few hundred settlers |

The Ashkenazi pattern is not "a bad gene pool" — several of the enriched alleles appear to have been **favoured in the past** (heterozygote advantage hypotheses exist for some, e.g. Tay–Sachs carrier frequency and tuberculosis, though these remain debated). What drift explains is the *concentration*; what selection may explain is *which* allele got concentrated.

### The bottleneck

A population crashes to a very small number and then recovers in size — but not in diversity.

```
large population ──► catastrophe (disease, habitat loss, hunting)
                        │
                        ▼
              few survivors (random subset of alleles)
                        │
                        ▼
              population regrows to large numbers
                        → census size N is large again
                        → but most original alleles were lost in the crash
```

**Cheetahs** are the standard example: after an apparent bottleneck in the late Pleistocene (and a second ~10,000 years ago), today's cheetahs are so genetically uniform that they accept **skin grafts from one another** — their MHC diversity is extremely low, which is precisely the vulnerability a bottleneck predicts, since MHC variation is what allows a population to recognise varied pathogens. Northern elephant seals were hunted to perhaps 20–30 individuals in the 1890s; the species recovered numerically but retains far less variation than its southern relatives.

## Neutral theory and nearly neutral theory

In 1968 Motoo Kimura proposed the **neutral theory**: most evolutionary change at the molecular level, and most variation within and between species, is **not caused by selection at all** but by the drift of selectively neutral mutations — those with no effect on fitness.

The argument is quantitative. For a new mutation to be driven to fixation by selection it must beat drift, and drift's strength scales with 1/2N. A mutation with advantage *s* is effectively invisible to selection when:

```
|s| << 1 / (2Nₑ)

   Nₑ = 100      → selection must beat ≈ 0.5%  → almost nothing is neutral
   Nₑ = 10⁶      → selection must beat ≈ 0.00005% → only near-zero effects drift
```

Kimura went further: **most mutations are so close to zero in effect that drift dominates even in large populations.** Ohta's **nearly neutral theory** refined this — mutations with small negative effects (*slightly deleterious*) behave neutrally when 2Nₑ|s| < 1, which means **the same mutation is effectively neutral in a small population and selected against in a large one.** The boundary between "neutral" and "selected" is therefore not a property of the mutation alone; it is a property of the mutation *and* the population size.

Neutral theory does not claim selection is unimportant — it claims selection explains the *fit* of organisms to their environment, while drift explains most of the *sequence differences* seen in DNA comparisons. Both are needed: molecular phylogenies (chapter 05) are built on the assumption that a good fraction of substitutions are neutral, and pseudogenes exist because drift lets broken genes persist.

## Effective population size vs census size

**Census size (N)** is the number of individuals you can count. **Effective population size (Nₑ)** is the size of the idealised population that would lose genetic diversity at the same rate — and it is almost always far smaller.

Typical reasons Nₑ ≪ N:

| Factor | Effect on Nₑ |
| --- | --- |
| **Unequal reproductive success** — a few males sire most offspring | Often the largest single reduction (harem species: Nₑ ≈ one-quarter of N) |
| **Fluctuating population size** | Harmonic mean — bad years dominate; a crash costs more than a boom gains |
| **Variance in family size** | High variance shrinks Nₑ |
| **Sex ratio bias** | Skewed sex ratio reduces the breeding pool |
| **Population structure** — subdivided into local groups | Nₑ ≈ total N / number of subgroups in the extreme |

The practical consequence: **a species with a million individuals but a skewed mating system may drift like a population of a few thousand.** Conservation biology uses Nₑ, not N, when setting minimum viable population sizes — the rough rule of thumb is that a population needs Nₑ of at least 50 to avoid short-term inbreeding depression and at least 500 to retain the capacity for long-term adaptive evolution.

## Drift vs selection: when each dominates

| | Natural selection | Genetic drift |
| --- | --- | --- |
| **Direction** | Predictable, toward favoured phenotype | Random, no preferred outcome |
| **Depends on fitness?** | By definition | No — neutral to fitness |
| **Strength vs population size** | Independent of N (relative advantage fixed) | **Scales with 1/N** — dominates when N is small |
| **Effect on variation** | Removes unfavourable alleles; can maintain variation (balancing) | Removes variation by random fixation/loss |
| **Can fix a harmful allele?** | No (unless balanced or conditionally beneficial) | **Yes**, if small enough |
| **Can lose a beneficial allele?** | Only if drift overwhelms weak selection | **Yes**, easily in small populations |

**Which wins?** Compare |s| with 1/(2Nₑ). If 2Nₑ|s| > 1, selection dominates and the deterministic prediction holds. If 2Nₑ|s| < 1, drift effectively decides the allele's fate. So the same beneficial mutation sweeps in a large population and vanishes in a small one — the reason population genetics is not optional in conservation and in cancer (where Nₑ is the number of cells, and thus enormous, making selection dominant over drift within a tumour).

## Hardy–Weinberg as the null model

The Hardy–Weinberg principle states that allele and genotype frequencies stay constant from generation to generation **if and only if** five conditions hold — which is to say, it describes a population where no evolution of any kind is happening. Full treatment is in [05 — Human inheritance patterns](../04-genetics/05-human-inheritance-patterns.md); the recap here is the assumption list, because each one names a force from this section:

```
p² + 2pq + q² = 1     and     p + q = 1

holds constant only if:
   1. NO MUTATION            (new alleles not entering)
   2. NO GENE FLOW           (alleles not moving between populations)
   3. INFINITE POPULATION     (no sampling error → no drift)
   4. RANDOM MATING           (no sexual selection / inbreeding bias)
   5. NO SELECTION           (all genotypes equal fitness)
```

Violation of assumption 3 alone gives **drift**; violation of assumption 2 gives **gene flow**; violations of 1, 4, and 5 give mutation, non-random mating, and selection respectively. The principle is used in two ways: to **predict expected genotype frequencies** and test whether observed ones fit (and if not, to identify which force is acting), and as the **null hypothesis** that every evolutionary mechanism is measured against.

## Gene flow: the homogenising force

**Gene flow (migration)** is the movement of alleles between populations — by dispersing individuals or by their gametes. Where drift makes populations *differ*, gene flow makes them *more alike*.

```
population A (p = 0.8)          population B (p = 0.2)
        │                                │
        └──────── migrants ──────────────┘
                     │
        A receives low-p gametes; B receives high-p gametes
                     ▼
        A: p falls toward 0.5-ish      B: p rises
                     ▼
        GENE FLOW REDUCES DIFFERENTIATION between the two
```

Properties worth holding:

- Even a **few migrants per generation** are enough to prevent substantial divergence — the standard rule of thumb is that migration rates of 1 migrant per generation keep populations genetically similar, and in practice much smaller amounts suffice for many loci.
- Gene flow **imports** alleles into a population, adding variation that drift alone would erode (this is why island populations with no immigration are the most depauperate).
- It **spreads beneficial alleles** faster than selection alone could move them through a large population — but it can also import maladapted alleles, creating **migration load** where local adaptation is under way.
- In humans, **admixture** is measurable gene flow: population genetics can estimate what fraction of an individual's genome derives from ancestral populations, and modern humans carry a few per cent Neanderthal and Denisovan ancestry — gene flow between our lineage and archaic ones.

Gene flow's power explains why widespread species are genetically uniform across continents while range-restricted endemics are patchy: continuous migration erases the differences drift would otherwise build.

## Mutation–selection balance

Mutation continually introduces new alleles (mostly deleterious ones); selection continually removes them. The result is a **stable equilibrium frequency** rather than zero — mutation–selection balance.

```
mutation rate μ ──▶ new deleterious alleles ──▶ q rises
                                                    │
selection coefficient s ◀── removes them ◀──────────┘
        equilibrium when mutation input = selection removal

   recessive:   q̂ ≈ √(μ / s)
   dominant:    q̂ ≈ μ / s
```

A worked example: achondroplasia arises by new mutation at rate μ ≈ 5 × 10⁻⁵, and heterozygotes have reduced fitness (s ≈ 0.5 against homozygotes; most cases are new mutations). Almost every case in a family is therefore a **fresh mutation**, not an inherited allele — and the condition persists at a stable low frequency because mutation keeps replacing what selection removes. This is why many severe dominant conditions are ~1/20,000 births with no family history, and why recessive carrier frequencies can be much higher than the disease frequency: carriers are invisible to selection, so q sits at √(μ/s), comfortably above what the disease rate alone suggests.

## Inbreeding depression ≠ drift

These are constantly confused because both involve small populations. They are different processes with different consequences:

| | Genetic drift | Inbreeding |
| --- | --- | --- |
| **What changes** | Allele **frequencies** | Genotype **frequencies** — specifically, more homozygotes |
| **Cause** | Random sampling in finite populations | Non-random mating between relatives |
| **Effect on diversity** | Loses alleles irreversibly | Does not remove alleles, but exposes them in homozygous state |
| **Evolutionary outcome** | Counts as evolution (frequencies changed) | Not evolution by itself — H–W allele frequencies unchanged |
| **Clinical consequence** | Rare alleles fixed or lost | **Inbreeding depression** — recessive disorders unmasked by homozygosity |

The two travel together in small populations: small N both accelerates drift *and* increases the chance of mating between relatives. But a population can inbreed without evolving (alleles unchanged, just more paired up), and it can drift without inbreeding (random mating in a small population).

## Why it matters in medicine and the real world

**Carrier screening programmes are founder-effect genetics in practice.** Ashkenazi Jewish screening panels test for Tay–Sachs, Canavan, familial dysautonomia, Gaucher, and others precisely because drift concentrated those alleles in that population; several guidelines also include specific BRCA1/BRCA2 founder mutations, since a single haplotype accounts for a large share of hereditary breast–ovarian cancer in this group. Similar population-targeted screening exists for **Finnish Heritage Diseases**, for Quebec's French Canadian population (with expanded carrier panels), and for consanguineous communities where homozygosity, not founder effect, is the driver. The clinical point: **prevalence in a population is not uniform, and knowing the population history predicts which alleles to look for first.**

**Bottlenecks explain disease susceptibility at species level.** The cheetah's low MHC diversity, and the genetic uniformity of cultivated crops and livestock (the Irish Potato Famine is a founder-effect disaster in agriculture), both follow from the same mechanism — and both are why genetic diversity is a conservation target in its own right, not a luxury.

**Genetic drift sets expectations for rare disease research.** In a small founder population a "rare" allele can be common enough to study and to design a therapy for; in a large panmictic population the same disorder scatters into dozens of private mutations. This is the reason gene-therapy development for some conditions runs through specific populations first.

**Ne is why outbreak and tumour populations behave as they do.** Within a host, a pathogen or tumour population passes through bottlenecks during transmission or treatment — the founding inoculum and the surviving clones after chemotherapy are random samples, so resistance or virulence alleles can be lost or fixed by luck before selection ever acts. The consequences appear in [07 — Microbiology](../07-microbiology/) and in the resistance logic of [02 — Natural selection](02-natural-selection.md).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Drift is weak selection" | It is **no** selection — directionless sampling error, powerful only when N is small. |
| "Drift and mutation are the same kind of force" | Mutation creates alleles; drift **moves their frequencies at random**. |
| "A founder effect is a type of selection" | It is drift in a founding sample — the allele rose by chance sampling, not by any advantage. |
| "Hardy–Weinberg means a population is evolving" | The opposite: it is the **null model where nothing evolves**, under five explicit assumptions. |
| "Gene flow creates new variation" | It **transfers existing alleles** between populations; only mutation creates new ones. |
| "Inbreeding changes allele frequencies" | Inbreeding changes **genotype** frequencies (more homozygotes); drift changes allele frequencies. |
| "Neutral means useless" | Neutral means **no effect on fitness in this population at this time** — and neutrality depends on 2Nₑs, so the same allele can be neutral in one population and selected in another. |
| "Big census size means no drift" | **Nₑ is what counts**, and unequal breeding success, fluctuating numbers, and structure can make Nₑ a fraction of N. |

## Key facts

- **Genetic drift** = random change in allele frequency from generation-to-generation sampling error; strongest when population size is small.
- Drift **fixes or loses alleles regardless of fitness** — it can eliminate a beneficial allele and fix a harmful one.
- **Founder effect**: a new population starts from a few individuals with an unrepresentative allele sample — Ashkenazi Tay–Sachs and BRCA founder mutations, Finnish Heritage Diseases, porphyria variegata in Afrikaners.
- **Bottleneck**: a crash leaves few survivors; numbers recover but diversity does not — cheetahs accept skin grafts from unrelated individuals because MHC variation collapsed.
- **Neutral theory**: most molecular change is drift of neutral mutations; **nearly neutral** mutations behave neutrally when 2Nₑ|s| < 1.
- **Nₑ ≪ N** because of unequal breeding success, fluctuating size, sex-ratio bias, and population structure; conservation targets use Nₑ.
- Selection beats drift when **2Nₑ|s| > 1**; below that, drift decides the outcome.
- **Hardy–Weinberg** is the no-evolution null model: no mutation, no flow, infinite size, random mating, no selection.
- **Gene flow homogenises** populations, adds variation, and spreads alleles — a few migrants per generation prevent divergence.
- **Mutation–selection balance**: recessive q̂ ≈ √(μ/s), dominant q̂ ≈ μ/s — why dominant disorders are usually new mutations and carriers exceed patients.
- **Inbreeding depression** unmasking recessives is a genotype-frequency effect, distinct from drift's allele-frequency effect.

## Practice questions

**1. Genetic drift is best defined as**

A. A predictable increase in beneficial alleles each generation
B. Random change in allele frequency caused by sampling of gametes in finite populations
C. The movement of alleles between populations by migration
D. The directed mutation of genes under environmental stress

**Answer: B**

Explanation: Drift is sampling error — every generation's gametes are a finite, random draw from the previous generation, so allele frequencies fluctuate even with no selection at all. It has no direction (A), it is the opposite of the homogenising force of migration (C), and mutations are not directed by environmental need (D). Its strength scales with 1/N, which is why it dominates in small populations.

---

**2. Tay–Sachs disease occurs at markedly higher frequency in Ashkenazi Jews than in surrounding populations. The best explanation is**

A. The allele was actively selected for in every generation
B. A founder effect: the founding population carried the allele at higher than average frequency, and drift plus endogamy concentrated it further
C. Ashkenazi Jews have a higher mutation rate at the HEXA gene
D. The disease is acquired rather than inherited in this population

**Answer: B**

Explanation: A small founding sample can by chance contain a rare allele at a frequency well above its source value; centuries of marriage within the community then maintained and amplified that imbalance through drift. The allele is inherited and recessive (D false) with no elevated mutation rate (C false), and while heterozygote-advantage hypotheses have been proposed for some Ashkenazi alleles, drift — not universal positive selection (A) — is the primary explanation for the concentration.

---

**3. Why are cheetahs immunologically vulnerable despite a large census population today?**

A. They have no MHC genes at all
B. Their population passed through severe bottlenecks that fixed a narrow set of alleles, including at the MHC, and has not fully recovered the diversity
C. Their immune system is suppressed by inbreeding within a single family
D. Large populations always have low genetic diversity

**Answer: B**

Explanation: Pleistocene bottlenecks reduced cheetahs to very few individuals, so most original alleles — including much MHC variation — were lost by drift, and the modern population descends from that narrow sample. Skin grafts between unrelated cheetahs are accepted because the MHC is too uniform to register as foreign. They do possess MHC genes (A); D is exactly backwards; and while cheetahs are not severely inbred within one family (C), the population-level diversity loss stands.

---

**4. The neutral theory of molecular evolution states that**

A. All mutations are harmful
B. Most molecular differences between species arise from drift of mutations with no effect on fitness, not from selection
C. Selection cannot act on DNA sequences
D. Populations never change allele frequencies

**Answer: B**

Explanation: Kimura's proposal was quantitative — most substitutions and most polymorphism at the molecular level are selectively neutral and were fixed by drift, while selection explains the adaptation of organisms rather than their sequence differences. A is wrong (many mutations are neutral or beneficial), C is wrong (selection clearly acts on sequences affecting function), and D denies evolution outright.

---

**5. Which comparison of natural selection and genetic drift is correct?**

A. Both require large population size to be effective
B. Selection is directionless; drift favours whatever increases fitness
C. Drift dominates when populations are small; selection dominates when 2Nₑ|s| is large
D. Both remove variation at the same rate regardless of conditions

**Answer: C**

Explanation: Drift's strength scales with 1/N, so it overwhelms weak selection in small populations; once 2Nₑ|s| exceeds about 1, selection determines the allele's trajectory. The two are reversed in A and B — selection is directional and drift is not — and their effects on variation differ depending on the mode of selection, so D cannot hold.

---

**6. A population of 10,000 individuals has an effective population size of 400. Which factor most likely explains the difference?**

A. Most individuals are dead
B. Unequal reproductive success, population structure, and fluctuating size reduce the breeding contribution to a fraction of the counted individuals
C. The census includes individuals that carry no DNA
D. Effective population size is always exactly one-twentieth of census size

**Answer: B**

Explanation: Nₑ counts genetic contribution, not bodies — if a few individuals produce most offspring, or the population crashed at some point, or it is subdivided into partly isolated groups, the number of breeders effectively contributing genes each generation is far smaller than the number alive. There is no fixed ratio (D), and the discrepancy has nothing to do with individuals lacking DNA (C) or being dead (A).

---

**7. In the Hardy–Weinberg principle, violation of the "infinite population size" assumption leads to**

A. Mutation
B. Gene flow
C. Genetic drift
D. Sexual selection

**Answer: C**

Explanation: The infinite-size assumption is what removes sampling error. A finite population draws gametes at random, so allele frequencies fluctuate each generation — that is drift. Mutation violates the no-mutation assumption, migration violates the no-gene-flow assumption, and non-random mating violates random mating; none of them follows from population size alone.

---

**8. Compared with drift, gene flow between two populations tends to**

A. Increase genetic differences between them
B. Reduce genetic differences between them by sharing alleles
C. Eliminate all alleles except one in each population
D. Have no effect because migrants cannot reproduce

**Answer: B**

Explanation: Migration moves existing alleles from a population where they are common into one where they are rare and vice versa, pulling the two gene pools toward similarity — the homogenising effect that counters the diverging effects of drift and local selection. A describes the opposite force, C is fixation (which drift can cause, not flow), and D is false since migrant reproduction is precisely how the alleles enter the new population.

---

**9. Which statement about mutation–selection balance is correct?**

A. Severe dominant disorders should be eliminated entirely by selection
B. For a recessive deleterious allele, equilibrium frequency q̂ ≈ √(μ/s), so carriers are much more common than affected individuals
C. Selection removes every harmful allele in one generation
D. Mutation rate and selection coefficient are unrelated to disease frequency

**Answer: B**

Explanation: For recessives, selection only sees homozygotes, which are rare when q is small, so removal is slow and mutation input can sustain q at √(μ/s) — a frequency far above the disease rate (q²), which is why carrier screening finds many more heterozygotes than patients. A and C misunderstand selection's reach on recessives, and D contradicts the equation itself.

---

**10. A conservation biologist recommends maintaining an effective population size of at least 500. The main reason is that**

A. Larger populations never experience selection
B. Small Nₑ allows drift to erode genetic variation and fix deleterious alleles too quickly to sustain long-term adaptive potential
C. Census size determines how much food a species needs
D. Gene flow stops completely below 500 individuals

**Answer: B**

Explanation: Below the threshold, drift dominates: beneficial variants are lost by chance, mildly deleterious alleles fix, and inbreeding rises, so the population loses the raw variation selection needs in future environments. The figure addresses genetic health, not ecology (C); selection and migration continue at any size (A, D) — they are simply outcompeted by sampling error when Nₑ is small.
