# The Urinary System

## Why it matters

The kidney is the body's **precision filtration-and-correction plant**: it filters the entire blood volume about **36 times a day**, reclaims **99% of what it filtered**, then chemically adjusts what remains. Nothing here is a new kind of transport — every step is **diffusion, osmosis, facilitated transport, or ATP-driven pumping** applied in a fixed sequence along a tube, under hormonal control ([02 — Passive transport](../03-cellular-processes/02-passive-transport.md), [03 — Active transport](../03-cellular-processes/03-active-transport.md)).

The design logic is **filter cheaply, then reclaim selectively**: build a non-selective, protein-free copy of plasma, then spend energy reabsorbing only what the body wants. Molecules cannot be picked out of whole blood directly; they are dumped into a tube and taken back one by one.

This also makes the kidney the **master regulator of blood pressure, blood pH, and blood volume simultaneously** — three homeostatic variables no other organ can substitute for.

| Variable defended | Main renal lever | Speed |
| --- | --- | --- |
| **Blood pressure and volume** | Na⁺ (and therefore water) excreted or retained | Minutes (nerves) to days (RAAS) |
| **Blood pH** (7.35–7.45) | H⁺ secreted, HCO₃⁻ reclaimed or generated | Hours to days |
| **Plasma osmolality** (~285–295 mOsm/kg) | Water reabsorbed independently of solute (ADH) | Minutes |

The three are inseparable: **sodium sets extracellular volume, volume sets pressure, and H⁺ is handled alongside Na⁺ in the same cells**. Hence the section rule — **structure → function → mechanism → regulation → homeostasis** — matters here more than anywhere: know which cell sits where, then what moves, then what changes the movement. Control-loop components are analysed in [03 — Homeostasis: the full control loop](../09-human-biology/03-homeostasis-control-loop.md).

## Anatomy: from kidney to nephron

### Gross structure — plumbing in series

| Structure | Key features | Function |
| --- | --- | --- |
| **Kidney** (×2) | ~150 g each; **cortex** outer, **medulla** inner as 8–18 **pyramids**; vessels enter at the **hilum** | Filtration, reabsorption, secretion, endocrine output |
| **Renal pelvis** | Funnel from minor and major **calyces** collecting urine at each papilla | Collection |
| **Ureter** (×2) | ~25–30 cm, peristaltic smooth muscle, **3 constrictions** | Propels urine — by peristalsis, not gravity |
| **Bladder** | Distensible detrusor, ~400–600 mL capacity | Storage |
| **Urethra** | Male ~20 cm (three parts); female **~4 cm** | Conduit; sphincters guard continence |

Urine flows one way because peristalsis pushes it forward and the **vesicoureteric valves close as the bladder fills** — so over-distension or reflux risks carrying bacteria back toward the kidney.

### The nephron: the functional unit

Each kidney holds **~1.2 million nephrons**; each is one continuous tube.

```
BLOOD → AFFERENT ARTERIOLE → GLOMERULUS        (filtration, ~55 mmHg)
              ↓
       BOWMAN'S CAPSULE → PROXIMAL CONVOLUTED TUBULE   (cortex)
              ↓
       LOOP OF HENLE — descends into the MEDULLA, returns
              ↓
       DISTAL CONVOLUTED TUBULE                (cortex)
              ↓
       COLLECTING DUCT — cortical → medullary  (shared by many nephrons)
              ↓
       PAPILLA → CALYX → PELVIS → URETER → BLADDER
```

| Segment | Location | Structural feature | Function |
| --- | --- | --- | --- |
| **Renal corpuscle** (glomerulus + Bowman's capsule) | Cortex | Fenestrated capillary tuft inside a capsular cup | Bulk, non-selective **filtration** |
| **Proximal convoluted tubule (PCT)** | Cortex | **Brush border**, crowded mitochondria | Mass reabsorption and secretion — the **workhorse** |
| **Loop of Henle** | Cortex → medulla → cortex | Descending, thin ascending, thick ascending limbs | Build the **medullary osmotic gradient** |
| **Distal convoluted tubule (DCT)** | Cortex | Short, few microvilli | Hormone-controlled **fine tuning** |
| **Collecting duct** (cortical → outer → inner medullary) | Cortex + medulla | **Principal cells** and **intercalated cells** | **Final** water, Na⁺, K⁺, H⁺ decision |

**Cortical nephrons** (~85%, short loops) do routine work; **juxtamedullary nephrons** (long loops deep into the medulla) generate the steep gradient that makes concentrated urine possible. The **vasa recta** run as hairpin loops beside those long loops, and **peritubular capillaries** recapture reabsorbed fluid — reabsorbed water must be returned to the blood, not left in tissue.

### The juxtaglomerular apparatus: the sensor

Where the DCT loops back to touch its own glomerulus, three cell types form the **juxtaglomerular apparatus (JGA)** — the kidney's self-contained control panel.

| Component | Location | Senses | Response |
| --- | --- | --- | --- |
| **Macula densa** | DCT wall apposed to the arteriole | **NaCl delivery** in tubular fluid | Low NaCl → signals renin release, dilates afferent arteriole; high NaCl → constricts it (**tubuloglomerular feedback**) |
| **Granular (juxtaglomerular) cells** | Wall of the **afferent arteriole** | **Stretch / perfusion pressure** | Low stretch → **renin** secretion |
| **Extraglomerular mesangial cells** | Between arteriole and macula densa | Signals from both | Relay |

A pressure sensor and a chemical sensor wired to one effector (renin), inside the organ being controlled.

## Filtration: the arrow chain

Filtration is **bulk flow driven by hydrostatic pressure** — the Starling logic of a systemic capillary, except that two arterioles in series hold the bed at arterial pressure.

```
AFFERENT ARTERIOLE (wide) → GLOMERULAR CAPILLARY, ~55 mmHg
        ↓  THE DRIVER: an arteriole upstream AND an arteriole (efferent) downstream
FILTRATION MEMBRANE: fenestrated endothelium → basement membrane → podocyte slit diaphragms
        ↓  PASSES: water, Na⁺, K⁺, Cl⁻, glucose, amino acids, urea, HCO₃⁻, H⁺
        ↓  BLOCKS: cells, platelets, plasma proteins (albumin is the test case)
BOWMAN'S CAPSULE SPACE = PROXIMAL TUBULAR FLUID = PLASMA MINUS PROTEIN
        ↓
PROXIMAL CONVOLUTED TUBULE begins reclamation
```

### The three forces: net filtration pressure

| Force | Approx. value | Direction |
| --- | --- | --- |
| **Glomerular hydrostatic (P_GC)** | **~55 mmHg** | **Out — drives filtration** |
| **Capsular hydrostatic (P_BS)** | ~15 mmHg | Opposes |
| **Blood colloid osmotic (π_GC)** | ~26 mmHg (albumin) | Opposes |
| Capsular colloid osmotic | ~0 (no protein crosses) | Negligible |

```
NFP = P_GC − (P_BS + π_GC) = 55 − (15 + 26) ≈ 15 mmHg
```

Unlike a systemic capillary, **filtration occurs along the whole glomerular length** because P_GC starts so high ([05 — Cardiovascular system](05-cardiovascular-system.md)). Because π_GC opposes filtration, **falling albumin raises NFP** while also removing the oncotic force that holds fluid in the capillary — the double insult behind oedema in nephrotic syndrome.

### The filtration membrane: size AND charge

| Layer | Structure | Barrier role |
| --- | --- | --- |
| **Fenestrated endothelium** | Pores 70–100 nm | Excludes cells — the coarsest sieve |
| **Glomerular basement membrane** | Collagen IV, laminin, proteoglycans | Traps large proteins; **heparan sulphate gives strong negative charge** |
| **Podocyte slit diaphragms** | Foot processes linked by **nephrin, podocin** | Final size sieve; nephrin loss → massive proteinuria |

Two independent properties: **size** and **fixed charge**. Albumin (6.9 nm) could squeeze through on size alone, but at blood pH it is strongly **negative** and is electrostatically repelled. Disease can therefore spill protein **without enlarging pores** — minimal change disease destroys the charge barrier only.

### GFR: worked calculation

**GFR** is the volume filtered per minute: ~**125 mL/min** in a healthy young adult.

```
1. Per day
     125 mL/min × 1,440 min = 180,000 mL = 180 L/day

2. What is excreted
     Urine ≈ 1.5 L/day → 180 − 1.5 = 178.5 L reabsorbed → 99.2% RECLAIMED

3. Filtration fraction (FF)
     Renal plasma flow ≈ 600 mL/min
     FF = GFR ÷ RPF = 125 ÷ 600 ≈ 0.21 → ~21% of plasma filtered per pass

4. Filtered load of glucose
     125 mL/min × 1.0 mg/mL ≈ 125 mg/min   Tm ≈ 375 mg/min
     125 < 375 → NORMAL URINE CONTAINS NO GLUCOSE
```

Three numbers to carry: **125 mL/min, 180 L/day, ~20% filtration fraction**. Because GFR is the single best index of renal function, it is estimated clinically from **creatinine clearance** and reported as eGFR.

### Determinants and autoregulation

| Determinant | Change | Effect on GFR |
| --- | --- | --- |
| **Afferent tone** | Constriction (sympathetic, angiotensin II, NSAIDs) | ↓ GFR |
| **Efferent tone** | Mild constriction (angiotensin II) | NFP ↑ → GFR defended; severe → ↓ GFR |
| **Systemic pressure** | Outside the autoregulatory range | GFR follows pressure |
| **Plasma albumin** | Falls (nephrotic syndrome) | Barrier damage dominates → proteinuria |
| **Capsular/ureteric pressure** | Obstruction (stone, enlarged prostate) | ↓ NFP → ↓ GFR |

**Autoregulation** holds GFR nearly constant as mean arterial pressure swings **~80–180 mmHg**:

```
MYOGENIC:    ↑ MAP → afferent smooth muscle STRETCHED → reflex CONTRACTION
             → less pressure transmitted to glomerulus → GFR unchanged

TUBULOGLOMERULAR FEEDBACK (the JGA):
   ↑ GFR → more NaCl at MACULA DENSA → AFFERENT CONSTRICTION → GFR returns to normal
   ↓ GFR → less NaCl at macula densa → AFFERENT DILATION + RENIN → GFR restored
```

Both are **intrinsic negative-feedback loops with receptor, controller, and effector inside one organ**. Beyond the autoregulatory window (haemorrhage, shock) they are overwhelmed and GFR falls with perfusion — which is why **prerenal failure is a flow problem, not a structural one**.

### Transport maximum: why glucose appears in urine

Glucose is filtered, then reclaimed by **sodium–glucose linked transporters (SGLT2 early PCT, SGLT1 late PCT)** — secondary active transport riding the Na⁺ gradient set by the basolateral Na⁺/K⁺-ATPase ([03 — Active transport](../03-cellular-processes/03-active-transport.md)):

```
FILTERED LOAD rises (plasma glucose ↑, as in diabetes mellitus)
        ↓
SGLT CARRIERS SATURATE — every carrier occupied  →  Tm ≈ 375 mg/min
        ↓  (reached at ~180 mg/dL plasma glucose = RENAL THRESHOLD; "splay" because carriers
        ↓   do not all saturate at once)
EXCESS GLUCOSE STAYS IN THE TUBE → GLYCOSURIA → osmotic diuresis (water follows sugar)
```

Glycosuria is therefore **not proof of diabetes**: it also appears when the filtered load outruns carriers — including patients deliberately given **SGLT2 inhibitors** to spill glucose and lower blood sugar.

## Tubular reabsorption and secretion: segment by segment

Filtration is only the opening move. This table is the chapter's spine — **what moves, how, and where it ends up**.

| Segment | Reabsorbed | Secreted into lumen | Mechanism |
| --- | --- | --- | --- |
| **PCT** | ~65% Na⁺ and water; ~100% glucose and amino acids; 80–90% HCO₃⁻; phosphate, K⁺, Cl⁻, citrate | **H⁺, K⁺**, creatinine, drugs, organic anions/cations | Na⁺/glucose and Na⁺/amino-acid **co-transport**, Na⁺/H⁺ exchange, Na⁺/K⁺-ATPase, **bulk flow (solvent drag)**, carbonic anhydrase |
| **Descending limb** | **Water** | — | Osmosis via **aquaporin-1** into the salty medulla |
| **Thin ascending** | NaCl | — | **Passive** diffusion out; water cannot follow |
| **Thick ascending** | Na⁺, K⁺, 2Cl⁻, Ca²⁺, Mg²⁺ | — | **NKCC2** symport; **impermeable to water** → dilutes fluid, builds gradient |
| **DCT** | Na⁺/Cl⁻ (NCC), Ca²⁺ (PTH-driven) | H⁺, K⁺ | Na⁺/Cl⁻ symport (**thiazide**-sensitive) |
| **Collecting duct — principal cells** | Na⁺ (**ENaC**), water (**AQP2**), urea | **K⁺** (ROMK) | **Aldosterone** opens ENaC; **ADH** inserts aquaporin-2 |
| **Collecting duct — intercalated cells** | HCO₃⁻ (type B) | **H⁺** (H⁺-ATPase) | Proton pumps — acid–base finishing control |

### Proximal convoluted tubule: reclaim most of it

Three structural facts explain the capacity: the **brush border** multiplies apical surface ~40-fold; **crowded mitochondria** fuel the Na⁺/K⁺-ATPase, giving the kidney a high oxygen demand per gram ([04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md)); and **leaky junctions** let solvent drag do much of the work for free. Because the PCT reclaims **obligatory** quantities whatever the hydration state, it cannot be diuresed.

### Loop of Henle: the countercurrent multiplier

The medulla must reach **300 → 1,200 mOsm/kg** before the collecting duct can reabsorb water against a gradient. The loop builds this by **repeating a small single effect and multiplying it along the axis** — the **countercurrent multiplier**.

```
DESCENDING LIMB — permeable to WATER, not salt
        ↓  water leaves by OSMOSIS into the salty interstitium (300 → 1,200 mOsm/kg)
        ↓  filtrate becomes MORE concentrated — maximal at the hairpin bend

THIN ASCENDING — permeable to SALT, not water → NaCl diffuses out, fluid starts to dilute

THICK ASCENDING — ACTIVE Na⁺/K⁺/2Cl⁻ (NKCC2), WATER IMPERMEABLE
        ↓  THE SINGLE EFFECT: salt out, no water follows → interstitium made salty
        ↓  tubular fluid falls to ~100 mOsm → the "diluting segment"
```

Because this limb is **water-impermeable, dilution and gradient production are the same event**. **Furosemide (frusemide)** blocks NKCC2: salt stays in the tubule, water cannot follow it out, the gradient collapses, and a large volume of dilute urine results — the strongest common diuretic works by disabling the gradient machine.

### Vasa recta: the countercurrent exchanger

A gradient must not be washed away by the blood passing through it. The **vasa recta** solve this by **equilibrating rather than flushing**:

| Flow | What happens |
| --- | --- |
| **Descending** into medulla | Water leaves; salt and urea enter → blood concentrates |
| **Hairpin turn** | Maximally concentrated, fully equilibrated with interstitium |
| **Ascending** out | Salt and urea leave; water re-enters → blood leaves only **slightly** hyperosmotic |

Slow flow and long hairpins maximise exchange, so **solute stays in the medulla**. The same arrangement traps oxygen, which is why the medulla is hypoxic and the thick ascending limb — its main consumer — is the segment first injured by ischaemia.

### Distal tubule and collecting duct: hormonal fine tuning

The late DCT and collecting duct decide minute by minute **how much water to give back**:

```
PLASMA OSMOLALITY RISES (dehydration, salty meal)
        ↓  hypothalamic OSMORECEPTORS → posterior pituitary releases ADH
ADH binds V2 on PRINCIPAL CELLS → cAMP cascade
        ↓  AQUAPORIN-2 vesicles FUSED into the apical membrane
        ↓  an otherwise impermeable wall now passes water → follows NaCl and urea
        ↓  SMALL, CONCENTRATED URINE → plasma osmolality falls

NO ADH → collecting duct stays IMPERMEABLE → LARGE, DILUTE URINE
```

| Hormone | Source | Renal action | Net effect |
| --- | --- | --- | --- |
| **ADH (vasopressin)** | Posterior pituitary | V2 → cAMP → **aquaporin-2 insertion**; ↑ urea permeability | Water retained → concentrated urine |
| **Aldosterone** | Zona glomerulosa | **ENaC** opens, Na⁺/K⁺-ATPase drives Na⁺ in, **K⁺ secreted** | Na⁺ (and water) retained, K⁺ lost |
| **Angiotensin II** | RAAS cascade | Stimulates Na⁺/H⁺ exchange, efferent constriction, aldosterone and ADH release | Na⁺/water retention, GFR defended |
| **ANP** | Atrial wall on stretch | **Opposes aldosterone** — inhibits Na⁺ reabsorption, suppresses renin | Na⁺ and water excreted, pressure ↓ |
| **Parathyroid hormone** | Parathyroid glands | ↑ DCT Ca²⁺ reabsorption, ↑ phosphate excretion | Ca²⁺ retained, phosphate lost |

**Final urine volume and concentration are decided here, not at the glomerulus**: GFR sets what is offered; ADH and aldosterone set what is taken back.

## Regulation: pressure, salt, and water

### The renin–angiotensin–aldosterone system

```
↓ RENAL PERFUSION / ↓ NaCl AT MACULA DENSA / β₁ SYMPATHETIC DRIVE
        ↓  GRANULAR (JUXTAGLOMERULAR) CELLS RELEASE RENIN
RENIN: angiotensinogen (LIVER) → ANGIOTENSIN I
        ↓  ACE on PULMONARY ENDOTHELIUM → ANGIOTENSIN II
ANGIOTENSIN II
   ├→ vasoconstriction → TPR ↑ → BP ↑
   ├→ EFFERENT constriction → NFP ↑ → GFR maintained
   ├→ PCT Na⁺/H⁺ exchange ↑ → Na⁺ and HCO₃⁻ reabsorbed
   ├→ ALDOSTERONE → ENaC → Na⁺/water retained, K⁺ secreted
   ├→ ADH release and hypothalamic THIRST
   └→ facilitates noradrenaline release
VOLUME and PRESSURE RISE → macula densa sees more NaCl → RENIN SWITCHED OFF
```

The loop works over **hours to days**, unlike the baroreflex which corrects in a beat ([05 — Cardiovascular system](05-cardiovascular-system.md)). Two renal facts make it the long-term pressure controller: **pressure natriuresis** (raised arterial pressure directly makes the kidney excrete more Na⁺ and water) and aldosterone, which sets how much filtered salt is kept. Remove the kidney's ability to excrete salt and hypertension becomes essentially unfixable.

**Sympathetic fibres** innervate both arterioles, the JGA, and PCT cells; severe drive constricts the afferent arteriole and cuts GFR — appropriate in haemorrhage, where perfusing brain and heart outranks urine production ([03 — Nervous system](03-nervous-system.md)). Prolonged shock therefore causes acute tubular necrosis: the kidney is deliberately sacrificed to defend pressure, then injured by the resulting ischaemia.

## Acid–base: the slow, permanent fix

Blood pH is defended at three speeds — fast chemical buffers, the **minutes-fast lung**, and the **hours-to-days-slow kidney**. Only the kidney removes acid from the body permanently and rebuilds bicarbonate ([06 — Acids, bases, and pH](../00-foundations/06-acids-bases-and-ph.md)); the lung changes CO₂ and nothing else ([06 — Respiratory system](06-respiratory-system.md)).

```
H⁺ SECRETED THROUGHOUT THE TUBULE (PCT: Na⁺/H⁺ exchange; collecting duct: H⁺-ATPase)
        ↓
FILTERED BICARBONATE RECLAIMED (PCT, ~80–90%):
   H⁺ + HCO₃⁻ → CO₂ + H₂O (carbonic anhydrase) → CO₂ enters cell → HCO₃⁻ back to blood
        ↓  NOTE: this RECLAIMS base — it does not yet create NEW base

NEW BASE IS MADE TWO WAYS:
   • TITRATABLE ACID — H⁺ + HPO₄²⁻ → H₂PO₄⁻  (urine pH falls)
   • AMMONIUM — glutamine metabolised in PCT → NH₄⁺ secreted
                → in the MEDULLA: NH₃ + H⁺ → NH₄⁺  (diffusion trapping — cannot leave)
                → excreted with Cl⁻; output RISES markedly in chronic acidosis
```

**Net acid excretion = titratable acid + ammonium − filtered bicarbonate that escapes.** Two consequences: reabsorbing filtered bicarbonate **regenerates but does not create** buffer, so renal failure loses both the capacity to excrete H⁺ and to make new base; and because **ammonium generation is the scalable lever**, chronic metabolic acidosis is corrected by upregulating ammoniagenesis over days.

| Disturbance | Renal compensation | Speed |
| --- | --- | --- |
| Respiratory acidosis (retained CO₂) | ↑ HCO₃⁻ reabsorption, ↑ NH₄⁺ | Hours to days |
| Respiratory alkalosis (blown-off CO₂) | ↓ HCO₃⁻ reabsorption, HCO₃⁻ lost in urine | Hours to days |
| Metabolic acidosis | ↑ H⁺ and NH₄⁺ excretion, new HCO₃⁻ made | Hours to days |
| Metabolic alkalosis | ↓ H⁺ excretion, HCO₃⁻ lost | Hours to days |

Respiratory compensation changes the Henderson–Hasselbalch ratio **without removing the acid load**; only renal correction changes the denominator permanently.

## Other functions of the kidney

| Function | Mechanism | Lost → |
| --- | --- | --- |
| **Erythropoiesis control** | Peritubular fibroblasts sense hypoxia (HIF) → **erythropoietin (EPO)** → marrow makes RBCs | **Anaemia of chronic kidney disease** ([05 — Cardiovascular system](05-cardiovascular-system.md)) |
| **Vitamin D activation** | PCT **1α-hydroxylase** → **1,25-(OH)₂ calcitriol** → gut absorbs Ca²⁺ | Hypocalcaemia, secondary hyperparathyroidism, renal osteodystrophy ([01 — Skeletal system](01-skeletal-system.md)) |
| **Gluconeogenesis** | PCT makes glucose from lactate, glycerol, amino acids in **prolonged fasting** or acidosis | Loss of a real glucose source during starvation ([07 — Digestive system](07-digestive-system.md)) |
| **Waste disposal** | **Urea** (hepatic amino-acid deamination), **creatinine** (muscle turnover), uric acid — filtered and partly secreted | **Uraemia** |
| **GFR marker** | **Inulin** = true GFR (filtered, neither reabsorbed nor secreted); **creatinine** is slightly secreted, so its clearance **overestimates** GFR | Falling eGFR stages the disease |

## Micturition: storage and emptying

The bladder is a **volume-storage organ with a two-sphincter guard**, and voiding is a spinal reflex the brain permits rather than commands.

| Structure | Tissue | Innervation | Role |
| --- | --- | --- | --- |
| **Detrusor** | Smooth muscle | **Parasympathetic M₃** (pelvic, S2–S4) contracts; sympathetic β₃ relaxes | Expulsion |
| **Internal sphincter** (bladder neck) | Smooth muscle | Sympathetic **α₁** (T11–L2) contracts | Involuntary closure |
| **External sphincter** | **Skeletal muscle** | Somatic **pudendal nerve** (Onuf's nucleus) | Voluntary closure |
| **Pontine micturition centre** | Pons | Coordinates storage ↔ voiding | ([03 — Nervous system](03-nervous-system.md)) |

```
STORAGE: filling → stretch receptor firing LOW
   sympathetic → detrusor RELAXES (β₃), internal sphincter CONTRACTS (α₁)
   somatic → external sphincter voluntarily CONTRACTED → CONTINENCE

THRESHOLD (~300–400 mL)
   stretch receptors FIRE → afferent pelvic nerves → SACRAL CORD
        ↓  pons gives the go-ahead if socially convenient
PARASYMPATHETIC OUT → detrusor CONTRACTS (M₃) + internal sphincter RELAXES
        ↓  somatic output to external sphincter WITHDRAWN → outlet opens
BLADDER PRESSURE > URETHRAL PRESSURE → VOIDING → stretch falls → reflex switches off
```

Continence needs **three simultaneous conditions**: relaxed detrusor, closed internal sphincter, voluntarily closed external sphincter. Failure of each gives a characteristic pattern — detrusor overactivity → urge incontinence; sphincter weakness → stress incontinence; **detrusor–sphincter dyssynergia** (sphincter firing while the detrusor contracts, typical of suprasacral spinal cord injury) → high-pressure voiding, reflux, infection. Infants void by reflex because cortical inhibition is not yet myelinated.

## Homeostasis: three variables, one organ

| Element | Volume / pressure | Osmolality | pH |
| --- | --- | --- | --- |
| **Detector** | Baroreceptors; JGA macula densa and granular cells | Hypothalamic osmoreceptors | Renal tubular cells; chemoreceptors |
| **Effector** | Arteriolar tone, ADH, aldosterone, ANP | **ADH → aquaporin-2** in collecting duct | **H⁺ pumps**, ammoniagenesis; lungs for fast compensation |
| **Response** | Na⁺/water retained or excreted → pressure returns | Water reabsorbed → osmolality returns | H⁺ excreted, new base made → pH returns |
| **Speed** | Seconds (baroreflex) → days (RAAS, pressure natriuresis) | Minutes | Hours to days (renal); minutes (respiratory) |

```
DEHYDRATION
   ↓  ↑ plasma osmolality + ↓ volume + ↓ pressure
   → osmoreceptors and JGA fire → ADH + RAAS + thirst all engaged
   → aquaporin-2 inserted, ENaC opens, salt and water retained
   → small dark urine → variables RETURN TO SET POINT → secretion switches off
```

**One stimulus recruits all three loops at once** — the redundancy is deliberate.

## Medical relevance

**Chronic kidney disease (CKD) is the slow loss of nephrons and therefore of every renal function at once.** GFR falls progressively (staged ≥90 down to <15 mL/min) and the consequences follow the job table: retained urea, creatinine, K⁺, H⁺, and phosphate produce **uraemia** (fatigue, nausea, encephalopathy, bleeding tendency); lost EPO gives anaemia; lost 1α-hydroxylase gives renal bone disease; failed Na⁺ and water handling gives oedema and hypertension. **Dialysis substitutes for filtration by diffusion across a semipermeable membrane** — no ATP, no transporter, just the concentration-gradient physics of ordinary membrane transport ([02 — Passive transport](../03-cellular-processes/02-passive-transport.md)):

| Modality | Membrane | Mechanism |
| --- | --- | --- |
| **Haemodialysis** | Synthetic dialysis membrane | Blood one way, dialysate the other; **urea and K⁺ diffuse down their gradients**, ultrafiltration removes excess water; ~3× weekly |
| **Peritoneal dialysis** | Patient's own peritoneum | Dialysate instilled in the abdomen; continuous exchange across peritoneal capillaries |

Diffusion only works down a gradient, so **clearance depends on flow rate, membrane area, and time** — which is why residual renal function still matters.

**Kidney stones (nephrolithiasis) are a crystallisation problem, not an infection.** Urine becomes **supersaturated** with calcium oxalate (most common), calcium phosphate, uric acid, or struvite; crystals aggregate and lodge in a ureter, and pain comes from ureteric spasm against an unyielding stone. Two preventive levers follow directly from the chemistry: **dilution** (high fluid intake keeps concentration below saturation) and **pH** (uric acid dissolves poorly in acidic urine, so alkalinising helps uric acid stones, while calcium phosphate forms more readily in alkaline urine). Risk rises with hypercalciuria, hyperparathyroidism, low citrate (a natural inhibitor), and urinary stasis.

**Urinary tract infection is an ascending infection, and anatomy explains who gets it.** *Escherichia coli* from normal perianal flora climbs **faecal flora → urethra → bladder (cystitis) → ureter (pyelonephritis)** ([07 — Bacterial structure and physiology](../07-microbiology/01-bacterial-structure-and-physiology.md)). The female urethra is **~4 cm against the male ~20 cm** and sits close to the vaginal and anal openings, so bacteria travel a much shorter distance — the entire anatomical reason for female predominance in UTI. Other risks are mechanical or functional: incomplete emptying, catheters (biofilm), vesicoureteric reflux in children, and stones giving bacteria a protected surface. Host defences — voiding flush, mucosal IgA, urine acidity — are defeated by stasis ([07 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md)).

**RAAS pharmacology works by interrupting one arrow of the cascade**, and every agent's adverse effect is a prediction of what its target segment normally does:

| Drug | Target | Mechanism | Characteristic adverse effect |
| --- | --- | --- | --- |
| **ACE inhibitors** (ramipril) | Angiotensin-converting enzyme | ↓ Ang II; **bradykinin not degraded** | Dry **cough**; angioedema; hyperkalaemia; GFR falls if both renal arteries stenosed |
| **ARBs** (losartan) | AT₁ receptor | Block Ang II directly — without the bradykinin effect | Hyperkalaemia; no cough |
| **Furosemide (frusemide)** | **NKCC2**, thick ascending limb | Blocks salt reabsorption, collapses the medullary gradient | Hypokalaemia, hypomagnesaemia, ototoxicity |
| **Spironolactone** | **Aldosterone** receptor | Blocks ENaC action → Na⁺ lost, K⁺ **retained** | **Hyperkalaemia**; gynaecomastia |
| **Thiazides** | **NCC** in the DCT | Blocks Na⁺/Cl⁻ co-transport | Hypokalaemia, hypercalciuria |
| **SGLT2 inhibitors** | SGLT2 in the PCT | Blocks glucose reclamation → glycosuria and osmotic diuresis | Genital mycotic infection, volume depletion |

**SIADH and diabetes insipidus are ADH excess versus ADH absence — opposite ends of one axis.**

| Feature | **SIADH** (excess ADH) | **Diabetes insipidus** (ADH absent or ignored) |
| --- | --- | --- |
| ADH | Inappropriately high | **Central**: not produced; **nephrogenic**: collecting duct unresponsive (lithium, hypokalaemia, V2 mutations) |
| Water balance | Retained | Lost — **polyuria**, often >3–5 L/day |
| Urine | **Concentrated** despite low plasma osmolality | Maximally **dilute** (<300 mOsm/kg) |
| Plasma sodium | **Dilutional hyponatraemia** (<135 mmol/L), euvolaemic | **Hypernatraemia** if thirst cannot match losses |
| Driver of symptoms | Water intoxication: headache, confusion, seizures | Intense **polydipsia**, nocturia, dehydration |

The mechanism of **dilutional hyponatraemia** is that SIADH adds **pure water** to a fixed sodium pool: total body Na⁺ is normal, but concentration falls because volume rose — so saline alone can worsen it.

**Rhabdomyolysis links skeletal muscle directly to kidney injury.** Massive muscle breakdown releases **myoglobin** ([02 — Muscular system](02-muscular-system.md)); it is filtered freely, and in acidified, concentrated PCT fluid it precipitates, obstructs tubules, scavenges nitric oxide, and generates oxidative damage — **acute kidney injury with dark, cola-coloured urine**. Dehydration and the acidosis of crush injury aggravate all three mechanisms, so aggressive intravenous fluid is the primary preventive treatment.

**Hypertension is both cause and consequence of renal failure — a self-amplifying loop.** Raised pressure damages glomerular capillaries and causes **glomerulosclerosis**, which lowers functioning nephron mass, which reduces pressure-natriuresis excretion, which raises pressure further; in parallel, ischaemic nephrons secrete more renin. This is why hypertension is a leading cause of end-stage renal disease worldwide, and why a patient presenting with both must be treated for both — one direction of the loop does not close on its own.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The kidney filters blood and keeps what it wants" | It filters **180 L/day of protein-free plasma** and reclaims **99%**; filtration is non-selective, and selectivity is imposed afterwards by tubular transporters |
| "Glucose in urine means diabetes mellitus" | Glycosuria appears whenever filtered load exceeds **Tm ~375 mg/min** — heavy carbohydrate loads, pregnancy, and **SGLT2 inhibitors** all cause it |
| "Filtration pressure is just systemic blood pressure" | NFP = P_GC − (P_BS + π_GC) ≈ **15 mmHg**; the glomerulus is held at ~55 mmHg by **two arterioles in series**, not by transmitted arterial pressure |
| "The loop of Henle reabsorbes water in both limbs" | Only the **descending limb** is water-permeable; the **thick ascending limb is water-impermeable** — it dilutes fluid precisely by moving salt without water |
| "ADH increases filtration" | ADH does not change GFR — it inserts **aquaporin-2** into the collecting duct, so more of the same filtrate is reabsorbed |
| "Reabsorbing bicarbonate creates new base" | It only **reclaims filtered bicarbonate**; new base requires **titratable acid and ammonium excretion**, the levers that fail first in renal failure |
| "Renin is an adrenal hormone" | **Renin comes from granular cells of the afferent arteriole**; aldosterone comes from the zona glomerulosa — renin starts the cascade, aldosterone ends it |
| "Oliguria means the kidney itself is broken" | Low output is **prerenal** (flow problem), **intrinsic** (tubular injury), or **postrenal** (obstruction); prerenal failure is reversible by restoring flow |
| "Creatinine clearance equals GFR exactly" | Creatinine is **slightly secreted**, so clearance overestimates GFR; **inulin** is the reference because it is filtered and neither reabsorbed nor secreted |
| "Urination is a voluntary act" | Voiding is a **sacral reflex** that pontine and cortical centres permit or suppress; continence needs relaxed detrusor plus both sphincters closed |
| "Kidney disease only follows high blood pressure" | The relationship is **bidirectional** — hypertension scars glomeruli, and a failing kidney cannot excrete the pressure-natriuresis load, so it sustains hypertension |

## Key facts

- The nephron runs **renal corpuscle → PCT → loop of Henle → DCT → collecting duct**; each segment's structure (brush border, thin/thick limbs, principal and intercalated cells) predicts its function.
- Filtration is driven by **glomerular hydrostatic ~55 mmHg** opposed by **capsular hydrostatic ~15** and **oncotic ~26**, giving **NFP ≈ 15 mmHg**; the membrane blocks by **size and negative charge**, not size alone.
- **GFR ≈ 125 mL/min = 180 L/day**, filtration fraction ≈ **20%**, and **99.2% of filtrate is reabsorbed** — urine is a processed residue, not a filtrate.
- **Autoregulation (myogenic + tubuloglomerular)** holds GFR constant across mean pressures ~80–180 mmHg; outside that range GFR follows perfusion, so shock causes prerenal failure.
- **PCT reclaims ~65% of Na⁺ and water, ~100% of glucose and amino acids, 80–90% of filtered HCO₃⁻**, and secretes H⁺, K⁺, creatinine, and drugs.
- **Glycosuria = filtered load > Tm (~375 mg/min)**; the renal threshold (~180 mg/dL) is below Tm because carriers saturate gradually (**splay**).
- The **countercurrent multiplier** (NKCC2 in the water-impermeable thick ascending limb) builds the **300 → 1,200 mOsm/kg** medullary gradient; the **vasa recta countercurrent exchanger** preserves it.
- **ADH inserts aquaporin-2** for water reclamation; **aldosterone opens ENaC** for Na⁺ retention and K⁺ secretion; **ANP opposes aldosterone** — final urine is decided in the collecting duct.
- **RAAS** runs renin → angiotensin I → angiotensin II (ACE) → aldosterone and ADH; **pressure natriuresis** is its long-term partner in setting blood pressure.
- The kidney is the **slow, permanent** arm of acid–base control — H⁺ secretion, HCO₃⁻ reclamation, **ammonium generation** — while the lung is fast but temporary.
- Endocrine roles: **EPO** (RBC production), **calcitriol** (Ca²⁺ absorption), **gluconeogenesis** in prolonged fasting; **creatinine clearance** estimates GFR but slightly overestimates it.
- Voiding is a **sacral reflex** coordinated by the pons: parasympathetic detrusor contraction (M₃), sphincter relaxation, voluntary permission of the external sphincter.
- Dialysis works by **diffusion across a semipermeable membrane**; stones are prevented by **dilution and pH control**; UTI is an **ascending infection** whose female predominance is anatomical.

## Practice questions

**1. The high filtration pressure of the glomerulus is generated because**

A. The renal artery is a high-pressure elastic artery with no downstream resistance
B. An afferent and an efferent arteriole sit in series around the capillary
C. The podocytes actively pump fluid into Bowman's capsule
D. The vasa recta compress the glomerular tuft during systole

**Answer: B**

Explanation: Two arterioles in series — wide afferent, narrower efferent — perfuse the tuft at arterial pressure, so hydrostatic pressure stays near 55 mmHg along the whole capillary instead of falling to ordinary capillary levels.

---

**2. Net filtration pressure is approximately 15 mmHg because**

A. 55 − (15 + 26) ≈ 14, driven by glomerular hydrostatic pressure against capsular and oncotic opposition
B. 55 + 15 − 26 ≈ 44, because capsular pressure aids filtration
C. Oncotic pressure of 55 mmHg drives fluid out
D. Bowman's capsule is at negative pressure

**Answer: A**

Explanation: NFP = P_GC − (P_BS + π_GC). Capsular hydrostatic and blood oncotic pressures both oppose filtration, while capsular oncotic pressure is negligible because almost no protein crosses the membrane.

---

**3. A healthy adult filters about 180 L per day but excretes about 1.5 L, which means**

A. The remaining fluid is pumped back into the renal artery
B. About 99% of the filtrate is reabsorbed along the tubule
C. Most filtrate returns through the lymphatics
D. GFR must be far lower than 125 mL/min

**Answer: B**

Explanation: 180 − 1.5 = 178.5 L reabsorbed, i.e. 99.2% of the filtrate, dominated by the PCT. Reabsorbed fluid enters peritubular capillaries; nothing is returned directly to the artery.

---

**4. Albumin is small enough to pass the size barrier but is almost absent from filtrate mainly because**

A. It is actively pumped back into the capillary
B. The fenestrations are narrower than albumin
C. The filtration membrane carries a strong negative charge that repels it
D. Podocytes metabolise it

**Answer: C**

Explanation: Albumin is negatively charged at blood pH, as are heparan sulphates of the basement membrane, so electrostatic repulsion excludes it. Losing the charge barrier alone — as in minimal change disease — causes heavy proteinuria.

---

**5. Glucose appears in the urine of an untreated diabetic because**

A. The kidney stops making ATP so carriers fail
B. The filtered load exceeds the transport maximum of the SGLT carriers
C. Glucose is actively secreted into the tubule
D. ADH blocks glucose reabsorption in the collecting duct

**Answer: B**

Explanation: SGLT2 and SGLT1 reclaim glucose by secondary active transport, and once the filtered load passes ~375 mg/min every carrier is occupied. Excess glucose stays in the tubule and drags water with it, causing osmotic diuresis.

---

**6. The thick ascending limb produces dilute tubular fluid because it**

A. Lets water follow the pumped salt osmotically
B. Actively transports Na⁺/K⁺/2Cl⁻ out while remaining impermeable to water
C. Passively absorbs urea
D. Expresses aquaporin-2 under ADH control

**Answer: B**

Explanation: NKCC2 moves salt out but no water can follow, so fluid falls to ~100 mOsm/kg by the time it reaches the DCT. The same water-impermeable transport is the single effect that builds the medullary gradient, and furosemide blocks it.

---

**7. A patient with SIADH has a plasma sodium of 128 mmol/L. The hyponatraemia is dilutional because**

A. Sodium has been lost while water was retained
B. Total body sodium is normal but excess pure water has expanded volume
C. ADH directly removes sodium from plasma
D. The patient is dehydrated and sodium has moved into cells

**Answer: B**

Explanation: ADH retains water without retaining sodium, so a normal sodium pool is dissolved in a larger volume — the patient is euvolaemic with inappropriately concentrated urine. True sodium loss would be hypovolaemic.

---

**8. The segment most directly responsible for generating the medullary osmotic gradient is the**

A. Proximal convoluted tubule
B. Descending limb of the loop of Henle
C. Thick ascending limb of the loop of Henle
D. Cortical collecting duct

**Answer: C**

Explanation: The thick ascending limb pumps NaCl into the interstitium while being impermeable to water, and countercurrent geometry multiplies that single effect to ~1,200 mOsm/kg. The descending limb merely lets water leave.

---

**9. In chronic metabolic acidosis the kidney corrects pH primarily by**

A. Increasing ventilation to blow off CO₂
B. Increasing ammonium and titratable acid excretion to generate new bicarbonate
C. Filtering more bicarbonate to raise its plasma level
D. Secreting bicarbonate into the tubular fluid

**Answer: B**

Explanation: Reclaiming filtered bicarbonate regenerates but does not create base; new bicarbonate appears only when a proton is excreted buffered by phosphate or ammonia. A describes the lung's fast but temporary compensation.

---

**10. Furosemide relieves oedema by blocking NKCC2 in the thick ascending limb, producing**

A. Increased water reabsorption in the collecting duct and a small concentrated urine
B. Salt retention in the tubule, collapse of the medullary gradient, and a large volume of dilute urine
C. Increased aldosterone secretion so that Na⁺ is retained
D. A fourfold rise in GFR that washes away interstitial fluid

**Answer: B**

Explanation: Blocking NKCC2 leaves Na⁺, K⁺, and Cl⁻ in the lumen, water cannot follow across an impermeable limb, and the gradient the collecting duct depends on is dissipated — hence potent diuresis with dilute urine, plus K⁺ and Mg²⁺ losses.
