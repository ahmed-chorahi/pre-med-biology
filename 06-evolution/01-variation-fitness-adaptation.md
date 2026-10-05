# Variation, Fitness, and Adaptation

## Why it matters

Evolution by natural selection requires three things to be true at the same time: **individuals differ from one another, those differences lead to different reproductive success, and the differences are passed on.** Remove any one of the three and the process stops. That is why this section opens with definitions rather than with Darwin — the three words in this chapter's title carry almost the whole of evolutionary biology, and in ordinary speech all three mean something looser than they mean here.

"Fitness" is the word most often misread: it does not mean strength, speed, health, or even survival. It is a bookkeeping quantity — **relative reproductive success measured in offspring** — on which a bacterium dividing every twenty minutes beats any athlete, and a sterile individual scores zero. "Adaptation" is misread in the opposite direction: it is not something an individual body does during a lifetime. Bodies acclimatise; **populations** adapt, over generations, as their allele frequencies shift.

Get these definitions right and a cascade of later errors never forms — Lamarckian reasoning, the belief that evolution rewards the strongest, and the confusion of variation with adaptation. In medicine the same distinctions decide how antibiotic resistance is read and why a drug's dose follows genotype rather than symptoms.

## What varies, and where variation comes from

Every individual in a sexually reproducing population is genetically unique. The sources of that uniqueness are few, precise, and worth memorising as a set, because they answer a question exams keep asking: *does this create new alleles, or only shuffle old ones?*

| Source | Level affected | When it happens | Creates new alleles? |
| --- | --- | --- | --- |
| **Mutation** | Single gene / DNA sequence | Any time DNA is replicated or repaired | **Yes — the only source** |
| **Crossing over (recombination)** | Chromosome segments | Prophase I of meiosis | No — shuffles existing alleles |
| **Independent assortment** | Whole chromosomes | Metaphase I of meiosis | No — shuffles chromosomes |
| **Random fertilisation** | Whole genome | Fusion of two gametes | No — combines two shuffled sets |
| **Gene flow** | Population | Migration between populations | No — imports and exports existing alleles |

The mechanism connecting a mutation to a visible difference runs through the central dogma, and every arrow in it is a place where the effect can be amplified, dampened, or erased:

```
random change in DNA sequence
   → altered mRNA codon during transcription
      → altered amino acid during translation
         → altered protein shape, stability, or amount
            → altered cell or organism phenotype
               → possible effect on survival and reproduction
                  → if heritable: allele frequency change next generation
```

Two features of this chain matter. **Mutation is random with respect to need** — a bacterium cannot decide to mutate its antibiotic target, and no amount of need directs a base substitution to the right gene. And the chain is leaky: most mutations are silent, many are deleterious, only rarely favourable. Selection sorts this raw output; it does not write it.

Recombination itself is treated in full in [12 — Meiosis](../03-cellular-processes/12-meiosis.md): independent assortment alone gives 2²³ ≈ 8.4 million gamete types per parent, and crossing over makes every such figure an underestimate.

### Heritable variation vs acquired variation: why Lamarck was retired with a mechanism

Lamarck proposed that organs used heavily strengthen through use and that the strengthening is inherited — the giraffe stretches its neck, so its offspring inherit a longer neck. This is not merely an old theory that was outvoted; **it fails at a specific mechanistic step**, and knowing the step is what stops it creeping back into reasoning.

```
LAMARCK'S CHAIN (claimed)
   effort stretches neck → neck tissue lengthens → change enters the germ line
                                              → offspring inherit longer neck

WHAT ACTUALLY HAPPENS
   giraffe stretches neck to reach leaves
      → muscle, tendon, and posture change (SOMATIC cells)
         → ovaries and testes hold a separate, protected DNA copy
            → Weismann barrier: body changes do not rewrite gamete DNA
               → offspring neck length = its own genotype + its own environment
```

Three facts kill the chain. **Somatic cells and germ line are separate lineages** — a scar, a tan, or a developed muscle leaves no trace in the DNA of ova or sperm. **Mutations arise during replication and repair, before and independently of any need**, so there is no feedback channel from "what the organism requires" to "what the sequence becomes". And **training adaptations are physiological, not genetic** — a blacksmith's strength is real, is not in his gametes, and his children are not born muscular.

| | Heritable variation | Acquired variation |
| --- | --- | --- |
| Example | HbS allele, blood group alleles, CYP2C19 variant | Muscle mass, tan, scar, vaccine-induced antibodies |
| Physical basis | Change in DNA of the germ line | Change in somatic tissue or physiology |
| Passed to offspring? | Yes | No |
| Visible to selection? | Yes — it changes allele frequencies | No — selection cannot act on it |

One caveat must be named so it is not mistaken for Lamarckism: **epigenetic marks** (methylation, small RNAs) occasionally transmit across a generation or two. In mammals they are largely reset, they do not rewrite DNA sequence, and none of them lets an organ send an instruction back to its gene. Lamarck's specific mechanism remains retired.

### Phenotype and genotype: which one does selection see?

**Genotype** is an individual's allele composition; **phenotype** is everything observable about it — structure, physiology, behaviour, development. The relationship is many-to-many:

```
                 PHENOTYPE
                     ▲
      genotype ──────┤
      environment ───┤
      developmental  │
      chance ────────┘
```

Three consequences follow, each examinable:

1. **The same genotype can give different phenotypes** in different environments — human skin pigmentation under different UV exposure, or a plant's leaf form in sun versus shade. No allele changed; the phenotype did.
2. **Different genotypes can give the same phenotype** — so a trait's presence tells you nothing certain about the alleles behind it.
3. **Genetic variation can hide behind a constant phenotype** (cryptic variation) until environmental stress exposes it. Selection, operating on phenotypes, cannot see the hidden part.

## Fitness: relative reproductive success

Formally, the fitness of a genotype is its contribution to the next generation's gene pool **measured against the other genotypes present**. Biologists write relative fitness as *w*, setting the best-performing genotype in that environment to *w* = 1, and the **selection coefficient** *s* = 1 − *w* as the deficit of everything else.

| Genotype | Phenotype in this example | Offspring produced | Relative fitness *w* | Selection coefficient *s* |
| --- | --- | --- | --- | --- |
| AA | Fully resistant | 100 | 1.0 | 0.0 |
| Aa | Partially resistant | 80 | 0.8 | 0.2 |
| aa | Susceptible | 50 | 0.5 | 0.5 |

Four properties of this measure are worth holding on to:

- **Relative, not absolute** — a genotype producing 50 offspring in a bad year can still have *w* = 1 if everything else produced fewer; only the ranking matters.
- **Environment-specific** — the same genotype has different *w* in a malarial region and a temperate one.
- **Reproduction, not survival, is the currency** — an individual who lives to 110 without offspring has fitness zero.
- **Measured across a life cycle**, not a snapshot: early and late reproduction trade against each other.

Strength, health, and intelligence can all raise fitness in a given environment, but only as means — none of them is the definition, and that misreading is the most common error in exam questions.

## Adaptation: a population-level fit to the environment

"Adaptation" is used in three distinct senses, and separating them prevents most arguments about it:

1. **A trait** shaped by natural selection for its current function — the eye is an adaptation for image formation.
2. **The process** by which a population becomes better matched to its environment over generations.
3. **The state** of being well matched (adaptedness) at a given moment.

Only the second sense is what evolution *does*, and three rules follow:

- **Populations adapt; individuals do not** — an individual never changes its allele frequencies.
- **Adaptation is retrospective.** A trait counts as an adaptation because selection shaped its current function; a trait co-opted later for a new job (an **exaptation** — feathers, plausibly first for insulation) was not designed for that use.
- **Adaptedness is never permanent or perfect** — environments change faster than selection tracks, trade-offs cap improvement, and variation must exist to act on. "Perfectly adapted" is always wrong; "better matched than the previous generation, here" is right.

### Trade-offs: why no organism is optimised without limit

Every benefit costs something, and the cost is what stops selection from producing an unconstrained optimum. The classic case is **sickle haemoglobin**, which you will meet again in [04 — Genetics](../04-genetics/):

```
HbA/HbA   normal haemoglobin          → full susceptibility to P. falciparum malaria
HbA/HbS   sickle trait                 → parasite growth impaired in red cells
                                        → survival advantage where malaria is endemic
HbS/HbS   sickle-cell disease          → severe haemolytic anaemia, organ damage
                                        → strongly reduced fitness without treatment
```

| Environment | HbA/HbA fitness | HbA/HbS fitness | HbS/HbS fitness |
| --- | --- | --- | --- |
| Malaria endemic | High | **Highest** — heterozygote advantage | Very low |
| No malaria | Highest | Slightly reduced (anaemia cost) | Very low |

No genotype wins everywhere, so the HbS allele settles at an **equilibrium frequency** set by the balance of benefit and cost — around 10–20% in parts of sub-Saharan Africa. The allele is neither "good" nor "bad"; it is a trade-off resolved by local conditions. The same logic applies to the peacock's tail, to delayed reproduction, and to the energetic expense of a large brain: **selection maximises net reproductive output, never any single trait.**

## Sexual selection: a fitness modifier that can oppose natural selection

Darwin's second mechanism handles a problem natural selection alone explains poorly: traits that reduce survival yet spread. **Sexual selection** is differential reproductive success arising from mating rather than survival, in two forms:

- **Intrasexual selection** — competition within one sex, usually male: antlers, size, combat, territory defence.
- **Intersexual selection** — choice by one sex, usually female: the peacock's tail, birds-of-paradise plumage, courtship song.

Why an expensive, predation-attracting ornament is an honest signal is explained by the **handicap principle**: only an individual in good condition can afford a costly ornament and survive anyway, so the ornament reliably advertises parasite resistance and foraging ability.

The structural point is that the two can pull in **opposite directions** — bright colour and large antlers raise mating success while lowering survival, so net fitness is a product:

```
net reproductive success = survival to mating × mating success
                           (natural selection)   (sexual selection)
```

Sexual selection is not a separate theory of evolution — it is a mode of the same differential reproduction, operating on a different currency.

## Why it matters in medicine and the real world

**Antibiotic resistance is a variation story before it is a treatment story.** A resistant mutant, or a strain carrying a resistance plasmid, must **already exist** before the drug arrives; the drug does not create resistance, it removes the susceptible competitors and leaves the variant to reproduce. The targets involved are the ones from [07 — Cells](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md); the clinical picture is developed in [07 — Microbiology](../07-microbiology/).

**Sickle cell is medicine's standing lesson in trade-offs.** Public health programmes in malaria-endemic regions weigh the anaemia cost of HbS against its protective effect — which is why carrier state is common, why newborn screening exists, and why the allele's frequency differs sharply between West Africa and the largely unselected African-American population.

**Pharmacogenetic variation is heritable variation with a dose attached.** Allelic variants of CYP2C19 and CYP2D6 change how quickly a patient activates or clears a drug — poor metabolisers accumulate toxicity, ultrarapid metabolisers lose efficacy. Dosing is individualised because variation in drug handling is DNA sequence, inherited, in exactly the sense this chapter defines.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Variation and adaptation mean the same thing" | **No.** Variation is the raw differences present; adaptation is the *outcome* of selection sorting them. A population can be highly variable and poorly adapted. |
| "The individual adapts during its lifetime" | Individuals **acclimatise or develop**; populations adapt. Adaptation in the evolutionary sense means allele frequency change across generations. |
| "Fitness means strength or health" | Fitness is **relative reproductive success** — offspring contributed relative to others, in a specific environment. |
| "Mutations happen because the organism needs them" | Mutations arise during replication and repair, **before and independently of need**. Selection acts on the result; it does not direct the origin. |

## Key facts

- Three requirements for natural selection: **variation, differential reproduction, heritability** — remove any one and evolution by selection stops.
- **Mutation is the only source of new alleles**; crossing over, independent assortment, random fertilisation, and gene flow only shuffle or transfer existing ones.
- **Lamarck fails mechanistically**: somatic changes do not reach the germ line (Weismann barrier), and mutation is random with respect to need.
- **Phenotype = genotype + environment + developmental chance**; selection acts on phenotype, inheritance runs through genotype.
- **Fitness = relative reproductive success**, environment-specific, measured in offspring — not strength, not survival alone.
- **Adaptation is population-level and retrospective**: populations adapt over generations; traits are adaptations because selection shaped their current function.
- **Trade-offs cap optimisation** — sickle heterozygote advantage: the same allele is beneficial in one environment and costly in another.
- **Sexual selection** can spread traits that lower survival, because net fitness = survival × mating success.
- **Acquired variation is invisible to selection**; only heritable variation changes allele frequencies.
- Standing genetic variation is the raw material for **antibiotic resistance and pharmacogenetic dosing**.

## Practice questions

**1. Which of the following can create an allele that has never existed in a population?**

A. Independent assortment during meiosis
B. Crossing over between homologous chromosomes
C. A point mutation during DNA replication
D. Random fertilisation of two gametes

**Answer: C**

Explanation: Only mutation alters DNA sequence and can therefore generate a genuinely new allele. Independent assortment rearranges whole chromosomes, crossing over swaps segments between homologues, and random fertilisation combines two existing sets of chromosomes — all three shuffle variation that is already present, and none invents new genetic information. This distinction is why mutation is called the ultimate source of all genetic variation while recombination is called the source of new combinations.

---

**2. A marathon runner trains for years and improves her running economy. Her children are not born with that improvement. This is because**

A. Acquired physiological changes occur in somatic cells and do not rewrite germ-line DNA
B. Athletic ability is not heritable in any species
C. Her gametes lacked oxygen during training
D. Natural selection eliminates athletic traits

**Answer: A**

Explanation: Training alters muscle, tendon, mitochondria, and neural control — all somatic changes. The DNA in ovaries and eggs is a separate copy held behind the Weismann barrier and is not rewritten by use or disuse, so offspring inherit sequence, not the parent's acquired physiology. B is false: many components of athletic capacity (VO₂ max, muscle fibre composition) do have heritable components; the point is that the training effect itself is not one of them. C and D describe mechanisms that do not exist.

---

**3. In evolutionary terms, an organism's fitness is best defined as**

A. Its physical strength relative to competitors
B. Its probability of surviving to old age
C. Its relative contribution to the next generation's gene pool through offspring
D. Its health as measured by a physician

**Answer: C**

Explanation: Fitness is a measure of reproductive output relative to other individuals in the same environment — it is the currency natural selection sorts. Survival matters only insofar as it enables reproduction: an individual who lives long but leaves no offspring has fitness zero, while a short-lived individual with many offspring has high fitness. Strength and health may help achieve reproduction in particular environments, but they are not the definition.

---

**4. Which statement about the sickle cell allele is correct?**

A. It is universally deleterious, so malaria cannot explain its frequency
B. In a malarial environment, heterozygotes have higher fitness than either homozygote
C. Selection in Africa is removing the HbS allele rapidly
D. The allele arose because populations needed malaria protection

**Answer: B**

Explanation: HbA/HbS heterozygotes suffer less severe malaria than HbA/HbA while avoiding the severe anaemia of HbS/HbS, giving them the highest relative fitness where malaria is endemic — heterozygote advantage, a balanced polymorphism, not a transient one. C is wrong because the protective benefit maintains the allele; B's environment-dependence is exactly why the same allele carries a net cost where malaria is absent. D repeats the retired idea that mutations arise in response to need.

---

**5. Why can a peacock's tail spread through a population even though it impairs flight and attracts predators?**

A. Peahens do not actually prefer it
B. Sexual selection favours it because it signals condition, and the mating benefit outweighs the survival cost
C. It is not heritable
D. Predators avoid bright colours

**Answer: B**

Explanation: The tail is an honest signal — only a male in good condition can pay the cost of growing and carrying it — so females choosing it gain viability genes for their offspring. Net reproductive success is the product of survival and mating success, and here the increase in mating success exceeds the decrease in survival. The trait is heritable (C false), preference is real (A false), and there is no general predator avoidance of bright colour (D false).

---

**6. Which of the following is a correct pairing of source and consequence?**

A. Crossing over — creates brand-new alleles
B. Gene flow — introduces new alleles only if mutation occurs during migration
C. Independent assortment — produces new combinations of existing alleles
D. Mutation — shuffles existing alleles between homologues

**Answer: C**

Explanation: Independent assortment at metaphase I randomises which parental chromosome goes to which gamete, generating new combinations of existing alleles. Crossing over also makes new combinations but does not create new alleles (A); gene flow can import alleles that are new *to the receiving population* without any mutation (B); and mutation changes sequence rather than shuffling it (D).

---

**7. Which of the following best distinguishes variation from adaptation?**

A. Adaptation is any inherited difference; variation is any visible difference
B. Variation is the set of differences present; adaptation is a trait (or a population's fit) produced by selection acting on those differences
C. Variation is always beneficial, whereas adaptation is always harmful
D. The two words are interchangeable in evolutionary biology

**Answer: B**

Explanation: Variation is the raw material — the differences in phenotype and genotype that exist in a population regardless of their effects. Adaptation is what selection makes of some of that material: either a specific trait shaped for a function or the population's improved fit to its environment. Variation can be neutral, deleterious, or beneficial, so it is not inherently advantageous (C), and neither word is a synonym for the other (A, D).

---

**8. Which observation would best support the conclusion that a trait under study is heritable rather than acquired?**

A. Individuals who exercise more have larger muscles
B. Offspring raised in a common environment resemble their biological parents more than their adoptive parents
C. The trait is common in the population
D. The trait improves survival

**Answer: B**

Explanation: Heritability is demonstrated when resemblance tracks genetic relatedness while environment is held constant — the logic of twin and adoption studies. A describes an acquired response to training, which is exactly what is *not* inherited. Commonness (C) and survival value (D) say nothing about transmission: a widespread trait may be entirely environmental, and a beneficial trait may still be non-heritable and therefore invisible to selection.
