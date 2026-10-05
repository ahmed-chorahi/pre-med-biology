# Speciation

## Why it matters

Speciation is the mechanism that turns evolution's small, population-level changes into the **diversity of life** — the reason there are separate species rather than one continuously variable global population. Every other chapter in this section describes a force acting within a population; this chapter describes what happens when a population **stops being one population**: when gene flow is severed, drift and selection pull the halves apart, and the two can no longer interbreed.

The practical core is **reproductive isolation**. Once you can classify an isolating barrier as prezygotic or postzygotic, and as acting before or after fertilisation, you can predict where in a life cycle a given incompatibility sits — which is the same reasoning used when a reproductive biologist investigates infertility, when a clinician interprets a failed cross-species or hybrid outcome, and when an epidemiologist asks how a pathogen jumps from one host species to another.

Speciation also frames the biggest questions in the section: how microevolution (allele frequency change) relates to macroevolution (the origin of new body plans and higher taxa), whether evolution is gradual or punctuated, and what a "species" actually is — a question that turns out to have several answers, each valid for a different kind of organism.

## The biological species concept

The most examinable definition, from Ernst Mayr:

> **A biological species is a group of actually or potentially interbreeding natural populations that is reproductively isolated from other such groups.**

The key phrase is *reproductively isolated* — species are defined by **the inability to exchange genes**, not by how different they look. A consequence worth stating: under this concept, two populations that look identical but cannot interbreed are different species, and two very different-looking populations that interbreed freely are the same species.

| Species concept | Defining criterion | Best for | Fails with |
| --- | --- | --- | --- |
| **Biological** | Reproductive isolation (interbreeding) | Sexual eukaryotes | Asexual organisms; fossils |
| **Morphological (phenetic)** | Shared structural features | Palaeontology, field survey | Cryptic species; convergent forms |
| **Phylogenetic** | Monophyletic group on a tree | Molecular systematics | Recently diverged lineages |
| **Ecological** | Occupies a distinct niche | Microbes, adaptive radiation | Poorly defined niche boundaries |

No single concept works everywhere — which is why "species" can be argued about. The biological concept remains the default for animals because it maps onto the mechanism that maintains species as units: **gene flow within, isolation without.**

## Reproductive isolation: prezygotic barriers

Prezygotic barriers prevent fertilisation from ever occurring. They are evolutionarily favoured over postzygotic barriers because they **waste no gametes** — hybrids that die or are sterile represent wasted reproductive effort, so selection builds barriers upstream where possible.

| Barrier | Mechanism | Example |
| --- | --- | --- |
| **Habitat isolation** | Two species breed in different habitats or on different parts of the same habitat | Two *Drosophila* species breeding on different host fruits; garter snakes that live in water vs on land |
| **Temporal isolation** | Breed at different times — season, day, or hour | *Drosophila* species mating at different times of day; plants flowering in spring vs summer |
| **Behavioural (ethological) isolation** | Species-specific courtship signals; females reject wrong displays | Bird songs and dances; firefly flash patterns; frog calls |
| **Mechanical isolation** | Genitalia or floral structures do not fit | Snail shell coiling direction (dextral vs sinistral) prevents genital contact |
| **Gametic isolation** | Sperm cannot recognise or penetrate the egg; incompatibility at the egg surface | Sea urchin sperm binding species-specific proteins on the egg membrane; many marine invertebrates |

The first three are **behavioural or ecological** — they keep encounters from happening or from being accepted. The last two are **gametic** — they act at the moment of fertilisation itself, and they are the reason a human sperm cannot fertilise a chimpanzee egg even if the two are placed together: sperm–egg recognition proteins have diverged sufficiently that binding fails.

## Reproductive isolation: postzygotic barriers

Postzygotic barriers act **after** fertilisation. Hybrids form but fail, and the failure tells you where the genetic incompatibility sits.

| Barrier | Mechanism | Example |
| --- | --- | --- |
| **Hybrid inviability** | Hybrid embryo or offspring dies or is unfit before reproductive age | Some salamander–frog crosses; many interspecific *Drosophila* embryos |
| **Hybrid sterility** | Hybrid survives but cannot produce functional gametes | **Mule** (horse × donkey) — viable, hardy, sterile; the hinny likewise |
| **Hybrid breakdown** | F1 hybrids are fertile, but F2 or backcross offspring are inviable or sterile | Rice species crosses; some *Gossypium* (cotton) crosses |

**Haldane's rule** is the useful generalisation: **if one sex of a hybrid is absent, inviable, or sterile, it is more often the heterogametic sex** (the one with two different sex chromosomes — XY males in mammals, ZW females in birds). The standard explanation is that sex-linked incompatibilities lack a second matched copy to mask them in the heterogametic sex — the same hemizygosity logic that exposes X-linked recessives in males, which you will have met in [03 — Non-Mendelian patterns](../04-genetics/03-non-mendelian-patterns.md).

```
hybrid genetic incompatibility
   → expressed on a single (heterogametic) sex chromosome
      → no homologous partner to mask it
         → that sex sterile or dead
            = HALDANE'S RULE
```

## Allopatric vs sympatric speciation

The two main geographic modes differ in **whether the initial split is physical**.

### Allopatric speciation — separation first

```
one continuous population
        │
        │  geographic barrier arises (river, mountain range, valley)
        │  OR a subset disperses beyond the barrier
        ▼
two geographically SEPARATE populations
        │
        ├─► population A: local selection, drift, founder effects
        ├─► population B: different local selection, drift, founder effects
        ▼
genetic divergence accumulates with NO GENE FLOW to oppose it
        ▼
secondary contact later:
   still interbreed → one species (maybe with a hybrid zone)
   cannot interbreed → TWO SPECIES (reproductive isolation complete)
```

Allopatry is considered the **default and best-documented** mode, because physical separation removes gene flow — the single force most capable of swamping divergence. It comes in two forms: **vicariance** (a barrier splits an existing population) and **peripatric / founder-event** speciation (a small group becomes isolated at the edge, subject to strong founder effect and drift — see [03 — Drift and gene flow](03-genetic-drift-and-gene-flow.md)).

### Sympatric speciation — divergence without a barrier

Speciation can begin **within a single geographic area** when reproductive isolation evolves directly, most plausibly through **disruptive selection plus assortative mating**:

```
one population, one habitat
   → disruptive selection favours two extreme phenotypes
      (e.g. feeding on small vs large seeds; host-plant preference)
      → each extreme mates preferentially with its own type
         (habitat choice, timing, or mate signal tied to the phenotype)
            → gene flow between the morphs declines
               → genetic divergence, then isolation
```

Sympatric speciation is best documented in **host-race formation in insects** (apple maggot flies shifting from hawthorn to introduced apple trees — same orchard, different host, different timing), in **cichlid fish** where mate choice is tied to colour and depth, and is the leading explanation for some **polyploid speciation in plants**, where a chromosome doubling instantly renders an individual incompatible with its parent population — the fastest known route to instantaneous reproductive isolation.

### Peripatric and parapatric (brief)

- **Peripatric**: a small peripheral isolate is cut off from the main population — allopatry with an extreme founder effect, so drift dominates early divergence.
- **Parapatric**: populations are adjacent but use different parts of a continuous range, with limited contact at the boundary — divergence proceeds while gene flow continues only across a narrow hybrid zone. **Ring species** are the limiting case (below).

## Reinforcement and character displacement

When two partially isolated populations come back into contact, selection can either **finish** the split or **sharpen** the difference.

**Reinforcement (the Wallace effect).** If hybrids are unfit, natural selection favours individuals that avoid mating with the other population — strengthening prezygotic barriers.

```
secondary contact
   → some hybridisation occurs
      → hybrids are inviable or sterile (wasted reproduction)
         → individuals that mate assortatively leave MORE offspring
            → preference for own type is selected FOR
               → prezygotic barriers STRENGTHEN → speciation completed
```

Reinforcement is the only stage of speciation that **requires** gene flow to evolve, and it is distinguished from simple divergence by the signature of *increased* prezygotic isolation where ranges overlap.

**Character displacement** is the ecological correlate: where two species coexist, natural selection **exaggerates** the differences between them (beak size in Darwin's finches on shared islands diverge more than on islands where only one species is present) because intermediate phenotypes compete with both — the character displaces away from the overlap.

```
allopatry:     species A mean beak = 9 mm    species B mean beak = 10 mm  (similar)
sympatry:      species A mean beak = 7 mm    species B mean beak = 12 mm  (diverged)
                ↑ differences magnified only where they co-occur
```

## Ring species

A ring species is a special case where a chain of populations connects two ends that meet **and fail to interbreed**, even though each adjacent link in the chain can interbreed with its neighbour.

```
population A ── interbreeds ── B ── C ── D ── E
      │                                        │
      └────────── meet at the far end ─────────┘
                 A and E DO NOT interbreed
```

The classic example is the *Ensatina* salamander ring around California's Central Valley, and the greenish warblers (*Phylloscopus trochiloides*) around the Tibetan Plateau. Ring species demonstrate **speciation in action**: reproductive isolation accumulates gradually along a geographic continuum, so the question "are A and E the same species?" has no clean answer — a live demonstration that species are a **stage in a process**, not a fixed category.

## Adaptive radiation

An adaptive radiation is a burst of speciation from a single ancestor into many forms exploiting different niches — often on islands or in newly opened adaptive space.

```
single ancestral colonist
        │
        ▼  ecological opportunity (empty niches, no competitors/predators)
        │
   ┌────┴────┬─────────┬──────────┐
   ▼         ▼         ▼          ▼
large-beak  small-beak  nectar-   insectivore
cracker     gleaner     feeder    specialist
   │         │          │          │
   └── each becomes reproductively isolated ──► many species
```

| Radiation | Ancestor | Diversification |
| --- | --- | --- |
| **Cichlids, African Great Lakes** | A few riverine cichlid ancestors | Hundreds of species in Lakes Victoria, Malawi, Tanganyika — differentiated by trophic morphology and **colour-based mate choice** (often sympatric) |
| **Darwin's finches** | One mainland seed-eating finch | 13+ species differing in beak size/shape for different foods; classic case of character displacement |
| **Hawaiian honeycreepers** | A single finch-like colonist | Dozens of species with radically different bills — nectar probes, seed crackers, insect gleaners — many now extinct through introduced disease |

The mechanism is **divergent selection on a colonising population with no competitors**, plus reproductive isolation evolving as mate choice follows ecology (song, habitat, and colour cues diverge with the niches). Cichlids show how fast this can be: Lake Victoria's hundreds of species arose within roughly the last 15,000 years.

## Punctuated equilibrium vs gradualism

Two models of **tempo and mode** describe how change appears in the fossil record:

| | Gradualism | Punctuated equilibrium |
| --- | --- | --- |
| **Rate** | Slow, steady, continuous | Long stasis interrupted by rapid bursts |
| **Where change occurs** | Throughout a species' range | In small, peripherally isolated populations (allopatry) |
| **Prediction in fossils** | Gradual transitional series | Species appear suddenly, then change little |
| **Mechanism** | Constant weak selection | Stasis = stabilising selection + gene flow; burst = founder event, drift, new selection |

The two are not mutually exclusive, and both are correct at different scales. **Gradualism** fits well at the population level where allele frequency change is measurable (antibiotic resistance, moth colouration). **Punctuated equilibrium** fits the *fossil* pattern: because most speciation happens in small isolated populations and takes a geologically short time, the transition is rarely preserved — species seem to appear fully formed, then persist unchanged for long periods (stasis). Stasis itself needs explaining: stabilising selection, constraints (chapter 02), and gene flow homogenising a large range all resist change.

## Macroevolution vs microevolution

| | Microevolution | Macroevolution |
| --- | --- | --- |
| **Definition** | Allele frequency change within a population | Patterns above species level — origins of new groups, body plans, mass extinctions |
| **Timescale** | Generations | Millions of years |
| **Evidence** | Direct observation, allele frequency data | Fossils, comparative anatomy, molecular phylogenies |
| **Mechanisms** | Selection, drift, flow, mutation | The *same* mechanisms plus speciation, extinction, and selection among species |

The continuity thesis — that macroevolution is microevolution plus time and speciation — is the mainstream position: there is no known new mechanism required. The counterpoint, species selection (differential speciation and extinction among species rather than among individuals), is a genuine additional process, but it operates on the same principle of variation, differential "success", and heritability — applied to species instead of organisms.

## Why it matters in medicine and the real world

**The species concept is not academic in microbiology.** Bacteria do not interbreed, so the biological species concept is unusable; bacterial taxonomy runs on **morphology, metabolic tests, and now DNA–DNA hybridisation / average nucleotide identity (ANI)** thresholds — practical cutoffs around 70% DNA–DNA hybridisation or ~95–96% ANI define a bacterial species. Recognising that "species" in bacteriology is a molecular convention, not reproductive isolation, prevents category errors when a single species (cohort of *E. coli*, *S. pneumoniae*) contains strains of wildly different pathogenicity. The organisms themselves are in [07 — Microbiology](../07-microbiology/).

**Speciation logic explains host shifts and emerging infection.** Pathogen speciation follows the same barriers in reverse: when a parasite's prezygotic or host-specific barriers break down, it can colonise a new host — the classic cases being myxoma virus in rabbits, *Plasmodium* species' host specificity, and avian influenza lineages partitioned by aquatic vs terrestrial hosts. Predicting spillover is applied reproductive isolation.

**Hybridisation has clinical and agricultural consequences.** Influenza's **antigenic shift** arises when two viral lineages co-infect one cell and *reassort* genome segments — the microbial analogue of hybridisation producing a novel combination to which the population has no immunity; this is why pandemic strains appear "suddenly". In agriculture, hybrid sterility and breakdown set hard limits on crossing (the mule principle), and hybrid zones are tracked as barometers of environmental change.

**Medical students meet isolating barriers as anatomy and timing.** Habitat, temporal, mechanical, and gametic isolation map onto the everyday causes of infertility — mismatched timing of ovulation, anatomical obstruction, and sperm–egg recognition failure — so the classification is directly portable to clinical reproductive physiology.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Species are defined by looking different" | Under the **biological** concept they are defined by reproductive isolation; morphology is a fallback concept for fossils. |
| "Hybrids are always sterile" | Postzygotic barriers come in three forms — inviability, sterility, and F2 breakdown — and some hybrids are fertile. |
| "Allopatric and sympatric mean the same thing" | Allopatry requires **geographic separation**; sympatric speciation begins **within one area** via ecological and mating divergence. |
| "Punctuated equilibrium contradicts natural selection" | It is a claim about **tempo** — long stasis under stabilising selection, bursts during speciation, not a rejection of mechanism. |
| "Macroevolution needs its own mechanism" | The mainstream view is microevolution plus speciation and time; species selection is an addition, not a replacement. |
| "Reinforcement happens when populations are separated" | Reinforcement happens on **secondary contact**, when unfit hybrids make assortative mating advantageous. |
| "A ring species proves species are not real" | It shows speciation is a **process with intermediate states** — the ends are distinct species while the chain shows the gradient. |
| "Bacterial species are biological species" | Bacteria do not interbreed; bacterial species are **molecularly defined conventions** (ANI, DNA–DNA hybridisation). |

## Key facts

- The **biological species concept**: a group of actually or potentially interbreeding populations, reproductively isolated from other such groups.
- **Prezygotic barriers**: habitat, temporal, behavioural, mechanical, gametic — they prevent fertilisation and waste no gametes.
- **Postzygotic barriers**: hybrid inviability, hybrid sterility, hybrid breakdown — hybrids form but fail.
- **Haldane's rule**: the heterogametic sex is more often inviable or sterile in hybrids.
- **Allopatric** speciation (geographic separation, no gene flow) is the best-supported default; **sympatric** speciation proceeds via disruptive selection plus assortative mating (or instantly, via polyploidy).
- **Peripatric** = small founder isolate at the range edge; **parapatric** = adjacent ranges with narrow contact.
- **Reinforcement** strengthens prezygotic barriers after secondary contact; **character displacement** exaggerates differences where species overlap ecologically.
- **Ring species** show isolation accumulating along a continuum — species as a process, not a fixed box.
- **Adaptive radiation** = rapid diversification into open niches — cichlids, Darwin's finches, Hawaiian honeycreepers.
- **Gradualism** predicts slow continuous change; **punctuated equilibrium** predicts long stasis with rapid bursts at speciation — both are observed at different scales.
- **Macroevolution** = microevolution + speciation + time, with possible species-level selection.

## Practice questions

**1. Under the biological species concept, two populations are considered different species if they**

A. Look different enough to be told apart in the field
B. Occupy different continents
C. Are reproductively isolated — they cannot interbreed to produce fertile offspring in nature
D. Have different DNA sequences at any single locus

**Answer: C**

Explanation: The biological species concept defines species by the boundary of gene flow — reproductive isolation is the criterion, not appearance or geography. Morphology (A) is the fallback concept for fossils, not the biological one; different continents do not prevent interbreeding in principle (B); and any single locus will differ between populations of the same species (D).

---

**2. Two frog species produce offspring that develop normally but are sterile. This is an example of**

A. Prezygotic mechanical isolation
B. Postzygotic hybrid sterility
C. Habitat isolation
D. Hybrid inviability

**Answer: B**

Explanation: Fertilisation occurred and the hybrid survived — so no prezygotic barrier acted (A, C) — but it cannot reproduce, which is the definition of hybrid sterility, one of the three postzygotic barriers (along with inviability, where the hybrid dies, and breakdown, where F2/backcross offspring fail). The mule is the standard example.

---

**3. A river appears and splits one mouse population in two. After thousands of years the two no longer interbreed. This sequence is**

A. Sympatric speciation by polyploidy
B. Allopatric speciation by vicariance
C. Reinforcement within a continuous population
D. Hybrid breakdown

**Answer: B**

Explanation: A physical barrier (the river) separated an existing population — vicariance, the classic allopatric route — after which gene flow ceased and divergence accumulated independently in each half. No geographic separation means it would be sympatric (A); reinforcement (C) requires secondary contact between already-diverging populations; hybrid breakdown concerns hybrid offspring (D).

---

**4. Which is a prezygotic isolating barrier?**

A. Hybrid inviability
B. Sterility of hybrid offspring
C. Females of one species rejecting the courtship song of another
D. Sterility of an F2 hybrid

**Answer: C**

Explanation: Prezygotic barriers prevent fertilisation from occurring at all; behavioural (ethological) isolation — species-specific courtship that the wrong species fails to perform or recognise — is one of the classic five (along with habitat, temporal, mechanical, and gametic). The three postzygotic barriers (A, B, D) all act after a fertilised egg exists, wasting reproductive effort.

---

**5. Haldane's rule predicts that in an unfit hybrid**

A. Both sexes are affected equally
B. The homogametic sex is always the fertile one
C. The heterogametic sex is more likely to be inviable or sterile
D. Only autosomal traits determine hybrid fitness

**Answer: C**

Explanation: The heterogametic sex (XY males in mammals, ZW females in birds) has only one copy of the sex chromosome, so recessive incompatibility alleles on it are exposed rather than masked — the same hemizygosity that makes X-linked recessives manifest mainly in males. Haldane's rule is a statistical tendency, not an absolute, which is why A is wrong.

---

**6. Which scenario is sympatric speciation?**

A. A mountain range divides a population into east and west halves
B. Apple maggot flies shift from hawthorn to introduced apple trees within the same orchard and mate preferentially on their host, diverging from the hawthorn race
C. An island colonised by a few individuals evolves into new species
D. Two populations diverge along a chain of interbreeding neighbours

**Answer: B**

Explanation: Sympatric speciation begins without geographic separation — here, ecological divergence (host choice) coupled to assortative mating (flies mate where they developed) reduces gene flow within a single area. A is vicariance (allopatric), C is a peripatric founder event (allopatric), and D describes a ring species.

---

**7. In character displacement, differences between two species become larger when**

A. The species are geographically separated
B. The species coexist, because intermediates compete with both and selection favours the extremes
C. Hybridisation increases
D. Drift dominates in both species

**Answer: B**

Explanation: Where the species overlap, individuals with intermediate phenotypes are the worst competitors against both parent types, so selection exaggerates the difference — beak sizes of coexisting Darwin's finch species diverge more than those of the same species on islands where only one is present. Separation removes that competitive pressure (A), and increased hybridisation would erode rather than magnify differences (C).

---

**8. Punctuated equilibrium proposes that**

A. Evolution occurs at a constant slow rate at all times
B. Species remain in long stasis with rapid change concentrated at speciation events
C. Macroevolution is unrelated to microevolution
D. Speciation never occurs in small peripheral populations

**Answer: B**

Explanation: Punctuated equilibrium's claim is about tempo: most morphological change is associated with the geologically rapid formation of new species (often in small isolated populations), while established species change little for long periods under stabilising selection. A describes gradualism; the two models are compatible at different scales rather than mutually exclusive (and D inverts the proposed mechanism).

---

**9. Why is the biological species concept unusable for most bacteria?**

A. Bacteria have no DNA
B. Bacteria do not interbreed sexually, so reproductive isolation cannot be assessed — species are defined molecularly instead
C. Bacteria are all identical
D. Bacteria are not alive

**Answer: B**

Explanation: The concept requires assessing whether populations can exchange genes through interbreeding, which bacteria (reproducing asexually and exchanging genes rarely and by different routes) cannot be evaluated against. Bacterial taxonomy therefore uses molecular criteria such as DNA–DNA hybridisation (~70%) or average nucleotide identity (~95–96%), plus morphology and metabolism. A, C, and D are all plainly false.

---

**10. A virus acquires new genome segments from a second viral lineage infecting the same cell, producing a dramatically new surface protein combination. The best analogy in this chapter is**

A. Reinforcement
B. Ring species formation
C. Hybridisation — genetic exchange between lineages producing a novel combination
D. Stabilising selection

**Answer: C**

Explanation: Influenza's antigenic shift is reassortment of whole genome segments between co-infecting lineages — the direct analogue of hybridisation, where two gene pools merge to produce a novel combination unavailable within either lineage alone. Because the human population has little immunity to the new surface proteins, pandemic strains emerge; reinforcement, ring species, and stabilising selection describe none of this.
