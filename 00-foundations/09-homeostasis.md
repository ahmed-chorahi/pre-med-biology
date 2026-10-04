# Homeostasis

## Core idea

A living thing is constantly being pushed away from its internal set points — by temperature, by what it eats, by exertion, by infection — and is constantly correcting. **Homeostasis is that continuous correcting.** It is not a property of an organ or a system; it is the organising principle of the whole organism, and nearly every system in [10 — Anatomy and Physiology](../10-anatomy-and-physiology/) exists to serve it.

> This chapter introduces the concept and its vocabulary. The full control loop with worked case studies on blood glucose, body temperature, and water balance is in 09-human-biology/03-homeostasis.md.

## The internal environment

The **internal environment** is the extracellular fluid — the plasma and interstitial fluid that bathes every cell. Cells do not reach the outside world directly; they are surrounded by this fluid, and everything they need must pass through it.

```
OUTSIDE WORLD
     ↓ food, O₂, water, temperature, pathogens
┌─────────────────────────────────┐
│  INTERNAL ENVIRONMENT           │  ← the compartment homeostasis defends
│    plasma + interstitial fluid  │
└─────────────────────────────────┘
     ↓ nutrients, O₂, hormones, waste
   INDIVIDUAL CELLS
```

This arrangement is why homeostasis is centralised. Every cell depends on the internal environment staying within narrow limits, and the internal environment is shared — so it must be regulated for the benefit of all cells simultaneously.

## What is regulated, and how tightly

| Variable | Normal range | Main controller |
| --- | --- | --- |
| Body temperature | ~37 °C (± 0.5 °C daily) | Hypothalamus |
| Blood glucose | ~70–110 mg/dL (fasting) | Pancreas — insulin and glucagon |
| pH (arterial blood) | 7.35–7.45 | Respiratory and renal control |
| Blood pressure | ~120/80 mmHg | Heart, blood vessels, kidneys |
| Water balance | Plasma osmolality within ~1% of normal | Hypothalamus, kidneys, thirst |
| Oxygen saturation | ~95–100% | Lungs, ventilation rate |

Read the "how tightly" column. These are not approximate targets. Body temperature varies by only about half a degree across a healthy day despite large changes in ambient temperature and activity. Plasma osmolality is defended to within about 1%. **Tightness is the point.**

## Feedback: the general principle

A **feedback loop** is a regulatory process in which the output of the process modifies the input.

### Negative feedback

**Negative feedback opposes the change and drives the variable back toward its set point.** It is the dominant mechanism of homeostasis, and it stabilises; it resists deviation.

```
VALUE DEVIATES FROM SET POINT
   ↓
RECEPTOR DETECTS THE DEVIATION
   ↓
CONTROL CENTRE COMPARES AGAINST SET POINT
   ↓
EFFECTOR ACTS TO OPPOSE THE CHANGE
   ↓
VALUE RETURNS TOWARD SET POINT
   ↓
SIGNAL TO THE CONTROL CENTRE DECREASES
```

This is why negative feedback is the mechanism of stability. Any initial deviation produces a response proportional to the size of the deviation, and that response reduces the deviation — which reduces the response. The system settles.

**The key insight, and it is often missed:** the stimulus is not the thing that is removed. The *deviation from set point* is removed. The variable does not return to zero; it returns to normal.

### Positive feedback

**Positive feedback amplifies the change.** It is not a homeostatic mechanism — it takes the system further from its starting point. It is used when amplification is the point.

| Example | Mechanism |
| --- | --- |
| **Childbirth** | Cervical stretch → oxytocin release → stronger contraction → more stretch → more oxytocin |
| **Blood clotting** | Damaged tissue → platelets adhere → release signals → more platelets adhere |
| **Action potential** | Na⁺ influx → depolarisation → more voltage-gated Na⁺ channels open → more Na⁺ influx |
| **Ovulation** | Rising estrogen → positive feedback on the pituitary → LH surge → ovulation |

The two childbirth mechanisms are worth contrasting directly, because they use the same hormone:

```
BIRTHING
   cervical stretch → oxytocin → contraction → MORE stretch → MORE oxytocin
                                                        ↑                    ↓
                                                    AMPLIFIED        ends only when
                                                                    the baby is delivered

FEEDBACK LOOP THAT TERMINATES
   high blood glucose → insulin → cells take up glucose → blood glucose FALLS
                                                 ↑                        ↓
                                          STIMULUS REMOVED
```

Positive feedback is self-terminating only because the thing that started it eventually stops happening. That is why it is used in childbirth and ovulation and almost nowhere else in routine regulation.

## Why a set point is a range, not a number

Two refinements that matter clinically.

**Negative feedback does not eliminate variation; it bounds it.** Control systems have sensitivity, and some noise remains around the target. So the normal state is a narrow range, not a single value.

**There are coordinated set points for several variables at once.** Blood volume, blood pressure, and sodium concentration are linked: they are three views of the same fluid and electrolyte state. This is why a disturbance in one shows up in the others, and why clinical reasoning about them has to consider them together.

## Homeostasis as a life characteristic

From [01 — Characteristics of life](01-characteristics-of-life.md), homeostasis is one of the defining properties of living things. It is worth being precise about why, because the connection to the rest of that list is not accidental.

A living thing is an **open system** that maintains internal order by spending energy. A crystal is also ordered, but nothing in it measures anything or corrects anything — its "order" is imposed by the environment, and if the environment changes, the crystal changes with it. A living thing instead actively maintains conditions that are *not* imposed from outside.

That distinction is the whole content of the word **homeostasis** — from *homeo* (same) and *stasis* (standing): **standing still**. Not literally still. Actively held.

## Medical relevance

**Vital signs are homeostasis being reported on.** Temperature, pulse, blood pressure, respiratory rate, oxygen saturation, and blood glucose are all measurements of controlled variables. This is why they are recorded in that particular order in every clinical assessment — the reasoning is to identify, as quickly as possible, which control system has stopped coping.

**Every illness is a disturbance of, or an attempt to work around, a control system.** This framing covers more than seems obvious:

| Problem | Homeostatic disturbance |
| --- | --- |
| Fever | Temperature set point is deliberately raised by infection-driven signals |
| Hypothermia | Heat-loss defence overwhelmed |
| Diabetes mellitus | Blood glucose control system fails — see the case study below |
| Dehydration | Water balance: intake cannot match loss |
| Hypertension | Blood pressure regulation fails |
| Respiratory acidosis | CO₂ elimination fails → pH falls |
| Heart failure | Cardiac output falls → blood pressure falls → fluid leaves vessels |
| Vertigo | Balance and postural control, a sensory-motor feedback loop, misfires |

**When compensation works, the patient looks well.** This is clinically important. In early heart failure, cardiac output falls, the kidneys retain sodium and water, and blood volume rises to restore blood pressure. The patient has oedema and fatigue but may not yet be markedly unwell — because homeostasis is holding a normal-looking blood pressure. It is also why blood pressure can look normal while the heart is failing. Compensation is protective and it is also how disease advances before decompensation.

**Decompensation is what the emergency is.** When the compensating mechanisms can no longer cope, values move quickly and in parallel, and the patient becomes acutely unwell. Any severe illness eventually ends in loss of compensation.

**Fever is a defended set point, not a broken thermometer.** In infection, pyrogens raise the hypothalamic set point. The patient is not malfunctioning — the control centre has deliberately moved its target, and shivering and vasoconstriction are the system working to reach the new target. This explains both the shivering and the chills. The distinction matters: the problem is not that the system has failed, but that the target has moved.

## Key facts

- The **internal environment** is the extracellular fluid that bathes every cell — plasma plus interstitial fluid.
- **Negative feedback** opposes a deviation and returns the variable toward its set point; it is the mechanism of stability.
- **Positive feedback** amplifies a change; it is used for childbirth, clotting, action potentials, and ovulation — not for regulation.
- A **feedback loop** is: change → receptor → control centre → effector → response → homeostasis.
- Negative feedback removes the **deviation**, not the stimulus.
- The **Bohr effect** (pH alters haemoglobin's oxygen affinity) is an example of a physical property serving homeostasis — see [06 — Acids, bases, and pH](06-acids-bases-and-ph.md).
- Vital signs are controlled variables. Compensation keeps patients looking well; decompensation is the emergency.
- A **fever** is a raised set point, not a failure of the control system.

## Practice questions

**1. A patient's blood glucose rises after a meal. The response that lowers it back toward normal is an example of**

A. A reflex arc
B. Negative feedback, because the response opposes the change
C. Positive feedback, because glucose is being produced
D. Exocytosis

**Answer: B**

Explanation: Insulin release raises cellular glucose uptake and storage, which lowers blood glucose — that is, it opposes the initial deviation and returns the variable to its set point. Positive feedback would amplify the rise, which is exactly what C claims. A is a different mechanism class — a reflex arc is a nerve-mediated response, not a loop that opposes a deviation from a set point. D describes a transport process, not a regulatory one.

---

**2. During childbirth, oxytocin release causes uterine contraction, which increases cervical stretch, which triggers further oxytocin release. This is**

A. Negative feedback
B. Homeostatic regulation
C. Thermoregulation
D. Positive feedback

**Answer: D**

Explanation: Each round amplifies the previous one, so the loop is positive. It terminates not because feedback reverses it, but because the stimulus ends when the baby is delivered. Homeostasis, by contrast, is regulation toward a set point, which is negative feedback by definition. C is unrelated.

---

**3. Which of the following variables is regulated over the narrowest range?**

A. Blood pressure
B. Blood glucose
C. Body temperature
D. Body mass

**Answer: C**

Explanation: Body temperature varies by only about half a degree Celsius across a normal day despite substantial variation in ambient temperature, activity, and metabolic rate. Blood glucose varies over a wider range around meals, blood pressure varies considerably with posture and exertion, and body mass changes slowly and is not held to a narrow physiological range. Narrowness of the defended range is the measure of how tightly a variable is regulated.

---

**4. A patient has a body temperature of 39 °C and is shivering. Which interpretation is correct?**

A. The set point has been raised by infection-driven signals, and the shivering is the system working to reach it
B. The temperature control system has failed and is generating heat randomly
C. Shivering indicates the set point has been lowered
D. The patient is too far from the environment

**Answer: A**

Explanation: In fever, pyrogens raise the hypothalamic set point. The control centre is functioning correctly; shivering and vasoconstriction are the effectors working to bring the temperature up to the new target. That is why the chills of a rising fever occur. The response being directed at a higher rather than lower target is the defining feature.

---

**5. In the early stage of heart failure, blood pressure remains near normal because the kidneys retain sodium and water. This is best described as**

A. Negative feedback that has become positive
B. Full recovery, because the blood pressure is normal
C. Compensation that masks the severity of the underlying problem
D. A failure of the kidneys

**Answer: C**

Explanation: Retaining sodium and water increases blood volume, which restores cardiac output and blood pressure — a negative feedback response working correctly. But the underlying cardiac problem persists and the fluid retention produces oedema. Compensation is protective and it also delays recognition, which is why patients can deteriorate substantially before the blood pressure changes. A is wrong because a normal reading does not mean the heart is working. D is wrong; the loop remains negative.

---

**6. Which statement best describes the internal environment?**

A. The fluid within the nucleus
B. The extracellular fluid surrounding cells, including plasma and interstitial fluid
C. The cytoplasm inside each individual cell
D. The contents of the digestive tract

**Answer: B**

Explanation: The internal environment is the extracellular fluid that bathes every cell — plasma and interstitial fluid together. Cells do not contact the external world directly; all exchange happens through this compartment, which is why it must be regulated for the benefit of all cells at once. A, C, and D are separate compartments, and D is outside the body rather than internal to it.

---

**7. A feedback loop is operating such that the response intensifies the original stimulus. What kind of loop is this, and where is it useful?**

A. Positive feedback — amplifying a process that must reach a threshold
B. Negative feedback — preventing overshoot
C. Negative feedback — restoring equilibrium
D. Positive feedback — restoring a set point

**Answer: A**

Explanation: When the response amplifies the stimulus, the loop is positive. It is used where amplification is required: platelet plug formation, the action potential, the LH surge for ovulation, and the contractions of labour. Restoring a set point requires negative feedback by definition, which is what rules out D.

---

**8. Why is the term 'homeostasis' more accurate for body temperature than for body mass?**

A. Body temperature is more important than body mass
B. Body temperature is corrected by active regulatory responses toward a narrow range, whereas body mass changes slowly and is not regulated to a narrow range
C. Body mass is regulated by negative feedback
D. Body mass is not a physiological variable

**Answer: B**

Explanation: Homeostasis means actively maintaining a condition within limits. Temperature regulation involves detection, comparison against a set point, and effector action, all within about half a degree. Body mass changes over months and no system corrects it back toward a target — which is why the term applies unevenly across physiological variables. A and D are incorrect.

---

**9. A patient's arterial pH falls to 7.25. Which system is most directly responsible for correcting this, and how?**

A. The heart, by increasing cardiac output
B. The lungs, by reducing ventilation
C. The stomach, by secreting acid
D. The lungs, by increasing ventilation to remove CO₂ and lower carbonic acid

**Answer: D**

Explanation: The dominant buffer system is bicarbonate/carbonic acid, and CO₂ is linked to it by $\mathrm{H^+ + HCO_3^- \rightleftharpoons H_2CO_3 \rightleftharpoons CO_2 + H_2O}$. Removing CO₂ pulls the equilibrium left, consuming hydrogen ions and raising pH. Increasing ventilation does this. Reducing ventilation would raise CO₂ and worsen the acidosis. The kidneys contribute over hours to days by excreting acid and reclaiming bicarbonate.

---

**10. Which scenario best illustrates that compensation can be protective in the short term but harmful in the long term?**

A. Persistent fluid retention maintaining blood pressure while worsening congestion
B. Shivering generating heat during exposure to cold
C. Increased ventilation removing CO₂ during vigorous exercise
D. A fever that abates as the infecting organism is cleared

**Answer: A**

Explanation: Retaining fluid is a correct response to reduced cardiac output, and it preserves blood pressure and organ perfusion. Sustained, however, it produces oedema and pulmonary congestion, and the increased volume increases the workload on the failing heart. C and D are adaptive responses that end when the stimulus ends. B is a resolution of a cause rather than compensation for it.