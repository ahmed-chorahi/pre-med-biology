# Population Growth

## Why it matters

A **population** is the lowest level of ecological organisation at which medicine operates. Patients are individuals, but epidemics, resistance, pests, and extinctions are properties of groups: how many there are, how fast the number changes, and what stops it changing. Vaccination coverage, quarantine length, insecticide rotation, fishery quotas, and captive-breeding targets are all interventions on a growth equation. The levels placing the population between organism and community are in [02 — Biological organisation](../00-foundations/02-biological-organization.md) and [01 — Levels of organization](01-levels-of-organization.md).

The two models below are usually sold as ecology, which is misleading. **Exponential** and **logistic** growth are the same mathematics wherever numbers multiply and resources run short: bacterial colony formation, spread within a ward, tumour expansion, national demographics, and algal blooms all run on the two equations developed here. A bacterium doubling every twenty minutes and a country doubling every thirty-five years differ in scale, not in form — hence the generation-time arithmetic in [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md) reappears with different units.

What makes the models examinable is not the algebra but the **mechanism behind each term**: why animals clump rather than spread evenly, what (K − N)/K measures, why a frost kills regardless of crowding while a famine does not. Each section states a quantity, then gives the causal chain producing it — because the chain, not the formula, transfers to a new situation.

## Population fundamentals

### What counts as a population

A **population** is all the individuals of **one species**, in **one area**, at **one time**. Change any qualifier and you have a different object:

| Level | Definition | Contrast |
| --- | --- | --- |
| **Population** | One species, one area, one time | Every *Escherichia coli* in one patient's gut at sampling |
| **Community** | All populations interacting in one area | The whole gut flora — *E. coli*, *Bacteroides*, candida |
| **Metapopulation** | Local populations linked by migration | Nest patches in a fragmented wood exchanging breeding birds |

A population therefore has properties an individual lacks: **density**, **age structure**, birth and death rates, a **distribution pattern**. And because the unit is local, a species can be secure worldwide while every one of its populations is tiny — the situation that drives extinction risk.

### Measuring density: quadrats and mark–recapture

**Population density** is individuals per unit area or volume. **Abundance** is the total count N; density divides it by space.

**Quadrats** suit organisms that stay put: place a fixed frame at random, count, repeat, average, multiply by total area.

```
10 random 1 m² quadrats: 3, 5, 4, 6, 2, 5, 4, 7, 3, 6
   → mean = 45 / 10 = 4.5 plants per m²
   → woodland = 2 000 m²  →  4.5 × 2 000 = 9 000 plants
```

**Mark–recapture** suits animals that move: mark and release a first sample, let them mix, then recapture and count marks. The **Lincoln–Petersen index** assumes marked individuals disperse evenly, so the marked fraction of the second sample equals the marked fraction of the whole population:

$$N = \frac{M \times n}{R}$$

M = marked and released, n = total in the second sample, R = marked recaptured.

**Worked example:**

```
first capture:  M = 50 fish caught, fin-clipped, released
second capture: n = 40 fish caught, of which R = 8 carry a clip

N = M × n / R = 50 × 40 / 8 = 2 000 / 8 = 250 fish
```

| Assumption | Failure and direction of bias |
| --- | --- |
| Marks are retained and harmless | Marks lost or marked fish eaten → R low → **N overestimated** |
| Marked fish mix fully first | Recaptured too soon → R high → **N underestimated** |
| No births, deaths, or migration between samples | The ratio no longer describes one closed group |
| Second sample is random | Netting a school of marked fish → R high → N overestimated |
### Spatial distribution: three patterns, three mechanisms

The pattern is diagnosed from the mechanism that produced it — the examinable part.

| Pattern | Appearance | **Mechanism** | Examples |
| --- | --- | --- | --- |
| **Clumped** | Groups with gaps between; **by far the most common** | Resources are patchy, so individuals gather where food, water, shade, or nest sites occur; reinforced by social grouping and offspring staying near parents | Herds, schools, weeds under a fallen tree, biofilm microcolonies, every infectious cluster |
| **Uniform** | Near-equal spacing | **Territoriality or interference competition**: each individual defends a radius, so neighbours cannot settle closer | Desert shrubs, nesting gannets, mangrove stems, penguins at pecking distance |
| **Random** | Haphazard placement | Resources evenly spread **and** no attraction or repulsion between individuals — the three conditions rarely hold together | Barnacles on uniform rock, wind-dispersed plants on flat sand |

```
CLUMPED   patchy resource → aggregation where it occurs → social grouping
          → offspring born where parents already are → CLUSTERS   [most common]

UNIFORM   limited resource per individual + defence of a radius
          → settlers too close are displaced or die → EVEN SPACING

RANDOM    even resources AND no territoriality AND no attraction
          → each position independent → HAPHAZARD          [rare]
```

Clumped therefore signals a patchy environment, uniform signals individuals pushing each other apart, random signals neither force acting.

## Demographic accounting

### The population balance equation

Population size changes for exactly four reasons:

$$\frac{dN}{dt} = (B + I) - (D + E)$$

| Term | Meaning | Effect on N |
| --- | --- | --- |
| **B** — births | New individuals produced | Raises |
| **I** — immigration | Arriving from elsewhere | Raises |
| **D** — deaths | Individuals dying | Lowers |
| **E** — emigration | Leaving for elsewhere | Lowers |

For a **closed** population (I = E = 0), dN/dt = B − D, and dividing by N gives the **rate of natural increase**:

```
r = b − d     (per-capita birth and death rates)

b = 0.035/yr, d = 0.014/yr → r = +0.021/yr → grows 2.1 % per year
b = 0.016/yr, d = 0.018/yr → r = −0.002/yr → slowly shrinks
```

The equation does not say *why* births or deaths changed; that needs the next sections.

### Age structure and population pyramids

An **age structure** splits the population into **pre-reproductive**, **reproductive**, and **post-reproductive** classes. Because the pre-reproductive cohort must pass through the breeding years, a pyramid is a **forecast one generation ahead**.

| Pyramid | Signature | **Mechanism** | Prediction |
| --- | --- | --- | --- |
| **Growing** | Broad base, narrowing top | Each cohort larger than the one before | Growth continues **15–25 years** even if fertility falls now — **population momentum** |
| **Stable** | Columns roughly equal until mortality rises | Births ≈ deaths; cohorts similar in size | Numbers hold; growth near zero |
| **Declining** | Narrow base, middle-age bulge | Births below replacement; smaller young cohorts | Long-term decline, rising dependency ratio |

A wide base means growth is still coming, a narrow base means decline is coming: the pyramid predicts the future more reliably than the present.

### Survivorship curves

A **survivorship curve** plots the proportion of a cohort alive against age, and each type is the arithmetic consequence of a different life history — a different answer to *how many offspring, how big, how guarded*.

| Type | Death pattern | Life-history explanation | Examples |
| --- | --- | --- | --- |
| **I** | Concentrated **late**, after reproduction | Few offspring, heavy parental investment, protected juveniles; deaths are mostly senescence | Humans (with care), elephants, whales, large mammals |
| **II** | **Constant** per-capita rate at every age | Mortality is **extrinsic and age-blind**: predation, accident, weather strike equally at any age | Birds, hydra, adult rodents |
| **III** | Overwhelmingly **in early stages** | Huge numbers of tiny offspring, no parental care, no protection — survivors then face low adult risk | Oysters, most invertebrates, most fish, annual plants |

```
Type I   low early risk → most reach maturity → deaths rise with age
Type II  constant hazard → survivors decline at a constant exponential rate
Type III mass early die-off → a small resistant minority persists to breed
```

The curve shows **where selection is strongest**: on the egg and larva (III) or on adult ability and late-life maintenance (I). The energetic trade-off forcing the choice runs through [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md).

## Exponential growth: dN/dt = rN

**Exponential growth** occurs when resources are effectively unlimited. The rate of change is proportional to the number already present:

$$\frac{dN}{dt} = rN$$

**r** is the **intrinsic rate of increase** — the maximum per-capita rate under ideal conditions, equal to b − d.

| Feature | Meaning |
| --- | --- |
| **J-shaped curve** | Slow at first, then abruptly steep |
| **No ceiling** | There is no K in the equation; N can only rise |
| **Acceleration** | dN/dt grows with N, so the population gets faster as it gets bigger |

### Doubling-time arithmetic

The population doubles when rt = ln 2, so the **doubling time** is:

$$t_d = \frac{\ln 2}{r} \approx \frac{0.693}{r}$$

**Worked example 1 — human demography:**

```
birth rate = 35 per 1 000/yr = 0.035
death rate = 14 per 1 000/yr = 0.014
r = b − d = 0.021 per year

t_d = 0.693 / 0.021 = 33 years

N₀ = 10 000 → 20 000 (33 y) → 40 000 (66 y) → 80 000 (99 y)
```

The **rule of 70** gives the same answer quickly: doubling time ≈ 70 ÷ percentage growth rate = 70 ÷ 2.1 ≈ 33 years.

**Worked example 2 — the same equation in bacterial units:**

```
E. coli, generation time g = 20 min
r = 0.693 / (1/3 h) = 2.08 per hour

one cell at 08:00 → 30 generations × 20 min = 10 hours
N = 2³⁰ ≈ 10⁹ cells by 18:00
```

This is the log phase of the bacterial growth curve in [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md), where generation time sets incubation period and culture time.

### Why exponential growth is always temporary

Exponential growth describes **conditions that destroy themselves:**

```
resources unlimited + no predation, disease, or waste
   → each individual reproduces at maximum rate → dN/dt = rN, curve steepens
      → consumption rises with N → resources deplete, waste accumulates
         → b falls, d rises → effective r declines toward zero
            → growth stops → the population is now limited
```

At 20-minute doubling a single *E. coli* would outmass the planet within days; instead the culture reaches **stationary phase** because nutrients, oxygen, and space run out. That is logistic growth arriving on a laboratory timescale.

## Logistic growth: dN/dt = rN(K − N)/K

The logistic model adds a ceiling — the **carrying capacity**:

$$\frac{dN}{dt} = rN\frac{K - N}{K}$$

| Symbol | Name | Meaning |
| --- | --- | --- |
| r | Intrinsic rate of increase | Maximum per-capita growth under ideal conditions |
| N | Current population size | |
| **K** | **Carrying capacity** | Largest population the environment sustains indefinitely — set by limiting resources, not by the species |
| **(K − N)/K** | **Fraction of capacity remaining** | 1 when N = 0, 0.5 at N = K/2, 0 when N = K |

The middle term is the whole idea: **growth is slowed in proportion to how much of the environment is already used.** At low N it is near 1, so growth is almost exponential; near K it collapses to 0.

**Worked example — a lake, K = 500 fish, r = 0.1/yr:**

```
dN/dt = rN(K − N)/K

N = 100:  0.1 × 100 × 400/500 = 10 × 0.80 = 8.0 fish/year
N = 250:  0.1 × 250 × 250/500 = 25 × 0.50 = 12.5 fish/year  ← maximum
N = 400:  0.1 × 400 × 100/500 = 40 × 0.20 = 8.0 fish/year
N = 480:  0.1 × 480 ×  20/500 = 48 × 0.04 = 1.92 fish/year
N = 500:  0.1 × 500 ×   0/500 = 50 × 0.00 = 0            ← at K
```

Two results worth memorising: growth is zero at N = 0 and at N = K, and **peaks at N = K/2**, where the maximum rate is rK/4 (0.1 × 500 ÷ 4 = 12.5, above) — which is why **harvest quotas hold populations near K/2**.

| Phase | N relative to K | Behaviour |
| --- | --- | --- |
| Early | N ≪ K | (K − N)/K ≈ 1 → effectively exponential |
| Deceleration | N → K/2 → K | Fraction remaining shrinks; curve bends |
| Equilibrium | N ≈ K | dN/dt ≈ 0; births balance deaths |

### Density-dependent and density-independent regulation

**Density-dependent factors** have a per-capita effect that strengthens as density rises; **density-independent factors** act on individuals regardless of crowding.

| | **Density-dependent** | **Density-independent** |
| --- | --- | --- |
| Per-capita effect | **Increases** with N | Constant at any N |
| Mechanism | Competition, predation, disease, waste | Weather, frost, fire, flood, drought |
| Role | **Regulates** — pushes N back towards K | **Sets the timing** of crashes |
| Examples | Starvation as food per capita falls; parasites spreading in a crowded warren; toxic waste | A late frost killing larvae whether 10 or 10 000 are present |
| Drives N to K? | Yes | No — it can knock N far below K with no feedback |

```
DENSITY-DEPENDENT FEEDBACK
   N rises → per-capita share of food and shelter falls
      → intraspecific competition intensifies → births fall, deaths rise
         → crowding accelerates parasite and waste effects
            → r(1 − N/K) falls to 0 → N stabilises near K   ← REGULATION

DENSITY-INDEPENDENT EVENT
   frost / fire / flood → mortality applied to everyone present
      → N falls with no relationship to crowding → regrowth from low N
         → no regulation, only fluctuation around a mean
```

The two interact: density-independent events usually set the timing of a crash, density-dependent competition decides who survives it.

### Overshoot and dieback

Populations respond to **conditions that existed one or more generations earlier**, so a lag builds in and numbers exceed K before correcting. **Overshoot** is N > K; **dieback** is the crash that follows.

```
momentum from past good conditions → N exceeds K
   → resource base degraded faster than it regenerates
      → starvation, disease, intensified competition
         → dieback: N falls BELOW K → resources recover → growth resumes
            → oscillation around K
```

The classic case: **29 reindeer introduced to St Paul Island in 1944**, no predators, abundant lichen — the herd reached roughly **2 000 by 1963**, overran the lichen, and collapsed to about **100 within three years**. The same shape appears in crashing algal blooms, bacterial decline phase, and predator–prey cycles, treated in [05 — Ecological relationships](05-ecological-relationships.md). Overshoot is the normal outcome of a lag, not a failure of the model.

## Life-history strategies: r-selected and K-selected

Species differ less in whether they obey these equations than in **how they pay for them**. Every individual has a finite energy budget, and a calorie spent on reproduction is a calorie not spent on growth or defence — the trade-off runs through cellular ATP allocation in [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md).

| Trait | **r-strategy** (fast) | **K-strategy** (slow) |
| --- | --- | --- |
| Emphasis | Maximise **r** | Persist near **K**, compete for slots |
| Development | **Fast**, early maturity | **Slow**, delayed maturity |
| Offspring | **Many**, small | **Few**, large |
| Parental care | **Little or none** | **Heavy and prolonged** |
| Age at first reproduction | **Early** | **Late** |
| Lifespan | Short | Long |
| Survivorship | Usually **III** | Usually **I** |
| Population | Unstable: booms and crashes | Stable, hovering near K |
| Examples | Insects, weeds, rodents, bacteria, oysters | Elephants, whales, humans, sharks, albatrosses |

```
FIXED ENERGY BUDGET
   ├─► MANY small offspring, reproduced EARLY → high r
   │      → rapid growth when conditions open, little defence,
   │        high early mortality (type III) → first in, first to crash
   └─► FEW large offspring, reproduced LATE → high competitive ability
          → slow growth, near K, low early mortality (type I)
          → last in, last to disappear when conditions tighten
```

**Modern framing.** The strict dichotomy is usually replaced by a **fast–slow continuum**: species sit on one axis from fast (short life, many offspring, early maturity) to slow (long life, few offspring, late maturity), humans at the slow end. The continuum is preferred because real species fall between the poles, a single species shifts with conditions, and r and K are **parameters of an environment**, not labels on a species. The examinable core stands: **the trade-off is energy allocation, and no organism maximises both offspring number and offspring investment.**

## The human population: demographic transition

Human demography changes asymmetrically: **death rates fall first, birth rates follow decades later.**

| Stage | Birth rate | Death rate | Natural increase | **Mechanism driving the change** |
| --- | --- | --- | --- | --- |
| **1 — High stationary** | High (35–45 ‰) | High (30–40 ‰) | **Near zero** | No contraception; children are labour; infant mortality forces high fertility; famine and epidemic keep deaths volatile |
| **2 — Early expanding** | Still high | **Falls sharply** | **Rapid** | **Sanitation, clean water, vaccination, food supply, and medicine lower mortality first** — birth rates unchanged |
| **3 — Late expanding** | **Falls sharply** | Low | **Slowing** | Urbanisation, female education, contraception, and falling child mortality remove the reasons for large families |
| **4 — Low stationary** | Low (10–15 ‰) | Low (10–12 ‰) | **Near zero** | Small families are the norm; growth continues through momentum of the large younger cohorts |

```
clean water + vaccination + food security + medicine
   → DEATH RATE FALLS FIRST   (medicine acts on death, not birth)
      → more children survive → fewer births needed
         → but custom and farm economics lag a generation
            → URBANISATION + FEMALE EDUCATION + CONTRACEPTION
               → BIRTH RATE FALLS SECOND → the gap (b − d) narrows
                  → growth decelerates → stage 4: near-zero growth, ageing structure
```

**Resource and sustainability implications.** Growth is concentrated in stage-2 and stage-3 countries, so absolute numbers keep rising for decades even if every country reached replacement fertility tomorrow — the **population momentum** visible in any broad-based pyramid. The environmental question is whether eight to ten billion people at rising per-capita consumption stay within the carrying capacities of arable land, freshwater, fisheries, and the atmosphere. Because **K belongs to the resource base rather than the species**, sustainability arguments are always arguments about K: raise it through technology, or lower demand upon it. Stage 5, visible already in parts of eastern Europe and Japan, shows the opposite problem — a constricting pyramid, a shrinking workforce, a rising dependency ratio.

## Relevance to medicine and the real world

**Epidemiology reuses these models wholesale.** R₀ is an exponential-growth parameter: above 1, case numbers follow dN/dt = rN, and pushing the effective reproduction number below 1 runs the same equation backwards. The **herd immunity threshold, p_c = 1 − 1/R₀**, and **generation time** are the arithmetic already built in [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md): generation time sets doubling time, and R₀ sets the vaccination coverage needed. Nothing in an outbreak curve differs qualitatively from the J-curve and S-curve above — only the units change.

**Antibiotic resistance is selection acting on a growing bacterial population.** A partially suppressive dose leaves susceptible cells competing among themselves while resistant mutants expand, and doubling arithmetic decides how fast a clone starting at one cell becomes clinically significant; the mechanism is in [02 — Natural selection](../06-evolution/02-natural-selection.md). This is why courses are finished as prescribed, why sub-therapeutic doses in agriculture select so effectively, and why stewardship **removes the growth advantage rather than killing harder**.

**Pest management works because eradication is the wrong objective.** Integrated pest management (IPM) monitors density and intervenes only above an **economic threshold** — where damage costs more than control — because spraying below it buys nothing while spraying above it applies the density-dependent selection pressure that breeds resistance. Driving a pest to zero also removes every susceptible individual, so an immigrant carrying resistance alleles recolonises an empty niche unopposed: resistance risk peaks where control is most aggressive. Hence rotating modes of action, planting unsprayed refuges, and using biological control that tracks pest density.

**Conservation is the same equations run in reverse.** A **minimum viable population** is the smallest N expected to persist against demographic accident and stochasticity, and below a few hundred to a few thousand individuals arithmetic becomes genetic: small N means drift dominates selection and inbreeding depression cuts survival and fertility — see [03 — Genetic drift and gene flow](../06-evolution/03-genetic-drift-and-gene-flow.md). A feedback follows: inbreeding lowers the birth rate, pushing N further below the threshold. Conservation therefore works on **r through habitat protection and K through habitat area**, sizes reintroductions on carrying capacity, and protects the diversity in [06 — Biodiversity](06-biodiversity.md).

**Cancer is a population-growth problem inside one body.** A transformed cell that escapes the checkpoints in [10 — Cell cycle and checkpoints](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) founds a clone, and clonal expansion is exponential while nutrients, space, and blood supply are unlimited: dN/dt = rN describes a tumour as it describes a culture. As the mass grows, oxygen limitation, necrosis, and competition among subclones bend the curve towards a logistic shape — which is why **tumour doubling time lengthens as the mass enlarges** and why detection thresholds matter. The framing also explains dosing: many anticancer and antibiotic agents act only on dividing cells, and public health treats disease in a population, not only in a patient.

**Demography is clinical too.** Age structure decides which services a region needs next: a broad-based pyramid means paediatric and obstetric demand now, a constricting one means geriatrics and a shrinking tax base. Epidemiology, resistance, pest control, conservation, and oncology all reduce to two questions: **how fast, and what limits it?**

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "r is the birth rate" | r is the **rate of natural increase, r = b − d**. A population can have a high birth rate and still have r ≤ 0. |
| "Carrying capacity is a fixed property of a species" | K is set by the **environment's limiting resources** for that species, so it changes with season, habitat area, and rivals. |
| "Logistic populations sit exactly at K" | K is an equilibrium around which N oscillates: populations **overshoot and dieback**, and crashes knock them below K between recoveries. |
| "Exponential growth is wrong because nothing grows exponentially forever" | It is correct **while limiting factors are negligible** — early log phase, early epidemic, post-catastrophe recovery. |
| "Density-independent factors regulate populations" | They cause crashes but give **no feedback**: a frost kills the same fraction at any density. Regulation (holding N near K) is density-dependent. |
| "Uniform distribution is the most common pattern" | **Clumped is most common**, because resources and shelter are patchy. Uniform needs active spacing behaviour; random needs even resources *and* no interaction. |
| "Type II survivorship means most individuals die young" | Type II is a **constant death rate at all ages**; type III has heavy early mortality; type I is the pattern where most live to old age. |
| "r-selected and K-selected are formal categories each species belongs to" | They are **endpoints of a fast–slow continuum**; a species shifts along it with conditions. r and K are parameters of a situation, not taxonomic labels. |
| "Mark–recapture is just counting twice" | N = M × n ÷ R assumes **complete mixing, mark fidelity, and no change between samples**. Lost marks inflate N; premature recapture deflates it. |
| "A wide-based pyramid means a large population" | Base width is a **proportion**, not an absolute number. It predicts **future** growth through momentum, even if fertility just fell to replacement. |
| "Medicine lowers birth rates in the demographic transition" | Medicine, sanitation, and food lower the **death rate**, first. **Birth rates fall later**, driven by urbanisation, education, and contraception. |

## Key facts

- A **population** = one species + one area + one time; density, age structure, distribution, and growth rate belong to the group, not the individual.
- **Density**: **quadrats** (mean × area) for sessile organisms; **mark–recapture** for mobile ones, N = M × n ÷ R — worked here as 50 × 40 ÷ 8 = **250**.
- **Distribution mechanisms**: **clumped** (patchy resources, social grouping — most common), **uniform** (territoriality, interference competition), **random** (even resources, no interaction — rare).
- **Balance equation**: dN/dt = (births + immigration) − (deaths + emigration); closed populations give r = b − d.
- **Pyramids** forecast one generation ahead: broad base = growing with momentum; equal columns = stable; constricted base = declining.
- **Survivorship**: **I** late mortality, well-cared-for young (humans, elephants); **II** constant hazard (birds, hydra); **III** heavy early die-off (oysters, most invertebrates).
- **Exponential dN/dt = rN** gives a **J-curve**; **t_d = 0.693/r** — r = 0.021/yr → **33 years** (rule of 70 gives it fast).
- Exponential growth is temporary: consumption and waste rise with N, so r falls — the laboratory version is log → stationary phase in [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md).
- **Logistic dN/dt = rN(K − N)/K** gives an **S-curve**; (K − N)/K is the **fraction of capacity unused**; growth peaks at **N = K/2** at rate **rK/4**.
- **K** is set by limiting resources; density-dependent factors (competition, predation, disease, waste) **regulate**, density-independent factors (frost, fire, flood) only **disturb**.
- **Overshoot and dieback** follow time lags: St Paul Island reindeer went from 29 (1944) to ~2 000 (1963) to ~100 (1966).
- **r vs K** are endpoints of a **fast–slow continuum** set by energy allocation: many small offspring early with no care (insects, weeds, rodents) versus few large late with heavy investment (elephants, whales, humans).
- The **demographic transition** lowers **death rates first** and **birth rates later**; momentum keeps numbers rising for decades after fertility falls.
- Models recur in medicine: **R₀ and herd immunity**, **antibiotic resistance as selection on a growing clone**, **IPM thresholds**, **minimum viable population and inbreeding**, **clonal expansion in tumours**.

## Practice questions

**1. In a mark–recapture survey, 50 fish are marked and released; a later sample of 40 contains 8 marked individuals. The estimated population is**

A. 100 fish
B. 250 fish
C. 320 fish
D. 2 000 fish

**Answer: B**

Explanation: N = M × n ÷ R = 50 × 40 ÷ 8 = **250**. D is the numerator with the division by R forgotten, A divides by n instead of R, and C matches no arrangement of the formula.

---

**2. Desert shrubs grow at almost perfectly regular spacing. The mechanism most likely responsible is**

A. Random seed dispersal over evenly textured soil
B. Territorial or root competition excluding neighbours from a defended radius
C. Predation removing individuals at random
D. Uniform rainfall across the site

**Answer: B**

Explanation: Uniform spacing arises when individuals **push each other apart** — allelopathy, root competition for water, territory defence — so no two settle closer than a minimum distance. Even resources plus random mortality would give a random pattern, not regular spacing.

---

**3. A closed population records 200 births, 60 deaths, 30 immigrants, and 10 emigrants in one year. Its dN/dt is**

A. +100
B. +140
C. +160
D. +260

**Answer: C**

Explanation: dN/dt = (B + I) − (D + E) = (200 + 30) − (60 + 10) = 230 − 70 = **+160 per year**. B treats the population as closed and ignores migration; D adds everything without subtracting.

---

**4. A population has a birth rate of 0.035/yr and a death rate of 0.014/yr. Under exponential growth its doubling time is approximately**

A. 14 years
B. 21 years
C. 33 years
D. 49 years

**Answer: C**

Explanation: r = 0.035 − 0.014 = **0.021/yr**, so t_d = 0.693 ÷ 0.021 ≈ **33 years** — confirmed by the rule of 70 (70 ÷ 2.1 ≈ 33). Doubling follows the *net* rate, never the birth rate alone.

---

**5. A lake has K = 1 000 fish and r = 0.2 per year. If N = 400, the growth rate dN/dt is**

A. 80 fish per year
B. 48 fish per year
C. 120 fish per year
D. 0 fish per year

**Answer: B**

Explanation: dN/dt = 0.2 × 400 × (1 000 − 400)/1 000 = 80 × 0.6 = **48 per year**. A omits the capacity term (pure exponential); D applies only at N = K; 0.6 is the fraction of capacity still unused.

---

**6. Which of the following is a density-independent factor limiting a population?**

A. Competition for nest sites intensifying with density
B. A severe frost killing overwintering larvae regardless of numbers
C. Predation increasing with prey density
D. Toxic waste accumulating as numbers rise

**Answer: B**

Explanation: A frost applies the same mortality at any density, so it **disturbs** the population without regulating it. A, C, and D get worse per individual as N rises, which is what pushes populations back towards K.

---

**7. Which statement correctly matches a survivorship curve with its explanation?**

A. Type I — enormous numbers of small offspring with no parental care
B. Type II — a constant per-capita death rate at every age from age-blind extrinsic hazards
C. Type III — most individuals survive to old age, deaths concentrated after reproduction
D. Type III — found only in species with extended parental care

**Answer: B**

Explanation: Type II has a hazard that does not change with age, giving a straight line on a log survivorship axis — birds and hydra are the standard examples. A and C swap type III and type I; D inverts type III, whose offspring get little or no care.

---

**8. Which pairing of life-history strategy and traits is correct?**

A. Elephants — rapid development, many small offspring, little parental care
B. Weeds — slow development, few offspring, prolonged parental investment
C. Rodents — early maturity, many small offspring, minimal parental care
D. Whales — large broods with no postnatal investment

**Answer: C**

Explanation: Rodents reproduce early, often, and with little investment per offspring — the fast end of the continuum. Elephants and whales are slow strategists with few, heavily invested young, so A and D invert the strategy and B inverts weeds.

---

**9. In the demographic transition, death rates fall before birth rates primarily because**

A. Contraception became available before modern medicine
B. Sanitation, vaccination, and food supply cut mortality; birth rates fall only once urbanisation, education, and contraception remove the reasons for large families
C. Governments deliberately reduced birth rates first
D. Birth rates are biologically fixed and cannot fall

**Answer: B**

Explanation: Medical and sanitary interventions act on **death**, so mortality — especially infant mortality — drops first while fertility habits persist a generation longer. Birth rates then fall for socioeconomic reasons: children cease to be farm labour, women gain education and contraception. A and C reverse the historical order; D is contradicted by every stage-3 and stage-4 country.

---

**10. Why is a tumour's growth exponential at first and logistic-like later?**

A. Cancer cells cannot divide, so growth must slow
B. Early on, space, nutrients, and vasculature are unlimited so clone size follows dN/dt = rN; as the mass enlarges, oxygen and nutrient limitation decelerate growth
C. The immune system switches itself off as the tumour grows
D. Tumours follow a type II survivorship curve and therefore never accelerate

**Answer: B**

Explanation: An expanding clone with no ceiling grows exponentially — the same equation as a bacterial culture. Once oxygen diffusion and competition for blood supply bind, growth decelerates, which is why **tumour doubling time lengthens with mass size**. A is false: division is unchecked, not absent.
