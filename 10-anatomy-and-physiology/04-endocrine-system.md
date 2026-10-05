# The Endocrine System

## Why it matters

Endocrinology is homeostasis made chemical: every gland answers the same three questions — **what signals it, what does it release, what turns it off.** The loop anatomy — stimulus, receptor, control centre, effector, response — is in [03 — Homeostasis: the full control loop](../09-human-biology/03-homeostasis-control-loop.md); this chapter is the **efferent pathway** when that pathway is a chemical in blood.

Nerves cannot do what hormones do. A nerve is wired point-to-point and fires for milliseconds: it cannot tell millions of adipocytes to release fatty acids over hours, and it has no wire to a distant organ. A **hormone** is broadcast in blood and acts on any cell bearing the right receptor, over seconds to days. Distance and duration are what hormones buy — and the systems interlock, because the **hypothalamus** is neural tissue that secretes hormones, the **posterior pituitary** is axon terminals releasing hormone made in hypothalamic cell bodies, and the **adrenal medulla** is a sympathetic ganglion that lost its axon. Where both arms solve one problem, the nerve covers the first ten seconds and the hormone the next ten days.

## Structure: ducts, glands, and the master hierarchy

### Endocrine versus exocrine

An **endocrine gland** has no duct and secretes into its own fenestrated capillaries (pituitary, thyroid, adrenal, islets, gonads); an **exocrine gland** keeps a duct and delivers to a surface (salivary, sweat, pancreatic acini).

| Property | Endocrine gland | Exocrine gland |
| --- | --- | --- |
| **Duct** | **None** — secretion into capillary blood | Present — product travels down it |
| **Target** | Any receptor-bearing cell (broadcast) | One surface or lumen (local) |

### The hypothalamus–pituitary hierarchy

The **pituitary** sits in the sella turcica, weighs about 0.5 g, and has two lobes of different embryonic origin and different wiring — which explains most of pituitary physiology.

```
HYPOTHALAMUS (neural tissue; holds the set point)
   |
   +-- releasing / inhibiting hormones --> HYPOPHYSEAL PORTAL VEINS
   |                                            |
   |                                            v
   |                                   ANTERIOR PITUITARY (adenohypophysis)
   |                                            |
   |                                            v trophic hormone (TSH, ACTH, LH/FSH)
   |                                   PERIPHERAL GLAND (thyroid, adrenal cortex, gonad)
   |                                            |
   |                                            v end hormone (T4, cortisol, oestradiol)
   |                                   TARGET TISSUES
   |<----------- negative feedback ------------+
   |
   +-- axons down the pituitary stalk -------> POSTERIOR PITUITARY (neurohypophysis)
                                                neural; diencephalic ectoderm
```
| Feature | Anterior pituitary | Posterior pituitary |
| --- | --- | --- |
| **Origin** | Oral ectoderm — **Rathke's pouch** | Neural ectoderm — diencephalic outgrowth |
| **Hypothalamic link** | **Hypophyseal portal system** (capillary to capillary) | **Axons** of the supraoptic and paraventricular nuclei |
| **Hormones made** | **GH, TSH, ACTH, FSH, LH, prolactin** | **None** |
| **Hormones released** | Its own six, into systemic blood | **ADH (vasopressin) and oxytocin** |
| **Regulated by** | Releasing and inhibiting hormones in portal blood | Hypothalamic action potentials; osmotic input |

Because the posterior lobe is purely axonal, stalk damage causes **diabetes insipidus within days** (the store runs out) while anterior hormones fail at once.

## Hormone chemistry determines behaviour

### The three chemical classes

| Property | **Peptide / protein** | **Steroid** | **Amine-derived** |
| --- | --- | --- | --- |
| **Built from** | Amino acids, on ribosomes ([03 — Proteins](../01-biochemistry/03-proteins.md)) | **Cholesterol** ([02 — Lipids](../01-biochemistry/02-lipids.md)) | Tyrosine or tryptophan; some iodinated |
| **Examples** | Insulin, glucagon, ADH, oxytocin, GH, TSH, ACTH, FSH, LH, PTH | Cortisol, aldosterone, testosterone, oestradiol, progesterone, calcitriol | Adrenaline, noradrenaline, dopamine; **T4 and T3**; melatonin |
| **Solubility** | Water-soluble, lipid-insoluble | **Lipophilic** | Catecholamines water-soluble; **T4/T3 lipophilic** |
| **Receptor address** | **Cell surface** — GPCR or receptor tyrosine kinase | **Intracellular / nuclear** | Catecholamines: surface GPCR. **T3/T4: nuclear** |
| **Mechanism** | Second messengers → enzyme phosphorylation | Hormone response element → **transcription** | Behaves as its class dictates |
| **Onset, duration** | **Seconds to minutes**, cleared fast | **Hours to days** | Adrenaline: seconds. Thyroxine: hours to days |
| **Oral dosing** | **Digested in the gut** — inject, or use a protected analogue | **Absorbed**, limited by first-pass metabolism | Adrenaline destroyed; **levothyroxine well absorbed** |
### The membrane rule: peptides are injected, steroids are swallowed

The plasma membrane is a lipid bilayer, so a polar molecule cannot simply diffuse across it ([02 — Plasma membrane and nucleus](../02-cell-biology/02-plasma-membrane-and-nucleus.md)). A peptide hormone is polar *and* a protein: gut proteases destroy it and the bilayer would exclude it anyway — hence **insulin must be injected**. Its receptor sits on the **outside**, so the message is relayed inward by a second messenger.

A **steroid is cholesterol-derived and lipophilic**, crosses membranes freely and has its receptor inside the cell — which is also why steroid drugs *can* be swallowed. What limits them is **first-pass metabolism**: absorbed portal blood is routed through the liver, which hydroxylates and conjugates much of the dose, so oral doses exceed parenteral ones — prednisolone rather than cortisol, ethinylestradiol in the pill. **Thyroxine proves the rule**: an amine chemically, but lipophilic with a nuclear receptor, so levothyroxine works as a tablet.

## Signal transduction: four mechanisms

### 1. GPCR → adenylyl cyclase → cAMP/PKA

The workhorse of peptide signalling: adrenaline at β-receptors, glucagon, ACTH, TSH, LH, FSH, PTH.

```
HORMONE (glucagon, adrenaline β1) binds the 7-pass GPCR
        ↓
RECEPTOR SHIFTS → Gsα SWAPS GDP FOR GTP → ACTIVATES ADENYLYL CYCLASE
        ↓
ATP --> cAMP   (the second messenger is made FROM ATP —
        ↓        [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md))
PROTEIN KINASE A → phosphorylates cytoplasmic enzymes and, in the nucleus, CREB
        ↓
PHOSPHORYLASE KINASE ON, GLYCOGEN SYNTHASE OFF
        ↓
GLYCOGEN BROKEN DOWN → glucose rises (liver)  or  CONTRACTILITY RISES (heart)
```

The inhibitory cousin **Gi** (somatostatin, α2, D2) lowers cAMP; one receptor engages many G proteins, so the chain **amplifies**.

### 2. GPCR → phospholipase C → IP₃ / DAG / Ca²⁺

Used by TRH, GnRH, angiotensin II, oxytocin at V1a receptors and α1-adrenergic — the Gq-coupled family.

```
HORMONE binds a Gq-COUPLED receptor → Gqα–GTP ACTIVATES PHOSPHOLIPASE C
        ↓
PIP2 IN THE MEMBRANE is cleaved --> IP3 + DAG
        ↓                         ↓           ↓
IP3 to the ER              stays in membrane  ACTIVATES PROTEIN KINASE C
        ↓
Ca2+ CHANNELS OPEN → cytosolic Ca2+ rises → binds CALMODULIN → kinases fire
        ↓
Ca2+ + PKC TOGETHER → SECRETION, SMOOTH MUSCLE CONTRACTION, GLYCOGENOLYSIS
```

The β cell fuses its insulin granule on this Ca²⁺ surge.

### 3. Receptor tyrosine kinase → PI3K/AKT and Ras/MAPK

Used by hormones whose job is **metabolism and growth** — insulin and IGF-1.

```
INSULIN or IGF-1 binds a RECEPTOR TYROSINE KINASE on the surface
        ↓ receptor AUTOPHOSPHORYLATES its own tail
   +-- IRS docks ----------------+-- Grb2 docks --+
   ↓                             ↓
PI3K --> PIP3 --> AKT/PKB      SOS swaps Ras GDP --> GTP
   ↓                             ↓
GLUT4 VESICLES FUSE WITH        RAF --> MEK --> ERK (MAPK cascade)
MEMBRANE; glycogen synthase ON  ↓
gluconeogenic genes OFF         growth and proliferation genes ON
   ↓
GLUCOSE UPTAKE AND STORAGE ↑    (IGF-1 driving chondrocytes to divide)
```

Insulin resistance is largely a **PI3K/AKT** defect, while sustained MAPK signalling is mitogenic — receptor tyrosine kinases are proto-oncogenes.

### 4. Steroid (nuclear) receptor → gene activation

```
STEROID HORMONE (cortisol, oestradiol, testosterone, calcitriol)
        ↓ diffuses through the lipid bilayer UNAIDED
binds its INTRACELLULAR / NUCLEAR RECEPTOR (held by HSP90 until hormone arrives)
        ↓ complex DIMERISES
BINDS A HORMONE RESPONSE ELEMENT in the promoter or enhancer
        ↓
RNA POLYMERASE recruited → TRANSCRIPTION ↑ → new protein → THE EFFECT
        ↓
hours to appear, days to wear off — the protein outlives the hormone
```

See [06 — Gene regulation](../05-molecular-biology/06-gene-regulation.md). Two clinical facts follow: genomic steroid effects are **slow** and **persist** after the hormone has gone.

## Regulation: closing the loop

### Feedback at three lengths

| Loop | What feeds back | Example |
| --- | --- | --- |
| **Long loop** | The **peripheral end hormone** inhibits hypothalamus *and* pituitary | Cortisol ⊣ CRH and ACTH; T3/T4 ⊣ TRH and TSH; gonadal steroids ⊣ GnRH, LH, FSH |
| **Short loop** | The **pituitary hormone** inhibits the hypothalamus | ACTH ⊣ CRH; GH ⊣ GHRH and raises somatostatin |
| **Ultrashort loop** | A **hypothalamic hormone** acts on the neurons that release it | GnRH on GnRH neurons; somatostatin on its own cells |

A **trophic** hormone (TSH, ACTH, LH, FSH) both stimulates secretion from its target gland and maintains it — so losing it atrophies the gland as well as starving it of signal. Feedback acts at every level at once, so one hormone level rarely localises a disease.

### Neural versus endocrine control

| Property | Neural control | Endocrine control |
| --- | --- | --- |
| **Carrier** | Action potential; neurotransmitter at a synapse | Hormone dissolved in blood |
| **Onset** | **Milliseconds to seconds** | Seconds to minutes; hours for genomic effects |
| **Duration** | Brief — stops when the neuron stops firing | Long — until the hormone is cleared |
| **Specificity** | **Point-to-point**: one synapse, one cell | **Broadcast**: only cells with the right receptor |

Bodies pair them: the baroreflex corrects pressure in one heartbeat, ADH and aldosterone over days.

## The major axes

### HPA axis: stress and glucose mobilisation

```
STRESS (haemorrhage, infection, hypoglycaemia, fear)
   or the CIRCADIAN drive — peak ~06:00–08:00, nadir ~midnight
        ↓
HYPOTHALAMUS, paraventricular nucleus → CRH (+ vasopressin)
        ↓ hypophyseal portal vessels
CORTICOTROPHS → ACTH (from pro-opiomelanocortin, POMC)
        ↓
ZONA FASCICULATA OF THE ADRENAL CORTEX → CORTISOL (a steroid)
        ↓
LIVER ↑ gluconeogenesis; MUSCLE protein catabolised; ADIPOSE lipolysis;
IMMUNE SYSTEM SUPPRESSED (NF-κB, phospholipase A2); vessels sensitised
        ↓
CORTISOL FEEDS BACK on pituitary (↓ ACTH) and hypothalamus (↓ CRH)
```

Cortisol is a **permissive hormone**: without it adrenaline cannot constrict vessels or mobilise glucose, so replacement precedes any stressor in adrenal insufficiency; it is prescribed deliberately as an anti-inflammatory. Aldosterone follows angiotensin II and potassium rather than ACTH, so Addison's loses salt control too.

| | **Cushing's (excess)** | **Addison's (primary failure)** |
| --- | --- | --- |
| **Picture** | Hyperglycaemia, central obesity, moon face, striae, infection | **Hypoglycaemia**, wasting, **low pressure** (aldosterone lost → Na⁺ loss, K⁺ retention), **addisonian crisis** under stress |
| **Clue** | **Circadian rhythm lost** — cortisol high all night | **High ACTH with low cortisol**; pigmentation, because POMC also yields MSH |

### HPT axis: metabolic rate, thermogenesis, and the goitre

```
COLD EXPOSURE / metabolic demand → HYPOTHALAMUS → TRH
        ↓ portal vessels → THYROTROPHS → TSH
        ↓
THYROID FOLLICLE: iodide trapped by Na+/I− SYMPORTER →
THYROPEROXIDASE iodinates thyroglobulin (MIT + DIT → T3 ; DIT + DIT → T4)
        ↓ T4 AND T3 released (~90 % as T4, bound to TBG)
PERIPHERAL DEIODINASE removes one iodine → T3, the active form
        ↓ T3 enters the nucleus of every cell → nuclear receptor
↑ Na/K-ATPase, ↑ oxygen consumption and HEAT, ↑ basal metabolic rate;
glycogen and fat broken down, foetal brain development
        ↓
T3/T4 INHIBIT TRH AND TSH → synthesis and release fall
```

**Goitre mechanism — a gland growing because the hormone is missing:**

```
DIETARY IODINE LOW → T4 synthesis FALLS → negative feedback REMOVED
        ↓ TSH RISES and stays high
TSH drives follicular hypertrophy and hyperplasia → GOITRE
```

Size reports **TSH drive, not hormone output**: the same swelling occurs in iodine-deficient hypothyroidism and in Graves' disease, for opposite reasons. **Calcitonin** comes from the **parafollicular C cells** when calcium rises; it inhibits osteoclasts and marks medullary thyroid carcinoma.

### HPG axis: puberty, the cycle, and menopause

```
PULSATILE GnRH — pulse frequency encodes the message; continuous GnRH
   SUPPRESSES the pituitary (the basis of drug therapy)
        ↓ hypophyseal portal vessels
GONADOTROPHS → FSH + LH
        ↓
TESTIS:  LH → LEYDIG CELLS → testosterone
         FSH → SERTOLI CELLS → spermatogenesis + INHIBIN B
OVARY:   FSH → follicular growth → oestradiol
         LH → ovulation and corpus luteum → progesterone
        ↓
GONADAL STEROIDS feed back on hypothalamus and pituitary;
INHIBIN B feeds back on FSH ALONE, tuning sperm production separately
```

In the **ovulatory cycle** rising oestradiol switches from negative to **positive feedback** at mid-cycle, giving the **LH surge** and ovulation. At **menopause** the ovaries fail and **FSH and LH rise markedly** — high gonadotrophins localise the failure to the ovary. Primary gonadal failure doubles as a genetics question: **Turner syndrome (45,X)** and **Klinefelter syndrome (47,XXY)** both raise FSH ([04 — Human inheritance patterns](../04-genetics/05-human-inheritance-patterns.md)); the axis in detail is in [10 — Reproductive system](10-reproductive-system.md).

### Somatotropic axis: growth and its timing

```
NIGHT-TIME SLEEP, EXERCISE, FASTING, HYPOGLYCAEMIA
        ↓
HYPOTHALAMUS: GHRH (stimulates) versus SOMATOSTATIN (inhibits) — a push–pull
        ↓ portal vessels → SOMATOTROPHS → GROWTH HORMONE in night-time PULSES
        ↓
(a) DIRECT: adipose LIPOLYSIS; muscle takes up amino acids; liver glucose ↑
(b) LIVER → IGF-1 → GROWTH PLATE CHONDROCYTES proliferate → bone lengthens
        ↓
FEEDBACK: IGF-1 ⊣ GHRH and ⊣ somatotrophs; GH ⊣ GHRH and ↑ somatostatin
```

Because longitudinal growth needs an **open epiphyseal plate**, timing decides the disease:

| Condition | Timing | Result |
| --- | --- | --- |
| **Gigantism** | Excess **before** the plates close | Proportional overgrowth in height |
| **Acromegaly** | Excess **after** closure | **Appositional** growth only: enlarged jaw and brow, large hands and feet, visceral enlargement, insulin resistance |
| **GH-deficient dwarfism** | Deficiency in childhood | **Proportionate short stature**, treatable with recombinant GH |
| **Achondroplasia** | Not hormonal — constitutively active **FGFR3** | Disproportionate short limbs ([04 — Human inheritance patterns](../04-genetics/05-human-inheritance-patterns.md)) |
### Calcium axis: PTH, calcitonin, and vitamin D

Calcium is defended as a controlled variable like temperature: one negative feedback loop ([03 — Homeostasis: the full control loop](../09-human-biology/03-homeostasis-control-loop.md), [01 — Skeletal system](01-skeletal-system.md)).

```
BLOOD IONISED CALCIUM FALLS (low dietary calcium, vitamin D deficiency, immobility)
        ↓
CALCIUM-SENSING RECEPTOR (CaSR) on CHIEF CELLS detects the fall
        ↓ PTH RELEASED within minutes → three effectors at once
   1. BONE   — PTH acts on OSTEOBLASTS → RANKL → OSTEOCLASTS resorb bone
               → Ca²⁺ and PO₄³⁻ released
   2. KIDNEY — ↑ Ca²⁺ reabsorption; ↓ PO₄³⁻ reabsorption (phosphaturia);
               ↑ 1α-HYDROXYLASE → 1,25-(OH)₂ CALCITRIOL
   3. GUT    — calcitriol → ↑ dietary Ca²⁺ absorption (the slow arm, days)
        ↓
BLOOD CALCIUM RISES toward 2.2–2.6 mmol/L
        ↓ CaSR on the parathyroid fires → PTH FALLS → loop idles
```

Vitamin D is a **pro-hormone with two obligatory hydroxylations**: skin + ultraviolet B → cholecalciferol → liver **25-hydroxylase** → 25(OH)D → kidney **1α-hydroxylase** (PTH-driven) → **calcitriol**. Without sunlight the loop leans harder on PTH, and sustained PTH excess hollows bone — rickets in children, osteomalacia in adults. **Calcitonin** runs the opposite arm: high calcium → C cells → osteoclasts inhibited.

### Adrenal medulla: the neural arm of fight-or-flight

The adrenal medulla is a **modified sympathetic ganglion**: chromaffin cells are postganglionic sympathetic neurons that lost their axons and now secrete into venous blood under **preganglionic sympathetic fibres**.

```
THREAT perceived → HYPOTHALAMUS → sympathetic outflow (thoracolumbar)
        ↓ preganglionic CHOLINERGIC fibres (splanchnic nerves)
CHROMAFFIN CELLS → ADRENALINE (~80 %) + NORADRENALINE (~20 %) into blood
β RECEPTORS: heart ↑ rate; bronchi DILATE; liver ↑ glycogenolysis;
             muscle glycolysis ↑
α RECEPTORS: cutaneous and splanchnic vessels CONSTRICT → pressure ↑
        ↓ GLUCOSE AND OXYGEN DELIVERED, airway opened — minutes, not hours
```

This is the **hormone arm of [03 — Nervous system](03-nervous-system.md)**: the same sympathetic programme broadcast so every organ obeys at once.

## Blood glucose: the exemplar endocrine loop

Two hormones made by cells millimetres apart in the same islet sense the same blood and do opposite things.

| | **Insulin** | **Glucagon** |
| --- | --- | --- |
| **Source** | Islet **β cells** (islet core) | Islet **α cells** (islet periphery) |
| **Stimulus** | **Rising glucose**; amino acids; incretins (GLP-1, GIP) | **Falling glucose**; sympathetic drive; amino acids |
| **Receptor** | **Receptor tyrosine kinase** → PI3K/AKT | **GPCR (Gs)** → cAMP/PKA |
| **Liver** | ↑ glycogenesis, ↑ glycolysis, ↑ lipogenesis; **↓ gluconeogenesis** | ↑ glycogenolysis and ↑ gluconeogenesis |
| **Muscle** | **GLUT4** translocation → ↑ uptake; ↑ glycogen and protein synthesis | No glucagon receptor — muscle glycogen feeds muscle only |
| **Adipose** | **GLUT4** uptake; ↑ lipogenesis; ↓ hormone-sensitive lipase | ↑ lipolysis → fatty acids and glycerol |
| **Net effect** | **GLUCOSE FALLS** | **GLUCOSE RISES** |

Secretion itself is electrical: glucose enters the β cell through **GLUT2**, glucokinase phosphorylates it, ATP rises, **K_ATP channels close**, the cell depolarises, **Ca²⁺ enters** and the granule fuses — the step sulphonylureas exploit.

```
ABSORBED MEAL → glucose RISES → β CELLS → INSULIN
        ↓ liver: GLYCOGEN SYNTHESIS ON, gluconeogenic genes OFF
        ↓ muscle and fat: GLUT4 to the membrane → glucose leaves the blood
        ↓ glucose also drives glycolysis, then lipogenesis when stores are full
          ([05 — Glycolysis](../03-cellular-processes/05-glycolysis.md),
           [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md))
GLUCOSE RETURNS TO ~4–5 mmol/L → β-cell stimulus falls → insulin falls

FASTING / EXERCISE → glucose FALLS → α CELLS → GLUCAGON
        ↓ liver only: GLYCOGENOLYSIS first (minutes), then GLUCONEOGENESIS
          from lactate, glycerol and amino acids (hours)
GLUCOSE RELEASED → glucose rises → glucagon falls → loop idles
```

## Water, salt, and the rest: a preview

### ADH and aldosterone

Both loops are handled properly in [08 — Urinary system](08-urinary-system.md); only the endocrine limbs are sketched here.

```
WATER LOSS / HIGH OSMOLALITY / LOW ARTERIAL VOLUME
        ↓ hypothalamic OSMORECEPTORS and baroreceptors
SUPRAOPTIC NUCLEUS synthesises ADH → axonal transport
        ↓ POSTERIOR PITUITARY releases it
V2 RECEPTORS in the COLLECTING DUCT → cAMP → AQUAPORIN-2 inserted
        ↓ water reabsorbed → dilute urine ↓ → osmolality restored

RENAL PERFUSION FALLS → JG CELLS RELEASE RENIN
        ↓ liver angiotensinogen → angiotensin I → (lung ACE) → ANGIOTENSIN II
ANGIOTENSIN II → ZONA GLOMERULOSA → ALDOSTERONE (steroid, genomic action)
        ↓ collecting duct: ENaC and Na/K-ATPase inserted
Na⁺ (then water) REABSORBED, K⁺ SECRETED → volume and pressure restored
```

Angiotensin II also drives thirst and ADH, so one trigger recruits three effectors; aldosterone acts genomically and takes hours, which is why the fast arm of volume control is ADH and vasoconstriction.

### Melatonin, oxytocin, prolactin

- **Melatonin** (pineal gland): darkness → sleep–wake and seasonal timing. It runs a **pure neural pathway** — retina → suprachiasmatic nucleus → superior cervical ganglion → pineal — and light suppresses it.
- **Oxytocin** (posterior pituitary, made in hypothalamus): cervical stretch and suckling → uterine contraction and milk ejection. Its loop is **positive feedback** — contraction increases stretch, which releases more, and it only ends at delivery.
- **Prolactin** (anterior pituitary lactotrophs): suckling → milk production. It is the unique **tonically inhibited** pituitary hormone — default "on" until dopamine turns it off — so a prolactinoma causes hypogonadism.

## Medical relevance

**Type 1 versus type 2 diabetes is effector loss versus effector resistance.** Type 1 is autoimmune destruction of β cells: absolute insulin deficiency follows, fat breaks down unopposed and **ketone bodies** accumulate → diabetic ketoacidosis. Type 2 begins with target tissue responding poorly to insulin (largely the PI3K/AKT branch), so β cells hypersecrete to compensate — a **relative** deficiency — then fail. Chronic hyperglycaemia damages vessels through the **polyol pathway**, **glycation end-products** and **protein kinase C**: **microvascular** retinopathy, nephropathy and neuropathy, **macrovascular** atherosclerosis.

**Thyroid function is read as two numbers, and the pair localises the lesion.** Hypothyroidism (usually autoimmune Hashimoto's) gives fatigue, weight gain, cold intolerance and bradycardia; untreated from birth it causes intellectual disability — hence newborn screening. Hyperthyroidism (Graves': stimulating immunoglobulins activate the TSH receptor, so the gland runs without TSH) gives weight loss, heat intolerance, tremor and tachycardia. The same logic applies to other axes: **high ACTH with low cortisol is primary adrenal failure**.

**Radioiodine works because the thyroid concentrates iodine.** The symporter traps I-131 into follicular cells, where short-range beta particles destroy tissue from inside — selectivity by transporter, not by drug design. It ablates residual thyroid cancer and treats Graves'; recombinant TSH raises uptake first (tumour cells take iodine only when driven), and a recent iodine load (contrast, kelp, amiodarone) blocks uptake.

**Growth disorders are a timing question.** Excess GH before epiphyseal closure gives gigantism; after closure the same excess gives acromegaly — jaw, brow, hands and feet enlarging, visceral growth, insulin resistance. GH deficiency in childhood gives proportionate, treatable dwarfism. Diagnosis needs **IGF-1 plus a dynamic GH test** — one pulsatile GH level means nothing.

**Hormone assays are meaningless without their feedback position.** Read trophic hormone and end hormone together: **high TSH with low T4 = primary hypothyroidism**; **low TSH with high T4 = primary hyperthyroidism**; **low TSH with low T4 = secondary** failure in the pituitary itself. Reading TSH without T4 is the commonest endocrine error: the number reports the *controller*, not the *variable*.

**The oral contraceptive pill is engineered feedback.** Ethinylestradiol (which survives first-pass metabolism) plus a progestogen suppress GnRH pulsatility, FSH and LH, so no follicle matures and there is **no LH surge and no ovulation**. Miss a pill and FSH rises — consistency matters more than timing ([10 — Reproductive system](10-reproductive-system.md)).

**Doping is endocrinology applied backwards.** Exogenous testosterone switches off GnRH, LH and FSH, so spermatogenesis stops — virilised and infertile at once; exogenous GH silences its own axis likewise. **Erythropoietin**, made by peritubular kidney cells in response to hypoxia via HIF, drives red cell production; injected EPO raises viscosity and risks thrombosis ([08 — Urinary system](08-urinary-system.md)).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The pituitary is the master gland that makes all hormones" | It is a **relay**: the hypothalamus drives it and it drives thyroid, adrenal cortex and gonads. The posterior pituitary makes nothing — it stores hypothalamic ADH and oxytocin. |
| "Peptide hormones can be given by mouth" | They are **digested by proteases** and could not cross the gut epithelium anyway. Insulin and GH are injected. |
| "Steroid hormones cannot be taken orally" | They can — being **lipophilic**, they are absorbed. What limits them is **first-pass hepatic metabolism**, hence higher oral doses or derivatives such as prednisolone and ethinylestradiol. |
| "Thyroxine is a steroid because it acts on genes" | It is an **amine** (tyrosine plus iodine) behaving like a steroid: lipophilic, nuclear receptor, genomic action — hence levothyroxine works as a tablet. |
| "Negative feedback acts only on the final gland" | There are **three lengths**: long (end hormone to hypothalamus and pituitary), short (pituitary hormone to hypothalamus), ultrashort (hypothalamic hormone to its own neurons). |
| "A high TSH means an overactive thyroid" | **High TSH means the thyroid is underperforming** — the pituitary raises TSH because T4 is low. A suppressed TSH accompanies thyrotoxicosis. |
| "A goitre means too much thyroid hormone" | A goitre is **growth driven by TSH**, which rises when hormone is scarce (iodine deficiency) and falls when it is abundant (Graves'). Size says nothing about output. |
| "Gigantism and acromegaly are different diseases" | The **same GH excess at different times**: before closure the long bones lengthen, after closure only appositional growth is possible. |
| "Insulin and glucagon are equally important for glucose" | They oppose each other, but **insulin is the only glucose-lowering hormone**; glucagon, adrenaline, cortisol, growth hormone and thyroid hormone all raise it. |
| "Hormonal control is just slow neural control" | Nerves are **wired, point-to-point, brief**; hormones are **broadcast, receptor-restricted, durable**. |

## Key facts

- **Hierarchy**: releasing hormones reach the **anterior pituitary via the hypophyseal portal system**; the **posterior pituitary stores hypothalamic ADH and oxytocin** and releases them from axon terminals.
- **Chemistry dictates behaviour**: peptides act at **surface receptors** via second messengers — fast, brief, destroyed if swallowed; steroids cross membranes, bind **nuclear receptors** and act on **transcription** — slow and lasting. **Oral steroids work** (limited by **first-pass metabolism**), oral peptides do not.
- **Four transduction mechanisms**: GPCR → **cAMP/PKA**; GPCR → **IP₃/DAG/Ca²⁺**; RTK → **PI3K/AKT and Ras/MAPK**; nuclear receptor → **hormone response element → transcription**.
- **Feedback comes in three lengths** — long, short, ultrashort — and a **trophic** hormone both secretes from and maintains its target gland, so losing it atrophies the gland.
- **HPA**: CRH → ACTH → **cortisol**, with a **circadian peak in the early morning**; glucose mobilisation, permissive effects, anti-inflammation; failure gives Cushing's or Addison's (pigmentation, because POMC also yields MSH).
- **HPT**: TRH → TSH → **T3/T4**, requiring **iodine** and thyroperoxidase; T3 raises basal metabolic rate; low iodine removes feedback → TSH rises → **goitre**.
- **HPG**: pulsatile GnRH → LH/FSH → gonadal steroids; mid-cycle oestradiol switches to **positive feedback** giving the LH surge.
- **Somatotropic**: GHRH versus somatostatin → pulsatile GH → **IGF-1** → growth plate; excess **before** closure gives gigantism, **after** closure acromegaly.
- **Calcium**: low ionised Ca²⁺ → **PTH** → bone resorption, renal reabsorption, calcitriol → gut absorption; CaSR shuts PTH off; **calcitonin** opposes it.
- **Insulin is the only hypoglycaemic hormone**; glucagon mobilises liver glucose; type 1 diabetes is effector loss, type 2 effector resistance with relative deficiency.

## Practice questions

**1. A drug binds an intracellular receptor and alters gene transcription, the effect appearing over 12 hours. Its class is most likely**

A. A peptide acting through a G-protein–coupled receptor
B. A cholesterol-derived steroid
C. An amino acid chain needing a cell-surface receptor tyrosine kinase
D. A water-soluble hormone cleared within minutes
**Answer: B**

Explanation: Steroids cross the membrane unaided and act on transcription — hours, not seconds; peptides (A, C) cannot cross.

---

**2. Glucagon raises blood glucose by activating**

A. A receptor tyrosine kinase and the Ras/MAPK cascade
B. A nuclear hormone response element
C. Adenylyl cyclase, raising cAMP and activating protein kinase A
D. Phospholipase C with no diacylglycerol production

**Answer: C**

Explanation: The glucagon receptor is Gs-coupled → adenylyl cyclase → cAMP → PKA. Insulin (A) is a RTK pathway, steroids (B) genomic, PLC (D) the α1 route.

---

**3. Which pairing of second messenger system with hormone is correct?**

A. IP₃ and DAG — adrenaline at β1 receptors
B. cAMP and PKA — TRH acting on gonadotrophs
C. IP₃ releasing ER calcium — GnRH acting on gonadotrophs
D. Direct Ras/MAPK activation — parathyroid hormone

**Answer: C**

Explanation: GnRH is Gq-coupled → phospholipase C → IP₃, which releases ER calcium; β1 adrenaline and PTH (A, D) use cAMP/PKA.

---

**4. Levothyroxine works by mouth while insulin does not because**

A. Levothyroxine is a peptide protected by an enteric coating
B. Insulin is a steroid destroyed by first-pass metabolism
C. Levothyroxine is lipophilic and absorbed; insulin is a protein digested in the gut and excluded by the membrane
D. Insulin must reach the nucleus, so it is injected directly

**Answer: C**

Explanation: Levothyroxine is lipophilic and absorbed; insulin is a peptide, digested by proteases and excluded by the bilayer, so it is injected.

---

**5. Which statement about the hypothalamus–pituitary hierarchy is correct?**

A. The posterior pituitary synthesises ADH and oxytocin
B. The anterior pituitary is linked by a portal vascular system, the posterior by axons
C. Releasing hormones reach their targets in systemic blood
D. The anterior pituitary is derived from neural ectoderm

**Answer: B**

Explanation: The anterior lobe sits behind portal veins, the posterior is axon terminals that only store hormone (A); the lobes arise from oral and neural ectoderm (D).

---

**6. A patient has T4 below the reference range and TSH above it. The lesion is in the**

A. Hypothalamus
B. Pituitary
C. Thyroid gland
D. Parathyroid gland

**Answer: C**

Explanation: Primary hypothyroidism — the gland fails, T4 falls and lifted feedback drives TSH up; a hypothalamic or pituitary lesion gives low or normal TSH.

---

**7. In iodine deficiency the thyroid enlarges because**

A. Iodine directly stimulates follicular cell division
B. Low T4 removes negative feedback, so TSH rises and trophically drives the gland
C. Calcitonin is overproduced and drives follicular growth
D. Autoantibodies stimulate the TSH receptor

**Answer: B**

Explanation: Iodine is T4's substrate, so low T4 lifts feedback, TSH rises and its trophic action hypertrophies the gland; D is Graves' disease.

---

**8. A person grows normally, then in adulthood the jaw, brow, hands and feet enlarge with no increase in height. The explanation is**

A. Excess GH before epiphyseal closure gives gigantism, after closure acromegaly
B. Excess thyroxine drives bony overgrowth
C. Excess IGF-1 in childhood with normal levels afterwards
D. Achondroplasia caused by overactive FGFR3

**Answer: A**

Explanation: Linear growth needs an open plate, so the same GH excess gives gigantism early and acromegaly after fusion; thyroxine (B) does not drive linear growth.

---

**9. Radioiodine (I-131) destroys thyroid tissue selectively because**

A. Iodine is incorporated into the DNA of every dividing cell
B. The sodium–iodide symporter concentrates iodine in follicular cells, so the isotope decays where it is trapped
C. I-131 binds the TSH receptor and triggers apoptosis
D. Only thyroid cells carry the enzyme that converts I-131 to a toxin

**Answer: B**

Explanation: The symporter concentrates iodide in follicular cells, so the isotope decays in place and beta particles spare distant tissue.

---

**10. Women taking a combined oral contraceptive fail to ovulate primarily because**

A. The pill directly destroys the corpus luteum
B. Exogenous oestrogen and progestogen suppress GnRH, LH and FSH, so no follicle matures and no LH surge occurs
C. The pill stimulates somatostatin, inhibiting all anterior pituitary hormones
D. The pill blocks progesterone receptors in the endometrium only

**Answer: B**

Explanation: Exogenous steroids hold GnRH, FSH and LH low, so no follicle matures and no LH surge occurs; D explains only the endometrial effect.
