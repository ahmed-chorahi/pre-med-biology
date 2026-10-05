# Protein Synthesis and Trafficking Organelles

## Why it matters

The instructions for every protein are in the nucleus; the working proteins are needed everywhere else. The organelles in this chapter are the **manufacturing and logistics system** that closes that gap: ribosomes build, the endoplasmic reticulum folds and inserts, the Golgi sorts and labels, vesicles carry, lysosomes recycle, and peroxisomes handle chemistry too dangerous to do in the open cytoplasm.

Read them as one continuous route rather than seven separate definitions:

```
NUCLEUS ──mRNA──▶ RIBOSOME ──▶ ROUGH ER ──vesicle──▶ GOLGI ──vesicle──▶ destination
                     │                                              ├─▶ plasma membrane (secretion)
                     │                                              ├─▶ outside the cell
                     │                                              └─▶ LYSOSOME
                     │
                     └─ (no signal sequence) ──▶ free in cytoplasm
                                                   │
                                                   ├─▶ cytosolic proteins
                                                   └─▶ SMOOTH ER / peroxisome / mitochondria

ROUGH ER = ribosomes attached     SMOOTH ER = no ribosomes, different jobs
```

Every arrow is a decision point, and most of the diseases in this chapter are arrows that went wrong.

## Ribosomes: the machines that read

| Property | Detail |
| --- | --- |
| **Composition** | rRNA + protein — a **ribozyme**, because catalysis is done by the RNA |
| **Cytosolic type (eukaryotes)** | **80S** = large 60S + small 40S subunits |
| **Bacterial / mitochondrial / chloroplast type** | **70S** = 50S + 30S |
| **Where made** | rRNA transcribed and subunits assembled in the **nucleolus** |
| **Where they work** | Free in cytoplasm, bound to rough ER, bound to outer mitochondrial membrane, free in bacteria |

**The S values are sedimentation rates, not masses** — a common exam trap. They reflect shape as well as weight, which is why 60S + 40S ≠ 100S.

### Translation in one pass

```
1. INITIATION   small subunit + mRNA find each other; first tRNA binds AUG
                     ↓
2. ELONGATION    tRNA delivers amino acid → codon read → peptide bond forms
                     ↓        (rRNA catalyses the bond — a ribozyme)
                 ribosome translocates one codon; cycle repeats
                     ↓
3. TERMINATION   stop codon binds a release factor; polypeptide released
                     ↓
4. RECYCLING     subunits separate, ready for another mRNA
```

Details of codons, tRNA, and the genetic code belong to [04 — Nucleic acids](../01-biochemistry/04-nucleic-acids.md) and [05 — Molecular Biology](../05-molecular-biology/). What matters *here* is the decision the ribosome never makes: **whether the protein stays soluble or enters the trafficking system.** That decision is made by a signal sequence.

### The signal peptide: the address label

A protein destined for the ER, for secretion, or for a membrane begins with a short **signal sequence** at its N-terminus.

```
cytosol:
  ribosome begins translating
        │
        ▼  signal sequence emerges
  SIGNAL RECOGNITION PARTICLE (SRP) binds it
        │   ← translation PAUSES
        ▼
  SRP docks to the SRP receptor on the ROUGH ER
        │
        ▼
  channel (translocon) opens; ribosome binds; translation RESUMES
        │
        ▼
  polypeptide is threaded INTO the ER lumen
        │
        ▼
  signal sequence is cleaved off; protein folds in the lumen
```

Three consequences follow, and each one is worth holding onto:

1. **Targeting is co-translational.** The protein is pushed into the ER while it is still being made, so it never enters the cytoplasm — where the crowded, reducing environment would be wrong for a protein that must fold with disulfide bonds.
2. **Folding happens in the ER lumen**, an oxidising environment that *permits* disulfide bonds, with chaperones (BiP and others) preventing aggregation. A misfolded protein is retained and retrotranslocated for degradation rather than shipped.
3. **Every protein in the secretory pathway passes through the ER.** The ER is the entry point, which is why it is physically continuous with the nuclear envelope — the mRNA leaves the nucleus and immediately meets the machinery that will handle its product.

**Free ribosomes vs bound ribosomes** is a distinction that confuses many students. The ribosomes themselves are identical and interchangeable; what differs is *where they are at that moment*, and that is determined entirely by whether the emerging protein has a signal sequence.

## The endoplasmic reticulum

The ER is a single continuous membrane system with two functional regions.

### Rough ER (RER)

| Feature | Detail |
| --- | --- |
| Appearance | Studded with ribosomes |
| Location | Continuous with the outer nuclear membrane |
| Job | Synthesis of **secreted proteins, membrane proteins, and lysosomal enzymes** |
| Extra job | Initial **N-linked glycosylation** — sugars added to the protein as it folds |
| Also | Calcium storage in specialised forms (see smooth ER) |

Cells that secrete heavily are visibly packed with RER: pancreatic acinar cells (digestive enzyme precursors), plasma cells (antibody factories), and goblet cells (mucus). **A cell's RER content is a direct readout of its secretory workload** — one of the first things visible under a microscope.

### Smooth ER (SER)

No ribosomes. Different jobs — and worth separating by function because they appear in different organs:

| Function | Where it is prominent | Notes |
| --- | --- | --- |
| **Phospholipid and steroid synthesis** | Testis, ovary, adrenal cortex | Steroid hormones are lipid-derived, so the machinery is membrane-based |
| **Detoxification** | Hepatocytes (liver) | Cytochrome P450 enzymes; also metabolises drugs and alcohol |
| **Ca²⁺ storage and release** | Skeletal and cardiac muscle (**sarcoplasmic reticulum**) | Triggers muscle contraction — see 10 — Muscular |
| **Glycogen metabolism** | Liver | Glucose-6-phosphatase releases free glucose into blood |

**The liver's smooth ER expands in response to chronic alcohol exposure** — the cell literally builds more detoxification membrane. That expansion has a pharmacological consequence: the same enzymes now clear other drugs faster, which is why chronic drinkers require higher doses of many medicines. The organelle adapts to demand, and the adaptation changes drug response.

**The sarcoplasmic reticulum is the smooth ER renamed for a tissue.** Its job — store Ca²⁺, release it on command — is exactly the "compartmentalise an ion" version of the smooth ER's calcium role. Same organelle, different name, different organ.

## The Golgi apparatus

The Golgi receives from the ER, modifies, sorts, and dispatches. It is **polarised**: cis face receives, trans face dispatches.

```
   RER ──vesicle──▶  CIS  ──▶ MEDIAL ──▶ TRANS  ──▶ sorting platform
   (entry)             │                    │
                    modifications         exits by destination
                    • glycan trimming     ├─▶ lysosome (M6P tag)
                    • phosphorylation     ├─▶ plasma membrane (constitutive)
                    • sulfation           ├─▶ secretory vesicle (regulated)
                                          └─▶ outside (secretion)
```

| Feature | Detail |
| --- | --- |
| **Structure** | Stack of flattened cisternae with distinct enzyme sets in each level |
| **Movement** | Vesicles bud from ER (COPII coat), arrive at cis face; within the Golgi, cisternae progress or cargo is carried forward (COPI coat for retrograde return) |
| **Modifications** | Trimming and completing carbohydrate chains started in the ER; phosphorylation of mannose to **mannose-6-phosphate (M6P)** — the lysosomal address tag |
| **Sorting** | Receptors at the trans face read tags and package cargo into the right vesicle |

**Two modes of secretion:**

- **Constitutive** — vesicles flow continuously to the membrane, delivering lipid and protein whether or not a signal arrives. Every cell does this; it is how membrane is renewed.
- **Regulated** — cargo is stored in dense secretory granules and released only on a specific trigger. Pancreatic enzyme granules, neurotransmitter vesicles, and histamine granules all work this way.

**Why the difference exists:** constitutive secretion is *maintenance*, regulated secretion is *a command*. Cells that must respond on demand cannot afford to have the product already loose in the extracellular space.

**Signal peptidase and pro-proteins.** Some proteins are shipped as inactive precursors and activated only at the destination — pro-insulin → insulin, pepsinogen → pepsin. Shipping inactive and activating on site is the same safety logic as the zymogens in [05 — Enzymes](../01-biochemistry/05-enzymes.md).

## Lysosomes

The lysosome is the cell's recycling and defence compartment: a vesicle of ~50 hydrolytic enzymes operating at **pH ~4.5–5**, maintained by a **proton pump (V-type H⁺-ATPase)** in its membrane.

| Property | Detail |
| --- | --- |
| **Enzymes** | Acid hydrolases — proteases, lipases, nucleases, glycosidases, phosphatases; ~50 types |
| **Optimum pH** | Acidic, set by the V-ATPase; the proton gradient stores the energy |
| **Origin of contents** | Delivered from the Golgi tagged with **mannose-6-phosphate** |
| **Origin of membrane** | Endocytosis from the plasma membrane; fusion with autophagic vesicles |

**Why acid inside?** Two reasons that reinforce each other:

1. The enzymes are acid hydrolases — they work best at low pH, so their activity is confined to the compartment.
2. If an enzyme leaks into the neutral cytoplasm, it is **inactive** there. The pH difference is a containment system as much as an operating condition.

**Safety by containment** is the unifying idea — exactly the logic of zymogens, one level down.

### What lysosomes receive

```
ENDOCYTOSIS      material taken in from outside → endosome → lysosome
PHAGOCYTOSIS     engulfed bacterium or debris → phagosome → lysosome
AUTOPHAGY        damaged organelle wrapped in membrane → autophagosome → lysosome
```

**Autophagy** ("self-eating") is the cell's quality control: it disassembles its own damaged components and reuses the building blocks. It is upregulated during starvation — the cell digests non-essential parts to survive — and it is now understood to be central to aging and to neurodegenerative disease.

**Phagocytosis** is where the lysosome meets immunology: a macrophage engulfs a bacterium, and the phagolysosome destroys it. Pathogens that survive have evolved to **prevent the fusion** — *Mycobacterium tuberculosis* is the textbook case, blocking phagosome–lysosome fusion and surviving inside the very cell sent to kill it.

### Lysosomal storage diseases

If one enzyme is missing, its substrate accumulates inside the lysosome, the organelle swells, and the cell — often a neuron — is damaged. **Substrate accumulation, not lack of product, causes the harm.**

| Disease | Missing enzyme | Accumulates | Main consequence |
| --- | --- | --- | --- |
| **Tay–Sachs** | Hexosaminidase A | GM2 ganglioside | Neurodegeneration, death in early childhood |
| **Gaucher** | Glucocerebrosidase | Glucocerebroside | Hepatosplenomegaly, bone disease |
| **Niemann–Pick** | Sphingomyelinase | Sphingomy lipid | Neurodegeneration, organ enlargement |
| **Pompe** | Acid α-glucosidase | Glycogen | Muscle weakness; enlarged heart |
| **Hurler (MPS I)** | α-L-iduronidase | Glycosaminoglycans | Skeletal and cognitive involvement |
| **I-cell disease** | **GlcNAc phosphotransferase** (not a hydrolase) | — | Enzymes never get the M6P tag, so they are **secreted** instead of delivered |

**I-cell disease is the exception that proves the mechanism.** The hydrolases are made perfectly well — but without the M6P tag they cannot be sorted to lysosomes, so they are exported and the lysosomes fill with undigested material. It demonstrates that **the address tag, not the enzyme, is the delivery system**, and it is the classic question distinguishing "missing enzyme" from "missing targeting."

**The treatment logic that follows:** if the enzyme is missing, supply it — **enzyme replacement therapy** works for several of these diseases because the injected enzyme is taken up by cells via surface receptors and delivered to lysosomes. For diseases where the enzyme cannot cross the blood–brain barrier, **substrate reduction** or **chaperone therapy** is used instead. Each strategy is a fix at a different point in the pathway this chapter describes.

## Peroxisomes

Smaller than lysosomes, single-membrane, and specialised for **oxidative chemistry that would damage the rest of the cell**.

| Feature | Detail |
| --- | --- |
| **Key enzymes** | Fatty acid **β-oxidation** (very-long-chain fatty acids), D-amino acid oxidase, uric acid oxidase |
| **Signature reaction** | Oxidases produce **H₂O₂**; **catalase** then breaks it down: 2 H₂O₂ → 2 H₂O + O₂ |
| **Relationship to mitochondria** | Fatty acids shortened in peroxisomes, then finished in mitochondria |
| **Origin** | Import of matrix proteins by a **peroxisomal targeting signal (PTS)** recognised by cytosolic receptors — proteins arrive fully folded, unlike ER import |

**The H₂O₂ problem and solution are one mechanism:** making a strong oxidant inside a sealed compartment and immediately destroying it with catalase. Catalase is one of the fastest enzymes known precisely because the substrate it handles is dangerous enough to require instant removal.

### Zellweger syndrome

**A peroxisome cannot import its enzymes at all.** The organelles form but stay empty. Consequences follow directly from the enzyme table:

- Very-long-chain fatty acids accumulate (cannot be oxidised) → neurological damage
- Plasmalogens (ether lipids important in myelin) are not synthesised → impaired myelination
- Detoxification fails

**Zellweger is fatal in infancy**, and its severity is the argument that peroxisomes are not optional accessories. The contrast with lysosomal storage disease is instructive: there, one enzyme is missing; here, **the whole compartment's contents are missing.**

### Common confusion: peroxisome vs lysosome

| | Lysosome | Peroxisome |
| --- | --- | --- |
| **Origin of contents** | From the **Golgi** (M6P tag), plus endocytosis | **Imported from cytosol** as folded proteins |
| **pH** | Acidic (~4.5) | Neutral (like cytoplasm) |
| **Main job** | Digest foreign and worn material | Oxidative reactions, H₂O₂ handling |
| **Energy yield** | None | No direct ATP; NADH generated in some reactions |

## The endomembrane system: one system, many compartments

A term worth having: the **endomembrane system** = nuclear envelope, ER, Golgi, lysosomes, vesicles, and plasma membrane — membranes that are physically convertible into one another by budding and fusion.

```
NUCLEAR ENVELOPE ◀─continuous─▶ ER ──budding─▶ GOLGI ──budding─▶ VESICLES
                                     ▲                              │
                                     │                              ▼
                              retrograde return                 DESTINATIONS
                              (salvage of resident               plasma membrane
                               enzymes)                           lysosome
                                                                  outside
```

Two traffic rules make the system work:

1. **Forward (anterograde)** transport is vesicular and directed: cargo moves cis → trans.
2. **Resident proteins are retrieved** — enzymes that belong to the ER carry a retrieval signal and are packaged back by COPI vesicles. Without retrieval, the cell's own machinery would drain out with the secreted product.

**Compartmentalisation buys incompatible chemistry.** As the ETC chapter will show, a proton gradient can be maintained only inside a closed compartment; here, a pH of 4.5 can coexist with a cytoplasm at 7.2; elsewhere, H₂O₂ is generated and destroyed without touching the cytosol. *A eukaryotic cell is a city of sealed rooms doing incompatible jobs side by side.*

## Medical relevance

**Secretory cells and disease — the connection table:**

| Cell type | What it ships | When it goes wrong |
| --- | --- | --- |
| Pancreatic acinar cell | Digestive zymogens | Acute pancreatitis — premature activation |
| Plasma cell | Antibodies | Multiple myeloma — monoclonal antibody overproduction |
| Goblet cell | Mucins | Mucus hypersecretion in airway disease |
| Hepatocyte | Albumin, clotting factors | Liver failure → loss of clotting and oncotic pressure |
| Chondrocyte | Extracellular matrix | Skeletal dysplasias from defective matrix export |

**Misfolding is a trafficking disease.** If a protein cannot fold in the ER, it is retained and degraded. A single amino acid change can do it: **α₁-antitrypsin misfolds, is retained in hepatocyte ER, and never reaches the lungs** — so the patient gets both liver damage (from accumulation) and emphysema (from absent protease inhibitor in lung). One protein, two organs, one trafficking failure.

**Cancer and the Golgi/secretion axis.** Tumour cells upregulate constitutive secretion to supply membrane for rapid growth and to release enzymes that degrade matrix — a requirement for invasion. Secretory pathway components are actively studied as drug targets.

**Viruses hijack this entire system.** Enveloped viruses acquire their lipid envelope by budding through ER or Golgi membranes, and their surface glycoproteins are processed by the Golgi's enzymes. That is why **host glycosylation inhibitors** and the pathways described here are antiviral research targets — the virus does not have its own secretory system, it borrows the cell's.

## Key facts

- **Ribosome 80S (eukaryotic cytosol) = 60S + 40S; 70S (bacteria, mitochondria, chloroplasts) = 50S + 30S.** S = sedimentation rate, not mass.
- Translation: initiation → elongation (peptide bond formed by **rRNA**) → termination → recycling.
- A **signal sequence** targets a ribosome to the RER via **SRP**; synthesis pauses, resumes into the ER lumen; the signal is cleaved. Free and bound ribosomes are the *same* machine.
- **RER**: secreted, membrane, and lysosomal proteins; folding and N-glycosylation. **SER**: lipid/steroid synthesis, detoxification, Ca²⁺ storage (sarcoplasmic reticulum), glycogen metabolism.
- **Golgi**: cis receives, trans dispatches; adds and trims glycans, phosphorylates mannose to **M6P**; constitutive vs regulated secretion.
- **Lysosome**: pH ~4.5 kept by **V-ATPase**; ~50 acid hydrolases; receives cargo via **M6P**, plus endocytosis, phagocytosis, autophagy. Low pH is *containment* — leaked enzymes are inactive at cytosolic pH.
- **Lysosomal storage diseases** = substrate accumulation from one missing enzyme; **I-cell disease = missing M6P tag**, so enzymes are secreted rather than delivered.
- **Peroxisomes**: β-oxidation of very-long-chain fatty acids; oxidases make H₂O₂, **catalase** destroys it; proteins import **already folded** via PTS. **Zellweger** = failed import.
- The **endomembrane system** interconverts by budding and fusion; resident proteins are retrieved by retrograde transport.

## Practice questions

**1. A protein is being synthesised and its signal sequence has just emerged from the ribosome. What happens next?**

A. The ribosome finishes translation in the cytosol, then the protein enters the ER
B. SRP binds the signal sequence, translation pauses, and the ribosome is targeted to the rough ER where synthesis resumes into the lumen
C. The protein is transported through a nuclear pore
D. The signal sequence is cleaved by a cytosolic protease

**Answer: B**

Explanation: Targeting is co-translational. SRP recognises the signal sequence and halts elongation until the ribosome docks at the ER's SRP receptor; translation then resumes with the polypeptide threaded through the translocon. Protein cannot enter the ER after full cytosolic synthesis (A), the nuclear pore handles nucleocytoplasmic traffic not ER import (C), and the signal is cleaved inside the ER, not in the cytosol (D).

---

**2. Ribosomes on the rough ER and free ribosomes in the cytoplasm differ in which way?**

A. Bound ribosomes are larger
B. Bound ribosomes are permanently attached and cannot be reused
C. They are the same ribosomes — location depends on whether the emerging protein has a signal sequence
D. Bound ribosomes synthesise only RNA

**Answer: C**

Explanation: Ribosomes are interchangeable; a ribosome becomes ER-bound only when the nascent chain carries a signal sequence recognised by SRP, and it is released after the chain completes. Size, permanence, and product type do not distinguish them — the targeting signal does.

---

**3. Which function is performed by the smooth ER but not by the rough ER?**

A. Folding of secreted proteins
B. Detoxification of drugs and alcohol
C. Glycosylation of lysosomal enzymes
D. Attachment of ribosomes

**Answer: B**

Explanation: Smooth ER carries out lipid and steroid synthesis, drug and alcohol detoxification (cytochrome P450), calcium storage, and glycogen metabolism. Protein folding, glycosylation, and ribosome attachment are rough ER functions — they require the ribosomes and the lumenal environment that only the RER provides.

---

**4. What is the role of mannose-6-phosphate in protein trafficking?**

A. It signals a protein for secretion outside the cell
B. It tags lysosomal enzymes in the Golgi for delivery to lysosomes
C. It marks proteins for degradation in the cytosol
D. It targets proteins to the smooth ER

**Answer: B**

Explanation: In the Golgi, the phosphotransferase adds phosphate to mannose residues of lysosomal hydrolases; M6P receptors at the trans face then package them into vesicles headed for lysosomes. Without the tag, as in I-cell disease, the enzymes are secreted instead — which is why the tag is the delivery system, not the enzyme itself.

---

**5. Why are lysosomal enzymes inactive if they leak into the cytoplasm?**

A. The cytoplasm contains competitive inhibitors
B. They are synthesised in an inactive form only in the lysosome
C. Their optimum pH is acidic, and the cytoplasm is near neutral
D. They have been irreversibly denatured by the lysosomal pH

**Answer: C**

Explanation: The hydrolases are acid hydrolases with optima near pH 4.5–5; at cytoplasmic pH ~7.2 they have little activity. That pH difference is containment — the compartment's acidity is both operating condition and safety mechanism. They are not zymogens requiring activation in the lysosome (B), and D has the causality reversed.

---

**6. Tay–Sachs disease results from accumulation of substrate because of a missing**

A. Proton pump in the lysosomal membrane
B. Mannose-6-phosphate transferase
C. Hexosaminidase A enzyme
D. Peroxisomal import receptor

**Answer: C**

Explanation: Tay–Sachs is a lysosomal storage disease caused by deficient hexosaminidase A, so GM2 ganglioside accumulates in lysosomes — particularly in neurons — and damages them. B would be I-cell disease (targeting failure, not hydrolase failure); A would prevent acidification and impair all hydrolases; D describes Zellweger syndrome.

---

**7. Which pair correctly matches an organelle with its characteristic chemistry?**

A. Lysosome — production of H₂O₂ and its breakdown by catalase
B. Peroxisome — oxidation of very-long-chain fatty acids with H₂O₂ as an intermediate
C. Smooth ER — hydrolysis of proteins at acidic pH
D. Golgi — β-oxidation of fatty acids

**Answer: B**

Explanation: Peroxisomes shorten very-long-chain fatty acids and use oxidases that generate H₂O₂, which catalase immediately decomposes. Lysosomes perform acid hydrolysis, not peroxide chemistry (A); the smooth ER has neither role (C); the Golgi modifies and sorts rather than oxidising fatty acids (D).

---

**8. Zellweger syndrome is best described as**

A. A missing single lysosomal hydrolase
B. A failure to acidify lysosomes
C. A failure to import enzymes into peroxisomes, leaving the organelles empty
D. A defect in the Golgi's M6P tagging

**Answer: C**

Explanation: In Zellweger syndrome peroxisomes assemble but cannot import their matrix enzymes, so the organelle exists without its contents. The consequences — very-long-chain fatty acid accumulation, failed plasmalogens, impaired detoxification — map exactly onto the missing enzymes. A and D are lysosomal diseases; B would be a V-ATPase defect affecting all hydrolases.

---

**9. A liver cell chronically exposed to alcohol shows expanded smooth ER. What is the most likely functional consequence?**

A. Increased secretion of digestive enzymes
B. Increased metabolism of drugs and alcohol, altering drug response
C. Increased lysosomal digestion
D. Increased ribosome production

**Answer: B**

Explanation: Smooth ER houses the cytochrome P450 detoxification system; chronic ethanol exposure induces its expansion, and the enlarged enzyme capacity clears other drugs faster — the mechanism of many drug–alcohol interactions. Digestive enzymes are a rough ER product (A), lysosomal digestion is unrelated (C), and ribosomes come from the nucleolus (D).

---

**10. Why does a cell use regulated rather than constitutive secretion for digestive enzymes?**

A. Regulated secretion is faster at delivering membrane lipids
B. It allows the cell to store enzymes as inactive precursors and release them only on a signal
C. Constitutive vesicles cannot fuse with the plasma membrane
D. Regulated secretion bypasses the Golgi

**Answer: B**

Explanation: Regulated secretion packages cargo into granules held until a specific trigger — so a pancreatic cell can stockpile zymogens safely and discharge them only when the gut signals. That is the whole point: maintenance (constitutive) versus command (regulated). Constitutive vesicles do reach the membrane (C), and both routes pass through the Golgi (D).
