# Acids, Bases, and pH

## Core idea

All solutions are acidic, basic, or neutral. What changes between them is the concentration of hydrogen ions, and because that concentration spans many orders of magnitude, biology uses a logarithmic scale. This chapter is short but it underpins enzyme activity, protein shape, oxygen transport, and acid–base balance in blood.

## Acids and bases

### Bronsted–Lowry

The operational definition:

- An **acid** donates a proton ($\mathrm{H}^+$)
- A **base** accepts a proton ($\mathrm{H}^+$)

Water amphoteric — it can act as either:

```
DONATE H⁺  →  H₂O  →  H⁺ + OH⁻        (water acting as an acid)
ACCEPT H⁺  →  H₂O  + H⁺  →  H₃O⁺        (water acting as a base)
```

### Arrhenius

- An acid increases the concentration of $\mathrm{H}^+$ in water
- A base increases the concentration of $\mathrm{OH}^-$ in water

Brønsted–Lowry is the more general and more useful definition. An Arrhenius base such as sodium hydroxide dissociates to release $\mathrm{OH}^-$, which then *accepts* a proton from water — so the base is really $\mathrm{OH}^-$, acting in the Brønsted sense.

### The behaviour that matters

What an acid or base actually does to a solution is dissociate or ionise — to produce ions. This is the part that matters for biology:

```
HCl  →  H⁺ + Cl⁻        strong acid, ionises completely
CH₃COOH  ⇄  H⁺ + CH₃COO⁻    weak acid, ionises only partially
```

| Type | Behaviour in water |
| --- | --- |
| **Strong acid** | Completely ionised — the equilibrium lies entirely to the right |
| **Weak acid** | Partially ionised — an equilibrium between the undissociated and dissociated forms |
| **Strong base** | Completely ionised |
| **Weak base** | Partially ionised |

**Why the distinction is critical in biology:** weak acid and weak base groups — carboxyl groups ($\mathrm{-COOH}$) and amino groups ($\mathrm{-NH_2}$) — line the surfaces of proteins, so nearly every biological molecule carries both. Which form they take depends on pH, and that decides their charge, their interactions, and therefore their function.

## pH

**pH is the negative logarithm of the hydrogen ion concentration.**

$$[\mathrm{H}^+] = 10^{-\mathrm{pH}} \qquad \mathrm{pH} = -\log_{10}[\mathrm{H}^+]$$

| pH | $[\mathrm{H}^+]$ (mol/L) | Character | Example |
| --- | --- | --- | --- |
| 0 | $10^{0}$ = 1 | Strongly acidic | |
| 1 | $10^{-1}$ | | Gastric acid (≈1–3) |
| 2 | $10^{-2}$ | | |
| 4 | $10^{-4}$ | | |
| 6 | $10^{-6}$ | | |
| **7** | **$10^{-7}$** | **Neutral** | **Pure water; blood plasma 7.35–7.45** |
| 8 | $10^{-8}$ | | |
| 9 | $10^{-9}$ | | |
| 10 | $10^{-10}$ | | |
| 12 | $10^{-12}$ | | |
| 14 | $10^{-14}$ | Strongly basic | |

Two consequences of the logarithmic scale that must be understood rather than assumed:

**A change of one pH unit is a tenfold change in $[\mathrm{H}^+]$.** Moving from pH 7 to pH 6 is a tenfold increase. Moving from pH 7 to pH 5 is a hundredfold increase.

**The scale also runs backwards.** An increase in pH means a *decrease* in hydrogen ions. pH 9 is ten times more basic than pH 7, and pH 5 is ten times more acidic than pH 6.

## Neutral, acid, and base

At 25 °C, pure water ionises to exactly equal concentrations:

$$[\mathrm{H}^+] = [\mathrm{OH}^-] = 1.0 \times 10^{-7} \ \mathrm{mol/L} \quad \Rightarrow \quad \mathrm{pH} = 7.0$$

Because the ionisation of water always produces $\mathrm{H}^+$ and $\mathrm{OH}^-$ in equal amounts, the two concentrations are linked:

$$[\mathrm{H}^+] \times [\mathrm{OH}^-] = K_w = 1.0 \times 10^{-14} \quad \text{(at 25 °C)}$$

This relationship is the most useful thing in the chapter. It means:

- Add acid and $[\mathrm{H}^+]$ rises, so $[\mathrm{OH}^-]$ must fall
- Add base and $[\mathrm{OH}^-]$ rises, so $[\mathrm{H}^+]$ falls
- If $[\mathrm{H}^+] = 10^{-5}$, then $[\mathrm{OH}^-] = 10^{-9}$

So a solution is acidic **relative to 7.0 at 25 °C** — acidic means a higher hydrogen ion concentration than neutral water, not "containing acid molecules."

**A note on temperature.** The neutral pH depends on temperature, and shifts slightly below 7 as temperature rises. This matters practically: physiological values are quoted for 37 °C, where neutral water is about pH 6.8 and blood plasma sits at 7.35–7.45 — slightly basic. Blood is basic, and that is normal.

## Buffers

A **buffer** resists a change in pH when a modest amount of acid or base is added. This is what keeps blood pH within 0.04 units of normal despite continuous acid production.

A buffer is a **weak acid and its conjugate base** present together in comparable amounts:

```
H₂CO₃  ⇄  H⁺ + HCO₃⁻
weak acid      conjugate base
```

The logic is that either component can absorb what is added:

```
ADD ACID (H⁺)
   → HCO₃⁻ + H⁺ → H₂CO₃
   → conjugate base consumed, pH barely moves

ADD BASE (OH⁻)
   → H₂CO₃ + OH⁻ → HCO₃⁻ + H₂O
   → weak acid consumed, pH barely moves
```

**Buffers do not prevent pH change — they limit it, and only until one component is exhausted.** Once the reserve is used up, pH moves sharply. This is why a buffer system that is continuously stressed eventually fails, and why the consequences of that failure are abrupt.

The bicarbonate buffer system in blood is the most important one in medicine:

```
H₂CO₃  ⇄  H⁺ + HCO₃⁻
  ↑          ↑
carbonic      bicarbonate
acid
```

Carbonic acid ($\mathrm{H_2CO_3}$) is formed from carbon dioxide and water, which is why carbon dioxide is the most important acid–base factor in blood:

```
METABOLISM → CO₂ → H₂O + CO₂ ⇄ H₂CO₃ ⇄ H⁺ + HCO₃⁻
   ↑                                                 ↑
CO₂ increases → H⁺ increases → pH falls (acidosis)
```

Because the lungs control CO₂ and the kidneys control HCO₃⁻, the two organ systems described in 10 — Respiratory and 10 — Urinary are both part of one pH control system. That is the single most useful thing to take from this chapter for physiology.

### Henderson–Hasselbalch

For a buffer, pH is predicted from the ratio of base to acid:

$$\mathrm{pH} = \mathrm{p}K_a + \log_{10}\frac{[\mathrm{A}^-]}{[\mathrm{HA}]}$$

where $\mathrm{p}K_a$ is the pH at which acid and conjugate base are present in equal concentrations. The most useful consequence: **when the ratio is 1:1, pH = pK_a**, and because the logarithmic scale means a tenfold shift in that ratio moves the pH by only one unit, a buffer works well only within about one pH unit of its pK_a.

## Why pH changes function

### 1. Protein shape

```
pH change → protonation state of R-groups changes
         → net charge changes
         → hydrogen bonding and ionic interactions change
         → tertiary structure changes
         → active site distorts
         → substrate no longer fits
         → enzyme loses activity
```

The ionisable groups on a protein are:

| Group | Behaviour |
| --- | --- |
| Carboxyl ($\mathrm{-COOH}$) | Loses a proton readily; becomes negatively charged ($\mathrm{-COO^-}$) |
| Amino ($\mathrm{-NH_2}$) | Accepts a proton readily; becomes positively charged ($\mathrm{-NH_3^+}$) |
| Histidine side chain | Ionises near physiological pH; the group that gives many enzymes their pH sensitivity |

Each protein has its own isoelectric point — the pH at which its net charge is zero — and solubility is lowest there.

### 2. Oxygen transport

This is the most direct physiological link, and it is high-yield.

```
H⁺ + HCO₃⁻ ⇄ H₂CO₃ ⇄ CO₂ + H₂O
   ↑         ↑
HIGHER pH → CO₂ is held as bicarbonate → haemoglobin holds O₂ readily
LOWER pH  → CO₂ is released        → haemoglobin releases O₂
```

This is the **Bohr effect**. In a tissue actively metabolising, it produces CO₂ and acid. The acid lowers pH, which shifts the reaction to the right, CO₂ is released, and haemoglobin lets go of oxygen. The tissue gets the oxygen it needs. In the lungs the reverse happens: CO₂ is exhaled, pH rises, and haemoglobin becomes a better oxygen carrier.

**Oxygen delivery is therefore pH-dependent.** That single fact is why blood pH is one of the most closely monitored values in clinical practice, and why changes in blood pH produce changes in tissue oxygenation.

### 3. Enzyme activity

Every enzyme has an **optimal pH** at which its active site is correctly charged and its rate is highest.

| Enzyme | Optimal pH | Reason |
| --- | --- | --- |
| Pepsin | ~1.5–2 | Stomach; acid needed for it to work and to keep it dormant in storage |
| Trypsin | ~7.5–8 | Small intestine; slightly alkaline |
| Salivary amylase | ~6.7 | Mouth; near neutral |

**Common confusion:** a change in body pH does not change the optimum pH of an enzyme. It moves the enzyme away from the conditions it works best in. The enzyme is not broken — it is functioning suboptimally.

## Medical relevance

**Normal blood pH is tightly defended.** Arterial pH is 7.35–7.45. Values outside 7.30–7.50 are clinically significant, and a pH below 7.35 is termed **acidaemia** (with **acidosis** referring to the process), above 7.45 **alkalaemia**. The narrowness of that range is what makes pH such a sensitive marker of physiological stress — and it is defended by three buffering systems working together: bicarbonate, phosphate, and plasma protein buffers.

**Disturbance of pH by failure of the systems that regulate it.** The three dominant causes follow directly from the regulation systems described above:

| Cause | Mechanism |
| --- | --- |
| **Respiratory** | Hypoventilation retains CO₂ → H₂CO₃ rises → pH falls. Hyperventilation blows off CO₂ → pH rises |
| **Metabolic** | Excess acid production or failure to excrete acid → bicarbonate consumed → pH falls |
| **Renal** | Failure of the kidneys to excrete acid or reclaim bicarbonate → pH disturbed |

Recognising which of the three is responsible is the whole question clinically, and the answer is determined by looking at what the compensating system is doing — which is why arterial blood gas results are read as a set of numbers rather than one value.

**Blood pH and cardiac function.** Cardiac muscle is highly sensitive to changes in pH. Acidosis reduces contractility and disrupts potassium channel behaviour, so the heart both pumps less effectively and becomes more prone to arrhythmia. This is why blood pH is one of the monitored variables during resuscitation.

**Local pH and tissue damage.** When a limb is crushed or a tissue is deprived of blood, cells switch partly to anaerobic metabolism and lactic acid accumulates. Local pH falls, and the falling pH is itself part of the injury: it impairs enzyme function and damages cell membranes. It is the reason debridement and restoring blood flow are time-sensitive concerns.

**Stomach acid as a chemical defence.** Gastric pH of 1–3 kills most ingested microbes and denatures ingested protein. Note that this is a *hostile* environment for the acid-secreting cells themselves, which is why they are protected by a mucus–bicarbonate barrier. That barrier failing is the mechanism of ulcer formation, in 10 — Digestive.

**Common confusion to retire:** "an acid is a substance that contains hydrogen." A substance can contain hydrogen and be basic — water, for one, and proteins at physiological pH. What matters is hydrogen ion concentration in solution, not whether the word appears in the formula.

## Key facts

- **Brønsted–Lowry:** acid = proton donor, base = proton acceptor. **Arrhenius:** acid raises $[\mathrm{H}^+]$, base raises $[\mathrm{OH}^-]$.
- Strong acids and bases **fully** ionise; weak ones reach an **equilibrium**.
- $\mathrm{pH} = -\log_{10}[\mathrm{H}^+]$ — one pH unit = tenfold change, and pH runs **inversely** to $[\mathrm{H}^+]$.
- $[\mathrm{H}^+]\times[\mathrm{OH}^-] = 1.0\times10^{-14}$ at 25 °C; at pH 7 both equal $10^{-7}$.
- **Buffers** are a weak acid plus its conjugate base. They resist change until one component is depleted, then fail.
- **Blood pH 7.35–7.45.** Carbonic acid / bicarbonate is the dominant buffer.
- **Bohr effect:** lower pH → haemoglobin releases more O₂.
- pH alters protein shape and therefore enzyme activity; it does not alter the enzyme's optimum pH.

## Practice questions

**1. A solution has a pH of 5. What is its hydrogen ion concentration, relative to a neutral solution?**

A. The same as at pH 7
B. One hundred times higher than at pH 7
C. Ten times higher than at pH 7
D. Ten times lower than at pH 7

**Answer: B**

Explanation: pH is logarithmic, so each unit is a tenfold change. From pH 7 to pH 5 is two units, so $[\mathrm{H}^+]$ is $10^{2} = 100$ times higher, i.e. $1.0 \times 10^{-5}$ mol/L compared with $1.0 \times 10^{-7}$ mol/L at pH 7. C accounts for only one unit.

---

**2. Which statement about strong and weak acids is correct?**

A. A strong acid ionises completely in water, whereas a weak acid ionises only partially
B. A strong acid is more concentrated than a weak acid
C. A weak acid has a lower molecular mass than a strong acid
D. A strong acid cannot be neutralised by a base

**Answer: A**

Explanation: Strong and weak describe the *extent* of ionisation, not the concentration — a dilute solution of a weak acid can have a lower $[\mathrm{H}^+]$ than a concentrated solution of another. C is false, and D is false because strong acids are neutralised completely and rapidly, which is what makes them dangerous. Complete ionisation is why a strong acid has a lower pK_a than a weak acid.

---

**3. A buffer solution is prepared with equal amounts of a weak acid and its conjugate base. What happens when a small amount of strong acid is added?**

A. The pH increases
B. The pH decreases sharply
C. The buffer is destroyed and the solution becomes neutral
D. The conjugate base binds the added protons, so the pH changes only slightly

**Answer: D**

Explanation: The conjugate base is present in sufficient quantity to accept the added protons, converting to the weak acid and consuming the added $\mathrm{H}^+$. Because pH is logarithmic, that small consumption of free hydrogen ions produces only a slight shift. This is exactly why the buffer is there. A is false because adding acid cannot raise the pH. B would be the result if the reserve were exhausted; C is backwards.

---

**4. Blood pH rises from 7.40 to 7.46. Which change in red blood cells has most likely occurred?**

A. Complete conversion of oxyhaemoglobin to reduced haemoglobin
B. Increased haemoglobin binding of oxygen
C. Destruction of the haemoglobin
D. Decreased haemoglobin binding of oxygen

**Answer: B**

Explanation: By the Bohr effect, higher pH shifts the reaction $\mathrm{H^+ + HCO_3^- \rightleftharpoons H_2CO_3 \rightleftharpoons CO_2 + H_2O}$ to the left, decreasing CO₂ and raising the pH. Haemoglobin's affinity for oxygen is higher at higher pH, so it holds oxygen more firmly. This is essential in the lungs. D describes what a fall in pH does instead: it has the opposite effect and promotes oxygen release in tissues.

---

**5. Why is it incorrect to describe an acid as 'a substance that contains hydrogen'?**

A. Hydrogen is only present as a gas in acids
B. Acids do not exist in nature
C. Many substances containing hydrogen, including water, are neutral or basic
D. Acids contain no hydrogen ions

**Answer: C**

Explanation: What defines an acidic solution is its raised hydrogen ion concentration, not the presence of the element hydrogen. Water contains two hydrogen atoms per molecule and is neutral. B is false — a weak acid still contains hydrogen; it simply ionises incompletely. A and D are false.

---

**6. At 25 °C, a solution has $[\mathrm{H}^+] = 1.0 \times 10^{-5}$ mol/L. What is its pH, and is it acidic, basic, or neutral?**

A. pH −5, acidic
B. pH 5, acidic
C. pH 9, acidic
D. pH 5, basic

**Answer: B**

Explanation: $\mathrm{pH} = -\log_{10}(1.0 \times 10^{-5}) = 5$. Since $10^{-5}$ exceeds the $10^{-7}$ hydrogen ion concentration of neutral water, the solution is acidic. Note that pH has no negative values — A inverts the logarithm. And since $[\mathrm{H}^+] \times [\mathrm{OH}^-] = 10^{-14}$, this solution's hydroxide concentration is $10^{-9}$, making pH 9 the pH of a *separate* solution, not this one.

---

**7. An enzyme functions optimally at pH 7.5. Its active site has a histidine residue whose ionisable group sits at that pH. What is the most likely effect of raising the pH to 9?**

A. The residue loses its proton and changes charge, so the active site's shape no longer complements the substrate
B. The substrate becomes denatured
C. The enzyme gains activity because pH is higher
D. The enzyme is permanently destroyed

**Answer: A**

Explanation: At pH 9, well above the pK_a of the histidine side chain, the group is almost entirely deprotonated and its charge has changed. That alters the local chemistry and hydrogen bonding of the active site, so the substrate no longer fits and the rate falls. The enzyme is not destroyed — its structure is disturbed reversibly, which is why restoring the pH restores the activity. D confuses a shift in optimum conditions with irreversible destruction. B is a category error — it is the enzyme, not the substrate, whose ionisation state matters here.

---

**8. A patient's arterial pH is 7.28, below the normal range, and the cause is a failure of the kidneys to excrete acid. Which pair of changes should accompany this?**

A. Bicarbonate falls as acid accumulates, and ventilation increases to lower CO₂
B. Bicarbonate falls as acid accumulates, and ventilation decreases to raise CO₂
C. Bicarbonate rises as a compensation, and ventilation decreases to raise CO₂
D. Bicarbonate rises as a compensation, and ventilation increases to lower CO₂

**Answer: A**

Explanation: This is a **metabolic acidosis**: the primary disturbance is a fall in bicarbonate, because acid that is not excreted consumes bicarbonate. The respiratory compensation runs in the opposite direction to the acidosis — ventilation increases so that more CO₂ is exhaled, and removing CO₂ pulls the equilibrium $\mathrm{H^+ + HCO_3^- \rightleftharpoons H_2CO_3 \rightleftharpoons CO_2 + H_2O}$ toward CO₂ and water, lowering the hydrogen ion concentration. In a **respiratory acidosis** the bicarbonate would instead rise slightly, as a compensation for retained CO₂. The direction of the bicarbonate change is therefore what identifies the process as metabolic rather than respiratory, and the pH value alone cannot tell you which it is.

---

**9. Which best explains why pepsin functions in the stomach but is inactive in the small intestine?**

A. Pepsin cannot function above 37 °C
B. Pepsin is destroyed by the neutral pH of the small intestine
C. Pepsin's optimal pH is acidic; in the slightly alkaline small intestine its active site is not correctly ionised
D. Pepsin requires carbon dioxide to function

**Answer: C**

Explanation: Pepsin has an optimum pH of about 1.5–2. The small intestine is at pH 7.5–8, which is well outside that range, so the ionisation of its catalytic groups is wrong and the substrate does not bind properly. The molecule is not destroyed — it would work again at low pH. This is a shift away from optimal conditions, not irreversible damage. D is false; human body temperature is close to optimum for most human enzymes.

---

**10. A solution is described as acidic. Compared with neutral water at the same temperature, it must have**

A. A pH above 7
B. A lower hydrogen ion concentration
C. A higher hydroxide ion concentration
D. A higher hydrogen ion concentration

**Answer: D**

Explanation: Acidic means a higher hydrogen ion concentration than neutral water. Because $[\mathrm{H}^+]\times[\mathrm{OH}^-]$ is constant, a higher $[\mathrm{H}^+]$ necessarily means a lower $[\mathrm{OH}^-]$. A, B, and C all describe a basic solution, not an acidic one.