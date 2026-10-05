# Microbial Reproduction and Transmission

## Why it matters

Two questions govern infectious disease epidemiology: **how fast does the pathogen multiply**, and **how does it get from one host to the next?** Everything that follows — incubation periods, dosing intervals, quarantine, vaccination coverage, outbreak investigation — is derived from those two answers. A bacterium doubling every 20 minutes and a bacterium doubling every 24 hours produce completely different clinical pictures, laboratory turnaround times, and public-health responses; a virus spread by 3-metre droplets and a virus spread by 3-micrometre nuclei suspended for hours require completely different isolation procedures.

This chapter is also where the **chain of infection** framework is introduced. The chain has six links, and — this is the point — **interrupting any one of them is sufficient to stop transmission.** Hand hygiene breaks faecal–oral transmission; a mask breaks droplet transmission; a vaccine makes the susceptible host no longer susceptible; drainage of an abscess closes the portal of exit. Most infection-control practice is nothing more than naming which link a given intervention acts on.

Finally, horizontal gene transfer deserves a second pass. Chapter 01 introduced transformation, transduction, and conjugation as genetic mechanisms; here they are treated as **epidemiological mechanisms** — the reason resistance that arises in one organism in one patient can be in the next patient in a different species by the following week.

## Binary fission and generation time

Bacteria reproduce by **binary fission**, not mitosis. The sequence is short and mechanistically distinct from eukaryotic division:

```
1. GROWTH          cell elongates; ribosomes and enzymes accumulate
        ↓
2. REPLICATION     single circular chromosome replicates from ONE origin
        ↓           (oriC); the two copies are pushed apart as the cell grows
3. SEGREGATION     Par system and elongation separate the chromosomes
        ↓
4. Z-RING          FtsZ (tubulin homologue) polymerises at MIDCELL,
        ↓           recruits division machinery
5. SEPTATION       new wall laid inward; membrane pinches →
        ↓
6. TWO DAUGHTER CELLS, each with one chromosome and (often) copies of
   every plasmid present in the parent
```

Two differences from eukaryotic division are reliably examined: **there is no spindle apparatus and no mitosis**, and **there is no cell plate** — the septum grows inward and the new wall is assembled locally, unlike a plant cell. FtsZ is the prokaryotic tubulin homologue discussed in [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md).

### Generation time: the arithmetic that explains everything

The **generation time** (*g*) is the time for one cell to become two. It depends on species and conditions:

| Organism | Generation time (optimal) | Consequence |
| --- | --- | --- |
| *Escherichia coli* (rich medium, 37 °C) | **~20 minutes** | Contamination visible within hours |
| *Staphylococcus aureus* | ~30 minutes | Rapid wound infection |
| *Vibrio cholerae* | ~8–10 minutes | Explosive watery diarrhoea |
| ***Mycobacterium tuberculosis*** | **~24 hours** (in vivo) | Cultures take 3–8 weeks; incubation of weeks to months |
| *Treponema pallidum* | ~30 hours | Syphilis progresses over years |
| Fungi (e.g. *Candida*) | ~1–2 hours | Slower growth → long antifungal courses |

Population size follows:

$$N = N_0 \times 2^{\,t/g}$$

**Worked example 1 — how long until a billion?**

```
one E. coli cell at 08:00, g = 20 min

N = 2ⁿ ≥ 10⁹
    → n ≥ log₂(10⁹) = 9 / 0.301 ≈ 30 generations
    → 30 × 20 min = 600 min = 10 hours

by 18:00 the flask contains ~10⁹ cells, all descended from one.
```

**Worked example 2 — why a contaminated culture is unusable.**

A single contaminating cell in a blood culture bottle reaches detectable density (≈10⁵–10⁶ CFU/mL) in roughly 6–8 hours; by 48 hours a colony on an agar plate is ~10⁷–10⁸ cells from one ancestor, which is why a "colony-forming unit" is counted as one original cell even though it now contains millions.

**Worked example 3 — why doubling cannot continue.**

At 20-minute doubling, one cell would produce more cells than exist in the observable universe in about two days. It never happens: nutrients deplete, waste accumulates, pH shifts, and space runs out — which is exactly the **stationary phase** of the growth curve in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md). The lag → log → stationary → decline curve is growth meeting a carrying capacity.

**Clinical translations worth holding:**

- The **incubation period** is roughly the time required to reach an infectious dose at the portal of entry — a faster-growing pathogen generally gives a shorter incubation period.
- **Antibiotic dosing intervals** must span the periods when the population is actively dividing, since β-lactams act only on growing cells.
- **Culture time in the laboratory** is set by generation time: rapid growers report in 24–48 hours; *Mycobacterium* requires weeks.

### Spore formation revisited

When nutrients run out, sporulating genera do not divide faster — they stop dividing and build a spore.

| | **Binary fission** | **Sporulation (endospore)** |
| --- | --- | --- |
| Purpose | **Increase cell number** | **Survive hostile conditions** |
| Product | Two equivalent vegetative cells | One dormant spore per parent cell |
| Metabolism during | Active | Essentially none |
| Trigger | Nutrient availability | Nutrient depletion, crowding |
| Result on return of nutrients | Continued growth | Germination → **one** vegetative cell |
| Clinical implication | Colonisation and infection | Persistence on surfaces, treatment failure, relapse |

**Sporulation is not reproduction and not a response to antibiotics alone** — it is a starvation response. That matters for *C. difficile*: antibiotics deplete the competing flora, spores germinate in the colon, and the vegetative population that emerges is then free to expand without competition. The structural and resistance details are in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md).

## Horizontal gene transfer: how resistance moves

Vertical inheritance (parent to offspring) explains spread within a lineage. It cannot explain why a resistance gene found in a soil *Streptococcus* appears in a hospital *Staphylococcus* within a season. For that you need horizontal transfer.

| Mechanism | Vehicle | Requirement | Speed of spread | Medical example |
| --- | --- | --- | --- | --- |
| **Transformation** | Free DNA from a lysed cell | A **competent** recipient (species-specific) | Local — whatever is in the environment | Uptake of resistance genes from DNA released on antibiotic treatment |
| **Transduction** | **Bacteriophage** | Susceptible bacterial host for the phage | Bounded by phage host range | Diphtheria toxin gene carried by a lysogenic phage; staphylococcal resistance via phage |
| **Conjugation** | **Sex pilus + mating bridge** | Physical contact; often a **conjugative plasmid** | **Fastest and cross-species** | **R plasmid transfer of multi-drug resistance** between *E. coli*, *Klebsiella*, *Salmonella* |

### R factors (resistance plasmids)

An **R plasmid** (R factor) is a self-transmissible plasmid carrying **one or usually several resistance genes together with transfer (*tra*) genes** that build the pilus and the bridge.

```
        R PLASMID
   ┌────────────────────────────┐
   │  tra genes (pilus, nicking)│──► makes the plasmid self-transmissible
   │  bla gene   (β-lactamase)  │
   │  sul gene   (sulfa target) │
   │  tet gene   (tetracycline  │
   │              efflux)       │
   │  aad gene   (aminoglycoside│
   │              modification) │
   └────────────────────────────┘
        │  one conjugation event
        ▼
   recipient is NOW resistant to four drug classes at once
```

Three consequences:

1. **Co-selection.** Giving one antibiotic selects for the whole plasmid — every gene on it is carried along. This is why resistance to drugs that were never used in a ward still rises there.
2. **Cross-species transfer.** Unlike transformation, conjugation is not restricted by species, so plasmids move between Enterobacteriaceae freely.
3. **Accumulation.** Transposons and **integrons** (gene cassettes with a common integrase) stack additional resistance cassettes onto the same element, producing the multi-drug-resistant organisms classified by WHO and national surveillance.

Mutation supplies the raw variation; **selection** enriches it; **horizontal transfer spreads it between organisms.** Three separate processes, frequently conflated.

## Viral replication modes

Viruses do not divide — they assemble. Their "reproductive rate" is the number of new virions produced from one infected cell (burst size) and the number of new hosts infected per case.

| Mode | What happens | Examples | Clinical consequence |
| --- | --- | --- | --- |
| **Lytic** | Replicate → assemble → **cell lyses** | Influenza (non-enveloped assembly aside — releases by budding with damage), poliovirus, phage T4 | Acute disease with rapid onset |
| **Lysogenic / latent** | Genome persists in host cell (prophage or provirus), copied silently with the cell | λ phage, **herpes simplex** (ganglia), **HIV** (provirus in memory CD4⁺ T cells) | Recurrence on reactivation (cold sores, shingles, genital herpes); lifelong infection |
| **Persistent / chronic** | Continuous release of virions **without killing the cell** | HBV, HCV | Decades of infectivity; cirrhosis and cancer risk |
| **Budding** | Virion acquires envelope and leaves; cell may survive | HIV, influenza, Ebola | Prolonged shedding |
| **Cell-to-cell spread** | Virion passes directly across junctions, avoiding extracellular exposure | HSV, cytomegalovirus | Immune evasion |

**The lytic–lysogenic choice in a phage** was covered in [03 — Viruses](03-viruses.md); the epidemiological point here is that **latent viruses generate a reservoir that no amount of acute-case isolation will remove**, because the host appears well and is often most infectious only on reactivation.

## The chain of infection

Six links, in order — and six opportunities to intervene.

```
   INFECTIOUS AGENT
         │
         ▼
   ─── RESERVOIR ───          where it normally lives
         │                    (human / animal / environment)
         ▼
   ─── PORTAL OF EXIT ───     how it leaves the reservoir
         │
         ▼
   ─── MODE OF TRANSMISSION ── how it travels
         │
         ▼
   ─── PORTAL OF ENTRY ───    how it gets in
         │
         ▼
   ─── SUSCEPTIBLE HOST ───   immunity, dose, underlying disease
```

| Link | Examples of intervention |
| --- | --- |
| Agent | Antimicrobial therapy reduces shedding |
| Reservoir | Culling infected birds; vector control; treating chronic carriers |
| Portal of exit | Masks, dressings, hand hygiene, isolation |
| Transmission | Ventilation, water treatment, condoms, gloves, sterilisation |
| Portal of entry | Handwashing, safe food handling, PEP after needlestick |
| Susceptible host | **Vaccination**, post-exposure prophylaxis, nutrition, CD4 preservation |

**Most of infection control is really link four.**

### Portals of exit

| Portal of exit | Organisms leaving by this route |
| --- | --- |
| **Respiratory tract** (cough, sneeze, talk) | *Mycobacterium tuberculosis*, influenza, measles, *Bordetella pertussis*, *N. meningitidis*, SARS-CoV-2 |
| **Faeces (faecal–oral)** | *Salmonella*, *Shigella*, *Vibrio cholerae*, *E. coli* pathotypes, norovirus, rotavirus, hepatitis A and E, *Giardia*, *Entamoeba*, *Cryptosporidium* |
| **Skin and lesions** (scaling, pus, crusts) | *Staphylococcus aureus*, *Streptococcus pyogenes*, *Mycobacterium leprae*, herpes simplex, varicella-zoster |
| **Genital secretions** | *Neisseria gonorrhoeae*, *Chlamydia trachomatis*, *Trichomonas vaginalis*, HIV, HPV |
| **Blood** (needles, bites, vectors) | HIV, HBV, HCV, *Plasmodium* (via mosquito), Ebola |
| **Placenta / breast milk** | Rubella, HIV, HBV, *Toxoplasma*, cytomegalovirus, Zika |
| **Urine, respiratory secretions, other body fluids** | Leptospirosis (urine), hantavirus |

### Portals of entry

| Portal of entry | Route | Organisms |
| --- | --- | --- |
| **Respiratory tract** | Inhaled droplets or dust | TB, influenza, measles, varicella, histoplasmosis, anthrax |
| **Gastrointestinal tract** | Ingestion | Hepatitis A, cholera, typhoid, norovirus, *Giardia* |
| **Skin** | Direct penetration or inoculation | Hookworm larvae, *S. aureus* in a cut, *Clostridium tetani* spores in a wound, schistosome cercariae |
| **Genital / urogenital** | Sexual contact | Gonorrhoea, chlamydia, syphilis, HIV, herpes |
| **Parenteral** (break in skin/mucosa) | Needlestick, transfusion, bite, surgery | HIV, HBV, HCV, rabies, Ebola |
| **Placenta (transplacental)** | Congenital infection | Rubella, HIV, syphilis, *Toxoplasma*, Zika, CMV |

## Modes of transmission

The distinction that drives isolation policy is **how far and how long the infectious particle travels**.

| Mode | Particle / vehicle | Distance and duration | Organisms | Main control |
| --- | --- | --- | --- | --- |
| **Direct contact** | Touching, skin to skin, sexual contact | Immediate proximity | *S. aureus* (impetigo), *S. pyogenes*, herpes simplex, HPV (warts), *Trichophyton* (tinea), scabies | Gloves, gowns, hand hygiene, condoms |
| **Droplet** | **Large droplets > 5 μm** | Short range, **< 1–2 m**, fall quickly | *N. meningitidis*, *S. pneumoniae*, influenza, pertussis, mumps, adenovirus | **Surgical mask**, ~1 m distance |
| **Airborne** | **Droplet nuclei ≤ 5 μm** and dust | **Metres to rooms, suspended for hours** | ***Mycobacterium tuberculosis***, **measles**, varicella, smallpox (historically), hantavirus | **Negative-pressure room, ventilation, N95/FFP2 respirator** |
| **Faecal–oral / vehicle** | Contaminated **water, food, hands, instruments** | Indefinite in the vehicle | Cholera, typhoid, hepatitis A/E, *Giardia*, *Cryptosporidium*, norovirus, *E. coli* O157:H7 | Water chlorination, sanitation, food safety, handwashing |
| **Vector-borne — biological** | Arthropod that replicates the pathogen | Km scale via flight | *Anopheles* → malaria; *Aedes* → dengue, Zika; tsetse → sleeping sickness; sandfly → leishmaniasis; tick → Lyme borreliosis | Insecticide, bed nets, repellents, habitat control |
| **Vector-borne — mechanical** | Fly feet and gut carrying organisms | Local | Flies carrying *Salmonella* onto food | Food covering, fly control |
| **Bloodborne / parenteral** | Blood and body fluids, needles | Direct inoculation | HIV, HBV, HCV, Ebola | Sharps safety, screening, universal precautions, needle-exchange |
| **Vertical (congenital)** | Transplacental, perinatal, breastfeeding | Mother to child | HIV, HBV, syphilis, rubella, CMV, *Toxoplasma*, Zika | Antenatal screening, antivirals in labour, immunoglobulin, infant prophylaxis |

**The envelope rule from [03 — Viruses](03-viruses.md) applies throughout:** enveloped viruses are fragile outside a host, so they cluster in direct contact, droplet, and bloodborne routes; non-enveloped viruses persist, so they dominate faecal–oral and vehicle transmission.

## Reservoirs

The reservoir is **where the pathogen normally lives and multiplies**, and knowing it tells you where to intervene.

| Reservoir | Meaning | Examples |
| --- | --- | --- |
| **Human** | Humans are the only natural host — transmission stops if humans are treated or immunised | Measles, varicella, tuberculosis (principally), *N. gonorrhoeae*, HIV |
| **Animal (zoonosis)** | Pathogen maintained in animals; humans are accidental hosts | Rabies, anthrax, plague, *Salmonella*, *Campylobacter*, brucellosis, Ebola (suspected bat reservoir), Lyme borreliosis |
| **Environmental** | Soil or water; no infected host needed | *Clostridium tetani*, *Clostridium perfringens*, *Legionella* (water systems), free-living amoebae |
| **Human chronic carrier** | Asymptomatic person shedding intermittently | Typhoid (*Salmonella typhi* — Mary Mallon), hepatitis B, *Shigella* |

**Zoonoses explain why most emerging infectious diseases are zoonotic**: the pathogen is already adapted to replication in a host, and human contact with that reservoir is the new variable (HIV from primates, SARS-CoV-1 from civets/bats, MERS from camels).

## R₀ and herd immunity

**R₀ (basic reproduction number)** = the average number of secondary cases produced by one infected individual in a **completely susceptible** population.

```
R₀ < 1   →  outbreak dies out (each case infects fewer than one)
R₀ > 1   →  spread accelerates
R₀ ≫ 1   →  explosive epidemic; high vaccination coverage required
```

| Disease | Approximate R₀ |
| --- | --- |
| Measles | **12–18** |
| Pertussis (whooping cough) | 12–17 |
| Smallpox | 5–7 |
| Poliomyelitis | 5–7 |
| Diphtheria | 6–7 |
| SARS-CoV-2 (ancestral) | ~2.5 |
| Seasonal influenza | ~1.3 |
| HIV | ~2–5 |

**Effective reproduction number, R_eff**, is R₀ multiplied by the proportion of the population that is still susceptible. If enough people are immune, R_eff falls below 1 and transmission stops — this is **herd immunity (community immunity)**. The theoretical threshold is:

$$p_c = 1 - \frac{1}{R_0}$$

**Worked example:**

```
measles, R₀ = 15      →  p_c = 1 − 1/15 = 0.933 → ~93% immune
pertussis, R₀ = 12.5  →  p_c = ~92%
polio, R₀ = 5         →  p_c = 80%
COVID-19 ancestral, R₀ ≈ 2.5 → p_c ≈ 60%
```

In practice the required **vaccine coverage is higher than p_c**, because no vaccine is 100 % effective, some people cannot be vaccinated (infants, immunosuppressed), and coverage is uneven geographically and socially. This is the arithmetic behind routine childhood schedules, and it explains why measles — the most transmissible disease on the list — is the first to resurface when coverage falls. The immune side of this argument (memory, secondary response, vaccine types) is in [09 — Human Biology](../09-human-biology/) and [03 — Viruses](03-viruses.md).

## Epidemiological vocabulary

| Term | Definition | Example |
| --- | --- | --- |
| **Sporadic** | Occurring irregularly and unpredictably | Typhoid in a country with good sanitation; rabies cases |
| **Endemic** | Constant, baseline presence in a defined population or region | Malaria in sub-Saharan Africa; tuberculosis worldwide; cholera in parts of South Asia |
| **Hyperendemic** | Perpetually high in prevalence | HIV in some sub-Saharan countries; hepatitis B in East Asia |
| **Outbreak (case cluster)** | More cases than expected **in a limited setting** | A single ward, a school, a restaurant |
| **Epidemic** | An increase, above expected, **in a defined community or region** | Influenza season; a *Salmonella* outbreak across a city |
| **Pandemic** | Epidemic spreading across **countries and continents** | 1918 influenza; 2009 H1N1; **COVID-19** |
| **Emerging infection** | Newly recognised, increasing, or geographically spreading | HIV (1980s), SARS (2003), MERS (2012), Ebola (2014), SARS-CoV-2 (2019) |
| **Zoonosis** | Animal-to-human infection | Rabies, avian influenza |
| **Attack rate** | Proportion of exposed people who become ill | Foodborne outbreak investigation |
| **Case fatality rate** | Proportion of diagnosed cases who die | Ebola (high), influenza (low) |

**Sporadic vs endemic is a frequency statement, not a severity statement**: sporadic means *irregular*; endemic means *always present at some level*. An endemic disease may be rare (malaria in Morocco) or hyperendemic.

## Medical relevance

**Isolation precautions follow directly from the mode of transmission.** Contact precautions (gloves, gowns, dedicated equipment) for *S. aureus*, VRE, and *C. difficile*; droplet precautions (surgical mask, 1 m) for meningococcus and influenza; airborne precautions (negative-pressure room, N95) for pulmonary tuberculosis and measles. Applying the wrong category is a common and dangerous error: a mask that stops droplets does **not** stop 3-micrometre nuclei drifting down a corridor.

**Incubation period determines contact tracing windows.** Measles contacts are followed for 21 days; rabies post-exposure prophylaxis is urgent because once symptoms appear the disease is invariably fatal; HIV PEP must begin within 72 hours. The interval is a function of the pathogen's generation time and dose at entry.

**R₀ sets vaccination policy.** Measles requires roughly 95 % coverage with two doses, which is why school-entry mandates exist and why measles outbreaks follow any fall in coverage below that level.

**Outbreak investigation walks the transmission chain backwards.** A cluster of watery diarrhoea → stool culture → vehicle identified (well water) → reservoir (a faecal contamination event) → portal of exit (an infected animal or sewage) → intervention at link four. The same logic identifies foodborne vehicles using attack rates among diners.

**Antibiotic pressure is itself an epidemiological intervention.** Restricting broad-spectrum use reduces selection pressure and slows resistance — a population-level application of the selection logic in [06 — Evolution](../06-evolution/). Hospital screening for MRSA on admission and decolonisation with mupirocin act on the reservoir and portal-of-exit links respectively.

**Blood safety is a vehicle-route success story.** Screening of donated blood for HIV, HBV, and HCV, plus pathogen reduction steps, has reduced transfusion-transmission to near zero — an intervention at the vehicle link that is invisible to patients and enormously effective.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Sporulation is bacterial reproduction" | Fission increases cell number; **sporulation produces one spore per cell** — survival, not multiplication. |
| "Generation time is fixed for a species" | It is a property of species *and conditions* — *E. coli* is ~20 min optimally, far slower at low temperature or poor medium, and *M. tuberculosis* takes ~24 h regardless. |
| "Droplet and airborne are the same" | Droplets are **> 5 μm, travel ~1 m, fall quickly** (mask + distance); droplet nuclei are **≤ 5 μm, remain airborne for hours** (respirator + ventilation). |
| "Direct contact means only skin touching skin" | Direct contact includes sexual contact and contact with secretions; **indirect (vehicle) contact** means a contaminated object or medium carries the organism. |
| "A vector is any animal involved" | A vector is an **arthropod (or occasionally other animal) that transmits**; a *reservoir* is where the pathogen lives. The dog that bites and transmits rabies is a vehicle, not a biological vector. |
| "R₀ is a property of the pathogen alone" | It depends on **pathogen, host behaviour, population density, and contact patterns** — hence estimates for the same disease vary between settings. |
| "Herd immunity means people who are naturally immune" | It means **any immunity** — vaccination, prior infection, or passive antibody — in enough of the population to push R_eff below 1. |
| "Endemic means widespread" | Endemic means **continuously present at a baseline**; it says nothing about how common that baseline is. |
| "Vertical transmission is always congenital" | Congenital (transplacental) is one form; **perinatal** (during birth) and **postnatal via breast milk** are also vertical routes. |
| "Antibiotics prevent secondary bacterial infection after viral illness" | **No** — they do not prevent anything; unnecessary use selects resistance and risks *C. difficile* |

## Key facts

- **Binary fission**: growth → chromosome replication from a single origin → segregation → **FtsZ Z-ring** → septation. **No mitosis, no spindle, no cell plate.**
- **Generation time**: *E. coli* ≈ **20 min** optimally; *M. tuberculosis* ≈ 24 h — growth rate sets incubation period and laboratory culture time.
- **N = N₀ × 2^(t/g)**: 30 generations ≈ 10 hours for *E. coli* → one cell to ~10⁹.
- Growth curve and its clinical meanings (log-phase susceptibility, stationary-phase tolerance) are in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md).
- **Sporulation is survival, not reproduction** — one cell, one spore, one cell.
- Horizontal transfer: **transformation** (naked DNA), **transduction** (phage), **conjugation** (pilus) — conjugation is fastest and crosses species barriers.
- **R plasmids** carry several resistance genes plus transfer genes → **co-selection** makes one antibiotic select for resistance to several.
- Viral replication modes: **lytic, lysogenic/latent, persistent, budding** — latent and chronic infections create reservoirs isolation cannot remove.
- **Chain of infection**: agent → reservoir → portal of exit → transmission → portal of entry → susceptible host — **break any link**.
- **Transmission modes**: direct contact, droplet (>5 μm, <1–2 m), airborne (≤5 μm, hours), faecal–oral/vehicle, vector (biological vs mechanical), bloodborne, vertical.
- **R₀** = secondary cases from one case in a fully susceptible population; **herd immunity threshold = 1 − 1/R₀** (measles ≈ 93–95 %).
- Vocabulary: **sporadic** (irregular) → **endemic** (baseline) → **epidemic** (above expected, one region) → **pandemic** (multi-country).

## Practice questions

**1. One *E. coli* cell divides every 20 minutes with no deaths. How many cells are present after 4 hours?**

A. 240 cells
B. 2¹² = 4 096
C. 2³⁰ ≈ 10⁹
D. 240 million

**Answer: B**

Explanation: Four hours is 240 minutes, which is 240 ÷ 20 = **12 generations**, so the population is 2¹² = 4 096 cells. Growth is geometric, not arithmetic, which eliminates A (one cell per division counted additively) and D (a linear extrapolation). Option C — roughly a billion cells — is the figure for about 30 generations, or ten hours, not four. The general form is N = N₀ × 2^(t/g).

---

**2. Which process increases the genetic diversity of a bacterial population without requiring cell-to-cell contact?**

A. Binary fission
B. Conjugation
C. Transformation
D. Sporulation

**Answer: C**

Explanation: Transformation is the uptake of free DNA from the environment — DNA released when other cells lyse — so no contact between living cells is needed; any competent recipient in the vicinity can incorporate it. Conjugation requires direct contact through a pilus, binary fission produces genetically identical daughters, and sporulation is a dormant survival state with no new genetic information.

---

**3. The most important practical difference between droplet and airborne precautions is that airborne transmission**

A. Requires only hand hygiene
B. Involves particles ≤ 5 μm that remain suspended over distances and hours, requiring ventilation and an N95 respirator
C. Occurs only through direct skin contact
D. Cannot be interrupted by any measure

**Answer: B**

Explanation: Droplet precautions deal with large particles that fall within about a metre — a surgical mask and physical distance suffice. Droplet nuclei of 5 μm or less stay airborne across rooms and for hours, so *Mycobacterium tuberculosis* and measles require negative-pressure isolation, HEPA ventilation, and a fitted N95/FFP2 respirator. Hand hygiene (A) is necessary but nowhere near sufficient, contact (C) is a different route, and D is contradicted by the whole of infection control.

---

**4. An R plasmid carrying genes for resistance to ampicillin, tetracycline, and streptomycin transfers to a recipient bacterium. The immediate consequence is that**

A. The recipient becomes resistant to all three drugs simultaneously
B. The recipient dies from plasmid toxicity
C. The plasmid integrates into the chromosome immediately
D. The recipient becomes sensitive to ampicillin

**Answer: A**

Explanation: Resistance genes on a single plasmid are inherited and expressed together, so one conjugation event transfers multi-drug resistance at once. Crucially, this creates **co-selection**: using only one of the three antibiotics still selects for cells carrying the whole plasmid, which is why resistance to drugs never used locally can still rise. Integration into the chromosome (C) may happen but is not required for expression, plasmids confer benefit rather than toxicity (B), and sensitivity is the opposite of the outcome (D).

---

**5. Which link of the chain of infection does vaccination act upon?**

A. Reservoir
B. Portal of exit
C. Mode of transmission
D. Susceptible host

**Answer: D**

Explanation: Vaccination generates memory B and T cells so that the individual is no longer susceptible — the organism may enter but is cleared before disease or significant shedding. Masks and ventilation act on transmission; treating a carrier acts on shedding (portal of exit); culling infected animals acts on the reservoir. Interrupting any single link breaks the chain, but the host link is the one vaccination addresses.

---

**6. Measles has an R₀ of approximately 15. The theoretical proportion of the population that must be immune to interrupt transmission is about**

A. 7 %
B. 60 %
C. 93 %
D. 150 %

**Answer: C**

Explanation: The herd immunity threshold is pc = 1 − 1/R₀ = 1 − 1/15 ≈ 0.933, i.e. about 93 % — and in practice coverage must be higher still because no vaccine is completely effective, some people cannot be vaccinated, and transmission clusters where coverage is lowest. Option A (1/R₀) is the susceptible fraction that may remain, B corresponds to an R₀ of about 2.5, and D is impossible.

---

**7. Which pair correctly matches an organism with its route of transmission?**

A. *Mycobacterium tuberculosis* — faecal–oral
B. *Vibrio cholerae* — airborne
C. *Neisseria meningitidis* — droplet
D. Measles — contact with fomites only

**Answer: C**

Explanation: Meningococcus spreads in large respiratory droplets at close range, so droplet precautions (surgical mask within 1 m) apply. *M. tuberculosis* is airborne via droplet nuclei, not faecal–oral; cholera is classically faecal–oral through contaminated water; measles is among the most infectious airborne diseases known, not a fomite-borne infection.

---

**8. A patient's infection is described as endemic in their country. This means**

A. It occurs only sporadically and unpredictably
B. It is constantly present at a baseline level in that population
C. It is spreading globally across continents
D. It is always fatal

**Answer: B**

Explanation: Endemic means continuously present at an expected baseline — malaria in sub-Saharan Africa, tuberculosis in many countries. Sporadic means irregular and unpredictable (A); pandemic means spreading across countries and continents (C); endemicity says nothing about severity or fatality (D). Epidemic, by contrast, means a rise above the expected baseline in a defined community.

---

**9. Which statement about sporulation is correct?**

A. It is triggered by antibiotics and produces multiple offspring
B. It is a starvation response producing one dormant, highly resistant spore per cell, with no increase in cell number
C. It is a form of sexual reproduction
D. It occurs in all bacterial species

**Answer: B**

Explanation: Sporulation is induced by nutrient depletion and crowding, not by antibiotics as such, and the product is one spore that can germinate into one vegetative cell — survival without multiplication. It is not sexual (C) and is confined to particular genera, principally *Bacillus* and *Clostridium* (D). Antibiotics do not directly trigger it, though the ecological disruption of antibiotic treatment can favour spore-forming organisms such as *Clostridioides difficile*.

---

**10. Why does an infection with a latent (lysogenic or proviral) virus create a public-health reservoir that acute-case isolation cannot remove?**

A. Latent viruses are not infectious at any time
B. The host is often asymptomatic and apparently healthy, yet can reactivate and shed virus, so transmission is not detectable by symptom screening
C. Latent viruses cannot be transmitted by any route
D. Latent viruses replicate only outside the body

**Answer: B**

Explanation: In latency the viral genome persists quietly in host cells — herpes simplex in sensory ganglia, HIV provirus in resting memory CD4⁺ T cells — and the person shows no symptoms. Reactivation produces shedding (recurrent herpes, zoster, viral rebound off therapy) without warning, so symptom-based screening misses them. This is precisely why reservoir links matter more than portal-of-exit interventions for these infections, and why lifelong suppressive therapy and contact precautions during reactivation are used.
