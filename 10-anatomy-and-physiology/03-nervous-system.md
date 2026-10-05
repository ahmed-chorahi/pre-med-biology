# The Nervous System

## Why it matters

The nervous system is the body's **fast control arm**: a withdrawal reflex completes in under 50 milliseconds while a hormone needs seconds to minutes. That is the neural-versus-endocrine contrast in [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md): neural control is rapid, brief, point-to-point; endocrine control is slower, broadcast, sustained.

Speed has a physical basis: **every nervous signal is ion movement across a membrane you already understand** — a potassium leak ([02 — Passive transport](../03-cellular-processes/02-passive-transport.md)), gradients made by the Na⁺/K⁺ pump ([03 — Active transport](../03-cellular-processes/03-active-transport.md)), and exocytosis at the synapse. The **action potential is the mechanism**; reflexes, sensation, thought, and movement are architecture built on it, developed here as **structure → function → mechanism → regulation → homeostasis**.

## Organisation: central, peripheral, and autonomic

| Division | Structures | Job |
| --- | --- | --- |
| **Central nervous system** | Brain and spinal cord | Integration: receive, compare, decide, command |
| **Peripheral — somatic** | Nerves to skin and muscle | Sensation; **voluntary** movement |
| **Peripheral — autonomic** | Visceral motor nerves and ganglia | **Involuntary** cardiac muscle, smooth muscle, glands |
| — sympathetic / parasympathetic | Thoracolumbar / craniosacral outflow | Fight or flight / rest and digest |
| — enteric | Plexuses in the gut wall | Local gut reflexes, partly independent |

**Afferent** fibres carry information **toward** the CNS, **efferent** fibres carry commands **away** — the a/e convention of [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md).

### Meninges, cerebrospinal fluid, and the blood–brain barrier

| Structure | What it is | Function |
| --- | --- | --- |
| **Dura mater** | Tough fibrous outer meninx | Protection; dural venous sinuses |
| **Arachnoid mater** | Middle layer over the subarachnoid space | Holds CSF; granulations absorb it |
| **Pia mater** | Delicate layer on cord and brain | Follows folds; carries vessels |
| **CSF** | ~150 mL, made by the **choroid plexus** | Buoyancy, cushioning, stable chemical bath |
| **Blood–brain barrier** | Endothelial cells sealed by **tight junctions** | Chemical isolation of the brain |

CSF is an ultrafiltrate of plasma with more Na⁺ and Cl⁻ and far less protein, so the brain floats in a controlled bath; added volume inside the rigid skull raises intracranial pressure.

**The barrier is a lipid-membership test.** With the paracellular route sealed, a molecule reaches the brain only by crossing the endothelial membrane, so it must be **lipophilic** (or use a transporter, as glucose does via GLUT1) — the fluid mosaic of [01 — Membrane structure and the fluid mosaic model](../03-cellular-processes/01-membrane-structure-and-fluid-mosaic.md) applied to drug design. Lipophilic molecules act centrally; polar ionised ones (penicillin G, dopamine) are excluded.

## Neuron structure → function

| Part | Structure | Function |
| --- | --- | --- |
| **Dendrites** | Branching extensions, often spiny | **Input** — receive transmitter, generate graded potentials |
| **Cell body (soma)** | Nucleus and organelles | Metabolic centre; integrates inputs |
| **Axon hillock** | Cone where soma meets axon | Densest voltage-gated Na⁺ channels — **the decision point** |
| **Axon** | Single long process | **Output** — carries the action potential |
| **Terminals** | Knobs holding vesicles | Release neurotransmitter |
| **Schwann cell** (PNS) | One cell wraps one segment | PNS myelin; re-myelinates after injury |
| **Oligodendrocyte** (CNS) | One cell wraps many segments | CNS myelin; poor regeneration |

That ratio is clinical: the PNS is repaired by Schwann cells, the CNS largely cannot — why multiple sclerosis never fully remits.

### Myelin, nodes of Ranvier, and conduction speed

**Myelin** is a lipid-rich spiral wrap interrupted every ~1 µm by **nodes of Ranvier**, where the membrane is bare and packed with voltage-gated Na⁺ channels.

```
unmyelinated:  AP regenerated at EVERY point; current leaks out
               continuously → slow CONTINUOUS conduction

myelinated:    [myelin]  node  [myelin]  node  [myelin]
               current flows INSIDE the axoplasm with almost no loss
               → AP regenerated only AT THE NODES → SALTATORY conduction
```

Myelin **raises membrane resistance** and **lowers capacitance**, so local current reaches the next node intact — cable physics, not "insulation speeding up electricity".

| Factor | Effect on conduction velocity |
| --- | --- |
| **Myelin** | Up to ~100× faster than unmyelinated |
| **Axon diameter** | Bigger is faster — a wider lumen has lower internal resistance |
| **Temperature** | Faster warm, slower cold (cold extremities tingle) |
| **Node/channel density** | More Na⁺ channels per node → faster regeneration |

## The resting membrane potential

Every neuron sits at a voltage: the **resting membrane potential** of a typical neuron is about **−70 mV**, inside negative relative to outside.

| Ion | Inside / outside | Permeability at rest | Nernst equilibrium potential |
| --- | --- | --- | --- |
| **K⁺** | 140 / 4 mmol/L | **High** — many K⁺ leak channels | **≈ −90 mV** |
| **Na⁺** | 15 / 145 mmol/L | Very few open channels | ≈ +60 mV |
| **Cl⁻** | Low / 110 mmol/L | Low–moderate | ≈ −70 mV |
| **Protein⁻** | High / negligible | Cannot cross | Not applicable |

```
K⁺ LEAKS OUT down its gradient through open K⁺ leak channels
        ↓
net positive charge leaves → the inside becomes NEGATIVE
        ↓
electrical pull back IN grows until it balances the chemical push OUT
        ↓
the membrane would settle at E_K ≈ −90 mV, EXCEPT the small Na⁺ leak
drags it slightly positive
        ↓
Na⁺/K⁺-ATPase: 3 Na⁺ OUT : 2 K⁺ IN per ATP restores gradients continuously
        ↓
STEADY STATE at ≈ −70 mV — energy-dependent, not equilibrium
```

**Two equations, one idea.** The **Nernst equation** balances *one* ion's gradient; the **Goldman–Hodgkin–Katz equation** weights each ion by its **relative permeability**. Because resting membranes are far more permeable to K⁺ than to anything else, the answer lands near E_K: **−70 mV**.

**The pump is not the battery.** It contributes only a few millivolts directly; its job is housekeeping — bailing out the Na⁺ that leaks in and the K⁺ that leaks out. Block it with ouabain or anoxia and the potential decays in seconds: −70 mV is held by continuous ATP expenditure, a defended deviation from equilibrium as defined in [09 — Homeostasis](../00-foundations/09-homeostasis.md).

## The action potential

The **action potential (AP)** is a 1–2 ms, self-propagating reversal of membrane voltage: positive feedback with two inbuilt off-switches.

```
STIMULUS → graded depolarisation reaches the AXON HILLOCK
        ↓
THRESHOLD ≈ −55 mV
        ↓  positive feedback: Na⁺ in → depolarise → more Na⁺ channels open
VOLTAGE-GATED Na⁺ CHANNELS OPEN (activation gates)
        ↓
RAPID DEPOLARISATION toward ≈ +30 mV (Na⁺ rushes in down its gradient)
        ↓  OFF-SWITCH 1: Na⁺ INACTIVATION gates shut (ball-and-chain)
        ↓  OFF-SWITCH 2: voltage-gated K⁺ channels (slowly) open
K⁺ leaves down its gradient → REPOLARISATION
        ↓
HYPERPOLARISATION to ≈ −80 mV — K⁺ channels close slowly
        ↓
leak channels dominate; Na⁺/K⁺-ATPase restores the gradients
        ↓
RESTING POTENTIAL −70 mV RESTORED — ready for the next event
```

| Phase | Channel state | Ion movement | Voltage |
| --- | --- | --- | --- |
| **Threshold** | Enough Na⁺ open to become self-sustaining | Net Na⁺ in | **−55 mV** |
| **Depolarisation** | Na⁺ activation gates **open** | **Na⁺ in** | → **≈ +30 mV** |
| **Repolarisation** | Na⁺ inactivation **shut**; K⁺ **open** | **K⁺ out** | → back down |
| **Hyperpolarisation** | K⁺ slow to close | K⁺ still out | ≈ −80 mV |
| **Restored** | K⁺ closes; Na⁺ gates reset | Pump restores gradients | −70 mV |

**Why all-or-none.** Below threshold too few Na⁺ channels open for depolarisation to outrun the K⁺ leak, so the event dies; above threshold the regenerative loop runs to completion and amplitude is fixed by **channel density and gradient size** — a pinprick and a crush give identical spikes. Intensity is coded by **frequency coding** (more spikes per second) and **recruitment** (more fibres), never by amplitude.

**Why refractory periods enforce one-way travel.** In the **absolute refractory period** every Na⁺ channel is inactivated, so that segment cannot refire at all; in the **relative refractory period** K⁺ conductance is still high, so only an unusually large depolarisation will fire.

```
AP travelling right →→→   [REFRACTORY behind]   [RESTING ahead]
                          cannot refire          can be brought to threshold
        → the impulse has ONLY ONE WAY TO GO, and a maximum firing rate
```

Unmyelinated **C fibres** (0.5–2 m/s) carry dull pain and temperature; thick myelinated **Aα fibres** (80–120 m/s) carry touch, proprioception, and motor output.

## Synaptic transmission

```
ACTION POTENTIAL arrives at the AXON TERMINAL
        ↓
VOLTAGE-GATED Ca²⁺ CHANNELS open → Ca²⁺ rushes in
        ↓
Ca²⁺ binds synaptotagmin → SNARE complex zips (synaptobrevin with syntaxin + SNAP-25)
        ↓
VESICLE FUSES with the presynaptic membrane → EXOCYTOSIS
        ↓
NEUROTRANSMITTER diffuses across the ~20–40 nm cleft → binds RECEPTORS
        ↓
IONOTROPIC → fast postsynaptic potential (ms)
METABOTROPIC → G-protein → second messenger (seconds–minutes)
        ↓
EPSP or IPSP → SUMMATION at the trigger zone
        ↓
threshold?  YES → new action potential   NO → signal ends
```

**Calcium is the obligatory trigger**: remove extracellular Ca²⁺ and the terminal still depolarises but releases nothing. The SNARE machinery is the fusion machine of [03 — Active transport](../03-cellular-processes/03-active-transport.md), which botulinum and tetanus toxins cut.

| Transmitter | Role | Receptor family |
| --- | --- | --- |
| **Acetylcholine** | Neuromuscular junction, ganglia, parasympathetic | Nicotinic (ionotropic), muscarinic (metabotropic) |
| **Noradrenaline** | Sympathetic endings; excites heart and vessels | α and β adrenergic |
| **Dopamine** | Substantia nigra; movement, reward | D1–D5 |
| **Glutamate** | The brain's main **excitatory** transmitter | AMPA, NMDA (ionotropic), mGluR |
| **GABA** | The brain's main **inhibitory** transmitter | GABA_A (Cl⁻), GABA_B |
| **Serotonin** | Raphe nuclei, gut; mood, sleep | 5-HT families |
| **Endorphins** | Hypothalamus, pituitary; analgesia | μ, κ, δ opioid |

| | **Ionotropic** | **Metabotropic** |
| --- | --- | --- |
| Structure | Receptor *is* an ion channel | Receptor + G-protein + effector enzyme |
| Speed | **Milliseconds**, direct | **Seconds to minutes**, via second messengers |
| Second messenger | None | **cAMP** (from ATP — [04 — ATP and metabolism](../03-cellular-processes/04-atp-and-metabolism.md)), IP₃, DAG, Ca²⁺ |
| Long-term effect | None directly | Can reach the nucleus and alter transcription ([06 — Gene regulation](../05-molecular-biology/06-gene-regulation.md)) |
| Examples | Nicotinic ACh, GABA_A, AMPA, glycine | Muscarinic, adrenergic, GABA_B, opioid, dopamine |

**The receptor, not the transmitter, decides the effect** — ACh is excitatory at nicotinic receptors on muscle yet inhibitory at M2 receptors on the heart, which is why receptor-selective drugs exist.

Synaptic potentials are **graded**, so they are summed: **temporal summation** adds inputs from **one** terminal in quick succession; **spatial summation** adds inputs from several terminals active **at the same moment**, and the axon hillock reads the total. **Shunting inhibition** deserves its own line: opening Cl⁻ channels holds the membrane near E_Cl so incoming excitation leaks away, inhibiting **without visible hyperpolarisation**.

### Signal termination

Signals end by **reuptake** — SSRIs block serotonin reuptake, **cocaine** blocks dopamine reuptake — by **enzymatic degradation** in the cleft (acetylcholinesterase, MAO; **anticholinesterases** treat myasthenia), or by **diffusion and glial uptake** (impaired clearance → excitotoxicity).

## The reflex arc

A **reflex** is an involuntary, stereotyped response organised in the spinal cord or brainstem and completed **before** the sensation reaches consciousness. Each synapse adds ~0.5 ms; a cortical round trip would cost a hand on a hot plate.

```
RECEPTOR (detects the stimulus — e.g. nociceptor in skin)
        ↓  stimulus → receptor potential → AP
SENSORY (AFFERENT) NEURON → enters cord via the DORSAL root
        ↓
INTERNEURON in grey matter (integrator; ABSENT in monosynaptic reflexes)
        ↓
MOTOR (EFFERENT) NEURON → leaves via the VENTRAL root
        ↓
EFFECTOR (muscle contracts) → RESPONSE reduces the stimulus → loop ends
```

Reflexes *bypass* the brain for speed — one to three synapses and tens of milliseconds — but descending pathways still set their gain: an upper motor neuron lesion makes reflexes pathologically brisk.

| | **Withdrawal (flexor)** | **Stretch (myotatic)** |
| --- | --- | --- |
| Stimulus and receptor | Nociception; nociceptor in skin | Sudden muscle stretch; **muscle spindle** |
| Synapses | **Polysynaptic** (interneuron present) | **Monosynaptic** (sensory meets motor directly) |
| Effector | Flexors of the same limb contract | **Same** muscle contracts — stretch opposed |
| Extra effect | **Crossed extensor reflex** in the opposite limb | **Reciprocal inhibition** of the antagonist |
| Function | Remove the limb from danger | Maintain posture; basis of the knee-jerk |

The stretch reflex is negative feedback in exactly the terms of [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md): stretch is the stimulus, the spindle the receptor, the afferent the input, the motor neuron the control centre, the muscle the effector, and contraction the response that removes the stretch. Reflex testing localises lesions: an **absent** reflex means the arc (root, ganglion, synapse, motor neuron, muscle) is broken; a **brisk** one means lost descending inhibition. **Gamma motor neurons** keep the spindle taut as the muscle shortens, without which the reflex vanishes during movement.

## The autonomic nervous system

The **autonomic nervous system (ANS)** supplies cardiac muscle, smooth muscle, and glands — the effectors of most involuntary control loops — with two usually **dual-innervated**, opposed divisions.

| Feature | **Sympathetic** | **Parasympathetic** |
| --- | --- | --- |
| Slogan | **Fight or flight** | **Rest and digest** |
| CNS origin | **T1–L2** (thoracolumbar) | **III, VII, IX, X** + **S2–S4** (craniosacral) |
| Ganglia | Near the cord — short pre-, long postganglionic | At the effector — long pre-, short postganglionic |
| Preganglionic transmitter | **Acetylcholine** | **Acetylcholine** |
| Postganglionic transmitter | **Noradrenaline** (ACh at sweat glands) | **Acetylcholine** |
| Postganglionic receptors | **Adrenergic α₁, α₂, β₁, β₂, β₃** | **Muscarinic M₁–M₅**; nicotinic at ganglia |
| Pupil, bronchi | **Dilate** | Constrict |
| Heart | **↑ rate, contractility, conduction** | **↓ rate, conduction** |
| Gut, bladder | **↓ motility**, sphincters hold urine | **↑ motility and secretion**, bladder voids |

### Receptor pharmacology

| Receptor | Type | Effect of activation |
| --- | --- | --- |
| **α₁** | Gq | Vasoconstriction, mydriasis, sphincter contraction |
| **α₂** | Gi, **presynaptic autoreceptor** | **↓ noradrenaline release** — negative feedback (clonidine) |
| **β₁** | Gs | ↑ heart rate, contractility, renin (**β-blockers** block it) |
| **β₂** | Gs | Bronchodilation, vasodilation, glycogenolysis (**salbutamol**) |
| **M₂ / M₃** | Gi / Gq | ↓ heart rate / smooth muscle contraction and secretion |
| **Nicotinic Nₘ / Nₙ** | Ionotropic, cation | Muscle end-plate potential / ganglionic transmission |

The adrenal medulla *is* a modified sympathetic ganglion, so circulating adrenaline still counts as sympathetic; and sympathetic sweat fibres are **cholinergic** — sweating is sympathetic in wiring, not chemistry.

### Dual innervation as a homeostatic mechanism

Most visceral organs receive both divisions with opposed effects — the neural arm of the effector stage in [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md). Two opposed nerves buy **graded control from two directions**, **rapid reciprocal switching**, and a **fail-safe** — loss of one arm leaves basal tone from the other.

```
DISTURBANCE (haemorrhage → arterial pressure falls)
        ↓
baroreceptors fire less → MEDULLA
        ↓
SYMPATHETIC ↑   and   PARASYMPATHETIC ↓   ← reciprocal, simultaneous
        ↓                                 ↓
heart rate ↑, vasoconstriction      vagal withdrawal adds rate
        ↓
pressure restored → baroreceptors fire again → BOTH outputs fall
```

Control rests on the **ratio** between the divisions, not an on/off switch; autonomic neuropathy removes both arms, leaving a heart rate that cannot correct. The **enteric nervous system** — ~100–500 million neurons in the gut's plexuses — performs peristalsis and secretion even in isolated gut, which sympathetic input inhibits and vagal input stimulates.

## The brain in functional regions

| Region | Function | Signature of damage |
| --- | --- | --- |
| **Medulla oblongata** | **Cardiovascular centre** (HR, vessel tone), **respiratory rhythm**; swallowing | Loss → respiratory and cardiac arrest |
| **Pons** | Relay; pneumotaxic centre fine-tunes breathing | Altered breathing pattern |
| **Cerebellum** | **Coordination**, balance, motor timing, posture | **Ataxia**, intention tremor, dysmetria |
| **Hypothalamus** | **Homeostatic control centre** — temperature, thirst, hunger, osmolarity, circadian rhythm | Diabetes insipidus, hyperthermia |
| **Thalamus** | **Sensory relay** for every sense except smell; gates cortex | Contralateral sensory loss |
| **Cerebrum / cortex** | Voluntary movement (precentral), sensation (postcentral), language, **association areas** | Contralateral deficit; aphasia |
| **Basal ganglia** | **Movement planning** and initiation, habit (striatum, globus pallidus, substantia nigra) | **Parkinson's** (too little movement); Huntington's (too much) |

The **hypothalamus** is where the nervous system becomes a control centre: it compares temperature, osmolarity, and hormones with defended values and outputs through the autonomic system (fast) and the pituitary (slow) — the neural half of the loop in [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md). The brain has **grey matter outside, white matter inside**; the spinal cord is the reverse.

### Spinal cord tracts

| Tract type | Direction | Fasciculus | Carries |
| --- | --- | --- | --- |
| **Ascending (sensory)** | ↑ to brain | **Dorsal columns** → medial lemniscus | Fine touch, vibration, conscious proprioception |
| | | **Spinothalamic** | Pain, temperature, crude touch |
| | | **Spinocerebellar** | Unconscious proprioception to the cerebellum |
| **Descending (motor)** | ↓ from brain | **Lateral corticospinal** | Voluntary, fractionated movement |
| | | Vestibulo-, reticulo-, rubrospinal | Posture, balance, gross movement, tone |

Localisation follows anatomy: spinothalamic fibres **cross in the cord**, dorsal column fibres **cross in the medulla**, so a one-sided cord lesion splits — pain and temperature lost on the *opposite* side, vibration and proprioception on the *same* side.

## Sensory reception

All sensation follows **detect → convert → encode**: **sensory transduction** turns the stimulus into a graded receptor potential, then into spikes.

```
STIMULUS → RECEPTOR channel/protein responds → RECEPTOR POTENTIAL
        ↓  threshold reached at the first node?
ACTION POTENTIALS → frequency + recruited fibres encode intensity
```

| Modality | Receptor | Stimulus | Transduction event |
| --- | --- | --- | --- |
| **Mechanoreceptor** | Pacinian, Meissner, Merkel, spindle | Pressure, vibration, stretch | Mechanically gated cation channels opened by deformation |
| **Photoreceptor** | Rods and cones | Photons | 11-*cis*-retinal isomerises → transducin → PDE → **cGMP falls, channels close** |
| **Chemoreceptor** | Taste buds, olfactory neurons, carotid bodies | Molecules | Ion channels or GPCRs bound by the ligand |
| **Thermoreceptor** | Warm and cold endings | Temperature | **TRP channels** with different thresholds |
| **Nociceptor** | Free nerve endings (Aδ, C) | Damage, extreme heat, acid | **TRPV1** and acid-sensing channels opened by H⁺ and capsaicin |

**Adaptation** is a fall in response to a *sustained* stimulus — a change **at the receptor**, not a changed set point, in the terms of [03 — Homeostasis control loop](../09-human-biology/03-homeostasis-control-loop.md). **Tonic** receptors (Merkel, muscle spindle) fire throughout a stimulus and report sustained state; **phasic** receptors (Pacinian corpuscle, olfactory neurons) fire at onset and offset and report *change*.

### Worked example: the eye

```
LIGHT → cornea → aqueous humour → LENS (accommodates) → vitreous → RETINA
        ↓ photon hits 11-cis-retinal in rhodopsin
transducin → phosphodiesterase → cGMP HYDROLYSED → cGMP falls
        ↓
Na⁺/Ca²⁺ channels in the outer segment CLOSE → cell HYPERPOLARISES
        ↓
glutamate release DECREASES → bipolar cells → ganglion cells → OPTIC NERVE
```

The photoreceptor **hyperpolarises to its stimulus** — light closes channels rather than opening them.

### Worked example: the ear

```
SOUND → pinna → ear canal → TYMPANIC MEMBRANE vibrates
        ↓ malleus → incus → stapes → OVAL WINDOW (amplified by area reduction)
fluid wave along the BASILAR MEMBRANE (base = high pitch, apex = low)
        ↓
STEROCILIA bend toward the tallest row → tip links pull channels OPEN
        ↓
K⁺ from endolymph (+80 mV) enters → hair cell DEPOLARISES → Ca²⁺ in
        ↓
GLUTAMATE release → cochlear nerve → brainstem → thalamus → auditory cortex
```

The ossicles solve the **impedance mismatch** between air and cochlear fluid — hence conductive hearing loss with middle-ear fluid — and the hair cell is a pure **mechanoreceptor**: deflection opens its channel directly.

## Medical relevance

**Multiple sclerosis is autoimmune demyelination of the CNS.** Plaques destroy myelin, so conduction slows and, in severe segments, is **blocked**. Symptoms worsen with heat or exercise (**Uhthoff's phenomenon**).

**Stroke is time-critical because neurons die without ATP.** **Ischaemic stroke** (~85%) is an occluded vessel; **haemorrhagic stroke** is a ruptured one. In ischaemia the pump fails within minutes, Na⁺ and water enter, the cell swells (**cytotoxic oedema**), and glutamate kills the salvageable **penumbra** — hence thrombolysis windows in hours.

**Diabetic peripheral neuropathy** follows chronic hyperglycaemia through polyol-pathway and glycation damage to the **vasa nervorum**. The longest fibres fail first: vibration and proprioception are lost before pain in a **glove-and-stocking** pattern.

**Myasthenia gravis is a postsynaptic failure of the signal to muscle** — see [02 — Muscular system](02-muscular-system.md): autoantibodies against the **nicotinic ACh receptor** reduce receptor number, so the end-plate potential misses threshold. The hallmark is **fatigable weakness** (ptosis, diplopia), treated with anticholinesterases; **botulinum toxin** blocks *release* presynaptically — same sign, opposite side of the synapse.

**Local anaesthetics abolish the action potential itself.** Lidocaine and bupivacaine are weak bases: the **uncharged form crosses the axon membrane**, ionises inside, and **blocks the voltage-gated Na⁺ channel from within**, so no spike is generated. Hence the block fails in **infected, acidic tissue**, and adrenaline is added to slow absorption. **General anaesthetics** differ: they enhance GABA_A inhibition or block NMDA receptors.

**Parkinson's disease is the loss of dopaminergic neurons in the substantia nigra pars compacta.** Falling dopamine input to the striatum leaves basal ganglia inhibition excessive — **bradykinesia, rigidity, resting tremor**. By the time symptoms appear most of those neurons are gone, so **L-DOPA** replaces the missing transmitter.

**Epilepsy is uncontrolled synchronised firing**: excitation outruns inhibition through lost GABAergic restraint, excess glutamate, or abnormal channel kinetics. **Phenytoin and carbamazepine** prolong Na⁺ channel inactivation, limiting high-frequency firing but not normal conduction.

**Opioids hijack the endorphin system.** Endorphins act at **μ, κ, δ opioid receptors** to suppress pain transmission; morphine and fentanyl are agonists at the same receptors, giving analgesia but also **respiratory depression** in overdose.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "A stronger stimulus gives a bigger action potential" | Action potentials are **all-or-none**; intensity is coded by **firing frequency and fibre recruitment**, never amplitude. Graded potentials do vary in size. |
| "The Na⁺/K⁺ pump generates the action potential" | The pump only **maintains the gradients**; the spike is passive Na⁺ and K⁺ flowing down them through gated channels, and repolarisation is **K⁺ leaving through open channels**, not the pump running backwards. |
| "Myelin speeds conduction by insulating the signal like a wire" | Myelin **raises membrane resistance and lowers capacitance**, so current reaches the next node and the AP is regenerated only there — **saltatory** conduction. |
| "IPSPs must hyperpolarise the cell" | **Shunting inhibition** raises Cl⁻ conductance so incoming excitation is short-circuited — inhibition with little change in voltage. |
| "Sympathetic = adrenaline, parasympathetic = acetylcholine" | **Both preganglionic fibres release ACh**; sympathetic *postganglionic* fibres release **noradrenaline** (sweat glands excepted). Adrenaline comes from the adrenal medulla. |
| "Sensory nerves carry signals to the brain" | Afferent means **toward the CNS**, not toward consciousness — most pathways synapse in the **thalamus**, and spinal reflexes finish without the brain. |
| "Local and general anaesthetics work the same way" | Local anaesthetics **block voltage-gated Na⁺ channels** so no AP forms; general anaesthetics **enhance inhibition or block excitation** centrally. |
| "Sensory adaptation means the stimulus ended" | The stimulus is unchanged; the **receptor** stopped responding. Adaptation is receptor-level, whereas fever is a **set-point change at the control centre**. |

## Key facts

- The nervous system is the **fast control arm**: signals in **milliseconds** versus hormones in seconds to hours — brief, point-to-point, and stopped when firing stops.
- **CSF** (~150 mL) floats and cushions the brain; the **blood–brain barrier** is endothelial **tight junctions**, so a CNS drug must be **lipophilic** or carried by a transporter.
- **Myelin** (Schwann cells in PNS, oligodendrocytes in CNS) with **nodes of Ranvier** gives **saltatory conduction**; velocity also rises with **axon diameter** and temperature.
- **Resting potential ≈ −70 mV**: permeability is far higher to **K⁺ than Na⁺**, and **Na⁺/K⁺-ATPase (3 Na⁺ out : 2 K⁺ in)** keeps the gradients supplied; Nernst balances one ion, Goldman weights by permeability.
- **Action potential chain**: stimulus → **threshold −55 mV** → voltage-gated **Na⁺ opens** → depolarisation to **+30 mV** → **Na⁺ inactivation** + voltage-gated **K⁺ opens** → repolarisation → **hyperpolarisation** → pump restores.
- The AP is **all-or-none**; **frequency and recruitment** encode intensity; **refractory periods** enforce one-way travel and a maximum rate.
- Transmission: AP → **Ca²⁺ influx** → **SNARE**-mediated fusion → transmitter → **ionotropic (fast)** or **metabotropic (slow)** receptors → **EPSP/IPSP** → **summation** → threshold; signals end by **reuptake, degradation, or diffusion** (SSRIs, anticholinesterases, cocaine).
- **Reflex arc**: receptor → sensory neuron → interneuron → motor neuron → effector; **stretch reflex monosynaptic** and negative feedback by design, **withdrawal reflex polysynaptic** with a crossed-extensor limb.
- **Sympathetic** (thoracolumbar, noradrenaline, α/β receptors) and **parasympathetic** (craniosacral, acetylcholine, muscarinic receptors) **dual-innervate** most organs — control by **ratio**, homeostasis applied to visceral effectors.
- Sensory receptors **transduce** a stimulus into a graded receptor potential then into **frequency**; **adaptation** is receptor-level and is never a set-point change.

## Practice questions

**1. The resting membrane potential of about −70 mV is best explained by**

A. Active transport of Na⁺ into the cell at rest
B. High resting permeability to K⁺ through leak channels, with the pump maintaining those gradients
C. Equal permeability to Na⁺ and K⁺, with the Na⁺ gradient dominating
D. Voltage-gated Na⁺ channels being open at rest

**Answer: B**

Explanation: K⁺ leak channels dominate resting conductance, so the membrane sits near E_K. The pump maintains the gradients but is not the battery.

---

**2. A stronger stimulus applied to a sensory nerve fibre produces**

A. A larger action potential
B. Same-sized action potentials but at a higher frequency
C. A longer-lasting single action potential
D. Smaller action potentials at low intensities

**Answer: B**

Explanation: Action potentials are all-or-none; intensity is signalled by firing frequency and fibre recruitment. Amplitude belongs to graded potentials.

---

**3. The refractory period of an axon ensures that an action potential**

A. Travels in both directions along a myelinated axon
B. Can be re-initiated at the same spot by a stronger stimulus
C. Travels only in one direction because the segment just behind it cannot yet refire
D. Is regenerated at every point along a demyelinated axon

**Answer: C**

Explanation: Na⁺ channels are inactivated during the absolute refractory period, so the segment just passed cannot refire.

---

**4. Myelin increases conduction velocity primarily because it**

A. Makes ions diffuse faster through the membrane
B. Raises membrane resistance and lowers capacitance, so the AP is regenerated only at nodes of Ranvier
C. Opens more Na⁺ channels along the internode
D. Converts continuous conduction into a slower graded potential

**Answer: B**

Explanation: Myelin reduces leak and capacitance, so current reaches the next node, where dense Na⁺ channels regenerate the AP — saltatory conduction.

---

**5. If all extracellular calcium were removed from a synapse, the result would be**

A. Continuous, uncontrolled neurotransmitter release
B. Action potentials would fail to propagate along the axon
C. The terminal would depolarise normally but fail to release neurotransmitter
D. Postsynaptic receptors are destroyed

**Answer: C**

Explanation: Ca²⁺ triggers SNARE-mediated vesicle fusion, so without it the terminal depolarises but releases nothing. Na⁺-dependent propagation is unaffected.

---

**6. Which pair correctly matches receptor type with speed of action?**

A. Ionotropic — slow, second-messenger mediated
B. Metabotropic — fast, direct ion flow
C. Ionotropic — fast, ligand-gated channel; metabotropic — slower, second messenger
D. Both are equally fast

**Answer: C**

Explanation: Ionotropic receptors are ligand-gated channels acting in milliseconds; metabotropic receptors act over seconds via G-proteins. The same transmitter can be excitatory or inhibitory depending on its receptor.

---

**7. Two excitatory synapses on one neuron fire together and reach threshold. This is**

A. Temporal summation
B. Spatial summation
C. Reciprocal inhibition
D. Sensory adaptation

**Answer: B**

Explanation: Spatial summation adds graded potentials from different terminals at the same moment; temporal summation reuses one terminal in succession.

---

**8. In the knee-jerk (stretch) reflex, the neural pathway is**

A. Receptor → sensory neuron → interneuron → motor neuron → effector
B. Receptor → motor neuron → sensory neuron → effector
C. Receptor → sensory neuron → motor neuron → effector (monosynaptic)
D. Receptor → sensory neuron → brain → motor neuron → effector

**Answer: C**

Explanation: The stretch reflex is monosynaptic — the Ia afferent synapses directly on the alpha motor neuron. Interneurons appear in polysynaptic reflexes.

---

**9. Which combination of sympathetic effects is correct?**

A. Pupil constricts, bronchi constrict, heart rate falls, gut motility rises
B. Pupil dilates, bronchi dilate, heart rate rises, gut motility falls
C. Pupil constricts, bronchi dilate, heart rate rises, gut motility rises
D. Pupil dilates, bronchi constrict, heart rate rises, gut motility rises

**Answer: B**

Explanation: Sympathetic activation mobilises for action: mydriasis, bronchodilation, tachycardia, inhibited digestion. Option A describes parasympathetic dominance.

---

**10. A local anaesthetic injected into infected, acidic tissue is less effective because**

A. The infection destroys the drug
B. Voltage-gated Na⁺ channels cannot be blocked in acid
C. The drug is ionised at low pH, cannot cross the membrane, and so cannot reach the Na⁺ channel
D. Acidic pH lowers the threshold for action potentials

**Answer: C**

Explanation: Local anaesthetics cross the membrane uncharged and bind the Na⁺ channel inside; in acidosis more stays protonated outside, so less enters.
