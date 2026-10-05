# Bacterial Structure and Physiology

## Why it matters

Bacteria are the pathogens you will meet first, most often, and most treatably — and almost every decision made at the bedside about them rests on two facts introduced here: **what the cell wall is made of**, and **how the organism grows**. The Gram stain that comes back from the laboratory directs antibiotic choice within hours; the growth phase of a culture explains why a stationary-phase bacterium tolerates drugs that kill its exponential-phase relatives; the presence of a plasmid explains why resistance appears in a ward overnight rather than over decades.

This chapter is also where microbiology stops being a catalogue. Each structure below is a solution to a problem — osmotic pressure, phagocytosis, desiccation, predation, antibiotic attack — and the solutions are what you are examined on. A capsule is not a definition to memorise; it is a defence against a macrophage. A β-lactam ring is not a chemical curiosity; it is a decoy that tricks an enzyme into destroying itself. Learn the problem and the structure follows.

Finally, bacterial genetics belongs in this chapter rather than in a later one because **antibiotic resistance is a genetic phenomenon with a structural consequence**. The three mechanisms of gene transfer — transformation, transduction, conjugation — are how a resistance gene that arises in one organism reaches another species by the following week. Understanding them is the difference between knowing that resistance spreads and knowing *how fast* and *by what route*.

## The cell wall: peptidoglycan

Everything the wall does follows from its chemistry. Peptidoglycan (also called murein) is a single enormous molecule wrapping the entire cell: a mesh of sugars cross-linked by short peptides.

```
   ──NAG──NAM──NAG──NAM──NAG──NAM──     glycan strands (β-1,4 linked)
        │      │      │
        │      │      │                    stem peptides hang off NAM
        Peptide cross-links (transpeptidation)
        │      │
   ──NAM──NAG──NAM──NAG──NAM──NAG──      next glycan strand
```

| Component | Identity | Role |
| --- | --- | --- |
| **NAG** | *N*-acetylglucosamine | Sugar alternating with NAM |
| **NAM** | *N*-acetylmuramic acid | Sugar carrying the stem peptide |
| **Stem peptide** | e.g. L-Lys–D-Ala–D-Ala (*S. aureus*: L-Lys–D-Ala–D-Ala) | Substrate for cross-linking |
| **Cross-link** | Peptide bridge between stem peptides | Converts strands into a rigid mesh |

Three enzymes build it, and each is a drug target:

```
1. GLYCOSYLTRANSFERASE   extends the glycan strands (NAG–NAM backbone)
             ↓
2. TRANSPEPTIDASE (PBP)  joins a stem peptide on one strand to a stem
             ↓           peptide on another — D-Ala–D-Ala + Gly₅ bridge
   THIS STEP IS THE CROSS-LINK. Free D-Ala–D-Ala termini are consumed.
             ↓
3. CARBOXYPEPTIDASE      trims excess peptides, controlling how much
                          cross-linking occurs
```

**The trick that makes β-lactam antibiotics work:** penicillin and its relatives contain a ring shaped like the D-Ala–D-Ala terminus of the stem peptide. The transpeptidase (a **penicillin-binding protein, PBP**) binds the drug instead of the substrate, the ring opens, and a serine in the active site is permanently acylated. The enzyme is inhibited irreversibly — the cell builds wall strands it can never cross-link, and under its own internal osmotic pressure it lyses.

**Lysozyme** — in tears, saliva, and nasal mucus — attacks the other half of the structure, hydrolysing the β-1,4 bond between NAG and NAM. Human cells have no peptidoglycan, which is why this enzyme is harmless to you and lethal to an unencapsulated bacterium. The same absence is why the wall is the basis of antibacterial selectivity; the argument is developed in [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md).

**Vancomycin** binds the stem peptide's D-Ala–D-Ala directly, sterically blocking transpeptidation. Because it binds a substrate rather than the enzyme, it still works against many β-lactam-resistant organisms — until the bacterium alters the target to D-Ala–**D-Lac**, which binds the drug a thousand-fold more weakly.

## Gram-positive vs Gram-negative

The two wall architectures are not degrees of the same design; they are different designs, and the difference determines which antibiotics can reach their target.

| Feature | Gram-positive | Gram-negative |
| --- | --- | --- |
| **Peptidoglycan** | Thick, multi-layered (20–80 nm) | Thin, 1–3 layers (2–7 nm) |
| **Outer membrane** | Absent | **Present** — asymmetric bilayer with LPS outer leaflet |
| **Periplasm** | Limited | Well-defined periplasmic space with enzymes |
| **Teichoic acids** | **Present** (wall and lipoteichoic) | Absent |
| **Porins** | None needed | **Present** in outer membrane |
| **Lipid A (endotoxin)** | Absent | **Present** |
| **Stain after Gram stain** | Purple | Pink |
| **Typical organisms** | *Staphylococcus*, *Streptococcus*, *Bacillus*, *Clostridium*, *Corynebacterium* | *E. coli*, *Salmonella*, *Pseudomonas*, *Neisseria*, *Klebsiella* |
| **Susceptibility to penicillin G, vancomycin, lysozyme** | Generally susceptible | **Intrinsically resistant** — outer membrane blocks them |
| **Endotoxin shock** | No | Yes (LPS) |

### Gram-positive extras

- **Wall teichoic acids** — anionic polymers of glycerol or ribitol phosphate threaded through the peptidoglycan; they carry wall charge, guide cell division, and are attachment sites for phages.
- **Lipoteichoic acids** — the same polymers anchored in the plasma membrane, extending the full thickness of the wall. They mediate adhesion to host tissue and can activate innate immune responses.
- **Surface proteins** — Protein A (*S. aureus*), M protein (*S. pyogenes*), and the C5a peptidase are anchored to the wall and each does a specific job against the immune system; they are covered in [06 — Host–pathogen interaction](06-host-pathogen-interaction.md).

### Gram-negative extras

```
EXTRACELLULAR
═══════════════════════════════════════════════  outer membrane
  O-antigen (LPS)  ── variable, target of antibodies
  core oligosaccharide
  LIPID A  ──────────  endotoxin; anchored in the bilayer
  porin trimers  ─────  aqueous channels; size and charge selective
───────────────────────────────────────────────  outer membrane inner leaflet
  PERIPLASM  ─────────  hydrolytic enzymes, binding proteins, PBPs
───────────────────────────────────────────────  thin peptidoglycan
═══════════════════════════════════════════════  plasma membrane
```

The outer membrane is an **asymmetric bilayer**: phospholipid inner leaflet, lipopolysaccharide outer leaflet. That asymmetry is the whole story. Lipid A — the anchor — is the **endotoxin**; it is not secreted but is released when the cell lyses or blebs, and it triggers macrophages to release TNF-α, IL-1, and IL-6, producing fever, vasodilation, and in severe cases septic shock. A patient with Gram-negative sepsis is responding to a structural component of a wall, not to a toxin the bacterium chose to make.

**Porins** are the compromise that makes an outer membrane survivable: without them nothing hydrophilic could enter. OmpF and OmpC in *E. coli* admit molecules under roughly 600 Da. Crucially, porins are **selective** — the general porins of *Pseudomonas aeruginosa* exclude many β-lactams by charge and size, and one of the classic resistance mechanisms is simply to stop making them.

The outer membrane's practical consequence: **large hydrophobic and charged molecules cannot get in.** Vancomycin (a large glycopeptide), penicillin G, and lysozyme fail against Gram-negative organisms not because their targets are absent but because they never arrive. EDTA, which chelates the Mg²⁺ and Ca²⁺ holding LPS together, disrupts the outer membrane — which is why some protocols pair it with an antibiotic to force entry.

## Surface appendages

| Structure | Composition | Key facts | Function |
| --- | --- | --- | --- |
| **Capsule** | Polysaccharide (some polypeptide — *B. anthracis* poly-D-glutamic acid) | **Not stained by simple stains**; seen by negative staining or capsule reaction; K antigen | Anti-phagocytic; prevents opsonisation; major virulence determinant |
| **Slime layer** | Loosely attached polysaccharide | Diffuse, easily washed off | Biofilm formation, surface adherence |
| **Fimbriae** | Pilin proteins | Short, numerous (hundreds per cell) | **Attachment** to host cells and surfaces — adhesins |
| **Pilus (sex pilus)** | Pilin proteins | Longer, fewer (1–10) | **Conjugation** — DNA transfer between cells |
| **Flagellum** | Flagellin | Long, external filament | Motility |

**Why a capsule matters clinically:** *Streptococcus pneumoniae* without a capsule is cleared by phagocytosis; with one, it causes invasive disease. The classical Griffith experiment — the first demonstration that something could transform one bacterium into another — used virulent encapsulated and avirulent non-encapsulated strains of *S. pneumoniae*.

### The prokaryotic flagellum is a rotary motor

This is one of the clearest structure–function stories in biology, and it is nothing like the eukaryotic flagellum.

```
   FILAMENT (flagellin — hollow, rigid)
        │
   HOOK (universal joint)
        │
   ROD  ── passes through ──
   ┌─────────────────────────────────┐
   │ MS ring / L ring in envelopes   │   basal body
   │ STATOR (MotA/MotB) ──────────── │   fixed to wall, H⁺ channel
   └─────────────────────────────────┘
        │
   SWITCH COMPLEX ← CheY~P (chemotaxis signal decides direction)

   H⁺ flow through stator → torque → filament rotates (~300–1000 rpm)
```

Three points that are reliably examined:

1. **The energy source is the proton motive force, not ATP.** Protons flow through the stator complexes (MotA/MotB) and the torque is generated mechanically. It is a true rotary motor — the only one known in a free-living cell.
2. **Direction is controlled, not the motor.** Chemotaxis proteins phosphorylate CheY; CheY~P binds the switch complex and reverses rotation, producing a tumbling run. Attractants suppress tumbling, so runs become longer.
3. **It is structurally unrelated to the eukaryotic flagellum.** Eukaryotic flagella and cilia are internal **9+2 microtubule** axonemes driven by dynein and ATP-powered sliding — see [05 — Structure and movement](../02-cell-biology/05-structure-and-movement.md). The word "flagellum" is used for both because of function alone. Same name, different machine, different energy source.

## Endospores: survival, not reproduction

A small number of genera — clinically, *Bacillus* and *Clostridium* — respond to nutrient stress by building an **endospore** inside the vegetative cell.

```
VEGETATIVE CELL under stress
        │  sporulation (~8 h, asymmetric septum)
        ▼
FORE-SPORE engulfed by mother cell
        │  cortex of modified peptidoglycan laid down
        ▼
SPORE COAT (cross-linked protein) + small acid-soluble proteins in core
        │  mother cell lyses
        ▼
FREE ENDOSPORE — metabolically inactive, resistant
        │  nutrient, heat, or bile signal
        ▼
GERMINATION → outgrowth → one vegetative cell
```

| Feature | Endospore |
| --- | --- |
| **Resistance** | Heat (autoclave required), drying, radiation, many chemicals, decades in soil |
| **Why** | Core dehydrated, **Ca²⁺–dipicolinic acid** in core, **SASPs** saturating and protecting DNA, thick coat, cortex maintaining tension |
| **Metabolism** | Essentially none — no measurable respiration or synthesis |
| **Reproduction** | **No.** One cell makes one spore, one spore makes one cell — no increase in cell number |
| **Germination** | Triggered by nutrients (L-amino acids, sugars), warmth, and specific receptors |

**Three clinical consequences follow directly:**

- **Sterilisation, not disinfection, is required.** Standard disinfectants and pasteurisation kill vegetative cells and leave spores alive. Only an autoclave (121 °C, 15 psi, 15–20 min) or dry heat reliably destroys them — a distinction defined properly in [06 — Host–pathogen interaction](06-host-pathogen-interaction.md).
- ***Clostridium difficile*** forms spores that survive weeks on hospital surfaces and pass through alcohol hand rub. They germinate in the colon when normal flora is suppressed by antibiotics, and they are the reason a *C. difficile* infection relapses: the first course clears vegetative cells while the spore reservoir survives to repopulate. Repeat infection with the same strain is reinfection from spores, not treatment failure of the original isolate.
- ***Clostridium tetani*, *C. botulinum*, and *Bacillus anthracis*** all use the spore as the environmental stage — the infecting dose is usually the spore, not the actively growing organism.

**A spore is not a capsule.** A capsule is a surface layer on a living, dividing cell; a spore is a dormant, internally rebuilt state of the whole organism. The comparison of spore, cyst, and capsule is consolidated in [08 — Comparison tables](08-comparison-tables.md).

## Metabolic classification

Bacteria are classified twice over — once by what they use for energy and carbon, once by their relationship with oxygen. Both schemes are examined, and both are simple once the axes are explicit.

### Energy and carbon source

| Category | Energy source | Carbon source | Electron donor | Example |
| --- | --- | --- | --- | --- |
| **Photoautotroph** | Light | CO₂ | H₂O or H₂S | Cyanobacteria (oxygenic); purple sulfur bacteria |
| **Photoheterotroph** | Light | Organic compounds | Organic compounds | Purple non-sulfur bacteria |
| **Chemoautotroph (chemolithotroph)** | Oxidation of inorganic compounds | CO₂ | NH₃, H₂S, H₂, Fe²⁺ | *Nitrosomonas* (NH₃ → NO₂⁻), *Nitrobacter* (NO₂⁻ → NO₃⁻), methanogens |
| **Chemoheterotroph** | Oxidation of organic compounds | Organic compounds | Organic compounds | **All human pathogens**; fungi, animals |

The autotroph/heterotroph axis is about **carbon**; the phototroph/chemotroph axis is about **energy**. Nitrifying bacteria are the classic chemoautotrophs and the reason sewage works can oxidise ammonia without adding organic carbon: they fix CO₂ using the energy released from oxidising ammonia, and they are the basis of the nitrogen cycle's nitrification step.

### Relationship with oxygen

| Category | Uses O₂? | Grows without it? | Example | Test implication |
| --- | --- | --- | --- | --- |
| **Obligate aerobe** | Yes, as terminal electron acceptor | No | *Mycobacterium tuberculosis*, *Pseudomonas aeruginosa* | Colonies concentrated at top of broth |
| **Facultative anaerobe** | Yes, preferred | **Yes — switches to fermentation or anaerobic respiration** | ***E. coli*, *Salmonella*, *Staphylococcus*, *Proteus*** | Growth throughout tube, thicker at top |
| **Obligate anaerobe** | Toxic | No | *Clostridium tetani*, *Bacteroides fragilis* | Growth only at bottom; pellet-shaped colonies |
| **Aerotolerant anaerobe** | Does not use it | Yes | *Streptococcus*, *Enterococcus* | Even growth throughout |
| **Microaerophile** | Yes, at low concentration | No | *Campylobacter jejuni*, *Helicobacter pylori* | Growth only in 2–10 % O₂ (candle jar or microaerophilic jar) |

**Facultative anaerobes are the medically important group** — they carry both an aerobic respiratory chain and a fermentation pathway, so they grow in tissue, on surfaces, in broth, and in the gut. Their yield of ATP per glucose is highest with oxygen and lowest fermenting, which is exactly the metabolic logic of [03 — Cellular Processes](../03-cellular-processes/).

### ROS defence: why aerobes need enzymes aerotolerant organisms lack

Reducing oxygen inevitably produces reactive oxygen species:

```
O₂ + e⁻ → O₂•⁻ (superoxide)          made by leaky electron transport
     │
     │  SUPEROXIDE DISMUTASE (SOD)
     ▼
H₂O₂ (hydrogen peroxide)
     │
     ├─→ CATALASE:  2 H₂O₂ → 2 H₂O + O₂
     └─→ PEROXIDASE: H₂O₂ + NADH → 2 H₂O + NAD⁺
```

Obligate aerobes have SOD **and** catalase. Obligate anaerobes have neither and are killed by oxygen. Aerotolerant organisms have SOD and peroxidase but **lack catalase** — a biochemical gap with an immediate laboratory use:

| Test | Substrate | Positive result | Positive genera | Negative genera |
| --- | --- | --- | --- | --- |
| **Catalase** | H₂O₂ | Rapid O₂ bubbles | *Staphylococcus*, *Micrococcus*, *Bacillus*, *Listeria* | ***Streptococcus*, *Enterococcus***, *Clostridium* |
| **Oxidase** | Tetramethyl-*p*-phenylenediamine → dark purple (cytochrome *c* oxidase present) | Colour change within 10 s | *Pseudomonas*, *Neisseria*, *Vibrio*, *Campylobacter* | **Enterobacteriaceae** (*E. coli*, *Salmonella*, *Klebsiella*) |

**Staphylococcus vs Streptococcus on a Gram-positive Gram stain is settled by one drop of hydrogen peroxide.** That is the entire practical value of the catalase test, and it appears in exam questions constantly.

## The growth curve

In a closed culture with excess medium, populations grow in four predictable phases.

```
log
cell │
number│                                    ______________  STATIONARY
     │                              ______/                (growth = death)
     │                        ____/
     │                   ____/  LOG (EXPONENTIAL) — constant generation
     │              ____/       time; cells most susceptible to antibiotics
     │         ____/
     │    ____/   LAG — no division; enzymes synthesised,
     │___/         ribosomes built, cells adapting to medium
     │___
     └────────────────────────────────────────────────────── time
                                              DEATH/DECLINE
                                              (nutrients exhausted,
                                               waste accumulates)
```

| Phase | What is happening | Why it matters |
| --- | --- | --- |
| **Lag** | No increase in number; mRNA, enzymes, and cell mass increase; cells adjust to new medium and repair injury | An inoculum from an old culture may show a lag of hours — a negative culture at 24 h does not mean no organisms were present |
| **Log (exponential)** | Maximum rate of division; generation time constant; composition of the population uniform | **Most susceptible to antibiotics** that act on growing cells (β-lactams, vancomycin) |
| **Stationary** | Growth rate = death rate; nutrients limiting, waste accumulating; sporulation induced; stringent response | Cells upregulate efflux pumps and stress responses — **tolerance rises** |
| **Death** | Viable count falls; some cells lyse, others persist as persisters | VBNC (viable but non-culturable) states explain culture-negative infection |

**The arithmetic of doubling.** Binary fission gives geometric growth:

$$N = N_0 \times 2^{t/g}$$

where *g* is the generation time. *E. coli* under optimal conditions divides about every **20 minutes**:

```
t = 0      1 cell
t = 20 min 2 cells        2¹
t = 40 min 4 cells        2²
t = 60 min 8 cells        2³
t = 1 h    8
t = 4 h    2¹² = 4 096
t = 6 h    2¹⁸ ≈ 262 000
t = 8 h    2²⁴ ≈ 16.7 million
t = 12 h   2³⁶ ≈ 6.9 × 10¹⁰
```

Twelve hours from a single cell is tens of billions — this is why a contaminated culture is unusable, why an infection has an incubation period measured in days rather than weeks, and why one presymptomatic patient can seed an outbreak. Growth is also why **antibiotic dosing intervals** matter: a drug with concentration-dependent killing must cover the log phase of a population doubling every few hours.

## The Gram stain mechanism

The stain is not a dye adsorbed to the cell — it is a differential procedure that exploits the wall architecture described above.

| Step | Reagent | What happens in Gram-positive | What happens in Gram-negative |
| --- | --- | --- | --- |
| 1. Primary stain | **Crystal violet** | All cells purple | All cells purple |
| 2. Mordant | **Gram's iodine** | Forms insoluble **crystal violet–iodine complex** inside the wall | Same complex forms |
| 3. Decolouriser | **Alcohol or acetone** | Alcohol dehydrates the thick peptidoglycan, shrinking and closing its pores — **complex is trapped** | Alcohol **dissolves the outer membrane** and washes the complex out of the thin wall — cells become colourless |
| 4. Counterstain | **Safranin** | Purple unchanged (too dark to see pink) | Cells take up safranin → **pink** |

**Timing is everything.** Excess decolourisation strips the dye from Gram-positive cells too, so they read as Gram-negative — the commonest cause of a misleading report. Insufficient decolourisation leaves Gram-negative cells purple. Gram-positive cells also become **gram-variable** in old cultures as walls degrade.

**Organisms the Gram stain does not resolve:** *Mycobacterium* (mycolic acid wall repels the stain — use acid-fast Ziehl–Neelsen), *Mycoplasma* (no wall at all), and *Chlamydia* and *Rickettsia* (obligately intracellular, best seen by immunofluorescence or Giemsa).

The stain comes first because the wall result predicts drug access: a thin-walled Gram-negative bacillus will not respond to vancomycin no matter what the sensitivity report says in vitro, because the molecule cannot cross the outer membrane.

## Bacterial genetics: how resistance travels

Bacteria have one circular chromosome and, very often, **plasmids** — small circular DNA replicating independently, frequently carrying accessory genes such as resistance. Genetic variation arises by mutation, but the speed of resistance spread comes from **horizontal gene transfer**: DNA moving between cells that are not parent and offspring.

| Mechanism | What moves | How | Direction | Key example |
| --- | --- | --- | --- | --- |
| **Transformation** | Naked DNA from the environment | Competent cell takes up free DNA (often after lysis) and incorporates it by recombination | Any cell that is competent | Griffith's *S. pneumoniae* experiment; *Haemophilus*, *Bacillus* uptake sequences |
| **Transduction** | Bacterial DNA packaged in a **bacteriophage** | Generalised: phage accidentally packages host DNA and injects it into a new cell. Specialised: integrated prophage excises carrying adjacent genes | Cell to cell via phage | Phage-mediated transfer of diphtheria toxin gene in *Corynebacterium diphtheriae* |
| **Conjugation** | Plasmid (or chromosomal) DNA | **Sex pilus** connects cells; a copy of the plasmid is transferred through a mating bridge | Directional, cell-to-cell contact | **F plasmid**, **R (resistance) plasmids**, Hfr strains |

**Why conjugation dominates clinically:** an R plasmid can carry resistance genes to several drug classes at once and move between species. A single conjugation event in a patient on two antibiotics selects for a cell resistant to both. This is why resistance maps in hospitals look like webs rather than trees.

**Plasmids worth naming:** F (fertility, pilus formation), **R plasmids** (multiple resistance genes, transferable), Col (colicin production), Ti ( tumour-inducing, in *Agrobacterium*). **Transposons** — "jumping genes" — move between chromosome and plasmid, which is how resistance genes accumulate onto a single transferable element.

Deep treatment of replication, recombination, and control is in [05 — Molecular Biology](../05-molecular-biology/), and the population-level consequences in [06 — Evolution](../06-evolution/).

## Antibiotic targets and resistance

| Target | Drug examples | What the drug does | Selective-toxicity basis |
| --- | --- | --- | --- |
| **Peptidoglycan cross-linking** | Penicillins, cephalosporins, carbapenems (bind **PBPs**); **vancomycin** (binds D-Ala–D-Ala); **bacitracin** (lipid carrier); fosfomycin (MurA) | Block wall synthesis → osmotic lysis | Humans have no cell wall |
| **70S ribosome — 30S** | Tetracyclines, aminoglycosides (streptomycin, gentamicin) | Block initiation or cause misreading | Human cytosolic ribosomes are 80S |
| **70S ribosome — 50S** | Macrolides (erythromycin, azithromycin), clindamycin, chloramphenicol, linezolid | Block translocation or peptide bond formation | As above; mitochondrial toxicity is the caveat |
| **DNA gyrase / topoisomerase IV** | Fluoroquinolones (ciprofloxacin, levofloxacin) | Prevent DNA supercoiling → block replication | Bacterial enzyme differs structurally from human topoisomerases |
| **RNA polymerase** | **Rifampicin** | Blocks initiation of transcription | Bacterial enzyme is a distinct protein |
| **Folate synthesis** | **Sulfonamides** (PABA analogues) + **trimethoprim** (DHFR) | Block two consecutive steps of folate synthesis | **Humans lack the pathway entirely** — we obtain folate in the diet |
| **Cell membrane integrity** | Polymyxins (colistin), daptomycin | Disrupt membrane potential and integrity | Limited — membranes are chemically similar; toxicity is why these are last-line |
| **Mycolic acid synthesis** | Isoniazid, ethambutol | Cell wall of mycobacteria | Absent in other bacteria and in humans |

**The classic sequential-blockade pair:** sulfonamide and trimethoprim together (co-trimoxazole) inhibit dihydropteroate synthase and dihydrofolate reductase respectively. Two weak inhibitors given together produce a strong, synergistic block — and resistance to one alone still leaves the pathway blocked.

### How resistance actually happens

| Mechanism | Molecular event | Example |
| --- | --- | --- |
| **Enzymatic degradation** | Enzyme destroys the drug | **β-lactamases** hydrolyse the β-lactam ring; extended-spectrum β-lactamases (ESBLs); carbapenemases (KPC, NDM-1) |
| **Target modification** | Drug can no longer bind | **MRSA**: *mecA* encodes **PBP2a**, a PBP with low β-lactam affinity; ribosomal methylation (*erm*) blocks macrolides; gyrase mutations block quinolones; *vanA* changes D-Ala–D-Ala to **D-Ala–D-Lac** (vancomycin resistance) |
| **Efflux pumps** | Drug pumped back out as fast as it enters | Tetracycline efflux (Tet); AcrAB–TolC multidrug pump in *E. coli* and *Salmonella* |
| **Reduced uptake** | Fewer doorways | **Porin loss** in *P. aeruginosa* and *Klebsiella*; altered porins in fluoroquinolone-resistant *Neisseria* |
| **Metabolic bypass / target overproduction** | Alternative route or excess target | PABA overproduction overcomes sulfonamide; altered DHOase overcomes trimethoprim |
| **Biofilm** | Physically protected, slow-growing, persister cells | Chronic *P. aeruginosa* in cystic fibrosis lungs; device-associated infection |

**The three rules that tie this chapter together:** a drug needs a target the host lacks; the target needs to be reachable; and the population needs to be growing. Break any one of them and therapy fails — and resistance is simply evolution breaking the first two.

## Medical relevance

**Gram status changes therapy within the first hour of a Gram stain.** A Gram-positive coccus in clusters suggests *Staphylococcus*; in chains, *Streptococcus*. A Gram-negative rod suggests Enterobacteriaceae or *Pseudomonas*. Empirical therapy is written against that result, then narrowed when culture and sensitivity return. Vancomycin is given for suspected MRSA precisely because MRSA retains a functional transpeptidase target for every β-lactam except the anti-MRSA cephalosporins — the drug reaches the target but the target no longer binds it.

**Endotoxin defines the treatment of Gram-negative sepsis.** Lipid A triggers macrophage release of TNF-α, IL-1, and IL-6, producing fever, tachycardia, vasodilation, disseminated intravascular coagulation, and shock. Because endotoxin is a structural component released on lysis, **bactericidal antibiotics that lyse cells can worsen the initial clinical picture** — a transient worsening after starting therapy is a recognised phenomenon. There is no neutralising drug of proven benefit; treatment is source control, fluid resuscitation, and appropriate antimicrobials.

**Spores drive infection control policy.** Autoclaving, not surface disinfection, is required for instruments; *C. difficile* outbreaks are contained by cohorting and bleach-based cleaning; *Bacillus* and *Clostridium* contaminate wounds from soil. The distinction between sterilisation, disinfection, and antisepsis is set out in [06 — Host–pathogen interaction](06-host-pathogen-interaction.md).

**Capsules are vaccine targets.** The polysaccharide conjugate vaccines against *S. pneumoniae*, *Neisseria meningitidis*, and *Haemophilus influenzae* type b all work by generating opsonising antibody against the capsule — the one structure the immune system cannot easily see.

**Biofilms explain chronic, device-associated infection.** Bacteria in a biofilm are phenotypically tolerant: slow growing, matrix-protected, and largely non-dividing, so drugs targeting synthesis fail. Prosthetic joints, catheters, heart valves, and the *P. aeruginosa* lung in cystic fibrosis are all biofilm diseases, and the definitive treatment is usually removal of the device rather than a longer course of antibiotics.

**Laboratory identity rests on the tests in this chapter:** Gram reaction → catalase (staph vs strep) → oxidase (pseudomonad vs enterobacterium) → coagulase (*S. aureus* vs coagulase-negative staphylococci). Each is a few drops of reagent and each eliminates half the possibilities.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Endospores reproduce bacteria" | **No.** One cell → one spore → one cell. Sporulation is a survival structure, not a reproductive one; cell number never increases. |
| "Capsule and endospore are similar" | Capsule = extracellular surface layer on a **living, dividing** cell, resisting phagocytosis. Spore = **dormant rebuilt state** of the whole cell, resisting heat and chemicals. |
| "Gram-negative means the cell has no wall" | Gram-negative cells have a wall — it is thin — plus an **outer membrane** that makes them intrinsically impermeable to several drugs. |
| "Lipid A is a toxin the bacterium secretes" | Endotoxin is **part of the outer membrane**, released when cells lyse or bleed vesicles; it is not a secreted product and cannot be cleared by a toxin-neutralising antibody in the usual way. |
| "Alcohol hand rub kills everything" | It kills vegetative cells and enveloped viruses efficiently but **does not reliably kill endospores** — hence soap, water, and chlorine for *C. difficile* spores. |
| "Facultative anaerobes are anaerobes" | They are aerobes that can switch. With oxygen they respire and yield far more ATP; without it they ferment. *E. coli* is a facultative anaerobe, not an anaerobe. |
| "Oxidase and catalase test the same thing" | Different enzymes, different substrates. Catalase = H₂O₂ → water (staph vs strep). Oxidase = cytochrome *c* oxidase (pseudomonas vs enterobacterium). |
| "Antibiotics work by killing dividing cells" | Only wall and nucleic-acid synthesis inhibitors require division. Membrane-active drugs and protein synthesis inhibitors act regardless of growth rate. |
| "Resistance only arises from antibiotic use" | Antibiotics **select** for pre-existing or newly arisen resistance; they do not create it. Genes can also arrive by transfer from organisms never exposed to the drug. |
| "Conjugation is bacterial reproduction" | It is **DNA transfer between existing cells**, not cell division. Donor and recipient both survive; only the genome changes. |

## Key facts

- Peptidoglycan = alternating **NAG and NAM** linked β-1,4, with stem peptides cross-linked by **transpeptidation** via **PBPs**; lysozyme cleaves the β-1,4 bond; vancomycin binds **D-Ala–D-Ala**.
- **Gram-positive**: thick peptidoglycan, teichoic and lipoteichoic acids, no outer membrane, purple. **Gram-negative**: thin peptidoglycan, periplasm, **outer membrane with LPS and porins**, pink, intrinsically resistant to large hydrophobic drugs.
- **Lipid A is endotoxin** — fever, TNF-α/IL-1 release, septic shock; it is a wall component, not a secreted toxin.
- Capsule = anti-phagocytic virulence factor (Griffith's *S. pneumoniae*); fimbriae = attachment; sex pilus = conjugation.
- The **prokaryotic flagellum** is a rotary motor powered by the **proton motive force**, not ATP; the eukaryotic 9+2 axoneme is dynein-driven — see [05 — Structure and movement](../02-cell-biology/05-structure-and-movement.md).
- **Endospores** (*Bacillus*, *Clostridium*) resist heat and chemicals via Ca²⁺–dipicolinic acid, SASPs, and dehydration; they are **not reproductive**; only autoclaving sterilises them.
- Metabolic axes: photo/chemo (energy) × auto/hetero (carbon); all human pathogens are **chemoheterotrophs**.
- Oxygen categories: aerobe, **facultative anaerobe (most pathogens)**, obligate anaerobe, aerotolerant, microaerophile.
- **Catalase test**: *Staphylococcus* positive, *Streptococcus* negative. **Oxidase test**: *Pseudomonas* positive, Enterobacteriaceae negative.
- Growth curve: **lag → log → stationary → death**; antibiotics that block wall synthesis act best in **log phase**; *E. coli* generation time ≈ **20 min**.
- Horizontal gene transfer: **transformation** (naked DNA), **transduction** (phage), **conjugation** (pilus, R plasmids) — the route resistance genes travel.
- Resistance mechanisms: **enzymatic degradation, target modification, efflux, reduced uptake**, plus bypass and biofilm tolerance.

## Practice questions

**1. A β-lactam antibiotic exerts its effect by**

A. Binding D-Ala–D-Ala and blocking transpeptidation directly
B. Acylating the active-site serine of penicillin-binding proteins, preventing peptide cross-linking
C. Inserting into the outer membrane and dissipating the proton gradient
D. Binding the 30S ribosomal subunit and causing misreading

**Answer: B**

Explanation: β-lactams are structural mimics of the D-Ala–D-Ala stem-peptide terminus; the transpeptidase (a PBP) binds the drug instead of the substrate, the ring opens, and the enzyme is irreversibly inhibited. Without cross-links the growing wall cannot withstand osmotic pressure and the cell lyses. Option A describes vancomycin, which binds the substrate rather than the enzyme; C describes polymyxins and daptomycin; D describes aminoglycosides such as streptomycin.

---

**2. A Gram-negative bacterium is intrinsically resistant to vancomycin because**

A. It lacks peptidoglycan
B. Its outer membrane prevents the large glycopeptide from reaching the periplasmic target
C. It produces an enzyme that hydrolyses the drug
D. It pumps the drug out faster than it enters

**Answer: B**

Explanation: Vancomycin is a large, charged molecule that cannot diffuse through porins and cannot cross the asymmetric outer membrane, so it never reaches the peptidoglycan it would otherwise block. Gram-positive organisms lack that barrier and are susceptible. A is false — Gram-negative cells have peptidoglycan, just a thin layer. C would describe β-lactamase activity against β-lactams, and D describes efflux, but neither explains *intrinsic* (universal, non-acquired) resistance of the species.

---

**3. Which structure is directly responsible for the endotoxic activity of a Gram-negative organism?**

A. Porin
B. Teichoic acid
C. Lipid A of lipopolysaccharide
D. Capsular polysaccharide

**Answer: C**

Explanation: Lipid A anchors LPS in the outer leaflet of the outer membrane and is released on lysis or in outer membrane vesicles. It triggers macrophage release of TNF-α, IL-1, and IL-6, producing fever, vasodilation, and potentially septic shock. Teichoic acids are Gram-positive (B), porins are channels (A), and capsules are anti-phagocytic rather than endotoxic (D).

---

**4. The most important difference between the prokaryotic flagellum and the eukaryotic flagellum is that the prokaryotic one**

A. Uses ATP hydrolysis by dynein
B. Contains a 9+2 microtubule axoneme
C. Rotates as a rigid filament driven by the proton motive force
D. Is surrounded by a membrane continuous with the plasma membrane

**Answer: C**

Explanation: The bacterial flagellum is a rotary motor: protons flow through stator complexes (MotA/MotB) in the basal body, generating torque that spins a filament of flagellin. Direction reversals are controlled by CheY~P at the switch complex. The eukaryotic flagellum instead has an internal 9+2 axoneme of microtubules in which dynein arms use ATP to slide doublets — see 02 — Cell Biology, chapter 05. B and A describe the eukaryotic form; D is true of the eukaryotic structure, not the bacterial one, which is external to the membrane.

---

**5. Which statement about bacterial endospores is correct?**

A. They increase the number of bacterial cells
B. They are formed by all bacteria under stress
C. They are metabolically inactive survival structures resistant to heat and disinfectants, formed by genera such as *Bacillus* and *Clostridium*
D. They are equivalent to capsules in function

**Answer: C**

Explanation: Sporulation produces one dormant spore from one vegetative cell — no increase in cell number, so it is not reproduction (A). Only certain genera sporulate (B), typically in response to nutrient depletion. The spore's resistance comes from core dehydration, Ca²⁺–dipicolinic acid, small acid-soluble proteins protecting DNA, and a protein coat — which is why only sterilisation (autoclaving) reliably destroys them. A capsule is a surface layer of a growing cell defending against phagocytosis, not a dormant state (D).

---

**6. A catalase-positive, coagulase-positive Gram-positive coccus in clusters is most likely**

A. *Streptococcus pyogenes*
B. *Staphylococcus aureus*
C. *Enterococcus faecalis*
D. *Streptococcus pneumoniae*

**Answer: B**

Explanation: Gram-positive cocci in clusters that are catalase-positive are staphylococci; among them, coagulase positivity identifies *S. aureus*. Streptococci and enterococci are catalase-negative (they lack catalase and use peroxidase), and they grow in chains rather than clusters. The catalase test — rapid bubbling with hydrogen peroxide — is the fastest first split between the two genera, which is why it appears in examination questions so often.

---

**7. During which phase of the bacterial growth curve are organisms most susceptible to cell wall–synthesising antibiotics?**

A. Lag phase
B. Log (exponential) phase
C. Stationary phase
D. Death phase

**Answer: B**

Explanation: β-lactams and vancomycin act on the machinery of ongoing wall construction, so they work best where that machinery is most active — the log phase, when every cell is elongating and cross-linking new peptidoglycan. In lag phase little wall synthesis occurs; in stationary phase cells are not dividing and stress responses and efflux raise tolerance; in death phase many cells are already non-viable. This is the pharmacological reason dosing regimens aim to maintain drug concentrations across the periods of fastest growth.

---

**8. Which pair correctly matches a gene transfer mechanism with its vehicle?**

A. Transformation — bacteriophage
B. Transduction — sex pilus
C. Conjugation — direct cell contact through a pilus and an R plasmid
D. Transduction — naked DNA in the environment

**Answer: C**

Explanation: Conjugation requires contact: a sex pilus brings cells together and a plasmid (often an R plasmid carrying multiple resistance genes) is copied across the mating bridge. Transformation takes up **naked** DNA from the environment (Griffith's experiment); transduction uses a **bacteriophage** as the vehicle — either generalised packaging of random host DNA or specialised excision carrying adjacent genes. Swapping A, B, and D simply confuses the three vehicles.

---

**9. A patient with Gram-negative sepsis deteriorates shortly after starting a bactericidal antibiotic. What is the most plausible mechanism?**

A. The antibiotic is inducing resistance
B. Lysis of the bacteria releases large amounts of lipid A endotoxin, amplifying the cytokine response
C. The antibiotic is itself pyrogenic
D. The patient has developed an allergy to the drug

**Answer: B**

Explanation: Lipid A is a structural component of the outer membrane; killing and lysing Gram-negative cells releases it in bulk, and the resulting TNF-α, IL-1, and IL-6 surge can transiently worsen fever, hypotension, and coagulopathy — the reason supportive care continues alongside antimicrobials. A is a slower process that does not explain an immediate clinical change; C is not a recognised property of these drugs at therapeutic dose; D would present with rash, bronchospasm, or hypotension of immediate hypersensitivity type, not with the septic picture described.

---

**10. Which is the correct basis for the selective toxicity of sulfonamides and trimethoprim?**

A. Human ribosomes are 80S while bacterial ribosomes are 70S
B. Humans lack the folate synthesis pathway and obtain folate from the diet, whereas bacteria must synthesise it
C. Human cells have no plasma membrane to be disrupted
D. DNA gyrase in humans is structurally identical to bacterial gyrase

**Answer: B**

Explanation: Sulfonamides are structural analogues of para-aminobenzoic acid and inhibit dihydropteroate synthase; trimethoprim inhibits dihydrofolate reductase. Both enzymes operate in the bacterial folate synthesis pathway, which humans do not possess at all — humans take up dietary folate. Giving both agents blocks two consecutive steps, producing synergy. A describes the basis of aminoglycoside, tetracycline, macrolide, and linezolid selectivity; C is not a real mechanism; D is false — human topoisomerases differ from bacterial gyrase, which is what makes quinolones selective.
