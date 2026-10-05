# Archaea

## Why it matters

Archaea are the third domain of life, and for a long time they were invisible — not because they are rare, but because they were misidentified. Every methanogen in a rumen, every halophile in a salt lake, and every thermophile in a hot spring was filed under "bacteria" until Carl Woese compared ribosomal RNA sequences in the late 1970s and found that these organisms diverge from bacteria as deeply as bacteria diverge from us. That single result redrew the tree of life and is the reason [00 — Foundations](../00-foundations/08-taxonomy-and-classification.md) treats the three-domain system rather than the older two-kingdom classification.

For pre-medicine, archaea matter for three specific reasons. First, they are the **control case for antibiotic selectivity**: an organism with 70S ribosomes, a circular chromosome, and a prokaryotic cell plan that is nonetheless unaffected by penicillin tells you exactly what the drug is aimed at. Second, they are the **probable ancestors of our own cells** — the eukaryotic nucleus and cytoplasm appear to descend from an archaeal lineage, and that argument is the foundation of the endosymbiotic account of mitochondria. Third, they are the **standard exam answer to "which domain has no known human pathogens"**, a point that comes up repeatedly precisely because it is counter-intuitive.

Finally, archaea are where **extremophile biochemistry** becomes practical. The enzymes that work at 100 °C come from archaea, and those enzymes are the tools that made molecular biology possible.

## Domain membership and the three-domain tree

| Domain | Cell plan | Membrane linkage | Information machinery | Example |
| --- | --- | --- | --- | --- |
| **Bacteria** | Prokaryotic | Ester-linked fatty acids | 70S ribosomes, RNA polymerase with 4–5 core subunits, sigma factor initiation | *E. coli*, *Streptococcus* |
| **Archaea** | Prokaryotic | **Ether-linked branched isoprenoids** | 70S ribosomes, **complex RNA polymerase, TATA-binding protein** | *Halobacterium*, *Methanobrevibacter*, *Sulfolobus* |
| **Eukarya** | Eukaryotic | Ester-linked fatty acids | 80S ribosomes, three RNA polymerases | Plants, animals, fungi, protists |

The split rests on **16S ribosomal RNA sequence comparison** (18S in eukaryotes). Woese's trees showed archaea grouping with bacteria on structural features but with eukarya on informational genes — the pattern that made the three-domain scheme necessary. The details of the classification system are in [00 — Foundations](../00-foundations/08-taxonomy-and-classification.md).

**The shape of the modern tree has changed again**, and this is now the examinable point:

```
1977  THREE-DOMAIN (Woese)          2010s–now  TWO-DOMAIN (Asgard)

      Bacteria                            Bacteria
          │                                   │
      Archaea                           Archaea ─┬─ Euryarchaeota
          │                                   │    (methanogens, halophiles)
      Eukarya                                 ├─ Crenarchaeota (thermophiles)
                                               └─ ASGARD clade
                                                    ├─ Lokiarchaeota
                                                    ├─ Thorarchaeota
                                                    ├─ Odinarchaeota
                                                    └─ Heimdallarchaeota
                                                          │
                                                     EUKARYA emerges
                                                     from within archaea
```

Under the two-domain model, **Eukarya is not a sister group to Archaea — it is nested inside them.** The three-domain tree is still what most textbooks draw as a first approximation, but the Asgard result is what current research assumes.

## Membranes: the feature that defines the domain

This is the deepest chemical difference between archaea and bacteria, and it is the reason extremophiles can exist.

| Feature | Bacterial / eukaryotic membrane | Archaeal membrane |
| --- | --- | --- |
| **Lipid linkage** | **Ester** bond between fatty acid and glycerol | **Ether** bond between isoprenoid alcohol and glycerol |
| **Hydrophobic tail** | Unbranched fatty acids | **Branched isoprenoid (phytanyl) chains** |
| **Backbone stereochemistry** | sn-glycerol-3-phosphate | sn-glycerol-1-phosphate (opposite chirality) |
| **Architecture** | Bilayer | Bilayer in many; **monolayer of tetraether lipids** in many thermophiles |
| **Stability** | Susceptible to hydrolysis and heat | **Resists hydrolysis, heat, and acid** |

```
BACTERIUM                          ARCHAEON

  polar head                        polar head
   │                                 │
   ester ─┐                          ether ─┐
          │                                 │
   ═══════╡  fatty acid              ═══════╡  isoprenoid, branched
   ═══════╡  (unbranched)            ──┐  ──┤  ──┐
          │                           └─┘  │   └─┐  methyl branches
   ester ─┘                          ether ─┘     └─ ether
   │                                 │
  polar head                        polar head

   ~2 nm apart if bilayer             can be a SINGLE continuous
                                      chain spanning the membrane
```

Why each feature helps:

1. **Ether bonds hydrolyse far more slowly than ester bonds**, especially at high temperature and extreme pH. A bacterial membrane boiled for an hour is hydrolysed; an archaeal membrane is not.
2. **Branched isoprenoid tails pack differently**: the methyl branches lower the melting point and prevent tight, crystalline packing that would crack a membrane when cooled, while the longer chains resist permeability when heated.
3. **Tetraether monolayers** in thermophiles such as *Sulfolobus* replace two separate sheets with one continuous sheet — there is no leaflet interface to pull apart at 85 °C, and proton permeability drops dramatically. This is why an acidophile can hold its cytoplasm near neutral while bathed in pH 2.

The ether/ester distinction was introduced in [00 — Foundations](../00-foundations/07-cells-prokaryotes-and-eukaryotes.md); everything below follows from it.

## Cell walls: why penicillin does nothing

**Archaea have no peptidoglycan.** There is no NAM, no NAG–NAM backbone, no muramic acid, no D-amino acid stem peptide, and no transpeptidase to inhibit.

| Wall type | Composition | Organism |
| --- | --- | --- |
| **Pseudopeptidoglycan (pseudomurein)** | N-acetyltalosaminuronic acid linked **β-1,3** (not β-1,4), L-amino acids only | *Methanobacterium*, *Methanopyrus* |
| **S-layer** | Crystalline array of protein or glycoprotein, non-covalently attached to the membrane | *Sulfolobus*, *Halobacterium*, many others |
| **Polysaccharide / glycoprotein wall** | Heteropolysaccharide, sometimes with sulfate | *Methanosarcina* |
| **Protein wall** | S-layer proteins only | Some methanogens, some halophiles |
| **None** | Naked cells (membrane alone) | Some *Thermoplasma* (which compensates with a coat of lipoglycoprotein) |

Two consequences are examined constantly:

- **Lysozyme does not work.** It hydrolyses β-1,4 bonds between NAG and NAM; pseudopeptidoglycan has neither sugar nor the bond.
- **Penicillin does not work.** There is no transpeptidase, no D-Ala–D-Ala, and no PBP to acylate — the drug has no target. **Resistance here is intrinsic and absolute, not acquired.** The same is true of vancomycin: without a stem peptide there is nothing for it to bind.

An archaeon growing on a penicillin disc shows no zone of inhibition — a striking result that makes the mechanism of β-lactams visible by its absence. The logic of target-based selectivity is covered in [01 — Enzymes](../01-biochemistry/05-enzymes.md).

## Extremophiles: adaptation, not tolerance

"Extreme" is relative to human physiology. Many archaea are **mesophiles** living in soil, ocean, and animal intestines at ordinary temperatures; the extremophiles are the ones that make the headlines.

| Group | Environment | Examples | Key adaptation |
| --- | --- | --- | --- |
| **Thermophiles / hyperthermophiles** | 60–121 °C (black smokers, hot springs) | *Sulfolobus* (80 °C, pH 2–3), *Pyrococcus furiosus* (100 °C), *Methanopyrus kandleri* (122 °C record) | Ether/tetraether lipids; proteins with more salt bridges and hydrophobic core packing; **reverse gyrase** (introduces positive supercoils — found only in hyperthermophiles); robust chaperones |
| **Halophiles** | Saturated NaCl (Great Salt Lake, solar salterns; 1.5–5 M) | *Halobacterium*, *Haloferax*, *Halococcus* | **Compatible solutes** — accumulate K⁺ and glutamate (or organic solutes) to match external osmolarity instead of losing water; **bacteriorhodopsin** uses light to pump protons for ATP when oxygen is scarce |
| **Acidophiles** | pH 0–3 | *Sulfolobus*, *Ferroplasma*, *Acidiplasma* | Impermeable tetraether membrane; active **H⁺ extrusion**; S-layer that excludes protons; cytoplasm held near neutral |
| **Alkaliphiles** | pH 9–12 | *Natronomonas*, some *Halobacterium* | Na⁺/H⁺ antiport; cell wall resisting hydrolysis |
| **Methanogens** | Strict anaerobes — rumen, wetlands, sediments, deep subsurface, cow pats | *Methanobrevibacter*, *Methanosarcina*, *Methanococcus* | Unique coenzyme biochemistry (below); oxygen-sensitive enzymes |
| **Anaerobic heterotrophs** | Deep-sea vents, subsurface | *Archaeoglobus* | Sulfate reduction with archaeal lipids |

**The general principles, which is what questions test:**

```
HIGH TEMPERATURE       ether + branched/monolayer lipids (no hydrolysis)
                       reverse gyrase; salt bridges; tight folding
                       → membrane stays sealed, protein stays folded

HIGH SALT              compatible solutes or K⁺/glutamate accumulate
                       inside → no osmotic water loss
                       enzymes evolved with acidic surface residues
                       that remain soluble at high ionic strength

LOW pH                 membrane impermeable to H⁺ (tetraether)
                       active proton extrusion → cytoplasm near pH 7
```

**Compatible solutes** deserve a note of their own because the concept recurs: when the outside world is hypertonic, a cell must raise its internal solute concentration without letting that solute damage its own enzymes. It does so by accumulating small molecules — KCl, potassium glutamate, glycerol, trehalose, ectoine — that are *compatible* with protein function, meaning they are excluded from the protein's hydration shell and so do not disturb folding. The alternative, letting salts into the cytoplasm, denatures enzymes; the strategy of collecting compatible solutes instead is used by bacteria, plants, and animals facing salt or drought stress as well.

## Methanogenesis: a reaction no other life performs

Methanogens are the only organisms on Earth that make methane as a terminal metabolic step, and the reaction is strictly archaeal.

```
Strictly anaerobic:

   CO₂ + 4 H₂  ──methanogenesis──▶  CH₄ + 2 H₂O        ΔG°′ ≈ −131 kJ
   (hydrogenotrophic — the dominant route)

   also:
   4 CH₃OH  ──▶  3 CH₄ + CO₂          (methylotrophic)
   CH₃COO⁻ + H₂O  ──▶  CH₄ + HCO₃⁻   (acetoclastic — important in sediments)
```

| Feature | Detail |
| --- | --- |
| **Oxygen** | Strictly absent — the pathway's enzymes (methyl-coenzyme M reductase, hydrogenases, ferredoxin oxidoreductases) are irreversibly oxygen-sensitive |
| **Unique cofactors** | Coenzyme M, coenzyme B, coenzyme F₄₂₀, methanofuran, tetrahydromethanopterin — molecules found nowhere else in biology |
| **Energy conservation** | A membrane-bound electron transport chain using ferredoxin and Na⁺/H⁺ gradients; **chemiosmotic ATP synthesis**, like all cells |
| **Electron acceptor** | CO₂ (or methyl compounds) — not O₂, not nitrate, not sulfate |

**Three places this matters:**

1. **The rumen.** *Methanobrevibacter ruminantium* and relatives consume H₂ produced by fermentative bacteria and protozoa, keeping the partial pressure of H₂ low enough that the upstream fermentations remain thermodynamically favourable. Without the methanogens, hydrogen would accumulate and fibre digestion would stall. The archaea are not digesting the grass; they are performing a service that keeps the rest of the consortium working — a fact of agricultural importance, since roughly a fifth of ruminant methane is exhaled or eructated.
2. **The atmosphere.** Methane is a greenhouse gas with roughly 80 times the warming potential of CO₂ over 20 years. Enteric fermentation from livestock, flooded rice paddies, landfills, wetlands, and ruminant-associated archaea together make methane cycling a genuine climate variable. Anaerobic digestion in sewage treatment deliberately harvests this methane as biogas.
3. **Human biology.** Methanogens are present in the human colon — *Methanobrevibacter smithii* is the best characterised — where they improve fermentation efficiency by consuming H₂. Their abundance correlates with constipation-predominant patterns in some studies, but the relationship is associative.

## Information processing: archaeal machinery looks eukaryotic

Archaea have a prokaryotic **cell plan** but eukaryote-like **information systems**. This is the chapter's central pattern, and it is what makes archaea the bridge to ourselves.

| Feature | Bacteria | Archaea | Eukarya |
| --- | --- | --- | --- |
| **Ribosomes** | 70S | **70S** | 80S (cytosolic) |
| **RNA polymerase** | Single, 4–5 core subunits | **Single (or three in Crenarchaeota), 11–13 subunits, homologous to RNA polymerase II** | Three (RNA Pol I, II, III) |
| **Promoter recognition** | Sigma factor | **TATA-binding protein (TBP) + transcription factor B (TFB)** — homologues of TBP and TFIIB | TBP + TFIIB and a full set of factors |
| **Transcription–translation coupling** | Coupled (no nucleus) | Coupled (no nucleus) | **Separated** by the nuclear envelope |
| **Introns** | Rare | **Common in tRNA and rRNA; some mRNA introns; many self-splicing** | Very common in mRNA |
| **Initiation factor for initiator tRNA** | IF2 | **aIF2** (eIF2 homologue) | eIF2 |
| **Elongation factors** | EF-Tu, EF-G | **EF-1α and EF-2** (eukaryotic type) | EF-1α, EF-2 |
| **DNA packaging** | Histone-like proteins (HU, IHF) in many | **True histones (H3/H4-like tetramers) in several lineages**; Alba in others | Histone octamer, nucleosomes |
| **DNA repair** | Some systems | **Extensive, eukaryote-like** — Mre11–Rad50, nucleotide excision, recombination repair | As archaea |

**Two consequences worth internalising:**

- **Sedimentation coefficient is size, not drug sensitivity.** Archaeal ribosomes are 70S and yet many archaea are naturally resistant to antibiotics that inhibit bacterial ribosomes — chloramphenicol and aminoglycoside resistance is common among methanogens, and chloramphenicol acetyltransferases are found on archaeal plasmids. The antibiotic test that would work on a bacterium fails here for the same reason penicillin fails: **the target's structure differs even when its size does not.**
- **The transcription story is the strongest evidence of kinship.** Sigma factors are a bacterial invention for promoter recognition; archaea replaced them with a TATA-binding protein that binds a TATA box upstream of the gene and recruits the polymerase — a mechanism recognisably ancestral to the eukaryotic system described in [05 — Molecular Biology](../05-molecular-biology/). Sequence and structural comparisons of RNA polymerase subunits give the same answer.

Because archaea couple transcription and translation (no nucleus) yet use eukaryote-like enzymes, they are the intermediate state the eukaryotic cell must have passed through. You cannot understand eukaryotic gene expression as simply "bacterial plus a nucleus."

## Asgard archaea and the origin of eukaryotic cells

In 2015, sediment from a hydrothermal field near Loki's Castle in the Arctic yielded a metagenome — **Lokiarchaeota** — encoding proteins thought to be exclusive to eukaryotes: ESCRT-III membrane-remodelling machinery, small GTPases of the Ras superfamily, ubiquitin-related modifiers, and actin homologues. Four more phyla followed (Thor, Odin, Heimdall, Gerd), and the group was named the **Asgard superphylum**.

```
ASGARD ARCHAEA  =  archaeal cell
                   + eukaryotic-type information and membrane machinery
                   + cytoskeletal and trafficking gene toolkit
                        │
                        │  + endosymbiotic α-proteobacterium
                        ▼
                THE FIRST EUKARYOTIC CELL
                        │
                        ▼
              mitochondrion acquired → larger cell, aerobic respiration
```

Heimdallarchaeota currently sits closest to eukaryotes in most analyses. The implications:

1. **The eukaryotic cell is archaeal in its informational core** (transcription, translation, DNA replication, repair, histones) and bacterial in its energetic machinery.
2. **Mitochondria came later, from an α-proteobacterium.** Their 70S ribosomes, circular genomes, and division by binary fission are the signature — developed in [02 — Cell Biology](../02-cell-biology/04-energy-and-containment-organelles.md).
3. The full argument for how an archaeal host and a bacterial symbiont produced the eukaryotic cell, and the sequence of events after that, belongs to [06 — Evolution](../06-evolution/).

**The evidence pattern is worth noting methodically:** phylogenomic placement of the host lineage, an α-proteobacterial origin for the mitochondrial proteome, the shared membrane chemistry of mitochondria with bacteria, and the distribution of eukaryotic signature proteins across Asgard genomes. No single line is decisive; together they make the two-domain tree the default assumption.

## Why archaea are medically almost irrelevant

**No archaeon is currently a recognised cause of human disease.** Koch's postulates have not been fulfilled for any archaeal species, no archaeal toxin has been characterised, and no antibiotic in clinical use targets archaeal-specific biology. That is the examinable fact.

The honest follow-up — which distinguishes a strong answer from a memorised one — is *why*:

| Candidate explanation | Reasoning | Status |
| --- | --- | --- |
| **No peptidoglycan, no LPS, no typical virulence machinery** | The structural triggers that drive acute bacterial pathology (endotoxin, exotoxins, capsules, secretion systems) have no archaeal equivalent described | Plausible; absence of evidence partly reflects limited study |
| **Niche occupancy** | Human-associated archaea are few in number and restricted largely to the colonic lumen, competing in an environment already saturated by bacteria | Supported by microbiome surveys |
| **Biochemistry mismatch** | Most human-associated archaea are strict anaerobes or methanogens whose optimal conditions do not correspond to sites of acute infection | Suggestive |
| **Detection bias** | Standard culture and 16S protocols historically failed to recover archaea, so disease could have been missed | Partly true, but modern metagenomics has not revealed hidden pathogens |

**Associations without causation are worth knowing, because questions sometimes use them.** *Methanobrevibacter smithii* is enriched in the colon in some constipation-predominant irritable bowel syndrome cohorts and in periodontal plaque alongside *Methanobrevibacter oralis*; halophilic archaea have been cultured rarely from clinical specimens such as wounds and urinary samples; both are found in some biofilms. None of these meets Koch's postulates, and none is taught as an established infection.

**Where archaea do show up medically is as tools and as analogues:**

- ***Pyrococcus furiosus* DNA polymerase (Pfu)** and polymerases from other hyperthermophiles made **PCR** possible — heat-stable enzyme, no re-addition each cycle.
- **Bacteriorhodopsin and rhodopsins** from halophiles are research tools in optogenetics.
- **Archaeal lipids and S-layers** are studied as drug-delivery and vaccine-particle scaffolds.
- The **selective-toxicity lesson** runs in the other direction: because archaea have no peptidoglycan and a different transcription machinery, they demonstrate that an antibiotic's effect depends entirely on having a target. Remove the target and the drug is inert. That is the same principle that governs why viruses are unaffected by antibiotics — see [03 — Viruses](03-viruses.md).

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Archaea are just extremophile bacteria" | Most archaea are **not** extremophiles, and most extremophiles that matter clinically are not archaea. Archaea occupy ordinary soils, oceans, and guts as well. |
| "Prokaryote means bacterium" | Prokaryote is a **cell plan**, not a taxon. Both Bacteria and Archaea are prokaryotic — no nucleus in either. |
| "Archaea are resistant to antibiotics because they have thick walls" | They are resistant because the **target is absent or different** — no peptidoglycan for penicillin, different ribosome for aminoglycosides. Resistance is structural, not a barrier effect. |
| "Archaea make ATP differently" | No. They use **chemiosmotic ATP synthesis across a membrane** exactly as bacteria and mitochondria do; what differs is the electron source (H₂ oxidation, methanogenesis), not the ATP-generating mechanism. |
| "The three-domain tree is settled science" | It was the standard model from 1977; the Asgard result supports **Eukarya nested within Archaea** — the two-domain tree. Both appear in print; know which is which. |
| "Methanogens are bacteria producing methane" | Methanogenesis is **exclusively archaeal**. No bacterium and no eukaryote performs it. |
| "Ether linkages are stronger bonds" | The bond is not dramatically stronger in energy terms; it **hydrolyses more slowly**, and the branched tails plus tetraether architecture reduce permeability and heat damage. |
| "No archaeal pathogens means archaea cannot interact with humans" | They colonise the gut, mouth, and skin as **commensals**; association is not causation, and Koch's postulates are unmet. |

## Key facts

- Three domains — **Bacteria, Archaea, Eukarya** — defined by rRNA sequence; the modern two-domain tree places **Eukarya inside Archaea** via the **Asgard superphylum**.
- Archaeal membranes: **ether-linked, branched isoprenoid lipids** on a *sn*-glycerol-1-phosphate backbone; many thermophiles use a **tetraether monolayer**.
- **No peptidoglycan**: walls are pseudopeptidoglycan (β-1,3 bonds), S-layers, protein, polysaccharide, or absent — hence **intrinsic resistance to penicillin, vancomycin, and lysozyme**.
- Extremophile adaptations: **ether/monolayer membranes** (heat), **compatible solutes and K⁺ accumulation** (salt), **impermeable membrane and proton extrusion** (acid), **reverse gyrase** (hyperthermophiles).
- **Methanogenesis**: CO₂ + 4 H₂ → CH₄ + 2 H₂O; unique coenzymes (coenzyme M, F₄₂₀); strict anaerobes; central to **rumen fermentation efficiency** and to atmospheric methane.
- Archaeal information machinery is **eukaryote-like**: complex RNA polymerase, **TATA-binding protein and TFB**, introns, histones in several lineages, EF-1α/EF-2, aIF2.
- Ribosomes are **70S** but antibiotic sensitivity differs from bacteria — **sedimentation coefficient is size, not drug binding**.
- **Asgard archaea** encode ESCRT-III, small GTPases, and actin homologues; Heimdallarchaeota is currently sister to Eukarya.
- Eukaryogenesis = **archaeal host + α-proteobacterial endosymbiont** → mitochondrion; see [02 — Cell Biology](../02-cell-biology/04-energy-and-containment-organelles.md) and [06 — Evolution](../06-evolution/).
- **No archaeon is a recognised human pathogen** — Koch's postulates unmet; associations with bowel, oral, and biofilm communities are not infections.
- Practical value: heat-stable **Pfu polymerase** for PCR; bacteriorhodopsin in optogenetics.

## Practice questions

**1. Penicillin has no effect on an archaeon because**

A. Archaea pump the drug out with efflux pumps
B. Archaea lack peptidoglycan and the transpeptidase target that penicillin acylates
C. Archaea have a thicker wall than bacteria
D. Penicillin is degraded by archaeal β-lactamases

**Answer: B**

Explanation: Penicillin works by mimicking D-Ala–D-Ala and irreversibly inhibiting the transpeptidase (PBP) that cross-links peptidoglycan. Archaeal walls contain pseudopeptidoglycan, S-layers, protein, or nothing at all — there is no peptidoglycan to weaken and no transpeptidase to inhibit, so the drug has no target. This is intrinsic, absolute resistance, not acquired resistance mediated by efflux (A) or β-lactamase (D), and thickness (C) is irrelevant when the substrate itself is absent.

---

**2. Which chemical feature most directly explains the heat resistance of archaeal membranes?**

A. Ester-linked unbranched fatty acids forming a stable bilayer
B. Ether-linked branched isoprenoid chains, often arranged as a tetraether monolayer
C. Peptidoglycan cross-links between lipids
D. Cholesterol inserted between phospholipids

**Answer: B**

Explanation: Ether bonds hydrolyse far more slowly than ester bonds, branched isoprenoid tails resist tight crystalline packing and reduce permeability at high temperature, and in hyperthermophiles two leaflets are fused into a single tetraether monolayer so there is no interface to pull apart. Together these let a membrane function at 80–120 °C where a bacterial membrane would hydrolyse and leak. A describes bacterial and eukaryotic membranes; C is not a real feature of any membrane; D is a eukaryotic (and some bacterial) membrane fluidity modulator, not the defining archaeal adaptation.

---

**3. The accumulation of KCl and organic solutes in a halophilic archaeon serves to**

A. Denature proteins at high ionic strength
B. Raise internal solute concentration to match the environment without disrupting enzyme function
C. Replace the need for a plasma membrane
D. Generate ATP by chemiosmosis

**Answer: B**

Explanation: In a hypersaline environment water would leave the cell by osmosis. The cell matches external osmolarity by accumulating **compatible solutes** — K⁺ with glutamate, or organics such as glycerol and ectoine — that are compatible with protein folding rather than disruptive salts inside the cytoplasm. This is a general strategy also used by salt-stressed bacteria, plants, and animals. A is the opposite of the goal, C is impossible, and D confuses osmotic balance with the membrane-based ATP synthesis that archaea, like all cells, perform using a proton or sodium gradient.

---

**4. Which statement correctly compares archaeal and bacterial transcription?**

A. Archaea use a sigma factor to recognise promoters, as bacteria do
B. Archaea use a single small RNA polymerase with four core subunits
C. Archaea use a TATA-binding protein and a complex RNA polymerase homologous to eukaryotic RNA polymerase II
D. Archaea translate proteins in the nucleus before export

**Answer: C**

Explanation: Archaeal promoters contain a TATA box bound by **TBP**, with transcription factor B recruiting a large, multi-subunit RNA polymerase — machinery homologous to the eukaryotic system. Bacteria instead use a small polymerase plus a **sigma factor** (A). B describes the bacterial enzyme, not the archaeal one. D is impossible: archaea have no nucleus, and transcription and translation are coupled in the cytoplasm.

---

**5. Methanogenesis differs from other forms of anaerobic respiration in that it**

A. Uses oxygen as the terminal electron acceptor at low partial pressure
B. Produces methane from CO₂ or methyl compounds using coenzymes unique to archaea
C. Occurs in bacteria but not archaea
D. Requires an external organic carbon source

**Answer: B**

Explanation: Methanogens reduce CO₂ (or methyl compounds, or acetate) to CH₄ using unique cofactors including coenzyme M, coenzyme B, F₄₂₀, and methanofuran, with methyl-coenzyme M reductase as the terminal enzyme. It is strictly anaerobic (A), exclusively archaeal (C), and the hydrogenotrophic route is autotrophic for carbon — CO₂ is the carbon source, not an organic one (D). The reaction sustains rumen fermentation by removing H₂, and the resulting methane is a significant atmospheric greenhouse gas.

---

**6. The discovery of Lokiarchaeota was important because it**

A. Showed archaea cause periodontal disease
B. Demonstrated that eukaryotic signature proteins are encoded by an archaeal lineage, supporting Eukarya nested within Archaea
C. Proved the three-domain tree correct
D. Revealed archaea have peptidoglycan

**Answer: B**

Explanation: Lokiarchaeota and related Asgard genomes carry genes previously considered eukaryote-specific — ESCRT-III, small GTPases, ubiquitin-like modifiers, actin homologues — placing a gene toolkit for membrane remodelling and cytoskeletal dynamics inside Archaea. This supports the two-domain tree in which Eukarya emerges from within the archaeal radiation, particularly from the Heimdallarchaeota branch. A is unsupported (no archaeal pathogen meets Koch's postulates), C is the opposite of the finding, and D contradicts the defining absence of peptidoglycan.

---

**7. Which pair is correct?**

A. Lysozyme is effective against archaea because they have carbohydrate walls
B. Pseudopeptidoglycan contains β-1,3 bonds, so lysozyme, which cleaves β-1,4 bonds, does not act on it
C. Archaea are susceptible to vancomycin because they have D-Ala–D-Ala
D. Archaeal walls contain muramic acid

**Answer: B**

Explanation: Pseudomurein is built from N-acetytalosaminuronic acid with β-1,3 linkages and only L-amino acids; lysozyme's substrate specificity is for the β-1,4 NAG–NAM bond, so it cannot cleave it. There is no muramic acid and no D-Ala–D-Ala stem peptide, so vancomycin has nothing to bind (C, D), and resistance to lysozyme follows from bond specificity rather than wall presence alone (A).

---

**8. Methanogens are of agricultural significance mainly because they**

A. Fix nitrogen for legumes
B. Digest cellulose directly in the rumen
C. Consume hydrogen produced by fermentation, keeping that fermentation thermodynamically favourable, and release methane
D. Kill rumen bacteria, releasing nutrients

**Answer: C**

Explanation: Ruminant fibre digestion is a community effort; fermentative bacteria and protozoa release H₂, and if H₂ accumulated the upstream reactions would become unfavourable. Methanogens scavenge H₂, converting it with CO₂ to CH₄, which keeps the fermentation running — and the methane is eructated, contributing substantially to agricultural greenhouse gas emissions. They do not fix nitrogen (A), do not attack cellulose themselves (B), and do not kill their partners (D).

---

**9. A microbiology student claims archaea must be resistant to all antibiotics. What is the correct response?**

A. Correct — archaea have no ribosomes
B. Correct — archaea live in extreme environments
C. Incorrect — resistance is target-specific; archaea lack peptidoglycan so β-lactams fail, but their ribosomes and enzymes differ only partly from bacterial ones, and other drug classes may still act
D. Incorrect — archaea are sensitive to every antibiotic that works on eukaryotes

**Answer: C**

Explanation: Resistance follows from whether the drug's target exists in the right form. β-Lactams have no target at all (no peptidoglycan), so resistance is absolute there — but that conclusion does not generalise to every compound. Archaeal ribosomes are 70S yet differ from bacterial ribosomes in sequence and in several drug-binding features, and archaeal membranes and metabolic enzymes present their own potential targets. A is false (70S ribosomes are present), B gives an irrelevant reason, and D is equally unsupported — a claim of universal sensitivity is as much an overstatement as one of universal resistance.

---

**10. Why is the archaeal genome's emphasis on DNA repair and histone-like proteins significant?**

A. It shows archaea are eukaryotes
B. It indicates shared ancestry of the informational machinery between archaea and eukaryotes, and it supports hyperthermophile survival where DNA damage is frequent
C. It proves archaea lack a cell nucleus permanently
D. It explains why archaea cannot be infected by viruses

**Answer: B**

Explanation: True histones (H3/H4-like tetramers) and repair systems homologous to eukaryotic Mre11–Rad50 and excision repair place the informational core of archaea next to that of eukaryotes — precisely the signal that suggested eukaryogenesis had an archaeal host. Functionally, the same machinery is essential at extreme temperatures, where depurination and strand breaks are frequent. A overstates the case: archaea remain prokaryotic in cell plan. C is a definitional observation rather than an explanation, and D is false — archaeal viruses are abundant and well studied.
