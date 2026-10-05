# Pyruvate Oxidation and the Citric Acid Cycle

## Why it matters

Glycolysis ends with pyruvate — a three-carbon molecule still holding most of glucose's energy. This chapter covers the two stages that finish the job: **pyruvate oxidation** (the short "link reaction") and the **citric acid cycle** (Krebs cycle, TCA cycle), both inside the mitochondrial matrix.

Together they do two things: they **oxidise the fuel completely to CO₂**, and they **load the electron carriers NADH and FADH₂** with the electrons that the next chapter converts into ATP. Only ~4 of the ~30 ATP per glucose appear directly here — the cycle's real product is not ATP, it is **reduced carriers**.

## Pyruvate oxidation (the link reaction)

Pyruvate from glycolysis is transported into the mitochondrial matrix and converted to **acetyl-CoA** — the universal two-carbon fuel-entry molecule.

```
PYRUVATE (C3, cytoplasm → matrix)
    │
    │  PYRUVATE DEHYDROGENASE COMPLEX (five cofactors!)
    │
    ├─ CO₂ released  (first carbon lost — this is an oxidation)
    ├─ NAD⁺ → NADH   (the electrons)
    └─ CoA attached
    ▼
ACETYL-CoA (C2)
```

**The reaction is irreversible** and it is the **point of no return for glucose carbon** — once pyruvate becomes acetyl-CoA, that carbon is committed to the cycle (or to fatty acid synthesis, if energy is plentiful). The pyruvate that entered can no longer become glucose.

### The enzyme and its cofactors

The pyruvate dehydrogenase complex is enormous — three enzymes working as a unit — and requires **five coenzymes**, three of them derived from B vitamins:

| Cofactor | Vitamin precursor | Role |
| --- | --- | --- |
| **TPP** (thiamine pyrophosphate) | **B₁** thiamine | Decarboxylation |
| **Lipoamide** | — | Acyl carrier and reoxidiser |
| **CoA** | **B₅** pantothenic acid | Accepts the acetyl group |
| **FAD** | **B₂** riboflavin | Electron acceptance |
| **NAD⁺** | **B₃** niacin | Final electron acceptor |

**Why this matters clinically:** a deficiency of any of these vitamins disables this complex — and the same five-coenzyme machinery runs **α-ketoglutarate dehydrogenase** in the cycle and **branched-chain α-ketoacid dehydrogenase** (maple syrup urine disease). **B₁ (thiamine) deficiency** therefore hits pyruvate oxidation hardest: brain cells, which depend on glucose oxidation, fail — **Wernicke–Korsakoff syndrome**, the neurological complication of chronic alcoholism (whose smooth-ER induction you met in 02 — Cell Biology).

**Arsenate and arsenite poison this step** by binding the lipoamide's sulfhydryl groups — a classic metabolic poison because the complex cannot run without them.

## The citric acid cycle

**Eight reactions in the mitochondrial matrix** that take acetyl-CoA's two carbons and release them as CO₂ while transferring the extracted electrons to NAD⁺ and FAD.

### The reactions, in order

| # | Reaction | Enzyme (memorise these four names) | Key feature |
| --- | --- | --- | --- |
| 1 | Acetyl-CoA (C2) + oxaloacetate (C4) → **citrate (C6)** | **Citrate synthase** | **Irreversible**; condensation; CoA released |
| 2 | Citrate → isocitrate | Aconitase | Isomerisation (moves the OH) |
| 3 | Isocitrate → α-ketoglutarate (C5) + **CO₂** | **Isocitrate dehydrogenase** | **Irreversible; rate-limiting**; NADH made |
| 4 | α-ketoglutarate (C5) → succinyl-CoA (C4) + **CO₂** | **α-ketoglutarate dehydrogenase** | **Irreversible**; NADH made; same 5-coenzyme complex |
| 5 | Succinyl-CoA → succinate | Succinyl-CoA synthetase | **GTP** made (substrate-level phosphorylation) |
| 6 | Succinate → fumarate | Succinate dehydrogenase | **FADH₂** made; the only enzyme in the inner membrane (Complex II) |
| 7 | Fumarate → malate | Fumarase | Hydration |
| 8 | Malate → **oxaloacetate** | Malate dehydrogenase | **NADH** made — regenerates the acceptor |

### The yield per turn (per acetyl-CoA)

```
        3 NADH   1 FADH₂   1 GTP   2 CO₂
```

**Per glucose (two turns):**

```
        6 NADH   2 FADH₂   2 GTP   4 CO₂
```

**Combined with the link reaction, one glucose produces 8 NADH, 2 FADH₂, 2 GTP before oxidative phosphorylation even begins.**

### The critical structural point: the cycle regenerates its acceptor

```
OAA (C4) + acetyl-CoA (C2) ──▶ citrate (C6) ──▶ ... ──▶ 2 CO₂ out ──▶ OAA (C4) again
```

**Oxaloacetate is a catalyst, not a consumed substrate.** The cycle turns because OAA is regenerated at step 8. This is why the pathway can run continuously as long as acetyl-CoA and NAD⁺/FAD are supplied — and why *anything that depletes OAA stops the whole cycle*, an idea that explains anaplerosis below.

### The cycle is amphibolic

It is both catabolic and anabolic:

| Direction | Role |
| --- | --- |
| **Catabolic** | Burns acetyl-CoA from carbohydrates, fats, and amino acids → electrons → ATP |
| **Anabolic** | Provides **biosynthetic precursors** — citrate → fatty acids; succinyl-CoA → haem; OAA → gluconeogenesis (via PEPCK); α-ketoglutarate → glutamate → amino acids |

**Anaplerotic reactions** refill intermediates drawn off for biosynthesis — the most important being **pyruvate carboxylase: pyruvate → oxaloacetate** (biotin-dependent, activated by acetyl-CoA). *If the cell siphons off OAA to make glucose, pyruvate carboxylase replaces it, or the cycle stalls.* Refilling is not optional maintenance; it is what keeps amphibolic pathways running.

### All three fuel types enter here

```
CARBOHYDRATES ──▶ glycolysis ──▶ pyruvate ──▶ acetyl-CoA ─┐
FATS ──▶ β-oxidation ──▶ acetyl-CoA ──────────────────────┼──▶ CITRIC ACID CYCLE
AMINO ACIDS ──▶ carbon skeletons ──▶ pyruvate/OAA/        │
                α-ketoglutarate/succinyl-CoA/fumarate ─────┘
```

**This is why the cycle is the metabolic crossroads.** Every macromolecule converges on it, which also explains why you **cannot convert fat to glucose** in net terms: fatty acids yield acetyl-CoA, and the two carbons entering as acetyl-CoA are lost as CO₂ before reaching OAA — so there is no net carbon left to build new glucose. Glycerol (the fat's backbone) can become glucose; the fatty acid chains cannot.

## Regulation

The cycle runs only when the cell needs it. The three irreversible enzymes respond to the cell's energy charge:

| Enzyme | Activated by | Inhibited by |
| --- | --- | --- |
| **Citrate synthase** | OAA, acetyl-CoA | ATP, NADH, citrate |
| **Isocitrate dehydrogenase** (rate-limiting) | **ADP, Ca²⁺** | **ATP, NADH** |
| **α-ketoglutarate dehydrogenase** | Ca²⁺ | ATP, NADH, succinyl-CoA |

**The pattern:** low energy (high ADP) and muscle contraction signals (Ca²⁺) speed it up; high energy (ATP, NADH) slows it. Exactly like PFK-1 in glycolysis — **the whole metabolic system reads the same two signals: adenine nucleotides and reducing equivalents.**

**Ca²⁺ activating three enzymes simultaneously** is the elegant link between muscle contraction and energy supply: the calcium that triggers contraction also switches on the cycle that makes the ATP to pay for it.

## Where the energy went

Glucose is now fully oxidised — all six carbons are CO₂. The energy is not in ATP yet; it is in **8 NADH and 2 FADH₂ per glucose** (plus 2 GTP made directly). Electrons carried by those molecules are worth the large majority of glucose's total free energy, and they are delivered to the electron transport chain in the next chapter.

```
GLUCOSE ──▶ 2 pyruvate ──▶ 2 acetyl-CoA ──▶ 4 CO₂
   six carbons out as CO₂; energy parked in electron carriers
```

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The cycle makes a lot of ATP" | It makes **2 GTP per glucose** — only ~4 ATP equivalent after shuttle costs. Its product is **NADH/FADH₂**. |
| "The citric acid cycle is only for carbohydrates" | It burns acetyl-CoA from **fats, carbs, and amino acids** — it is the crossroads, not a glucose pathway. |
| "CO₂ we exhale comes from the air we inhale" | Exhaled CO₂ contains **carbon from food**, fixed by this cycle and pyruvate dehydrogenase. |
| "The cycle turns once per glucose" | **Twice** — one turn per acetyl-CoA. |
| "Oxaloacetate is used up each turn" | It is **regenerated** — it is the catalytic acceptor. |

## Medical relevance

**Thiamine (B₁) deficiency** — impaired pyruvate dehydrogenase and α-ketoglutarate dehydrogenase → brain cannot oxidise glucose → **Wernicke–Korsakoff** (confusion, ataxia, ophthalmoplegia; then permanent memory loss). Also seen in malnutrition and after bariatric surgery. Treatable if caught early — **the biochemistry is reversible, the neuronal damage may not be.**

**Beriberi** — the same enzyme defect expressed as heart failure and neuropathy in B₁-deficient diets, because heart and nerve are the most energy-dependent tissues.

**Viral mimicry against this cycle:** **reovirus** and certain cancers alter cycle enzyme expression; the observation that **many tumours accumulate citrate** and export it (rather than burning it) reframed the cycle as a biosynthetic hub, not just an energy furnace — citrate leaving the mitochondrion becomes the carbon source for fatty acid synthesis in proliferating cells.

**Poisons:** **arsenite** (binds lipoate), **fluoroacetate** ("lethal synthesis" — converted to fluorocitrate, which blocks aconitase), **cyanide** (next chapter — blocks the cycle's electrons downstream). Each targets a named step.

**Anaplerotic failure** appears clinically in **propionic and methylmalonic acidemias** — organic acidemias where odd-chain and certain amino acid catabolism cannot feed the cycle cleanly, intermediates accumulate, and the cycle's flux falls. Refilling, and the enzymes of entry, are as essential as the cycle itself.

## Key facts

- **Link reaction:** pyruvate → acetyl-CoA + CO₂ + NADH, by the **pyruvate dehydrogenase complex** requiring **TPP, lipoamide, CoA, FAD, NAD⁺** (vitamins B₁, B₅, B₂, B₃). Irreversible; the point of no return for glucose carbon.
- Cycle occurs in the **mitochondrial matrix**; **turns twice per glucose**.
- **Per turn: 3 NADH, 1 FADH₂, 1 GTP, 2 CO₂.** Per glucose: 6 NADH, 2 FADH₂, 2 GTP, 4 CO₂.
- Four named irreversible enzymes: **citrate synthase, isocitrate dehydrogenase (rate-limiting), α-ketoglutarate dehydrogenase, and (in gluconeogenesis terms) the cycle's exit via PEPCK** — plus the link reaction itself.
- **Oxaloacetate is regenerated**, not consumed — the cycle is catalytic in its acceptor.
- **Amphibolic:** catabolic for energy, anabolic for precursors (citrate→fat, succinyl-CoA→haem, OAA→glucose, α-KG→glutamate).
- **Cannot net-convert fat to glucose** — acetyl-CoA carbons are lost as CO₂ before reaching OAA; glycerol can.
- **Anaplerosis** (pyruvate carboxylase: pyruvate → OAA) refills intermediates drawn off for biosynthesis.
- Regulation reads **ADP/Ca²⁺ (up) vs ATP/NADH (down)** at the three irreversible enzymes.
- **B₁ deficiency** → impaired link reaction and α-KG dehydrogenase → Wernicke–Korsakoff, beriberi.

## Practice questions

**1. The primary purpose of the citric acid cycle is to**

A. Produce most of the cell's ATP directly
B. Oxidise acetyl-CoA to CO₂ while loading NADH and FADH₂ for oxidative phosphorylation
C. Split glucose into two pyruvates
D. Produce oxygen

**Answer: B**

Explanation: The cycle itself makes only 2 GTP per glucose; its real yield is the electrons captured in 6 NADH and 2 FADH₂, which the electron transport chain converts into the large ATP payoff. Glycolysis performs the splitting (C), and oxygen is consumed downstream, never produced (D).

---

**2. One turn of the citric acid cycle produces which set of products?**

A. 3 NADH, 1 FADH₂, 1 GTP, 2 CO₂
B. 2 NADH, 2 FADH₂, 2 ATP, 1 CO₂
C. 6 NADH, 2 FADH₂, 2 GTP
D. 4 ATP, 4 NADH

**Answer: A**

Explanation: Per acetyl-CoA entering, three dehydrogenases make 3 NADH, succinate dehydrogenase makes 1 FADH₂, substrate-level phosphorylation makes 1 GTP, and two decarboxylations release 2 CO₂. Option C is the yield *per glucose* (two turns), not per turn.

---

**3. Which enzyme is the rate-limiting step of the citric acid cycle?**

A. Citrate synthase
B. Isocitrate dehydrogenase
C. Malate dehydrogenase
D. Aconitase

**Answer: B**

Explanation: Isocitrate dehydrogenase is allosterically activated by ADP and Ca²⁺ and inhibited by ATP and NADH — the classic control point responding to the cell's energy charge. Citrate synthase is the first committed step and is regulated too, but the principal flux controller is isocitrate dehydrogenase.

---

**4. Why is the pyruvate dehydrogenase complex clinically significant in thiamine deficiency?**

A. It requires thiamine as an allosteric inhibitor
B. TPP is a required cofactor, so B₁ deficiency impairs pyruvate oxidation and α-ketoglutarate dehydrogenase, depriving the brain of ATP
C. Thiamine is the enzyme's substrate
D. Thiamine deficiency blocks glycolysis directly

**Answer: B**

Explanation: TPP (thiamine pyrophosphate) is essential for the decarboxylation steps of both PDH and α-ketoglutarate dehydrogenase. Without it, glucose cannot be oxidised past pyruvate, and high-energy tissues — brain, heart, peripheral nerves — fail. Wernicke–Korsakoff and beriberi are the clinical expressions; glycolysis itself does not require thiamine.

---

**5. Oxaloacetate functions in the citric acid cycle as**

A. A consumed substrate that must be resynthesised each turn
B. The regenerated acceptor that condenses with acetyl-CoA — a catalytic participant
C. An inhibitor of citrate synthase
D. A product excreted from the cell

**Answer: B**

Explanation: OAA joins acetyl-CoA to form citrate and is regenerated at the malate dehydrogenase step — it is used but not used up, exactly as a catalyst. The cycle turns continuously as long as OAA is present, which is why anaplerotic reactions must replenish any OAA siphoned off for biosynthesis.

---

**6. Which statement explains why fatty acids cannot be converted to glucose in net terms?**

A. Fatty acids contain no carbon
B. Fatty acids are broken down to acetyl-CoA, whose two carbons are lost as CO₂ before reaching oxaloacetate, so no net carbon is available to form new glucose
C. Glucose cannot be made from any fat-related molecule
D. The enzymes are absent in animal cells

**Answer: B**

Explanation: Acetyl-CoA entering the cycle loses both of its carbons as CO₂ within the first turn and does not yield a net OAA surplus (the cycle's OAA is regenerated, not increased). Animals lack a glyoxylate cycle to fix that, so net gluconeogenesis from the fatty acid chains is impossible. Glycerol from the triglyceride backbone *can* become glucose.

---

**7. A cell with high ATP and NADH levels will show which effect on the citric acid cycle?**

A. Increased flux through all steps
B. Inhibition of citrate synthase, isocitrate dehydrogenase, and α-ketoglutarate dehydrogenase, slowing the cycle
C. Activation of isocitrate dehydrogenase
D. No change — the cycle is constitutive

**Answer: B**

Explanation: ATP and NADH are the signals of energy abundance; they allosterically inhibit the three irreversible enzymes, slowing the cycle when the cell already has enough energy. ADP and Ca²⁺ are the activating signals (C). The cycle is heavily regulated, not constitutive.

---

**8. Anaplerotic reactions are best described as**

A. Reactions that completely oxidise glucose
B. Reactions that replenish citric acid cycle intermediates drawn off for biosynthesis
C. Reactions occurring only in the cytoplasm
D. The breakdown of fatty acids

**Answer: B**

Explanation: Because intermediates such as OAA, α-ketoglutarate, and succinyl-CoA are siphoned off to make amino acids, glucose, and haem, they must be refilled or the cycle stalls. Pyruvate carboxylase (pyruvate → OAA) is the classic anaplerotic enzyme. Without replenishment, an amphibolic pathway would run down.

---

**9. In which compartment does the citric acid cycle occur?**

A. Cytosol
B. Inner mitochondrial membrane
C. Mitochondrial matrix
D. Rough ER

**Answer: C**

Explanation: All eight soluble enzymes sit in the matrix, which is also where pyruvate dehydrogenase operates — so the link reaction and the cycle share a compartment. The electron transport chain (next chapter) is in the inner membrane, where the NADH and FADH₂ made here deliver their electrons.

---

**10. Which molecule is required for the link reaction but not for glycolysis?**

A. NAD⁺
B. Coenzyme A
C. ADP
D. Glucose

**Answer: B**

Explanation: CoA accepts the two-carbon acetyl group to form acetyl-CoA — a product of the link reaction, not of glycolysis. NAD⁺ is used by both (GAPDH in glycolysis, PDH in the link reaction); ADP is a glycolytic substrate; glucose is glycolysis's starting material. The distinctive requirement here is the vitamin B₅-derived CoA carrier.
