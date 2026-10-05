# The Immune System

## Why it matters

[06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md) gave the microbe's half — virulence factors, toxins, evasion, sepsis. This is the **host's half**: barriers, phagocytes, complement, T cells, B cells, and the rules that keep them pointed at microbes rather than at you. Every counter-move catalogued there mirrors a defence described here.

```
LINE 1 — BARRIERS   immediate   no specificity   no memory
LINE 2 — INNATE     minutes     PAMP patterns    no memory
LINE 3 — ADAPTIVE   days        one epitope      lifelong memory

each line holds until the next arrives → LAYERED DEFENCE
```

Two further rules govern everything. **Self versus non-self**: food, commensals and a foetal graft are foreign yet tolerated, while self protein must never be attacked — the line separating tolerance, allergy and autoimmunity. And **clonal selection**, which runs backwards from intuition: the receptor exists *before* the pathogen.

```
RANDOM V(D)J REARRANGEMENT → millions of lymphocytes, ONE receptor each
        ↓ antigen arrives and binds the single matching receptor
CLONAL SELECTION → expansion → effectors (antibody, killers) + MEMORY
        ↓ same antigen years later → response starts from memory, not from zero
```

The section-wide discipline applies component by component: **structure → function → mechanism → regulation → homeostasis** — shape sets the job, mechanism is a chain, regulation stops it, failure is the clinical picture. Tissue context is in [01 — Four tissue types](../09-human-biology/01-four-tissue-types.md).

## Three lines of defence at a glance

| | **First: barriers** | **Second: innate** | **Third: adaptive** |
| --- | --- | --- | --- |
| **Members** | Skin, cilia, acid, enzymes, normal flora | Phagocytes, inflammation, complement, NK cells, fever | **B cells → antibody**; **T cells → cell-mediated** |
| **Speed** | Immediate | Minutes to hours | 7–14 days first exposure; 1–3 days after |
| **Recognition** | None — blocks everything | **PAMPs** (LPS, lipoteichoic acid, flagellin, CpG) via **TLRs** | One epitope, one clone |
| **Memory** | No | **No** | **Yes** |
| **Failure gives** | Breach, infection of sterile sites | Sepsis, recurrent bacterial and fungal infection | Recurrent viral infection, no vaccine response |

Innate and adaptive are a relay, not rivals: innate buys time and carries antigen to lymph nodes, adaptive feeds back — **opsonising antibody** accelerates phagocytosis and **IgM/IgG** drive complement. Antibody without complement fails; antigen without CD4 help goes nowhere.

## First line: barriers

The first line is pure **structure**: nothing is recognised, nothing remembered — the body presents a surface a microbe cannot cross.

### Physical barriers

| Barrier | Structure | Mechanism |
| --- | --- | --- |
| **Skin** | Keratinised stratified squamous epithelium, constantly shedding | Dry, abrasive, renewed — microbes leave with dead cells |
| **Mucociliary escalator** | Pseudostratified ciliated epithelium + goblet cells | Cilia drive a mucus sheet to the pharynx; **smoking paralyses it**, immotile cilia cause recurrent chest infection |
| **Mucus** | Glycoprotein gel (gut, airway, urogenital) | Traps and immobilises; carries IgA and lysozyme |
| **Flow and flushing** | Tears, saliva, urine, peristalsis | Mechanical removal — a microbe must adhere faster than it is washed away |
| **Blink** | Lacrimal apparatus | Washes the conjunctiva and delivers lysozyme |

### Chemical barriers

| Barrier | Chemistry | Effect |
| --- | --- | --- |
| **Skin** | Sebum → **pH ~5.5**; sweat (lysozyme, salt) | Acid mantle inhibits pathogens, cutaneous flora thrives |
| **Stomach** | **HCl, pH 1.5–3.5** | Near-sterilising step for everything swallowed |
| **Vagina** | Lactic acid, **pH ~4** | Selects *Lactobacillus*; pH rises after antibiotics |
| **Tears, saliva, airway** | **Lysozyme** | Cleaves the NAM–NAG bond of **peptidoglycan**; best where Gram-positive wall is exposed ([01 — Bacterial structure and physiology](../07-microbiology/01-bacterial-structure-and-physiology.md)) |
| **Defensins** | Small cationic peptides (Paneth cells, neutrophils) | Insert into microbial membranes → **pores** → lysis |
| **Surfactant, lactoferrin** | Collectins SP-A/SP-D; iron-binding protein | Opsonise and **withhold iron** |

### Biological barriers: colonisation resistance

Every surface is already **occupied**. Normal flora take nutrients, hold adhesion sites, keep pH low and secrete bacteriocins against newcomers — **colonisation resistance** ([07 — Beneficial microorganisms](../07-microbiology/07-beneficial-microorganisms.md)). Remove it and disease follows: broad-spectrum antibiotics strip the flora, then *Clostridioides difficile* or *Candida* overgrows; germ-free animals even have underdeveloped lymphoid tissue, so flora is a training partner as well as a wall. Each pathogen's answer — capsule, IgA protease, intracellular niche — sits in the evasion table of [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md).

## Innate immunity: the immediate response

Innate immunity is **mechanism, not memory**: the same receptors and effector chains fire on the thousandth exposure as on the first. It recognises **pathogen-associated molecular patterns** — LPS, lipoteichoic acid, flagellin, peptidoglycan, unmethylated CpG DNA — via **pattern-recognition receptors**, chiefly **toll-like receptors (TLRs)**. PAMPs are shared by whole microbial classes, so innate recognition separates **microbial from host**, not one species from another.

### The phagocytes

| Cell | Origin | Features | Role |
| --- | --- | --- | --- |
| **Neutrophil** | Bone marrow; **short-lived**, most abundant white cell | Multilobed nucleus, fine granules; arrives first in numbers | Kills fast and dies — **pus is dead neutrophils, debris and microbes** |
| **Macrophage** | Monocyte → tissue (**Kupffer**, microglia, alveolar) | Large, long-lived, lysosome-rich | Phagocytosis, **cytokine secretion**, **antigen presentation** |
| **Dendritic cell** | Skin (**Langerhans**), mucosa, blood | Long processes, huge surface | **Bridge to adaptive**: captures antigen, migrates to the lymph node, presents on **MHC II** |
| **Mast cell / basophil** | Beside vessels in connective tissue | Granules of **histamine**, heparin | Degranulation → vasodilation and leak; effector of type I hypersensitivity |
| **Eosinophil** | Blood, mucosa | Bilobed, major basic protein | **Anti-helminth** degranulation; prominent in allergy |

**Neutrophils arrive first and do not survive; macrophages arrive later, eat, then report** — hence early abscesses are neutrophilic and tuberculosis, which hides inside macrophages, becomes a granuloma problem.

### Phagocytosis: the mechanism chain

```
1. ATTACHMENT — PRRs bind PAMPs, OR microbe is OPSONISED (C3b via CR1,
   IgG via Fc receptor) → opsonised uptake is much faster
        ↓
2. INGESTION — pseudopods surround it → PHAGOSOME
        ↓
3. MATURATION — phagosome + LYSOSOME = PHAGOLYSOSOME (H+ pumps → pH ~4.5)
        ↓
4. KILLING — a) OXIDATIVE BURST: NADPH oxidase → O2− → H2O2 → HOCl
             b) NON-OXIDATIVE: lysozyme, defensins, cathepsins, low pH
        ↓
5. DIGESTION → peptide loaded onto MHC II if the cell is an APC
```

**Chronic granulomatous disease** is a defect of **NADPH oxidase**: step 4a fails, catalase-positive organisms (*S. aureus*, *Aspergillus*) survive, and tissue walls itself off in **granulomas**. Each microbial counter-move — capsule blocking attachment, *M. tuberculosis* blocking step 3, *Listeria* escaping the vesicle — is the other side of this chain ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)).

### Inflammation: the mechanism chain

```
INJURY or MICROBE → macrophages and mast cells release histamine,
        prostaglandins, leukotrienes, TNF-α, IL-1
        ↓
VASODILATION → REDNESS + HEAT; VENULAR LEAK → OEDEMA
        ↓ bradykinin, prostaglandins, pressure → PAIN → LOSS OF FUNCTION
SELECTINS and ICAM-1 displayed → neutrophils ROLL, ADHERE, DIAPEDESIS
        ↓ CHEMOTAXIS along C5a, IL-8, bacterial formyl peptides, LTB4
PHAGOCYTOSIS clears the focus → RESOLUTION (lipoxins, IL-10, TGF-β)
        ↓ material not cleared → CHRONIC inflammation → granuloma / fibrosis
```

**Resolution is active, not passive**: anti-inflammatory mediators switch the chain off at its site. When the same mediators act **systemically**, vasodilation and capillary leak become hypotension and coagulation becomes disseminated intravascular coagulation — the cytokine storm of **sepsis** ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)). Local is protective; systemic is lethal.

### Complement: three pathways, one convergence

**Complement** is ~30 liver-made plasma proteins circulating inactive until a surface triggers them; only initiation differs.

| Pathway | Trigger | Initiating complex | What it detects |
| --- | --- | --- | --- |
| **Classical** | Antigen bound to **IgG or IgM** | **C1q** binds Fc → C1r/C1s | Antibody already present — links innate to adaptive |
| **Alternative** | Spontaneous **C3 hydrolysis ("tick-over")** | **C3bBb** (with factor B, factor D), stabilised by properdin | Surfaces lacking host regulators (factor H, DAF) — **no antibody needed** |
| **Lectin** | **Mannose-binding lectin** binds microbial mannose/fucose | MASP proteases cleave C2 and C4 | Microbial glycans absent from host glycoproteins |

```
CLASSICAL   ALTERNATIVE   LECTIN   → all converge on C3 CONVERTASE
                                    → C3 = C3a + C3b
C3b  = OPSONIN (CR1 on phagocytes) + amplifies the convertase
C3a, C5a = ANAPHYLATOXINS → mast cell degranulation, smooth-muscle spasm
C5a  = strongest CHEMOTACTIC signal for neutrophils
C5b + C6 + C7 + C8 + C9 → MAC (C5b–9) PORE → osmotic LYSIS
```

Four outputs: **opsonisation, inflammation, chemotaxis, lysis** — the classic failure of the last being Gram-negative bacteraemia, and (from loss of the protective GPI anchors) paroxysmal nocturnal haemoglobinuria. Pathogens counter each step: *S. pyogenes* **M protein binds factor H**, its **C5a peptidase** destroys the chemotactic signal, *Neisseria* coats itself in **sialic acid** ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)). Antibody exploits the cascade deliberately: **IgM is the best complement activator**, one pentamer alone starting the classical pathway.

### Natural killer cells: the missing-self detector

**NK cells** are innate large granular lymphocytes: no prior sensitisation, no specific antigen — they read the **absence of self**.

```
Normal cell → MHC CLASS I present → INHIBITORY receptor engaged → no kill
Virus-infected / tumour cell → MHC I lost ("missing self")
        → inhibition withdrawn, activating receptors (NKG2D) unopposed
        → PERFORIN pores + GRANZYMES → caspases → APOPTOSIS
```

They also perform **ADCC**: CD16 binds the Fc of IgG-coated targets, so antibody marks and the NK cell delivers — covering the blind spot of CD8 T cells, which *require* MHC I to see a target.

### Cytokines and fever

**IL-1, IL-6 and TNF-α** raise the hypothalamic **temperature set point** via prostaglandin E₂: **fever** is a host cytokine effect, not a product of the microbe, so viruses, fungi and sterile injury all cause it. The liver answers with **C-reactive protein** and **mannose-binding lectin**, acute-phase opsonins. Regulation is negative feedback plus **IL-10 and TGF-β**; in bulk the same mediators produce sepsis, and its failure gives immunoparalysis after critical illness.

## Adaptive immunity: the machinery

Adaptive immunity is **specific, clonally distributed and memory-bearing**. Its receptors arise by **V(D)J recombination** — somatic rearrangement of gene segments — which is why the repertoire is enormous while the genes stay in the germline ([01 — Genes, alleles, genotype, phenotype](../04-genetics/01-genes-alleles-genotype-phenotype.md)). Two arms: **humoral** (B cells and antibody, against extracellular microbes and toxins) and **cell-mediated** (T cells, against intracellular microbes).

### Antigen presentation: MHC class I and class II

T cells never see a whole pathogen — they see **peptide on a surface molecule**, and the two MHC classes are the routing system saying where the antigen came from.

| | **MHC class I** | **MHC class II** |
| --- | --- | --- |
| **Molecules** | HLA-A, B, C | HLA-DR, DP, DQ |
| **Found on** | **ALL nucleated cells** (not red cells) | **Professional APCs only**: dendritic cells, macrophages, B cells |
| **Peptide source** | **Intracellular** — proteasome digests viral/tumour proteins, **TAP** loads the ER | **Extracellular** — degraded in the phagolysosome; invariant chain then **HLM-DM** edit the groove |
| **Read by** | **CD8⁺ cytotoxic T cells** | **CD4⁺ helper T cells** |
| **Meaning** | "Something foreign is replicating **inside me**" | "I have **eaten** something foreign" |

```
INTRACELLULAR antigen → proteasome → TAP → ER → MHC I → CD8 T cell
        → CYTOTOXIC KILLING of the infected cell
EXTRACELLULAR antigen → APC phagosome → MHC II → CD4 T cell
        → HELPER SIGNALS (cytokines, CD40L) to the rest of the response
```

A cell that loses MHC I (many tumours, herpesvirus-infected cells) is invisible to CD8 cells yet conspicuous to **NK cells** — the two systems cover each other's gap. Red cells, with no MHC at all, are handled by antibody and complement.

### Two-signal activation: the autoimmunity safeguard

A naive T cell needs **two signals**: **(1)** TCR binding of **peptide–MHC**, and **(2)** **co-stimulation** — CD28 engaging **B7 (CD80/86)**, which an APC expresses only after its TLRs sense danger.

**Signal 1 without signal 2 does not activate: it induces anergy or deletion.** Resting tissue cells express no B7, so a T cell recognising a self peptide on them is switched off, not switched on. Tumours exploit the mirror of this with **PD-L1** engaging **PD-1** to silence T cells — the rationale for checkpoint-inhibitor immunotherapy.

### B cells and humoral immunity

```
NAIVE B CELL, ONE receptor specificity → antigen cross-links the BCR
        ↓ peptide presented on MHC II to a T follicular helper cell
CD40L + IL-4/IL-21 → CLONAL EXPANSION → GERMINAL CENTRE
        ↓ somatic hypermutation + selection by best fit → AFFINITY MATURATION
        ↓ class-switch recombination (IgM → IgG / IgA / IgE)
PLASMA CELLS (hundreds of antibody molecules per second) + MEMORY B CELLS
```

#### Antibody structure

An immunoglobulin is a Y of **two identical heavy chains and two identical light chains** joined by disulphide bonds.

| Region | Position | Function |
| --- | --- | --- |
| **Variable region (V)** | N-terminal ends of **both** heavy and light chains, hypervariable **CDRs** | The **antigen-binding site (paratope)** — two per antibody, identical |
| **Constant region (C)** | Remaining heavy-chain domains + light-chain constant | Defines the **class**; the **Fc** end binds Fc receptors and complement |
| **Hinge** | Flexible segment (IgG) | Lets the arms span epitopes spaced apart → **cross-linking** |
| **Fab / Fc** | Two arms / stem | Fab **binds**; Fc **acts** — opsonisation, C1q, placental transfer, mast cell binding |

Papain cleaves above the hinge → two Fab + one Fc; pepsin below it → one F(ab')₂ that still cross-links antigen.

#### The five classes

| Class | Shape | Where it acts | Special features |
| --- | --- | --- | --- |
| **IgM** | **Pentamer** | Blood, first responder | **First antibody made**; 10 binding sites → **best complement activator**; no placental transfer |
| **IgG** | Monomer | Blood and tissue — **the main systemic antibody** | **Opsonisation**; **crosses the placenta** via FcRn ([05 — Placenta and foetal exchange](../11-reproduction-and-development/05-placenta-and-maternal-fetal-exchange.md)); the antibody of vaccine immunity |
| **IgA** | Dimer, **secretory** | **Mucosa**, gut, airway, breast milk | **Secretory component** resists proteolysis; neutralises at the surface without inflammation |
| **IgE** | Monomer on **FcεRI** | Bound to mast cells and basophils | **Degranulation when cross-linked** — type I allergy and **anti-helminth** defence |
| **IgD** | Monomer | B-cell surface | Co-expressed with IgM as the **B-cell receptor** |

#### What antibody does

| Function | Mechanism |
| --- | --- |
| **Neutralisation** | Coats the viral attachment site or toxin active site so neither can bind its receptor |
| **Opsonisation** | **IgG Fc → Fcγ receptors**, and C3b → CR1, accelerate ingestion |
| **Complement activation** | **IgM** then IgG bind C1q → classical cascade → C3b and MAC |
| **Agglutination** | One antibody cross-links many particles → clumps (basis of blood grouping) |
| **ADCC** | NK cell **CD16** binds Fc of an antibody-coated cell |

**Antibody works only where it can reach** — extracellular fluid, blood, mucosa. Anything inside a cell is physically protected, the decisive limit of humoral immunity.

### T cells and cell-mediated immunity

T cells mature in the **thymus**; both subsets read peptide–MHC but differ in class and therefore in job.

#### Helper subsets (CD4)

| Subset | Drivers | Factor | Role | Dominates in |
| --- | --- | --- | --- | --- |
| **Th1** | IL-12, IFN-γ | T-bet | **Activates macrophages**; opsonising IgG | Intracellular bacteria — *M. tuberculosis* |
| **Th2** | IL-4 | GATA-3 | **IgE switching**, eosinophil and mast cell recruitment | Helminths; hijacked in allergy |
| **Th17** | IL-6, TGF-β, IL-23 | RORγt | **Neutrophil recruitment**, barrier defence | Extracellular bacteria and fungi; psoriasis |
| **Treg** | TGF-β, IL-10 | **Foxp3** | **Suppresses** effectors — tolerance enforced | Peripheral tolerance; loss → IPEX |
| **Tfh** | IL-6, IL-21 | Bcl-6 | Germinal-centre help for B cells | Affinity maturation, class switching |

IFN-γ antagonises Th2 and IL-4 antagonises Th1, so responses **polarise** rather than mix — which is why one clinical picture dominates.

#### Cytotoxic T cells (CD8)

```
CTL TCR binds peptide–MHC I → CD8 confirms class I → synapse locks
        ↓ granules polarise toward the target
PERFORIN polymerises → PORES; GRANZYMES enter → CASPASES → APOPTOSIS
(alternative) FAS LIGAND binds FAS → caspase-8 → APOPTOSIS
```

The target dies by **apoptosis, not necrosis** — no inflammatory spill — and the CTL detaches to kill again. This clears virus-infected and tumour cells and is the mechanism of transplant rejection.

**Delayed-type hypersensitivity** is the same machinery in tissue: sensitised memory T cells take **24–72 hours** to recruit and activate macrophages, with no antibody involved — the basis of the tuberculin test and contact dermatitis (type IV below).

### Immunological memory

| | **Primary** | **Secondary** |
| --- | --- | --- |
| **Lag** | **7–14 days** | **1–3 days** |
| **Class first** | Mainly **IgM** | Mainly **IgG**, class-switched |
| **Peak and affinity** | Lower; low, variable affinity | **Much higher; high affinity** after **affinity maturation** |
| **Cells** | Naive clone, selected from scratch | **Memory clones**, already expanded |

```
first exposure → lag → IgM rises and falls → MEMORY CELLS remain
second exposure → no relearning → fast, large, high-affinity IgG
        → usually no disease → the whole basis of VACCINATION
```

Vaccination creates **memory without disease** (platforms below; virology in [03 — Viruses](../07-microbiology/03-viruses.md)). Vaccines fail when **antigenic variation** moves the target or **titre wanes** without boosters.

### Tolerance: self is not selected against

| Arm | Where | Mechanism | Failure |
| --- | --- | --- | --- |
| **Central** | **Thymus** (T), **bone marrow** (B) | **Negative selection**: high-affinity self-reactive clones are deleted. Thymic **AIRE** forces expression of tissue-specific antigens (insulin, thyroglobulin) so the test can be run | **AIRE mutations → APECED**: autoimmune polyendocrinopathy |
| **Peripheral** | Body tissues | **Anergy** without co-stimulation; **Treg** suppression; antigen **sequestered** behind a barrier; activation-induced cell death | Autoimmunity once an escaped clone is triggered |

**Tolerance is antigen-specific; immunosuppression is not** — every transplant drug suppresses the second as well as the first. Susceptibility sits in inherited **HLA alleles**: HLA-DR3/DR4 with type 1 diabetes, **HLA-B27** with ankylosing spondylitis, HLA-DQ2/DQ8 with coeliac disease.

## Hypersensitivity: the four types

**Hypersensitivity is an excessive or misdirected immune response causing tissue damage** — the system working as designed at the wrong target or the wrong scale.

| Type | Name | Mechanism | Examples | Test |
| --- | --- | --- | --- | --- |
| **I** | Anaphylactic / atopic | **IgE** bound to **FcεRI on mast cells**; re-exposure cross-links it → degranulation in **minutes**: histamine, leukotrienes → vasodilation, bronchoconstriction | **Anaphylaxis**, asthma, hay fever, urticaria, food allergy | **Skin prick test** or specific **IgE** |
| **II** | Cytotoxic | **IgG/IgM against a cell-surface antigen** → MAC, Fc-mediated phagocytosis, ADCC → cell destruction | **Autoimmune haemolytic anaemia**, **transfusion reactions**, haemolytic disease of the newborn, **myasthenia gravis** ([02 — Muscular system](02-muscular-system.md)) | **Direct Coombs test** |
| **III** | Immune complex | **Antigen–antibody complexes deposit** in vessels, glomeruli, joints → complement and neutrophils damage tissue | **Serum sickness**, **SLE**, post-streptococcal glomerulonephritis | Low **C3/C4** (consumption) |
| **IV** | Delayed, cell-mediated | Sensitised **T cells and macrophages** release cytokines; peak at **48–72 hours**; no antibody | **Contact dermatitis** (nickel), **tuberculin (Mantoux) test**, granulomas, type 1 diabetes | Intradermal injection read at **48–72 h** |

Memorise the pairing: **IgE = I, antibody-on-a-cell = II, deposited complex = III, T cells and delay = IV.** Types I and IV differ by timing (minutes versus days) and by effector (IgE versus T cells).

## Immunodeficiency

**Primary** immunodeficiency is a genetic defect of one component; **secondary** is acquired loss of function. The infections a patient gets are a map of which limb failed.

| Defect | Mechanism | Typical infections |
| --- | --- | --- |
| **X-linked agammaglobulinaemia** | **Btk** mutation → no B-cell maturation → **no antibody** | Encapsulated bacteria from ~6 months; giardiasis |
| **SCID** | **T and B cells both fail** (γ-chain or ADA defect) | Opportunistic infection from birth; no vaccine response |
| **DiGeorge syndrome** | 22q11 deletion → **no thymus** | Viral, fungal, *Pneumocystis*; hypoparathyroidism, cardiac defects |
| **Chronic granulomatous disease** | **NADPH oxidase** defect → no oxidative burst | *S. aureus*, *Aspergillus*, *Serratia*; granulomas |
| **Complement deficiency (C1–C3)** | No opsonisation or classical pathway | Severe **encapsulated** infection; lupus-like disease |
| **HIV / AIDS** | **Destruction of CD4⁺ T cells** | Opportunistic infections and cancers by CD4 count |

### Secondary: HIV destroys the helper cell

HIV is a virus in [03 — Viruses](../07-microbiology/03-viruses.md); its immunological signature is that it attacks the cell *coordinating* the response.

```
gp120 binds CD4 + CCR5/CXCR4 on a HELPER T CELL → fusion, PROVIRUS integrated
        ↓ budding infects more CD4 cells; chronic activation exhausts them
CD4 COUNT FALLS (normal 500–1500/µL)
        ↓ Tfh/Th1 help lost → NO ANTIBODY MATURATION, weak macrophage activation
<200: Pneumocystis pneumonia, oral candidiasis, Kaposi sarcoma
<100: toxoplasmosis, cryptococcal meningitis
< 50: cytomegalovirus retinitis, Mycobacterium avium, CNS lymphoma
        ↓ AIDS — everything downstream of CD4 fails
```

**Antibody responses to new antigens collapse first** (poor vaccine responses, falling titres), then pathogens needing macrophage activation, then opportunistic infection: everything contained by a healthy host in [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md) reactivates when CD4 help disappears.

## Medical relevance

### Vaccine types

| Type | Example | Content and mechanism | Trade-off |
| --- | --- | --- | --- |
| **Live attenuated** | MMR, BCG, oral polio, varicella | Weakened but **replicating** → intracellular antigen → **MHC I and II** → CD8 as well as CD4, strong memory | Best, longest immunity; **contraindicated in pregnancy and immunodeficiency** |
| **Inactivated** | Injectable polio, hepatitis A, rabies | Killed organism → extracellular antigen → **MHC II only** → antibody | Safe, no reversion; **needs boosters**, weak CD8 |
| **Subunit / recombinant** | Hepatitis B (HBsAg), HPV (VLP), acellular pertussis | Purified protein or particle | Very safe and defined; **adjuvant and boosters required** |
| **Toxoid** | **Tetanus, diphtheria** | Formalin-**detoxified exotoxin** → **neutralising antitoxin** — immunity to the toxin, not the microbe | Cannot cause disease; possible only because an exotoxin is a protein that keeps its shape ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)) |
| **Conjugate** | *H. influenzae* b, pneumococcal, meningococcal | **Polysaccharide linked to a carrier protein** | Works in **infants** — see below |

Plain polysaccharide is **T-independent**: no T-cell help, no germinal centres, **no memory**, and a poor response in under-2s. Conjugation forces APCs to present **carrier-protein peptide on MHC II** → CD4 help → class switching, affinity maturation and lasting memory — the single link that lets conjugate vaccines protect infants where plain polysaccharide cannot ([01 — Bacterial structure and physiology](../07-microbiology/01-bacterial-structure-and-physiology.md)). Vaccination works by **clonal selection**: it stores the clone rather than waiting for the pathogen to select it during illness.

### Allergy and antihistamines

Atopy is **excess IgE** against harmless antigen on a **Th2-polarised** background: re-exposure cross-links IgE on mast cells and mediators act in minutes — **histamine at H1** gives vasodilation, leak, itching and bronchoconstriction, while leukotrienes sustain the late phase.

- **Antihistamines are H1-receptor antagonists** (cetirizine, loratadine, chlorphenamine): they block the receptor, not the IgE or the mast cell — good for rhinitis and urticaria, weak in asthma.
- **Adrenaline treats anaphylaxis**: α1 vasoconstriction restores blood pressure, β2 bronchodilates, mast cells stabilise.
- Mechanism-based prevention: allergen avoidance, **omalizumab** (anti-IgE), montelukast, inhaled corticosteroids, and **desensitisation** shifting Th2 toward Th1/Treg.

### Autoimmunity

Autoimmunity needs **HLA susceptibility** + an **environmental trigger** (molecular mimicry — *S. pyogenes* M protein and cardiac myosin in rheumatic fever; post-viral bystander activation) + **loss of regulation** (Treg failure). Organ-specific disease (type 1 diabetes, Graves', myasthenia) tracks one antigen; systemic disease (SLE) tracks antigen present everywhere — nuclear material, hence anti-dsDNA and immune-complex nephritis.

### Transplant rejection

| Rejection | Timing | Mechanism | Prevention |
| --- | --- | --- | --- |
| **Hyperacute** | Minutes–hours | **Pre-formed antibody** against donor ABO/HLA → complement and thrombosis | **Cross-match** before transplant |
| **Acute** | Days–weeks | **CD8 CTL** against donor **MHC I**; **CD4** against donor **MHC II** | **HLA matching** (best at HLA-DR) + immunosuppression |
| **Chronic** | Months–years | Low-grade antibody and T-cell injury → graft vasculopathy, fibrosis | Long-term immunosuppression, BP and lipid control |

Immunosuppressants target the mechanism: **calcineurin inhibitors (ciclosporin, tacrolimus)** block the phosphatase activating **NFAT**, so **IL-2 is not transcribed** and T cells cannot proliferate; **mycophenolate** starves lymphocytes of guanine; **corticosteroids** suppress NF-κB broadly; **sirolimus** blocks mTOR downstream of IL-2. The cost is infection, opportunistic tumours (EBV-driven post-transplant lymphoproliferative disorder) and lost vaccine responses.

### Monoclonal antibodies and immunoglobulin replacement

Engineered IgG against one target: **adalimumab** (anti-TNF-α), **rituximab** (anti-CD20), **trastuzumab** (anti-HER2), **omalizumab** (anti-IgE), **checkpoints** (anti-PD-1/PD-L1) — infection and autoimmune side effects come from the pathway blocked. **Immunoglobulin replacement** (IV or subcutaneous IgG, ~400–600 mg/kg/month) supplies antibody where none is made, preventing infection and bronchiectasis but **creating no memory**, because memory needs surviving B cells.

### Why antibody cannot clear an intracellular infection

Antibody reaches extracellular fluid only: virus in the cytoplasm, *M. tuberculosis* in a macrophage vacuole, *Plasmodium* in a red cell are inaccessible. Clearance needs **CD8 T cells** to kill infected cells, **NK cells** where MHC I is lost, and **IFN-γ**-activated macrophages — so drugs must **penetrate cells** (six months of therapy for tuberculosis), antibody is adjunctive rather than curative, and AIDS patients reactivate infections a healthy host holds in check ([06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The receptor is made when the pathogen arrives" | **Clonal selection is the reverse**: a random repertoire exists first, and antigen *selects* the matching clone. Nothing is tailored to order. |
| "Innate and adaptive work independently" | They are a **relay**: innate buys time and presents antigen; antibody then accelerates phagocytosis and complement. |
| "Antibody can treat any infection" | Antibody works only **outside cells**; intracellular pathogens need CD8 T cells, NK cells and activated macrophages, plus drugs that enter cells. |
| "MHC I and II differ only in which cells carry them" | They differ in **peptide source and meaning**: I = intracellular peptide → CD8; II = extracellular peptide on APCs → CD4. |
| "A T cell activates on antigen alone" | It needs **two signals**; peptide without co-stimulation gives **anergy**, an autoimmunity safeguard. |
| "Fever means bacterial infection" | Fever is **cytokine-driven** (IL-1, IL-6, TNF-α → PGE₂ → hypothalamus); viral, fungal and sterile causes produce it too. |
| "IgM and IgG differ only in timing" | **IgM** is first, pentameric and best at complement; **IgG** is the main systemic antibody, opsonises and **crosses the placenta**. |
| "Vaccination treats infection" | Vaccination creates **memory without disease** — prophylactic only; post-exposure immunoglobulin is passive antibody, not vaccination. |
| "Hypersensitivity means allergy" | Only **type I is allergic (IgE)**; II is antibody on a cell, III is deposited complex, IV is **T-cell mediated and delayed**. |
| "Immunosuppression and tolerance are the same" | **Tolerance is antigen-specific**; immunosuppression hits everything, hence infection and cancer risk after transplantation. |
| "Neutrophils and macrophages are interchangeable" | **Neutrophils arrive first, are short-lived and make pus; macrophages are long-lived, resident, secrete cytokines and present antigen.** |

## Key facts

- **Three lines trade speed for specificity**: barriers immediate and unspecific, innate minutes and pattern-specific with **no memory**, adaptive days but epitope-specific **with memory**.
- **Clonal selection**: the repertoire is generated **before** antigen encounter; antigen selects and expands the matching clone — the basis of all vaccination.
- **Self versus non-self** is enforced centrally (**negative selection, AIRE**) and peripherally (**Treg, anergy**); failure gives autoimmunity, with **HLA alleles** setting genetic risk.
- **First line** = physical (keratinised skin, **mucociliary escalator**, flushing), chemical (**lysozyme**, **acid pH**, **defensins**), biological (**colonisation resistance**).
- **Phagocytosis**: attachment → ingestion → phagosome → **phagolysosome** → **NADPH oxidase/ROS** killing → peptide on **MHC II**. Oxidase defect = **chronic granulomatous disease**.
- **Inflammation**: vasodilation → redness/heat; permeability → oedema/pain; chemotaxis → recruitment; resolution is active, and systemic spread is **sepsis**.
- **Complement**: classical (**C1 + IgG/IgM**), alternative (**spontaneous C3b**), lectin (**mannose**) → **C3 convertase** → **C3b opsonisation**, **C3a/C5a anaphylatoxins**, **MAC (C5b-9) lysis** — countered by **factor H binding, C5a peptidase, sialic acid**.
- **NK cells** detect **missing self** (no MHC I) and kill by **perforin and granzymes**; they also perform **ADCC**, covering the blind spot of CD8 cells.
- **MHC I on all nucleated cells → CD8** (intracellular antigen); **MHC II on APCs → CD4** (extracellular). **Two signals** are required for activation — signal 1 alone gives anergy.
- **Antibody**: two heavy + two light chains, **variable** binding and **constant Fc** effector regions, flexible hinge. **IgM** first and best at complement; **IgG** main systemic and **placental**; **IgA** mucosal; **IgE** allergy and parasites; **IgD** the BCR.
- **Antibody functions**: neutralisation, opsonisation, complement activation, agglutination, ADCC — all restricted to **extracellular** targets.
- **Memory**: primary lags **7–14 days**, mostly low-affinity **IgM**; secondary is faster, larger, **high-affinity IgG** after **affinity maturation**.
- **Gell–Coombs**: I = IgE/mast cells; II = IgG on a cell surface; III = immune complexes; IV = T cells, delayed (contact dermatitis, tuberculin test).
- **Immunodeficiency**: primary is genetic (agammaglobulinaemia = no Btk → no antibody; SCID = no T and B; DiGeorge = no thymus); secondary is dominated by **HIV destruction of CD4 T cells**.

## Practice questions

**1. The principle of clonal selection is that**

A. Lymphocytes reshape their receptor to fit the antigen encountered
B. A diverse repertoire exists first, and antigen selects and expands the matching clone
C. Only B cells undergo clonal selection; T cells are selected independently
D. Memory cells arise during the innate response within minutes

**Answer: B**

Explanation: Rearrangement generates the repertoire **before** any exposure; antigen then selects the pre-existing cell whose receptor fits and drives it to divide. Receptor reshaping is the obsolete instructive theory, and T cells are selected the same way as B cells.

---

**2. A boy has no detectable immunoglobulins and recurrent sinopulmonary infections from 6 months of age. The defect is in**

A. Thymic epithelium development
B. Assembly of NADPH oxidase
C. B-cell maturation signalling through Btk
D. CD4 T-cell infection by a retrovirus

**Answer: C**

Explanation: **X-linked agammaglobulinaemia** blocks B-cell maturation at the pre-B stage, so no plasma cells appear once maternal IgG wanes at about 6 months. DiGeorge removes T cells, CGD impairs phagocyte killing, and HIV is acquired rather than presenting in infancy with all immunoglobulin classes absent.

---

**3. In phagocytosis, the step immediately before killing by the oxidative burst is**

A. Attachment through opsonin receptors
B. Fusion of the phagosome with lysosomes
C. Loading of peptide onto MHC class I
D. Chemotaxis along a C5a gradient

**Answer: B**

Explanation: Killing occurs inside the **phagolysosome**, where lysosomal enzymes and acidification combine with NADPH oxidase–derived reactive oxygen species. Attachment and chemotaxis are earlier, and peptide is loaded onto **MHC II** after killing, not onto class I.

---

**4. The terminal complex that lyses a Gram-negative organism in the bloodstream is**

A. C1q bound to mannose residues
B. C3bBb, the alternative pathway C3 convertase
C. C5b–9, the membrane attack complex
D. Factor B complexed with properdin

**Answer: C**

Explanation: All three pathways converge on C3 convertase, after which C5b recruits C6, C7, C8 and multiple C9 to form the **membrane attack complex**, a pore causing osmotic lysis. C1q initiates the classical pathway and C3bBb is the alternative convertase — neither lyses directly.

---

**5. A virus-infected cell that has lost MHC class I will most directly be recognised by**

A. CD4 helper T cells reading MHC class II
B. NK cells through loss of inhibitory "missing-self" signalling
C. B cells through surface immunoglobulin
D. Neutrophils through mannose-binding lectin

**Answer: B**

Explanation: MHC class I normally delivers an **inhibitory** signal to NK cells, so its disappearance withdraws inhibition and the cell is killed by perforin and granzymes. CD8 cytotoxic cells, by contrast, **require** class I to see a target — which is exactly why the two systems complement each other.

---

**6. Which pairing of MHC class, peptide source and T-cell subset is correct?**

A. Class I — extracellular peptide — CD4 helper T cells
B. Class II — cytosolic peptide — CD8 cytotoxic T cells
C. Class I — proteasome-derived intracellular peptide — CD8 cytotoxic T cells
D. Class II — peptide loaded in the ER by TAP — CD8 cells

**Answer: C**

Explanation: Class I sits on all nucleated cells, presents **intracellular** peptide processed by the proteasome and loaded by **TAP**, and is read by **CD8**; class II is on APCs, presents **vesicular** peptide, and is read by **CD4**. Options A, B and D all invert one half of the pairing.

---

**7. A conjugate vaccine works in infants where a plain polysaccharide vaccine does not because conjugation**

A. Makes the vaccine live and able to replicate
B. Adds toxoid so that antitoxin antibody is produced
C. Makes the response T-dependent by presenting carrier-protein peptide on MHC II, giving CD4 help, class switching and memory
D. Allows the polysaccharide to bypass antigen-presenting cells

**Answer: C**

Explanation: Polysaccharides are **T-independent** — no T-cell help, no germinal centres, no memory, and a poor response in under-2s. Linking one to a carrier protein makes APCs present that protein's peptide on **MHC II**, recruiting CD4 help and producing class switching, affinity maturation and lasting memory.

---

**8. Four days after starting a drug a patient develops a painful swollen wrist with low serum C3. This is**

A. Type I — IgE cross-linking on mast cells
B. Type II — IgG directed at synovial cell surfaces
C. Type III — deposited antigen–antibody complexes activating complement
D. Type IV — drug-specific memory T cells

**Answer: C**

Explanation: **Serum sickness** is the archetype: soluble drug–antibody complexes deposit in vessels and joints, **consume complement** (hence low C3) and recruit neutrophils that damage tissue. Type I would be immediate, type IV would be delayed but without complement consumption, and type II requires antibody against a fixed cell-surface antigen.

---

**9. The correct contrast between primary and secondary antibody responses is that the primary**

A. Peaks sooner and produces mainly high-affinity IgG
B. Lags 7–14 days and is mainly IgM, whereas the secondary is faster, larger and mainly high-affinity IgG
C. Is produced by memory cells that expand immediately
D. Has equal affinity because somatic hypermutation occurs only in memory cells

**Answer: B**

Explanation: A first encounter requires selection and expansion, so the **lag is 7–14 days** and the antibody is mostly **low-affinity IgM**; memory cells skip that learning phase, giving a response in **1–3 days** that is larger, class-switched to **IgG** and higher affinity.

---

**10. Antibody therapy cannot clear chronic *Mycobacterium tuberculosis* infection because**

A. Mycobacteria are too large to be agglutinated
B. The bacillus survives inside macrophage phagosomes where antibody cannot reach, so clearance requires CD4-driven macrophage activation
C. Mycobacterial proteases digest antibody in the bloodstream
D. Tuberculosis provokes no antibody response at all

**Answer: B**

Explanation: Immunoglobulin acts only in extracellular fluid, while *M. tuberculosis* prevents its phagosome from acidifying and persists inside macrophage; control therefore needs **Th1/IFN-γ activation** and granuloma formation, plus drugs that enter cells. Antibody is produced in this infection, is not selectively destroyed, and agglutination is irrelevant to an intracellular niche.
