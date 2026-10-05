# Nutrient Cycles

## Why it matters

Two things move through an ecosystem, and they obey opposite rules. **Energy flows one way and is degraded to heat at every transfer**, so it must be resupplied from outside. **Matter cycles endlessly**: the carbon, nitrogen, and phosphorus atoms in your proteins have been through other organisms before you and will be through many more after you — nothing is destroyed, only rearranged ([03 — Atoms and elements](../00-foundations/03-atoms-and-elements.md)).

The corollary is this chapter's organising idea: **every nutrient cycle is chemistry you have already studied, run at planetary scale.** Photosynthesis pulls carbon out of the atmosphere and respiration puts it back; nitrogen fixation reduces N₂ to ammonia and denitrification oxidises it back. If you know the reactions, the cycles are those reactions with geography attached.

And the geography is overwhelmingly microbial: plants cannot fix N₂, animals cannot weather rock, no eukaryote can nitrify ammonia or denitrify nitrate. **Microorganisms hold the enzymes and occupy the redox niches, so they are the engines of every biogeochemical cycle** ([07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md)). A **biogeochemical cycle** is the movement of an element between biotic and abiotic reservoirs, and it has two architectures: **gaseous cycles** (carbon, nitrogen) pass through the atmosphere and are effectively closed and globally mixed, while **sedimentary cycles** (phosphorus) have no atmospheric phase and return only by weathering, sediment, and tectonics — slow and leaky. That difference explains fertiliser policy and which nutrient limits a lake.

## The carbon cycle

Carbon is the skeleton of every organic molecule, so its cycle is the cycle of life itself. Held as an arrow chain, every arrow is a reaction you already know — the first is [09 — Photosynthesis](../03-cellular-processes/09-photosynthesis.md):

```
ATMOSPHERIC CO₂
      │
      ├─► PHOTOSYNTHESIS (producers — see 09 — Photosynthesis)
      │        CO₂ + H₂O + light ──► sugar + O₂   (C: atmosphere → biomass)
      ▼
   PRODUCERS ──► CONSUMERS ──► HIGHER CONSUMERS
      │              │               │
      └──────────────┴───────┬───────┘
                             ▼
                    RESPIRATION (all living things)
                    sugar + O₂ ──► CO₂ + H₂O + ATP   (C returns to air)
      │
      ▼
   DEATH ──► DECOMPOSITION (bacteria, fungi)
             organic C ──► CO₂ (aerobic) or CH₄ (anaerobic, methanogens)
             remainder enters SOIL ORGANIC MATTER
```

Two features deserve a pause. **Respiration and photosynthesis are exact chemical opposites running simultaneously everywhere**: an ecosystem is a net sink or a net source according to which rate is higher — a growing forest fixes more than it respires, while at night or after disturbance it releases more. Second, **decomposition closes the loop for everything that is not eaten**; without it, carbon would stay locked in dead matter.

### Carbon pools

| Pool | Approximate size (gigatonnes C) | Turnover | Notes |
| --- | --- | --- | --- |
| **Atmosphere** (CO₂) | ~870 | Years to decades | Small stock, huge flux; passed 420 ppm recently |
| **Ocean** (dissolved + biotic) | ~38,000 | Surface years, deep centuries | Largest active exchange pool; phytoplankton fix the dissolved CO₂ |
| **Living biomass** | ~500 | Years to decades | Plants, animals, microbes |
| **Soil organic matter** | ~1,500–2,400 | Decades to centuries | Humified dead material; major land store |
| **Fossil fuels** | ~1,000+ recoverable | **Millions of years** | Outside the cycle until burned |
| **Sedimentary rock** | Enormous | 10⁸ years | Ultimate reservoir; limestone is its visible face |

The pattern: **the fastest-turning pools are the smallest**; the enormous ones turn over too slowly to matter on a human timescale. The atmosphere exchanges roughly 200 gigatonnes of carbon per year with land and ocean in each direction — a small stock carrying large traffic, so it responds quickly to an imbalance.

### Fossil fuels: carbon locked out of the cycle

Coal, oil, and gas are organisms buried faster than they could be decomposed, then cooked by heat and pressure over **hundreds of millions of years** — carbon that escaped the biological cycle and was sealed from the surface. Combustion reverses the lock-in:

```
FOSSIL CARBON (buried ~300 million years, out of the cycle)
      │   combustion: C + O₂ ──► CO₂ + energy
      ▼
ATMOSPHERE / OCEAN   (released over ~150 years of industrial burning)
      ▼
photosynthesis and ocean absorption remove only so much, so fast
      ▼
NET ACCUMULATION OF CO₂ IN THE ATMOSPHERE
```

The mechanism is **rate mismatch, not novelty**: the atoms are ordinary carbon, but a flux sized for a couple of centuries is hitting sinks sized for a geological era.

### The greenhouse effect and climate change

**Carbon dioxide is transparent to incoming visible sunlight but absorbs outgoing infrared (heat) radiation.** CO₂ has vibrational modes whose energy gaps match thermal infrared wavelengths; when the warm surface emits at one of them, CO₂ absorbs it and **re-radiates in all directions, including back downward**, so energy lingers near the surface and the planet must warm further before outgoing flux again matches incoming sunlight.

```
more CO₂ ──► more outgoing infrared absorbed and re-radiated downward
      ──► energy lingers in the lower atmosphere ──► TEMPERATURE RISES
      ──► ice and snow retreat (less reflection — a positive feedback)
      ──► oceans warm, expand, stratify, hold less dissolved O₂
      ──► rainfall belts move, deserts widen
      ──► BIOME SHIFTS; species track suitable conditions or decline
```

The natural greenhouse effect keeps Earth habitable; without it the planet would sit far below freezing. The problem is its **enhancement** — greenhouse gases added faster than removal can offset. **Nitrous oxide (N₂O)** from fertilised and waterlogged soils is both a greenhouse gas and an ozone-depleting substance, coupling the nitrogen cycle to climate.

## The nitrogen cycle

Nitrogen is the most **microbially driven** of the major cycles. Atmospheric N₂ is 78% of the air and useless to you: the **triple bond** is among the strongest in chemistry, and no eukaryote carries an enzyme that can break it. Every nitrogen atom in your DNA entered the biosphere through one of five reactions.

```
            N₂ (atmosphere)
      ▲                 │
      │ (5)             │ (1) NITROGEN FIXATION
      │                 ▼
      │              NH₃ / NH₄⁺ ──────────► (3) ASSIMILATION ──► amino acids
      │                 │                          ▲                  │
      │                 │                          │ (4) AMMONIFICATION
      │                 │                          │   organic N ──► NH₃
      │                 │ (2) NITRIFICATION (aerobic)
      │                 ▼
      │            NO₂⁻  ──►  NO₃⁻
      │                              │
      └── (5) DENITRIFICATION ◄──────┘
           (anaerobic)  NO₃⁻ ──► N₂
```

### 1. Nitrogen fixation: N₂ → NH₃

The reaction that opens the cycle. **Nitrogenase** reduces N₂ to ammonia at a cost of **16 ATP per N₂** and is irreversibly destroyed by oxygen — a constraint that dictates where fixation happens:

| Fixer | Habitat | Mechanism |
| --- | --- | --- |
| ***Rhizobium*, *Bradyrhizobium*** | Legume root nodules | Symbiosis: plant supplies carbon and an oxygen-buffered nodule (leghaemoglobin); bacteria supply ammonia |
| ***Azotobacter*, *Azospirillum*** | Free-living in soil | Shield nitrogenase through high respiration |
| **Cyanobacteria** (*Anabaena*, *Trichodesmium*) | Water, paddy fields | **Heterocysts** lack photosystem II, so no O₂ forms where nitrogenase runs |
| **Industrial Haber–Bosch** | Factory | N₂ + 3H₂ → 2NH₃ at high temperature and pressure over iron — the same reaction, fossil-fuelled |

The biological rows are detailed in [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md). The fourth now fixes **more nitrogen than all biology combined** — the largest human intervention in any nutrient cycle, and the source of the fertiliser surplus below.

### 2. Nitrification: NH₃ → NO₂⁻ → NO₃⁻

Two aerobic oxidation steps performed by **chemoautotrophs** that burn inorganic nitrogen for energy and use it to fix CO₂ — nutritionally the mirror image of photosynthesis:

```
NH₃ ──► NO₂⁻ ──► NO₃⁻
      Nitrosomonas   Nitrobacter (also Nitrospira)
      also Nitrosospira, and AMMONIA-OXIDISING ARCHAEA
      (Nitrosopumilus, Nitrososphaera — see 02 — Archaea)
```

Both steps **release energy** the organisms spend on carbon fixation — light-independent primary production — and both are **strictly aerobic**, which is why waterlogged soils nitrify poorly. Archaeal ammonia oxidisers often outnumber the bacteria in soil and ocean, so "*Nitrosomonas* and *Nitrobacter* only" is a simplification ([02 — Archaea](../07-microbiology/02-archaea.md)). The series oxidises nitrogen all the way to nitrate, undoing the reduction fixation performed.

### 3. Assimilation: NO₃⁻/NH₄⁺ → living nitrogen

Plants absorb nitrate or ammonium through roots (algae take it from water), reduce it back to ammonia using **nitrite and nitrate reductase** — spending ATP and reductant to reverse what nitrification just did — and insert it into carbon skeletons to make **amino acids**. From there it becomes protein, nucleic acid, and chlorophyll and climbs the food chain ([02 — Food chains, webs and trophic levels](02-food-chains-webs-and-trophic-levels.md)). Plants favour nitrate because it is abundant, mobile in the transpiration stream, and lacks the toxicity of free ammonia.

### 4. Ammonification: organic N → NH₃

Excretion, death, and waste leave nitrogen locked in amino acids, urea, and nucleic acids. **Decomposers — mainly bacteria and fungi — deaminate these molecules and release ammonia**, again available for nitrification or uptake. This is the step that makes nitrogen a *cycle* rather than a one-way consumption line; without it, nitrogen would accumulate in dead biomass.

### 5. Denitrification: NO₃⁻ → N₂ (closing the loop)

Under **anaerobic** conditions — waterlogged soil, sediments, anoxic microsites — facultative bacteria such as ***Pseudomonas*** switch to **anaerobic respiration**, using nitrate as the terminal electron acceptor instead of oxygen:

```
NO₃⁻ ──► NO₂⁻ ──► NO ──► N₂O ──► N₂  (gas, escapes to atmosphere)
   nitrate reductase → nitrite reductase → NO reductase → N₂O reductase
```

N₂ is inert and leaves the system, so denitrification is agriculturally a **loss of fertiliser** but ecologically **indispensable** — the only reaction returning nitrogen to the atmosphere, without which fixed nitrogen would grow without bound. The intermediate **N₂O** is a potent greenhouse gas, so incomplete denitrification carries a double climate penalty.

### Gaseous versus non-gaseous

| Feature | **Nitrogen cycle** | **Phosphorus cycle** |
| --- | --- | --- |
| Atmospheric phase? | **Yes — N₂ is the largest reservoir** | **None** |
| Return route | Denitrification and fixation close the loop through the air | Weathering of rock; erosion → sediment → uplift |
| Global mixing | Atmosphere mixes rapidly; essentially uniform | Local to a watershed or geological province |
| Long-term leak | None — atoms recycle indefinitely | Lost to deep sediment for millions of years |
| Consequence | Biology competes for one globally shared pool | Fertility depends on a region's own rocks and runoff |

**Nitrogen has a gaseous phase; phosphorus does not** — the difference that determines how each cycle is disrupted and restored.

## The phosphorus cycle

Phosphorus is the exception that proves the rule — a nutrient with no atmosphere, whose cycle is written in stone:

```
ROCK (apatite — calcium phosphate)
      │ WEATHERING: physical breakdown + acid action of roots,
      │ mycorrhizal fungi, and soil CO₂/H⁺
      ▼
SOIL / WATER PHOSPHATE  (H₂PO₄⁻, HPO₄²⁻ — the form plants absorb)
      │
      ├─► PLANTS ──► CONSUMERS ──► DECOMPOSERS ──► back to soil phosphate
      │
      ├──── leaching and runoff ────► LAKES AND OCEANS
      ▼                                   │
      └──── retained in soil ◄────────────▼
                                    SEDIMENT ──► lithified to rock
                                            │
                          UPLIFT over millions of years ──► exposed rock
```

There is **no gas-phase shortcut**: every atom reaching the sea ends in sediment, and the only route back to the continents is mountain building, measured in tens of millions of years. On a human timescale the phosphorus cycle is effectively **one-way** — rock → soil → water → sediment.

### Phosphorus inside cells

| Role | Molecule | Link |
| --- | --- | --- |
| **Energy currency** — phosphoanhydride bonds | ATP, GTP, creatine phosphate | [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md) |
| **Information backbone** — phosphodiester bonds | DNA, RNA | [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) |
| **Membrane architecture** — phosphate head groups | Phospholipids | cell biology |
| **Structural mineral** | Hydroxyapatite in bone and enamel | skeletal biology |
| **Regulation** — phosphorylation switches enzymes | Kinase/phosphatase targets | cell signalling |

### Phosphorus as the limiting nutrient

A **limiting nutrient** is the resource in shortest supply relative to demand — the one whose addition produces the largest growth response ([04 — Population growth](04-population-growth.md); trophic transfer in [02 — Food chains, webs and trophic levels](02-food-chains-webs-and-trophic-levels.md)). Because phosphorus has no atmospheric reservoir and is released only by slow weathering, **freshwater lakes are very frequently phosphorus-limited**: a trickle of phosphate from farmland, sewage, or detergent can double algal growth. Marine systems are more often **nitrogen-limited**, because N₂ is abundant but unusable and the biological supply of fixed nitrogen is therefore small. The working rule is **freshwater → phosphorus, marine → nitrogen**, with co-limitation common.

## The water cycle: the medium that connects all cycles

Water is the solvent and transport system that makes every other cycle possible — carbon rides the transpiration stream, nitrogen climbs root to leaf, phosphate diffuses in soil water, and nitrification, denitrification, and weathering all need a liquid phase.

```
EVAPORATION (oceans, lakes)  ─┐
TRANSPIRATION (leaf stomata) ─┼─► ATMOSPHERIC WATER VAPOUR
                              ▼
                       PRECIPITATION (rain, snow)
                              ├─► RUNOFF overland → rivers → sea
                              ├─► INFILTRATION → GROUNDWATER → springs
                              └─► SNOW AND ICE storage (seasonal delay)
```

**Transpiration** is the biological arm of the loop: roots take up water, leaves release it through stomata, and the evaporation-driven pull lifts dissolved nitrogen and minerals from soil to canopy ([04 — Water transport and transpiration](../08-plant-biology/04-water-transport-and-transpiration.md)). Deforestation shortens the loop — less transpiration, less recycled rainfall, altered runoff. The water cycle sets the pace of the others: drought stalls decomposition and weathering; flooding accelerates erosion and oxygen depletion.

## Human disruption of the cycles

| Intervention | Cycle | Mechanism | Consequence |
| --- | --- | --- | --- |
| **Haber–Bosch fertiliser** | Nitrogen | Industrial fixation exceeds natural fixation; applied N exceeds crop uptake | **Run-off of NO₃⁻/NH₄⁺ → eutrophication** (chain below); groundwater nitrate → methaemoglobinaemia |
| **Fossil fuel combustion** | Carbon | Geological carbon returned to the active cycle faster than sinks can capture it | **Enhanced greenhouse effect** → warming, ocean acidification, biome shifts |
| **Phosphate mining, sewage, detergents** | Phosphorus | Accelerated release with no atmospheric buffer | Freshwater eutrophication; phosphorus accumulates in sediment where it is hard to remove |
| **Deforestation and tillage** | N, C, P | Removes vegetation holding nutrients; exposes soil to erosion | Soil N and organic C loss, sediment-loaded rivers, immediate CO₂ release |
| **Acid rain** (SOₓ, NOₓ deposition) | Sulfur, nitrogen | Combustion oxidises S and N to acids falling as rain, snow, or dry deposition | Soil base cations leached, aluminium mobilised, lakes acidified — though deposition also adds usable N |
| **Drainage of wetlands** | Nitrogen | Removes anoxic sites where denitrification runs | Fixed N accumulates; waterlogged fertilised soils emit N₂O |

### Eutrophication: the fertiliser run-off arrow chain

**Eutrophication** is nutrient enrichment of a water body — a good thing (more nutrients) going catastrophically wrong through a predictable chain:

```
EXCESS N AND P RUNOFF (fertiliser, sewage, manure)
      ▼
ALGAL BLOOM (explosive growth — cyanobacteria, dinoflagellates)
      ▼
bloom shades the water → submerged plants and algae die
      ▼
DEAD ALGAE SINK → DECOMPOSERS BLOOM → AEROBIC DECOMPOSITION
      ▼
O₂ CONSUMED faster than diffusion can replace it → HYPOXIA (< 2 mg/L) → ANOXIA
      ▼
FISH AND BENTHIC ANIMALS SUFFOCATE → DEAD ZONE
      (Gulf of Mexico, Baltic Sea)
```

**The oxygen is consumed by decomposition, not by the living algae** — the bloom is the cause, suffocation the effect, and the delay between them is why blooms are often noticed only after the fish have died. Under anoxia alternative electron acceptors take over: nitrate first (denitrification, releasing N₂O), then sulfate (hydrogen sulfide, the rotten-egg smell of a dying lake). Cyanobacterial blooms add a hazard of their own — **hepatotoxins and neurotoxins** contaminating drinking water and shellfish.

## Relevance to medicine and the real world

**Dead zones are a public-health story as much as an ecological one.** When bottom water loses oxygen, the sea floor reorganises around whatever tolerates hypoxia — largely microbes plus a few hardy animals. Filter-feeding shellfish that cannot flee — oysters, mussels, clams — either die or become concentrated reservoirs of whatever is in the water, because they pump litres a day through their bodies. Warming plus nutrient loading has expanded ***Vibrio*** bacteria, including *V. vulnificus* and *V. parahaemolyticus* (wound infection, seafood-borne gastroenteritis), into latitudes too cold for them before, while harmful algal blooms cause paralytic and amnesic shellfish poisoning. The eutrophication chain does not stop at dead fish; it reshapes which pathogens a coastal population meets.

**Contaminants ride the food web, and the cycles decide who eats them.** Mercury from combustion and mining is methylated by anaerobic sediment bacteria to **methylmercury**, taken up at the base of the food chain and **biomagnified** — concentration rises at each trophic level, so top predators and the people who eat them carry the highest doses. Lead from paint and (formerly) leaded petrol behaves similarly in soils. Both are nutrient cycles hijacked: elements that belong in rock are inserted into the biological loop in forms organisms cannot excrete ([02 — Food chains, webs and trophic levels](02-food-chains-webs-and-trophic-levels.md)).

**Climate change is moving disease.** A warmer atmosphere is a shifted water cycle, and shifted temperature and rainfall redraw the maps of every organism that depends on them, vectors included. Mosquitoes transmitting malaria, dengue, Zika, and chikungunya need minimum temperatures for extrinsic incubation of the parasite or virus inside the insect; warming lifts that constraint at altitude and latitude, extending transmission seasons into previously too-cool highlands, while flooding and displacement worsen sanitation and water-borne transmission. Tick-borne encephalitis and Lyme disease shift with milder winters. The chain runs from carbon-cycle disruption straight to pathogen range, which is why [05 — Microbial reproduction and transmission](../07-microbiology/05-microbial-reproduction-and-transmission.md) matters to epidemiology as well as microbiology.

**Agriculture can work with the cycles instead of against them.** The Haber–Bosch surplus exists because crops cannot fix their own nitrogen — but legumes can, for free, given the right partner. **Rhizobial inoculants** on seed, and **mycorrhizal inoculants** that mine phosphate, replace part of the applied fertiliser with biology and cut run-off at source; **crop rotation** leaves fixed nitrogen in residues; precision application reduces the pulse of soluble N that feeds blooms. These are not soft alternatives to fertiliser — they are the original cycles restored as design constraints, and the symbioses are set out in [07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md).

**The carbon cycle is the mechanism behind climate policy.** Every target — net zero, carbon budgets, offsetting — is applied biochemistry: arithmetic on the fluxes of the arrow chain at the top of this chapter. "Sequestering" means accelerating photosynthesis and burial; "cutting emissions" means slowing the combustion arrow; "offsetting" claims a sink arrow has grown to match a source arrow. It is the same molecule and the same reaction whether it leaves a smokestack or a mitochondrion. It also explains why trees planted today cannot cancel emissions released today: the sink is rate-limited by photosynthesis, and the source is not.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Energy cycles like nutrients do" | **Energy flows one way and is lost as heat at every transfer; matter cycles.** Energy must be resupplied by the Sun — matter does not need to be. |
| "Plants make oxygen and animals use it" | Both respire continuously, plants included. The O₂ cycle is the **balance of two rates**, not a division of labour between kingdoms. |
| "Photosynthesis is done by plants" | Most global photosynthesis is done by **phytoplankton** — cyanobacteria and algae; land plants contribute only part of the total. |
| "Nitrogen fixation and nitrification are the same" | Different reactions and organisms: **fixation** is N₂ → NH₃ (nitrogenase; *Rhizobium*, *Azotobacter*, cyanobacteria, Haber–Bosch); **nitrification** is NH₃ → NO₂⁻ → NO₃⁻ (*Nitrosomonas*, *Nitrobacter*, ammonia-oxidising archaea). |
| "Plants fix atmospheric nitrogen" | No eukaryote has nitrogenase. Plants **host** fixers in nodules or absorb nitrogen fixed elsewhere; legumes pay the bacteria in photosynthate. |
| "Denitrification is just a nuisance that wastes fertiliser" | Agriculturally a loss, ecologically **essential** — the only reaction returning N₂ to the atmosphere and closing the nitrogen cycle. |
| "Phosphorus behaves like carbon or nitrogen" | Phosphorus has **no atmospheric phase**; its reservoir is rock and its return is weathering plus tectonics over millions of years — which is why it so often limits freshwater systems. |
| "Nitrogen is always the limiting nutrient" | **Freshwater is usually phosphorus-limited, marine usually nitrogen-limited**, and co-limitation is common. Limitation is whichever resource is scarcest *in that system*. |
| "Burning fossil fuels creates new carbon" | It transfers carbon from the **geological pool into the active cycle**. The atoms are unchanged; the rate of transfer overwhelms the sinks. |
| "The greenhouse effect is pollution" | The **natural** greenhouse effect keeps Earth habitable. The problem is the **enhanced** effect from added gases that delay heat loss to space. |
| "Decomposition is done by bacteria alone" | **Fungi are equally important**, especially for lignin and cellulose; insects and detritivores fragment the material first. It is a community succession. |

## Key facts

- **Energy flows one way and degrades to heat; matter cycles indefinitely** — the atoms in your protein have been in other organisms and will be in others again.
- Nutrient cycles are **cell biology at planetary scale** — photosynthesis, respiration, fixation, nitrification, denitrification are the arrows — and **microorganisms are the engines**: no eukaryote can fix N₂, nitrify ammonia, or denitrify nitrate.
- Carbon chain: **CO₂ → photosynthesis → producers → consumers → respiration → CO₂**, with **decomposition** returning the rest and soil as a store.
- **Fossil fuels are carbon locked out of the cycle for millions of years**; combustion returns it faster than photosynthesis and the ocean can re-capture it.
- **CO₂ absorbs outgoing infrared and re-radiates it in all directions including downward** — the enhanced effect raises global temperature and shifts biomes.
- Nitrogen's five steps: **fixation → nitrification → assimilation → ammonification → denitrification**.
- **Nitrogenase** costs **16 ATP per N₂** and is oxygen-sensitive; fixers are *Rhizobium* nodules, *Azotobacter*, cyanobacteria, plus **Haber–Bosch**, which exceeds all biology.
- **Nitrification is aerobic and chemoautotrophic**: *Nitrosomonas* (and ammonia-oxidising archaea) make NO₂⁻; *Nitrobacter* makes NO₃⁻.
- **Denitrification is anaerobic respiration** (*Pseudomonas*) ending in N₂ — closing the loop; incomplete versions release greenhouse N₂O.
- **Nitrogen has a gaseous phase (N₂), phosphorus does not** — the phosphorus cycle is sedimentary: rock → weathering → soil → organisms → sediment.
- **Phosphorus often limits freshwater** (nitrogen more often limits marine systems); it is essential as ATP, nucleic acid backbone, phospholipid, and bone mineral.
- The **water cycle** connects all the others: evaporation, transpiration, precipitation, runoff, groundwater.
- **Human disruption changes the rate of one arrow relative to the others**; classic chain: excess N and P → algal bloom → decomposition → hypoxia → dead zone.

## Practice questions

**1. The most accurate statement about energy and matter in ecosystems is**

A. Energy flows one way and is lost as heat, while matter is recycled between biotic and abiotic reservoirs
B. Both energy and matter cycle endlessly through ecosystems
C. Matter flows one way, while energy cycles between trophic levels
D. Energy is conserved at every trophic transfer, so only matter needs resupply

**Answer: A**

Explanation: Each transfer between trophic levels dissipates most energy as heat, so energy must be resupplied by the Sun and cannot be recycled. Matter is not destroyed, so atoms are reassembled into new organisms — that is a biogeochemical cycle. C inverts the two; B and D ignore the energy lost at each step.

---

**2. Carbon released by burning fossil fuels is best described as**

A. Newly created carbon that never existed in the biosphere
B. Carbon returned from a geological pool to the active cycle faster than sinks can reabsorb it
C. Carbon that photosynthesis is unable to fix
D. Carbon permanently removed from the atmosphere

**Answer: B**

Explanation: Fossil fuels are organic carbon buried and locked out of circulation for millions of years; combustion returns it as CO₂ in decades, overwhelming photosynthesis and ocean uptake. The atoms are those of ordinary respiration — the problem is the flux, not the chemistry. A, C, and D misstate the origin of the carbon or the direction of transfer.

---

**3. Which organism is correctly paired with its role in the nitrogen cycle?**

A. *Nitrobacter* — nitrogen fixation in legume nodules
B. *Rhizobium* — conversion of nitrate to atmospheric N₂
C. *Pseudomonas* — denitrification, returning N₂ to the atmosphere under anaerobic conditions
D. *Nitrosomonas* — assimilation of nitrate into amino acids by plants

**Answer: C**

Explanation: *Pseudomonas* uses nitrate as a terminal electron acceptor under anaerobic conditions, reducing it through nitrite and nitrous oxide to N₂ — the step that closes the nitrogen cycle. *Nitrobacter* performs the second half of nitrification, *Rhizobium* fixes N₂, and *Nitrosomonas* oxidises ammonia to nitrite; assimilation is done by plants, not bacteria.

---

**4. The two steps of nitrification, performed by *Nitrosomonas* and *Nitrobacter*, convert**

A. N₂ to NH₃, then NH₃ to NO₂⁻
B. NH₃ to NO₂⁻, then NO₂⁻ to NO₃⁻
C. NO₃⁻ to NO₂⁻, then NO₂⁻ to N₂
D. Organic nitrogen to NH₃, then NH₃ to N₂

**Answer: B**

Explanation: Ammonia is oxidised to nitrite by *Nitrosomonas* (and by ammonia-oxidising archaea), and nitrite is then oxidised to nitrate by *Nitrobacter* — both aerobic chemoautotrophs gaining energy from these oxidations. A describes fixation followed by the first nitrification step, C describes denitrification, and D begins with ammonification.

---

**5. A farmer floods a field and later measures nitrogen loss to the atmosphere. The process responsible is**

A. Nitrogen fixation, which consumes atmospheric N₂
B. Ammonification, which volatilises amino acids
C. Denitrification, in which anaerobic bacteria reduce nitrate to N₂ gas
D. Assimilation, in which plants take up ammonium

**Answer: C**

Explanation: Waterlogging removes oxygen, so facultative anaerobes such as *Pseudomonas* switch to nitrate respiration and reduce NO₃⁻ stepwise to N₂, which escapes — an economic loss of fertiliser but the reaction that closes the cycle. Fixation moves nitrogen the opposite way (atmosphere → soil), ammonification releases NH₃ but not N₂, and assimilation locks nitrogen into biomass.

---

**6. Unlike the carbon and nitrogen cycles, the phosphorus cycle**

A. Lacks an atmospheric phase, so its return path is weathering, sedimentation, and tectonic uplift
B. Has an atmospheric reservoir of gaseous phosphorus
C. Depends entirely on denitrifying bacteria
D. Is closed and rapid on a human timescale

**Answer: A**

Explanation: No significant gaseous phosphorus species exist, so phosphorus moves rock → soil → organisms → sediment, and only mountain building returns it to exposed rock — a loop measured in millions of years. That missing shortcut is why freshwater is commonly phosphorus-limited and phosphate pollution persists locally. Denitrification belongs to the nitrogen cycle.

---

**7. In the eutrophication arrow chain, the direct cause of fish kills in a dead zone is**

A. The algal bloom consuming all the oxygen while alive
B. Release of nitrous oxide by the bloom
C. Nitrogen fixation by cyanobacteria removing nitrogen from the water
D. Aerobic decomposition of dead algae consuming dissolved oxygen faster than it is replenished

**Answer: D**

Explanation: The bloom shades and kills submerged vegetation; when the algae die, decomposers multiply and their aerobic respiration strips the water of oxygen — bloom → death → decomposition → suffocation. Living algae produce oxygen during the day, so depletion follows their death. Nitrous oxide and nitrogen removal do not kill the fish.

---

**8. The Haber–Bosch process is significant to the nitrogen cycle because it**

A. Replaces denitrification and so closes the nitrogen cycle naturally
B. Fixes atmospheric nitrogen industrially at a rate exceeding all biological fixation combined, creating a surplus that drives eutrophication
C. Converts nitrate back to N₂ and so removes fertiliser from ecosystems
D. Is the only reaction capable of producing nitrogenase

**Answer: B**

Explanation: Industrial N₂ + H₂ → NH₃ over an iron catalyst now fixes more nitrogen than all microorganisms together, and applied fertiliser exceeds crop uptake, so the surplus runs off into waterways — the first arrow of the eutrophication chain. A and C describe denitrification, which Haber–Bosch does not perform; industry bypasses nitrogenase rather than producing it.

---

**9. Carbon dioxide warms the lower atmosphere primarily because it**

A. Absorbs incoming sunlight and converts it directly to heat
B. Prevents water vapour from condensing
C. Reflects sunlight back to space before it reaches the ground
D. Absorbs outgoing infrared radiation and re-emits it in all directions, including back toward the surface

**Answer: D**

Explanation: CO₂ is transparent to incoming visible light but absorbs thermal infrared emitted by the warm surface, then re-radiates it in every direction, so some returns downward and the surface must warm until outgoing flux again matches incoming. Adding CO₂ strengthens that mechanism. A and C describe other processes (ozone absorption, albedo); B describes none.

---

**10. Mercury concentrations rise from plankton to small fish to large predatory fish and humans because**

A. Mercury is created at each trophic level by metabolism
B. Mercury is fixed from the atmosphere by phytoplankton like nitrogen
C. Mercury is transferred with energy but is not excreted, so it accumulates at each step — biomagnification
D. Larger organisms eat proportionally less food than smaller ones

**Answer: C**

Explanation: Methylmercury made by sediment bacteria enters the food chain at the base and is retained in tissue rather than excreted, while only about a tenth of the energy passes upward, so concentration climbs with trophic level (**biomagnification**). Nothing creates mercury biologically — it is mobilised by emissions and microbial methylation. The trophic arithmetic is in [02 — Food chains, webs and trophic levels](02-food-chains-webs-and-trophic-levels.md).
