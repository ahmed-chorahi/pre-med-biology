# Ecological Relationships

## Why it matters

Every other chapter describes a population in isolation; this one describes what happens when **two populations meet** — what eats what, what competes with what, and what each depends on.

The organising idea is accounting: score every interaction by its **effect on each partner** — beneficial (+), harmful (−) or neutral (0) — and the score predicts what selection does next. −/− drives divergence or exclusion; +/− drives a coevolutionary arms race; +/+ drives reciprocal specialisation and needs a mechanism to stop cheating.

Three classes are already familiar from a different angle. **Parasitism is host–pathogen interaction read from the host's side** — the capsules, toxins and evasion tactics of [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md), rescored as ecology. **Mutualism underpins agriculture**: nitrogen fixation, mycorrhizal trading and pollination are +/+ interactions humans manage, subsidise and accidentally break. **Competition explains distribution** — why a species is abundant here and absent a few kilometres away, and why a healthy gut resists invasion. The score also selects the mechanism: [02 — Natural selection](../06-evolution/02-natural-selection.md) on two species at once.

## The master table

| Interaction type | Effect on A | Effect on B | Example | Evolutionary outcome |
| --- | --- | --- | --- | --- |
| **Competition** | − | − | Two finch species on one seed supply | Exclusion, or divergence: partitioning, character displacement |
| **Predation** | + | − | Wolf kills elk; ladybird eats aphids | Coevolutionary arms race; prey rarely driven extinct |
| **Herbivory** | + | − | Caterpillar eats a leaf; rabbit grazes turf | Arms race: plant defences (thorns, tannins, alkaloids) against counter-adaptations |
| **Parasitism** (+/−, long-lived, usually does not kill immediately) | + | − | Tapeworm in the gut; *Plasmodium* in a red cell | Arms race; virulence set by a transmission–damage trade-off |
| **Mutualism** | + | + | Mycorrhiza (P for C); rhizobium–legume (N for C); cleaner fish | Reciprocal specialisation, policed by partner choice and sanctions |
| **Commensalism** | + | 0 | Remora on a shark; barnacles on a whale | Little selection on B; usually resolves to weak +/+ or +/− |
| **Amensalism** | − | 0 | Black walnut juglone inhibiting neighbours | Selection on A only; B too unaffected to respond |

Two warnings. **Predation, herbivory and parasitism share the +/− score**, differing only in *how* the resource is taken. And **commensalism (+/0) is rare**: altering an energy budget almost always helps or harms it, so "+/0" is usually a measurement failure.

## Competition

**Competition** is any interaction in which two individuals or species draw on the same limiting resource, so each lowers the other's fitness. It is the only class that is **−/− for both parties regardless of who wins** — both leave with less than they would have had alone, so competitive ability is about *who suffers least*, not who gains most.

### Intraspecific vs interspecific competition

| | **Intraspecific** | **Interspecific** |
| --- | --- | --- |
| **Between** | Members of the same species | Members of different species |
| **Overlap** | Perfect — identical requirements | Partial — similar niches |
| **Consequence** | Density dependence: sets *K* and shapes logistic growth (see [04 — Population growth](04-population-growth.md)) | Exclusion, character displacement or resource partitioning — which species live together |

### The competitive exclusion principle

Gause's principle, from his *Paramecium* experiments: **two species cannot coexist indefinitely on one limiting resource; one is eliminated, or the populations diverge until they no longer compete for the same thing.**

```
two species, ONE limiting resource, identical requirements
   → the slightly better competitor captures more of it
      → its population grows, the other's declines
         → EXCLUSION
   OR → variants using a DIFFERENT part of the resource win
        → niches diverge → COEXISTENCE
```

In Gause's cultures *P. caudatum* vanished when both shared one food yet persisted on different foods: what is excluded is a *duplicate*.

### How coexistence is restored

| Mechanism | What changes | Example |
| --- | --- | --- |
| **Resource partitioning** | Each species uses a *different* resource or part of one | Warblers foraging in different zones of one tree; anolis on different perches |
| **Character displacement** | Heritable *traits* diverge — beak size, body size, mouthparts | Darwin's finches: beaks diverge more where species co-occur |
| **Temporal separation** | Feeding or flowering shifts to different times | Day-active vs night-active foragers; spring vs summer flowering |

**Character displacement** is the evolutionary resolution — the link to [04 — Speciation](../06-evolution/04-speciation.md): where ranges overlap, intermediates are outcompeted by *both* specialists, so selection exaggerates the difference.

### Interference vs exploitation

| | **Interference competition** | **Exploitation competition** |
| --- | --- | --- |
| **Mechanism** | Direct antagonism — fighting, aggression, chemical inhibition | Indirect: each consumer depletes the shared resource |
| **Contact required** | Yes | No — the loser may never meet the winner |
| **Examples** | Territorial disputes; ant wars; plants poisoning neighbours | Two predators draining one prey pool; microbes exhausting iron |

Exploitation competition is why **a competitor can be excluded without ever meeting the winner**, and why microbial competition is invisible on a plate until you ask what the winner secreted.

## Predation and herbivory

**Predation** is a +/− interaction in which one organism kills and consumes another; **herbivory** carries the same sign but takes tissue from a living organism that usually survives. Both generate escalating adaptation.

### Predator–prey dynamics

The Lotka–Volterra insight is best carried as a circular causal chain:

```
prey density ↑
   → more food per predator → predator birth rate ↑
      → predator density ↑
         → predation mortality ↑ → prey density ↓
            → less food per predator → predator birth rate ↓
               → predator density ↓ → predation released
                  → prey recover → CYCLE REPEATS
                  (phase lag: prey peak precedes predator peak)
```

Two features recur: **the peaks are out of phase** (the prey maximum comes first) and the cycle is **negative feedback**, each success containing the seed of its own reversal. Real systems rarely cycle as clean sinusoids, so the chain is a model (trophic dynamics: [02 — Food chains, webs and trophic levels](02-food-chains-webs-and-trophic-levels.md)).

### Coevolutionary arms races

Because each side is the other's selection pressure, predator and prey evolve **reciprocal counter-adaptations**: speed against speed (pronghorn–cheetah), camouflage against visual acuity (peppered moth against a bird's search image), toxicity against tolerance (monarch against a garter snake with resistant sodium channels), armour against crushing jaws. Any prey variant that escapes better leaves more offspring; any predator that captures better leaves more offspring; each improvement shifts the other's optimum, so the two appear as **matched pairs** — [02 — Natural selection](../06-evolution/02-natural-selection.md) on two species at once.

### Why predators rarely drive prey extinct

Pure Lotka–Volterra mathematics allows prey extinction; nature resists it via

- **Predator switching** — prey switch to alternatives when one becomes scarce, releasing the declining species.
- **Spatial refuges** — prey survive where predators cannot reach and repopulate from there.
- **Density-dependent reproduction** — survivors breed into emptied space faster than predation removes them.
- **Arms-race equilibrium** — escape improves as the population falls, so the last individuals are hardest to catch.

Predation-driven extinction is therefore reserved for **introduced predators meeting naive populations** — rats and cats on islands — where none of these defences has an evolutionary history.

### Herbivory: the plant's side of +/−

A herbivore gains energy without killing the plant, so the optimal defence deters feeding at acceptable cost — and defence competes for the carbon fixed in [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md), making cheap defences constitutive and expensive ones inducible.

| Defence type | Mechanism | Example |
| --- | --- | --- |
| **Physical / structural** | Make tissue hard, sharp or inaccessible | Thorns and spines, hooked trichomes, silica phytoliths that wear down teeth |
| **Chemical** | Reduce digestibility or poison the herbivore | **Tannins** bind proteins and enzymes → lower digestibility; **alkaloids** (nicotine, caffeine) are neurotoxic; **cyanogenic glycosides** release HCN on damage |
| **Indirect** | Recruit the herbivore's enemies | Damaged leaves release **volatiles** that attract parasitoid wasps and predatory mites |

**Latex and resin canals** are pressurised so tissue breach gums up mouthparts instantly, and **indirect defence** converts the plant's −/− with the herbivore into a +/+ with its natural enemy.

## Parasitism

**Parasitism** is a +/− interaction in which one organism (the parasite) lives **in or on** another (the host), depends on it for resources, and **usually does not kill the host immediately**.

| Feature | Predation | Parasitism |
| --- | --- | --- |
| **Contact** | Kills and consumes, then leaves | Lives **in** (endoparasite) or **on** (ectoparasite) the host |
| **Killing** | Immediate at the encounter | Usually **delayed or absent** — host survives |
| **Size** | Usually larger than prey | Usually **much smaller** than the host |
| **Resource use** | Biomass converted at once | Drawn down slowly while the host lives |

Dependence is the defining point: killing the host instantly destroys the parasite's own food supply, so selection favours **reduced virulence** where transmission needs a mobile host — virulence stays high where it does not.

### Parasite life cycles and their ecological consequences

Many parasites cannot complete their life cycle in one host; complexity is an adaptation to **transmission risk**:

| Life-cycle feature | Mechanism | Consequence |
| --- | --- | --- |
| **Definitive vs intermediate hosts** | Sexual reproduction in one host, larval development in another | Two populations to infect — prevalence decoupled from host density |
| **Trophic transmission** | Larva encysts in prey, waiting to be eaten | Host manipulation (ants climbing grass, rodents losing fear of cats) |
| **Vector transmission** | A blood-feeding arthropod moves the parasite between hosts | Control targets vector ecology — insecticide, bed nets, reservoirs (see [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md)) |
| **Vertical transmission** | Parent directly to offspring | Low virulence favoured — a dead parent transmits nothing |

**Complex life cycles spread risk across hosts and habitats**, so no single control point eliminates the parasite — malaria control needs mosquito ecology, drugs and reservoir management at once.

### Parasitoids: the predation–parasitism boundary

**Parasitoid wasps** (Ichneumonidae, Braconidae) blur the boundary deliberately: the female lays an egg in a living caterpillar, the larva feeds on non-essential tissues while the host keeps growing, and only then is the host killed as the wasp pupates — parasitism during development, predation at the end.

Parasitoids are treated ecologically as predators because they eventually kill every individual they attack; the only difference from predation is *timing*. They are also the backbone of **biological control**, since a parasitoid's host range can be narrow enough to target a pest alone.

### The virulence evolution trade-off

Why do pathogens harm hosts at all, when a dead host is a dead end? The standard answer is a **trade-off between transmission and host damage**:

```
replicate faster → more transmission stages shed → more infections
   BUT → greater tissue damage → host immobilised or dead sooner
      → less time and opportunity for transmission
         ↓
optimum virulence is INTERMEDIATE
```

**Virulence evolves upward when transmission does not depend on host mobility** (waterborne or environmentally shed pathogens) and **downward when transmission needs a healthy, active host** (respiratory viruses spread by coughing). Crucially, **virulence is not a fixed property of a species** — it shifts with host density, co-infection and route, which is why *Staphylococcus aureus* is harmless on skin and lethal in blood. Myxoma virus in Australian rabbits is the textbook case: virulence fell toward an intermediate optimum while rabbit resistance rose.

## Mutualism

**Mutualism** is a +/+ interaction. Because each side is a resource the other could exploit, the puzzle is not why it arises but **why it persists** — the answer is mechanisms that punish cheating.

In an **obligate** mutualism neither partner completes its life cycle alone, so losing one means extinction of the other (lichens, yucca and yucca moth, fig–fig wasp, corals and zooxanthellae). In a **facultative** mutualism both survive apart and the interaction merely raises fitness (mycorrhizae, rhizobium–legume, cleaner fish, gut microbiota).

### Mechanisms that stabilise mutualism

Reciprocal benefit alone does not stop cheating — a mutant taking the benefit without paying would spread. Three policing mechanisms do:

| Mechanism | How it works | Example |
| --- | --- | --- |
| **Partner choice** | Preferentially associate with the better partner *before* committing | Legumes infect roots with the best nitrogen-fixing strains first |
| **Sanctions** | Punish a partner that underperforms *after* association | A legume **cuts oxygen to nodules that are not fixing nitrogen**, so the cheater loses its protected niche; figs abort over-parasitised fruits |
| **Vertical transmission** | Pass the partner to offspring, aligning interests across generations | Inherited bacterial symbionts of aphids and many insects |

Choice and sanctions let cooperation out-earn cheating, making the +/+ relationship evolutionarily stable.

### Mycorrhizae: phosphorus for carbon

**Mycorrhizal fungi** thread into plant root cells and extend the effective root surface by orders of magnitude: the plant donates photosynthetic **C** (hyphae cannot fix carbon) in exchange for soil **P**, water and micronutrients that roots scavenge too slowly for. Hyphae are far thinner than roots and reach soil volume roots cannot, and phosphorus — immobile in soil, depletable within millimetres of a root — is the currency. **Around 80–90% of land plant species form mycorrhizae**, so this is the default condition of plant life (mechanisms: [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md)).

### Rhizobium–legume nitrogen fixation

Atmospheric N₂ is inert and legumes cannot use it; **Rhizobium** bacteria solve this inside specialised root nodules:

```
N₂ + 8H⁺ + 8e⁻ + 16ATP ──nitrogenase──► 2NH₃   (inside the nodule)
plant: O₂-free environment, carbon, ATP → bacteroid
bacterium: nitrogenase, protected from O₂ → NH₃ → amino acids
   → plant growth, fed by plant photosynthate
```

Nitrogenase is **irreversibly inactivated by oxygen**, so the nodule must stay anaerobic — usually with **leghaemoglobin**, which binds O₂ and gives active nodules their pink colour. That single constraint explains the whole symbiosis: the plant cannot fix nitrogen without an anaerobic partner, and the bacterium cannot get carbon without a photosynthetic host.

### Pollination, gut microbiota, cleaner fish

**Pollination** is +/+ in which the animal gains food (nectar, pollen protein) and the plant gains **directed gamete transfer** that wind cannot deliver efficiently. Matching traits evolve on both sides — nectar spur length to pollinator tongue, colour and scent tuned to pollinator senses — and many plants depend on a single pollinator (plant machinery: [06 — Plant reproduction and alternation of generations](../08-plant-biology/06-plant-reproduction-and-alternation-of-generations.md)).

The **gut community** gains a warm, continuously fed habitat; the host gains vitamin synthesis, short-chain fatty acids from fibre and **colonisation resistance** — residents outcompeting incoming pathogens for nutrients, adhesion sites and space. That is competition as a therapeutic barrier, which is why broad-spectrum antibiotics can cause disease by removing a +/+ partner (see [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)).

On Indo-Pacific reefs, **cleaner wrasse** (*Labroides dimidiatus*) remove ectoparasites from client fish, which queue in a trance-like pose. What stabilises it is **partner choice and punishment**: clients visit preferred cleaners more, and cleaners that cheat by biting mucus are chased or abandoned.

## Commensalism and amensalism

| Type | Example | Mechanism |
| --- | --- | --- |
| **+ / 0** | **Remora and shark** | Suction disc on the modified dorsal fin gives transport, protection and scraps; the shark measures no gain or loss |
| **+ / 0** | **Barnacles on whales; cattle egrets; epiphytes on trees** | Transport into food-rich water; cattle stir insects from grass; epiphytes gain light without parasitising the host |
| **− / 0** | **Black walnut (*Juglans nigra*) juglone** | Roots and litter release **juglone**, which inhibits respiration and electron transport in neighbours |
| **− / 0** | **Shade cast by a tall tree** | The plant beneath is light-limited; the tall tree gains nothing — the shading is incidental |

**Commensalism (+/0)** means one benefits and the other is unaffected; **amensalism (−/0)** means one is harmed and the other is unaffected. The caveat matters: **"+/0" is usually a measurement not made carefully enough** — a remora's cleaning may slightly help its host, its drag may slightly hurt, and juglone autotoxicity on the walnut itself is measurable, so precise accounting usually converts a supposed commensalism into a weak mutualism or parasitism.

## Mimicry and anti-predator signalling

**Mimicry** is the resemblance of one species to another, and its payoff depends entirely on what predators have already learned.

| | **Batesian mimicry** | **Müllerian mimicry** |
| --- | --- | --- |
| **Mimic** | Harmless (palatable) | Harmful (unpalatable or dangerous) |
| **Relationship** | +/− (mimic cheats at the model's expense) | +/+ (shared predator education) |
| **Example** | **Hoverfly** mimicking a stinging **wasp**; king snake copying a coral snake | Two unpalatable butterfly or wasp species converging on one banding pattern |

The evolutionary logic of Batesian mimicry is **negative frequency dependence**:

```
mimic rare, model common
   → predators meet the model first and learn to avoid the pattern
      → the rare mimic inherits that avoidance → HIGH protection
mimic becomes COMMON
   → predators meet the mimic more often than the model
      → they learn the pattern predicts a free meal
         → avoidance collapses → protection lost
```

A Batesian mimic gains **most when it is rare**, which is why mimics are usually far less abundant than their models. Müllerian mimicry works differently: two toxic species with separate patterns each need their own predator-education programme, paid for in killed predators, so converging on **one shared signal** lets a single learning event teach avoidance of both — a frequency-independent +/+ benefit.

Camouflage and warning colouration sit either side of this spectrum. **Crypsis** (background matching, disruptive coloration, countershading, masquerade as a leaf or twig) avoids detection by sending no signal at all; **aposematism** (bright, conspicuous patterns) advertises an *honest* defence after detection. Batesian mimicry reuses that warning pattern dishonestly; Müllerian mimicry shares it honestly — opposite solutions to one predator pressure, both reading predator learning psychology.

## Keystone species

A **keystone species** is one whose **effect on community structure is disproportionate to its abundance** — remove it and the community reorganises. It is a statement about *influence per unit biomass*, not about being large or numerous.

### The original experiment: *Pisaster* on mussel beds

Robert Paine's intertidal experiment (Washington State, 1966) is the archetype. The sea star *Pisaster ochraceus* preys on mussels that would otherwise monopolise the rock face:

```
intact community:
Pisaster eats mussels → they cannot monopolise the substrate
   → barnacles, limpets, algae, anemones persist → HIGH diversity

remove Pisaster (experimental removal):
mussels overgrow the rock → competitor exclusion in fast forward
   → barnacles, limpets, algae driven off → diversity COLLAPSES
     (~15 species → 8)
```

The removal did not merely reduce a mussel population — it allowed a competitive −/− to run to exclusion, so diversity fell as a consequence. Paine's work founded the keystone concept and linked predation directly to competitive exclusion.

### Sea otters, urchins, and kelp forests

```
otters present → heavy predation on urchins → urchins low
   → kelp grazed lightly → KELP FOREST thrives
otters removed (fur trade) → urchins explode → grazing
   → kelp destroyed → low-diversity "urchin barren"
```

This is a **trophic cascade** — a predator's effect transmitted down two links to the base of the food web — and the clearest demonstration that one predator can determine the physical structure of a habitat (see [06 — Biodiversity](06-biodiversity.md)).

| | **Keystone species** | **Dominant species** |
| --- | --- | --- |
| **Abundance / biomass** | Often **small** relative to the community | **Largest** biomass or number |
| **Mechanism** | Interaction role — predation, mutualism, engineering | Sheer competitive dominance monopolising resources |
| **Effect of removal** | Community reorganises disproportionately to its biomass | Productivity or biomass falls roughly in proportion |
| **Diagnostic** | Effect ÷ biomass is large | Effect ≈ biomass |
| **Examples** | *Pisaster*, sea otter, keystone pollinators, tropical fig trees | Dominant kelp, dominant prairie grass, a single canopy tree |

A related category is the **ecosystem engineer** — a species that physically creates or modifies habitat (beavers, corals, earthworms) — and engineers often qualify as keystone species, since the structure they build is what the community lives in.

## Relevance to medicine and the real world

**The interaction classes are the infectious-disease classes.** Calling a pathogen a parasite is not a metaphor — it is the same +/− accounting read from the host's side: dependence on a living host, selection toward reduced virulence when transmission needs host mobility, and an arms race in which every immune defence has a counter-move. Everything in [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md) — capsules answering phagocytosis, antigenic variation answering memory — is the predator–prey arms race with the microbe as predator. Identify the benefit, the harm and the transmission route, and the virulence strategy follows.

**Mutualism is agricultural technology.** Rhizobial and mycorrhizal inoculants are sold because coating a seed with the right symbiont raises yield without fertiliser — a direct application of the P-for-C and N-for-C trades. The same logic explains **pollinator decline**: where crops are obligately animal-pollinated, losing the +/+ partner means losing the harvest, and why fumigation and broad-spectrum fungicides can cut the *next* season's yield — they destroy mutualists too (organismal detail: [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md)).

**Biological control replaces chemicals with +/− interactions.** Instead of poisoning a pest you introduce its predator, parasitoid or pathogen, and the interaction regulates itself. The successes — parasitoid wasps against scale insects, the cactus moth against prickly pear, *Bacillus thuringiensis* (Bt) and **bacteriophage** therapy — need an agent narrow enough in host range, since a generalist switches to native prey; **specificity of niche** is the engineering problem.

**Competition is the basis of colonisation resistance in the gut.** A healthy gut resists *Clostridioides difficile*, *Salmonella* and *Candida* not because they are absent but because resident microbiota already occupy the niche, exhaust the nutrients, hold adhesion sites and secrete bacteriocins — exploitation and interference competition as a therapeutic barrier. Broad-spectrum antibiotics remove the competitors and the niche refills with whatever arrives next, so antibiotic-associated diarrhoea and thrush are **competition released**, not toxicity — which is why faecal microbiota transplantation reinstates a competitive community rather than adding a drug.

**Antibiotic development exploits microbial competition deliberately.** Every antibiotic began as a chemical weapon in a microbial arms race — *Penicillium* poisoning its bacterial competitors, *Streptomyces* clearing the soil around it — and the original screen for zones of inhibition is literally **looking for interference competition in a petri dish**, with resistance as the counter-move. The same framework predicts disturbance: removing a keystone predator collapses diversity through competitive exclusion.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Predation, herbivory and parasitism have different signs" | All three are **+/−**; they differ in mechanism — kill-and-consume, feed without killing, or live in or on a long-term host. |
| "A parasite always kills its host" | The host must **usually survive** long enough to transmit; killing too fast destroys the parasite's own habitat. Predation kills at the encounter. |
| "Higher virulence is always favoured" | Virulence is a **trade-off**: more replication means more transmission but faster host damage, so selection usually favours an intermediate optimum. |
| "Batesian and Müllerian mimicry differ in which species looks like which" | They differ by **whether the mimic is harmful**: harmless = Batesian (mimic must stay rare); harmful = Müllerian (+/+). |
| "A keystone species is the most abundant one" | It is the species whose **influence is disproportionate to its biomass** — often rare. The most abundant is the **dominant** species. |

## Key facts

- Interactions are scored by effect on each partner (**+/−, −/−, +/+, +/0, −/0**), and the sign predicts the selection regime: arms race, divergence or exclusion, or policed coevolution.
- **Competition is −/− for both parties** even when one wins; ability is about who suffers least, not who gains most.
- **Competitive exclusion** (Gause): two species cannot coexist on one limiting resource — one is eliminated, or the niches diverge. Coexistence is restored by **resource partitioning**, **character displacement** (see [04 — Speciation](../06-evolution/04-speciation.md)) and **temporal separation**.
- **Predator–prey cycles** are negative feedback with a phase lag (prey peak first); **arms races** yield matched adaptations on both sides.
- Prey rarely go extinct through predation: **switching, refuges, density dependence and arms-race equilibrium** — except against introduced predators and naive prey.
- **Parasitism** = lives in or on the host, depends on it, usually does not kill quickly; **parasitoid wasps** sit on the predation–parasitism boundary, and **virulence evolution** is a **transmission–damage trade-off** with an intermediate optimum — virulence is never a fixed species property.
- **Mutualism** is stabilised by **partner choice and sanctions**, not by mutual benefit alone; mycorrhizae trade P for C and rhizobium N for C via oxygen-sensitive **nitrogenase**.
- **Batesian mimicry** is negative frequency-dependent (the mimic must stay rare); **Müllerian mimicry** is two harmful species sharing one signal (+/+).
- A **keystone species** has influence disproportionate to its biomass (*Pisaster*, sea otter); **dominant species** are defined by biomass instead.

## Practice questions

**1. Two paramecium species are grown on one limiting food source. What is the interaction's sign?**

A. −/− for both: the resource is finite
B. +/−: one species grows faster
C. +/0: the loser is unaffected
D. +/+: both obtain food

**Answer: A**

Explanation: Competition is −/− regardless of who wins, because each leaves with less than it would have had alone. Ability is about who suffers least, not who gains most.

---

**2. Two finch species on one island feed at different canopy heights. What has happened?**

A. Competitive exclusion has run to completion
B. Character displacement diverged their traits where ranges overlap
C. The interaction became commensal
D. One species became parasitic

**Answer: B**

Explanation: Divergence of heritable traits where the species co-occur is character displacement, the evolutionary route out of exclusion. Feeding at different heights is the partitioning it produces.

---

**3. In a predator–prey time series, which peaks first, and what does the lag represent?**

A. Predator first; the lag is incubation time
B. Prey first; the lag is the delay before extra food becomes extra predators
C. Both simultaneously; there is no lag
D. Prey first; the lag is viral incubation in the predator

**Answer: B**

Explanation: The cycle is negative feedback with a phase lag — prey rise, predators follow, then predation reverses both. The lag is demographic: predators must eat before they reproduce.

---

**4. A respiratory virus spread only by coughing from a mobile host evolves lower virulence. Why?**

A. Lower virulence reduces transmission stages shed
B. Transmission needs an active host, so damage cuts off spread
C. Virulence is fixed and cannot evolve
D. Lower virulence increases replication inside the host

**Answer: B**

Explanation: When transmission depends on host mobility, damaging the host too quickly removes the vehicle, so selection favours reduced virulence. Virulence stays high where shedding continues regardless of host condition.

---

**5. A legume starves root nodules whose rhizobium fix no nitrogen. This illustrates:**

A. Partner choice acting before association
B. Sanctions policing a mutualism after association
C. Interference competition with free-living bacteria
D. Vertical transmission of the symbiont

**Answer: B**

Explanation: Sanctions punish a partner that underperforms *after* association, stopping cheaters taking carbon and fixing nothing. Partner choice would be preferring better strains before infecting the root.

---

**6. A harmless hoverfly resembles a stinging wasp. What happens to its protection as hoverflies become common?**

A. It increases: predators learn faster
B. It collapses: the pattern predicts a free meal
C. It is unchanged; mimicry is frequency-independent
D. The hoverfly becomes Müllerian with the wasp

**Answer: B**

Explanation: Batesian mimicry is negative frequency-dependent — the mimic gains most when rare, so mimics stay rarer than models. Once mimics outnumber models, predator learning breaks the illusion.

---

**7. A rare species controls community structure while the most abundant monopolises light. Which distinction applies?**

A. First is dominant, second is keystone
B. First is keystone, second is dominant
C. Both are keystone species
D. Both are ecosystem engineers

**Answer: B**

Explanation: A keystone species has influence disproportionate to its biomass — *Pisaster*, sea otter — so removal reorganises the community. Dominant species are defined by sheer biomass instead.

---

**8. A protozoan lives in red cells, drains nutrients slowly and lets the host survive for months. It is:**

A. Predation: the host is harmed
B. Parasitism: lives in the host, usually does not kill immediately
C. Commensalism: the host survives
D. Amensalism: one party is unaffected

**Answer: B**

Explanation: Parasitism is +/− with residence on a long-lived host; killing it at once would destroy the parasite's own food supply. Predation kills at the encounter and consumes the prey outright.

---

**9. Nitrogenase fixes N₂ but is destroyed by oxygen, so the rhizobium sits in a low-oxygen nodule. What is the trade?**

A. Phosphorus for oxygen
B. Fixed nitrogen for plant photosynthate
C. Carbon for ATP
D. Water for nitrogen

**Answer: B**

Explanation: The trade is N for C — the plant gains amino acids and pays 20–30% of its photosynthetic carbon as ATP and reductant. Mycorrhizae run the parallel P-for-C trade (see [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md)).

---

**10. A black walnut releases juglone into the soil, inhibiting neighbouring plants without being affected itself. This is:**

A. Amensalism, −/0
B. Competition, −/−
C. Commensalism, +/0
D. Mutualism, +/+

**Answer: A**

Explanation: The walnut is unaffected while its neighbours are harmed — the −/0 signature of amensalism. Competition for light and water would be a separate −/− interaction.
