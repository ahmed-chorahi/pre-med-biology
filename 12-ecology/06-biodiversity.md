# Biodiversity

## Why it matters

**Biodiversity** — the variety of life at every level of organisation — is the *product* of evolution and the *substrate* on which every ecosystem process runs. Variation, selection, and speciation ([01 — Variation, fitness, and adaptation](../06-evolution/01-variation-fitness-adaptation.md), [02 — Natural selection](../06-evolution/02-natural-selection.md)) have been accumulating variety for billions of years, and that variety is what fixes nitrogen, pollinates crops, purifies water, and supplies the molecules pharmacology was built on. Strip it away and the processes do not slow gracefully — they fail, because they are carried out by *populations*, and populations are what go extinct.

Biodiversity is also **the thing being lost fastest**, and the losses are not random: competitive exclusion explains why an introduced predator empties a naive community, drift why a shrinking fragment loses alleles before it loses species, selection why pathogens spread in stressed hosts. Conservation biology is the applied end of those causal chains, joining evolution (section 06), microbiology (section 07), and ecology.

This chapter defines **the three levels of biodiversity**, then the quantitative tools that turn decline into predictions, and closes with threats and conservation as mirror images.

## Three levels of biodiversity

| Level | What is counted | Typical measure | Question it answers |
| --- | --- | --- | --- |
| **Genetic diversity** | Alleles *within* a species | Heterozygosity, allelic richness | Can this population adapt to a new pathogen or climate? |
| **Species diversity** | Species *within* a community | **Richness** × **evenness** | How is the community structured, and will it persist? |
| **Ecosystem diversity** | Ecosystems, biomes, and their processes | Habitat types, biome area, process rates | How many ways does this landscape process energy and matter? |

### Genetic diversity

**Genetic diversity** is the stock of alleles in a population's gene pool — the raw material defined in [01 — Genes, alleles, genotype, and phenotype](../04-genetics/01-genes-alleles-genotype-phenotype.md) and the variation selection acts on. **Selection can only act on variation that already exists**: a population with no resistance allele cannot evolve one on demand; it must wait for mutation.

```
low genetic diversity ─► few adaptive alleles ─► weak response to new pathogen
                     └─► homozygosity ─► deleterious recessives expressed
                     └─► whole population shares one susceptibility
                                   │
                                   ▼
                 one pathogen type / one catastrophe ─► collapse
```

| Disaster | What was grown | Why it failed |
| --- | --- | --- |
| **Irish potato famine (1845–52)** | Near-monoculture of the clone **"Lumper"** | *Phytophthora infestans* met **uniform susceptibility** over millions of hectares — no resistant allele to be selected ([04 — Fungi and protozoa](../07-microbiology/04-fungi-and-protozoa.md)) |
| **Panama disease of banana** | **Gros Michel**, now **Cavendish** — sterile triploid clones | *Fusarium oxysporum* f.sp. *cubense* destroyed Gros Michel in the 1950s; **Tropical Race 4** now threatens Cavendish. With no sex, resistance alleles are never reshuffled |

A **monoculture** is a population whose genetic diversity has been deliberately minimised: maximum yield uniformity, maximum catastrophic risk. Wild crop relatives are conserved as a living allele reserve ([08 — Plant biology](../08-plant-biology/)).

### Species diversity

**Species diversity** has two components, always reported separately.

- **Species richness** — the *number of different species* present.
- **Species evenness** — *how equally individuals are distributed among those species*.

| Community (10 species, 100 individuals) | Distribution | Evenness | Interpretation |
| --- | --- | --- | --- |
| **A** | 10 species × 10 individuals | **High** | No dominant monopolises resources |
| **B** | 1 species × 91 + 9 species × 1 | **Very low** | Same richness, near-monoculture in function; nine rare species are one disturbance from local loss |

So **a community of 10 species with equal counts is more diverse than 10 species dominated by one** — identical richness, different diversity. **Simpson's** and **Shannon–Wiener** indices therefore combine both terms rather than counting species alone.

### Ecosystem diversity

**Ecosystem diversity** is variety at the largest scale: the range of **biomes** and habitats and the processes they run — nutrient cycling ([03 — Nutrient cycles](03-nutrient-cycles.md)) and trophic structure ([02 — Food chains, webs, and trophic levels](02-food-chains-webs-and-trophic-levels.md)) among them.

| Biome | What its loss removes |
| --- | --- |
| **Tropical rainforest** | Largest reservoir of terrestrial species; carbon released on clearing |
| **Coral reef** | ~25% of marine species on <1% of ocean floor; coastal protection and fisheries |
| **Wetland** | Water purification and flood storage, replaced at cost if lost |

## Why diversity matters functionally

### The insurance (redundancy) hypothesis

The **insurance (redundancy) hypothesis** states that many species perform overlapping roles, so when one is lost another **functionally similar** species takes over and the process continues.

```
high diversity ─► several species share each role (functional redundancy)
                         │
species X lost to disease, drought, or overexploitation
                         │
                         ▼
species Y, Z (same role, different tolerances) increase
                         │
                         ▼
      ecosystem process (decomposition, pollination, grazing) CONTINUES
```

The mechanism is **compensatory dynamics**: species differing in their responses to fluctuation replace one another, so total process rate is steadier than any single population. Redundancy cannot be measured until something is removed — which is why species counts are worth preserving.

### Diversity, stability, and invasion resistance

The **diversity–stability relationship** was tested experimentally: sow **randomly assembled plant communities of 1, 2, 4, 8, 16, and 32 species** on identical plots, perturb them, and measure function. Because richness is manipulated independently of environment, any difference in function must be caused by diversity itself — the causal design *is* the evidence.

| Prediction | Result |
| --- | --- |
| **Resist invasion** | Low-richness plots are colonised readily; **high-richness plots resist invasion** because light, water, and nutrients are already fully captured |
| **Recover faster** | After drought or clipping, **more species → quicker recovery**, because tolerant species are present somewhere in the mix |
| **Maintain function** | Year-to-year variability falls as richness rises — the **portfolio effect**: many independently fluctuating populations average out |

**Invasion resistance is competitive exclusion run in reverse**: a saturated community leaves no empty niche, so an invader finds no opening — the principle developed in [05 — Ecological relationships](05-ecological-relationships.md).

### Keystone species and genetic adaptive potential

The insurance hypothesis buffers *function*; the **keystone species** concept marks species that are *not* redundant — one whose effect on community structure is **disproportionate to its biomass** (sea otters holding urchins in check, and thereby kelp forests). Redundancy protects processes; keystone loss breaks structure (see [05 — Ecological relationships](05-ecological-relationships.md)).

At population level the same argument is **adaptive potential**: genetically diverse populations harbour more alleles for selection to use as conditions change, while small populations lose fitness through **inbreeding depression** and lose alleles through **drift** ([03 — Genetic drift and gene flow](../06-evolution/03-genetic-drift-and-gene-flow.md)).

```
population declines ─► effective size (Ne) falls
      ├─► drift overwhelms selection ─► alleles lost at random
      ├─► inbreeding ─► homozygosity ─► deleterious recessives expressed
      └─► adaptive potential falls ─► slower response to disease or climate
                    │
                    ▼
        extinction risk rises EVEN IF the species count is unchanged
```

Genetic diversity can therefore erode invisibly while a species still looks common — which is why conservation monitors alleles, not just head-counts.

## The species–area relationship

**Larger areas hold more species**, expressed as the **species–area relationship**:

```
S = cA^z          (S = species, A = area, c and z = constants)

linearised:   log S = log c + z log A     ─► straight line on log–log axes
```

| Term | Meaning | Typical behaviour |
| --- | --- | --- |
| **S** | Predicted richness | Rises with area |
| **A** | Habitat area | Any consistent unit |
| **z** | **Slope** of the log–log line | Usually **0.15–0.35**; higher for isolated habitat islands (c sets the height of the line) |

Two mechanisms: (1) **bigger areas are more varied** — more habitats, edges, and microclimates mean more niches to fill; (2) **bigger populations go extinct more slowly**, buffered against demographic and environmental stochasticity ([04 — Population growth](04-population-growth.md)).

Losses from habitat reduction are therefore calculable in advance (**extinction debt**):

| Habitat change | z = 0.25 | z = 0.30 |
| --- | --- | --- |
| Area halved | S falls to 0.84 → **~16% lost** | S falls to 0.81 → **~19% lost** |
| 90% destroyed | S falls to 0.56 → **~44% lost** | S falls to 0.50 → **~50% lost** |

The familiar rule of thumb — **destroy 90% of habitat and lose about half the species** — is S = cA^z at A = 0.1 with z ≈ 0.3.

## Island biogeography: fragments as islands

**MacArthur–Wilson theory** explains *why* the relationship holds, treating richness as the balance of two rates:

```
distance from source ─► immigration
   far ─► LOW      near ─► HIGH

island area ─► extinction
   small ─► HIGH (small populations, fewer niches)     large ─► LOW

S rises until immigration = extinction ─► S* (equilibrium)
```

| Island type | Immigration | Extinction | Equilibrium S* |
| --- | --- | --- | --- |
| **Large, near mainland** | High | Low | **Highest** |
| **Large, far** | Low | Low | Intermediate (colonist-poor) |
| **Small, near** | High | High | Intermediate (extinction-prone) |
| **Small, far** | Low | High | **Lowest** |

**S\* is a dynamic equilibrium**: the *identities* of species turn over continuously while the *count* stays roughly constant.

### Habitat fragments as islands, and reserve design

A woodlot surrounded by farmland is an island in a hostile sea, so the design rules follow directly:

| Design principle | Theoretical basis | Practical form |
| --- | --- | --- |
| **Make reserves large** | Area ↑ → extinction ↓ → S\* ↑ | One large reserve preferred over several small (SLOSS) |
| **Keep them near sources** | Distance ↓ → immigration ↑ → recolonisation | Buffer zones, proximity to wilderness cores |
| **Connect fragments** | Corridors raise immigration and gene flow | Corridors, hedgerows, stepping stones; expect local turnover and manage it as a metapopulation |

Corridors also deliver the **rescue effect** — a dwindling population reinforced by immigrants — the same gene flow that slows inbreeding ([03 — Genetic drift and gene flow](../06-evolution/03-genetic-drift-and-gene-flow.md)).

## Disturbance, succession, and the intermediate disturbance hypothesis

**Ecological succession** is the ordered change in community composition after disturbance or on a new surface. The dividing question is one thing: **is there soil?**

| Feature | **Primary succession** | **Secondary succession** |
| --- | --- | --- |
| Starting substrate | **Bare rock, lava, till — no soil, no seed bank** | **Soil (and usually seed bank) already present** |
| Typical start | Retreating glacier, cooled lava, new island | Fire, abandoned farmland, clear-cut |
| Speed | Very slow — soil must be *built* | Faster — soil and biota are inherited |
| Pioneers | **Lichens and cyanobacteria**, then mosses | Fast grasses, weeds, surviving resprouters |
| Classic sequence | **rock → lichen → moss → soil → plants → shrubs → forest** | field → weeds → grasses → shrubs → forest |

The primary sequence is mechanistic: **lichens** (a fungus–alga partnership, [04 — Fungi and protozoa](../07-microbiology/04-fungi-and-protozoa.md)) secrete acids that pit rock and trap dust plus their own decaying tissue, manufacturing the first millimetres of soil; only then can mosses and vascular plants establish. Each stage **modifies the environment so the next becomes possible and itself becomes impossible** — **facilitation**. **Pioneer species** are stress-tolerant, highly dispersive, short-lived, and hugely fecund; intermediate stages are dominated by faster competitors; the classical terminal stage is the **climax community**.

### The climax concept and its critique

The classical (Clementsian) view held that succession ends in a stable **climax** fixed by climate. The modern critique: many communities are **not** single-species equilibria, because disturbance, dispersal limitation, and historical contingency keep them in flux; **disturbance-maintained systems** — grasslands kept open by fire and grazing — would convert to forest if left untouched, so their "climax" *is* the disturbance; and **alternative stable states** exist that do not simply reverse when pressure is removed. Succession is therefore a **tendency with a variable endpoint**, not a ladder.

### The intermediate disturbance hypothesis

The **intermediate disturbance hypothesis (IDH)** predicts that **diversity is maximal when disturbance is neither too rare nor too severe**.

| Disturbance | What happens | Diversity |
| --- | --- | --- |
| **Low** | **Competitive exclusion** runs unopposed; the best competitor monopolises space and resources | **Low** — a few dominants ([05 — Ecological relationships](05-ecological-relationships.md)) |
| **Intermediate** | Dominants removed often enough to open gaps, but not so severely that everything is wiped; gaps are colonised by mixed competitors and dispersers | **Highest** — coexistence of strategies across a patch mosaic |
| **High** | Only severe-damage tolerators survive; recolonisation repeatedly reset | **Low** — stress-tolerant pioneers only |

The mechanism is a **trade-off between competitive ability and colonisation or stress tolerance**: strong competitors win in undisturbed patches but arrive poorly in gaps; good colonisers lose in place but reach gaps first. Interrupt competitive exclusion and diversity rises — but only locally; regionally the IDH can reverse, so it is a hypothesis, not a law.

## Threats to biodiversity

Every major threat is a mechanism you have already met, applied to whole communities.

| Threat | Mechanism | Signature consequence |
| --- | --- | --- |
| **Habitat loss and fragmentation** — *the largest driver* | Area ↓ → extinction ↑, immigration ↓; small populations → **drift and inbreeding** ([03 — Genetic drift](../06-evolution/03-genetic-drift-and-gene-flow.md)) | **Extinction debt**; alleles lost before species are |
| **Invasive species** | **Competitive exclusion of naive communities** — no coevolved defences ([05 — Ecological relationships](05-ecological-relationships.md)) | Homogenised biotas; island and lake faunas worst |
| **Overexploitation** | Harvest above the **intrinsic growth rate** ([04 — Population growth](04-population-growth.md)) | Cod collapse; bycatch; **fisheries-induced evolution** |
| **Pollution** | Nutrient enrichment → bloom → hypoxia; toxins **biomagnify** up chains ([03 — Nutrient cycles](03-nutrient-cycles.md)) | Coastal dead zones; DDT eggshell thinning |
| **Climate change** | **Biome shift faster than migration** — species cannot cross hostile matrix fast enough | Extinction traps; coral bleaching; phenological mismatch |
| **Disease** | Epidemics in **naive or stressed hosts** ([05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md)) | **Chytrid fungus** driving amphibian extinctions; **white-nose syndrome** in bats |

Fungal wildlife disease is the emerging pattern — the organisms of [04 — Fungi and protozoa](../07-microbiology/04-fungi-and-protozoa.md) are among the most destructive pathogens known, and **thermal sensitivity of fungal growth** interacts with host physiology in either direction.

These threats **synergise**: a fragmented, genetically poor population cannot adapt to a warming climate, is more susceptible to an emerging pathogen, and is then harvested faster than it recovers.

## Conservation biology

**Conservation biology** prevents extinction, restores function, and sustains genetic variation. Its tools divide by *where organisms are kept* and *which level of biodiversity is managed*.

### In-situ conservation

**In-situ conservation** protects species **in their natural habitat**, where evolution continues.

| Strategy | Mechanism it exploits |
| --- | --- |
| **Protected areas and reserves** (incl. marine protected areas) | Area ↑ → extinction ↓, S\* ↑ (MacArthur–Wilson); stock rebuilds and spills over |
| **Wildlife corridors, stepping stones** | Immigration and **gene flow** ↑ → rescue effect, less drift and inbreeding |
| **Community management, harvest quotas** | Keeps human take below recruitment; aligns incentives with population growth ([04 — Population growth](04-population-growth.md)) |
| **Translocation, assisted migration** | Substitutes human dispersal for immigration the landscape no longer allows |

### Ex-situ conservation

**Ex-situ conservation** removes organisms from the threat *in place* — a holding strategy that preserves options.

| Strategy | Examples | Strength | Limitation |
| --- | --- | --- | --- |
| **Seed banks** | **Svalbard Global Seed Vault**, millennium seed banks | Cheap, long-lived, genetically diverse, duplicated worldwide | Cannot hold animals, clonal or recalcitrant-seeded species, or ecological interactions |
| **Botanic gardens** | Living collections, recovery programmes | Breeding material, reintroduction source | Often genetically narrow; needs permanent funding |
| **Captive breeding** | Giant panda, Arabian oryx, condor | Demographic insurance; reintroduction pipelines | **Domestication risk**, lost natural behaviour, small Ne, no ecosystem role |

### Genetic management

Because biodiversity has a genetic level, conservation must manage **populations**, not just species lists.

| Concept | Why it matters |
| --- | --- |
| **Minimum viable population (MVP)** — smallest size with a stated probability (e.g. 95%) of persisting for a stated time (e.g. 100 years) | Folds demographic stochasticity, environmental variance, and **drift/inbreeding** into one target — typically hundreds to thousands |
| **Effective population size (Ne)** — idealised size losing heterozygosity at the same rate | Far smaller than census N: 10,000 counted may be Ne ≈ hundreds |
| **Genetic rescue** — introducing individuals from another population | Injects alleles and reverses inbreeding depression; the Florida panther revived by Texas puma introduction |

Genetic and ecological halves must run together: a reserve meeting the MVP but isolated still drifts toward inbreeding, while a corridor joining fragments can spread **outbreeding depression** or disease — so conservation needs both a population geneticist and a community ecologist ([01 — Levels of organization](01-levels-of-organization.md)).

### Restoration ecology

**Restoration ecology** returns a degraded system to a self-sustaining trajectory — succession deliberately accelerated.

```
degraded site ─► remove the stressor (drainage reversed, invader cleared)
             ─► rebuild substrate (soil, hydrology, channel form)
             ─► reintroduce structure and function
                (pioneers → canopy; pollinators, dispersers, mycorrhizae)
             ─► reconnect to a source population (corridor)
                        │
                        ▼
        self-replacing community with ongoing natural selection
```

Success is measured in **function restored** and **self-replacement**, not species planted: supply propagules where immigration is low, impose controlled disturbance where competitive exclusion has frozen the system, and monitor diversity *and* process rates.

## Relevance to medicine and the real world

**Biodiversity is a pharmaceutical reservoir.** Aspirin derives from salicylic acid long extracted from willow bark; **penicillin** came from *Penicillium* exploiting bacterial competitors, as described in [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md); **quinine** comes from cinchona bark; **artemisinin**, the backbone of combination therapy against *Plasmodium falciparum*, came from *Artemisia annua*; **lovastatin and related statins** are fungal metabolites from *Penicillium*. These compounds are **weapons in microbial and plant competition**, which is why they are distributed across the tree of life — and why losing species loses potential drugs.

**Biodiversity also buffers human disease through the dilution effect.** As diversity falls, the surviving community is often dominated by **competent reservoir hosts** — species that support pathogen replication and transmit efficiently — so human infection risk rises. The chain: diverse community → many reservoir-poor hosts → transmission attempts "wasted" on incompetent hosts → reservoir prevalence falls → spillover to humans falls. This is the transmission ecology of [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md); dilution is not universal, so the claim is that **biodiversity loss can increase human infection risk**, not that it always does.

**Ecosystem services are the flow of benefits from functioning ecosystems, and several carry direct economic value.** Wild pollinators contribute a large share of crop yield; wetlands and soil microbiomes purify water; forests, soils, and oceans sequester carbon. All three depend on the cycles in [03 — Nutrient cycles](03-nutrient-cycles.md) and the trophic transfers in [02 — Food chains, webs, and trophic levels](02-food-chains-webs-and-trophic-levels.md): break the community and the flux stops, and the replacement cost falls on the public purse. Valuation is contested; the biology is not — **function depends on the organisms performing it**.

**Food security is a biodiversity problem at the genetic level.** Modern agriculture runs on a narrow genetic base — a handful of high-yield cultivars — the configuration behind the Irish potato famine and the Gros Michel collapse. Wild relatives and landraces are the reservoir of alleles for drought, salinity, and disease tolerance, and breeding is a search through that reservoir. Preserving agrobiodiversity is medical in effect, because famine and malnutrition are health outcomes; the plant biology involved belongs to [08 — Plant biology](../08-plant-biology/).

**Resistance itself is a biodiversity-and-evolution phenomenon.** Antibiotic resistance genes are **ancient and environmental** — they circulate in soil and water microbes where they evolved as competitive weapons long before hospitals existed ([02 — Natural selection](../06-evolution/02-natural-selection.md)). Antibiotic use selects in those communities, and resistant lineages move between environment, livestock, and patients by horizontal gene transfer — so stewardship is partly ecological policy.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| Richness vs diversity | **Richness is the species count; diversity adds evenness.** 10 equally abundant species beats 10 species where one holds 91% of individuals. |
| Genetic vs species diversity | Genetic diversity is **alleles within one species**; species diversity is **differences between species**. A population can be genetically impoverished with its species count unchanged. |
| Island biogeography fixes a species list | S\* is an equilibrium in **rates**, not identities — species turn over while the count stays roughly constant. |
| Succession always ends in a stable climax | Many communities are **disturbance-maintained** and can occupy alternative stable states; the climax is a tendency, not a rule. |
| Intermediate disturbance means "disturbance is good" | It is **hump-shaped**: low *and* high disturbance both lower diversity; only moderate disturbance maximises it by interrupting competitive exclusion. |
| Ex-situ conservation substitutes for habitat | Seed banks and zoos **preserve options**, not ecosystems — no food web, pollination, or nutrient cycling. A backup, not a replacement. |
| Conservation is only counting species | It must manage **alleles too**: MVP, effective size, gene flow, and genetic rescue decide persistence. |
| Biodiversity loss is unrelated to human health | It connects through **drug discovery, the dilution effect on zoonoses, ecosystem services, crop genetic resources, and environmental resistance genes.** |

## Key facts

- Biodiversity has **three levels**: **genetic** (alleles within species), **species** (richness **and** evenness), and **ecosystem** (biomes, habitats, their processes).
- **Monocultures are genetically vulnerable** — the Irish potato famine (one clone vs *Phytophthora infestans*) and banana **Panama disease** (*Fusarium* vs Gros Michel/Cavendish): uniform susceptibility, no resistant allele present.
- **Richness** = species count; **evenness** = equality of abundance: 10 equally abundant species is more diverse than 10 species with one holding 91% of individuals.
- The **insurance (redundancy) hypothesis**: overlapping roles let a process survive losing one species; **keystone species** are the non-redundant exceptions.
- Experiments manipulating **richness independently of environment** show diverse communities **resist invasion, recover faster, and fluctuate less** (portfolio effect).
- **Species–area**: **S = cA^z** (log–log linear, z ≈ 0.15–0.35); **~90% habitat loss ⇒ ~50% species loss** at z ≈ 0.3.
- **MacArthur–Wilson**: S\* is where **immigration = extinction**; **large, near islands hold most species**, with identities turning over while counts stay constant and habitat loss causing **extinction debt**. Reserve design follows: **bigger, closer to source, connected** (corridors give the **rescue effect**).
- **Primary succession starts from bare rock** (lichen → moss → soil → plants); **secondary succession starts with soil**; succession is a tendency with a variable endpoint.
- **Intermediate disturbance hypothesis**: moderate disturbance maximises diversity by preventing **competitive exclusion**, via the trade-off between competitive ability and colonisation or stress tolerance.
- **Habitat loss and fragmentation is the largest driver**; invasives, overexploitation, pollution, rapid climate shift, and disease follow — and they **synergise**.
- **Conservation** = in-situ (reserves, corridors, community management) + ex-situ (seed banks, botanic gardens, captive breeding) + **genetic management** (MVP, Ne, genetic rescue) + restoration.
- **Biodiversity underpins medicine**: aspirin, penicillin, quinine, artemisinin, statins; the **dilution effect** on zoonoses; ecosystem services; crop genetic resources; environmental **resistance genes**.

## Practice questions

**1. Two woodland plots each hold 10 bird species. Plot A has 10 individuals of each; plot B has 91 of one species and 1 of each other. Which is correct?**

A. Plot B has greater species richness
B. Richness is equal, but plot A has greater diversity because its evenness is higher
C. The plots have equal diversity because richness is identical
D. Plot B is more diverse because it holds more individuals in total

**Answer: B**

Explanation: Both hold 10 species, so richness is identical; diversity adds **evenness**, which A has. Total abundance (D) plays no part in diversity indices.

---

**2. Gros Michel and Cavendish bananas are devastated or threatened by Panama disease because bananas**

A. Have no defence against fungi of any kind
B. Are propagated clonally, so the crop has almost no genetic diversity for selection to act on
C. Lack cell walls, allowing hyphal penetration
D. Cannot mutate to form resistant types

**Answer: B**

Explanation: Vegetative propagation makes every plant near-identical — a **monoculture with minimal allelic variation** — so one pathogen genotype infects the entire crop. With no resistant allele present, selection has nothing to favour.

---

**3. Which statement about the species–area relationship S = cA^z is correct?**

A. Doubling area always doubles the number of species
B. Plotted on log–log axes it is linear, with slope z usually about 0.15–0.35
C. It applies only to oceanic islands
D. It cannot predict losses when habitat is destroyed

**Answer: B**

Explanation: log S = log c + z log A is linear with slope **z** usually 0.15–0.35. Because z < 1, doubling area does not double species (A); the relation holds on mainland (C) and predicts loss from habitat reduction (D).

---

**4. Under MacArthur–Wilson theory, species richness is highest on an island that is**

A. Small and far from the mainland
B. Large and far from the mainland
C. Small and near the mainland
D. Large and near the mainland

**Answer: D**

Explanation: Proximity raises **immigration** and area lowers **extinction**; S\* is where the two rates meet. Small islands suffer high extinction (A, C); distant ones stay colonist-poor (B).

---

**5. After a new island forms, its species number rises then fluctuates around a stable value. This means that**

A. The identities of the species are fixed permanently
B. Species continually arrive and die out while the total count stays roughly constant
C. Evolution stops once equilibrium is reached
D. Immigration and extinction both cease at equilibrium

**Answer: B**

Explanation: S\* is a **dynamic equilibrium of rates** — immigration and extinction continue at equal magnitude, so identities turn over while the count stays stable. Neither process ceases at equilibrium (D).

---

**6. Primary succession on newly cooled lava is best described as**

A. Grasses → lichens → shrubs → mosses
B. Lichens → mosses → soil formation → vascular plants
C. Mature forest → pioneer weeds → bare rock
D. Soil present from the start and simply fertilised

**Answer: B**

Explanation: Primary succession starts with no soil, so lichens and cyanobacteria weather rock first, mosses then build substrate, and only then can plants root. D describes **secondary** succession.

---

**7. The intermediate disturbance hypothesis predicts peak diversity at moderate disturbance because**

A. Severe disturbance creates the most niches
B. Moderate disturbance repeatedly removes dominant competitors, preventing competitive exclusion while leaving populations able to recolonise
C. Disturbance permanently eliminates all weak competitors
D. Low disturbance maximises evenness because no species ever declines

**Answer: B**

Explanation: The mechanism is a **trade-off between competitive ability and colonisation or stress tolerance**. No disturbance lets dominants exclude others, extreme disturbance leaves only tolerators, and moderate disturbance opens gaps for both.

---

**8. Which pairing of conservation strategy and biodiversity level is correct?**

A. Wildlife corridors — genetic diversity, via increased gene flow
B. Seed banks — primarily ecosystem diversity
C. Captive breeding — species richness of the surrounding community
D. Community-based reserves — allelic richness within one locus

**Answer: A**

Explanation: Corridors raise **gene flow** between populations, countering drift and inbreeding — a genetic-level intervention. Seed banks (B), captive breeding (C), and community reserves (D) act at other levels.

---

**9. White-nose syndrome is killing hibernating bats via the fungus *Pseudogymnoascus destructans*. This threat is best classified as**

A. Pollution, because the fungus releases cave toxins
B. Emerging disease — a fungal pathogen exploiting stressed hosts with no effective defence
C. Habitat fragmentation, because the fungus blocks cave entrances
D. Overexploitation, because bats are harvested during hibernation

**Answer: B**

Explanation: The fungus depletes the fat reserves of torpid bats until starvation — an **emerging infectious disease**. It mirrors the chytrid fungus driving amphibian declines ([04 — Fungi and protozoa](../07-microbiology/04-fungi-and-protozoa.md)).

---

**10. Which statement best links biodiversity loss to human medicine?**

A. Diverse communities always raise human infection through the dilution effect
B. It supplies pharmaceutical compounds, buffers zoonotic transmission, and its loss may raise infection risk and shrink future drug discovery
C. Ecosystem services are unaffected because nutrient cycles are chemical, not biological
D. Antibiotic resistance genes originated in hospitals and exist nowhere else

**Answer: B**

Explanation: Biodiversity supplies a **pharmaceutical reservoir**, a possible **dilution effect**, and ecosystem services. Dilution is conditional (A); nutrient cycles depend on organisms (C); resistance genes are **ancient and environmental** (D).
