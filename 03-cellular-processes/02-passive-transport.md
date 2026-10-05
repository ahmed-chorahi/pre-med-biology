# Passive Transport: Diffusion, Facilitated Diffusion, Osmosis, Tonicity

## Why it matters

Cells must acquire nutrients and dispose of waste without spending ATP on every molecule. **Passive transport** is the answer: movement **down a gradient, with no energy input**, driven only by the random motion of particles. The whole chapter is one idea with four names — *diffusion, facilitated diffusion, osmosis, tonicity* — and one rule: **passive transport never moves a substance against its gradient, and it never continues once equilibrium is reached.**

Everything here follows from the membrane's selective permeability from [02 — Cell Biology](../02-cell-biology/02-plasma-membrane-and-nucleus.md): small nonpolar molecules cross freely; everything else needs a protein. The proteins make it *facilitated*, not *active* — the gradient still provides the energy.

## Diffusion

**Diffusion is the net movement of particles from high concentration to low concentration, caused by random thermal motion.** Individual molecules move randomly in all directions; statistically, more leave the crowded side than the uncrowded side, so there is *net* movement until concentrations equalise.

```
t = 0                    t = mid                   t = equilibrium

 ●●●●● ●                  ●●● ● ●                  ● ● ● ● ●
 ●●●●● ●                  ● ● ● ● ●                ● ● ● ● ●
 ●●●●● ●                  ● ● ● ● ●                ● ● ● ● ●
 ─────────                ─────────                 ─────────
                          net movement →            NO NET MOVEMENT
                                                  (still moving both ways)
```

**At equilibrium, motion does not stop — only net movement stops.** This distinction matters for understanding why transport proteins are still needed at "equilibrium" in some contexts, and why diffusion is a statistical phenomenon rather than a directed one.

### What speeds diffusion up

| Factor | Effect |
| --- | --- |
| **Temperature** | Higher — faster molecular motion |
| **Steepness of gradient** | Steeper — more net movement |
| **Mass of the particle** | Lighter — faster (small molecules move faster than large ones) |
| **Medium** | Faster in gas than liquid than gel |
| **Distance** | Diffusion time rises with the **square** of distance |

**The distance limit is the crucial one for biology.** Diffusion is fast over micrometres and useless over centimetres — a molecule takes milliseconds to cross a cell but hours to cross a large organism's body. **This is why no organism above microscopic size can rely on diffusion alone**, and why circulatory systems, lungs, and guts exist: they bring surfaces to the material instead of letting material diffuse to the surfaces. Surface area and distance, not chemistry, are why you need a cardiovascular system.

### Diffusion across the membrane

Two routes, decided by the molecule:

```
SMALL NONPOLAR (O₂, CO₂, steroid hormones)
        ──────────────────▶  straight through the lipid bilayer

IONS, GLUCOSE, AMINO ACIDS, POLAR MOLECULES
        ──── ✕ blocked ────  must use a TRANSPORT PROTEIN
```

**Simple diffusion rate depends on:** lipid solubility (partition coefficient), size, and the gradient. Ethanol and anaesthetic gases cross easily; glucose and Na⁺ do not cross at all.

## Facilitated diffusion

**Facilitated diffusion is passive transport through a membrane protein.** The protein provides a route; the *gradient still supplies all the energy*. It is therefore not a form of active transport despite involving a protein.

### Two kinds of transport protein

| | **Channel** | **Carrier (permease)** |
| --- | --- | --- |
| **Mechanism** | Open hydrophilic pore (when open) | Undergoes conformational change; binds and releases |
| **Speed** | Up to 10⁸ ions/sec — near diffusion limit | ~10²–10⁴ molecules/sec |
| **Selectivity** | By **diameter and charge** | By **binding-site shape and chemistry** |
| **Regulation** | Gating: voltage, ligand, mechanical, light | Substrate availability; phosphorylation |
| **Example** | Aquaporin, K⁺ leak channel | GLUT transporters (glucose) |

**Gated channels** open and close — this is how a nerve impulse works, and it is covered in 10 — Nervous. The principle is here: **a channel that never closed would be a leak, not a signal.**

### The kinetic signature

Facilitated diffusion shows **saturation** — because carriers are finite:

```
RATE
    │           ─────────── Vmax   (all carriers occupied)
    │          /
    │         /      ← facilitated
    │        /           diffusion saturates
    │       /
    │   ───/──────────────  simple diffusion: linear, no limit
    │    /
    └────────────────────→ concentration gradient
```

- **Simple diffusion:** rate rises in direct proportion to the gradient — no limit, no saturation, because no protein is involved.
- **Facilitated diffusion:** rate rises then plateaus — **Vmax when all carriers are busy.**

This curve is the diagnostic difference between the two. A transport process that plateaus has a protein in it. (Same logic as enzyme kinetics in [05 — Enzymes](../01-biochemistry/05-enzymes.md) — because a carrier *is* a binding protein with a finite number of sites.)

**GLUT transporters** illustrate the family: **GLUT1** (basal uptake, most cells), **GLUT2** (liver and pancreatic β-cells — low affinity, high capacity, acts as a glucose sensor), **GLUT4** (muscle and fat — **stored in vesicles and moved to the membrane only when insulin signals**), **GLUT3** (neurons — high affinity, constant supply).

**GLUT4 is the diabetes-relevant one:** insulin triggers GLUT4-containing vesicles to fuse with the membrane, inserting carriers and raising glucose uptake up to ~10-fold. Insulin resistance can involve failure of this translocation — the mechanism chapter 03 of this section builds on when it covers regulation.

## Osmosis

**Osmosis is the net movement of water across a selectively permeable membrane, from high water concentration to low water concentration.**

Why water crosses when solutes cannot: the membrane is permeable to water (slowly through the lipids, rapidly through **aquaporins**) but not to most solutes. So when solute concentrations differ across the membrane, water moves to equalise them.

### How to think about it without getting reversed

Two equivalent vocabularies; use whichever the question uses:

| Water moves toward... | Same statement as... |
| --- | --- |
| **Hypertonic side** (more solute) | Lower water potential |
| The side where solute will dissolve | To dilute the more concentrated solution |

**Memory aid:** *water follows solute.* Where there is more dissolved stuff, water goes.

### Osmotic pressure

The pressure needed to **stop** osmosis — a **colligative property**, proportional to the number of dissolved particles, not their identity:

```
osmotic pressure ∝ concentration of PARTICLES
```

So 1 M glucose and 1 M NaCl do not exert equal osmotic pressure: NaCl dissociates into two ions, so it contributes nearly twice the particles. In clinical fluids, this is why **normal saline (0.9% NaCl) and 5% dextrose are not interchangeable in osmotic effect despite both being "isotonic-ish"** — the particle count governs.

## Tonicity

**Tonicity describes how a solution changes a cell's volume** — a *functional* property, not just a concentration.

| Solution | Compared with cell | Water moves... | Cell result |
| --- | --- | --- | --- |
| **Hypotonic** | Less solute | **Into** the cell | **Swells** → may lyse (animal) or become turgid (plant) |
| **Isotonic** | Equal solute | In and out equally | **No net change** — normal shape |
| **Hypertonic** | More solute | **Out of** the cell | **Shrinks** → crenates (animal) or plasmolyses (plant) |

```
   HYPOTONIC         ISOTONIC         HYPERTONIC

     ╭───╮           ┌───┐             .·.·.
    │ 💧 │ cells     │   │            ( ·○· )  shrivelled
     ╰─┬─╯  swell    └───┘             '·°·'
    lysis if        normal            crenation
    animal
```

**Animal vs plant responses differ because only plants have a wall:**

- **Animal cell in hypotonic solution** → water enters → swells → **lyses** (no wall to resist). Red blood cells are the standard example.
- **Plant cell in hypotonic solution** → water enters → vacuole pushes against the wall → **turgor** → wall pushes back → **equilibrium at high pressure**. Turgor is what holds a herbaceous plant upright.
- **Plant cell in hypertotonic solution** → water leaves → membrane pulls away from the wall → **plasmolysis** — and it is *reversible* if returned to water, until the cell is damaged.

### Why tonicity and osmolarity are not synonyms

- **Osmolarity** = measured total particle concentration (a physical quantity).
- **Tonicity** = the *non-penetrating* solute's effect on cell volume (a biological outcome).

A solution of urea may be iso-osmolar with plasma yet **hypotonic in effect**, because urea slowly penetrates the cell: it equalises first, then water follows it in. **Only solutes that cannot cross determine tonicity.** Exam questions routinely test this exact difference.

## Putting it together: the three passive routes

| Route | Who uses it | Energy | Saturable? |
| --- | --- | --- | --- |
| **Simple diffusion** | O₂, CO₂, N₂, steroid hormones, ethanol | Gradient only | No |
| **Facilitated diffusion** | Glucose (GLUT), amino acids, ions through channels | Gradient only | **Yes** |
| **Osmosis** | Water (aquaporins or lipids) | Water potential gradient | Aquaporins can saturate |

All three are passive: **none can move a substance against its gradient, and none uses ATP directly.** The moment a cell needs to go *against* the gradient, it pays — which is chapter 03.

## Medical relevance

**IV fluid choice is applied tonicity.**

| Fluid | Tonicity | Effect on cells |
| --- | --- | --- |
| **0.9% NaCl (normal saline)** | Isotonic | Volume preserved |
| **5% dextrose in water** | Initially isotonic, then hypotonic as glucose is metabolised | Water enters cells after metabolism |
| **0.45% NaCl (half-normal)** | Hypotonic | Cells swell gradually |
| **3% / 5% NaCl** | Hypertonic | Cells shrink — used carefully to reduce cerebral oedema |

Giving plain water intravenously would lyse red blood cells — a direct consequence of the hypotonic row.

**Red blood cells as the standard model.** In hypotonic solution they lyse (haemolysis); in hypertotic solution they crenate. Both appearances are classic microscopy findings, and both follow directly from the absence of a cell wall.

**Tonicity in infections and wounds.** **Hypertonic saline** draws water out of bacteria and oedematous tissue — the same osmosis, applied deliberately. Conversely, organisms living in high salt (halophiles) have internal chemistry matched to their environment, because a mismatch would dehydrate them instantly.

**Kidney handling of water.** The nephron concentrates urine by making the medulla hypertonic and letting water leave through aquaporins — osmosis doing the kidney's work. The details are in 10 — Urinary; the principle is this chapter's middle section.

**Osmotic pressure in the circulation.** Plasma protein loss (nephrotic syndrome, liver failure) lowers blood colloid osmotic pressure → water stays in tissues → **oedema**. The physics of the last section, expressed as a disease sign.

## Key facts

- Passive transport = **down a gradient, no ATP, equilibrium stops net movement** (molecular motion continues).
- Diffusion rate ∝ gradient and temperature; **diffusion time ∝ distance²**, which is why large organisms need circulatory systems.
- **Facilitated diffusion uses proteins but no energy**; channels are fast pores, carriers are slower conformational changers.
- **Saturation (Vmax)** distinguishes carrier-mediated transport from simple diffusion — the curve plateaus because carriers are finite.
- **Osmosis** = water moving down its own gradient across a permeable membrane; **water follows solute.**
- **Osmotic pressure** is colligative — depends on particle number, not identity (NaCl counts double).
- **Tonicity** is set only by **non-penetrating** solutes: hypotonic → swell/lyse; hypertonic → shrink/crenate; plants gain **turgor** instead of lysing because of the wall.
- Tonicity ≠ osmolarity: a penetrating solute can be iso-osmolar yet hypotonic in effect.
- **GLUT4** moves to the membrane on insulin signal — the link between this chapter and glucose regulation.

## Practice questions

**1. A cell is placed in a solution containing a solute that cannot cross the membrane. The cell shrinks. The solution is**

A. Hypotonic
B. Isotonic
C. Hypertonic
D. Isotonic but hyperosmolar

**Answer: C**

Explanation: Shrinkage means water left the cell, which happens when the outside solution has more non-penetrating solute — a hypertonic solution. Water follows solute. Hypotonic solutions would swell the cell; an isotonic solution would produce no net change.

---

**2. Which observation distinguishes facilitated diffusion from simple diffusion experimentally?**

A. Facilitated diffusion requires ATP
B. The rate plateaus at high concentrations because transport proteins become saturated
C. Facilitated diffusion moves substances against the gradient
D. Simple diffusion requires a channel

**Answer: B**

Explanation: Saturation is the signature of a finite number of transport proteins — the same logic as enzyme Vmax. Facilitated diffusion uses no ATP (A) and never goes against a gradient (C); simple diffusion needs no protein at all (D) and shows a rate that rises linearly with the gradient.

---

**3. Water moves across a selectively permeable membrane toward the side with**

A. More non-penetrating solute — lower water concentration
B. Less solute
C. Higher glucose only if glucose is a penetrating solute
D. Equal osmotic pressure but higher temperature

**Answer: A**

Explanation: More solute means fewer free water molecules — a lower water concentration — so net water movement is toward that side. "Water follows solute" is the same statement. B would describe movement away from solute, which is backwards.

---

**4. Why does a solution of 1 M NaCl have a greater osmotic pressure than 1 M glucose?**

A. NaCl is more soluble
B. NaCl dissociates into two particles, and osmotic pressure is proportional to particle number
C. Glucose is a penetrating solute
D. Sodium binds water more strongly per molecule

**Answer: B**

Explanation: Osmotic pressure is colligative — it depends on how many particles are dissolved, not what they are. NaCl yields ~2 ions per formula unit, glucose stays as 1 molecule, so the NaCl solution has roughly twice the particle concentration. C is irrelevant to comparing two solutions directly.

---

**5. A red blood cell is placed in pure water. What happens and why?**

A. It shrinks — water leaves down its gradient
B. It stays the same — water cannot cross the membrane
C. It swells and may lyse — water enters osmotically because there is no wall to resist
D. It becomes turgid

**Answer: C**

Explanation: Pure water is maximally hypotonic relative to the cytoplasm, so water enters through aquaporins and the lipids; an animal cell has no wall, so it swells and the membrane bursts (haemolysis). Turgidity (D) describes plant cells, which are saved by the wall.

---

**6. A plant cell in a hypertonic solution shows the membrane pulling away from the cell wall. This is called**

A. Turgor
B. Plasmolysis
C. Lysis
D. Crenation

**Answer: B**

Explanation: Water leaves the vacuole and cytoplasm, the plasma membrane shrinks inward and separates from the wall — plasmolysis, reversible if returned to hypotonic solution before damage. Crenation is the equivalent shrivelling of an animal cell; lysis is bursting; turgor is the pressurised state in hypotonic conditions.

---

**7. Which statement correctly distinguishes osmolarity from tonicity?**

A. They are identical terms
B. Osmolarity counts all solute particles; tonicity depends only on non-penetrating solutes' effect on cell volume
C. Tonicity counts particles; osmolarity depends on penetration
D. Osmolarity applies only to plant cells

**Answer: B**

Explanation: Osmolarity is a physical measurement of total particles. Tonicity is a biological outcome: only solutes that cannot cross the membrane can sustain a gradient that moves water and changes cell volume. A penetrating solute contributes to osmolarity but not to lasting tonicity — which is why urea solutions can be iso-osmolar yet hypotonic in effect.

---

**8. Which process requires energy input to move a substance across a membrane?**

A. Osmosis
B. Facilitated diffusion through a channel
C. Simple diffusion of oxygen
D. Sodium ions moving against their concentration gradient through a pump

**Answer: D**

Explanation: Movement against a gradient is, by definition, not passive — it requires ATP (or an coupled gradient). Osmosis and both forms of diffusion move substances *down* their gradients and cost no direct energy. The pump in D is primary active transport, the subject of the next chapter.

---

**9. Why do large multicellular organisms require a circulatory system rather than relying on diffusion?**

A. Diffusion stops at equilibrium and cannot continue in tissues
B. Diffusion time increases with the square of distance, so it is far too slow to supply cells more than a short distance from a surface
C. Diffusion does not occur in body fluids
D. Circulation generates ATP for tissues

**Answer: B**

Explanation: Diffusion is rapid over micrometres but grows with distance squared — a centimetre-scale supply would take hours. Circulatory, respiratory, and digestive systems exist to keep every cell within a short diffusion distance of a supply line. A is wrong because diffusion continues (dynamically at equilibrium) as long as concentration differences are maintained by consumption.

---

**10. Insulin increases glucose uptake in muscle by**

A. Opening a glucose channel that is always present
B. Increasing the gradient for simple diffusion
C. Triggering GLUT4-containing vesicles to fuse with the plasma membrane, inserting more carriers
D. Phosphorylating glucose so it cannot leave the cell

**Answer: C**

Explanation: Muscle and fat cells store GLUT4 internally; insulin signalling causes those vesicles to translocate and fuse with the membrane, raising the number of carriers and thus Vmax for glucose uptake. Failure of this translocation is part of insulin resistance. The glucose is then phosphorylated *after* entry (D), which traps it but does not cause its uptake.
