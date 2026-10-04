# Lipids

## Why they matter

Lipids are the only one of the four macromolecule families that is **not** a polymer, and the only one defined by behaviour rather than by a repeating backbone. That is why lipids are so structurally diverse — steroids, waxes, and carotenoids look nothing alike but all share one property: they are poorly soluble in water.

That single shared property produces most of their functions, including cell membranes, energy storage, and insulation.

## What makes a lipid a lipid

| Feature | Consequence |
| --- | --- |
| Predominantly nonpolar | Hydrophobic; insoluble in water |
| High proportion of C–H bonds | C–H is nonpolar, so these contribute nothing to water solubility |
| Often contain only C, H, and O | No nitrogen or phosphorus required |

The key phrase is **predominantly**. Many lipids contain a small polar region — a carboxyl group, a phosphate group, a hydroxyl group — and it is that polar region that makes them behave in specific, predictable ways. Amphipathic lipids, which have both, are the basis of membranes.

## Fatty acids

Fatty acids are the building blocks of most lipids.

```
       CH₃—CH₂—CH₂—CH₂—(CH₂)ₙ—COOH
       ↑                        ↑
   methyl end              carboxyl group
                            (polar, ionisable)
```

Two defining features:

**The carboxyl group (–COOH)** is polar and can lose a proton to become **–COO⁻**. This is the reactive end that forms bonds with other molecules, and it is why fatty acids are described as amphipathic.

**The hydrocarbon tail** is a chain of nonpolar C–H bonds. Its length determines the fatty acid's melting behaviour: longer tails have more dispersion interactions between chains, so they are more tightly packed and have higher melting points.

### Saturated vs unsaturated

The critical distinction is the presence of carbon–carbon **double bonds**.

```
SATURATED                UNSATURATED (cis)
    H   H   H               H      H
    |   |   |               |      |
— C— C — C — C —        — C ═ C — C —
    |   |   |               |  \        ↑
    H   H   H               H   \  H   kink
                                        |
                        the cis double bond forces a permanent bend
```

| Property | Saturated | Unsaturated |
| --- | --- | --- |
| C=C double bonds | None | One or more |
| Shape | Straight | Kinked at each cis double bond |
| Chain packing | Tight | Loose |
| Melting point | Higher | Lower |
| State at room temperature | Often solid (fats) | Often liquid (oils) |
| Hydrogenation | Already saturated | Possible — converts oil to solid fat |

**Why the kink matters, mechanistically.** Dispersion interactions between neighbouring fatty acid tails are the main attractive force holding a lipid layer together. A cis double bond puts a permanent bend in the chain so neighbouring tails cannot pack closely. Fewer contacts means less energy stabilises the layer, so the melting point falls and the lipid is fluid at a lower temperature. Everything downstream — oil versus fat, membrane fluidity, cooking behaviour — follows from that geometry.

**Common confusion to retire: trans vs cis.** A *trans* double bond does not produce a kink, because the substituents lie opposite across the double bond. A trans fatty acid therefore behaves like a saturated fatty acid, packing tightly and having a relatively high melting point. Hydrogenation (used to turn liquid oils into solid fats) produces predominantly trans isomers, which is why trans fats behave as saturated fats despite having double bonds.

### Essential fatty acids

The body cannot synthesise certain fatty acids and must obtain them from the diet — these are **essential fatty acids**:

| Fatty acid | Why needed |
| --- | --- |
| **Linoleic acid** (omega-6) | Precursor for arachidonic acid and eicosanoids |
| **α-Linolenic acid** (omega-3) | Precursor for EPA and DHA, which contribute to membrane phospholipids |

Eicosanoids — prostaglandins, thromboxanes, leukotrienes — are potent local regulators of inflammation, vascular tone, and clotting, and are derived from arachidonic acid. So the chain from dietary fatty acid to inflammatory mediator is a chain to keep in mind:

```
DIETARY OMEGA-6 → LINOLOEIC ACID → ARACHIDONIC ACID → PROSTAGLANDINS / THROMBOXANES / LEUKOTRIENES
   ↑                                                                                ↓
   └──────────────── regulates inflammation, vascular tone, platelet aggregation
```

This is covered further in 10 — Immune and 10 — Cardiovascular.

## Lipid subclasses

### Triglycerides (triacylglycerols)

Formed from **three fatty acids** attached to one glycerol backbone. Not true polymers.

```
GLYCEROL — three hydroxyl groups
   +
THREE FATTY ACIDS — each with one carboxyl group
   ↓ esterification (three dehydration reactions)
TRIGLYCERIDE + 3 H₂O
```

| Property | Detail |
| --- | --- |
| Function | **Long-term energy storage** — about 9 kcal/g, more than double carbohydrate or protein |
| Where stored | Adipose tissue (fat), liver |
| Function in adipose | Not stored as a bulk phase; stored as **triglyceride droplets** within adipocytes |
| Why droplets | Lipids are already hydrophobic; storing them in an aqueous phase would require a surface that would still be exposed to water |
| Isomer of interest | A **triglyceride** in which one fatty acid has been removed is a **diglyceride**; two removed, a **monoglyceride** — these intermediates appear in lipid metabolism |

Triglycerides are chemically inert and water-insoluble, which is ideal for storage: they can be stored in concentrated form without water, they do not interfere with the cellular aqueous environment, and they cannot leave the cell by diffusion.

### Phospholipids

A glycerol backbone, **two fatty acids**, and a **phosphate group** attached to a third alcohol. So the third position is occupied by a polar, charged head rather than by a hydrocarbon chain.

```
        polar head group
              |
   CH₂ — O — P — O — CH₂
   |                        |
 CH = CH                CH = CH      ← two hydrophobic tails
   |
 CH₂ — O — P ...
```

This is an **amphipathic** molecule — it has a hydrophilic region and a hydrophobic region — and it is the structural basis of every cell membrane.

**Why that produces a bilayer:**

```
WATER   ← hydrophilic heads face the water on both sides
─────
 o o o     heads
|tail|     tails point inward, away from water
|tail|
 o o o
─────
WATER
```

The tails are excluded from water by the hydrophobic effect, so they cluster in the interior where no water is present, while the polar heads remain in contact with water on either side. The bilayer is stable *and* fluid, and it self-seals because lipids in the interior are not energetically committed to any particular arrangement. The tail's kinks are why it stays fluid — see 02 — Cell Biology.

Phospholipid classes are named by the alcohol attached to the phosphate:

| Class | Alcohol | Where notable |
| --- | --- | --- |
| Phosphatidylcholine (lecithin) | Choline | Cell membranes; egg yolk |
| Phosphatidylethanolamine | Ethanolamine | Cell membranes |
| Phosphatidylserine | Serine | Cell membranes; negatively charged; membrane signalling |
| Phosphatidylinositol | Inositol | Cell signalling — cleaved to give second messengers |

That last row is the reason phospholipids appear in cell signalling at all. Phosphatidylinositol bisphosphate in the inner leaflet of the membrane is cleaved by phospholipase C into **diacylglycerol**, which stays in the membrane, and **inositol trisphosphate**, which is released and diffuses into the cytoplasm to act as a second messenger. A structural lipid generating a signal is a good example of structure producing function.

### Steroids

Four fused carbon rings plus functional groups. Not derived from fatty acids at all.

| Steroid | Role |
| --- | --- |
| **Cholesterol** | Membrane fluidity buffer; precursor for steroid hormones |
| **Testosterone** | Androgen; from cholesterol |
| **Oestrogen** | From cholesterol |
| **Progesterone** | From cholesterol |
| **Cortisol** | Glucocorticoid; from cholesterol |
| **Aldosterone** | Mineralocorticoid; from cholesterol |
| **Vitamin D** | From cholesterol, with UV light |

**Common confusion:** cholesterol is not a fat and not a fatty acid. It is a steroid with a rigid four-ring structure. This is not a semantic point — the rigid ring system and the near absence of hydrocarbon tails are why cholesterol *intercalates between phospholipid tails* rather than aligning with them, and that specific geometry is what gives it its buffering effect on membrane fluidity.

### Waxes

Long-chain fatty acids esterified to long-chain alcohols. Highly hydrophobic, used for waterproofing.

| Example | Function |
| --- | --- |
| Sebum | Lubricates and waterproofs skin and hair |
| Cerumen (earwax) | Waterproofs the ear canal |
| Cuticular wax on leaf surfaces | Reduces water loss |
| Beeswax | Structural |

### Other lipids

| Lipid | Function |
| --- | --- |
| **Terpenes** | Fragrance, flavour, rubber; precursor to many steroids and vitamins |
| **Steroids** | Hormones, cholesterol, vitamin D |
| **Waxes** | Waterproofing |
| **Eicosanoids** | Prostaglandins, thromboxanes, leukotrienes — local regulators |
| **Fat-soluble vitamins** | A, D, E, K |

## Summary of functions

| Function | Example |
| --- | --- |
| **Long-term energy storage** | Triglycerides in adipose tissue and liver |
| **Thermal insulation** | Subcutaneous fat |
| **Membranes** | Phospholipid bilayer; cholesterol modulates fluidity |
| **Structure / waterproofing** | Waxes |
| **Hormones** | Steroid hormones — oestrogen, testosterone, cortisol |
| **Signalling** | Eicosanoids, phosphatidylinositol-derived second messengers |
| **Precursors** | Cholesterol → steroid hormones and vitamin D |
| **Fat-soluble transport** | Dietary lipids carried in lipoproteins — see 10 — Cardiovascular |

## Medical relevance

**Dietary fat is transported, not dissolved.** Triglycerides and cholesterol are packaged into **lipoproteins** — particles with a hydrophilic protein and phospholipid shell surrounding a core of hydrophobic lipid. Four are clinically central:

| Lipoprotein | Composition | Clinical significance |
| --- | --- | --- |
| **Chylomicron** | Most triglyceride; enters lymph, then blood | Carries dietary fat from intestine to tissue |
| **VLDL** | Rich in triglyceride | Made by liver; precursor to LDL |
| **LDL** | Cholesterol-rich; density low because of fat content | Delivers cholesterol to tissues; high levels associated with atherosclerotic risk |
| **HDL** | Protein-rich; density high | Reverse cholesterol transport; low levels associated with higher risk |

The classes are named for **density**, which reflects the protein-to-lipid ratio — not for their function or where they came from. This explains why "low density" and "high density" correlate oppositely with risk. The system is covered in 10 — Cardiovascular.

**Fat digestion is a separate pathway from carbohydrate and protein.** Bile salts emulsify large fat droplets into small ones — mechanically increasing the surface area available to lipases, exactly the surface-area principle that constrains cell size (see [02 — Biological organization](../00-foundations/02-biological-organization.md)). Lipase then hydrolyses triglycerides at the intestinal brush border. The absorbed products are reassembled into triglycerides inside intestinal cells and packaged into chylomicrons, because they must cross into lymph rather than blood directly.

**Essential fatty acids are a dietary requirement, not an optional nutrient.** Deficiency produces a specific pattern — scaly skin, impaired wound healing, and poor growth — and it is worth recognising because the mechanism is a failure to make a class of molecules rather than to obtain energy.

**Phospholipids in cell signalling.** Phosphatidylinositol bisphosphate, a membrane phospholipid, is cleaved to produce two second messengers: diacylglycerol, which stays in the membrane, and inositol trisphosphate, which diffuses into the cytoplasm. This is how many hormones that cannot cross the membrane signal to the cell. See 10 — Endocrine.

**Eicosanoids mediate inflammation and vascular tone.** Prostaglandins and leukotrienes derived from arachidonic acid contribute to inflammatory response, vasodilation, and bronchoconstriction. This is why NSAIDs act by blocking cyclooxygenase, the enzyme at the head of that pathway — the drug mechanism and the biochemical pathway are the same fact. See 10 — Immune.

**Cholesterol in membranes is a fluidity buffer, not simply a negative.**

```
LOW TEMPERATURE          HIGH TEMPERATURE
lipids packed tight      lipids too mobile, leaky
      ↓ cholesterol inserts between tails and holds them apart
   FLUIDITY MAINTAINED ACROSS TEMPERATURE
```

Because its rigid ring system lacks the flexible tails of a fatty acid, cholesterol does not align with them; it wedges between them and restrains their movement. So it *reduces* fluidity at high temperature and *prevents tight packing and rigidification* at low temperature. Membrane lipids in the body are therefore not uniformly fluid, and temperature-sensitive organisms — including mammals — depend on this buffering.

**Steroid hormones are made from cholesterol,** which is why the adrenal cortex needs cholesterol as a precursor and why the endocrine system sits downstream of cholesterol availability. See 10 — Endocrine.

## Key facts

- Lipids are **not true polymers**; they are defined by **hydrophobicity**, not by a repeating backbone.
- Fatty acids: **carboxyl head** (polar, ionisable) + **hydrocarbon tail** (nonpolar).
- **Saturated** = no C=C → straight → tightly packed → higher melting point. **Unsaturated** = C=C → **cis kink** → loose packing → lower melting point.
- Cis kinks prevent tight packing; **trans** double bonds do **not** kink.
- **Triglycerides** = glycerol + 3 fatty acids → long-term energy storage, ~9 kcal/g.
- **Phospholipids** = glycerol + 2 fatty acids + phosphate head → **amphipathic** → the bilayer.
- **Steroids** = 4 fused rings; not fatty acid derivatives. Cholesterol → steroid hormones + vitamin D.
- **Eicosanoids** (from arachidonic acid) = prostaglandins, thromboxanes, leukotrienes.
- Lipoproteins transport lipids; classes are named by **density**, which tracks the protein:lipid ratio.
- Cholesterol **buffers** membrane fluidity — reducing it when too high, preventing rigidification when too low.

## Practice questions

**1. Why does a cis double bond in a fatty acid lower its melting point?**

A. The double bond weakens the covalent bonds along the chain
B. The double bond adds polar groups to the chain
C. The chain becomes shorter at the double bond
D. The kink it introduces prevents neighbouring tails from packing closely, reducing dispersion interactions between them

**Answer: D**

Explanation: Dispersion interactions between well-packed hydrocarbon tails are the main attractive force in a lipid layer. A cis double bond imposes a permanent bend so tails cannot align, which reduces the number of contacts and lowers the melting point. A is wrong — covalent bond strength is not meaningfully affected, and breaking bonds is not what melting involves. B is false; a double bond is nonpolar. C is false; no carbons are removed.

---

**2. Which statement correctly describes phospholipids?**

A. They are completely nonpolar and insoluble in water
B. They contain a hydrophilic phosphate head and hydrophobic fatty acid tails, making them amphipathic
C. They consist of four fused carbon rings
D. They are true polymers of fatty acids

**Answer: B**

Explanation: A phospholipid has a glycerol backbone, two fatty acid tails, and a phosphate-containing head group. The polar head and nonpolar tails make it amphipathic, which is precisely what allows it to form a bilayer with heads facing water on both sides. A is wrong — that combination of head and tails makes the molecule amphipathic, not completely nonpolar and insoluble. C describes steroids, which are built from four fused carbon rings. D is wrong because lipids are not true polymers.

---

**3. A lipid is described as saturated. What does that indicate about its structure?**

A. All of its carbons are bonded to the maximum possible number of hydrogen atoms but still contains double bonds
B. It is soluble in water
C. It has been fully hydrogenated and contains no carbon–carbon double bonds
D. It contains equal numbers of saturated and unsaturated fatty acids

**Answer: C**

Explanation: "Saturated" means no carbon–carbon double bonds, so every carbon carries the maximum number of hydrogens possible given its bonding. A carbon–hydrogen double bond would itself be a double bond, so A is contradictory. B describes a mixture rather than a molecule. D is backwards — saturated fats are more hydrophobic.

---

**4. Lipoproteins are classified by density. What determines a lipoprotein's density?**

A. The ratio of protein to lipid, since protein is less dense than lipid
B. The number of triglycerides it contains
C. Its diameter
D. Where it was produced

**Answer: A**

Explanation: Lipoproteins are spherical particles with a protein and phospholipid shell around a core of hydrophobic lipid. The more protein relative to lipid, the higher the density — which is why HDL is the most protein-rich and most dense, and LDL and chylomicrons are lipid-rich and less dense. The triglycerides (B), size (C), and tissue of origin (D) all correlate with composition but do not define density.

---

**5. A cell is surrounded by an aqueous environment, yet it maintains a stable lipid bilayer. What makes the bilayer possible?**

A. The bilayer is held together by covalent bonds between adjacent lipids
B. Phospholipids are small enough to dissolve in water
C. The hydrophobic tails are repelled by water and cluster in the interior, while the polar heads remain in contact with water
D. Water bonds covalently to the phosphate heads

**Answer: C**

Explanation: This is the hydrophobic effect. Lipid tails are nonpolar and cannot hydrogen-bond with water, so they cluster where no water is present, while the polar heads stay in the aqueous phase on either side. This produces a bilayer that is both stable and self-sealing. A is false — lipids are not covalently bonded to one another, and it is those weak noncovalent contacts that allow fluidity. B and D are false; a bilayer is not a solution, and water associates with the phosphate head by hydrogen bonding rather than covalent bonds. the opposite applies.

---

**6. Which statement about cholesterol in cell membranes is correct?**

A. It is the main structural component of the lipid bilayer
B. It has a rigid four-ring structure and wedges between phospholipid tails, reducing fluidity when it is too high and preventing tight packing when it is too low
C. It increases membrane fluidity at all temperatures
D. It forms covalent bonds with phospholipids

**Answer: B**

Explanation: Cholesterol lacks flexible hydrocarbon tails, so rather than aligning with them it inserts between them and restrains movement. At high temperature this reduces excessive fluidity; at low temperature it prevents the tight packing that would rigidify the membrane. It therefore buffers fluidity across a temperature range. A is only half true. C is false, and D is wrong — phospholipids form the bilayer, and cholesterol is a minority component.

---

**7. A patient cannot synthesise certain fatty acids and must obtain them from the diet. These are called**

A. Free fatty acids
B. Polyunsaturated fats
C. Non-essential fatty acids
D. Essential fatty acids

**Answer: D**

Explanation: Essential fatty acids are those the body cannot synthesise and must obtain from diet — linoleic acid and α-linolenic acid. They are needed to make eicosanoids and membrane phospholipids. Non-essential fatty acids can be synthesised. Polyunsaturated describes a bond pattern, not a dietary requirement, and free fatty acids describes a metabolic intermediate, not a dietary category.

---

**8. Fat digestion in the small intestine is facilitated by bile salts. What is their role?**

A. They emulsify large fat droplets into smaller ones, increasing the surface area available to lipases
B. They enzymatically cleave the ester bonds in triglycerides
C. They transport lipids across the intestinal cell membrane
D. They are broken down to supply energy

**Answer: A**

Explanation: Bile salts emulsify — they break large fat globules into fine droplets, increasing surface area so lipase can act more efficiently. This is the same surface-area principle that constrains maximum cell size and shapes the alveoli. B is wrong because lipase, not bile salts, cleaves ester bonds. C is the function of micelles and chylomicrons; bile salts participate in micelle formation but do not themselves cross the membrane. D is not their function.

---

**9. Why is it accurate to describe cholesterol as a steroid rather than a fat?**

A. Cholesterol has a rigid four-fused-ring structure rather than hydrocarbon chains, and is not derived from fatty acids
B. Cholesterol is unsaturated
C. Cholesterol contains no oxygen atoms
D. Cholesterol is a protein

**Answer: A**

Explanation: Steroids are defined by four fused carbon rings with attached functional groups. Cholesterol has this structure and is not derived from fatty acids, so "fat" — which implies fatty-acid chains — does not fit. B is false; cholesterol contains several hydroxyl groups. C is false. D is not the basis of the distinction, and most of the cholesterol molecule is not unsaturated.

---

**10. A pathway begins with arachidonic acid and produces prostaglandins, thromboxanes, and leukotrienes. Which statement correctly connects this pathway to medicine?**

A. These mediators function as cell membrane components
B. These mediators are derived from dietary essential fatty acids and regulate inflammation, vascular tone, and platelet aggregation
C. These mediators are steroid hormones made from cholesterol
D. These mediators are produced only in the digestive tract

**Answer: B**

Explanation: Arachidonic acid derives from the essential fatty acid linoleic acid, and its eicosanoid products act as local regulators of inflammation, vascular tone, and platelet function. This is why NSAIDs act by blocking cyclooxygenase, the enzyme at the head of this pathway — the drug mechanism and the biochemical pathway are the same fact. C describes steroids, which are built from cholesterol by a different biosynthetic pathway entirely. A and D misstate the source and function of these mediators.