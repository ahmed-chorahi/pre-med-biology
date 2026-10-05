# The Electron Transport Chain and ATP Synthase

## Why it matters

This is where a cell's energy budget is actually paid. Glycolysis and the citric acid cycle extracted electrons from glucose and loaded them onto NADH and FADH₂ — carrying only a few ATP's worth of energy between them. The **electron transport chain** burns those electrons down a staircase to oxygen, uses the released energy to pump protons across a membrane, and **ATP synthase** converts the resulting gradient into ~28 of the ~30 ATP from one glucose.

The mechanism — **Peter Mitchell's chemiosmotic hypothesis**, for which he won the Nobel Prize — is one of the great ideas in biology: *energy is stored not in a chemical intermediate but in a **proton gradient across a membrane**.* Everything in this chapter follows from that single move.

## The setup

| Element | Location |
| --- | --- |
| **Electron transport chain (Complexes I–IV)** | Inner mitochondrial membrane |
| **ATP synthase (Complex V)** | Inner mitochondrial membrane |
| **NADH, FADH₂, O₂, ADP, Pᵢ** | Matrix / intermembrane space |
| **The proton gradient** | H⁺ accumulated in the **intermembrane space** |

```
INTERMEMBRANE SPACE     [H⁺] HIGH ──────────────┐
                               │                  │
   NADH ─e⁻▶ I ─▶ Q ─▶ III ─▶ cyt c ─▶ IV ─▶ O₂   │  electrons flow
   FADH₂ ─▶ II ────────┘            │      │      │  downhill
                                     │      └─ pumps H⁺ outward
   matrix:        II, and each pump ─┘             │
                                     │                  │
                                     ▼                  ▼
                              NAD⁺, FAD          GRADIENT STORED
                                                   │
                                     ATP SYNTHASE ←┘  H⁺ flows BACK in
                                                   │
                                                   ▼
                                            ADP + Pᵢ → ATP
```

**Two coupled processes:** electron flow *pushes* protons out; proton flow back *through ATP synthase* makes ATP. Block either one and ATP production stops.

## The chain, complex by complex

| Complex | Name | Electrons from | Reaction | Protons pumped per 2e⁻ |
| --- | --- | --- | --- | --- |
| **I** | NADH:ubiquinone oxidoreductase | **NADH** | NADH → ubiquinone (Q) | **4** |
| **II** | Succinate dehydrogenase | **FADH₂** | FADH₂ → Q | **0** |
| **III** | Cytochrome *bc₁* complex | QH₂ | Q → cytochrome *c* | **4** |
| **IV** | Cytochrome *c* oxidase | cyt *c* | cyt *c* → **O₂** (→ H₂O) | **2** |
| **V** | ATP synthase | H⁺ gradient | H⁺ flow → ATP | — (consumes gradient) |

Key points:

- **Oxygen is the final electron acceptor at Complex IV** — it is *not* branched off early, it is the very last stop, where 4 electrons reduce O₂ to 2 H₂O. Without O₂, the chain backs up: no electron sink, no pumping, no gradient, no ATP.
- **FADH₂ enters at Complex II**, bypassing Complex I — **fewer protons pumped per pair of electrons, hence fewer ATP** (FADH₂ ≈ 1.5 ATP vs NADH ≈ 2.5 ATP in modern accounting).
- **Complex II is citric acid cycle's succinate dehydrogenase** — the one cycle enzyme embedded in the membrane. The cycle and the chain are literally the same machine at that point.
- **Q (ubiquinone) and cytochrome *c*** are the mobile carriers shuttling electrons between the fixed complexes.

### The accounting, corrected

| Carrier | ATP per pair of electrons |
| --- | --- |
| NADH (matrix) | **2.5** |
| FADH₂ | **1.5** |
| Glycolytic NADH (depends on shuttle) | 1.5 or 2.5 |
| **Total per glucose** | **~30–32 ATP** |

Older texts say 36–38; they used whole numbers and ignored the cost of moving cytosolic NADH electrons across the membrane. The modern ~30–32 is the figure to use.

## Chemiosmosis: the actual mechanism

**Chemiosmotic coupling** has three requirements, and every question about uncouplers is testing whether you know them:

1. **A membrane** that is impermeable to H⁺ (the inner mitochondrial membrane).
2. **A pump** that moves H⁺ across it (Complexes I, III, IV).
3. **A return path** through **ATP synthase** that harnesses the flow.

```
        H⁺ pumped out against gradient → stores potential energy
        (like water behind a dam)

        H⁺ flows back through ATP synthase → kinetic energy →
        mechanical rotation → chemical bond (ATP)
```

**The proton-motive force** has two components: a **chemical gradient** (pH difference — matrix is more alkaline) and an **electrical gradient** (the intermembrane space is positive relative to the matrix). Together they are the battery.

### ATP synthase: a rotary motor

| Part | Composition | Function |
| --- | --- | --- |
| **F₀** | Membrane-embedded ring of *c* subunits | Proton channel; spins as H⁺ passes |
| **F₁** | Matrix-facing head (α₃β₃γδε) | Catalytic sites for ADP + Pᵢ → ATP on the **β** subunits |
| **The γ subunit** | Central stalk | **Rotates with F₀**, acting as a crankshaft inside F₁ |

```
H⁺ in ─▶ F₀ ring spins ─▶ γ stalk rotates ─▶ β subunits change shape
                                                  │
                           open → loose → tight → catalysis → ATP released
```

**Binding change mechanism (Boyer):** the three β subunits cycle through three conformations — *open* (release ATP), *loose* (bind ADP + Pᵢ), *tight* (form ATP). **Rotation cycles them through the states; the chemistry needs no energy input once the parts are together** — the energy goes into *releasing* the ATP and turning the crank. Roughly **4 protons flow per ATP** made (10 per full 3-turn rotation producing 3 ATP).

**Why a motor?** A rotary machine couples a continuous flow (protons) to a cyclic set of conformational changes — the most efficient way to convert one kind of energy into another repeatedly. ATP synthase runs at up to ~100 revolutions per second in active cells.

## Inhibitors and poisons — the map of the chain

Each toxin blocks a named site, and the question always asks what happens *upstream* and *downstream* of the block:

| Agent | Site | Consequence |
| --- | --- | --- |
| **Rotenone, barbiturates** | Complex I | Blocks electron entry from NADH; NADH accumulates |
| **Malonate** | Complex II | Competitive with succinate — blocks FADH₂ entry |
| **Antimycin A** | Complex III | Stops transfer to cytochrome *c* |
| **Cyanide, carbon monoxide, hydrogen sulfide** | **Complex IV** | **Block oxygen use** — chain stops entirely; O₂ not consumed |
| **Oligomycin** | ATP synthase (F₀ channel) | Stops ATP synthesis; gradient builds until pumping halts |
| **Uncouplers (DNP, aspirin in overdose)** | Membrane | Carry H⁺ across → **gradient dissipates as heat → no ATP** |

**The reasoning pattern:**

```
BLOCK electron transport (cyanide)
   → no pumping → no gradient → no ATP
   → O₂ NOT consumed (cannot accept electrons)
   → upstream carriers stuck reduced (NADH backs up)

BLOCK ATP synthase (oligomycin)
   → gradient builds and then STOPS pumping (no return flow)
   → O₂ consumption falls
   → respiration coupled to ATP use: when ATP use falls, O₂ use falls
```

**Cyanide poisoning in one line:** electrons cannot reach oxygen, so the chain jams, oxidative phosphorylation stops, and cells with the highest ATP demand — brain and heart — fail within minutes despite plentiful oxygen in the blood. **The blood is oxygenated; the cells cannot use it.**

**Uncouplers are the opposite failure:** the chain runs flat out (O₂ consumption *rises*), protons leak back without passing through ATP synthase, and the energy emerges as **heat** instead of ATP. Respiration and phosphorylation come apart — that is literally what "uncoupled" means.

## Coupling, control, and demand

The system is **demand-driven**, not supply-driven:

```
ATP used → ADP rises → ADP stimulates ATP synthase and the chain
                      → O₂ consumption rises
ATP abundant → little ADP → synthase idle → chain slows → O₂ falls
```

**State 3 vs state 4 respiration:** actively phosphorylating mitochondria (high ADP) consume O₂ fast; idle mitochondria (no ADP) slow to a crawl because **the gradient itself back-inhibits pumping**. The chain cannot pump against an ever-steeper gradient indefinitely — once full, it stops. This is why **oxygen consumption measures ATP demand**, and why a patient's metabolic rate can be read from O₂ use.

## Brown fat: deliberate uncoupling

**Thermogenin (UCP1)** is a regulated proton leak in the inner membrane of brown adipose tissue. When activated (by sympathetic signalling, norepinephrine, free fatty acids):

```
chain runs → protons pumped → UCP1 lets them back in → HEAT, no ATP
```

**Purpose:** non-shivering thermogenesis — newborns, hibernating animals, and (to a lesser extent) adults generate warmth by *wasting* the gradient on purpose. **The uncoupler mechanism, recruited as a physiological function** — an excellent demonstration that the gradient, not oxygen use itself, is the regulated quantity.

## Reactive oxygen species as a side-effect

Electrons passed to O₂ sometimes land on it prematurely, producing **superoxide (O₂⁻)** — most often at Complexes I and III. The cell defends with **superoxide dismutase, catalase, glutathione peroxidase** (NADPH-dependent, from chapter 04's carrier table).

**Consequences of leak:** mtDNA sits right beside the chain with limited repair, so oxidative damage accumulates with age — the **free-radical theory of aging**, and a contributor to neurodegeneration. The chain that keeps you alive also damages you slowly; the defence systems are as much a part of the story as the complexes.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "The chain makes ATP directly" | The chain makes a **gradient**; ATP synthase makes ATP. Two steps, one membrane. |
| "Oxygen is used in glycolysis" | Oxygen is used **only at Complex IV** — the very end. |
| "Uncouplers stop respiration" | They **increase** it — electrons flow without ATP being made, so O₂ consumption rises while ATP falls. |
| "NADH and FADH₂ give the same yield" | FADH₂ enters at Complex II, pumping fewer protons → **1.5 vs 2.5 ATP**. |
| "Protons flow into the matrix to make ATP" | Correct — and the direction matters: **outward pumping, inward flow through synthase.** |
| "The gradient is chemical only" | It is chemical (pH) **and electrical** (membrane potential) — together, proton-motive force. |

## Medical relevance

**Cyanide, CO, and H₂S poisoning** = Complex IV blockade. Treatment: **hydroxocobalamin** (binds cyanide), **100% oxygen** (mass-action competition at CO sites), and **thiosulfate** as a cyanide sink. The pathology is cellular suffocation despite normal blood oxygenation.

**Mitochondrial diseases** (02 — Cell Biology) are, mechanistically, defects in this chapter's complexes — hence lactic acidosis (the chain fails, glycolysis runs anaerobically), myopathy, and neurological involvement in energy-hungry tissues.

**Aspirin overdose** acts partly as an uncoupler at high doses — heat production rises, O₂ use climbs, ATP falls; fever and respiratory alkalosis follow. The same molecule that inhibits cyclooxygenase at therapeutic doses becomes a mitochondrial uncoupler at toxic ones — **dose changes mechanism**.

**Uncouplers as drugs under study:** **brown-fat activation** and UCP1 upregulation are researched for obesity (burning fat as heat). The pharmacological principle — *make the gradient leak and the fuel burns* — is already proven by DNP's history as a dangerous weight-loss drug of the 1930s.

**Why do cells die in a heart attack within minutes?** Not from oxygen lack in the blood alone but because **without O₂ at Complex IV the gradient collapses**, ATP fails, pumps stop, and the cell swells and dies — ischemia–reperfusion injury follows when returning flow generates a burst of ROS from partially reduced chain carriers.

## Key facts

- The chain is **Complexes I–IV in the inner mitochondrial membrane**; ATP synthase is **Complex V**.
- **NADH enters at I; FADH₂ enters at II** (succinate dehydrogenase — a Krebs cycle enzyme) — II pumps no protons, so FADH₂ yields less.
- **O₂ is the final electron acceptor at IV**, reduced to H₂O.
- Protons pumped into the **intermembrane space** by I, III, IV → gradient (chemical + electrical) = **proton-motive force**.
- **Chemiosmosis:** gradient stored across an H⁺-impermeable membrane, harvested through ATP synthase.
- **ATP synthase:** F₀ proton channel rotates the γ stalk, cycling β subunits through open/loose/tight conformations; ~4 H⁺ per ATP.
- Yields: **NADH ≈ 2.5 ATP, FADH₂ ≈ 1.5 ATP; ~30–32 ATP per glucose total.**
- **Cyanide/CO block IV** → chain stops, O₂ not consumed. **Oligomycin blocks synthase** → gradient builds, respiration falls. **Uncouplers** → leak → O₂ use rises, ATP falls, heat rises.
- **Respiration is demand-driven:** ADP level controls the rate; the gradient back-inhibits pumping when full.
- **UCP1/thermogenin** deliberately leaks protons in brown fat for heat; ROS leak at the chain damages mtDNA over time.

## Practice questions

**1. The direct source of energy used by ATP synthase to make ATP is**

A. Hydrolysis of glucose
B. The proton gradient across the inner mitochondrial membrane
C. Direct transfer of electrons from NADH
D. Sunlight

**Answer: B**

Explanation: ATP synthase is a turbine: protons flowing down their electrochemical gradient through F₀ rotate the stalk, driving conformational changes in F₁ that produce ATP. Glucose's energy was already spent building that gradient, and electrons never enter the synthase directly — they are used upstream to pump the protons.

---

**2. Cyanide poisoning causes death primarily because**

A. It blocks glycolysis
B. It prevents electrons from reaching oxygen at Complex IV, so the proton gradient and ATP production collapse
C. It destroys the mitochondrial DNA
D. It uncouples the chain, producing excess ATP

**Answer: B**

Explanation: Cyanide binds cytochrome c oxidase, stopping electron flow to oxygen. Without electron flow, no protons are pumped, no gradient forms, and oxidative phosphorylation ceases — brain and heart fail within minutes. Oxygen consumption stops (unlike uncoupling, which raises it), and blood oxygenation remains normal because the block is intracellular.

---

**3. Which statement about FADH₂ compared with NADH is correct?**

A. It yields more ATP because it enters later
B. It yields fewer ATP because it donates electrons at Complex II, bypassing the proton-pumping Complex I
C. It produces ATP directly by substrate-level phosphorylation
D. It is used only in the cytoplasm

**Answer: B**

Explanation: Complex II pumps no protons, so each FADH₂ pair drives fewer H⁺ across the membrane and yields ~1.5 ATP versus ~2.5 for NADH. Entering "downstream" means less of the electrochemical drop is captured — the staircase argument applied to the chain.

---

**4. The term "uncoupler" means an agent that**

A. Stops electron transport completely
B. Allows protons to cross the inner membrane without passing through ATP synthase, dissipating the gradient as heat and separating respiration from phosphorylation
C. Enhances ATP synthase activity
D. Blocks oxygen binding to haemoglobin

**Answer: B**

Explanation: Uncouplers short-circuit the dam — electrons still flow and oxygen is still consumed (often faster than usual), but the proton gradient never builds, so no ATP is made and the energy appears as heat. That is why "uncoupled" specifically describes the separation of electron transport from ATP synthesis, with O₂ consumption rising while ATP output falls.

---

**5. Where are protons accumulated by the electron transport chain?**

A. In the mitochondrial matrix
B. In the intermembrane space
C. In the cytoplasm
D. Inside the ATP synthase

**Answer: B**

Explanation: Complexes I, III, and IV pump H⁺ *out* of the matrix into the intermembrane space, making it acidic and positively charged relative to the matrix. Protons then flow back into the matrix through ATP synthase — the return flow is what powers ATP production.

---

**6. Which complex of the electron transport chain is identical to an enzyme of the citric acid cycle?**

A. Complex I
B. Complex II (succinate dehydrogenase)
C. Complex III
D. Complex IV

**Answer: B**

Explanation: Succinate dehydrogenase catalyses succinate → fumarate in the cycle and is the only cycle enzyme embedded in the inner membrane, functioning there as Complex II — where it passes electrons from FADH₂ to ubiquinone. The two pathways are physically joined at this enzyme.

---

**7. Oligomycin inhibits ATP synthesis. What is the immediate effect on oxygen consumption?**

A. It increases dramatically
B. It decreases, because the gradient builds and back-inhibits proton pumping
C. It is unchanged
D. It stops instantly at zero

**Answer: B**

Explanation: With the return path blocked, protons continue pumping until the gradient becomes too steep to push against, and pumping slows — so oxygen consumption falls in step. This demonstrates that respiration is coupled to phosphorylation: no ADP phosphorylation, little respiration. (Uncouplers produce the opposite pattern.)

---

**8. How many ATP are produced per molecule of FADH₂ oxidised?**

A. 3
B. 1.5
C. 2.5
D. 0

**Answer: B**

Explanation: FADH₂ donates at Complex II, bypassing Complex I's four pumped protons, so the yield is ~1.5 ATP versus ~2.5 for NADH. These fractional modern values reflect ~4 protons per ATP and account for transport costs; the older 2 and 3 figures are rounded and no longer preferred.

---

**9. In brown adipose tissue, thermogenin (UCP1)**

A. Increases ATP yield
B. Allows protons to bypass ATP synthase, generating heat instead of ATP
C. Blocks the electron transport chain
D. Synthesises ATP without a gradient

**Answer: B**

Explanation: UCP1 is a regulated proton leak — electrons flow, oxygen is consumed, protons return through UCP1 rather than ATP synthase, and the energy is released as heat. This is deliberate uncoupling used for non-shivering thermogenesis: the mechanism of DNP recruited as a normal physiological function.

---

**10. Why does oxygen consumption fall when a cell's ATP demand falls?**

A. Oxygen is consumed by other pathways when ATP is plentiful
B. With little ADP, ATP synthase slows, the gradient steepens, and the gradient itself back-inhibits proton pumping — so the chain slows
C. ATP directly blocks oxygen binding at Complex IV
D. Cells stop containing mitochondria

**Answer: B**

Explanation: The system is demand-driven. Low ADP means little proton flow through the synthase, so the gradient builds until pumping against it is energetically prohibitive — respiration slows accordingly. There is no direct oxygen-blocking mechanism by ATP (C); control is exerted entirely through the gradient and the phosphorylation machinery.
