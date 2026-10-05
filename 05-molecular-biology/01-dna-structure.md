# DNA Structure

## Why it matters

Every question in molecular biology eventually reduces to one of three: **how is the information stored, how is it copied, and how is it read?** All three answers come from the shape of DNA. Complementary base pairing explains copying, the reversibility of hydrogen bonding explains how the copy is made without destroying the original, and the sequence of bases along a strand is the information itself.

This is the clearest case in biology of **structure determining function**. DNA is not a bag of information held together by strong glue; it is a molecule engineered (by evolution) to be stable when it must be and separable when it must be. The two strands grip each other firmly through millions of individually weak interactions, then part like a zip under the action of a single enzyme and re-form afterwards.

The chapter deepens what [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) introduced: the chemistry of the nucleotide, the rules of pairing, and the geometry of the helix — then shows why those features make replication, repair, and regulation possible at all.

## The nucleotide, revisited

Every strand of DNA is a polymer of **nucleotides**. Each nucleotide has three parts:

```
      NITROGENOUS BASE
             │
   PHOSPHATE ─── SUGAR (deoxyribose)
    (5′ end)      (1′–5′ carbons)
```

| Component | Identity | Role |
| --- | --- | --- |
| **Phosphate** | Phosphoric acid esterified to the 5′ carbon | Negative charge at physiological pH; makes the backbone hydrophilic and acidic |
| **Sugar** | **2-deoxyribose** (a pentose) | Structural spine; the 2′ position defines DNA vs RNA |
| **Base** | Purine (A, G) or pyrimidine (C, T) | Carries the information; faces inward |

### Deoxyribose vs ribose: one oxygen, one consequence

```
RIBOSE                      DEOXYRIBOSE

 C2′:  ─ OH                  C2′:  ─ H
        │                           │
     (reactive)                (unreactive)
```

The missing oxygen at the 2′ carbon has two effects that shape the whole of biology:

1. **Chemical stability.** The 2′-OH in RNA can attack the adjacent phosphodiester bond and cut the backbone. DNA cannot do this, so it survives for decades inside a cell and for millennia outside one — a requirement for an archival molecule.
2. **Enzyme recognition.** DNA polymerases and repair enzymes have active sites built around a **deoxy** sugar; a ribose sugar placed in a DNA strand is recognised as an error and removed. The distinction is not cosmetic — it is a quality-control signal.

### Base pairing: A=T with two hydrogen bonds, G≡C with three

```
   ADENINE ═══════ THYMINE        GUANINE ≡≡≡≡ CYTOSINE
       two hydrogen bonds            three hydrogen bonds
       (easier to separate)          (harder to separate)

   A · · · T          G · · · C
       purine–pyrimidine in both cases → constant helix width
```

| Pair | Hydrogen bonds | Geometry |
| --- | --- | --- |
| **A–T** | **2** | Purine–pyrimidine, same width as G–C |
| **G–C** | **3** | Purine–pyrimidine, same width as A–T |

Two rules follow, and both matter:

- **Purine always pairs with pyrimidine.** A purine–purine pair is too wide; a pyrimidine–pyrimidine pair is too narrow. Constant width is what lets any sequence fit into a regular helix.
- **Pairing is specific but not symmetric in strength.** Three hydrogen bonds make G–C pairs individually harder to pull apart than A–T pairs — the basis of the melting behaviour described below.

**Chargaff's rules** were the empirical anchor. Erwin Chargaff measured base composition across species and found **%A = %T** and **%G = %C**, but that the A+T : G+C ratio differed between organisms. Those ratios are the direct consequence of the pairing rules — Chargaff supplied the arithmetic before anyone supplied the structure.

### Antiparallel strands and 5′→3′ directionality

The two strands run in **opposite directions**:

```
    5′ ──────── A T G C C T A ──────── 3′
    ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║ ║
    3′ ──────── T A C G G A T ──────── 5′
    template          complementary
                      (new) strand
```

Each strand has chemically distinct ends: a **5′ phosphate** and a **3′ hydroxyl**. Because a polymerase can only add a nucleotide to a free 3′-OH, **every nucleic acid polymer in the cell — DNA or RNA — is built in the 5′→3′ direction**. This single chemical fact later dictates the leading/lagging architecture of the replication fork and the direction RNA polymerase must travel. It is reviewed in [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) and cashed out in [02 — DNA replication](02-dna-replication.md).

## The double helix

Watson and Crick's 1953 model: two right-handed **B-form** helical strands wound around a common axis, sugar–phosphate backbones outside, bases stacked inside.

```
         5′ end
          │
     ╭────┴────╮   ← major groove (wide, protein-binding face)
     │  G ··· C │
     │  C ··· G │   ← minor groove (narrow)
     │  A ··· T │
     │  T ··· A │
     │  G ··· C │
     ╰────┬────╯
          │
         3′ end
```

Three features do the work:

| Feature | What it does |
| --- | --- |
| **Base stacking** — van der Waals and hydrophobic contacts between adjacent stacked bases | The **dominant** stabilising force; the reason the helix has a defined melting temperature at all |
| **Hydrogen bonds between paired bases** | Provide **specificity**: only complementary sequences stay paired, and the bonds can be broken and re-formed reversibly |
| **Major and minor grooves** | Expose a sequence-dependent pattern of chemical groups so proteins can **read** the sequence without unwinding the helix (see below) |

### Reading without unwinding

Because the backbones are offset, the **major groove** presents a distinct pattern of hydrogen-bond donors, acceptors, and methyl groups for every possible base pair. Transcription factors insert an α-helix into that groove and identify their binding site by the pattern alone — the physical basis of the gene regulation in [06 — Gene regulation](06-gene-regulation.md).

### Why structure explains function and replication

The logic can be stated as a chain of consequences:

```text
COMPLEMENTARY PAIRING
        ↓
each strand specifies the other
        ↓
strand separation gives two TEMPLATES
        ↓
each template directs synthesis of a new partner
        ↓
SEMICONSERVATIVE REPLICATION (proven by Meselson–Stahl)
        ↓
hydrogen bonds are weak and reversible
        ↓
strands can be opened locally without cutting the backbone
        ↓
one molecule can be copied thousands of times without being consumed
```

Two more structural facts extend the logic:

- **The backbone is covalent; the strands are not.** Splitting a chromosome costs a few hydrogen bonds per base pair, not a single covalent bond — so replication and transcription are cheap, and the original molecule survives intact.
- **Sequence, not composition, is the information.** Two molecules with 50 % A/T and 50 % G/C but different orders carry different messages. Stacking depends on neighbours, so even physical properties such as melting temperature depend on **order**, not just ratio.

## Chromosomes at a glance: replicons, centromeres, telomeres

A eukaryotic chromosome is not an endless uniform thread; it is a linear molecule with defined functional regions.

```
TELOMERE ──── [origin] ──── replicon ──── [origin] ──── ... ──── CENTROMERE ──── ... ──── TELOMERE
   (cap)                                                     │
                                              kinetochore attaches here → spindle fibre
```

| Region | Function | Chapter |
| --- | --- | --- |
| **Origin of replication** | Where the fork is licensed to start; a stretch of DNA served by one origin is a **replicon** | [02 — DNA replication](02-dna-replication.md) |
| **Centromere** | Constricted region where the **kinetochore** assembles so the spindle can segregate the chromosome | [10 — Cell cycle](../03-cellular-processes/10-cell-cycle-and-checkpoints.md) |
| **Telomere** | Tandem repeats (TTAGGG in humans) capping each end — solves the end-replication problem and protects ends from being read as breaks | [02 — DNA replication](02-dna-replication.md) |
| **Gene-rich vs gene-poor regions** | Chromatin packaging, discussed in [06 — Gene regulation](06-gene-regulation.md) | [02 — Cell biology](../02-cell-biology/02-plasma-membrane-and-nucleus.md) |

Linear chromosomes face two problems circular bacterial chromosomes never do: **an end that cannot be fully copied** and **an end that looks like a broken DNA molecule to the repair machinery**. Telomeres solve both, and the solution has a dark side that reappears in cancer.

## Denaturation, renaturation, and melting temperature

Because only hydrogen bonds and stacking hold the two strands together, heat can separate them — **denaturation** (melting). Cooling lets complementary strands find each other again — **renaturation** (annealing).

```
        native duplex                     separated strands
   5′ ═══════════ 3′   ── heat ──▶   5′ ═══        ═══ 3′
   3′ ═══════════ 5′   ◀─ cool ──   3′ ═══        ═══ 5′
        (hypochromic)                      (hyperchromic)
```

- **Hyperchromicity:** single-stranded DNA absorbs ~30–40 % more UV light at 260 nm than duplex DNA, because stacked bases in a helix quench each other's absorption. Melting is therefore measurable — a spectrophotometer can watch a chromosome come apart.
- **Tm (melting temperature)** is the midpoint of denaturation: the temperature at which half the strands are separated.

| Factor | Effect on Tm | Why |
| --- | --- | --- |
| **Higher G–C content** | **Raises Tm** | Three hydrogen bonds per pair instead of two |
| **Longer molecule** | Raises Tm | More total interactions per strand |
| **Higher salt** | Raises Tm | Na⁺ shields the negative backbone charges that otherwise repel |
| **More A–T content** | **Lowers Tm** | Two bonds; A–T rich regions open first |

**Practical consequence:** **A–T rich regions melt first**, which is not an accident of sequence — origins of replication and many promoters are deliberately A–T rich so that the machinery can open the DNA at body temperature. The stability of the genome is uniform; the *accessibility* of the genome is programmed by sequence.

Renaturation is the basis of everything that reads DNA by complementarity: PCR amplification, hybridisation blots, fluorescent in situ hybridisation, antisense probes, and DNA–DNA or DNA–RNA hybrid formation in diagnostics.

## The evidence: how the structure was found

| Contribution | Who | What it showed |
| --- | --- | --- |
| **Chargaff's rules** | Erwin Chargaff (1950s) | A = T, G = C, and species-specific ratios — the constraint any model had to satisfy |
| **Photo 51** | **Rosalind Franklin** and Raymond Gosling (1952) | An X-ray diffraction pattern showing a **helix**, **antiparallel strands**, a repeat of ~3.4 Å between bases, and a diameter of ~20 Å |
| **Model building** | **James Watson and Francis Crick** (1953) | Combined Chargaff's arithmetic, Franklin's diffraction data, and Jerry Donohue's correction of base structures into the double-helix model |
| **Confirmatory work** | Wilkins, and later Franklin's continued diffraction | Physical data consistent with the model |

**The often-missed point:** no one "discovered" the structure by looking at it. Chargaff supplied the chemical constraints, Franklin supplied the physical dimensions, and Watson and Crick supplied the modelling that made all the constraints fit at once. Franklin's contribution was essential and was not recognised in the 1962 Nobel award — a standard example of how scientific credit is distributed unevenly.

**Chargaff's second insight is underused in exams:** base ratios *differ between species*. That means sequence carries heritable, species-specific information — the chemical notion of a "gene" became possible only once composition was shown to be variable.

## Medical relevance

**Melting temperature is a diagnostic tool.** PCR primers are designed so their Tm values match the cycling temperature; hybridisation-based tests (including some pathogen and genotype assays) are read as "does this probe melt off at the expected temperature?" A test that fails usually fails because of GC content, not because of biology.

**A–T rich regions are the genome's weak points.** Origins, promoters, and trinucleotide repeat tracts with high A–T content are prone to strand separation and slippage — one reason repetitive, compositionally biased sequences are fragile and mutation-prone (see [07 — Mutations](07-mutations.md)).

**UV damage happens where bases stack.** Adjacent pyrimidines absorb UV and fuse into **thymine dimers**, distorting the helix — a structural lesion that must be removed by nucleotide excision repair. Xeroderma pigmentosum, the classic repair disease, is discussed in [07 — Mutations](07-mutations.md).

**Nucleoside and nucleotide analogues are a whole drug class.** Because polymerases read the sugar and base, a modified sugar or base is accepted and then stalls the enzyme. Acyclovir (a guanine analogue without a proper sugar), AZT, and 5-fluorouracil all work by impersonating a normal nucleotide — the same trick is used deliberately in sequencing, where labelled chain terminators stop synthesis at a known base.

**Forensics reads structure directly.** Short tandem repeats are separated by length, and mitochondrial DNA is sequenced where nuclear DNA is degraded — both possible because the backbone survives conditions that destroy proteins, and because complementary probes bind specifically.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| "A–T and G–C hold the helix together equally" | G–C has **three** hydrogen bonds, A–T two — GC content raises Tm. Stacking, not hydrogen bonding, is still the largest single stabiliser. |
| "Denaturation breaks the backbone" | It separates **strands** by disrupting hydrogen bonds and stacking; the covalent backbone is untouched. |
| "Complementary means identical" | Complementary strands are **base-pairing partners**, so their sequences are reverse complements — the opposite written sequence. |
| "Tm depends only on length" | It depends on **length, GC content, and salt**; two equal-length fragments can differ by tens of degrees. |
| "Chargaff proved the double helix" | He proved **base ratios**; the helical, antiparallel model came from diffraction plus model building. |
| "5′ and 3′ mark the two strands' chemical polarity differently" | They mark **each strand's** polarity: 5′ phosphate on one end, 3′ OH on the other. Antiparallel means the two strands read in opposite directions. |

## Key facts

- A nucleotide = **phosphate + deoxyribose + base**; DNA's sugar lacks the 2′-OH, making it far more stable than RNA.
- **A pairs with T by two hydrogen bonds; G pairs with C by three.** Purine always pairs with pyrimidine, keeping helix width constant.
- **Chargaff's rules** (A = T, G = C, species-specific ratios) are the arithmetic consequence of base pairing and were the constraint on the model.
- The two strands are **antiparallel**: one 5′→3′, the other 3′→5′; every polymerase builds **5′→3′** using a free 3′-OH.
- The helix is **right-handed B-DNA** with bases stacked inward and backbones outside; **base stacking is the dominant stabiliser**, hydrogen bonds give **specificity and reversibility**.
- Proteins read sequence through the **major groove** without unwinding DNA.
- Structure explains replication: strand separation yields two templates, each specifying a new partner → **semiconservative replication**.
- **Telomeres** cap linear chromosome ends (TTAGGG repeats); **centromeres** anchor the kinetochore; an origin and the DNA it serves define a **replicon**.
- **Tm** rises with GC content, length, and salt; A–T rich regions (origins, promoters) melt first — programmed accessibility.
- Denaturation/renaturation is measurable by **hyperchromicity at 260 nm** and underpins PCR, hybridisation tests, and antisense probes.
- Evidence came from three sources: **Chargaff (chemistry), Franklin (diffraction), Watson–Crick (model building)**.

## Practice questions

**1. Which feature of DNA explains why it can be copied without being consumed?**

A. The covalent sugar–phosphate backbone
B. Reversible hydrogen bonding between complementary bases
C. The presence of deoxyribose
D. Negative charge on the phosphates

**Answer: B**

Explanation: Hydrogen bonds are individually weak and can be broken and re-formed at will, so the two strands separate locally under helicase action and each serves as a template — the original molecule survives the process intact. The backbone (A) must *not* be broken for replication to be cheap, but it is not what allows separation and re-pairing; deoxyribose (C) contributes stability rather than copyability; the charge (D) affects solubility and protein binding, not template copying.

---

**2. A DNA sample contains 30 % guanine and 30 % cytosine. What percentage of its bases is adenine?**

A. 30 %
B. 40 %
C. 20 %
D. 10 %

**Answer: C**

Explanation: Chargaff's rules give two equalities — A = T and G = C — and the four bases must total 100 %. Here G + C = 60 %, which leaves 40 % for A + T; since A = T, adenine is 20 %. The reliable method is always the same two steps: subtract the known G + C total from 100, then halve the remainder. Getting the order of operations wrong (halving before subtracting) is the classic way this question is lost.

---

**3. Compared with an A–T rich fragment of the same length, a G–C rich fragment will**

A. Have a lower melting temperature
B. Have a higher melting temperature
C. Have an identical melting temperature
D. Melt only under alkaline conditions

**Answer: B**

Explanation: Each G–C pair has three hydrogen bonds versus two for A–T, so more energy is required to separate the strands, raising Tm. Salt and length also shift Tm, but at equal length and ionic strength GC content dominates. This is why PCR primers and hybridisation probes are designed around predicted GC content, and why A–T rich origins and promoters open easily at body temperature.

---

**4. The antiparallel nature of DNA means that**

A. One strand has a 5′ phosphate and the other has no phosphate
B. The two strands run in opposite directions, one 5′→3′ and the other 3′→5′
C. One strand is DNA and the other is RNA
D. The bases point outward on one strand and inward on the other

**Answer: B**

Explanation: Antiparallel refers solely to directional polarity: each strand runs 5′→3′, and the two are aligned in opposite orientations so that base pairs fit. Because polymerases only extend a 3′-OH, this opposition is exactly what will force discontinuous synthesis on one strand during replication. Backbones are chemically equivalent on both strands (A), both are DNA (C), and base orientation is the same on both (D).

---

**5. Which contribution was Rosalind Franklin's primary experimental evidence for the double helix?**

A. Measurement of base ratios across species
B. X-ray diffraction images showing a helix with a 3.4 Å repeat
C. Model building from chemical constraints
D. Discovery that DNA carries transforming activity

**Answer: B**

Explanation: Franklin's diffraction work, especially Photo 51, established the helical shape, the diameter, the spacing between stacked bases, and the antiparallel arrangement. Base ratios (A) were Chargaff's, model building (C) was Watson and Crick's synthesis of the other data, and transforming activity (D) is Avery's earlier work on the chemical nature of the gene.

---

**6. Why does single-stranded DNA absorb more UV light at 260 nm than double-stranded DNA?**

A. Single strands contain more thymine
B. Bases in a helix are stacked and quench one another's absorption
C. Double-stranded DNA destroys the bases
D. Phosphates absorb UV only when paired

**Answer: B**

Explanation: Stacking interactions between base pairs in the helix reduce their UV absorption — the bases are effectively shielding each other. When the strands separate, the bases become more exposed and absorption rises (hyperchromicity). This measurable change is how laboratories monitor denaturation and follow PCR in real time. Base composition (A) is unchanged by melting, no bases are destroyed (C), and phosphates do not account for the 260 nm signal (D).

---

**7. What structural feature allows a transcription factor to identify its binding site without unwinding DNA?**

A. The phosphate backbone's negative charge
B. The pattern of chemical groups exposed in the major groove
C. The hydrogen bonds between the two strands
D. The deoxyribose sugars

**Answer: B**

Explanation: Because the backbones are offset, each base pair presents a unique arrangement of donors, acceptors, and methyl groups in the major groove, and proteins read that pattern with an inserted recognition helix. The backbone (A) and sugars (D) are sequence-invariant and carry no information; the inter-strand hydrogen bonds (C) are buried and not distinguishable from outside.

---

**8. Telomeres exist because linear chromosomes**

A. Cannot be unwound by helicase
B. Have an end-replication problem and ends that resemble DNA breaks
C. Lack origins of replication
D. Are replicated before mitosis

**Answer: B**

Explanation: The lagging-strand machinery cannot place an RNA primer right at the very end, so each round of replication shortens chromosome ends; telomeric repeats absorb that loss. Telomeres also blunt-protect the ends so repair enzymes do not treat them as double-strand breaks and fuse chromosomes together. Origins are plentiful on linear chromosomes (C), unwinding is not the issue (A), and replication timing (D) is a cell-cycle matter, not a telomere function.

---

**9. Which statement about Chargaff's rules is most accurate?**

A. They proved the helical shape of DNA
B. They showed A = T and G = C in a given organism, with ratios varying between species
C. They demonstrated that DNA is the transforming principle
D. They established that RNA carries the code

**Answer: B**

Explanation: Chargaff's quantitative base measurements provided the constraint that any structural model had to satisfy and, crucially, showed that base composition differs between species — so sequence can carry heritable information. The helical geometry came from X-ray diffraction (A); transformation was Avery's work (C); and the coding role of RNA was established much later.

---

**10. A laboratory heats DNA to separate the strands and then cools it. The strands reassociate. This process is called**

A. Replication
B. Denaturation followed by renaturation (annealing)
C. Transcription
D. Translation

**Answer: B**

Explanation: Heating disrupts hydrogen bonds and stacking (denaturation); cooling allows complementary sequences to find each other and re-form the duplex (renaturation/annealing). It is not replication — no new strand is synthesised, only existing ones reassociate. Transcription and translation are enzyme-catalysed reading processes, not thermal separation and re-pairing. Annealing is the physical principle behind PCR's cooling step and behind every hybridisation-based diagnostic.
