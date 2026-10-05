# Natural Selection

## Why it matters

Natural selection is the only mechanism in biology that **produces adaptation as a by-product of a blind, algorithmic process.** It has no foresight, no goal, and no blueprint — it is simply the consequence of three facts being true together: organisms vary, variants differ in offspring, and the differences are heritable. From those three facts, allele frequencies shift in a definite direction, and complex design-like structures accumulate over generations.

What makes the mechanism worth studying in detail is its **logical structure**. Darwin's four postulates, written in 1859, map almost exactly onto a modern gene-level statement of the same argument, and the mapping is where most exam questions live. A student who can state "nature selects" but cannot run the chain variation → differential reproduction → heritability → allele frequency change has not understood the mechanism — they have memorised a slogan.

The mechanism also has boundaries: selection cannot build what development will not permit, cannot pay for what trade-offs forbid, and cannot make every trait an optimal adaptation. Knowing where its explanatory power ends is the difference between using adaptationism as a tool and using it as an assumption.

## Darwin's four postulates, then and now

Darwin argued in *On the Origin of Species* by stating four claims and drawing one conclusion. Modern biology restates each at the level of genes and alleles rather than individuals and species — the conclusion is unchanged, but the reasoning becomes testable.

| Darwin's postulate (1859) | Modern gene-level reformulation |
| --- | --- |
| 1. Individuals within a species **vary** | Populations carry standing genetic variation: multiple alleles at many loci |
| 2. Much of this variation is **heritable** | Offspring resemble parents because DNA sequence is transmitted through gametes |
| 3. More offspring are produced than can survive — there is a **struggle for existence** | Resource limits make reproductive output a competition |
| 4. Individuals with favourable variants survive and reproduce **differentially** | Alleles raising relative fitness increase in frequency across generations |

The conclusion, stated in one line:

```
variation + differential reproduction + heritability
   = non-random change in allele frequencies
      = evolution by natural selection
```

Two clarifications keep this from being over-read. First, **selection acts on individuals' phenotypes but is recorded in gene frequencies** — an individual is selected or not; a population evolves or does not. Second, the postulates must *all* hold: variation without heritability (a tan), or heritability without differential reproduction (neutral alleles), each fails to produce selection — which is why exam distractors offer one of the three in isolation.

## The logical chain, step by step

```
1. VARIATION           phenotypes differ among individuals
        ↓
2. DIFFERENTIAL        some phenotypes leave more offspring
   REPRODUCTION        than others (differences in relative fitness)
        ↓
3. HERITABILITY        the advantageous variants are passed on
        ↓
4. ALLELE FREQUENCY    p and q shift in the next generation;
   CHANGE              repeated across generations → evolution,
                        and, if the environment persists, adaptation
```

The chain is **irreversible in direction but not in outcome**: if the environment reverses, selection reverses, and the allele can decline again. Nothing in the mechanism guarantees progress, permanence, or optimality — only a non-random shift while the conditions hold.

## Worked example: industrial melanism in the peppered moth

The peppered moth (*Biston betularia*) remains the cleanest documented case of selection in a wild animal because **every link in the chain was measured** rather than assumed.

**Background.** Before industrialisation the pale form (*typica*) was almost universal and the dark form (*carbonaria*) rare — around 2% in 1848 — caused by a single dominant allele. Moths rest on lichen-covered trunks and birds are the main predators, so the pale moth matches the background and the dark one does not. Then soot from burning coal killed the lichen and blackened bark in industrial districts: the background flipped from pale to dark.

**The mechanism — predation, not pigment preference:**

```
pre-1850, soot-free woodland
   pale lichen background → typica camouflaged, carbonaria conspicuous
      → birds eat dark moths preferentially
         → carbonaria allele frequency ≈ 2%

industrial soot kills lichen, blackens bark
   dark background → now carbonaria camouflaged, typica conspicuous
      → birds eat pale moths preferentially
         → differential reproduction FLIPS DIRECTION
            → carbonaria allele frequency rises to ~95% in polluted areas

Clean Air Acts (1950s–60s) remove the soot
   lichen returns → direction flips back → dark form declines again
```

**The measured allele frequency shift:**

| Period | Environment | Direction of selection | *carbonaria* frequency (typical industrial area) |
| --- | --- | --- | --- |
| Pre-1850 | Pale lichen, clean bark | Against dark form | ~0.02 |
| 1850–1950 | Soot-blackened bark | **For dark form** | ~0.95 |
| Post-1960 | Lichen returns | Against dark form | Falling again |

Three points are often lost. **Selection acted on phenotype via a predator**, not on the allele directly — the moth never chose its colour. **The trait was not newly created by pollution**: the dark allele was already present as standing variation, so the response was immediate. And **the change is reversible** — exactly what happened when legislation cleaned the air, showing that selection tracks the current environment rather than driving toward a fixed ideal.

## Antibiotic resistance: selection in real time

Industrial melanism takes decades to notice. Antibiotic resistance takes days, which is why it is the mechanism's most medically urgent demonstration — and why the steps are worth memorising in order.

```
1. STANDING VARIATION     a small number of bacteria already carry a resistance
                          allele (or resistance plasmid) — mutation existed BEFORE
                          the drug; nothing is caused by the drug
        ↓
2. SELECTION              antibiotic kills or inhibits susceptible cells
        ↓
3. SURVIVORS REPRODUCE    resistant cells face no competition for nutrients
                          → binary fission every ~20 minutes, unchecked
        ↓
4. ALLELE FREQUENCY SHIFT resistance allele approaches fixation in the colony
        ↓
5. THERAPEUTIC FAILURE    the drug that once cleared the infection no longer works
```

The targets are the ones from [07 — Cells](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md) — peptidoglycan synthesis, the 70S ribosome, DNA gyrase — which is also why resistance mutations that change those targets can carry a fitness cost when the drug is absent. Everything clinical about the problem (mixture of mechanisms, plasmid spread, stewardship) is developed in [07 — Microbiology](../07-microbiology/).

The two features that make it selection: **the drug selects, it does not create** — an antibiotic does not direct any mutation toward resistance — and **the outcome is a population-level frequency change**, never an individual bacterium "learning" to tolerate the drug.

## The three shapes of selection

How selection reshapes a trait's distribution depends on which phenotypes are favoured. The graphs below are ASCII sketches of frequency curves — in each, the solid curve is before selection and the dashed curve is after.

```
STABILISING                     DIRECTIONAL                 DISTRUPTIVE
(both extremes selected against) (one extreme favoured)      (both extremes favoured,
                                                               centre selected against)

count                           count                       count
 │   ▄█▄                         │      ▄█▄                 │  ▄█▄      ▄█▄
 │  ████▄                        │     █████                │ █████    █████
 │ ▟██████▙                      │    ██████▄               │▟██████▙▟██████▙
 │▟██████████▙▄▄                 │   ████████▄▄             │▄████████████████▄
 └──────────────── trait         └────────────── trait      └──────────────── trait
   ▔▔▔▔▔▔▔▔▔▔▔                   ▔▔▔▔▔▔▔▔▔▔▔▔▔            ▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔
   (narrower, same mean)          (mean shifted)             (variance increased)
```

| Mode | What is favoured | Effect on distribution | Textbook example |
| --- | --- | --- | --- |
| **Stabilising** | The intermediate phenotype | Mean unchanged; variance **decreases** | Human birth weight — very low and very high weights both raise neonatal mortality |
| **Directional** | One extreme phenotype | Mean **shifts** toward that extreme | Industrial melanism; antibiotic resistance; giraffe neck length under food competition |
| **Disruptive** | Both extremes, intermediates penalised | Variance **increases**; can split a population | Seed-cracking finches with small vs large beaks; possibly a first step toward speciation |

Note the symmetry with drift: selection **is directional by definition** (it has a preferred phenotype), whereas drift moves frequencies without preference. A fourth pattern — **balancing selection** — keeps both alleles (heterozygote advantage, as with sickle cell from [01 — Variation](01-variation-fitness-adaptation.md)) and maintains variation rather than removing it.

## Constraints on selection: why not everything is optimal

Selection is a tinkerer working with what already exists, and three classes of constraint limit what it can produce.

**Phylogenetic constraint.** Evolution works on the existing body plan. Humans inherit the vertebrate eye wiring with the retina placed backwards and a blind spot where the optic nerve exits; the octopus eye, built on a different lineage, has none — evidence that the vertebrate version is a historical accident, not an optimum. Snakes likewise retain vestigial pelvic structures from limbed ancestors.

**Developmental (structural) constraint.** Some phenotypes are simply not on the menu. Developmental pathways channel variation into available forms — four limbs in tetrapods, five digits as the default tetrapod hand, segmental body plans. Selection can modify a hand into a flipper, a wing, or a hoof; it cannot build a wing from a structure development cannot make.

**Energetic and trade-off constraint.** Every trait costs resources and carries opportunity costs — the sickle cell trade-off from chapter 01, the peacock's tail, immune activation, endothermy, and large brains all drawing on one metabolic budget. Selection optimises **allocation**, never any single trait in isolation.

```
benefit of trait ──────────────────▶
cost of trait  ───────────────────▶
net fitness    = benefit − cost   → optimum is where the difference peaks,
                                     not where benefit alone peaks
```

### The adaptationism caution

Treating every trait as an adaptation produced by selection for its current function is a **hypothesis, not a default.** Gould and Lewontin's classic critique (the "spandrels" paper) pointed out that a trait may exist because it is a by-product of something else (spandrels — the triangular spaces produced by arches, decorated but not selected for decoration), may be neutral and fixed by drift, may be a constraint, or may be a legacy of ancestral function no longer under selection.

The discipline is: **before asking "what is this trait for?", ask "does it need a selective explanation at all?"** Adaptationism is a productive research programme when it generates testable stories; it is a fallacy when it merely narrates whatever exists.

## Why selection acts on individuals but changes populations

This is the single most-repeated conceptual point in the section, and it is worth stating with its arithmetic.

- Selection **cannot** act on a population as a whole — it has no physiology. It acts on **individuals**: each is either leaving more, average, or fewer offspring.
- Individuals **do not evolve**. Their allele frequencies are fixed at conception; they either pass genes on or they do not.
- Populations evolve because the differential reproduction of many individuals **accumulates** into a shifted allele frequency distribution.

```
generation 1:  p = 0.30 (aa favoured, s = 0.4)
   → differential reproduction this season only
generation 2:  p = 0.22
generation 3:  p = 0.15
   ... each generation's shift is the sum of thousands of individual
       reproductive events, never a change inside any one organism
```

The direction is set by the environment; the magnitude by the strength of selection, the heritability of the trait, and the availability of genetic variation.

## Why it matters in medicine and the real world

**Antibiotic stewardship is applied population genetics.** Every course of antibiotics is a selection event: incomplete courses, agricultural growth promoters, and over-the-counter access all raise the strength of selection and accelerate resistance. The mechanism predicts the intervention — reduce the selection pressure, and the costly resistance allele declines. Link [07 — Microbiology](../07-microbiology/) for the resistance mechanisms themselves.

**Cancer is somatic natural selection.** A tumour is a population of cells under selection: variation arises by mutation and chromosome missegregation, differential reproduction is uncontrolled division, and heritability is the transmission of mutations to daughter cells. Chemotherapy is the selection pressure — and relapse with resistant clones is the predicted outcome, which is why combination therapy (multiple simultaneous pressures) is used. The checkpoint failures that generate the variation are in [10 — Cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md).

**Vaccine design anticipates selection.** Influenza and HIV escape vaccine-induced immunity by the same logic as bacteria escape drugs: standing antigenic variation is sorted by an immune pressure. Strain selection for the annual vaccine is a bet on which variant will be favoured next season.

**Public health traits under selection in humans.** Sickle cell trait in malaria zones, G6PD deficiency and malaria, and — where documented — shifts in allele frequency under modern medical care (which removes some previously strong selection) are all chapter-2 mechanisms running in our own species. The genetics sit in [04 — Genetics](../04-genetics/).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The drug/pathogen causes the resistant mutant" | The mutation arises first and **randomly**; the drug **selects** the variant that already existed. |
| "Individuals evolve during their lives" | Individuals are selected; **populations** evolve through allele frequency change across generations. |
| "Selection is goal-directed" | It has no foresight or endpoint — it only favours whatever works **now**, in the current environment. |
| "Selection acts on genotypes" | It acts on **phenotypes**; genotypes are dragged along only insofar as they built the phenotype and are heritable. |
| "The fittest always survive" | Fitness is **relative and probabilistic** — a favourable variant can still be eaten; it just leaves more offspring on average. |
| "Stabilising selection creates new traits" | It **removes extremes** and narrows an existing distribution; it does not generate variation. |
| "Every trait is an adaptation" | Traits may be by-products, constraints, or drift products — adaptationism is a hypothesis to test, not a premise. |
| "Lamarckian use-and-disuse is a form of natural selection" | Use-and-disuse proposes acquired change; natural selection requires **heritable** variation and cannot see an acquired trait. |

## Key facts

- Darwin's four postulates in modern terms: **standing genetic variation, heritability, overproduction of offspring, differential reproductive success** — all four must hold.
- The chain: **variation → differential reproduction → heritability → allele frequency change**, repeated over generations.
- Industrial melanism: **predation by birds on a changed background** flipped selection direction; the dark allele was pre-existing standing variation, and frequencies reversed when the air was cleaned.
- Antibiotic resistance sequence: **mutation exists → drug removes susceptible cells → survivors reproduce unchecked → frequency shift → treatment failure**.
- **Stabilising** selection narrows a distribution; **directional** shifts the mean; **disruptive** increases variance and can split a population.
- Selection is **directional by definition**; drift is not — it moves frequencies with no preferred phenotype.
- **Constraints**: phylogenetic history, developmental possibility, and energetic trade-offs all cap what selection can achieve.
- **Adaptationism is a hypothesis**, not a default — by-products (spandrels), constraints, and neutral traits need no selective story.
- Selection acts on **individuals**; only **populations** change allele frequencies.
- Standing variation, not induced mutation, is why responses to selection are fast — the same reason antibiotic resistance appears within a single infection.

## Practice questions

**1. Which combination of conditions is required for natural selection to change a population?**

A. Mutation, genetic drift, and migration
B. Variation, differential reproductive success, and heritability of the variation
C. Sexual selection, a changing environment, and large population size
D. Overproduction of offspring, mutation, and acquired characteristics

**Answer: B**

Explanation: Selection is defined by three conditions being true together — individuals vary, the variants differ in offspring produced, and offspring resemble parents. Remove any one (for example, variation with no heritability, as with a suntan) and no allele frequency change follows. A describes mechanisms of evolution generally but not selection specifically, C is too narrow, and D includes acquired characteristics, which by definition cannot be inherited.

---

**2. In the peppered moth example, why did the dark form increase in frequency during the industrial period?**

A. Soot caused mutations producing dark pigment
B. Individual moths darkened their wings to match the bark
C. Bird predation removed the more conspicuous pale form on darkened trunks, leaving dark moths to reproduce more
D. The dark allele made moths physiologically stronger

**Answer: C**

Explanation: The mechanism is differential predation: on soot-blackened, lichen-free bark the pale *typica* form was conspicuous and eaten more, so the *carbonaria* allele was passed on more often. Pollution did not create the allele (A) — it was already present at about 2% — and moths do not alter their own pigment within a lifetime (B). Nothing about the allele confers strength (D); its effect is purely visual against a particular background.

---

**3. A patient finishes only half a course of an antibiotic. Which statement best explains the risk?**

A. The remaining drug becomes chemically inactive
B. Surviving partially resistant bacteria reproduce under reduced competition, increasing the frequency of resistance alleles in the population
C. The bacteria learn to tolerate the drug
D. The incomplete dose causes new mutations directed at the drug target

**Answer: B**

Explanation: Stopping early removes the pressure while susceptible competitors are still present in reduced numbers, so resistant survivors reproduce with less competition and shift the population's allele frequencies toward resistance. This is selection acting on standing variation, not instruction — mutations arise randomly and before treatment (D false), bacteria acquire no memory of the drug (C false), and the drug's chemistry is irrelevant here (A false).

---

**4. Stabilising selection on human birth weight is illustrated by the fact that**

A. Very low and very high birth weights both carry higher neonatal risk, so intermediate weights are favoured
B. Each generation's average birth weight rises steadily
C. Only the heaviest babies survive
D. Birth weight is not heritable

**Answer: A**

Explanation: Stabilising selection acts against both extremes while preserving the intermediate — here it narrows the distribution without moving the mean, reducing variance over generations. Directional selection would raise the mean (B, C), which is not what is observed. Birth weight does have a substantial heritable component (D), which is precisely what allows the selection to work.

---

**5. The three requirements of natural selection map onto Darwin's postulates. Which modern statement matches the "heritability" postulate?**

A. More offspring are produced than can survive
B. Individuals within a species vary
C. Offspring resemble parents because DNA is transmitted through gametes
D. Resources in the environment are limited

**Answer: C**

Explanation: Heritability is the postulate that variation passes from parent to offspring — in modern terms, through DNA sequence carried in gametes, which is covered in [12 — Meiosis](../03-cellular-processes/12-meiosis.md). Overproduction (A) and resource limitation (D) make up the struggle for existence; variation (B) is a separate postulate. Without transmission, differential survival leaves no trace in the gene pool.

---

**6. Which scenario is an example of disruptive selection?**

A. Average-sized seeds being favoured over very small and very large ones
B. In a population of finches, both very small and very large beaks are favoured while intermediate beaks are selected against
C. The mean beak size increasing over generations of drought
D. An allele frequency remaining constant because heterozygotes are most fit

**Answer: B**

Explanation: Disruptive selection penalises the intermediate and favours both extremes, increasing variance and potentially splitting a population into two — a possible route to speciation. A is stabilising, C is directional, and D describes balancing (heterozygote advantage) selection, which maintains rather than increases variation.

---

**7. Why is the vertebrate eye's blind spot better explained as a constraint than as an adaptation?**

A. Vision is not important to vertebrates
B. The retina's inverted wiring is a developmental legacy of the vertebrate lineage, and selection could not re-engineer it without large intermediate costs — the octopus eye lacks the blind spot
C. The blind spot improves visual acuity
D. Mutations affecting eye development are always lethal

**Answer: B**

Explanation: The photoreceptors face backwards and the optic nerve exits in front of them because that is how the vertebrate retina developed; re-routing would require a costly intermediate stage, so the lineage is stuck with it. The camera-style eye of octopods, built on a different ancestry with receptors facing forward and no blind spot, shows the outcome is not an optimum but a historical path. Options A, C, and D are all factually wrong.

---

**8. Which statement correctly describes the level at which selection operates?**

A. Individuals evolve during their lifetime in response to the environment
B. Selection acts on individual phenotypes, but allele frequency change occurs only in populations across generations
C. Populations are units of physiology and are therefore selected directly
D. Genotypes are selected independently of the phenotype they produce

**Answer: B**

Explanation: Individuals are the entities that live, reproduce, or fail to — but an individual's allele frequencies are fixed and cannot change. Only when many individuals reproduce differentially does the population's gene pool shift, and only across generations. A confuses acclimatisation with evolution, C gives populations a physiology they do not have, and D is wrong because selection can only see a genotype through the phenotype it builds.

---

**9. What is the main criticism of "adaptationism"?**

A. It assumes traits can have selective value
B. It treats every trait as shaped by selection for its current function, ignoring by-products, constraints, and drift
C. It denies that selection occurs
D. It claims that mutations arise in response to need

**Answer: B**

Explanation: The adaptationist programme tells a selective story for whatever exists — the spandrel critique's point is that a trait may instead be a structural by-product, a developmental constraint, or a neutral feature fixed by drift, none of which requires a function. It does not deny selection (C) and does not endorse directed mutation (D); it is a warning that "what is this for?" must be tested rather than assumed.

---

**10. In antibiotic therapy, combination treatment with two or more drugs is used because**

A. Two drugs always chemically neutralise each other's side effects
B. Simultaneous independent resistance mutations are far less likely than resistance to a single drug, so selection has a much smaller target
C. Bacteria cannot mutate at all when exposed to multiple drugs
D. Drugs become more potent when mixed

**Answer: B**

Explanation: Resistance to one drug usually requires a single mutation or plasmid; resistance to two drugs given together requires both, and if they act on different targets the mutations must co-occur in the same cell — a probability that is the product of two small numbers. Selection still acts, but the standing variation for dual resistance is far rarer. Bacteria mutate regardless (C), and neither chemical neutralisation (A) nor added potency (D) is the mechanism.
