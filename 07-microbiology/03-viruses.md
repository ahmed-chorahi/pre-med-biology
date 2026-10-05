# Viruses

## Why it matters

Viruses sit at the edge of the definition of life, and they cause the majority of acute infectious disease you will encounter. Every cold, every bout of influenza, every case of measles, hepatitis, HIV, and COVID-19 is a viral infection — and the reason the common cold remains uncured while bacterial pneumonia is routinely cured is entirely explained by the biology in this chapter. **Antibiotics do not work on viruses**, and that statement only becomes useful once you know *why*: the structures those drugs target simply do not exist in a virion.

Viruses also matter as a model. Bacteriophages supplied the experimental evidence that DNA is the genetic material, that the genetic code is triplet, and that genes are arranged in operators — before anyone knew what a gene looked like. And the replication strategies here, particularly reverse transcription and integration, connect directly to oncology, to the mechanics of retroelements in the human genome, and to how antiviral drugs are designed.

Finally, viruses are the case where **structure dictates control**. An enveloped virus is destroyed by soap; a non-enveloped virus is not. An influenza virus can swap gene segments with a relative and produce a pandemic; a measles virus cannot change enough to escape immunity. Understanding the physical particle explains the public-health rule, and understanding the genome explains the epidemiology.

## What a virus is — and what it is not

A virus is an **obligate intracellular parasite** consisting of genetic material — DNA or RNA, never both in the infectious particle — enclosed in a protein coat, that can replicate only inside a host cell using that cell's machinery.

| Feature | Virus | Cell |
| --- | --- | --- |
| **Cellular organisation** | **None** | Present |
| **Ribosomes** | **None** — cannot synthesise protein | 70S or 80S |
| **Metabolism** | **None** — no respiration, no ATP generation | Complete pathways |
| **Genome** | One type of nucleic acid: DNA *or* RNA | Both DNA and RNA |
| **Reproduction** | Only inside a host cell, by redirecting host machinery | Independent binary fission or division |
| **Growth, homeostasis, response** | Absent | Present |
| **Evolution** | **Yes** — mutation, selection, recombination, drift | Yes |

The first three absences are decisive: the cell theory statement that all living things are made of cells, and that cells come from pre-existing cells, was qualified in [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md) precisely because viruses are not cells.

### The "are viruses alive?" question

```
ARGUMENTS FOR "NOT ALIVE"              ARGUMENTS FOR "ALIVE ENOUGH"
─────────────────────────────          ─────────────────────────────
No cell, no metabolism, no growth      Carry genetic material, evolve rapidly
Inert outside a host (virion only)    Natural selection acts on populations
Cannot reproduce independently         Some encode enzymes (replicases, RT)
Obligate parasite of the machinery     Within a cell, directs its own replication
  of something else
```

The standard resolution: **the virion is not alive; the replicating virus inside a cell is a biological entity that evolves.** Life is a continuum question rather than a property list, and an exam answer that says "viruses are obligate intracellular parasites lacking metabolism and ribosomes, and therefore are not considered living organisms, though they evolve" is complete. What you should not say is that viruses are "dead bacteria" or "tiny cells" — they have neither.

## Virion structure

### The capsid

The capsid is a self-assembled shell of protein subunits called **capsomeres**, built around the genome.

| Capsid symmetry | Geometry | Examples |
| --- | --- | --- |
| **Helical** | Capsomeres coil around the genome → rigid rod or flexible filament | Tobacco mosaic virus (300 × 18 nm rod); Ebola (filamentous); rhabdoviruses (bullet-shaped) |
| **Icosahedral** | 20 triangular faces, 12 vertices — the most efficient closed shell | Poliovirus, adenovirus, rhinovirus, norovirus, hepatitis B core |
| **Complex** | Head–tail assembly, or irregular with extra structures | Bacteriophage T4 (head + contractile tail + baseplate + tail fibres); **poxviruses** (large, brick-shaped, with lateral bodies) |

```
HELICAL                 ICOSAHEDRAL              COMPLEX (phage T4)

 ┌──────┐                 /\      /\                 ┌─────┐ head (dsDNA)
 │≡≡≡≡≡≡│               /  \____/  \                │     │
 │≡≡≡≡≡≡│              |  /\    /\  |               └──┬──┘
 │≡≡≡≡≡≡│              | /  \__/  \ |                ══╪══ contractile sheath
 └──────┘               \/________\/                 ══╪══ baseplate
 genome inside          20 faces, 12 vertices         ──┴── tail fibres
 (RNA or DNA)                                        (attach to host)
```

The capsid's jobs: **protect the genome** from nucleases and physical damage, **determine host range** through receptor-binding proteins, and in some viruses **mediate attachment and entry**.

### The envelope

Many viruses add a **lipid envelope** outside the capsid. Critically, the envelope is **stolen from the host**.

```
viral glycoproteins inserted into host ER / Golgi membrane
        │  (processed by the Golgi exactly like host proteins)
        ▼
virion buds through the membrane
        │  acquires lipid bilayer + embedded viral spikes
        ▼
ENVELOPED VIRION  —  host lipid, viral protein
```

This is viral hijacking of the secretory pathway in its most literal form: budding through the endoplasmic reticulum, Golgi, or plasma membrane means the envelope is chemically **host membrane** carrying **viral glycoproteins** that were folded, glycosylated, and sorted by the cell's own machinery. The full route is described in [02 — Cell Biology](../02-cell-biology/03-protein-synthesis-and-trafficking-organelles.md), and the chapter's statement that "viruses hijack this entire system" is exactly this step.

| Property | Enveloped virus | Non-enveloped (naked) virus |
| --- | --- | --- |
| **Membrane** | Present, host-derived | Absent |
| **Typical examples** | Influenza, HIV, measles, SARS-CoV-2, herpes simplex, Ebola, hepatitis B | Poliovirus, norovirus, adenovirus, rotavirus, hepatitis A |
| **Susceptibility** | **Killed by detergents, soap, alcohol, heat, drying** | **Resistant** to detergents, many disinfectants, stomach acid |
| **Environmental survival** | Poor — requires close contact or droplets | Excellent — faecal–oral route, fomites, survives months |
| **Infection control** | Hand hygiene with soap or alcohol is highly effective | Soap removes but does not destroy; **hands and surfaces need more** |

**This single difference predicts the route of transmission.** Enveloped viruses spread by respiratory droplets, blood, and close contact because they cannot survive long outside a body. Non-enveloped viruses dominate the faecal–oral and fomite routes because they persist on surfaces and pass through the gut. That link is made explicitly in [05 — Microbial reproduction and transmission](05-microbial-reproduction-and-transmission.md).

### Size

Viruses span roughly 20–300 nm — below the resolution of a light microscope, visible only by electron microscopy:

```
Bacterium  ──────── 1 000–5 000 nm     (≈ 100× larger than most viruses)
Poxvirus   ──────── 300 × 200 nm        largest animal virus
T4 phage   ──────── 200 nm head
Ebola      ──────── filament, 80 nm wide
HIV        ──────── 100–120 nm
Influenza  ──────── 80–120 nm
Adenovirus ──────── 90 nm
Poliovirus ──────── 30 nm
Rhinovirus ──────── 30 nm
```

## Genome types and Baltimore classification

Baltimore's scheme sorts viruses by **genome type and the strategy used to reach mRNA**, because all viruses must make mRNA to be translated by host ribosomes.

```
                        ┌────────────── DNA viruses ──────────────┐
                        │  I   dsDNA        (herpes, pox, adeno)  │
                        │  II  ssDNA        (parvovirus)          │
                        └─────────────────────────────────────────┘
GENOME                  ┌────────────── RNA viruses ──────────────┐
                        │  III dsRNA        (rotavirus)           │
                        │  IV  (+)ssRNA     (polio, flavivirus,   │
                        │                    SARS-CoV-2)          │
                        │  V   (−)ssRNA     (influenza, rabies,   │
                        │                    Ebola, measles)      │
                        │  VI ssRNA + RT    (HIV, HTLV)           │
                        │  VII dsDNA + RT   (hepadnavirus, HBV)   │
                        └─────────────────────────────────────────┘
```

| Class | Genome | First step needed to make mRNA | Key enzyme carried | Example |
| --- | --- | --- | --- | --- |
| **I** | dsDNA | Transcription by host (or viral) DNA-dependent RNA polymerase | Some carry their own polymerase (poxviruses) | Herpes simplex, adenovirus, smallpox |
| **II** | ssDNA | Convert to dsDNA first, then transcribe | Host or viral DNA polymerase | Parvovirus B19 |
| **III** | dsRNA | Transcribe inside the capsid — **RNA-dependent RNA polymerase must be packaged**, because host cells cannot read dsRNA | **Viral RdRp in the particle** | Rotavirus |
| **IV** | **(+)ssRNA** | Genome *is* mRNA — translate immediately | Replicase made from the genome | Poliovirus, hepatitis C, **SARS-CoV-2** |
| **V** | **(−)ssRNA** | Must be transcribed to mRNA first — genome cannot be translated | **RdRp packaged in the virion** | Influenza, measles, rabies, Ebola |
| **VI** | ssRNA with **reverse transcriptase** | Reverse transcribe to dsDNA → integrate as provirus → host transcription | **Reverse transcriptase + integrase** | **HIV**, HTLV |
| **VII** | dsDNA with an RNA intermediate | Transcribe to RNA, then reverse transcribe back to dsDNA | Reverse transcriptase | Hepatitis B |

Three rules worth committing to:

1. **Host cells have no RNA-dependent RNA polymerase.** Any virus needing one must encode it — and that enzyme is a prime drug target because humans have nothing like it.
2. **(+)ssRNA can be translated directly**; it is infectious by itself in the sense that injected genome produces protein. (−)ssRNA is not, because it looks like neither mRNA nor anything a ribosome will read.
3. **Retroviruses must integrate.** HIV's genome becomes a permanent part of the host chromosome — which is why the infection is lifelong and why latency exists.

DNA replication, transcription control, and reverse transcription mechanics are developed in [05 — Molecular Biology](../05-molecular-biology/); nucleic acid chemistry is in [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md).

## Lytic and lysogenic cycles

Bacteriophages define the two patterns, and the same logic applies to animal viruses (herpesviruses and HIV are the classic lysogenic/latent examples).

```
        BACTERIophage infects E. coli
                 │
                 ▼
        ┌── LYTIC CYCLE ─────────────────────────────────┐
        │  adsorb → inject DNA → hijack host ribosomes   │
        │     → replicate phage DNA → synthesise capsid  │
        │       proteins → ASSEMBLE → LYSIN cleaves wall │
        │         → cell BURSTS → ~100–200 virions       │
        │           released, cell dead                  │
        └────────────────────────────────────────────────┘

        ┌── LYSOGENIC CYCLE ─────────────────────────────┐
        │  phage DNA integrates into host chromosome     │
        │     → PROPHAGE, replicated with the bacterium  │
        │         at every division (no virion made,     │
        │           host survives, immunity often       │
        │             conferred)                        │
        │                 │  UV, stress, DNA damage      │
        │                 ▼  (induction)                 │
        │        excision → enters LYTIC cycle           │
        └────────────────────────────────────────────────┘
```

**The distinction in one sentence:** the lytic cycle kills the host now; the lysogenic cycle keeps the host alive and copies the viral genome along with it, deferring the decision.

**Why lysogeny matters beyond the laboratory:** a prophage can carry **virulence genes** — the toxin genes of *Corynebacterium diphtheriae* and *Clostridium tetani* are phage-encoded, so only lysogenised strains are pathogenic. Lysogenic conversion is also how Shiga toxin genes arrive in *E. coli* O157:H7. The phage is not the pathogen; it is the payload carrier.

Lysogeny in animal viruses is called **latency**: herpes simplex establishes latency in sensory ganglia and reactivates periodically; HIV establishes a latent reservoir in memory CD4⁺ T cells that antiviral therapy cannot eliminate.

## The replication cycle, step by step

Every virus follows the same sequence; only the details differ.

```
1. ATTACHMENT      virion surface protein binds a specific HOST RECEPTOR
        ↓           (specificity = host range and tissue tropism)
2. PENETRATION     receptor-mediated endocytosis, or MEMBRANE FUSION
        ↓
3. UNCOATING       capsid removed; genome released into cytoplasm/nucleus
        ↓
4. BIOSYNTHESIS    early enzymes made → genome replicated → late
        ↓           structural proteins made  ("eclipse period" — no
        ↓             intact virions detectable inside the cell)
5. ASSEMBLY        genome packaged into capsids
        ↓
6. RELEASE         BUDDING (enveloped — cell survives for a while)
                    or LYSIS (naked — cell destroyed)
```

### Worked example 1 — influenza

| Step | Influenza detail |
| --- | --- |
| Attachment | **Haemagglutinin (HA)** binds **sialic acid** on respiratory epithelium |
| Entry | Receptor-mediated endocytosis |
| Uncoating | **M2 ion channel** lets H⁺ into the endosome; low pH triggers fusion of viral envelope with the endosomal membrane and release of the segmented genome |
| Biosynthesis | **RdRp (viral, packaged in the virion)** transcribes (−)ssRNA to mRNA in the nucleus; viral RNA polymerase also performs **cap-snatching** — stealing the 5′ cap from host pre-mRNA to prime its own transcripts |
| Assembly | Segments (8) package into new virions at the plasma membrane |
| Release | **Neuraminidase (NA)** cleaves sialic acid so buds are not re-adsorbed |

**Antigenic drift vs antigenic shift** — a distinction that decides whether a season is ordinary or historic:

| | Antigenic **drift** | Antigenic **shift** |
| --- | --- | --- |
| Mechanism | **Point mutations** in HA and NA genes during replication | **Reassortment** of genome segments when two strains co-infect one cell |
| Speed | Gradual, continuous | Abrupt |
| Consequence | Seasonal influenza epidemics; prior immunity largely fails to recognise it | **New subtype → pandemic** (1918, 1957, 1968, 2009) |
| Why possible | RNA polymerase lacks proofreading | The genome is **segmented** — segments can be shuffled like a deck of cards |

Reassortment requires **co-infection** with two strains in the same cell — the reason a pig, infected by both an avian and a human strain, is the classic mixing vessel. Because the genome is segmented, a mixed virion can carry avian HA and human-adapted polymerase genes.

### Worked example 2 — HIV

```
HIV attaches: gp120 → CD4 → CCR5/CXCR4 co-receptor
        ↓
FUSION (gp41) → capsid enters cytoplasm
        ↓
UNCOATING → REVERSE TRANSCRIPTION (RT)
   (+)ssRNA ──RT──▶ RNA:DNA hybrid ──RT──▶ dsDNA
        ↓
dsDNA enters nucleus → INTEGRASE inserts it as PROVIRUS
        ↓
host RNA polymerase II transcribes provirus → mRNA + genomic RNA
        ↓
translation: Gag, Pol, Env → processed by VIRAL PROTEASE
        ↓
ASSEMBLING virion buds (acquiring envelope) → MATURATION
```

| Feature | Detail |
| --- | --- |
| **Target cell** | CD4⁺ T cells (also macrophages, dendritic cells) |
| **Latency** | Provirus persists transcriptionally silent in **memory CD4⁺ T cells** — invisible to the immune system and to drugs |
| **Why no cure** | The latent reservoir is long-lived and does not depend on ongoing replication, so drugs that block replication leave it untouched |
| **Mutation rate** | Reverse transcriptase lacks proofreading → very high error rate → quasispecies, rapid escape from both immunity and monotherapy |

This is why HIV therapy uses **combinations of three drugs from at least two classes**: single-drug resistance emerges within weeks in a virus this error-prone.

### Worked example 3 — a plant virus and a tumour virus

- **Tobacco mosaic virus**: the original virus ever purified; helical capsid around (+)ssRNA; mechanical entry through wounds — no envelope, no receptor.
- **HPV and HBV**: persistent infection with integration or oncogenic protein expression → cervical cancer and hepatocellular carcinoma respectively. Roughly 15 % of human cancers have an infectious cause, and these two plus EBV, HTLV-1, and *H. pylori* account for most of them.

## Bacteriophages as model systems

Phages are viruses of bacteria and the most numerous biological entities on Earth. They are also the workhorse of molecular biology.

| Contribution | Experiment |
| --- | --- |
| **DNA is the genetic material** | Hershey–Chase (1952): ³²P-labelled phage DNA entered the bacterium; ³⁵S-labelled protein coat stayed outside |
| **Genetic code is triplet** | Crick, Brenner, and colleagues used phage T4 frameshift mutants |
| **Operons and regulation** | Jacob and Monod's λ and lactose operon work |
| **Transduction** | Lederberg showed phages can move bacterial genes — a resistance-transfer route |
| **Sequencing and therapy** | Phage display (2018 Nobel Prize); **phage therapy** as an alternative to antibiotics for multidrug-resistant infection |

### The plaque assay

```
   dilute phage over a bacterial LAWN (soft agar over nutrient agar)
        │
        ▼
   each infectious particle infects one cell → lysis → progeny
   infect neighbours → CLEAR ZONE = PLAQUE
        │
        ▼
   count plaques × dilution = PFU (plaque-forming units) per mL
```

A plaque is a visible hole in an opaque bacterial lawn, and each plaque ideally derives from **one initial infectious particle**. Serial dilution lets you quantify infectivity — something you cannot do by looking at a patient. Plaque morphology (large, small, turbid, clear) is itself diagnostic: **turbid plaques indicate a temperate phage** (some lysogens survive in the clearing), while clear plaques indicate obligately lytic phages.

## Prions and viroids: the edge cases

If a virus strains the definition of life, these two break it outright.

| | **Viroid** | **Prion** |
| --- | --- | --- |
| **What it is** | Naked circular RNA, ~250 nucleotides, **no capsid, no protein at all** | A **misfolded protein** — no nucleic acid of any kind |
| **Genome** | Yes — small RNA genome that self-catalyses | **None** |
| **Replication** | Uses the host's RNA polymerase II; some viroids self-cleave with **hammerhead ribozyme** | **Copies its conformation**: PrP^Sc converts host PrP^C to more PrP^Sc |
| **Hosts** | **Plants only** (potato spindle tuber, chrysanthemum stunt) | Animals — including humans |
| **Disease** | Stunting, yellowing, crop loss | **Transmissible spongiform encephalopathies**: CJD, variant CJD (BSE), kuru, GSS, fatal familial insomnia, scrapie |
| **Clinical signature** | Agricultural | Dementia, ataxia, myoclonus; **spongiform change** on histology; no inflammatory response |
| **Sterilisation** | Standard RNA inactivation | **Resistant** — needs stronger protocols (prolonged autoclaving at 134 °C, sodium hydroxide, or incineration) |

Two conclusions follow. First, **infectivity does not require a genome** — a protein conformation can propagate information, which is what PrP^Sc demonstrates. Second, the immune system does not recognise prions as foreign (they are a shape of self-protein), so there is no inflammation and no vaccine. Prions are covered again in [06 — Host–pathogen interaction](06-host-pathogen-interaction.md) where immune evasion is discussed.

## Antiviral drug targets

Antibiotics attack structures and pathways bacteria have and we do not. Viruses have almost none of those and instead borrow our machinery — so antivirals must target **virus-encoded enzymes** or **virus–host interactions**, which is why they are narrower, harder to develop, and more prone to resistance.

| Target stage | Drug class | Example | Notes |
| --- | --- | --- | --- |
| **Attachment / entry** | Monoclonal antibody; receptor antagonist; fusion inhibitor | Palivizumab (RSV); maraviroc (CCR5 blocker, HIV); enfuvirtide (fusion inhibitor) | Prevents the first step entirely |
| **Uncoating** | Ion channel blocker | **Amantadine, rimantadine** (influenza **M2**) | Resistance now near-universal in circulating influenza — no longer used |
| **Reverse transcription** | **Nucleoside reverse transcriptase inhibitors (NRTIs)** | **Zidovudine (AZT), tenofovir, emtricitabine, lamivudine** | Chain terminators: lack a 3′-OH so the growing DNA stops. Backbone of HIV therapy |
| | Non-nucleoside RT inhibitors (NNRTIs) | Efavirenz, nevirapine | Bind allosterically on RT |
| **Viral genome replication** | Nucleoside analogues | **Acyclovir** (herpes — needs viral thymidine kinase to be activated, so it is selective for infected cells); sofosbuvir (HCV); remdesivir | Activation by a viral enzyme is a second layer of selectivity |
| **Integration** | Integrase strand-transfer inhibitor | **Raltegravir, dolutegravir** (HIV) | Blocks provirus formation |
| **Polyprotein processing** | **Protease inhibitors** | Ritonavir, atazanavir (HIV); grazoprevir (HCV) | Viral polyproteins cannot mature without cleavage |
| **Release** | **Neuraminidase inhibitor** | **Oseltamivir (Tamiflu), zanamivir** (influenza) | Prevents sialic acid cleavage → virions stay clumped on the cell surface |
| **Cap-dependent endonuclease** | Polymerase acidic inhibitor | Baloxavir (influenza) | Blocks cap-snatching |
| **Viral assembly / maturation** | Capsid inhibitors | Lenacapavir (HIV) | Newer class |

**Why antibiotics fail on viruses — the four reasons:**

```
1. No CELL WALL            → β-lactams, vancomycin have no target
2. No 70S RIBOSOME         → aminoglycosides, tetracyclines, macrolides
                             have nothing to bind
3. No FOLATE SYNTHESIS     → sulfonamides and trimethoprim cannot block
                             a pathway that does not exist
4. NO METABOLISM OR INDEPENDENT
   REPLICATION             → nothing is "poisoned"; the virus uses YOUR
                             enzymes, so poisoning them poisons you
```

There is also a practical point: an antibiotic needs a target unique to the pathogen, and a virus is mostly **your own machinery in disguise**. Where a virus does encode something unique — RT, RdRp, protease, integrase, neuraminidase, M2 — a drug can exist. That is the entire map of antiviral pharmacology.

**Resistance follows the same four mechanisms as bacterial resistance**: target mutation (M2 changes, neuraminidase mutations), reduced activation (thymidine kinase deletion in HSV), efflux, and — for viruses — simply an enormous mutation supply rate from error-prone replication. Combination therapy suppresses it.

## Vaccines: training before the encounter

A vaccine presents an antigen **without disease** so that the adaptive immune system generates memory B and T cells in advance. On real infection, the **secondary response** is faster, stronger, and longer-lasting than the primary one — usually clearing the pathogen before symptoms begin.

| Vaccine type | What is given | Examples |
| --- | --- | --- |
| **Live attenuated** | Weakened replicating virus | MMR, oral polio, varicella, yellow fever |
| **Inactivated (killed)** | Whole virus, non-replicating | Injected polio, rabies, hepatitis A |
| **Subunit / recombinant** | Purified protein or polysaccharide | Hepatitis B (HBsAg), HPV (virus-like particles), pertussis component |
| **Conjugate** | Polysaccharide linked to protein — converts a T-independent response into T-dependent memory | Hib, pneumococcal conjugate |
| **Toxoid** | Inactivated toxin | Tetanus, diphtheria |
| **mRNA / viral vector** | Genetic instructions for an antigen | mRNA COVID-19 vaccines; Ebola viral-vector vaccine |

**Herd immunity** is the population-level payoff: when a sufficient proportion is immune, chains of transmission break and even unvaccinated individuals are partly protected. The threshold depends on how transmissible the disease is — high for measles, lower for influenza — and the concept is developed in [09 — Human Biology](../09-human-biology/) and in [05 — Microbial reproduction and transmission](05-microbial-reproduction-and-transmission.md).

## Medical relevance

**Diagnosis differs by virus type.** Viruses cannot be cultured on agar: you need cell culture (slow, often not attempted), **PCR** amplifying a genome segment (fast, specific, quantitative), or antigen/antibody serology. The window period matters — PCR turns positive before antibodies do, which is why it is used early. HIV diagnosis uses antigen/antibody combination assays with a fourth-generation window of weeks, and RNA testing detects infection before seroconversion.

**Influenza treatment is time-critical and limited.** Oseltamivir must be started within about 48 hours of symptom onset to shorten illness meaningfully; after viral shedding has peaked it offers little. Because NA inhibitors affect release rather than replication, they do not prevent disease if given as prophylaxis late in an exposure.

**HIV is a chronic, controllable disease.** Combination antiretroviral therapy suppresses viral load to undetectable levels — and **undetectable equals untransmittable** — converting what was a uniformly fatal diagnosis into a manageable chronic condition with near-normal life expectancy. The latent reservoir, not drug resistance, is the remaining obstacle to cure.

**Oncogenic viruses link infection to cancer.** HPV → cervical cancer (prevented by vaccination); HBV and HCV → hepatocellular carcinoma; EBV → Burkitt lymphoma and nasopharyngeal carcinoma; HTLV-1 → adult T-cell leukaemia; HPV and EBV → oropharyngeal cancer. Screening programmes (cervical cytology, hepatitis B/C surveillance) are therefore cancer-prevention programmes.

**Viral gastroenteritis is the classic "why no antibiotics" case.** Rotavirus (dsRNA, non-enveloped) and norovirus (ssRNA, non-enveloped) cause self-limiting diarrhoea; the management is rehydration, not antimicrobials. Antibiotics provide no benefit, add *C. difficile* risk, and drive resistance — a point made in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md).

**Infection control follows envelope status.** Alcohol hand rub works well against influenza, HIV, and coronaviruses (enveloped) but poorly against norovirus and rotavirus (non-enveloped) — hence the isolation and chlorine-based cleaning protocols for ward outbreaks of viral gastroenteritis.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Viruses are the smallest bacteria" | They are **not bacteria**. No cell, no ribosomes, no metabolism — they are particles, not organisms with a cell plan. |
| "Antibiotics kill viruses" | Antibiotics target peptidoglycan, 70S ribosomes, folate synthesis, and gyrase. **A virus has none of these.** |
| "All RNA viruses use reverse transcriptase" | Only **Class VI (retroviruses)** do. Other RNA viruses use an **RNA-dependent RNA polymerase**, which is a different enzyme. |
| "(+) and (−) mean the two strands of one genome" | In Baltimore terms, **(+) is the strand that serves as mRNA**; (−) is its complement and must be transcribed before it can be translated. |
| "Lysogenic means the virus is dormant and inactive" | The prophage is **replicating with the host** at every division — it is transcriptionally quiet but genetically active, and it can be induced. |
| "Enveloped viruses are more dangerous because they have a membrane" | The opposite for transmission: the envelope makes them **fragile outside the body**. It is the non-enveloped viruses that persist on surfaces. |
| "A plaque is where the virus grew on the agar" | Viruses do not grow on agar. The plaque is a **clearing in a bacterial lawn** caused by lysis spreading outward from one infectious particle. |
| "Prions have a hidden genome" | None has ever been found. PrP^Sc propagates by **templated misfolding**, not by nucleic acid replication. |
| "Viroids are just tiny viruses" | Viroids have **no capsid and no protein** — they are naked RNA. They infect plants only. |
| "A negative HIV test means no infection" | Antibodies take weeks to appear. **PCR or antigen testing** is required in the window period. |

## Key facts

- A virus is **acellular, metabolically inert, has no ribosomes**, and replicates only inside a host cell — see [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md).
- Virion = **nucleocapsid** (genome + capsid) and, in many viruses, a **host-derived envelope** carrying viral glycoproteins.
- Capsid symmetries: **helical** (TMV, Ebola), **icosahedral** (polio, adenovirus), **complex** (T4 phage, poxvirus).
- **Envelope = host membrane stolen during budding** — the secretory system hijacked; envelope viruses are destroyed by soap and alcohol.
- **Baltimore classes I–VII** sort viruses by genome type and route to mRNA; host cells have **no RNA-dependent RNA polymerase**, so RNA viruses must carry or encode one.
- **Lytic** cycle destroys the host; **lysogenic/latent** cycle maintains the genome with the host and can be **induced** — prophages can carry toxin genes (diphtheria, tetanus).
- Replication steps: **attachment → penetration → uncoating → biosynthesis → assembly → release**.
- **Influenza**: segmented (−)ssRNA; **drift** = point mutations (seasonal), **shift** = reassortment (pandemic); **HA** attaches, **NA** releases; **M2** mediates uncoating.
- **HIV**: **reverse transcriptase → integrase → provirus → latency** in memory CD4⁺ T cells; error-prone RT demands **combination therapy**.
- **Phage plaque assay** quantifies infectivity (PFU) and gave much of molecular biology its founding evidence.
- **Prions** = misfolded protein with no nucleic acid (CJD, BSE); **viroids** = naked circular RNA in plants.
- Antiviral targets: **entry, uncoating (amantadine), RT (NRTIs), integrase, protease, neuraminidase (oseltamivir)** — antibiotics have no target in a virus.

## Practice questions

**1. An antibiotic course is prescribed for a patient with confirmed influenza. It will fail because**

A. Influenza virus has a thick cell wall protecting it
B. The virus lacks a cell wall, 70S ribosome, folate pathway, and independent metabolism — the structures antibacterials target
C. The virus pumps the antibiotic out with efflux pumps
D. Influenza has acquired resistance to all antibiotic classes

**Answer: B**

Explanation: Antibacterials are selective for features bacteria possess and humans lack — peptidoglycan, 70S ribosomes, bacterial folate synthesis, DNA gyrase. A virus has none of them: it is a genome in a protein coat, has no ribosomes of its own, and replicates by borrowing the host's machinery. There is therefore nothing for the drug to bind. Resistance (C, D) is a property of a target that exists but is altered; here the target never existed. A cell wall claim (A) confuses viruses with bacteria.

---

**2. The envelope of an influenza virion is derived from**

A. Synthesised lipid made de novo by the virus
B. Host cell membrane acquired during budding, containing host lipid and viral glycoproteins
C. The bacterial outer membrane
D. Capsid protein cross-linked with cholesterol

**Answer: B**

Explanation: Enveloped viruses bud through host membranes — plasma membrane, ER, or Golgi — so their lipid bilayer is host membrane. Viral glycoproteins (HA and NA in influenza) are inserted into that membrane and processed through the host secretory pathway exactly as host proteins would be. The virus encodes the protein, not the lipid. This is why enveloped viruses are fragile outside the body: removing or disrupting that stolen membrane with soap or alcohol destroys the particle.

---

**3. Antigenic shift in influenza differs from antigenic drift in that it**

A. Results from point mutations in haemagglutinin
B. Occurs gradually over many seasons
C. Involves reassortment of genome segments between two co-infecting strains, producing a novel subtype
D. Affects only neuraminidase

**Answer: C**

Explanation: Influenza's genome is segmented (eight segments). When two different strains infect the same cell, segments can be shuffled during assembly — a progeny virion may carry, for example, an avian HA with human-adapted polymerase genes. The resulting subtype is antigenically novel, so population immunity is absent and a pandemic can follow. Drift is the gradual accumulation of point mutations by an error-prone polymerase, causing ordinary seasonal epidemics. Both affect HA and NA, not NA alone.

---

**4. Which feature of HIV makes a sterilising cure difficult even with sustained antiretroviral therapy?**

A. Its envelope is unusually thick
B. Reverse transcriptase proofreads with high fidelity
C. Integration of a provirus into long-lived memory CD4⁺ T cells creates a latent reservoir that is not targeted by drugs acting on active replication
D. It integrates into human chromosomes only once per infection cycle and is then inert forever

**Answer: C**

Explanation: HIV reverse transcribes its genome and integrase inserts it as a provirus. In many cells the provirus is transcriptionally silent within resting memory CD4⁺ T cells — no viral protein is made, so there is no target for the drugs and no signal for the immune system. Cells persist for years and can reactivate. This reservoir, not failure of the drugs to suppress active replication, is the barrier to cure. B is the opposite of the truth: RT lacks proofreading, which drives mutation and drug resistance.

---

**5. In the lytic cycle of a bacteriophage, the host cell**

A. Survives and carries the prophage through division
B. Is lysed after viral components are assembled, releasing new virions
C. Becomes immune to reinfection without any change
D. Excises the viral genome and expels it

**Answer: B**

Explanation: The lytic cycle uses the host's ribosomes and nucleotides to build new phage particles, then a lysin (endolysin) degrades the peptidoglycan and the cell bursts. Option A describes the lysogenic cycle, where the phage genome integrates as a prophage and is replicated with the chromosome; D describes excision, which precedes induction *into* the lytic cycle rather than ending it. C is a property of lysogenised bacteria, which are often superinfection-immune.

---

**6. Why must a Class V ((−)ssRNA) virus carry an RNA-dependent RNA polymerase inside the virion?**

A. Host cells can translate (−)ssRNA directly
B. The host lacks RNA-dependent RNA polymerase, and the incoming negative-sense genome cannot serve as mRNA
C. It is needed to reverse transcribe the genome into DNA
D. It degrades the host genome

**Answer: B**

Explanation: Ribosomes translate only mRNA, and a negative-sense RNA genome is the complement of mRNA — it cannot be read. Conversion requires an RNA-dependent RNA polymerase, and because human cells have no such enzyme, the virus must supply it in the particle so transcription can begin immediately after uncoating. Option A describes the advantage of (+)ssRNA viruses; C describes reverse transcriptase (retroviruses); D is not a step in viral replication.

---

**7. A turbid plaque on a bacterial lawn most likely indicates**

A. A virulent, obligately lytic phage
B. A temperate phage in which some cells lysogenise and survive within the clearing
C. Contamination with a fungus
D. Resistance mutation in the phage

**Answer: B**

Explanation: Clear plaques come from phages that lyse every infected cell. Turbid (hazy) plaques arise when a proportion of infected cells lysogenise rather than lyse, so cells continue to grow within the zone — the signature of a temperate phage such as λ. This is why plaque morphology is informative rather than merely descriptive. Contamination would appear as colonies rather than as regular clearings in the lawn.

---

**8. Which pair correctly matches an antiviral drug with its target?**

A. Oseltamivir — reverse transcriptase
B. Zidovudine (AZT) — neuraminidase
C. Amantadine — influenza M2 ion channel, blocking uncoating
D. Ritonavir — viral attachment receptor

**Answer: C**

Explanation: Amantadine blocks the M2 proton channel, preventing acidification of the interior and so preventing uncoating (resistance is now widespread, which is why it is rarely used). Oseltamivir inhibits **neuraminidase** and blocks release; AZT is a nucleoside analogue that terminates synthesis by **reverse transcriptase** in HIV; ritonavir is a **protease inhibitor** that blocks polyprotein processing. Matching each drug to its enzyme is a standard examination requirement.

---

**9. Which statement about prions is correct?**

A. They contain a small circular RNA genome
B. They are viruses with an unusually protein-rich capsid
C. They are misfolded proteins that convert normal PrP^C into PrP^Sc, with no nucleic acid, and cause spongiform encephalopathy
D. They are killed by routine alcohol disinfection

**Answer: C**

Explanation: Prions are conformational pathogens: PrP^Sc acts as a template that refolds host PrP^C into more PrP^Sc, accumulating in brain tissue and producing spongiform change, dementia, and ataxia. There has never been a demonstrated nucleic acid, which is what makes them extraordinary — infectivity without a genome (A is the viroid description). They are not viruses (B). They resist routine disinfection, requiring incineration, prolonged autoclaving at 134 °C, or sodium hydroxide (D).

---

**10. A patient asks why an antibiotic will not help their viral sore throat. The best answer is**

A. Antibiotics only work on fungi
B. Antibiotics kill bacteria by targeting structures such as the cell wall and 70S ribosome, which viruses do not have; viruses also replicate using your own cells
C. Antibiotics work but viruses are already immune to them
D. Antibiotics must be given intravenously to work against viruses

**Answer: B**

Explanation: The explanation must identify the target difference: peptidoglycan, 70S ribosomes, folate synthesis, and gyrase are bacterial, not viral, and a virus replicates by commandeering host cells — so poisoning its "physiology" would mean poisoning the patient's own cells. This is why antivirals must hit virus-specific enzymes such as reverse transcriptase, protease, integrase, or neuraminidase. A is false (antibiotics have no useful antifungal action — antifungals are a separate class), C is wrong because viruses are not pre-immune in that sense, and D confuses routes of administration with mechanism.
