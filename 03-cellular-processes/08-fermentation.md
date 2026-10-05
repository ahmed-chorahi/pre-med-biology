# Fermentation

## Why it matters

Fermentation is the answer to a specific, narrow problem: **the cell has run out of oxygen (or mitochondria), the electron transport chain has stopped, and NAD⁺ is about to run out — which would halt glycolysis and with it all ATP production.** Fermentation does not make extra ATP. It performs one single chemical service: **regenerates NAD⁺** so the two ATP from glycolysis can keep coming.

Understanding that this is a *rescue mechanism, not an energy strategy* retires the most common error in basic metabolism. A cell that ferments is not choosing a lazy way to make energy — it is keeping the only ATP-producing pathway it still has access to running.

## The problem stated precisely

Recall glycolysis's oxidation step ([05 — Glycolysis](05-glycolysis.md)):

```
glyceraldehyde-3-phosphate + NAD⁺ + Pᵢ ──▶ 1,3-BPG + NADH
```

**NAD⁺ is consumed.** The cell holds a small, finite pool. Under aerobic conditions NADH donates its electrons to the chain and NAD⁺ is returned at Complex I. But **without oxygen the chain backs up**, Complex I cannot reoxidise NADH, and the NAD⁺ pool empties within seconds.

```
NO O₂
  → ETC stops
    → NADH cannot donate electrons
      → NAD⁺ not regenerated
        → GAPDH blocked
          → GLYCOLYSIS STOPS
            → 2 ATP/sec → 0  → cell dies
```

**Fermentation breaks this chain at the third link** by finding a *different* way to dump NADH's electrons — not onto oxygen, but onto an organic molecule that is already sitting right there: **pyruvate**.

## The two routes

```
                         pyruvate (from glycolysis)
                              │
            ┌─────────────────┴──────────────────┐
            ▼                                    ▼
   LACTATE FERMENTATION               ETHANOL FERMENTATION
   (animals, some bacteria,          (yeast, some plants/microbes)
    RBCs, muscle)
            │                                    │
            │  pyruvate + NADH ─▶ lactate        │  pyruvate ─▶ acetaldehyde + CO₂
            │       LACTATE DEHYDROGENASE        │       PYRUVATE DECARBOXYLASE
            │                                    │  acetaldehyde + NADH ─▶ ETHANOL
            │  ← NAD⁺ returned                   │       ALCOHOL DEHYDROGENASE
            ▼                                    ▼      ← NAD⁺ returned
        lactate                               ethanol + CO₂
```

### Lactate fermentation

- **One enzyme:** lactate dehydrogenase (LDH), reversible, no ATP involved.
- **Carbon count:** three in, three out — **no CO₂ released** (unlike ethanol, which decarboxylates).
- **NAD⁺ regenerated** by passing NADH's electrons onto pyruvate.

### Ethanol fermentation (two steps)

- Pyruvate decarboxylase removes CO₂ (a **thiamine-dependent** step — TPP again, as in chapter 06) → acetaldehyde.
- Alcohol dehydrogenase reduces acetaldehyde to ethanol, oxidising NADH → NAD⁺.
- **Two carbons lost as CO₂** — this is where bread rises and the carbonation in fermented drinks begins.

**Why yeast makes ethanol but you make lactate:** the difference is enzymatic, not strategic — yeast lacks the LDH route at useful rates and uses pyruvate decarboxylase, which irreversibly commits pyruvate to acetaldehyde and prevents it from going back. Same goal (NAD⁺), different machinery.

## The energetics — stated bluntly

| Pathway | ATP per glucose | Source |
| --- | --- | --- |
| Glycolysis → lactate | **2** | Substrate-level only |
| Glycolysis → ethanol | **2** | Substrate-level only |
| Full aerobic respiration | **~30–32** | Mostly oxidative phosphorylation |

**Fermentation adds nothing.** The 2 ATP are entirely glycolysis's; fermentation's contribution is invisible on the balance sheet because it appears only as *NAD⁺ returned*. A cell fermenting to survive is running at about 6% of aerobic efficiency — which is why **cells that ferment long-term (tumours, exercising muscle) pay for it in waste products and pH**, and why **obligate fermenters stay small**.

**Anaerobic respiration vs fermentation — a distinction exams love:**

| | Fermentation | Anaerobic respiration |
| --- | --- | --- |
| Final electron acceptor | **An organic molecule** (pyruvate, acetaldehyde) | **An inorganic molecule other than O₂** (nitrate, sulfate) |
| ETC present? | **No** | **Yes** |
| Extra ATP beyond glycolysis? | **No** | **Yes** (from the chain) |
| Example | Yeast, your muscle | Some bacteria using NO₃⁻ |

*Bacteria using nitrate as an electron acceptor are respiring, not fermenting — they have a chain and earn extra ATP. Fermentation by definition has no electron transport chain.*

## Who ferments, and why it matters

### Your red blood cells

Mature erythrocytes have **no mitochondria** — they ferment **obligately**, producing lactate continuously. They cannot do anything else. This is why:

- Blood lactate includes a constant red-cell contribution.
- RBCs depend entirely on glucose supply and on glycolytic enzymes — pyruvate kinase deficiency is a haemolytic anaemia (chapter 05).

### Your muscle during intense exercise

Outrunning the blood supply, muscle runs anaerobically and accumulates **lactate and H⁺**:

```
high demand → O₂ delivery limited → pyruvate → lactate (regenerating NAD⁺)
                                        │
                                        ▼
                     H⁺ accumulation → lower pH → fatigue,
                     reduced Ca²⁺ sensitivity of contractile proteins
```

**The Cori cycle** recovers the waste:

```
MUSCLE: glucose → lactate          (exports lactate, gains nothing)
   │
   │  blood
   ▼
LIVER: lactate → glucose           (gluconeogenesis, costs 6 ATP)
   │
   │  blood
   ▼
MUSCLE: uses the new glucose
```

**The liver pays 6 ATP to reassemble what the muscle salvaged** — a division of labour: the muscle gets ATP quickly and at low efficiency; the liver cleans up the carbon and recharges it. Lactate is therefore not a dead-end waste product — it is **a fuel for gluconeogenesis**, a point that overturns the "lactic acid is poison" simplification.

**Old exercise physiology myths worth retiring:** lactate does not cause the delayed muscle soreness felt days later (that is structural damage), and the oxygen debt concept is better described as **EPOC** (excess post-exercise oxygen consumption) — used to restore phosphate stores, clear lactate, and reoxygenate myoglobin.

### Yeast and industry

| Application | Basis |
| --- | --- |
| **Bread** | CO₂ from ethanol fermentation leavens dough; ethanol evaporates in baking |
| **Wine, beer** | Ethanol is the product; yeast killed by concentration or removed |
| **Sauerkraut, yoghurt** | Bacterial lactate fermentation acidifies and preserves |
| **Silage** | Lactic acid drops pH, preserving fodder |

**Preservation by fermentation** is the same principle as every acid-based food safety rule: **lower pH inhibits pathogens** — and the acid here is a fermentation product.

### Cancer: the Warburg effect, finally in context

Many tumour cells ferment glucose to lactate **even when oxygen is plentiful** — aerobic glycolysis (chapter 04). Why would a cell choose 2 ATP over 30?

- **Speed:** glycolysis produces ATP *fast*, even if inefficiently.
- **Biosynthetic precursors:** intermediates are siphoned off to make nucleotides, lipids, and amino acids for division — the cycle's carbon is needed for *building*, not just burning.
- **Microenvironment:** the resulting acidic extracellular pH favours invasion and suppresses immune cells.

**Fermentation in a tumour is not primitive regression — it is a proliferative strategy.** And it is exactly why **FDG-PET** works: glucose analogue accumulates in the most glycolytically active tissue.

## Clinical notes

**Lactic acidosis** — lactate production exceeds liver clearance. Causes: shock (tissue hypoperfusion), sepsis, extreme exercise, metformin in renal failure, thiamine deficiency (impairs the aerobic route downstream). It is a **sign that oxygen delivery has failed at tissue level** even if blood gases look acceptable.

**D-lactic acidosis** in patients with short-bowel syndrome — bacterial fermentation in the gut produces the D-isomer of lactate, which human LDH clears poorly → confusion and ataxia after carbohydrate meals.

**Alcohol metabolism** runs the ethanol-reverse reaction in the liver: ethanol → acetaldehyde → acetate (alcohol dehydrogenase, then aldehyde dehydrogenase), producing **NADH** in bulk. That NADH/NAD⁺ ratio swing inhibits gluconeogenesis — the mechanism of **fasting hypoglycaemia in alcohol intoxication** — and links straight back to chapter 04's carrier balance.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Fermentation produces ATP" | **No.** Glycolysis produces the 2; fermentation only returns NAD⁺. |
| "Fermentation is the same as anaerobic respiration" | No — anaerobic respiration has a **chain and an inorganic acceptor** and makes extra ATP. |
| "Lactate is a waste product" | It is a **NAD⁺ source** and a **gluconeogenic substrate** (Cori cycle). |
| "Cells ferment because they are primitive" | Cells ferment because **the chain is unavailable or bypassed** — and tumours ferment *despite* oxygen. |
| "Fermentation occurs in mitochondria" | It is entirely **cytosolic** — no organelle involved. |

## Key facts

- **Fermentation's sole purpose: regenerate NAD⁺** so glycolysis can continue. No ATP is produced by fermentation itself.
- Two routes: **lactate** (LDH; 3C→3C, no CO₂) and **ethanol + CO₂** (pyruvate decarboxylase then alcohol dehydrogenase).
- Yield: **2 ATP per glucose** — vs ~30–32 aerobic.
- **Anaerobic respiration ≠ fermentation:** respiration has a chain, an inorganic terminal acceptor, and extra ATP.
- **RBCs ferment obligately** (no mitochondria); muscle ferments under exertion; **Cori cycle** shuttles lactate to the liver for gluconeogenesis at a 6-ATP cost.
- **Warburg effect:** tumours ferment aerobically for speed and biosynthetic precursors, acidifying the environment — the basis of FDG-PET.
- **Lactic acidosis** = production outstripping clearance = tissue oxygen delivery failure.
- Yeast fermentation: bread (CO₂), wine/beer (ethanol); bacterial lactate fermentation preserves food by lowering pH.

## Practice questions

**1. The primary purpose of fermentation in an anaerobic cell is to**

A. Produce additional ATP
B. Regenerate NAD⁺ so glycolysis can continue
C. Oxidise glucose completely to CO₂
D. Create oxygen for the electron transport chain

**Answer: B**

Explanation: Glycolysis consumes NAD⁺ at GAPDH; with the chain stopped, NADH would deplete the pool and glycolysis would halt. Fermentation dumps NADH's electrons onto pyruvate (or a derivative), returning NAD⁺ — the only service it provides. The 2 ATP come from glycolysis itself, unchanged.

---

**2. Which is a correct comparison of fermentation and anaerobic respiration?**

A. Fermentation uses an electron transport chain; anaerobic respiration does not
B. Anaerobic respiration uses an inorganic final electron acceptor and yields extra ATP; fermentation uses an organic acceptor and yields none beyond glycolysis
C. Both produce large ATP yields
D. Anaerobic respiration requires oxygen

**Answer: B**

Explanation: Anaerobic respiration means using nitrate, sulfate, or another inorganic molecule instead of O₂ as the terminal acceptor — a real chain with proton pumping and extra ATP. Fermentation has no chain at all; pyruvate or a derivative accepts the electrons. Neither requires oxygen (D), which is the point of both.

---

**3. During intense exercise, muscle accumulates lactate because**

A. The electron transport chain produces lactate
B. Oxygen is insufficient for the chain, so pyruvate is reduced to lactate to regenerate NAD⁺ for glycolysis
C. Lactate is the normal product of aerobic respiration
D. Mitochondria convert pyruvate to lactate directly

**Answer: B**

Explanation: When ATP demand outstrips oxygen delivery, NADH cannot be reoxidised through the chain, so LDH transfers its electrons to pyruvate — regenerating NAD⁺ and allowing glycolysis to keep making ATP. It is a cytosolic rescue route, not a mitochondrial one (D), and aerobic respiration ends at CO₂ and water (C).

---

**4. In the Cori cycle, lactate produced in muscle is**

A. Excreted by the kidney
B. Taken up by the liver and converted back to glucose, which returns to muscle
C. Converted to ATP within the muscle
D. Converted to fatty acid in muscle

**Answer: B**

Explanation: The liver performs gluconeogenesis from lactate (costing 6 ATP per glucose made) and exports the glucose, which the muscle reuses. The muscle gets rapid ATP at low efficiency; the liver reclaims the carbon. Lactate is a recyclable fuel intermediate, not a terminal waste product.

---

**5. Ethanol fermentation releases CO₂ but lactate fermentation does not. Why?**

A. Ethanol fermentation occurs in mitochondria
B. Pyruvate decarboxylase removes a carbon from pyruvate before reduction; LDH reduces pyruvate intact
C. Lactate fermentation produces more ATP
D. CO₂ is toxic to animal cells

**Answer: B**

Explanation: The ethanol route first decarboxylates pyruvate to acetaldehyde (releasing CO₂), then reduces it to ethanol. Lactate dehydrogenase simply reduces the three-carbon pyruvate to three-carbon lactate — no carbon is lost. The difference is the enzyme path, not the compartment or energy yield.

---

**6. A tumour cell with plentiful oxygen converting glucose to lactate illustrates**

A. Complete oxidative metabolism
B. The Warburg effect — aerobic glycolysis used for speed and biosynthetic intermediates
C. A failure of glycolysis
D. Mitochondrial complex IV deficiency

**Answer: B**

Explanation: Many cancer cells preferentially ferment glucose even in normoxia — aerobic glycolysis. The payoff is fast ATP and diversion of glycolytic intermediates into nucleotide, lipid, and amino acid synthesis for division, plus an acidic environment that aids invasion. It is a deliberate metabolic programme, not oxygen deprivation.

---

**7. Why do mature red blood cells necessarily ferment?**

A. They lack glycolytic enzymes
B. They have no mitochondria, so pyruvate cannot be oxidised and NAD⁺ must be regenerated by lactate production
C. They have no haemoglobin to carry oxygen
D. They lack the enzyme that produces lactate

**Answer: B**

Explanation: Enucleation removes the nucleus and organelles — including mitochondria — so the chain, citric acid cycle, and aerobic ATP production are unavailable. Glycolysis plus LDH-mediated lactate fermentation is their only route to ATP, which keeps their pumps and deformability running. They do have LDH and glycolytic enzymes (D, A) and haemoglobin (C).

---

**8. Which of the following is NOT a function of fermentation?**

A. Regenerating NAD⁺
B. Allowing glycolysis to continue without oxygen
C. Producing the bulk of the cell's ATP
D. Generating lactate or ethanol as end products

**Answer: C**

Explanation: Fermentation produces no ATP beyond glycolysis's net 2 — the bulk of ATP (~28) comes from oxidative phosphorylation, which by definition is unavailable during fermentation. Regenerating NAD⁺ (A), sustaining glycolysis (B), and yielding lactate or ethanol (D) are precisely what fermentation does.

---

**9. Lactic acidosis in a patient with circulatory shock is best explained by**

A. Overactive mitochondria
B. Tissue oxygen delivery failing, forcing widespread anaerobic glycolysis with lactate production exceeding hepatic clearance
C. Excess dietary lactate
D. Blocking of the citric acid cycle by oxygen

**Answer: B**

Explanation: Shock means poor perfusion, so tissues receive insufficient oxygen regardless of arterial oxygen content; the chain stops, cells ferment, and lactate accumulates faster than the liver can clear it. The measurement is a readout of tissue-level oxygen adequacy. Mitochondria are underperforming, not overactive (A).

---

**10. How does alcohol metabolism in the liver cause fasting hypoglycaemia?**

A. Ethanol is converted directly to glucose
B. Ethanol oxidation produces large amounts of NADH, raising the NADH/NAD⁺ ratio and inhibiting gluconeogenesis
C. Alcohol destroys pancreatic β-cells permanently
D. Ethanol inhibits intestinal glucose absorption only

**Answer: B**

Explanation: Alcohol dehydrogenase and aldehyde dehydrogenase both generate NADH. The resulting high NADH/NAD⁺ ratio blocks the pyruvate dehydrogenase and citric acid cycle steps and stalls gluconeogenesis (lactate → pyruvate equilibrium shifts), so the liver cannot maintain blood glucose during fasting. It is a redox problem, not a substrate or absorption problem.
