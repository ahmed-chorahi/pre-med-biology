# Glycolysis

## Why it matters

Glycolysis is the pathway almost every living cell shares — bacteria, plants, your neurons, your red blood cells. It splits a six-carbon glucose into two three-carbon pyruvates, making a small amount of ATP directly and loading electrons onto NADH. It happens in the **cytoplasm**, needs **no oxygen**, and runs whether or not mitochondria exist.

Its importance is threefold: it is the **entry point for all carbohydrate fuel**, it is the **only pathway available to anaerobic cells**, and it is the pathway whose regulation sets the tone for the whole metabolism you will study in the next three chapters.

## The scheme at a glance

```
                    INVESTMENT PHASE (costs 2 ATP)
   glucose (C6)
      │   hexokinase ▶ glucose-6-phosphate        irreversible #1
      │   isomerise   ▶ fructose-6-phosphate
      │   PFK-1 ▶ fructose-1,6-bisphosphate       irreversible #2 ★ rate-limiting
      │   split       ▶ DHAP ⇄ glyceraldehyde-3-phosphate (G3P)   (×2 from here)
      │
                    PAYOFF PHASE (makes 4 ATP + 2 NADH)
      │   glyceraldehyde-3-phosphate ─▶ 1,3-BPG   (NADH made)
      │   ─▶ 3-phosphoglycerate       (ATP made)
      │   ─▶ 2-phosphoglycerate ─▶ phosphoenolpyruvate (PEP)
      │   pyruvate kinase ▶ PYRUVATE              irreversible #3 (ATP made)
      ▼
   2 × pyruvate (C3)

NET: glucose + 2 NAD⁺ + 2 ADP + 2 Pᵢ ─▶ 2 pyruvate + 2 NADH + 2 ATP + 2 H₂O
```

**The architecture matters more than memorising all ten enzymes:**

- **Two irreversible steps** — hexokinase, phosphofructokinase-1 (PFK-1), pyruvate kinase — are the regulation points. Everything reversible can run both ways in gluconeogenesis; these three cannot, which is why they control direction.
- **One ATP "investment," two ATP "payoff" per half-pathway → net 2 ATP.** The cell spends 2 to earn 4.
- **One oxidation step** — glyceraldehyde-3-phosphate dehydrogenase — is where NADH is captured. That single step is the pathway's energy harvest beyond substrate-level phosphorylation.

## The three irreversible steps, and their control

### 1. Hexokinase — gatekeeper of entry

Glucose → glucose-6-phosphate. Traps glucose inside the cell (a phosphate gives it a charge, and charged molecules cannot cross the membrane). **Inhibited by its own product** (glucose-6-phosphate) — simple product inhibition preventing pointless trapping when downstream pathways are saturated.

The liver uses **glucokinase** instead: same reaction, *not* inhibited by G6P, and only active when glucose is high — so the liver takes up glucose when the body has plenty and releases it when the body does not. Same chemistry, different regulation, different organ logic.

### 2. PFK-1 — the committed step ★

Fructose-6-phosphate → fructose-1,6-bisphosphate. **This is the rate-limiting step of glycolysis and its primary regulation point**, because it is the first step unique to glycolysis — everything before it can also feed other pathways.

| Signal | Effect on PFK-1 | Meaning |
| --- | --- | --- |
| **High ATP** | **Inhibits** | Energy charge is high — slow down |
| **High citrate** | **Inhibits** | Krebs cycle is full — stop feeding it |
| **High AMP** | **Activates** | Energy charge is low — speed up |
| **Fructose-2,6-bisphosphate** | **Strong activator** | Insulin-mediated signal of the fed state |

**This is the same logic as feedback inhibition in [05 — Enzymes](../01-biochemistry/05-enzymes.md):** the cell's energy status directly tunes the pathway's throttle. ATP inhibiting its own production pathway is negative feedback at the metabolic level.

### 3. Pyruvate kinase — committing to pyruvate

PEP → pyruvate. **Activated by fructose-1,6-bisphosphate** (feed-forward activation — the pathway's earlier product primes its last step) and **inhibited by ATP and alanine** (alanine signals that protein is being made from pyruvate's transamination product; do not burn it).

**Feed-forward activation** deserves a word: it means the middle of a pathway accelerates the end of it, so intermediates do not pile up. Pathways are wired in both directions — feedback brakes and feed-forward throttle.

## What glycolysis actually yields

| Product | Per glucose | Purpose |
| --- | --- | --- |
| **Net ATP** | **2** | Substrate-level phosphorylation (PGK and pyruvate kinase make it directly) |
| **NADH** | **2** | Electrons for the ETC — *if* mitochondria and O₂ are available |
| **Pyruvate** | **2** | The entry ticket to the citric acid cycle (aerobic) or the substrate for fermentation (anaerobic) |

**Substrate-level phosphorylation** — ATP made by transferring a phosphate directly from a substrate to ADP, *without* a proton gradient — is contrasted with **oxidative phosphorylation** (chapter 07), which makes most of the cell's ATP by a completely different mechanism. Knowing which is which explains the entire energy budget.

**Only 2 ATP from a 30-carbon-equivalent oxidation?** Glycolysis deliberately extracts little: the glucose is not yet *oxidised* — most of its electrons are still in pyruvate. The big harvest happens downstream in the mitochondrion. Glycolysis's job is to **prepare the fuel and make a starter amount of ATP that works without oxygen.**

## The fate of pyruvate

The branch point of carbohydrate metabolism:

```
                         ┌── AEROBIC: pyruvate → acetyl-CoA → citric acid cycle
                         │            (mitochondria, ~30 ATP total per glucose)
pyruvate (2) ────────────┤
                         ├── ANAEROBIC (animal): → LACTATE
                         │            regenerates NAD⁺, no extra ATP
                         │
                         └── ANAEROBIC (yeast): → ETHANOL + CO₂
                                    regenerates NAD⁺
```

Which route is taken is decided by **whether the cell has mitochondria and oxygen**, and by whether the NADH produced can be shuttled into them. The three fates are chapters 06, 08, and 07 respectively — this chapter ends at the branch point.

**The decision rule:** *pyruvate goes to the mitochondrion if there is oxygen and a way to deliver electrons there; otherwise it becomes lactate or ethanol to regenerate NAD⁺ so glycolysis can continue.*

## Why anaerobic cells need fermentation at all

Glycolysis's oxidation step consumes **NAD⁺**. If nothing reoxidises NADH, NAD⁺ runs out and **glycolysis stops** — the pathway cannot proceed past glyceraldehyde-3-phosphate dehydrogenase without a supply of NAD⁺.

```
NAD⁺ limited pool
   │
   ▼
used by GAPDH ──▶ NADH
   │                    if no ETC to recycle:
   ▼                    NAD⁺ NOT regenerated
glycolysis STOPS        → fermentation passes electrons from NADH to pyruvate
                        → NAD⁺ returned → glycolysis continues
```

**Fermentation is not a way to make energy** — it makes no ATP beyond glycolysis's 2. It is a way to **recycle NAD⁺** so the 2 ATP keep coming. This is chapter 08's entire point and is the single most misunderstood idea in basic metabolism.

## Regulation in context: the fed and fasting states

| State | Hormonal signal | Effect on glycolysis |
| --- | --- | --- |
| **Fed (high glucose, insulin)** | Insulin ↑ | Induces glucokinase, PFK-2 (makes F-2,6-BP), pyruvate kinase → **glycolysis runs**, glucose stored |
| **Fasting (low glucose, glucagon)** | Glucagon ↑ (liver) | Fructose-2,6-bisphosphate falls → PFK-1 slows → **glycolysis suppressed**, glucose spared for the brain |

**Liver glycolysis is deliberately throttled during fasting** because the liver's job then is to *make* glucose for other organs, not consume it. The same pathway is promoted or suppressed in different tissues for different reasons — muscle runs glycolysis hard during exercise regardless, because it needs ATP locally and can afford to produce lactate.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Glycolysis requires oxygen" | It does not — it is **anaerobic by definition**. Oxygen decides what happens *to pyruvate afterward*. |
| "Glycolysis makes most of the ATP" | It makes **2 net**; oxidative phosphorylation makes ~28 of the ~30. |
| "Fermentation produces ATP" | **No.** Only glycolysis does; fermentation only regenerates NAD⁺. |
| "Glycolysis happens in mitochondria" | It happens in the **cytoplasm**. Mitochondria only see pyruvate. |
| "Lactate is a waste product" | Lactate is a **NAD⁺-regenerating product**; it is also a gluconeogenesis substrate (Cori cycle). |

## Medical relevance

**Red blood cells are obligate glycolysers.** Mature erythrocytes have no mitochondria — everything they do runs on glycolysis and fermentation, which is why they produce lactate continuously and why they depend entirely on glucose supply. Their ATP runs the Na⁺/K⁺ pump and maintains their deformability.

**The Warburg effect revisited:** many tumour cells run glycolysis heavily even with oxygen present, fermenting to lactate — a less efficient but *faster* ATP strategy that also supplies biosynthetic intermediates for rapidly dividing cells. That reliance underlies **FDG-PET imaging**.

**Pyruvate kinase deficiency** is an inherited haemolytic anaemia — the payoff-phase enzyme fails, ATP in red cells falls, and the cells become rigid and are destroyed. A direct lesson: *a glycolytic enzyme defect presents as blood disease, because blood cells depend on this pathway most.*

**Toxins that block the pathway:** **fluoride** inhibits enolase (used in blood collection tubes to prevent glycolysis from consuming glucose); **arsenate** uncouples the GAPDH step; **iodoacetate** alkylates the enzyme's cysteine. Each is a named poison because each is a named step.

**Lactic acidosis** accumulates when lactate production outstrips clearance — shock, extreme exertion, sepsis, or metformin-associated cases — and is the clinical face of anaerobic glycolysis running systemically.

## Key facts

- Location: **cytoplasm**; no organelle, no oxygen required; universal across domains of life.
- **Net yield: 2 ATP + 2 NADH + 2 pyruvate per glucose** (2 invested, 4 made).
- Three **irreversible, regulated** steps: **hexokinase** (product-inhibited), **PFK-1** (rate-limiting; inhibited by ATP and citrate, activated by AMP and fructose-2,6-bisphosphate), **pyruvate kinase** (feed-forward activated by F-1,6-BP; inhibited by ATP and alanine).
- **Substrate-level phosphorylation** makes glycolysis's ATP directly — no gradient, no oxygen.
- Pyruvate's three fates: **→ acetyl-CoA (aerobic), → lactate, → ethanol + CO₂** — chosen by oxygen availability and mitochondrial capacity.
- **NAD⁺ must be regenerated** or glycolysis halts; fermentation is the anaerobic regeneration route and makes **no additional ATP**.
- Insulin accelerates glycolysis; glucagon (liver) suppresses it — via fructose-2,6-bisphosphate.
- Red cells: no mitochondria → obligate glycolysis; pyruvate kinase deficiency → haemolytic anaemia.

## Practice questions

**1. The net ATP yield of glycolysis per molecule of glucose is**

A. 4
B. 2
C. 36
D. 1

**Answer: B**

Explanation: Four ATP are produced (two per triose), but two were invested in the preparatory phase, so the net is 2. The larger yield of ~30 ATP comes from oxidative phosphorylation downstream, not glycolysis itself.

---

**2. Phosphofructokinase-1 is considered the rate-limiting enzyme of glycolysis because**

A. It is the first enzyme in the pathway
B. It catalyses the first step unique to glycolysis, making it the committed step
C. It has the fastest catalytic rate
D. It is the only enzyme located in mitochondria

**Answer: B**

Explanation: Earlier steps feed other pathways (glucose-6-phosphate can enter the pentose pathway or glycogen synthesis), so those do not commit glucose to glycolysis. PFK-1's product does — making it the control point. Regulation at the committed step means the cell does not waste resources committing fuel it may not want to burn.

---

**3. Which combination correctly describes allosteric regulation of PFK-1?**

A. ATP and citrate activate; AMP inhibits
B. ATP and citrate inhibit; AMP and fructose-2,6-bisphosphate activate
C. ATP inhibits glycolysis only at pyruvate kinase
D. Fructose-2,6-bisphosphate inhibits PFK-1 during fasting

**Answer: B**

Explanation: High ATP and citrate signal ample energy and a full Krebs cycle, so they slow the pathway; low energy (AMP) and the fed-state signal fructose-2,6-bisphosphate accelerate it. This lets the cell's energy charge set glycolytic flux directly.

---

**4. Why must fermentation occur in anaerobic cells even though it produces no ATP itself?**

A. To make NAD⁺ so glycolysis can continue producing its 2 ATP
B. To produce additional ATP anaerobically
C. To create oxygen
D. To oxidise pyruvate completely

**Answer: A**

Explanation: The GAPDH step of glycolysis consumes NAD⁺; without a route to reoxidise NADH, the pool depletes and glycolysis halts. Fermentation passes electrons from NADH to pyruvate (or a derivative), regenerating NAD⁺ — allowing the ATP-producing steps to keep running. Fermentation adds no ATP of its own.

---

**5. Which organelle does glycolysis occur in?**

A. Mitochondrial matrix
B. Rough endoplasmic reticulum
C. Cytosol
D. Nucleus

**Answer: C**

Explanation: All ten enzymes are cytosolic. Pyruvate is the product that travels into the mitochondrion for further oxidation. Nothing in glycolysis requires a compartment or oxygen, which is why the pathway works in enucleated red cells and in anaerobic bacteria alike.

---

**6. Which statement about pyruvate kinase is correct?**

A. It is allosterically activated by ATP
B. It is the irreversible step converting phosphoenolpyruvate to pyruvate, producing ATP by substrate-level phosphorylation, and is feed-forward activated by fructose-1,6-bisphosphate
C. It catalyses the first step of glycolysis
D. It requires NAD⁺ as a coenzyme

**Answer: B**

Explanation: Pyruvate kinase makes the pathway's last ATP directly from PEP — the highest-energy phosphate transfer in glycolysis — and is stimulated by the upstream intermediate fructose-1,6-bisphosphate so the pathway's middle accelerates its end. ATP *inhibits* it (A); hexokinase is first (C); NAD⁺ is used at GAPDH, not here (D).

---

**7. A patient with pyruvate kinase deficiency would most likely present with**

A. Liver failure only
B. Haemolytic anaemia
C. Diabetes mellitus
D. Loss of sensation

**Answer: B**

Explanation: Mature red blood cells have no mitochondria and depend entirely on glycolysis for the ATP that maintains their ion pumps and deformability. Without pyruvate kinase, ATP falls, cells become rigid and are destroyed — a haemolytic anaemia. The pathway's tissue dependency determines the disease's location.

---

**8. Which molecule is NOT a product of glycolysis?**

A. Pyruvate
B. NADH
C. ATP
D. Acetyl-CoA

**Answer: D**

Explanation: Glycolysis ends at pyruvate; acetyl-CoA is formed in the mitochondrial link reaction (pyruvate oxidation), the next chapter. Pyruvate, NADH, and net ATP are all direct products in the cytosol.

---

**9. During fasting, glucagon suppresses liver glycolysis mainly by**

A. Destroying glycolytic enzymes
B. Lowering fructose-2,6-bisphosphate, relieving PFK-1 activation
C. Removing oxygen from the liver
D. Converting glucose to pyruvate irreversibly

**Answer: B**

Explanation: Glucagon signalling in the liver lowers fructose-2,6-bisphosphate — the most potent activator of PFK-1 — so glycolytic flux falls and glucose is spared for export to the brain. Enzymes are not destroyed (A); the liver remains fully oxygenated (C); the point is to *reduce* flux through the pathway.

---

**10. Fluoride is added to blood collection tubes to**

A. Preserve red blood cell shape
B. Inhibit glycolysis so the tube's glucose concentration is not lowered by the cells' metabolism
C. Prevent bacterial contamination
D. Activate pyruvate kinase

**Answer: B**

Explanation: Cells in a drawn sample continue metabolising glucose; that would artefactually lower the measured glucose. Fluoride inhibits enolase, blocking glycolysis and preserving the glucose level for diagnosis. The reason a preservative works at all is that glycolysis runs continuously in every cell — including those outside the body.
