# Homeostasis: The Full Control Loop

## Why it matters

Medicine is the study of what happens when a control loop fails. A patient rarely presents with a number; they present with a deviation the body could no longer hold, or with the side effects of the holding itself. Fever is a control centre working correctly at a raised target; oedema in heart failure is an effector working correctly on a problem it cannot solve. Reading illness means reading loop anatomy.

Every chapter in section 10 — [Anatomy and Physiology](../10-anatomy-and-physiology/) — follows one progression: **structure → function → mechanism → regulation → homeostasis**. [01 — Four tissue types](01-four-tissue-types.md) and [02 — Organs and organ systems](02-organs-and-organ-systems.md) supply the first three; this chapter defines the last two — **regulation**, how activity is adjusted by other parts of the body, and **homeostasis**, the closed-loop correction holding a variable within a defended range.

The template matters more than the examples, which are interchangeable: temperature, glucose, pressure, and pH are one circuit drawn four times. Learn the chain and each new system becomes naming components rather than learning a new idea.

## What homeostasis is — and what it is not

### A dynamic steady state

**Homeostasis** (from *homeo*, same, and *stasis*, standing) is the continuous maintenance of a variable within a defended range by negative feedback. The word doing the work is *continuous*: corrections overshoot, disturbances arrive unannounced, effectors lag, so the value oscillates around its target. Homeostasis is a **dynamic steady state** — a band held open by metabolic work — not a frozen number; an unchanging 37.000 °C all day would mean a broken controller.

| Term | Definition | Example: body temperature |
| --- | --- | --- |
| **Controlled variable** | The quantity held within limits | Core temperature |
| **Set point** | The value the control centre defends | ~37 °C |
| **Normal range** | The band accepted without correction | ~36.5–37.5 °C |
| **Stimulus** | Whatever pushes the variable out of range | Cold immersion, exertion, infection |
| **Negative deviation** | Value falls below the set point | Excess heat loss → cooling |
| **Positive deviation** | Value rises above the set point | Excess heat production → warming |

Two rules follow. **The response opposes the deviation, not the variable**, and **negative feedback removes the deviation, not the stimulus**: an hour in the cold does not switch the loop off, so heat production and heat loss can run at once.

### Homeostasis is not equilibrium

The commonest error is treating homeostasis as "balance", and balance as everything stopping. **Equilibrium** is reached when all gradients have dissipated and no work remains; in an organism it is death.

| Property | Homeostatic steady state | Thermodynamic equilibrium |
| --- | --- | --- |
| Exchange and energy | **Open**; energy continuously spent to pump, contract, secrete | Effectively closed; no work done |
| Gradients and variable | Actively maintained; the value oscillates in a defended band | Dissipated; the value is fixed |
| Disturbance | Detected and opposed | Absent — the system adopts the new state |
| Status | Alive | Dead |

An ecosystem shows the contrast: a mature pond is an open-system steady state, but nothing in it *measures* its temperature or pH and *corrects* them — if the climate shifts, the pond shifts with it. A body **defends** its values, fighting back through named components at a cost in ATP. Homeostasis is not balance but *actively maintained imbalance*.

## The negative feedback loop, component by component

Every negative feedback loop decomposes into the same seven elements. Learn them as a sequence, because exams and ward reasoning ask you to *locate* a failure: which link is broken?

### The master arrow chain

```
      STIMULUS / DISTURBANCE
  (pushes the variable away from its set point)
                ↓
           RECEPTOR
  (detects the deviation; makes a signal)
                ↓
     AFFERENT (INPUT) PATHWAY
  (signal travels TOWARD the control centre)
                ↓
         CONTROL CENTRE
  (compares with the SET POINT; selects an output:
   hypothalamus, medulla, islet, kidney, adrenal)
                ↓
     EFFERENT (OUTPUT) PATHWAY
  (nerve or hormone carries the command out)
                ↓
         EFFECTOR
  (the muscle or gland that can change the value)
                ↓
         RESPONSE
  (it OPPOSES the original change)
                ↓
  VARIABLE RETURNS TO ITS NORMAL RANGE
                ↓
  receptor signal FALLS → output falls → responses
  switch off → loop idles until the next deviation
```

The last two steps are what make the feedback *negative*: the response undermines its own trigger, so the loop settles instead of running away.

| Component | Question it answers | What its failure looks like |
| --- | --- | --- |
| **Set point** | What is the target? | Moved (fever), or none defended |
| **Receptor** | Who noticed? | Silent drift — nephrogenic diabetes insipidus |
| **Afferent pathway** | How did the message get in? | Signal never arrives (sensory neuropathy) |
| **Control centre** | Who decides? | Wrong decision at normal input (inappropriate ADH) |
| **Efferent pathway** | How did the command get out? | Issued but undelivered (autonomic neuropathy) |
| **Effector** | Who can change the value? | No capacity to act (type 1 diabetes) |
| **Response** | Did it oppose the change? | Wrong direction or magnitude |

## Four worked examples

### 1. Thermoregulation

```
COLD → heat loss exceeds heat production → temperature FALLS
        ↓
cutaneous + central THERMORECEPTORS (afferent nerves)
        ↓
HYPOTHALAMUS compares with the ~37 °C set point
        ↓  autonomic + somatic efferent output
EFFECTORS: muscle → SHIVERING ; skin vessels → VASOCONSTRICTION
           adrenal medulla → ↑ metabolic rate ; BEHAVIOUR → warmth
        ↓
HEAT CONSERVED AND MADE → temperature returns to range
        ↓
receptor firing falls → responses switch off

WARM → temperature RISES → hypothalamus →
sweat glands → EVAPORATIVE COOLING ; vessels → VASODILATION ;
behaviour → shade → heat lost → loop idles
```

| Component | Thermoregulation |
| --- | --- |
| Controlled variable | Core temperature (~37 °C, defended to about ±0.5 °C) |
| Stimulus | Cold exposure; exertion or a hot environment |
| Receptor | Cutaneous warm and cold fibres, plus hypothalamic neurons sensing blood |
| Afferent pathway | Spinothalamic tracts; local hypothalamic sensing |
| Control centre | **Posterior hypothalamus** |
| Efferent pathway | Sympathetic nerves to skin vessels and sweat glands; somatic motor nerves |
| Effector | Skeletal muscle, cutaneous arterioles, eccrine sweat glands |
| Response | Shivering, vasoconstriction when cold; sweating, vasodilation when warm |

Behaviour is part of the loop: the only arm with access to the environment, and the first lost in delirium or hypothermia.

**Fever is the same loop with a moved target.** Pyrogens and cytokines (IL-1, IL-6, TNF-α) induce hypothalamic cyclo-oxygenase → **prostaglandin E₂**, raising the defended value; the full pathway is in [06 — Host–pathogen interaction](../07-microbiology/06-host-pathogen-interaction.md). A shivering patient at 39.5 °C is not thermoregulating badly: the intact controller is driving *up* to the new target. Fever is a **reset**, not a breakdown.

### 2. Blood glucose

```
ABSORBED MEAL → blood glucose RISES
        ↓
β CELLS sense the rise (glucose → ATP → K⁺ channels close)
        ↓  efferent: INSULIN released
EFFECTORS — liver, muscle, adipose tissue
        ↓  glycogenesis; ↓ gluconeogenesis; glucose → triglyceride
        ↓  GLUT4 moved to the membrane → ↑ glucose uptake
BLOOD GLUCOSE FALLS → β-cell stimulus falls → insulin falls

FASTING / EXERCISE → blood glucose FALLS
        ↓
α CELLS secrete GLUCAGON → LIVER
        ↓  GLYCOGENOLYSIS, then GLUCONEOGENESIS (lactate, glycerol, amino acids)
GLUCOSE RELEASED → glucose rises → glucagon falls → loop idles
```

| Component | Blood glucose regulation |
| --- | --- |
| Controlled variable | Blood glucose (~4–5 mmol/L fasting) |
| Stimulus | Carbohydrate absorption (rise); fasting or exertion (fall) |
| Receptor and control centre | The **islet β cell and α cell** — each senses glucose directly |
| Afferent pathway | Intrinsic glucose metabolism within the islet cell |
| Efferent pathway | Hormonal: insulin and glucagon in the blood |
| Effector | Liver (glycogenesis, glycogenolysis, gluconeogenesis), muscle (glycogen, uptake), fat (lipogenesis) |
| Response | **Insulin lowers glucose; glucagon raises it** |

**Insulin is the only hormone that lowers blood glucose**, while glucagon, adrenaline, cortisol, growth hormone, and thyroid hormone all raise it: hypoglycaemia kills in minutes, hyperglycaemia over decades — one dedicated reducer against a committee of raisers. The β cell is itself a complete loop: glucose entry raises the ATP:ADP ratio, K_ATP channels close, the membrane depolarises, calcium enters, granules exocytose — why sulfonylureas close that channel directly. Liver uses insulin-independent GLUT2, muscle and fat **GLUT4** ([04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md)).

### 3. Blood pressure

Arterial pressure is cardiac output × peripheral resistance, defended on two timescales: a fast neural loop for the first seconds, a slow hormonal loop after that.

```
HAEMORRHAGE / standing up → arterial pressure FALLS
        ↓
BARORECEPTORS (carotid sinus, aortic arch) fire less
        ↓  afferent: glossopharyngeal (IX), vagus (X)
CARDIOVASCULAR CENTRE OF THE MEDULLA
        ↓  efferent: ↑ sympathetic, ↓ parasympathetic
HEART → ↑ rate and contractility ; ARTERIOLES → VASOCONSTRICTION
        ↓
CARDIAC OUTPUT × RESISTANCE rise → pressure returns to set point
        ↓
baroreceptor firing normalises → medullary output falls

SUSTAINED LOW PRESSURE (minutes to days)
        ↓  ADH → aquaporin-2 → water retained
        ↓  juxtaglomerular cells → RENIN → angiotensin II + aldosterone
Na⁺ and water retained, vessels constricted → pressure ↑
```

| Component | Rapid baroreflex | Slow hormonal / renal arm |
| --- | --- | --- |
| Stimulus | Sudden pressure change | Sustained low pressure or perfusion |
| Receptor | Baroreceptors, carotid sinus and aortic arch | Juxtaglomerular cells; osmoreceptors, volume sensors |
| Afferent pathway | Cranial nerves IX and X to the medulla | Humoral renin cascade; renal signalling |
| Control centre | Medullary cardiovascular centre | Kidney; hypothalamic–pituitary–adrenal axis |
| Efferent pathway | Sympathetic and parasympathetic nerves | ADH, angiotensin II, aldosterone |
| Effector | Heart, arteriolar and venous smooth muscle | Kidney, arterioles, adrenal cortex |
| Response | ↑ rate, ↑ contractility, vasoconstriction | Water and sodium retention → pressure restored |
| Timescale | **One or two heartbeats; seconds** | Minutes to days |

Layering solves a general problem: a loop fast enough to stop you fainting cannot be sustained, and one built on renal sodium handling can run for weeks but is too slow for syncope. **Bodies pair a rapid, shallow, self-limiting loop with a slow, deep, sustainable one.** Chronic hypertension *resets* the baroreceptors to the prevailing pressure — receptor recalibration, not a set-point change.

### 4. Blood pH

Arterial pH is defended at **7.35–7.45** — a hydrogen ion range of roughly 35–45 nmol/L. The severity follows from enzymes: catalysis depends on the ionisation of active-site residues, so a shift of a few tenths impairs substrate binding and structure ([06 — Acids, bases, and pH](../00-foundations/06-acids-bases-and-ph.md), [05 — Enzymes](../01-biochemistry/05-enzymes.md)).

```
METABOLIC ACID LOAD (lactate, ketoacids, renal H⁺ loss)
        ↓  [H⁺] rises → pH FALLS

LAYER 1 — CHEMICAL BUFFERS   (SECONDS)
        H⁺ + HCO₃⁻ ⇌ H₂CO₃ ⇌ CO₂ + H₂O → H⁺ consumed, pH blunted

LAYER 2 — RESPIRATORY   (1–3 MINUTES)
        chemoreceptors detect ↓ pH / ↑ CO₂ → medullary centre
        ↓  HYPERVENTILATION → CO₂ BLOWN OFF
        ↓  [H₂CO₃] falls → equilibrium shifts LEFT → H⁺ consumed
        ↓  pH rises back toward 7.35–7.45

LAYER 3 — RENAL   (HOURS TO DAYS)
        kidney EXCRETES H⁺ and regenerates HCO₃⁻ → pH normal
```

| Layer | Speed | What it fixes | Limitation |
| --- | --- | --- | --- |
| **Chemical buffers** (bicarbonate, phosphate, protein) | **Seconds**, until the buffer base is consumed | Any strong acid or alkali, immediately | **Finite capacity** — blunts, removes nothing |
| **Respiratory** (ventilation alters CO₂) | **1–3 minutes** | The CO₂ limb of the buffer equation | Volatile component only |
| **Renal** (H⁺ excretion, HCO₃⁻ regeneration) | **Hours**, full over **2–3 days** | The **only** layer that removes acid | Too slow for an acute crisis |

Speed and capacity are traded off: the instantaneous defences are trivial and exhaust quickly, while the layer with unlimited capacity takes days to recruit. Hence acute acidosis is managed at the ventilator first, and the *pattern* of compensation diagnoses — metabolic acidosis by Kussmaul breathing, respiratory acidosis by renal bicarbonate retention.

## Positive feedback: when amplification is the point

**Positive feedback** gives the response the same sign as the stimulus: it reinforces the deviation instead of opposing it. It is self-amplifying, does not settle, and is not homeostatic — licensed only where a process must be driven past a threshold, and since an unstable loop left running would destroy the system, **every positive loop must terminate on an external event or off-switch.**

### Childbirth: the Ferguson reflex

```
FETAL HEAD PRESSES ON THE CERVIX during a contraction
        ↓  stretch receptors in the cervix
afferent nerves → HYPOTHALAMUS → POSTERIOR PITUITARY
        ↓  OXYTOCIN released
UTERUS CONTRACTS → the fetus is driven further against the cervix
        ↓
MORE STRETCH → MORE OXYTOCIN → STRONGER CONTRACTION
        ↓  each cycle AMPLIFIES the last
TERMINATION IS EXTERNAL: delivery removes the stretch → loop ends
```

**Milk ejection** is the same design: suckling → nipple receptors → hypothalamus → oxytocin → myoepithelial cells contract → milk ejected → the infant suckles harder → more oxytocin.

| Positive loop | What amplifies | How it terminates |
| --- | --- | --- |
| **Childbirth (Ferguson reflex)** | Oxytocin → contraction → more stretch → more oxytocin | Delivery ends it |
| **Milk ejection** | Oxytocin → myoepithelial contraction → more suckling | Feeding ends |
| **Clotting cascade** | Trace Xa → thrombin → more Xa; platelets recruit platelets | **Brakes**: antithrombin III, protein C; failure gives DIC |
| **Action potential** | Na⁺ influx → depolarisation → more Na⁺ channels open | **Inbuilt**: channel inactivation plus K⁺ repolarisation |

| Feature | Negative feedback | Positive feedback |
| --- | --- | --- |
| Effect on the deviation | **Opposes** it | **Amplifies** it |
| Sign of the loop | Opposite in sign to the stimulus | Same in sign as the stimulus |
| Stability | Stabilising, self-limiting | Unstable; ends only by event or off-switch |
| Steady state | Reaches one | Never — runs to a threshold or termination |
| Duration | Continuous, idling between disturbances | Brief, event-driven |
| Examples | Temperature, glucose, pH, pressure, calcium | Childbirth, milk ejection, clotting, action potential |
| Failure signature | A value drifts out of range | Runaway: DIC, seizures |

**Why positive feedback is rare** follows from the table: negative feedback produces a stable operating point, which is what an organism needs for nearly every variable, and positive feedback cannot produce stability by construction. It does three jobs only — pushing through a threshold (the action potential), completing an event rapidly (expulsion of the fetus), and irreversible commitment (clotting). When the ending fails, disease follows: DIC, or a seizure.

## Moving the set point deliberately

A set point is not fixed: several states legitimately shift the defended value, and distinguishing a true set-point change from a change in receptor sensitivity is a recurring trap.

| Situation | Set point moved? | Mechanism |
| --- | --- | --- |
| **Circadian core temperature** | **Yes** — ~0.5 °C | The suprachiasmatic nucleus anticipates the active phase: temperature peaks late afternoon, nadirs around 04:00 |
| **Basal body temperature after ovulation** | **Yes** — +0.3–0.5 °C | Progesterone from the corpus luteum acts on hypothalamic thermoregulation; a biphasic chart confirms it |
| **Fever** | **Yes** — +1–4 °C | Pyrogens → IL-1, IL-6, TNF-α → hypothalamic PGE₂ |
| **Heat acclimatisation** | No — effector gain is retuned | Sweating starts earlier, larger and more dilute; plasma volume expands |
| **Behavioural choice** | No — higher centres override output | Cortical drive acts on the effector arm only |

### Receptor adaptation is not a set-point change

| | Receptor adaptation | True set-point change |
| --- | --- | --- |
| **Where** | At the **receptor** — sensitivity declines under sustained stimulation | At the **control centre** — a different value is defended |
| **The variable itself** | Not defended differently | Genuinely defended at a new value |
| **Examples** | Olfactory adaptation (the smell vanishes, concentration unchanged); *Aplysia* habituation; baroreceptor resetting in hypertension | Fever; circadian temperature; post-ovulation basal temperature |
| **Clinical trap** | "The drug stopped working" may be receptor-level | Treat the *cause of the moved target*, not the value alone |

**Habituation** is a decreased response to a repeated, irrelevant stimulus; **sensitisation** is an increased response after a noxious event. Both change reflex gain at receptor, synapse, or effector — neither moves a defended set point.

## Neural and endocrine control arms

Almost every loop uses one or both output systems; section 10 develops them in [03 — Nervous system](../10-anatomy-and-physiology/03-nervous-system.md) and [04 — Endocrine system](../10-anatomy-and-physiology/04-endocrine-system.md).

| Property | Neural control | Endocrine control |
| --- | --- | --- |
| Signal carrier | Action potential; neurotransmitter at a synapse | Hormone carried in the blood |
| Onset | **Milliseconds to seconds** | Seconds to minutes; hours for genomic effects |
| Duration | Brief — ends when the neuron stops firing | Long — until the hormone is cleared (minutes to days) |
| Specificity | **Point-to-point**: one synapse, one target cell | **Broadcast**: restricted to cells bearing the right receptor |
| Effectors | Skeletal, cardiac and smooth muscle, glands | Liver, kidney, bone, gonad, thyroid, adipose |
| Ideal for | Phasic correction of an imminent deviation | Sustained correction of a slow deviation |

Most loops use both, in sequence: the neural arm buys time while the endocrine arm solves the problem. Blood pressure uses the baroreflex for ten seconds and ADH, angiotensin II, and aldosterone for the next ten days; glucose pairs rapid insulin exocytosis with slower transcriptional changes over hours.

## Failure modes: the medical frame

If every system is a control loop, every disease is a loop fault, and the faults cluster by component.

| Condition | Component that fails | Loop logic |
| --- | --- | --- |
| **Type 1 diabetes** | **Effector loss** — β cells destroyed by autoimmunity | The lowering arm does not exist; replace the signal |
| **Type 2 diabetes** | **Effector resistance** — liver, muscle, fat respond poorly | Reduced gain; β-cell overproduction compensates until it cannot |
| **Heart failure** | Effector capacity exhausted; compensation then harms | Low output read as low pressure → fluid retained → oedema, raised workload → decompensation |
| **SIADH** | **Control centre issues a wrong output** | ADH secreted with no disturbance to correct |
| **Nephrogenic diabetes insipidus** | **Effector unresponsive to the signal** | Centre works; the kidney ignores ADH → massive dilute urine |
| **Baroreflex failure** | Afferent or efferent neural pathway | Standing evokes no vasoconstriction → orthostatic hypotension |
| **Drug tolerance** | **Receptor arm** — fewer receptors or weaker coupling | The same signal gives a smaller response; the dose–response curve shifts right |
| **Addisonian crisis** | Effector hormone absent (aldosterone, cortisol) | Sodium and water lost, glucose falls, tone collapses |

### Medicine's three levers

| Lever | What is acted on | Examples |
| --- | --- | --- |
| **1. Remove the disturbance** | The stimulus driving the deviation | Antibiotics and source control end pyrogen drive; fluid replaces haemorrhage |
| **2. Support the effector** | Supply or replace the output arm | **Insulin** in type 1 diabetes; oxygen; a pacemaker; hydrocortisone; antipyretics block PGE₂ so a raised set point falls |
| **3. Reset or repair the receptor arm** | Sensitivity, receptor number, loop gain | Weight loss and sensitising drugs restore insulin sensitivity; opioid taper reverses tolerance |

## Medical relevance

**Clinical reasoning is component identification.** The useful question when a value is abnormal is not "what is the number?" but "which link is broken?" Dilute urine with a high ADH level points to a control centre issuing the wrong output; orthostatic hypotension with no rise in heart rate points to the afferent or efferent limb; a potassium rise without aldosterone points to the effector side.

**Diabetes shows two failures in one loop.** Type 1 is effector loss: destroy the β cell and no signalling can lower glucose, so therapy supplies the missing signal. Type 2 is effector resistance: insulin is present, often in excess, but liver, muscle, and fat respond weakly, so treatment targets the response arm while protecting a β cell worked to death to compensate.

**Heart failure is where a correct loop becomes the disease.** Falling output is read as low pressure, so renin, angiotensin II, aldosterone, and ADH retain sodium and water until pressure recovers — on paper the loop has succeeded, in the patient there is oedema and a greater workload. The patient looks stable for months before decompensation is sudden, which is why ACE inhibitors and beta-blockers are used in a weak heart: they treat the compensation, not the number it produces.

**Receptor-level pharmacology explains tolerance and withdrawal.** Chronically occupied receptors are internalised or uncoupled, so a constant agonist concentration yields a falling response — tolerance is receptor downregulation, not drug degradation. The same rightward shift of the dose–response curve explains the diminishing effect of nitrates and opioids and why abrupt withdrawal produces an exaggerated opposite effect.

**Fever is the most commonly misunderstood presentation.** A pyrogen-driven rise is a moved set point: shivering is a working controller driving toward a higher target, so antipyretics are for comfort, not a marker of success. Acid–base reading is the same lesson in response times — acidotic within minutes of an airway obstruction means only buffers and the respiratory centre have acted, so ventilation comes first.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "Homeostasis means the internal environment never changes" | It is a **dynamic steady state**: the value oscillates inside a defended band because disturbances and corrections never stop. Perfect constancy would mean a broken controller. |
| "Homeostasis is equilibrium" | **Equilibrium is death** — all gradients dissipated, no work done. Homeostasis is an open, energy-dependent defence the environment would not supply. |
| "Negative feedback removes the stimulus" | It removes the **deviation from the set point**. Standing in the cold keeps the loop running, so heat production and heat loss can both be elevated. |
| "Positive feedback is always pathological" | It is normal for childbirth, milk ejection, clotting, the action potential, and the LH surge; pathological only when termination fails. |
| "A fever means thermoregulation broke down" | Fever is a **set-point reset**: cytokines induce hypothalamic PGE₂, and shivering is the intact loop working toward the new target. |
| "An ecosystem's steady state is homeostasis" | Ecosystem stability is a **balance of flows** with no receptor, centre, or effector defending a target; it drifts with the conditions. |
| "Insulin and glucagon are symmetric opposites" | They oppose each other, but **insulin is the only glucose-lowering hormone**; glucagon, adrenaline, cortisol, growth hormone, and thyroid hormone all raise it. |
| "Receptor adaptation means the set point changed" | Adaptation occurs **at the receptor** (smell, habituation, baroreceptor resetting); a set-point change occurs **at the control centre** (fever, circadian temperature, ovulation). |
| "Tolerance means the drug was destroyed" | Tolerance is usually **receptor downregulation**, often reversible on withdrawal — hence abrupt stopping can produce an exaggerated opposite effect. |

## Key facts

- **Homeostasis is a dynamic steady state**: a variable is held within a **normal range** around a **set point** by continuous negative feedback, not frozen at one value.
- **Homeostasis is not equilibrium** — equilibrium is a closed-system endpoint with no gradients and no work, which in an organism is death.
- The universal loop is **stimulus → receptor → afferent pathway → control centre → efferent pathway → effector → response opposing the change**; that response then removes its own trigger.
- **Negative feedback removes the deviation, not the stimulus** — the loop runs as long as the disturbance persists.
- **Thermoregulation**: thermoreceptors → hypothalamus → shivering, vasoconstriction, sweating, behaviour; **fever is a pyrogen-driven reset of the set point**.
- **Blood glucose**: β cells release **insulin** (glycogenesis, GLUT4 uptake, glucose falls); α cells release **glucagon** (glycogenolysis, gluconeogenesis, glucose rises). **Insulin is the only glucose-lowering hormone.**
- **Blood pressure** is defended on two timescales: the baroreflex within one or two heartbeats, ADH/angiotensin II/aldosterone over minutes to days.
- **Blood pH 7.35–7.45** is defended by buffers (**seconds**), respiratory compensation (**minutes**), and renal compensation (**hours to days**); only the kidneys remove fixed acid, and pH must stay narrow because enzyme ionisation and protein structure depend on it.
- **Positive feedback amplifies rather than opposes** and must terminate: childbirth, milk ejection, clotting, action potential, ovulation.
- **Set points can legitimately move** (circadian temperature, post-ovulation temperature, fever); **receptor adaptation** changes sensitivity only.
- **Failure modes map to components**: type 1 effector loss, type 2 effector resistance, SIADH a wrong centre output, tolerance receptor downregulation. Levers: **remove the disturbance, support the effector, repair the receptor arm.**

## Practice questions

**1. During a rapid haemorrhage arterial pressure falls. The afferent (input) pathway of the corrective reflex is**

A. Sympathetic fibres leaving the medulla to constrict arterioles
B. Release of antidiuretic hormone from the posterior pituitary
C. Increased contractility of the ventricular myocardium
D. Reduced baroreceptor firing in the carotid sinus and aortic arch, via nerves IX and X

**Answer: D**

Explanation: The afferent limb carries information *toward* the control centre — here the falling baroreceptor discharge travelling via nerves IX and X. A, B, and C are all efferent responses.

---

**2. Which statement best describes homeostasis?**

A. The internal environment is held absolutely constant
B. A dynamic steady state in which a variable is actively defended within a narrow range by negative feedback
C. The state a closed system reaches once all gradients have dissipated
D. The state of an ecosystem whose populations stop changing

**Answer: B**

Explanation: Homeostasis spends energy to hold a variable inside a defended band while it oscillates around the set point. C is thermodynamic equilibrium, which in an organism means death; D is an ecosystem's balance of flows, which defends no target.

---

**3. A patient with lobar pneumonia has a temperature of 39.5 °C and is shivering. The best explanation is**

A. Pyrogen-driven prostaglandin E₂ has raised the hypothalamic set point, and effectors work to reach it
B. The thermoregulatory centre has failed and generates heat randomly
C. The set point has been lowered, so heat escapes uncontrollably
D. The patient's thermoreceptors have been destroyed by the infection

**Answer: A**

Explanation: IL-1, IL-6, and TNF-α induce hypothalamic cyclo-oxygenase and PGE₂, so the controller now defends a higher value. Shivering is a correct response to a body still below that target — hence chills during a rising fever.

---

**4. In type 1 and type 2 diabetes mellitus respectively, the loop component that fails is**

A. Control centre and receptor
B. Afferent pathway and efferent pathway
C. Effector loss and effector resistance
D. Set point and control centre

**Answer: C**

Explanation: Type 1 follows autoimmune destruction of β cells, so the lowering signal — insulin — no longer exists. Type 2 retains secretion but target cells respond poorly, so the loop runs with reduced gain.

---

**5. Which of the following is positive feedback that must be terminated by an external event?**

A. Sweating when core temperature rises
B. The Ferguson reflex during labour
C. Baroreceptor-mediated slowing of the heart after a rise in pressure
D. Insulin release in response to a rise in blood glucose

**Answer: B**

Explanation: Cervical stretch triggers oxytocin, oxytocin triggers contraction, and contraction increases stretch — each cycle amplifies the last, so the loop ends only at delivery. The other three oppose their triggers and self-terminate.

---

**6. Which statement about hormonal control of blood glucose is correct?**

A. Insulin is the only hormone that lowers blood glucose, whereas many hormones raise it
B. Glucagon is the only hormone that lowers blood glucose
C. Insulin and glucagon act on the same receptor on the same cells
D. Glucose falls in fasting because insulin promotes glycogen breakdown

**Answer: A**

Explanation: Hypoglycaemia threatens the brain within minutes, so there is one dedicated reducer — insulin — against a committee of raisers. Glucagon raises glucose (B, D) and binds a different receptor (C).

---

**7. A patient develops a sudden severe metabolic acidosis. Which defence acts first?**

A. Renal excretion of hydrogen ions into the urine
B. Increased ventilation blowing off carbon dioxide
C. Chemical buffering of hydrogen ions by the bicarbonate buffer system
D. Aldosterone-mediated sodium reabsorption in the distal nephron

**Answer: C**

Explanation: Buffers act instantaneously with no receptor, centre, or energy cost, defending pH within seconds. Respiratory compensation follows in minutes; renal compensation, the only layer removing fixed acid, takes hours to days.

---

**8. Which correctly contrasts neural and endocrine control?**

A. Neural control is slower and longer-lasting; endocrine control faster and briefer
B. Endocrine signals cannot be regulated by negative feedback
C. Neural control is used only for conscious movements
D. Neural control is rapid, brief, and cell-specific; endocrine control is slower to start, broadcast in blood, and lasts until the hormone is degraded

**Answer: D**

Explanation: Neurotransmission works in milliseconds and stops when the neuron stops firing, whereas a hormone acts only on receptor-bearing cells until cleared. A reverses the two; B and C ignore hormonal loops and autonomic control.

---

**9. Which pair correctly identifies whether a set point has changed?**

A. Fever — receptor adaptation; post-ovulation rise in basal body temperature — set point changed
B. Fever — set point changed; post-ovulation rise in basal body temperature — set point changed
C. Habituation to a repeated sound — the set point for hearing has been lowered
D. Baroreceptor resetting in chronic hypertension — the medulla has deliberately raised its target

**Answer: B**

Explanation: Both are control-centre changes: pyrogen-induced PGE₂ raises the thermoregulatory target, and progesterone raises defended temperature after ovulation. Habituation changes reflex gain only, and baroreceptor resetting is receptor recalibration.

---

**10. A patient with type 2 diabetes is started on treatment that restores insulin sensitivity in liver and muscle. In control-loop terms this is**

A. Removing the disturbance
B. Replacing a missing effector signal
C. Repairing the receptor/response arm so the signal regains its effect
D. Deliberately resetting the set point for blood glucose

**Answer: C**

Explanation: In type 2 diabetes the signal is present but target cells respond poorly, so the lever is restoring gain at the response arm. B is the type 1 strategy, A would remove the glucose load, and D would be a target change like fever.
