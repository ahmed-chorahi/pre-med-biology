# Food Chains, Food Webs, Energy Flow, and Trophic Levels

## Why it matters

Every ecosystem on Earth runs on two thermodynamic facts working in opposition: **photosynthesis captures a thin stream of sunlight as chemical energy**, and **every transfer of that energy converts a large fraction of it into unusable heat**. This chapter is the arithmetic that follows from those facts. The **10% rule**, the shapes of ecological pyramids, the four-to-five-level ceiling on chain length, and the rarity of top predators are not conventions invented for convenience — they are the visible consequences of the **second law of thermodynamics** applied to living systems.

A student who can recite "only 10% passes to the next level" without being able to say *why* the number is 10 and not 50 has memorised a slogan; a student who can run the calculation from first principles can answer almost any question the topic generates, including the ones dressed up as pyramids, fisheries, or pesticide poisoning.

The chapter also fixes the vocabulary of the whole section. **Trophic levels** are defined by *where an organism's energy comes from*, not by size or kingdom. Chains are simplified diagrams; **webs** are the reality, and a web's structure decides whether a community holds together when a species is removed. The same arithmetic also explains why **energy flows one way through an ecosystem while matter cycles endlessly** — the distinction that organises all of ecology.

## Producers, consumers, and decomposers

An ecosystem's members are classified not by anatomy but by **energetic role**: who eats whom, and where the energy entering their bodies came from.

### Trophic levels are defined by energy source, not size or taxonomy

A **trophic level** is the position an organism occupies in the sequence of energy transfers.

| Trophic level | Energy source | Examples |
| --- | --- | --- |
| **Producers (autotrophs)** | Inorganic carbon (CO₂) + light or chemical energy | Green plants, cyanobacteria, algae, some chemoautotrophic bacteria |
| **Primary consumers (herbivores)** | Energy fixed by producers | Zooplankton, caterpillars, rabbits, cattle |
| **Secondary consumers (carnivores/herbivore-eaters)** | Energy in herbivore tissue | Frogs, small birds, lions eating zebras |
| **Tertiary consumers (carnivore-eaters)** | Energy in secondary-consumer tissue | Hawks, sharks, eagles |
| **Apex predators** | Top of their chain — nothing routinely eats them | Orcas, wolves, large sharks, adult crocodiles |
| **Omnivores** | Feed at two or more trophic levels at once | Humans, boars, brown bears |
| **Decomposers** | Dead organic matter at *every* level | Fungi, bacteria |
| **Detritivores** | Particulate dead matter (leaf litter, carcasses) | Earthworms, dung beetles, vultures |

Four consequences of taking the definition seriously are worth spelling out:

- A **cow is a primary consumer** even though it outweighs the wolf that kills it. Size is irrelevant.
- **Fungi are not plants**: they are heterotrophs that absorb nutrients externally, so they sit with the decomposers despite being sessile.
- **A parasite's trophic level follows its host's diet** — a tapeworm in a human sits wherever the human eats, which is why parasites are drawn at the same level as their host's food.
- **Omnivores shift level with their meal**, so one species can occupy level two in one chain and level three in another.

### The three functional groups

```
SUNLIGHT ──▶ PRODUCERS (autotrophs): light energy ──▶ chemical energy
                  │  eaten by
                  ▼
            CONSUMERS (heterotrophs): each transfer loses heat
                  │  die, excrete, moult
                  ▼
        DECOMPOSERS & DETRITIVORES ──▶ CO₂, H₂O, NH₄⁺, PO₄³⁻
                  └──▶ reused by producers (the loop closes)
```

**Producers** are the only organisms that add energy to the living part of an ecosystem. Their capture of light is covered in [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md) (6 CO₂ + 6 H₂O + light → sugar + O₂), and that sugar is the *only* way energy enters a food web. Chemosynthetic bacteria at hydrothermal vents run whole ecosystems without photosynthesis by substituting chemical oxidation for light, yet remain **autotrophs** by the same definition: inorganic carbon, not organic.

**Consumers** cannot add energy; they only *transfer* it, and pay a tax on every transfer. **Primary consumers** eat producers, **secondary consumers** eat primary consumers, and so on.

**Decomposers and detritivores close the loop.** Fungi and bacteria secrete enzymes externally, absorb the resulting small molecules, and release CO₂ and mineral nutrients — nitrogen as ammonium, phosphorus as phosphate — so producers can take them up again; the microbial side is in [07 — Beneficial Microorganisms](../07-microbiology/07-beneficial-microorganisms.md). Without them, dead matter would pile up and the mineral supply for photosynthesis would be locked away within a few seasons. **Decomposition is why ecosystems are cycles rather than pipelines**, even though the energy flowing through them is not.

## Food chains and food webs

### Anatomy of a chain

A **food chain** is a single linear pathway of energy transfer, written in the direction energy travels:

```
GRASS ──▶ GRASSHOPPER ──▶ FROG ──▶ SNAKE ──▶ HAWK
           primary       secondary  tertiary   apex
           consumer      consumer   consumer   predator
```

Read left to right, each arrow means **"is eaten by"** — equivalently, "energy flows to". The chain begins with a producer and, in practice, ends after four or five links. A **grazing food chain** starts with living plant material; a **detrital food chain** starts with dead organic matter (leaf litter → millipede → shrew → owl). In most terrestrial ecosystems the detrital channel is the *larger* of the two, because most plant production is never eaten but dies and is decomposed.

### Why the web is the real object

Chains are teaching diagrams. In nature most organisms eat more than one thing and are eaten by more than one, so the correct picture is a **food web**: a set of chains sharing species.

```
                    ┌──▶ HAWK ◀──────┐
                    │                 │
GRASS ──▶ GRASSHOPPER ──▶ FROG ──▶ SNAKE
   │           │                       ▲
   │           └──▶ SPARROW ───────────┘
   │
   └──▶ MOUSE ──▶ OWL
```

Three structural features matter, each with a name:

- **Omnivory** — feeding at more than one trophic level (a bear eating berries *and* salmon). It means an organism can occupy a different level in different chains *in the same web*.
- **Connectance** — the fraction of all possible species pairs actually linked by feeding (realised links ÷ possible links); typical food webs run about 0.1–0.3.
- **Link weight (interaction strength)** — how much of a predator's diet, or of a prey's mortality, each link represents. Ecologists distinguish **strong** links (specialist pairings that dominate energy flow) from **weak** links (rare, incidental feeding).

**Web structure determines stability.** A web with many weak links redistributes damage: remove one species and its predators switch to alternatives. A web with a few very strong links is efficient but brittle — remove the single prey on which a specialist depends and the whole pathway collapses. The general result is that **high connectance plus many weak links stabilises a community, whereas a handful of dominant strong links transmits shocks up and down the chain** — which is why species richness and food-web stability are treated together in [06 — Biodiversity](06-biodiversity.md), and why the trophic cascades described later follow from removing a single top link.

## Energy flow arithmetic

### GPP, R, and NPP

Ecologists measure energy, not just mass, because **energy is what is lost at each step**. All four quantities below are expressed per unit area per unit time (**J/m²/yr** or the mass equivalent **g/m²/yr**), and the first three form a simple subtraction:

```
SUNLIGHT ──photosynthesis──▶ GROSS PRIMARY PRODUCTION (GPP)
                                │  total energy fixed by producers
                                ├──▶ PLANT RESPIRATION (R)
                                │      maintenance, growth, ion uptake
                                │      ──▶ LOST AS HEAT
                                ▼
                    NET PRIMARY PRODUCTION (NPP) = GPP − R
                                │
                                ├──▶ eaten by herbivores
                                └──▶ dies → decomposers
                                    (the uneaten fraction feeds the
                                     detrital chain rather than vanishing)
```

- **GPP (gross primary production)** — the *total* chemical energy a producer fixes in a given time; the gross capture rate of the chloroplasts.
- **R (respiration)** — the producer's own metabolic cost, dissipated as heat ([04 — ATP and Metabolism](../03-cellular-processes/04-atp-and-metabolism.md) — every ATP hydrolysed ends as heat).
- **NPP (net primary production)** — **NPP = GPP − R**: the energy left for growth, storage, and everything that will eat the producer. It is what is *available* to the rest of the web and the correct measure of how much life an ecosystem supports.
- **ACP (assimilated consumer production)** — the slice of NPP consumers retain as their own new tissue: consumption minus faeces and urine (never assimilated) minus their own respiration. It is NPP one level up — often called **secondary production** — with the same units.

**Worked arithmetic.** Suppose a grassland fixes 20,000 kJ/m²/yr as GPP, of which the plants spend 12,000 kJ/m²/yr on their own respiration:

```
NPP = GPP − R = 20,000 − 12,000 = 8,000 kJ/m²/yr
```

Of that 8,000, herbivores eat perhaps 1,000 (the rest dies and is decomposed); of the 1,000 eaten, ~400 is assimilated; herbivore respiration takes ~250 of those; **ACP ≈ 150 kJ/m²/yr** of new herbivore tissue. Huge losses have occurred before a single carnivore eats anything — and typical NPP runs from about 90 g/m²/yr in a desert to 2,200 in a rainforest.

### The 10% rule (Lindeman's efficiency), with a worked example

**Lindeman's efficiency** (trophic transfer efficiency) is the percentage of energy at one level that is passed on as biomass at the next — typically **~10%, with a realistic range of about 5–20%**.

```
PRODUCERS        10,000 kJ available in plant tissue
                      │
                      │  ~10% transferred
                      ▼
HERBIVORES         1,000 kJ in herbivore tissue
                      │  ~10% transferred
                      ▼
CARNIVORES           100 kJ in carnivore tissue
                      │  ~10% transferred
                      ▼
TOP PREDATOR          10 kJ available at level four
```

**Where does the other 90% go, exactly?** Three sinks, in descending order of importance:

| Loss | What it is | Rough share of the energy at a level |
| --- | --- | --- |
| **Respiration → heat** | Maintenance metabolism, movement, body heat; every ATP ends as heat (second law) | Largest single loss |
| **Not eaten** | Plant stems, roots and **lignified cell walls** ([01 — Plant Cells and Tissues](../08-plant-biology/01-plant-cells-and-tissues.md)); bones and shells in animals | Very large in the plant → herbivore step |
| **Not assimilated, plus dead matter** | Faeces, urine, undigested cellulose, carcases, litter — all pass straight to decomposers | Large for herbivores (~60% of what is eaten) |

These losses are *why* transfer efficiency differs between steps:

| Transition | Proportion eaten (consumption efficiency) | Proportion assimilated | Trophic transfer efficiency |
| --- | --- | --- | --- |
| Plant → herbivore | ~10% (most plant tissue is never grazed) | ~40% (cellulose is hard to digest) | **~2%** |
| Herbivore → carnivore | ~60% | ~90% | **~10–20%** |
| Carnivore → carnivore | ~50–60% | ~90% | **~5–15%** |

The classic **~10% figure is an average** across these steps. It is low at the first step because most plant tissue is never eaten and cellulose resists digestion, higher thereafter because animal tissue is digestible — but respiration still eats most of what is assimilated.

### Why the second law is the cause

The 10% rule is not a biological constant; it is a **thermodynamic one**. The second law states that every energy transfer degrades some usable energy into **low-grade heat that can no longer do work**:

```
chemical energy in a molecule
      │  transfer (digestion, transport, oxidative phosphorylation)
      ▼
part becomes work (movement, biosynthesis, active transport)
part becomes heat, radiated away and unrecoverable
      └──▶ no organism further up the chain can re-capture it
```

Every ATP hydrolysed ends as heat; every electron transport chain leaks energy as heat ([04 — ATP and Metabolism](../03-cellular-processes/04-atp-and-metabolism.md)). **No biological mechanism could raise transfer efficiency to 50%** — that would require an engine returning all of its waste heat to the fuel, a perpetual-motion machine. The arithmetic is forced on ecology by physics.

### Why food chains are short

Extending the worked example by one step gives 10,000 → 1,000 → 100 → 10 → **1 kJ** at level five: a ten-thousandth of the original energy. By the fourth or fifth link there is too little left to support a breeding population — individuals must range over enormous areas, encounter rates fall below replacement, and the lineage dies out locally. **Food chains therefore run to about 4–5 trophic levels**, an observation that follows directly from the transfer arithmetic. It is also why **apex predators are rare**: their biomass is what survives three or four successive ~90% losses, so they occupy a tiny fraction of the ecosystem's energy budget.

## Ecological pyramids

An **ecological pyramid** compares a quantity at each trophic level, producers at the base. Three quantities are used, and — the most examined distinction in the chapter — **only one can never be inverted**.

### Pyramid of numbers

Counts individuals at each level. It **can be inverted**, because a single large organism can support many small ones:

```
   INVERTED PYRAMID OF NUMBERS (woodland)

        10,000 caterpillars   ▲
         500 songbirds        │
           5 hawks            │  numbers FALL going up —
         1 oak tree           ▼  yet energy still flows upward
```

The oak tree is one individual, the caterpillars feeding on it are thousands: the pyramid is upside-down but **nothing is wrong**, because the tree's *biomass* and *production* still exceed the consumers'. Numbers are a poor proxy for energy when individuals differ enormously in size.

### Pyramid of biomass

Measures standing mass (g/m²) at each level. Usually upright, but **can be inverted in aquatic systems**:

```
UPRIGHT (typical grassland)     INVERTED (open water, snapshot)

   producers  ▓▓▓▓▓▓▓             producers  ▓
   herbivores ▓▓▓▓                 herbivores ▓▓▓
   carnivores ▓▓                   carnivores ▓▓▓
   apex       ▓                    apex       ▓▓
```

**Why an aquatic biomass pyramid inverts:** phytoplankton have an extremely **high turnover rate** — they divide many times a week and are grazed almost as fast — so at any instant their **standing crop** (the biomass present *right now*) is small while their *rate of production* over a season is enormous. Zooplankton, longer-lived, accumulate more mass than the crop of algae supporting them at that moment. A biomass pyramid is a **stock measurement**, and a stock can be small even when the flow through it is large; measure *annual production* instead and the inversion disappears.

### Pyramid of energy

Plots energy flow (J/m²/yr) at each level. It is **never inverted, in any ecosystem, without exception**:

```
            ▲  energy flow (kJ/m²/yr)
      level 4   ██                  top predators: smallest flow
      level 3   ████
      level 2   ████████
      level 1   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓   producers: largest flow
            └──────────────────────
```

**The reason is the second law.** The energy pyramid measures a *rate of transfer*, and by thermodynamics each level must pass on less than it received — the remainder has been respired as heat and left the system. An inverted energy pyramid would mean level two contained more energy per year than level one supplied, i.e. consumers creating energy from nothing. **The shape is fixed by physics, not by biology.**

### The three pyramids compared

| Pyramid | Quantity measured | Unit | Can it be inverted? | Why / why not |
| --- | --- | --- | --- | --- |
| **Numbers** | Individuals per level | count | **Yes** | One tree may host thousands of insects |
| **Biomass** | Standing mass per level | g/m² | **Yes, in some systems** | Aquatic producers turn over fast: small standing crop, huge annual production |
| **Energy** | Energy transferred per unit time | J/m²/yr | **Never** | A rate constrained by the second law — each level must lose energy as heat |

**The examiner's trap:** "an inverted pyramid" alone is meaningless — the answer must name *which* pyramid: numbers invert freely, biomass in water, **energy never**.

## Why energy flows one way but matter cycles

The two great flows through an ecosystem are fundamentally unlike each other:

```
SUN ──▶ producers ──▶ consumers ──▶ decomposers ──▶ CO₂ + heat to space
  │         │              │              │
  │    carbon, nitrogen, phosphorus, water — captured, passed on,
  │    released by respiration and decomposition, and CAPTURED AGAIN
  │
  └── energy enters ONCE as short-wave light and leaves as long-wave heat,
      dispersed and impossible to recycle
```

- **Energy is unidirectional.** It arrives as sunlight, is converted to chemical energy, and leaves as infrared heat. Feeding on yesterday's sunlight is impossible, and every trophic transfer leaks more: an ecosystem needs continuous energy *input* and continuous heat *output*, so it is open with respect to energy.
- **Matter is cyclical.** Atoms of carbon, nitrogen, phosphorus, and water are used, excreted, decomposed to inorganic form, and re-used indefinitely — no atom is consumed by eating. The cycles themselves are in [03 — Nutrient Cycles](03-nutrient-cycles.md); what matters here is *why* they can cycle at all: only energy carries a second-law tax.

This asymmetry is why **energy flow constrains ecosystems (short chains, rare top predators) while nutrient supply constrains their chemistry (limiting elements, eutrophication)**, and it makes decomposers indispensable: they return matter to the inorganic pool. Without them energy would still flow through the grazing chain, but the atoms would not come back.

## Relevance to medicine and the real world

**Agriculture is energy arithmetic with a policy attached.** Feeding crops to animals and then eating the animals loses roughly 90% of the original plant energy at each transfer — on the order of **8–10 kg of grain per 1 kg of beef**, through faecal losses, undigested cellulose, and respiration. The same hectare feeds many more people as wheat than as steak, so farming is a deliberate attempt to **shorten the food chain to level one**, the shortest path from sunlight to dinner. This is not a moral claim but Lindeman's arithmetic: it explains why herbivorous diets are energetically efficient and why grain-fed meat is expensive in energy, land, water, and money.

**Biomagnification is the same arithmetic run on a pollutant.** Persistent, lipophilic (fat-soluble) toxins such as **DDT** and **methylmercury** are absorbed faster than they are excreted or metabolised. Because they are stored in fatty tissue rather than passed out, each trophic transfer *concentrates* them — a top predator's concentration can be a million-fold higher than the surrounding water. The mechanism is **retention plus transfer**: the organism keeps the toxin and passes it on with its tissue, so the ~90% of energy lost at each step does **not** remove the toxin with it. DDT-era eggshell thinning in raptors and pelicans pushed several species to the edge, and the bans that followed coincided with the rise of **biological control** — using predatory and parasitic microbes and insects instead of chemicals (see [07 — Beneficial Microorganisms](../07-microbiology/07-beneficial-microorganisms.md)). Since humans sit near the top of most food chains, **we are the endpoint of biomagnification for whatever we release into the web**.

**Human mercury poisoning is biomagnification with a clinical face.** Methylmercury made by sulphate-reducing bacteria in sediments enters plankton, passes to small fish, then to predatory fish (tuna, swordfish, shark, pike), concentrating at every step. The **Minamata** epidemic in 1950s Japan — industrial mercury discharged into a bay — produced numbness, ataxia, visual and auditory loss, and severe developmental damage in children exposed *in utero*, because mercury crosses the placenta and the fetal brain is uniquely vulnerable. Advice to limit large predatory fish in pregnancy is applied trophic-level reasoning: choose a lower-level species and the dose falls by an order of magnitude.

**Fisheries science is a question of which level you are harvesting.** **Maximum sustainable yield (MSY)** depends on the production rate at the harvested trophic level — and production falls by roughly 90% for every step up. Stocks of high-level predators (cod, tuna, sharks) produce far less new biomass per year than planktivorous fish, so they support far smaller catches before declining. Fleets that deplete the big predators and shift to smaller, lower-level species are **"fishing down the food web"** — an economically visible symptom of the same energy pyramid.

**Protecting top predators is an energy-web intervention, not sentiment.** Removing wolves from Yellowstone allowed elk to browse riparian willow and aspen unchecked; vegetation thinned, riverbanks eroded, and songbird and beaver numbers fell, while reintroducing wolves reversed the sequence. This is a **trophic cascade**: an apex predator's effect propagates down every level below it because the web's links transmit force. Because apex predators hold a tiny share of a system's energy, their numbers are few, so their loss is easy and their recovery slow. Conserving them is a decision about **web structure and link weights**: a system with top-down links intact reroutes disturbance instead of amplifying it.

**The clinical translation:** trophic arithmetic explains dietary guidance (eat lower on the chain for efficiency, avoid top predators for contaminant load) and why **persistent pollutants are a population-level, generational problem rather than an individual dose** — the population thinking of [02 — Natural Selection](../06-evolution/02-natural-selection.md).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "A trophic level is defined by size or species" | It is defined by the **source of energy**: a whale eating krill is a primary consumer, as is an elephant eating grass. |
| "Producers make energy" | They **convert** light energy into chemical energy (09 — Photosynthesis); energy is conserved, only its form changes. |
| "The 10% rule means exactly 10% every time" | It is an **average** of roughly 5–20%: plant → herbivore is often ~2%, herbivore → carnivore ~10–20%. |
| "Energy is recycled through the ecosystem" | Energy **flows one way**: sunlight in, heat out. Only **matter** cycles. |
| "An inverted pyramid means an impossible ecosystem" | Only **energy** pyramids can never invert; numbers invert (one tree, many insects) and aquatic biomass inverts (fast-turnover phytoplankton). |
| "NPP = GPP" | **NPP = GPP − R**. GPP is total fixation; NPP is what remains after the producer's own respiration. |
| "Decomposers are a trophic level you eat next" | They work **in parallel with every level**, breaking dead matter from all of them and returning minerals to producers. |
| "A food chain and a food web are interchangeable" | A chain is one linear pathway; a web is many chains sharing species, and omnivory lets one species occupy different levels in different chains. |
| "Biomass accumulated at a high level proves a lot of energy flowed there" | Biomass is a **stock**; energy flow is a **rate**. Long-lived top consumers hold stock fed by a small annual flow. |
| "Biomagnification is the same as bioaccumulation" | **Bioaccumulation** builds a toxin in one organism over its lifetime; **biomagnification** is the increase *up trophic levels*. |
| "Food chains are long in productive ecosystems" | Productivity raises the **biomass at every level**, but transfer efficiency still caps **length** at ~4–5 levels. |

## Key facts

- Trophic levels are defined by **energy source** — producer, primary/secondary/tertiary consumer, apex predator, omnivore, decomposer, detritivore — never by size or taxonomy.
- **Producers** are the only organisms adding energy to the web (light → chemical energy, [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md)); consumers only transfer it; **decomposers close the matter loop**.
- **GPP − R = NPP**, measured per unit area per unit time (**J/m²/yr** or **g/m²/yr**); **ACP** is the consumer-level equivalent — consumption minus waste minus respiration.
- **Lindeman's efficiency ≈ 10%** (range 5–20%): 10,000 kJ → 1,000 kJ → 100 kJ → 10 kJ across four levels.
- The missing 90% is **respiration heat, uneaten material, and undigested material** — the plant → herbivore step is worst (~2%) because most plant tissue is never eaten and cellulose resists digestion.
- The **second law** guarantees the loss: every transfer degrades usable energy to heat that no organism can recapture ([04 — ATP and Metabolism](../03-cellular-processes/04-atp-and-metabolism.md)), which **caps chains at ~4–5 levels** and makes apex predators rare.
- **Pyramid of numbers** can invert (one tree, many insects); **pyramid of biomass** can invert in water (small standing crop, huge turnover); **pyramid of energy never inverts** — the standing crop is a **stock**, production a **rate**.
- **Energy is unidirectional** (sunlight in, heat out) while **matter cycles** — see [03 — Nutrient Cycles](03-nutrient-cycles.md).
- Food **chains** are simplifications; **webs** show omnivory, and structure (connectance, link weight) sets stability — many weak links stabilise, few strong links transmit collapse.
- **Biomagnification** concentrates persistent lipophilic toxins (DDT, methylmercury) up the chain because they are retained, not metabolised — apex predators and humans are the endpoint.
- **Maximum sustainable yield** tracks trophic level, and **trophic cascades** (wolves → elk → riparian vegetation) show that protecting top predators is an energy-web intervention.

## Practice questions

**1. Which statement correctly defines a trophic level?**

A. The physical size of an organism relative to others in its habitat
B. The position of an organism defined by the source of the energy it consumes
C. The taxonomic kingdom to which an organism belongs
D. The geographic zone an organism occupies

**Answer: B**

Explanation: A trophic level is assigned purely by where the energy entering an organism's body originated — sunlight fixed by producers, herbivore tissue, carnivore tissue. A cow and a mouse eating grass are both primary consumers regardless of size (A), taxonomy does not decide it (C), and habitat is irrelevant (D).

---

**2. Starting with 10,000 kJ of energy in producers, approximately how much energy is available to a tertiary consumer if transfer efficiency is 10% per level?**

A. 1,000 kJ
B. 100 kJ
C. 10 kJ
D. 1,000 kJ/m²/yr of net production

**Answer: C**

Explanation: 10,000 → 1,000 (primary) → 100 (secondary) → 10 kJ (tertiary): each step multiplies by 0.1. A is the primary consumer's share, B the secondary consumer's, and D wrongly attaches rate units.

---

**3. In an ecosystem where producers fix 15,000 kJ/m²/yr and respire 9,000 kJ/m²/yr, net primary production is**

A. 24,000 kJ/m²/yr
B. 15,000 kJ/m²/yr
C. 6,000 kJ/m²/yr
D. 9,000 kJ/m²/yr

**Answer: C**

Explanation: NPP = GPP − R = 15,000 − 9,000 = 6,000 kJ/m²/yr — the energy actually available to consumers and decomposers. A adds what should be subtracted, B equates NPP with GPP, and D reports respiration alone.

---

**4. Which ecological pyramid can NEVER be inverted, in any ecosystem?**

A. Pyramid of numbers
B. Pyramid of biomass
C. Pyramid of energy
D. Both numbers and biomass pyramids

**Answer: C**

Explanation: An energy pyramid measures flow per unit time, and the second law guarantees each level passes on less than it received — inverting it would mean consumers create energy. Numbers invert readily (one oak tree, thousands of caterpillars) and aquatic biomass inverts because the producer standing crop is small relative to its rapid turnover.

---

**5. A lake shows an inverted pyramid of biomass. The best explanation is that**

A. The producers there are not performing photosynthesis
B. Their standing crop is very small but turnover is very high, so annual production far exceeds the biomass present at any instant
C. Energy flows upward from carnivores to producers
D. The measurement of biomass in water is always inaccurate

**Answer: B**

Explanation: Phytoplankton divide and are grazed within days, so their standing stock at a snapshot is small while seasonal production is large — the pyramid measures a stock, not a rate. The producers are photosynthetic (A), energy flow never reverses (C), and the pattern is real rather than a measurement artefact (D).

---

**6. The primary reason food chains rarely exceed four to five trophic levels is that**

A. There are not enough species to fill more levels
B. Predators above the fifth level refuse to eat smaller animals
C. Cumulative losses of ~90% per transfer leave too little energy to support a viable population
D. Producers refuse to grow when chains are long

**Answer: C**

Explanation: Repeating ~10% transfer leaves roughly 1/10,000 of the original energy by level five — too little to find food and reproduce above replacement. Chain length follows energy arithmetic and the second law, not species availability (A), prey-size preferences (B), or any effect on producers (D).

---

**7. Which loss accounts for the largest share of energy missing between trophic levels?**

A. Energy converted to heat by respiration, plus material never eaten and never digested
B. Energy stored permanently in fossil fuels
C. Energy used to build bones and shells exclusively
D. Energy returned to the Sun

**Answer: A**

Explanation: Respiration dissipates most assimilated energy as heat, while uneaten and undigested material passes straight to decomposers — together these account for the ~90% that never transfers. Nothing returns to the Sun (D), fossil fuels are negligible (B), and building tissue is not itself a loss (C).

---

**8. Methylmercury concentrations are highest in large predatory fish and in humans who eat them because**

A. Mercury is created by the fish's metabolism
B. Mercury is soluble in water and so is absorbed continuously at every level
C. Mercury is retained rather than excreted or metabolised, so it concentrates with each transfer up the trophic levels
D. Large fish have more fat-free tissue than small fish

**Answer: C**

Explanation: Methylmercury is persistent and lipophilic; organisms keep it and pass it on with their tissue, so each transfer simultaneously magnifies concentration — the definition of biomagnification. It is not manufactured (A), water solubility is not the mechanism (B), and fat solubility rather than fat-free tissue matters (D).

---

**9. Which pair of statements about energy and matter in an ecosystem is correct?**

A. Energy cycles; matter flows in one direction
B. Both energy and matter cycle endlessly
C. Energy flows one way and is lost as heat; matter is recycled by decomposers and reused by producers
D. Matter flows one way; energy cycles

**Answer: C**

Explanation: Energy enters once as sunlight and leaves as infrared heat, so every ecosystem needs continuous input. Atoms of carbon, nitrogen, and phosphorus are released by respiration and decomposition and taken up again — the role of decomposers, and the subject of [03 — Nutrient Cycles](03-nutrient-cycles.md).

---

**10. Compared with a grazing food chain, a detrital food chain**

A. Begins with living plant tissue eaten by herbivores
B. Begins with dead organic matter and is usually the larger channel of energy flow in terrestrial ecosystems
C. Contains no decomposers
D. Reaches higher trophic levels because detritus is more energy-rich

**Answer: B**

Explanation: Most plant production is never grazed — it dies and enters the detrital channel, where fungi, bacteria, and detritivores process it; in most land ecosystems this channel carries more energy than grazing. A describes the grazing chain, detrital chains are defined by their decomposers (C), and the same ~10% rule limits their length (D).
