# Enzymes

## Why they matter

Without enzymes, the reactions that make life possible would not run fast enough. Enzymes do not make thermodynamically impossible reactions possible, and they do not supply energy — they **reduce activation energy so reactions can occur at biologically useful rates**. Every metabolic pathway, every digestion step, every DNA replication event depends on them.

Almost every drug works by influencing an enzyme or a receptor. So this chapter is pharmacology's foundation as much as biochemistry's.

## What an enzyme is

An **enzyme** is a biological catalyst — almost always a protein — that accelerates a specific reaction by lowering its activation energy.

| Enzyme | Catalyst? | Consumed? |
| --- | --- | --- |
| Yes | No — returned unchanged | No |
| Reduced to its components by heat or pH | Yes — so that protection costs energy | Yes |

Two consequences follow. First, **enzymes are not used up**, so they can be present in small quantities and used repeatedly. Second, **they do not change which reactions are thermodynamically favourable** — a reaction with a large positive free-energy change cannot be driven forward by an enzyme.

```
DIFFERENT REACTIONS, DIFFERENT BARRIERS

     free energy
          │                     ╱ ← with enzyme
          │                   ╱
          │                 ╱
          │            ___╱
          │      ╱          ← activation energy is SMALLER
          │    ╱    _______← with enzyme
          │  ╱   ╱
          │╱  ╱               ← without enzyme, activation
          └───────────────────    energy is LARGER
              reaction progress
```

The curves have the same starting and ending points. The enzyme lowers the peak and nothing else.

## Terminology

| Term | Meaning |
| --- | --- |
| **Substrate** | The reactant an enzyme acts on |
| **Active site** | The region where the substrate binds — a small part of the enzyme |
| **Enzyme–substrate complex** | The bound state |
| **Product** | What remains after catalysis |
| **Cofactor** | A non-protein ion needed in small amounts: Mg²⁺, Zn²⁺, Fe²⁺, Cu²⁺ |
| **Coenzyme** | An **organic** cofactor: NAD⁺, FAD, CoA |
| **Apoenzyme** | The protein alone, without its cofactor |
| **Holoenzyme** | Apoenzyme + cofactor — the working form |

**Cofactor vs coenzyme.** A **cofactor** is any non-protein requirement; a **coenzyme** is the subset that is organic. So NAD⁺ is a coenzyme, and Mg²⁺ is a cofactor that is *not* a coenzyme. Many students lose the distinction here; write it down.

Some enzymes require a cofactor and are therefore **not** active without it — which is a common clinical theme, since the deficiency of a metal or vitamin produces a characteristic enzyme failure.

## How enzymes work

### The active site is a three-dimensional pocket

The active site is formed by residues brought together from distant parts of the polypeptide chain by folding. So the shape of the site is determined by the **tertiary structure**, which is determined by the primary sequence. This is the clearest example in biology of the chain **sequence → shape → function**.

### Lock-and-key vs induced fit

**Lock-and-key** is the older model: the substrate fits a rigid active site.

**Induced fit** is what actually happens. The active site is flexible, and binding — particularly between the two domains of an enzyme — changes the enzyme's conformation into its active form. So part of the catalytic power comes from the *enzyme* changing shape to accommodate and then to strain the substrate.

```
LOCK AND KEY                        INDUCED FIT

   [active site]                       [active site]
   fixed shape                         open ──┐
        ┌───┐                                ↓ binding
        │ ▓ │ ← substrate fits      [active site]
        └───┘                       changed shape
                                    strains substrate
```

Induced fit explains **cooperativity** — why substrate binding at one site can increase the affinity of other sites. See [03 — Proteins](03-proteins.md#quaternary-structure).

### The catalytic mechanism

Enzymes speed up reactions by lowering activation energy. They do this by:

| Mechanism | What it means |
| --- | --- |
| **Orientation** | Bringing reactants into precise spatial relationship — the most important single effect |
| **Strain/distortion** | Binding in a way that strains a substrate bond, raising its energy |
| **Microenvironment** | Creating local conditions unlike the bulk solution — an appropriately ionised group, a hydrophobic pocket that excludes water |
| **Temporary acid–base catalysis** | Residues donate or accept protons during the reaction |
| **Covalent catalysis** | A temporary covalent bond forms with the substrate |
| **Metal ion catalysis** | A cofactor ion stabilises negative charge — a common role for Mg²⁺ |

The mechanism is the same in every enzyme: **lower the barrier, do not change the equilibrium.** An enzyme cannot make an energetically unfavourable reaction happen; it makes a favourable reaction fast.

## Specificity

Enzymes act on one substrate, or on a family of related substrates. The basis is the **active site** — the shape and chemical properties of a small region that determines which molecules can bind.

Specificity has a practical consequence: **two structurally similar molecules can have very different fates.** The drug **methotrexate** inhibits the human enzyme dihydrofolate reductase far more strongly than it inhibits most bacterial versions of that enzyme — because of small structural differences between the two. Selectivity, not potency, is the goal.

### Chiral molecules and enantiomers

Chirality explains most of the rest:

```
        COOH                    COOH
         |                       |
    H — C — H              H — C — H
         |        MIRROR        |
    NH₂                  NH₂
     L-amino acid        D-amino acid
```

Enzymes are themselves chiral, so they act on only one enantiomer. This is why two enantiomers of one drug can differ substantially in both potency and toxicity. Thalidomide is the cautionary example: giving only one enantiomer does not avoid the harmful effects, because the two forms interconvert in the body.

**Common confusion to retire:** "amino acids come in left- and right-handed forms" is not the same as "amino acids have one form." All amino acids in natural proteins are L-configured, glycine excepted, since with only a hydrogen for a side chain it is achiral. Enantiomers do exist, and D-amino acids occur in some bacterial cell walls — but they are not part of normal protein synthesis.

## Naming

Almost all enzymes end in **-ase**:

| Enzyme | Substrate broken down |
| --- | --- |
| Amylase | Starch (amylon) |
| Lipase | Lipid (lipos) |
| Protease / peptidase | Protein (pepton) |
| Lactase | Lactose |
| Maltase | Maltose |
| Phosphatase | Phosphate |
| Catalase | Hydrogen peroxide |
| Pepsin, trypsin | Proteases that work in the stomach / at pH ~8 |
| Lysozyme | Cleaves bacterial peptidoglycan — not a substrate named convention |

**Common confusion:** a few enzyme names do not end in -ase, because the convention came later than the enzymes themselves — pepsin, trypsin, thrombin, and lysozyme among them. Knowing the -ase pattern is a useful prior, not a rule.

## Factors affecting enzyme activity

Each of these changes the enzyme's **shape** or its **active site's chemical environment.** That is the unifying point.

### Temperature

```
ACTIVITY
    │      ╱‾‾╲
    │     ╱    ╲
    │    ╱      ╲
    │   ╱        ╲
    │  ╱          ╲
    └───────────────→ temperature
     ↑        ↑
   rising   falling: DENATURED
```

- Activity **rises** with temperature — up to a point. The extra kinetic energy increases collisions at the active site.
- Above the optimum, activity **falls sharply** as the tertiary structure collapses.
- Human enzymes have optima near 37 °C. Most are denatured by heat that would take seconds.
- **Low temperature slows the enzyme without destroying it.** Enzymes used in industry are chosen partly for this.

### pH

Each enzyme has an optimum at which its active-site residues are correctly ionised.

| Enzyme | Optimum pH |
| --- | --- |
| Pepsin | ~1.5–2 |
| Trypsin | ~7.5–8 |
| Salivary amylase | ~6.7 |

Deviation changes the charge on ionisable groups — particularly **histidine**, whose side chain sits near physiological pH and is therefore the most sensitive. See [03 — Proteins](03-proteins.md#acidic-and-basic-side-chains-and-ph-dependence).

**Common confusion:** changing pH does not change an enzyme's optimum. It moves the enzyme away from the conditions it works best in. The enzyme is not damaged.

### Substrate concentration

```
RATE
    │              ──────────── Vmax  (all active sites occupied)
    │           __/
    │         _/
    │       _/
    │     _/
    │   _/
    │ _/
    └─────────────────────────→ substrate concentration
```

- Low substrate → rate rises roughly in proportion to concentration
- High substrate → **saturation**: every active site is occupied, so adding more substrate changes nothing
- **Km** is the substrate concentration at half Vmax. **Lower Km means higher apparent affinity.**

### Competitive and non-competitive inhibitors

This is the single highest-yield mechanism in the chapter, because it explains how drug classes work.

**Competitive** — the inhibitor resembles the substrate and binds to the active site.

```
         [active site] ———─ normal
   ┌──────┐                        ┌──────┐
   │      │ +  ▓ ▓ ▓ ▓              │  ▓▓  │  ← blocked
   └──────┘   ↑ competes            └──────┘
              for the site
   ▓▓▓▓ = SUBSTRATE   ▒▒▒▒ = INHIBITOR
```

**Overcoming a competitive inhibitor:** raise substrate concentration, and the substrate outcompetes the inhibitor. **Enzyme Vmax is unchanged; apparent Km increases.**

**Non-competitive (allosteric)** — the inhibitor binds at a **different site** and changes the active site's shape.

```
   [active site] ———─ normal      [active site] ✕  ← distorted
                                          ↑
              ┌────┐                      │
              │    │ —── INHIBITOR binds here
              └────┘        (allosteric site)
```

**Not overcome** by raising substrate concentration, because the inhibitor is not competing for the same site. **Vmax decreases; Km is unchanged.**

| | Competitive | Non-competitive |
| --- | --- | --- |
| Binds at | Active site | Allosteric site |
| Can substrate outcompete? | **Yes** | **No** |
| Effect on Vmax | Unchanged | **Decreased** |
| Effect on Km | Increases (apparent affinity falls) | Unchanged |
| Structural basis | Inhibitor resembles substrate | Changes the enzyme's shape |

**Suffocation poisons are non-competitive.** Carbon monoxide binds haemoglobin's iron, changing the shape of the binding site so oxygen no longer fits. The site is not the oxygen-binding site — so it cannot be outcompeted by more oxygen. See [01 — Proteins](03-proteins.md) and 10 — Cardiovascular.

**Many drugs work this way.** Methotrexate is competitive at dihydrofolate reductase. Statins are competitive inhibitors of HMG-CoA reductase. Both use the competitive model.

## Inhibition and regulation in cells

**Feedback inhibition** — a pathway's final product inhibits an enzyme early in the pathway.

```
START ──▶ E1 ──▶ E2 ──▶ E3 ──▶ END PRODUCT
           ↑
     inhibited by the END PRODUCT
```

Why it works: the cell makes only what it needs. If the end product accumulates, it stops the pathway at its first committed step rather than at the last — which saves the substrates and energy that would otherwise be consumed.

This is **negative feedback at the level of a molecular machine**, and it is the same principle as the control loops in [09 — Homeostasis](../00-foundations/09-homeostasis.md), one level down.

**Allosteric regulation and cooperativity.** Many enzymes have an allosteric site where a regulatory molecule binds, changing the affinity or activity of the active site. Hemoglobin is the standard non-enzyme example: binding of one oxygen increases the affinity of the remaining subunits, producing the sigmoidal curve and efficient loading and unloading.

**Reversible covalent modification** — phosphorylation by a protein kinase, dephosphorylation by a protein phosphatase. Addition and removal of a phosphate group changes the protein's charge, which changes its interactions and its conformation, which changes its activity.

**Proteolytic activation.** Some enzymes are made in an inactive form and switched on by cutting. **Trypsinogen → trypsin** is cleaved by enteropeptidase, then trypsin activates more trypsinogen — an amplification loop, and the reason one duodenal mucosal breach can produce extensive proteolysis in the pancreas.

**Zymogen activation is a safety mechanism.** Pancreatic proteases are made as inactive precursors so they do not digest the pancreas that makes them. Activation inside the gut is triggered by an acid-dependent signal. Acute pancreatitis is the consequence of activation in the wrong place.

## Cofactors, coenzymes, and vitamins

Organic coenzymes are often derived from **vitamins**. The body cannot synthesise them and must obtain them from the diet; the deficiency of a vitamin is therefore a deficiency of a required coenzyme, which is a deficiency of every enzyme that uses it.

| Vitamin | Coenzyme derived from | Enzyme class affected |
| --- | --- | --- |
| **B₁** thiamine | Thiamine pyrophosphate (TPP) | Pyruvate dehydrogenase, α-ketoglutarate dehydrogenase |
| **B₂** riboflavin | FAD, FMN | Oxidation–reduction reactions |
| **B₃** niacin | NAD⁺, NADP⁺ | Dehydrogenases |
| **B₅** pantothenic acid | Coenzyme A | Acyl-group transfer; fatty acid synthesis |
| **B₆** pyridoxine | Pyridoxal phosphate (PLP) | Transamination, decarboxylation |
| **B₇** biotin | Biotin itself | Carboxylation reactions |
| **B₉** folate | Tetrahydrofolate (THF) | One-carbon transfer; nucleotide synthesis |
| **K** | — | γ-carboxylation of clotting factors |
| **A** (retinol) | Retinal | Visual cycle |

**One consequence worth noting:** because these coenzymes are shared across many pathways, a single vitamin deficiency produces **multiple system failures at once**. Thiamine deficiency impairs pyruvate dehydrogenase in the brain, not in muscle alone — which is why the neurological manifestations are prominent. See [03 — Cellular Processes](../03-cellular-processes/).

**Why oxidation–reduction reactions require NAD⁺ and FAD.** NAD⁺ and FAD act as electron carriers: they pick up electrons and hydrogen in one reaction and pass them to another. This is what couples reactions — the anabolism and catabolism pair from [01 — Characteristics of life](../00-foundations/01-characteristics-of-life.md). NAD⁺ accepting electrons gives NADH, which carries them to the electron transport chain. FAD is covalently bound within its enzyme rather than floating free, which is why it is often described as a prosthetic group.

## Regulation summary

| Level | Example |
| --- | --- |
| **Allosteric** | ATP inhibiting its own producing enzymes; cooperativity in haemoglobin |
| **Covalent modification** | Phosphorylation/dephosphorylation of glycogen phosphorylase |
| **Proteolytic activation** | Trypsinogen → trypsin; clotting cascade |
| **Feedback inhibition** | Product inhibiting an early step in the same pathway |
| **Subunit assembly** | cAMP-dependent protein kinase only active when its regulatory and catalytic subunits separate |
| **Compartmentalisation** | Enzymes separated into different organelles, so a substrate and its enzyme meet only where required |
| **Proteolysis** | Damaged or misfolded protein degraded and removed |

## Medical relevance

**Enzyme levels in blood as diagnostic markers.** Because enzymes are normally contained within cells, injury releases them into the circulation — so their concentrations become measurable markers of tissue damage. Serum enzyme concentration rises after cell injury and rises in proportion to the amount of damage.

**Medical consequence:** enzyme measurements are a common diagnostic strategy, and the enzyme's tissue of origin helps localise the injury. See 10 — Cardiovascular.

**Drug classes defined by mechanism.** A large fraction of medicines work by inhibiting enzymes, and the classification follows the mechanism:

| Mechanism | Examples |
| --- | --- |
| **Competitive inhibition** | Statins at HMG-CoA reductase; methotrexate at dihydrofolate reductase |
| **Irreversible inhibition** | Aspirin at cyclooxygenase — acetylates the enzyme, so it cannot be recovered |
| **Non-competitive / allosteric** | Some ion channel modulators |
| **Enzyme induction** | Chronic ethanol induces CYP450 enzymes, accelerating metabolism of other drugs — see 10 — Urinary |
| **Enzyme inhibition** | Cimetidine inhibits hepatic enzymes, slowing the metabolism of co-administered drugs |
| **Enzyme replacement** | Exogenous enzyme given where a metabolic enzyme is deficient |
| **Enzyme inhibition for cancer** | Agents inhibiting enzymes in nucleotide synthesis or signalling, which proliferating tumour cells depend on |

**Why selectivity determines toxicity.** An inhibitor that acts on a target shared by human and microbial cells causes harm. So does one that acts on a human enzyme similar to the microbial target. Most of pharmacology is the search for the difference. And the flip side is off-target toxicity: a drug that binds a human enzyme whose structure resembles the intended target.

**Genetic enzyme disorders.** Individually uncommon but numerous, and instructive because they show what a single missing enzyme produces:

| Deficiency | Accumulating substrate | Consequence |
| --- | --- | --- |
| **Phenylalanine hydroxylase** | Phenylalanine | Phenylketonuria |
| **Hexokinase / G6PD** | Glucose-6-phosphate; oxidant stress | Haemolytic anaemia |
| **Aldehyde dehydrogenase** | Acetaldehyde | Reactions to alcohol |
| **Fumarylacetoacetate hydrolase** | Fumarylacetoacetic acid | Tyrosinaemia |
| **Adenosine deaminase** | Adenosine / deoxyadenosine | Immune dysfunction |

**Diagnosis by enzyme assay.** Measuring enzyme activity in cells or plasma establishes the diagnosis where no other test is definitive — a common reason the enzymology in this chapter is examined.

**Enzymes in the extracellular environment.** The digestive enzymes are secreted into the gut, not retained inside cells. Their activity is controlled by where they are released and by the conditions there — pepsin is inhibited by the bicarbonate-rich mucus that protects the stomach lining.

## Key facts

- Enzymes lower **activation energy**. They do **not** change ΔG or equilibrium, and they are not consumed.
- Active site = the substrate-binding region; specificity comes from its **3D shape and chemistry**.
- **Induced fit**: binding changes the enzyme's shape — which also explains **cooperativity**.
- **Cofactor** = non-protein requirement (Mg²⁺, Zn²⁺); **coenzyme** = the **organic** subset (NAD⁺, FAD, CoA).
- **Temperature and pH** act by **changing the shape** of the enzyme or the ionisation of its active site. They do not change the enzyme's optimum.
- Saturation at high substrate: Vmax when all active sites are occupied; **Km = [S] at ½ Vmax**.
- **Competitive**: binds the active site, can be outcompeted by substrate, **Vmax unchanged, Km increases**. **Non-competitive**: binds elsewhere, distorts the site, **not overcome**, **Vmax falls, Km unchanged**.
- **Feedback inhibition**: the end product of a pathway inhibits an early enzyme.
- **Zymogen activation** is a safety mechanism — proteases made inactive so they do not digest their own tissue.
- Most organic coenzymes come from **vitamins**, so a vitamin deficiency produces multiple enzyme failures at once.

## Practice questions

**1. An enzyme dramatically increases the rate of a reaction. Which statement about it is correct?**

A. It makes an energetically unfavourable reaction favourable
B. It lowers activation energy and does not change the equilibrium position or the reaction's free-energy change
C. It increases the concentration of the substrate
D. It is consumed and must be replaced after each reaction

**Answer: B**

Explanation: The catalyst lowers the barrier, so both forward and reverse reactions speed up equally and the equilibrium position is unchanged. Enzymes cannot make an unfavourable reaction favourable — that would violate thermodynamics. They are returned unchanged after each cycle, and they act on substrate concentration rather than altering it.

---

**2. A competitive inhibitor reduces the reaction rate. What is the most accurate way to overcome the inhibition?**

A. Increase the enzyme concentration indefinitely
B. Raise the substrate concentration so the substrate outcompetes the inhibitor for the active site
C. Decrease the pH
D. Raise the temperature

**Answer: B**

Explanation: A competitive inhibitor resembles the substrate and occupies the active site, so raising substrate concentration allows the substrate to occupy a greater fraction of the available sites. This is the distinguishing feature of competitive inhibition — that Vmax is unchanged and apparent Km increases. Temperature and pH changes act on the enzyme itself and are not a way to relieve competition.

---

**3. A non-competitive inhibitor reduces enzyme activity. Which change would restore activity?**

A. Increasing substrate concentration
B. Increasing the inhibitor concentration
C. Removing the inhibitor, since substrate cannot compete for an allosteric site
D. Decreasing the temperature

**Answer: C**

Explanation: A non-competitive inhibitor binds at a site other than the active site and distorts the enzyme's conformation, so more substrate cannot dislodge it. That is exactly what distinguishes it from competitive inhibition, and it is why non-competitive inhibition lowers Vmax. B would worsen the inhibition.

---

**4. Which statement about zymogen activation is correct?**

A. It converts an inactive enzyme precursor into its active form by cleavage
B. It requires an increase in pH
C. It is how enzymes are first synthesised from amino acids
D. It denatures the enzyme so it can refold into a new shape

**Answer: A**

Explanation: Zymogens are inactive precursors made by proteolytic cleavage — trypsinogen to trypsin is the standard example. The function is safety: pancreatic proteases are made inactive so they do not digest the pancreas that produces them, and they are switched on only in the gut. C describes translation, which builds the precursor from amino acids rather than activating it.

---

**5. A patient has a deficiency of an essential vitamin. Why does the deficiency affect many different enzyme reactions?**

A. Vitamins increase the substrate concentration
B. Vitamins function as structural components of membranes
C. Vitamins are part of the enzyme's amino acid sequence
D. Vitamins are converted into coenzymes that many different enzymes require

**Answer: D**

Explanation: Many organic coenzymes are derived from vitamins — NAD⁺ from niacin, TPP from thiamine, CoA from pantothenic acid, PLP from pyridoxine. Since these coenzymes are shared across many pathways, a single deficiency disables many enzymes at once, producing multi-system failure. A is false because a vitamin does not change the substrate concentration. C is false because the vitamin is a separate coenzyme molecule, not part of the enzyme's amino acid sequence. B misstates the mechanism.

---

**6. Why does an enzyme denature at high temperature but remain functional at low temperature?**

A. Cold denatures proteins and heat preserves them
B. Heat disrupts the weak noncovalent interactions maintaining shape, whereas cold reduces molecular motion without destroying them
C. Enzymes function only between 0 °C and 40 °C
D. Cold breaks peptide bonds while heat only changes shape

**Answer: B**

Explanation: Heat supplies enough energy to overcome hydrogen bonds, electrostatic interactions, and dispersion forces that maintain tertiary structure, so the enzyme unfolds. Cold simply slows molecular motion, reducing collision frequency without destroying structure — which is why refrigerated enzymes retain activity and can be reactivated by warming. Cold does not break covalent bonds, and heat does not either: both statements in A are wrong.

---

**7. A drug inhibits dihydrofolate reductase more strongly in human cells than in bacterial cells. This selectivity arises because**

A. Human cells have more reductase enzyme than bacterial cells
B. Bacteria do not need folate
C. The enzyme's structure differs between the two organisms, so the inhibitor binds one form better
D. Human cells use more folate

**Answer: C**

Explanation: Drug selectivity comes from structural difference at the target. If the human and bacterial enzymes differ in shape and charge around the active site, a molecule designed to fit one will bind the other less strongly. That is why structure-based drug development begins with determining the target's structure. A, B, and D are incorrect.

---

**8. In a metabolic pathway, the final product inhibits the first enzyme. What is the functional advantage of inhibiting an early step rather than a late one?**

A. It increases the concentration of the end product
B. It prevents the cell from making a large amount of product
C. It prevents other pathways from functioning
D. It saves the intermediates and energy that would be consumed producing them

**Answer: D**

Explanation: Blocking the first committed step conserves the upstream substrates and the energy already invested in them. Blocking only the last step would still require the cell to run the whole pathway and then discard the product. Either way the cell stops producing excess — but early inhibition wastes less.

---

**9. Two enantiomers of the same drug reach the same tissue. Only one is pharmacologically active. Why?**

A. Enzymes are chiral and bind only the enantiomer whose stereochemistry complements the active site
B. One enantiomer is always broken down by the liver before it acts
C. Enantiomers have different molecular formulas
D. Only one enantiomer can cross a cell membrane

**Answer: A**

Explanation: Enzymes have chiral active sites, so they bind and transform only the enantiomer that fits. Because enzymes throughout the body act stereoselectively, one enantiomer may act while the other is inert, or may act differently — which is why enantiomers can differ substantially in both potency and toxicity. C is false; enantiomers have identical molecular formulas and differ only in the spatial arrangement of atoms. D is false because both enantiomers share the same formula and similar physicochemical properties, so neither is excluded from crossing a membrane on that basis.

---

**10. Why are trypsinogen and other pancreatic proteases secreted in an inactive form?**

A. Because active proteases would digest the pancreas that produces them
B. Because they must be converted into carbohydrates before use
C. Because inactive enzymes are easier to transport in the blood
D. Because the pancreas cannot produce active enzymes

**Answer: A**

Explanation: Proteolytic enzymes are highly destructive to the proteins of the cell that makes them. Making them as inactive zymogens confines activation to the duodenum, where the triggering conditions occur. If activation happens in the pancreas instead — the mechanism of acute pancreatitis — the organ digests itself. That is why zymogen activation is a safety mechanism rather than a processing convenience.