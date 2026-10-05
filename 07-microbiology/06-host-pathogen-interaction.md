# Host–Pathogen Interaction

## Why it matters

Every chapter so far has described the microbe: its wall, its genome, its life cycle, its transmission. This chapter describes the **relationship** — what the microbe does to you, what you do to it, and what happens when the second half fails. The central idea to carry forward is that **virulence is not a fixed property of an organism.** *Staphylococcus aureus* lives on the skin of roughly a third of healthy people without causing anything, and the same species can cause a fatal sepsis when it reaches the bloodstream through a cannula. The organism is identical; the context is not. Infection is an event that occurs when a sufficiently virulent microbe, at a sufficient dose, reaches a susceptible tissue in a host whose defences cannot contain it — and disease begins only when the microbe's actions *or the body's response to them* start to damage tissue.

Two more organising ideas run through the chapter. First, **the immune system is a set of specific obstacles, and every virulence factor is an answer to one of them.** A capsule answers phagocytosis; a protease answers complement; antigenic variation answers antibody memory. Learn the defence and the counter-defence follows logically — which is far more reliable than memorising lists of factors. Second, much of what looks like infection is actually **the host's own response**: fever, inflammation, shock, and coagulopathy are largely cytokine-driven. This is why killing bacteria too quickly can transiently worsen a patient, and why much of critical-care medicine is supporting the response rather than attacking the microbe.

Finally, this chapter fixes the vocabulary that infection control, microbiology reports, and epidemiology all use — colonisation versus infection, contamination versus disease, sterilisation versus disinfection, MIC versus MBC. These distinctions are not pedantic: they determine which surfaces need autoclaving, which drugs are bactericidal, and whether a positive culture means disease.

## Normal flora: the body is not empty

Before any pathogen arrives, you are already colonised. The **normal flora** (commensal microbiota) occupies every surface exposed to the environment, and in most sites the resident community is a stabilising force rather than a threat.

| Site | Dominant residents | Function or consequence |
| --- | --- | --- |
| **Skin** | *Staphylococcus epidermidis*, *Corynebacterium*, cutaneous propionibacteria, *Malassezia* | Acidic, salty, oily surface restricts growth; coagulase-negative staphylococci colonise catheters and cause device infection |
| **Gut** | *Bacteroides*, *Bifidobacterium*, *Clostridium*, *Lactobacillus*, *E. coli* (a minority) | Ferments fibre → short-chain fatty acids; synthesises vitamin K and biotin; **colonisation resistance** against ingested pathogens |
| **Mouth** | *Streptococcus* species (mutans, sanguinis, mitis), anaerobes posteriorly | Dental plaque is a biofilm; *S. mutans* acid production causes caries; bacteraemia after brushing is routine and usually harmless |
| **Upper respiratory tract** | *Streptococcus pneumoniae*, *Haemophilus*, *Neisseria*, *Corynebacterium* | Nasopharyngeal carriage is normal; disease appears when defences fail or a new strain arrives |
| **Vagina** (post-pubertal) | *Lactobacillus* species | Lactic acid keeps pH ~4; oestrogen-driven glycogen feeds lactobacilli — the reason the flora changes at puberty and with antibiotics |

Three rules prevent most misunderstandings:

1. **Some sites are normally sterile.** Blood, cerebrospinal fluid, urine in the bladder, the lower respiratory tract, and the peritoneal cavity should contain no microbes. Anything recovered from them is significant — a single colony in a properly taken blood culture matters.
2. **The same organism can be commensal or pathogen depending on location.** *E. coli* in the gut is a mutualist; *E. coli* in the blood is a Gram-negative sepsis. *Candida albicans* on mucosa is carriage; in the bloodstream it is candidaemia.
3. **The flora actively defends the space it occupies.** Resident bacteria consume nutrients, occupy adhesion sites, maintain acidic pH, and secrete bacteriocins against newcomers. This **colonisation resistance** is why broad-spectrum antibiotics can cause disease in their own right: wiping out the flora removes the barrier, and the result is *Clostridioides difficile* diarrhoea or candidal overgrowth. The mechanism is covered again in [07 — Beneficial microorganisms](07-beneficial-microorganisms.md).

## Koch's postulates: how "cause" was proved — and where they fail

Robert Koch's postulates (1884) remain the logical template for proving that a microbe causes a disease:

```
1. The organism must be found in EVERY case of the disease
        ↓
2. It must be isolated and grown in PURE CULTURE
        ↓
3. The pure culture must REPRODUCE the disease when
   introduced into a healthy susceptible animal
        ↓
4. The organism must be REISOLATED from that animal
   and be identical to the original
```

The framework is still the reasoning behind outbreak investigation, and its limitations are as instructive as the framework itself:

| Limitation | Example |
| --- | --- |
| **Some pathogens cannot be grown in pure culture** | *Mycobacterium leprae* (obligate intracellular); many viruses require cell culture — hence modified postulates |
| **Carriers exist without disease** | Typhoid Mary (Mary Mallon) harboured *Salmonella* Typhi and transmitted it while healthy — postulate 1 as written is violated |
| **Ethical limits on reproduction** | Deliberately infecting humans with HIV or prions is impossible; molecular versions (sequence present, expressed, consistent) replace animal reproduction |
| **Some diseases are polymicrobial** | Periodontal disease, aspiration pneumonia, diabetic foot infection — no single organism satisfies the chain |
| **The organism may cause disease only after a second event** | *Helicobacter pylori* carriage is near-universal but ulceration requires strain virulence factors plus host factors |

The modern molecular replacement is straightforward: **detect the agent's nucleic acid, show it is present and expressed in every case, and exclude other agents** — which is why PCR has overtaken culture as the first test in many infections.

## Virulence factors

A **virulence factor** is any structure or product that lets a microbe establish, spread, or damage. They fall into three families: things on the surface that defeat immune recognition, enzymes that open tissue, and toxins that damage host cells directly.

### The surface: capsule and the proteins that disguise the cell

| Factor | Produced by | What it does | Consequence |
| --- | --- | --- | --- |
| **Capsule** | *S. pneumoniae*, *N. meningitidis*, *H. influenzae* b, *Klebsiella*, *Cryptococcus* | Polysaccharide layer masks surface antigens and prevents C3b deposition and phagocyte contact | **Anti-phagocytic**; the basis of Griffith's transforming principle and of conjugate vaccines, which raise opsonising antibody against the capsule |
| **Protein A** | *Staphylococcus aureus* | Binds the **Fc region of IgG**, holding antibodies on the surface with their antigen-binding ends pointed away | Opsonisation fails — the phagocyte's Fc receptor has nothing to grip; also interferes with complement |
| **M protein** | *Streptococcus pyogenes* (group A strep) | Surface fibrillar protein; binds **factor H** (a complement regulator) and fibrinogen | C3b on the bacterial surface is degraded → alternative pathway complement is switched off; also anti-phagocytic; molecular mimicry with cardiac myosin contributes to rheumatic fever |
| **C5a peptidase** | *S. pyogenes* | Enzymatically degrades **C5a**, the strongest complement-derived chemotactic signal | Neutrophils are not recruited to the site — the alarm signal is destroyed before it works |
| **Sialylation / factor H recruitment** | *Neisseria*, *Group B streptococcus* | Host sialic acid coat or bound host regulators | Complement is mistaken for "self" and inactivated |
| **Biofilm matrix** | *S. epidermidis*, *P. aeruginosa*, *S. aureus* on devices | Polysaccharide–protein–DNA matrix physically shields cells and slows growth | Phenotypic tolerance to antibiotics and phagocytes; device infection — see [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md) |
| **IgA protease** | *N. gonorrhoeae*, *H. influenzae*, *S. pneumoniae* | Cleaves secretory IgA at mucosal surfaces | The first-line mucosal antibody is destroyed where it is deployed |

The pattern is worth stating explicitly: **antibody and complement are the two main opsonins, and the classic surface virulence factors each neutralise one of them.** Capsule blocks deposition; Protein A blocks Fc usage; M protein blocks C3b through factor H; C5a peptidase blocks recruitment. Learn the opsonisation pathway from [03 — Cellular Processes](../03-cellular-processes/) and each factor becomes a single-step counter-move.

### Enzymes that open tissue and spread infection

| Enzyme | Producer | Action | Clinical logic |
| --- | --- | --- | --- |
| **Coagulase** | *S. aureus* | Clots fibrin around the bacterium | Fibrin shell walls off an abscess, shielding it from antibody and phagocytes; the coagulase test separates *S. aureus* from harmless coagulase-negative staphylococci |
| **Streptokinase / staphylokinase** | *S. pyogenes*, *S. aureus* | Activate plasminogen → plasmin → **dissolve fibrin clots** | The opposite strategy to coagulase: break down the clot to reach fresh tissue; the same enzyme class is used therapeutically as a thrombolytic |
| **Hyaluronidase** | *S. pyogenes*, *Clostridium* spp. | Hydrolyses hyaluronic acid of connective tissue ground substance | Historic "spreading factor" — allows bacteria to move through tissue planes |
| **Collagenase** | *Clostridium perfringens* | Degrades collagen | Tissue destruction in gas gangrene |
| **Lecithinase / phospholipase C** | *C. perfringens* (α-toxin), *Pseudomonas* | Cleaves membrane phospholipids | Cell lysis; the α-toxin is the principal virulence factor of gas gangrene |
| **DNase (protease)** | *S. aureus*, *S. pyogenes* | Degrades extracellular DNA in pus | Pus is thinned, releasing nutrients and reducing viscosity — aids spread |
| **Hemolysins** | *S. aureus* (α-hemolysin), streptolysins | Pore-forming toxins lyse red cells and leukocytes | Iron release from erythrocytes and killing of phagocytes at the site |
| **Urease** | *Proteus*, *H. pylori*, *Cryptococcus* | Urea → ammonia (alkaline) | *Proteus*: staghorn calculi in alkaline urine; *H. pylori*: survives gastric acid locally |

## Toxins: the two kinds

**Toxigenicity** — the ability to produce toxin — is distinct from **invasiveness**, the ability to grow in tissue. Some of the most lethal infections are barely invasive: *Corynebacterium diphtheriae* stays in the throat and sends a toxin to the heart; *Clostridium tetani* stays in a dirty wound and sends a toxin to the spinal cord.

### Exotoxins

Exotoxins are **secreted proteins**, mostly from Gram-positive bacteria (though *E. coli*, *Vibrio*, and *Shigella* are important Gram-negative exceptions). They are specific, potent, and heat-labile — and they come in three mechanistic classes:

| Class | Mechanism | Examples |
| --- | --- | --- |
| **A–B (two-subunit) toxins** | B subunit binds a specific receptor → A subunit enters and enzymatically modifies one host target | **Cholera toxin**: ADP-ribosylates Gsα → adenylyl cyclase permanently on → cAMP rises → CFTR chloride secretion → water floods the gut. **Diphtheria toxin**: ADP-ribosylates **EF-2** (diphthamide) → all protein synthesis stops. **Pertussis toxin**, **Shiga toxin**, **E. coli heat-labile toxin** |
| **Pore-forming / membrane-disrupting toxins** | Insert into the host membrane and lyse the cell | **α-toxin** of *S. aureus* (heptameric pore), streptolysins, perfringolysin |
| **Superantigens** | Bridge **MHC class II** on an antigen-presenting cell and the **Vβ region of the TCR** → 2–20% of all T cells activated at once, independent of antigen | **TSST-1** (toxic shock syndrome toxin-1), staphylococcal enterotoxins → TNF-α, IL-1, IL-2 storm → fever, rash, hypotension, shock |

Neurotoxins deserve their own line because they are the purest example of a single-target mechanism: **tetanospasmin** cleaves synaptobrevin in inhibitory (glycinergic/GABAergic) neurons at the spinal cord → loss of inhibition → spastic paralysis; **botulinum toxin** cleaves SNARE proteins (synaptobrevin, SNAP-25, syntaxin) at the neuromuscular junction → acetylcholine is not released → flaccid paralysis. Same family of targets, opposite clinical result — and both are among the most potent substances known, which is why micro-doses of botulinum toxin are used therapeutically.

### Endotoxin

Endotoxin is not secreted at all. It is **lipid A**, the inner portion of lipopolysaccharide, which is an integral component of the **Gram-negative outer membrane** described in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md). It is released when cells lyse — and also in outer membrane vesicles from living cells.

Its action is indirect: lipid A binds **TLR4** on macrophages → NF-κB → TNF-α, IL-1, IL-6 → the systemic inflammatory cascade. There is no receptor-mediated entry and no enzymatic "A chain"; the molecule simply is the trigger. This has three practical consequences: endotoxin cannot be neutralised by an antibody against a secreted protein in the usual way, it cannot be removed by dialysis of the toxin alone, and **bactericidal antibiotics that lyse Gram-negative cells can release a burst of it**, transiently worsening a septic patient.

### Exotoxin vs endotoxin — the comparison that must be automatic

| Property | Exotoxin | Endotoxin (Lipid A) |
| --- | --- | --- |
| **Chemical nature** | Protein | Lipid (part of LPS) |
| **Source** | Secreted by living cell (mostly Gram-positive) | Structural component of **Gram-negative** outer membrane; released on lysis |
| **Heat stability** | **Labile** — destroyed at 60–80 °C | **Stable** — survives 100 °C for an hour |
| **Potency** | Extremely high (µg quantities lethal) | Low — requires large amounts |
| **Action** | Specific enzymatic or receptor-mediated effects; disease specific to toxin | General: fever, inflammation, hypotension, DIC, shock — the same picture regardless of species |
| **Fever** | Not directly pyrogenic (except superantigens) | **Pyrogenic** — via cytokine release |
| **Toxoid formation** | **Yes** — formalin detoxification → vaccine (tetanus, diphtheria) | **No** |
| **Neutralising antibody** | Effective | Ineffective in practice |
| **Typical diseases** | Diphtheria, tetanus, botulism, cholera, food poisoning, toxic shock | Gram-negative sepsis, meningococcaemia (with other factors), fever after transfusion or infusion of contaminated fluid |

## Immune evasion: how pathogens survive the defence

The innate and adaptive defences are covered properly in the immune chapters of a later section; what matters here is the **counter-move each pathogen has evolved**, because these are the answers that appear in exam questions and in clinical failure.

| Defence | Counter-move | Example |
| --- | --- | --- |
| **Antibody recognition** | Change the antigen before antibody appears | **Antigenic variation**: *Trypanosoma brucei* switches **VSG** coats sequentially; influenza **drift and shift**; *Neisseria* pilin variation |
| **Phagocytosis** | Prevent ingestion or survive it | Capsule, M protein, Protein A (above); **leukocidins** (PVL) kill neutrophils |
| **Phagosome → lysosome fusion** | Block the phagosome's maturation | ***Mycobacterium tuberculosis*** prevents acidification and fusion — the bacillus survives inside macrophages, which is why cell-mediated immunity (granuloma formation) is required |
| **Escape the vacuole** | Break out into the cytoplasm and use host actin | ***Listeria monocytogenes***: listeriolysin O lyses the phagosome; ActA hijacks actin to rocket into neighbouring cells, avoiding antibody entirely |
| **Oxidative burst** | Neutralise reactive oxygen species | Catalase and superoxide dismutase of *S. aureus*; catalase-peroxidase of *M. tuberculosis* |
| **Complement** | Recruit host regulators or destroy fragments | M protein binds factor H; C5a peptidase destroys C5a; sialic acid coat |
| **Intracellular hiding place** | Live where antibodies cannot reach | *M. tuberculosis*, *Listeria*, *Toxoplasma* (parasitophorous vacuole), *Plasmodium* (inside RBCs — no MHC at all, see [04 — Fungi and protozoa](04-fungi-and-protozoa.md)) |
| **Biofilm** | Matrix-protected, slow-growing, persister state | Device infection and chronic *P. aeruginosa* in cystic fibrosis |
| **Immune recognition of "foreign" at all** | Be made of self-like material | **Prions** — pure host-conformation protein; no inflammation, no vaccine, no antibody response (see [03 — Viruses](03-viruses.md)) |
| **Latency** | Hide the genome, express little or nothing | Herpesviruses in ganglia, HIV provirus in resting CD4⁺ T cells — no antigen to attack between reactivations |

The therapeutic consequence: **intracellular pathogens are not cured by antibody.** Drugs must enter host cells, and clearance requires T cells and macrophage activation — which is why tuberculosis therapy runs for six months and why AIDS patients reactivate infections that were previously contained.

## Naming the illness: infection terminology

Precision here prevents real errors in reports and questions:

| Term | Meaning |
| --- | --- |
| **Colonisation** | Microbe present and multiplying **without tissue damage or host response** — normal flora, or MRSA on a screen swab |
| **Infection** | Microbe present **and causing disease** — invasion, multiplication, and a host response |
| **Contamination** | Microbes present on a specimen or surface that should not be there — a laboratory artefact, not a patient state |
| **Localised / systemic** | Confined to one site vs involving the circulation or multiple organs |
| **Primary infection** | First infection in a previously healthy person |
| **Secondary (opportunistic) infection** | Infection arising when defences are impaired or flora is disturbed — the AIDS-defining opportunistic infections, or thrush after antibiotics |
| **Focal / metastatic / disseminated** | Single site → spread to a second site → multiple sites throughout the body |
| **Acute / chronic** | Rapid onset, short course, strong response vs prolonged, low-grade, often relapsing |
| **Bacteraemia / septicaemia** | Bacteria in the blood (may be transient and harmless, as after brushing teeth) vs sustained infection with clinical signs |
| **Sepsis** | Infection provoking a **systemic inflammatory response with organ dysfunction** |
| **Carrier state** | Shedding without symptoms — healthy carrier (convalescent or chronic, e.g. *Salmonella* Typhi) — the reservoir link of the chain in [05 — Microbial reproduction and transmission](05-microbial-reproduction-and-transmission.md) |

## Sepsis: when the response becomes the disease

Sepsis is the clearest demonstration that the host response can be more dangerous than the microbe.

```
INFECTION (often Gram-negative lysis, but any severe infection)
        ↓  lipid A / wall fragments / exotoxins activate TLRs on macrophages
NF-κB → TNF-α, IL-1, IL-6 released into the circulation
        ↓
FEVER (hypothalamic reset), ACUTE-PHASE RESPONSE (liver: CRP, fibrinogen)
        ↓
VASODILATION + CAPILLARY LEAK  → hypotension, tissue oedema
        ↓
ENDOTHELIAL ACTIVATION → coagulation cascade unopposed
        ↓
DISSEMINATED INTRAVASCULAR COAGULATION (DIC):
   microclots consume platelets and clotting factors
        ↓
   paradoxical BLEEDING + organ microinfarction
        ↓
CIRCULATORY SHOCK → multi-organ failure → death if untreated
```

Two points are repeatedly examined. First, **the fever of sepsis is cytokine-driven, not caused by the organism directly** — which is why sterile inflammation (burns, pancreatitis) can produce an identical picture, and why cultures can be negative in a septic patient already on antibiotics. Second, **temporary worsening after starting antibiotics** in Gram-negative sepsis is explained by the lysis of cells releasing lipid A in bulk; this is a reason to support the circulation concurrently, not to stop therapy. Sepsis is treated by **source control** (drain the abscess, remove the catheter), **fluid resuscitation**, and **appropriate antimicrobials** — there is no licensed neutralising drug for endotoxin.

## Killing microbes: sterilisation, disinfection, antisepsis

This vocabulary was deferred from [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md), because it only becomes meaningful once you know why spores resist everything.

| Term | Definition | Target |
| --- | --- | --- |
| **Decontamination** | Removal/reduction of microbes to a safe level — the umbrella term | — |
| **Sterilisation** | **Destruction of ALL forms of microbial life, including endospores** | Everything — surgical instruments, culture media, implants |
| **Disinfection** | Reduction of microbial numbers on **inanimate objects** to safe levels — spores may survive | Surfaces, equipment |
| **Antisepsis** | Disinfection **on living tissue** | Skin, mucous membranes |
| **Sanitisation** | Reducing counts to public-health standards | Food preparation surfaces, utensils |
| **Pasteurisation** | Mild heat killing vegetative pathogens and spoilage organisms in food/drink | Milk, juice — **not sterile** |
| **Asepsis** | Technique preventing microbes reaching a site — the sterile field, hand hygiene, gloving | Practice, not a chemical |

### Physical methods

| Method | Conditions | What it does | Notes |
| --- | --- | --- | --- |
| **Moist heat — autoclave** | **121 °C, 15 psi, 15–20 min** | Denatures protein and nucleic acid; **kills spores** | The reference sterilisation method; biological indicator *Geobacillus stearothermophilus* spores validate each cycle |
| **Moist heat — boiling** | 100 °C, 10–30 min | Kills vegetative cells and most viruses | **Does not reliably kill spores** — hence not sterilisation |
| **Pasteurisation** | 72 °C for 15 s (HTST), or 63 °C for 30 min | Kills vegetative pathogens (*Mycobacterium*, *Salmonella*, brucellae) | Milk keeps its flavour because spores and thermoduric organisms survive |
| **Dry heat — hot-air oven** | 160–170 °C for 2 h | Oxidation; sterilises glassware, metal, powders | Slower than moist heat at lower temperature |
| **Dry heat — flaming/incineration** | >800 °C | Instant destruction | Inoculation loops; also how clinical waste and carcasses are disposed of |
| **Radiation — UV** | ~254 nm | Forms **thymine dimers** → blocks replication | **Surface and air only — no penetration**; a UV-treated room is not a sterilised instrument |
| **Radiation — ionising (gamma, electron beam)** | — | Ionisation → DNA breakage | Sterilises through sealed packaging: syringes, sutures, implants, single-use equipment |
| **Filtration** | **0.22 µm** membrane; HEPA filters for air | Removes bacteria without heat | Heat-labile media, antibiotics, vaccines; **viruses and mycoplasma need smaller pores** (0.1 µm or smaller) |
| **Cold** | Refrigeration 4 °C; freezing −20/−70 °C | **Bacteriostatic** — slows growth, does not kill | Storage and preservation only; repeated freezing damages cells but is not sterilisation |

### Chemical methods

| Agent | Class | Use | Limitations |
| --- | --- | --- | --- |
| **Ethanol / isopropanol (60–80%)** | Alcohol | Hand rub, skin, small surfaces | Protein denaturation and membrane dissolution; **no sporicidal action**, evaporates, flammable |
| **Chlorhexidine** | Biguanide | Skin preparation, mucosal wash | Persistent activity on skin; **not sporicidal**, poor against some Gram-negatives and non-enveloped viruses |
| **Povidone–iodine** | Iodine | Skin, pre-operative scrub | Broad, slow; inactivated by organic matter |
| **Hypochlorite (bleach)** | Oxidising | Spill decontamination, *C. difficile* ward cleaning, water treatment | Sporicidal at adequate concentration and contact time; corrosive, inactivated by organic load |
| **Hydrogen peroxide / peracetic acid** | Oxidising | Surface decontamination, endoscope reprocessing | Sporicidal; peracetic acid used for instrument immersion |
| **Glutaraldehyde / ortho-phthalaldehyde** | Aldehyde | High-level disinfection of endoscopes | Sporicidal with prolonged exposure; irritant, requires activation and rinse |
| **Ethylene oxide** | Alkylating gas | **Sterilisation of heat-sensitive equipment** — plastics, electronics, catheters | Gas, long cycle, toxic and carcinogenic — requires aeration |
| **Quaternary ammonium compounds** | Cationic surfactant | Low-level disinfection of floors, furniture | **Bacteriostatic only**; ineffective against *Mycobacterium*, spores, and non-enveloped viruses |
| **Formaldehyde** | Alkylating | Specimen preservation, vaccine inactivation (historical) | Too toxic for live tissue |

**What decides whether anything is actually sterile** is a matter of four variables: **the organism and its spore burden**, **concentration or temperature**, **contact time**, and **organic load** (which shields microbes and neutralises chemicals). That is why a surface wiped with disinfectant for one second is not disinfected, why instruments soaked in blood-stained solution fail, and why **endospores are the benchmark** — if a process kills *Bacillus* and *Geobacillus* spores, it has killed everything.

## Antimicrobial susceptibility: MIC, MBC, and the disc diffusion test

Laboratories report susceptibility in three related quantities:

- **MIC (minimum inhibitory concentration)** — the **lowest concentration of drug that prevents visible growth** of the organism. It measures *inhibition*, not killing.
- **MBC (minimum bactericidal concentration)** — the lowest concentration that **kills ≥99.9%** of the inoculum.
- **MBC:MIC ratio** — a rough guide to behaviour: a low ratio (commonly ≤4) suggests the drug is bactericidal against that organism; a high ratio suggests bacteriostatic action.

**Bacteriostatic vs bactericidal is not an absolute property of a drug** — it depends on the organism, the drug concentration, and the site. The same agent can be static at low concentration and cidal at high concentration, which is why dosing regimens aim to keep concentrations above the MIC (or above the MBC for endocarditis and other deep infections) for as much of the dosing interval as possible.

Two laboratory methods dominate:

| Method | How it works | Output |
| --- | --- | --- |
| **Kirby–Bauer disc diffusion** | Paper disc impregnated with a fixed drug dose is placed on a lawn of the organism; drug diffuses outward forming a concentration gradient | **Zone diameter in mm**, interpreted against **breakpoints** specific to drug and organism: *S* (susceptible), *I* (intermediate), *R* (resistant) |
| **Broth microdilution / gradient strip (E-test)** | Drug concentrations prepared in a series of wells, or a strip with a gradient on agar | Direct **MIC value** in µg/mL — quantitative and comparable over time |

**Selective toxicity** — the principle that a drug must harm the microbe and not the patient — underlies every target in [01 — Bacterial structure and physiology](01-bacterial-structure-and-physiology.md): peptidoglycan, 70S ribosomes, folate synthesis, and bacterial gyrase are all absent or structurally different in human cells. The same reasoning explains the *limits* of antifungal and antiprotozoal therapy, where the overlap with human machinery is far greater ([04 — Fungi and protozoa](04-fungi-and-protozoa.md)).

## Medical relevance

**Hand hygiene is the single most effective infection-control measure.** Every link of the chain of infection in [05 — Microbial reproduction and transmission](05-microbial-reproduction-and-transmission.md) can be broken, and hands are the link that moves flora between patients. Alcohol hand rub is fast and effective against vegetative bacteria and enveloped viruses but **does not clear spores** — soap, water, and gloved precautions are required for *C. difficile*, which is precisely why ward outbreaks follow antibiotic prescribing rather than poor hand technique alone.

**Sterilisation policy follows the spore.** Instruments that enter tissue are autoclaved (121 °C, 15 psi, 15–20 min) or, if heat-sensitive, ethylene-oxide sterilised; skin is disinfected, not sterilised; floors and furniture are cleaned with low- to intermediate-level disinfectants; single-use items are incinerated. Confusing these categories is how contaminated reusable devices survive their "disinfection" cycle and cause outbreaks.

**Empirical therapy is written from Gram reaction and source, then de-escalated.** A Gram stain from cerebrospinal fluid changes an antibiotic prescription within minutes; culture and MIC values then narrow it. Sepsis is treated as a medical emergency: cultures first if it does not delay treatment, then broad-spectrum antimicrobials, fluids, and source control — with the knowledge that lysis of Gram-negative organisms may release endotoxin.

**Toxoid vaccines exist because exotoxins are proteins that can be detoxified without losing their shape.** Tetanus and diphtheria immunity is antitoxin immunity: the vaccine trains antibody against a formalin-inactivated toxin that can no longer cause disease but still binds neutralising antibody. Conversely, **endotoxin cannot be made into a toxoid** — hence no comparable vaccine, and why Gram-negative sepsis is managed supportively.

**Disrupting the normal flora is itself a prescription risk.** Broad-spectrum antibiotics reduce colonisation resistance and select for resistant organisms; *C. difficile* toxin-mediated disease follows, and mucosal candidiasis appears when bacterial competitors disappear. Prophylactic antibiotics are therefore chosen for spectrum and duration deliberately, not by default.

**Diagnostics depend on knowing what is sterile.** A positive blood culture, pus from a closed abscess, or any growth from cerebrospinal fluid is disease until proven otherwise; a swab of a chronic wound or skin surface frequently shows colonisation that will not respond to antibiotics. Interpreting a laboratory report correctly is mostly knowing which body sites should have no growth at all.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Colonisation means infection" | **Colonisation is presence without disease or tissue invasion.** Infection requires multiplication plus damage or a host response. MRSA on a screen swab is colonisation; MRSA in a wound is infection. |
| "Contamination is the same as colonisation" | Contamination is a **specimen or surface** problem (the sample was mishandled); colonisation is a **patient** state. |
| "The organism itself causes all the signs of sepsis" | Fever, hypotension, and coagulopathy are largely **cytokine-mediated host responses** (TNF-α, IL-1, IL-6). Sterile insults can mimic sepsis exactly. |
| "Bactericidal and bacteriostatic are fixed properties of a drug" | The distinction depends on **concentration, organism, and site**. A static drug at low concentration can kill at high concentration — which is why dosing matters. |
| "MIC is the concentration that kills the bacteria" | **MIC inhibits; MBC kills.** The two numbers are reported separately for that reason. |
| "Sterilisation and disinfection are interchangeable" | Sterilisation **must destroy spores**; disinfection may leave spores alive. Only sterilisation is acceptable for instruments entering tissue. |
| "Antiseptics and disinfectants are the same chemical used differently" | **Antiseptics are formulated for living tissue** (chlorhexidine, povidone–iodine, dilute alcohol); many disinfectants (hypochlorite, glutaraldehyde, quats) are too toxic for skin. |
| "Alcohol kills everything, including spores" | Alcohol is an excellent **vegetative** killer and the basis of hand rubs, but it is **not sporicidal** — hence bleach and autoclaves for *C. difficile*. |
| "Exotoxin and endotoxin differ only in which bacterium makes them" | They differ in chemistry, heat stability, potency, mechanism, and treatability: **protein vs lipid, labile vs stable, specific vs systemic, toxoidable vs not.** |
| "Antibiotics are always the right treatment for infection" | Toxin-mediated disease may need **antitoxin or toxoid-preventive immunity**; intracellular pathogens need cell-mediated immunity plus drugs that penetrate cells; device-associated biofilm infection usually needs **device removal**. |
| "Normal flora are harmless passengers" | They are protective — **colonisation resistance**, vitamin synthesis, immune training — and they become pathogenic only when displaced (gut → blood, mouth → valve) or suppressed (post-antibiotic overgrowth). |
| "UV light sterilises instruments" | UV **does not penetrate**; it decontaminates air and surfaces by making thymine dimers. Instruments require moist heat, gas, or ionising radiation. |
| "A fever means a bacterial infection" | Fever is a **cytokine-reset of the hypothalamus** — viral, fungal, parasitic, autoimmune, and sterile causes all produce it. |

## Key facts

- **Virulence is contextual**: the same organism is commensal at one site and pathogenic at another; infection requires the right microbe, dose, route, and a susceptible host.
- **Normal flora provide colonisation resistance**; broad-spectrum antibiotics remove it, causing *C. difficile* and candidiasis. Blood, CSF, urine, and lower respiratory tract are **normally sterile**.
- **Koch's postulates** define causation and fail for carriers, unculturable organisms, polymicrobial disease, and unethical reproduction — PCR-based molecular criteria have largely replaced them.
- Anti-phagocytic and anti-opsonin factors: **capsule** (blocks C3b), **Protein A** (*S. aureus*, binds IgG Fc), **M protein** (group A strep, binds factor H), **C5a peptidase** (destroys the chemotactic signal).
- Tissue-degrading enzymes: **coagulase** (walls off abscess), **kinases** (dissolve fibrin), **hyaluronidase and collagenase** (spread), **DNase** (thins pus).
- **Exotoxins** are secreted proteins — A–B toxins (cholera, diphtheria), pore-formers, superantigens (TSST-1), and neurotoxins (tetanus, botulinum) — heat-labile and **toxoidable**.
- **Endotoxin is lipid A** of the Gram-negative outer membrane: heat-stable, released on lysis, acts via TLR4 → TNF/IL-1/IL-6 → fever, DIC, shock; **cannot be made into a toxoid**, and lyse-inducing antibiotics can transiently worsen sepsis.
- Immune evasion maps onto immune defence: **antigenic variation** vs antibody, **phagosome blockade** (*M. tuberculosis*), **vacuole escape** (*Listeria*), **intracellular niches** (RBC, macrophage), **biofilm**, **latency**, and **prions** (not recognised as foreign at all).
- **Sepsis is the host response becoming the disease**: cytokines → vasodilation, capillary leak, DIC, shock; treatment is source control, fluids, and antimicrobials.
- **Sterilisation kills spores; disinfection does not necessarily; antisepsis is disinfection on living tissue.** The autoclave reference is **121 °C, 15 psi, 15–20 min**; UV does not penetrate; filtration (0.22 µm) is for heat-labile fluids.
- **MIC inhibits, MBC kills**; disc diffusion reports zones against breakpoints; both feed the choice between empirical and directed therapy.
- **Selectivity is the whole game**: targets the host lacks (cell wall, 70S ribosome, folate pathway, bacterial gyrase) — the principle that carries through every antimicrobial chapter in this section.

## Practice questions

**1. Protein A on *Staphylococcus aureus* resists phagocytosis primarily because it**

A. Prevents C3b from being deposited on the bacterial surface
B. Binds the Fc region of IgG so that antibodies cannot opsonise effectively
C. Digests the chemotactic fragment C5a
D. Forms a polysaccharide capsule around the cell

**Answer: B**

Explanation: Protein A anchors the **Fc end** of IgG to the staphylococcal surface, leaving the antigen-binding sites pointing outward — so the antibody coats the bacterium in the wrong orientation and phagocyte Fc receptors cannot engage it. Option A describes the capsule and M protein–factor H mechanism; C is the action of the streptococcal C5a peptidase; D describes the capsule itself, which is a different virulence factor with the same endpoint.

---

**2. Which statement correctly distinguishes exotoxin from endotoxin?**

A. Exotoxins are lipid components of the Gram-negative cell wall released on lysis
B. Endotoxins are secreted proteins that can be converted to toxoids
C. Exotoxins are secreted proteins, heat-labile and toxoidable; endotoxin is lipid A, heat-stable, and released when Gram-negative cells lyse
D. Endotoxin causes disease only in the gut, exotoxin only in the blood

**Answer: C**

Explanation: The two classes differ in chemistry, physical stability, and immunological handling — protein vs lipid, labile vs stable, toxoidable vs not — and this table is the fastest way to answer any toxin question. A and B invert the definitions; D is false because endotoxin acts systemically wherever Gram-negative bacteraemia occurs, while exotoxin diseases include purely gastrointestinal ones such as cholera.

---

**3. A patient develops fever, hypotension, and a rash 12 hours after a tampon is removed. The toxin involved is most likely acting by**

A. ADP-ribosylating elongation factor 2
B. Forming pores in the host cell membrane
C. Bridging MHC class II and the T-cell receptor Vβ region, causing polyclonal T-cell activation
D. Inhibiting the release of inhibitory neurotransmitters in the spinal cord

**Answer: C**

Explanation: Toxic shock syndrome is caused by **TSST-1**, a **superantigen** that cross-links MHC II on antigen-presenting cells with the Vβ portion of the TCR — activating up to 20% of T cells at once and producing a TNF-α/IL-1 storm that explains fever, rash, and shock. A is diphtheria toxin; B describes α-hemolysin and streptolysins; D describes tetanospasmin, which causes spastic rather than shock physiology.

---

**4. *Mycobacterium tuberculosis* survives inside macrophages mainly because it**

A. Produces a polysaccharide capsule that prevents contact with the cell
B. Prevents the phagosome from acidifying and fusing with the lysosome
C. Is too large to be phagocytosed
D. Secreted IgA protease destroys incoming antibody

**Answer: B**

Explanation: The tubercle bacillus blocks phagosome maturation — inhibiting acidification and phagosome–lysosome fusion — so it persists within the very cell sent to kill it. That intracellular niche is why clearance requires **cell-mediated immunity and granuloma formation** rather than antibody, and why therapy is prolonged. A is the mechanism of pneumococcal and meningococcal disease; C is wrong (the bacillus is readily phagocytosed); D is not a mycobacterial mechanism.

---

**5. The correct conditions for sterilisation with a steam autoclave are**

A. 63 °C for 30 minutes
B. 100 °C for 10 minutes
C. 121 °C at 15 psi for 15–20 minutes
D. UV irradiation at 254 nm for 30 minutes

**Answer: C**

Explanation: Moist heat under pressure at **121 °C, 15 psi, 15–20 minutes** penetrates and denatures protein throughout, including in **endospores**, which is the defining requirement of sterilisation. A is batch pasteurisation and kills only vegetative organisms; B is boiling, which does not reliably kill spores; D is UV, which has no penetration and decontaminates only exposed surfaces.

---

**6. The minimum inhibitory concentration (MIC) of an antibiotic is defined as the lowest concentration that**

A. Kills 99.9% of the inoculum
B. Prevents visible growth of the organism
C. Achieves sterilisation of the blood in vivo
D. Produces a zone of inhibition of 18 mm on a disc diffusion plate

**Answer: B**

Explanation: MIC = **inhibition**, measured as the lowest drug concentration with no visible growth in broth or on a gradient strip. The concentration that kills 99.9% is the **MBC** (A); C is a clinical outcome, not an in-vitro measurement; D confuses the disc diffusion readout, which is a zone diameter interpreted against breakpoints, with a concentration value.

---

**7. Which agent is correctly matched with its clinical use?**

A. Chlorhexidine — sterilisation of surgical instruments
B. 70% alcohol — hand antisepsis, but not reliable against spores
C. Quaternary ammonium compounds — sporicidal disinfection of blood spills
D. Boiling water — sterilisation of culture media

**Answer: B**

Explanation: Alcohol at 60–80% denatures proteins and disrupts membranes rapidly, making it ideal for hand rubs — yet it **does not kill endospores**, so spore-forming organisms such as *C. difficile* require soap, water, chlorine, or heat. Chlorhexidine is an antiseptic for living tissue, not a sterilant (A); quats are only bacteriostatic and ineffective against mycobacteria and spores (C); boiling does not achieve sterilisation (D).

---

**8. Tetanus and diphtheria vaccines contain toxoids because**

A. Toxoids are live attenuated bacteria that colonise without disease
B. The exotoxin can be chemically detoxified while preserving the antigenic shape that neutralising antibody recognises
C. Endotoxin cannot be neutralised by any vaccine
D. The organisms cannot be grown in culture

**Answer: B**

Explanation: Formalin treatment destroys the toxic activity of a **protein** exotoxin without unfolding its antigenic surface, so antibody raised against the toxoid still binds and neutralises the real toxin. Tetanus and diphtheria immunity is therefore **antitoxin** immunity, not anti-bacterial immunity. A describes live vaccines; C confuses endotoxin with the antigen used here — endotoxin in fact cannot be toxoided, which is why no analogous vaccine exists; D is false.

---

**9. A patient on broad-spectrum antibiotics develops profuse watery diarrhoea with pseudomembranes on colonoscopy. The mechanism is**

A. Direct invasion of the colonic mucosa by the antibiotic residue
B. Loss of colonisation resistance allowing *Clostridioides difficile* to expand and release toxin
C. Overgrowth of *Lactobacillus* producing too much lactic acid
D. Endotoxin released by the antibiotic's bactericidal action

**Answer: B**

Explanation: Normal gut flora normally excludes incoming organisms by competing for nutrients and adhesion sites and by producing bacteriocins — **colonisation resistance**. Broad-spectrum antibiotics suppress the flora, and *C. difficile* (spore-forming, intrinsically resistant) then proliferates and produces toxins A and B, causing pseudomembranous colitis. A is nonsensical (antibiotics are not invaders); C would be protective rather than pathogenic; D describes the mechanism of worsening in Gram-negative sepsis, not diarrhoea after antibiotics.

---

**10. The transient clinical worsening sometimes seen shortly after starting a bactericidal antibiotic in Gram-negative sepsis is best explained by**

A. Development of an allergic reaction to the drug
B. Release of lipid A endotoxin as bacterial cells lyse, amplifying the cytokine response
C. The antibiotic acting as a pyrogen itself
D. Conversion of the organism to a resistant phenotype within hours

**Answer: B**

Explanation: Lipid A is a structural component of the outer membrane, so rapid lysis releases it in bulk → TLR4 → TNF-α, IL-1, IL-6 surge, which can transiently worsen fever, hypotension, and coagulopathy. This is a reason to couple antimicrobials with fluid resuscitation and source control, not to withhold or stop therapy. A would present with rash or bronchospasm rather than the septic picture; C is not a property of antibiotics at therapeutic dose; D would not occur within the first hours of treatment in this pattern.
