# Active Transport: Pumps, Cotransport, Endocytosis, Exocytosis

## Why it matters

Passive transport can equalise concentrations but can never create one. Cells routinely need the *opposite* — high Na⁺ outside and high K⁺ inside, low Ca²⁺ inside, stomach acid at pH 1, a neuron ready to fire. All of that requires moving substances **against their gradient**, which means **paying energy**.

This chapter has three payment methods:

```
1. PRIMARY ACTIVE TRANSPORT     ATP used directly by the pump
2. SECONDARY ACTIVE TRANSPORT   one gradient built earlier pays for another
3. BULK TRANSPORT               vesicles move large loads (endocytosis / exocytosis)
```

Everything a cell does that passive transport cannot do is one of these three.

## Primary active transport

**A pump uses ATP directly to move a substance against its gradient.** The defining test: **if it is blocked, the gradient collapses** — because the gradient exists only as long as the pump runs.

### The sodium–potassium pump (Na⁺/K⁺-ATPase)

The most important pump in human physiology — every animal cell runs one, and it consumes roughly a **quarter of a resting cell's ATP** (more in a resting neuron).

```
OUTSIDE        Na⁺ high, K⁺ low
        ┌─────────────────────────┐
        │   3 Na⁺ bind inside ──▶ ATP phosphorylates pump
        │                        pump changes shape
        │   3 Na⁺ released OUTSIDE
        │
        │   2 K⁺ bind outside ──▶ dephosphorylation
        │   2 K⁺ released INSIDE
        └─────────────────────────┘
INSIDE         K⁺ high, Na⁺ low

         3 Na⁺ out : 2 K⁺ in  — per ATP
```

**Consequences, in order of importance:**

| Consequence | Why it matters |
| --- | --- |
| **Steep Na⁺ gradient (out) and K⁺ gradient (in)** | Stored energy for secondary transport — the cell's battery |
| **3 out, 2 in = net loss of positive charge** | Makes the inside **negatively charged** → the resting membrane potential |
| **Low intracellular Na⁺** | Keeps the cell from swelling — Na⁺ draws water in, so pumping Na⁺ out is how volume is controlled |
| **K⁺ leak channels** | Maintain the potential; the pump sets up what the leaks then exploit |

**This is the single most important mechanism in this section** — the pump does not just move ions, it creates the electrical and osmotic state of the cell. Depolarisation in nerves, co-transport of glucose, cell volume control, and the resting potential all run on this one gradient. If the pump stops (cyanide, lack of ATP), Na⁺ leaks in, water follows, and the cell **swells and dies** — osmosis, from chapter 02, as the executioner.

### Other major pumps

| Pump | Moves | ATP per cycle | Function |
| --- | --- | --- | --- |
| **Ca²⁺-ATPase (PMCA, SERCA)** | Ca²⁺ out of cytosol | 1 per Ca²⁺ | Keeps cytosolic Ca²⁺ ~10,000× lower than outside; SERCA loads the sarcoplasmic reticulum |
| **H⁺/K⁺-ATPase** | H⁺ into stomach lumen, K⁺ back | 1 | **Makes stomach acid**; blocked by proton-pump inhibitors |
| **H⁺-ATPase (V-type)** | H⁺ into lysosomes | — | Acidifies lysosomes to pH ~4.5 (chapter 03, 02 — Cell Biology) |
| **ABC transporters** | Various (pumps drugs, lipids, peptides) | 1 | **CFTR is a Cl⁻ channel of this family**; others pump chemotherapeutic drugs out of cancer cells (**multidrug resistance**) |

**Why Ca²⁺ must be pumped:** calcium is a *signal*, and a signal is only useful if the background is silent. Cells keep cytosolic Ca²⁺ near 10⁻⁷ M; the moment channels open, Ca²⁺ floods in and triggers contraction, secretion, or enzyme activation. Pumping it back out resets the system. **Signal = rapid passive entry; reset = paid export.** That pairing is the design pattern of the whole calcium system.

## Secondary active transport (cotransport)

**No ATP is used directly.** The pump-built Na⁺ gradient does the work — Na⁺ flows down *its* gradient, and the energy released drags a second substance against *its* gradient.

| Type | Direction of second solute | Example |
| --- | --- | --- |
| **Symport (cotransport)** | Same direction as Na⁺ | **SGLT1** — Na⁺ + glucose into gut epithelium; Na⁺ + amino acid symporters |
| **Antiport (exchange)** | Opposite direction to Na⁺ | **Na⁺/Ca²⁺ exchanger** (NCX); **Na⁺/H⁺ exchanger**; Cl⁻/HCO₃⁻ exchanger |

```
PRIMARY:     ATP ──▶ Na⁺/K⁺ pump ──▶ steep Na⁺ gradient (outside high)

SECONDARY:   Na⁺ rushing IN  ──▶ drags glucose IN (against glucose's gradient)
             (energy borrowed from the pump)
```

**The chain of energy:** glucose is absorbed against its gradient in the gut *because* ATP was spent earlier by the Na⁺/K⁺ pump. It is borrowed energy, not free energy — **secondary active transport is still ultimately ATP-powered**, one step removed.

**SGLT1 is the textbook case and a drug target.** The gut and kidney reabsorb glucose against its gradient using Na⁺-glucose symporters. **SGLT2 inhibitors** (gliflozins) block the renal version, so glucose stays in the urine and is excreted — a diabetes drug whose mechanism is nothing but inhibiting a cotransporter from this chapter.

### Active vs passive — the decision table

| | Passive | Primary active | Secondary active |
| --- | --- | --- | --- |
| Direction | Down gradient | **Against** | **Against** (second solute) |
| Energy | Gradient itself | **ATP directly** | **Na⁺ gradient** (indirectly ATP) |
| Protein | Channel or carrier | Pump | Cotransporter |
| Stops when | Equilibrium | ATP runs out | Na⁺ gradient gone |

## Bulk transport: vesicular movement

Small molecules use pumps and carriers; **macromolecules and large volumes use vesicles.** Bulk transport is *always* energy-dependent — it requires membrane bending, motor-driven movement, and fusion, all ATP-consuming processes — even when the cargo itself moves "down" a gradient.

### Endocytosis — bringing material in

| Type | What is taken in | Specificity | Example |
| --- | --- | --- | --- |
| **Phagocytosis** ("cell eating") | Large particles, whole cells | Receptor-driven, actin-based pseudopods | Macrophage engulfing a bacterium → phagolysosome |
| **Pinocytosis** ("cell drinking") | Extracellular fluid and dissolved solute | Non-specific; bulk sampling | Most cells; sampling the environment |
| **Receptor-mediated endocytosis** | Specific molecules bound to receptors | **Highly specific**, concentrated in **clathrin-coated pits** | Cholesterol uptake (LDL), iron uptake (transferrin), insulin signal termination |

**Receptor-mediated endocytosis is the high-efficiency version** — receptors concentrate cargo in coated pits, a clathrin-coated vesicle buds (with **dynamin** pinching the neck), the coat is shed, and the endosome sorts:

```
receptor + ligand ─▶ coated pit ─▶ clathrin vesicle ─▶ EARLY ENDOSOME
                                                               │
                    ┌──────────────────────────────────────────┤
                    ▼                                          ▼
            RECYCLED receptors                          LATE ENDOSOME → LYSOSOME
            back to membrane                             (ligand degraded,
                                                          receptors recovered)
```

**Why sort instead of digest everything:** the cell recovers its receptors. In the LDL pathway, the **receptor returns to the surface while cholesterol stays inside** — one receptor cycles hundreds of times. Waste that, and you lose the ability to clear LDL.

**Familial hypercholesterolaemia is the demonstration.** Mutations in the **LDL receptor** → LDL cannot be cleared from blood → cholesterol accumulates → **premature atherosclerosis and heart attacks**, heterozygotes with LDL 2–3× normal, homozygotes with myocardial infarction in childhood. One broken item from this table, and the entire lipoprotein system fails. It is the clearest clinical proof that receptor-mediated endocytosis matters.

**Signal termination by endocytosis.** A receptor that stays on the surface keeps signalling. Internalising it ends the message — so endocytosis is not just nutrition, it is **part of signal termination**, linking back to the contact-inhibition discussion in 02 — Cell Biology.

### Exocytosis — pushing material out

A vesicle from the Golgi (or endosome) **fuses with the plasma membrane**, dumping its contents outside and adding its lipids to the membrane.

```
vesicle ── tethering (Rab proteins) ── docking (SNAREs zip together)
        ── fusion ── pore opens ── contents released
        ── membrane now contains vesicle lipids + proteins
```

**SNAREs** are the fusion machine: **v-SNAREs** on the vesicle zip with **t-SNAREs** on the target membrane, pulling the two bilayers together until they merge. **Botulinum toxin and tetanus toxin are proteases that cut SNAREs** — so nerves cannot release transmitter. The reason a bacterium's toxin causes paralysis is a direct attack on this chapter's fusion machinery.

**Two roles:**
1. **Secretion** — neurotransmitter release, digestive enzyme release, hormone release (regulated exocytosis, 02 — Cell Biology).
2. **Membrane renewal** — constitutive exocytosis delivers new lipid and protein; the membrane grows unless balanced by endocytosis.

**Membrane traffic is a cycle:** endocytosis removes membrane, exocytosis adds it. In a resting cell the two rates match, so surface area stays constant. **Traffic is balanced, not one-way.**

## How the three mechanisms connect

```
        PRIMARY (pumps)
              │ builds Na⁺ gradient
              ▼
        SECONDARY (cotransport) ◀── uses the gradient
              │ delivers glucose, amino acids, ions
              ▼
        CELL HAS MATERIAL
              │ macromolecules too large for carriers
              ▼
        ENDOCYTOSIS (in) / EXOCYTOSIS (out)
              │ requires membrane traffic, ATP, SNAREs
              ▼
        LYSOSOME digests · MEMBRANE renewed · SIGNALS terminated
```

**One gradient, three users.** The Na⁺/K⁺ pump sits at the top of the hierarchy: block it and secondary transport stops, cell volume fails, and the membrane potential collapses — all at once.

## Regulation and inhibition

| Agent | Target | Effect |
| --- | --- | --- |
| **Ouabain, digoxin** | Na⁺/K⁺-ATPase | Inhibit the pump — increased cardiac contractility (digoxin), used clinically |
| **Loop diuretics (furosemide)** | Na⁺/K⁺/2Cl⁻ cotransporter in kidney | Block secondary transport → salt and water lost in urine |
| **Proton-pump inhibitors (omeprazole)** | H⁺/K⁺-ATPase | Suppress stomach acid production |
| **SGLT2 inhibitors (empagliflozin)** | Na⁺/glucose cotransporter in kidney | Glucose excreted in urine — diabetes therapy |
| **Botulinum / tetanus toxin** | SNAREs | Block exocytosis → flaccid / spastic paralysis |
| **Cyanide (indirectly)** | ETC → no ATP | All pumps fail → gradients collapse |

Notice the pattern: **five of six are clinical drugs**, and each is a named inhibitor of one transporter. Transport proteins are among the most drugged targets in medicine precisely because they are membrane-embedded, specific, and rate-limiting.

## Medical relevance

**Cell volume control fails when pumps fail.** Ischaemia stops ATP production, Na⁺/K⁺ fails, Na⁺ and water enter, the cell swells — **cytotoxic oedema**, a major component of stroke damage. Everything in the volume story is chapter 02's osmosis plus this chapter's pump.

**Cancer and multidrug resistance.** Many tumour cells **overexpress ABC transporters** (P-glycoprotein) that pump chemotherapy drugs out as fast as they enter — cells become resistant to many unrelated drugs at once. The mechanism is exocytosis-adjacent pumping from this chapter's first section, and blocking it is an active area of research.

**Iron and cholesterol handling define two classic diseases:** transferrin receptor defects cause iron-deficiency-like states despite adequate iron; LDL receptor defects cause familial hypercholesterolaemia. Both are failures of receptor-mediated endocytosis.

**Secretion failure is neuroparalysis.** The SNARE story above: botulism in infants from contaminated honey, therapeutic Botox used deliberately to cut SNAREs in overactive muscles — the same molecule, dose and context deciding between disease and treatment.

## Key facts

- Active transport moves substances **against a gradient** and always requires energy — directly (ATP) or indirectly (an ion gradient).
- **Na⁺/K⁺-ATPase: 3 Na⁺ out, 2 K⁺ in, 1 ATP** — creates the ion gradients, the membrane potential, and the volume-control system; consumes ~25% of resting ATP.
- **Secondary active transport borrows the Na⁺ gradient**: symport (SGLT1, glucose) or antiport (Na⁺/Ca²⁺); blocked pump → all cotransport stops.
- **Ca²⁺ is kept ~10,000× lower inside** by pumps; entry is the signal, pumping is the reset.
- **Endocytosis** = phagocytosis, pinocytosis, **receptor-mediated (clathrin, LDL)**; receptors are recycled while cargo is degraded.
- **Exocytosis** = SNARE-mediated fusion; used for secretion, membrane renewal, and signal termination; **botulinum toxin cuts SNAREs**.
- Bulk transport always costs energy and is balanced by endocytosis so surface area stays constant.
- Drug targets: digoxin (pump), loop diuretics (cotransporter), PPIs (H⁺/K⁺ pump), SGLT2 inhibitors, Botox (SNAREs).

## Practice questions

**1. The sodium–potassium pump moves per ATP molecule hydrolysed:**

A. 2 Na⁺ in and 3 K⁺ out
B. 3 Na⁺ out and 2 K⁺ in
C. 3 Na⁺ in and 3 K⁺ out
D. 2 Na⁺ out and 2 K⁺ in

**Answer: B**

Explanation: Three sodium ions are exported and two potassium imported for each ATP, making the pump electrogenic (net loss of one positive charge) and building the steep gradients that drive the resting potential and all secondary transport. The 3:2 stoichiometry is the detail exams test.

---

**2. Glucose absorption against its concentration gradient in the small intestine is driven by**

A. Direct hydrolysis of ATP by the glucose transporter
B. Simple diffusion down the glucose gradient
C. The sodium gradient established by Na⁺/K⁺-ATPase, with Na⁺ and glucose entering together
D. Endocytosis of glucose molecules

**Answer: C**

Explanation: SGLT1 is a Na⁺–glucose symporter: Na⁺ moving down its steep gradient (maintained by the pump) supplies the energy to drag glucose in against its own gradient. It is secondary active transport — the ATP cost is paid by the pump, not by the transporter. B fails because the gradient is uphill; A describes a primary active pump.

---

**3. A cell is treated with a drug that inhibits the Na⁺/K⁺-ATPase. Which is the most immediate consequence?**

A. Glucose uptake by GLUT4 increases
B. Ion gradients begin to collapse, the membrane potential falls, and the cell begins to swell
C. Exocytosis speeds up
D. Calcium is pumped into the cell more rapidly

**Answer: B**

Explanation: With the pump stopped, Na⁺ leaks in down its channel-driven gradient and K⁺ leaks out; the gradients that existed only because of the pump dissipate, the potential generated partly by the 3:2 stoichiometry falls, and water follows Na⁺ inward by osmosis — swelling and eventual lysis. A and C require energy the cell is losing; D is not a direct effect.

---

**4. Familial hypercholesterolaemia results from defective**

A. ATP production
B. Receptor-mediated endocytosis of LDL via the LDL receptor
C. Exocytosis of cholesterol
D. Passive diffusion of cholesterol into cells

**Answer: B**

Explanation: The LDL receptor concentrates LDL in clathrin-coated pits; without functional receptors, LDL remains in the blood, plasma cholesterol rises, and atherosclerosis develops early — severely in homozygotes. Cholesterol is a lipid and could in principle cross membranes, but uptake at these quantities depends on the receptor pathway.

---

**5. Which statement distinguishes secondary active transport from primary active transport?**

A. Secondary active transport uses no energy of any kind
B. Secondary active transport uses ATP directly
C. Secondary active transport uses the energy stored in an existing ion gradient rather than hydrolysing ATP itself
D. Secondary active transport moves substances down their gradients

**Answer: C**

Explanation: Secondary transport is powered by another ion — usually Na⁺ — moving down the gradient a pump built earlier. The energy is indirect (ultimately ATP), so A is wrong; the transporter itself binds no ATP, so B is wrong; the transported substance moves *against* its gradient, so D is wrong.

---

**6. Botulinum toxin causes flaccid paralysis because it**

A. Inhibits the Na⁺/K⁺ pump
B. Degrades SNARE proteins, preventing vesicle fusion and neurotransmitter release
C. Blocks voltage-gated sodium channels
D. Prevents endocytosis of the receptor

**Answer: B**

Explanation: Exocytosis requires v-SNAREs and t-SNAREs to zip vesicles to the membrane. Botulinum protease cleaves them, so synaptic vesicles cannot fuse and acetylcholine is not released — muscles cannot contract. The target is the fusion machinery of this chapter, not the channels or pumps.

---

**7. During receptor-mediated endocytosis of LDL, what happens to the LDL receptor itself?**

A. It is degraded with the LDL in the lysosome every time
B. It is recycled back to the plasma membrane while the LDL is released for degradation
C. It is secreted outside the cell
D. It is incorporated permanently into the lysosome

**Answer: B**

Explanation: In the endosome the acidic environment strips LDL from its receptor; the receptor is packaged into returning vesicles and reused — sometimes hundreds of times — while LDL proceeds to the lysosome for cholesterol release. Recycling is what makes the pathway efficient; losing it would double the cell's protein cost of uptake.

---

**8. What is the direct function of the Ca²⁺-ATPase in a muscle cell?**

A. To let calcium in to trigger contraction
B. To pump Ca²⁺ back into the sarcoplasmic reticulum, lowering cytosolic Ca²⁺ so relaxation can occur
C. To convert ATP into contractile force
D. To export potassium

**Answer: B**

Explanation: Contraction begins when Ca²⁺ floods the cytosol (passively, through channels); relaxation requires its removal — SERCA pumps it back into the sarcoplasmic reticulum against its gradient. The pattern is signal = passive entry, reset = active export. A is the channel's role, and force generation is the myosin ATPase, not the calcium pump.

---

**9. Which type of endocytosis is highly specific and concentrates its cargo in clathrin-coated pits?**

A. Phagocytosis
B. Pinocytosis
C. Receptor-mediated endocytosis
D. Exocytosis

**Answer: C**

Explanation: Receptor-mediated endocytosis uses specific receptor–ligand binding to gather target molecules in coated pits before budding — giving huge selectivity and efficiency compared with the indiscriminate fluid sampling of pinocytosis or the particle engulfment of phagocytosis. Exocytosis is outward transport, not an endocytic route.

---

**10. Which clinical drug acts by inhibiting a secondary active transporter?**

A. Ouabain
B. Furosemide (loop diuretic) blocking the Na⁺/K⁺/2Cl⁻ cotransporter
C. Botulinum toxin
D. Cyanide

**Answer: B**

Explanation: The Na⁺-K⁺-2Cl⁻ cotransporter in the thick ascending limb is a secondary active transporter; loop diuretics block it, so salt and water are lost in urine. Ouabain hits the primary pump; botulinum hits SNAREs; cyanide depletes ATP entirely (an indirect effect on all energy-dependent transport).
