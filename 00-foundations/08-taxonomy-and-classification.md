# Taxonomy and Classification

## Core idea

Naming and sorting living things is not bookkeeping. Classification is a set of claims about evolutionary relationships, and the criteria used have changed substantially as evidence improved. Knowing which system is being used — and why — prevents a whole class of exam errors.

## Binomial nomenclature

Every species receives a two-part name, given in Latin or Latinised Greek and written in italics.

```
HOMO SAPIENS
 │      │
Genus   specific epithet
(capitalised)  (lower case)
```

The two parts together name the species. **Genus is always capitalised; specific epithet never is.** The specific epithet alone is meaningless — *sapiens* is not a name, but *Homo sapiens* is.

The system is due to **Carl Linnaeus**, who formalised it in the 18th century. He established the two-name convention and the hierarchical ranks that are still in use.

### Ranks

```
DOMAIN
 └── KINGDOM
      └── PHYLUM (division, in botany)
           └── CLASS
                └── ORDER
                     └── FAMILY
                          └── GENUS
                               └── SPECIES
```

Memorisation device, and its limitation: **Domain Kingdom Phylum Class Order Family Genus Species** — but this is genuinely useful only down to kingdom. Beyond that, ranks are conventions rather than natural quantities.

**Example — a human:**

| Rank | Name |
| --- | --- |
| Domain | Eukaryota |
| Kingdom | Animalia |
| Phylum | Chordata |
| Class | Mammalia |
| Order | Primates |
| Family | Hominidae |
| Genus | *Homo* |
| Species | *Homo sapiens* |

The phylogenetic file names ending in `-a` in the example above — Chordata, Mammalia, Primates, Hominidae — are the convention (though no longer required) for **cladistic** ranks: groups defined by a common ancestor. See 06 — Evolution.

## Two ways to classify

### Linnaean taxonomy

Groups organisms by overall similarity of characteristics, arranged hierarchically. A system of nested bins. Practical and still used for labelling specimens, but it does not by itself indicate evolutionary relationship.

### Phylogenetic systematics (cladistics)

Groups organisms by **shared derived characteristics** — *synapomorphies* — which indicate common ancestry.

```
                          ┌── A
              ┌── trait ───┤
              │            └── B
── ancestor ───┤
              │        ┌── C
              └── trait ┤
                       └── D
```

A **clade** is a group containing an ancestor and *all* of its descendants. Any group that excludes descendants of its common ancestor is **paraphyletic** and is not a valid clade. Any group that includes organisms without a recent common ancestor within the group is **polyphyletic**.

**The critical distinction:**

> **Similarity is not the same as relatedness.**

Convergent evolution produces similar features in organisms that are not closely related. This is the single most important consequence of the shift from Linnaean to phylogenetic classification.

| Convergence | Independent origin of similar traits |
| --- | --- |
| Wings | Bats and birds fly — similar function, but bat wings are skin stretched over elongated fingers and bird wings are modified forelimbs with feathers |
| Eyes | Convergent evolution across many lineages |
| Homeothermy | Evolved independently in mammals and in birds |
| Glucose | As an energy molecule, arrived at independently in several lineages |

**Convergent evolution is the reason the distinction matters clinically.** Eyes evolved separately in vertebrates and cephalopods, so the *structure* is similar but the *development* differs. Convergent traits are an evolutionary fact, not evidence of close relation, and mistaking them for homology is one of the most durable errors in biology.

### Homology and analogy

| Term | Meaning | Example |
| --- | --- | --- |
| **Homolog** | Same underlying structure, different function; inherited from a common ancestor | Human arm, whale flipper, bat wing — the same skeletal plan serving different functions |
| **Analog** | Similar function, different structure and origin | Bird wing and insect wing |

The human forelimb is the standard homology example, and the reason it is such a good one is that the structure is the *same* while the use is entirely different. The functional similarity is real; the anatomical similarity is what carries the evolutionary information.

## The two-domain system

Traditionally, classification used **five kingdoms**: Monera (or Prokaryota), Protista, Fungi, Plantae, Animalia. This has been replaced by **three domains**, based on genetic sequence comparison:

| Domain | Includes | Cell plan |
| --- | --- | --- |
| **Bacteria** | Bacteria | Prokaryotic |
| **Archaea** | Archaea | Prokaryotic |
| **Eukarya** | Animals, plants, fungi, protists | Eukaryotic |

This matters because the three-domain system separates Archaea from Bacteria, which the five-kingdom system did not. The evidence for that separation is described in 06 — Evolution.

The old kingdom Monera lumped Bacteria and Archaea together, which is now understood to be wrong — the two groups differ as much from each other as either differs from eukaryotes.

## Naming and the species problem

**What a species is.** A species is a group of interbreeding natural populations that are reproductively isolated from other such groups. Under this biological species concept, members of one species can produce fertile offspring; members of two different species cannot.

**Where the concept breaks down**, which is worth knowing because these exceptions are routinely examined:

| Case | Problem |
| --- | --- |
| Asexual organisms | Bacteria, many protozoa — no interbreeding occurs at all |
| Hybridisation | Some plant and animal species interbreed and produce fertile hybrids |
| Ring species | *Larus* gull complex — interbreeding varies continuously around the range, so where one species ends and the next begins is genuinely arbitrary |
| Fossils | Cannot be tested for reproductive isolation at all |
| Geographical isolation | Two populations are separated by distance, so they cannot be tested |

For asexual organisms and fossils, the **morphological species concept** — grouping by overall structural similarity — is used instead. Each concept answers a different question, so neither is "wrong"; they are tools for different situations.

**Subspecies and varieties** may be named where a distinct, interbreeding population exists within a species with its own geographic range. The category is used inconsistently, and its boundaries are not set by biology.

## Taxonomic ranks are conventions

Worth being clear about, because students often assume ranks carry fixed amounts of biological difference.

- **Genus** and **species** are well supported by evolutionary evidence.
- Higher ranks are conventions. What actually varies across lineages is **branching order** — the sequence of divergences.
- The number of described species continues to grow with molecular methods, and estimates of the total number of species on Earth differ by orders of magnitude. This is an active area of research, not a settled figure.

## Medical relevance

**Taxonomy determines which organisms are treated as related, and epidemiology follows relationship.** Whether two clinical isolates are considered one outbreak depends on strain-level genetic comparison, not on species-level classification. Tracking mutations to distinguish related transmission chains from coincidental cases is entirely a phylogenetic exercise applied to real data. See [05 — Molecular Biology](../05-molecular-biology/) and [07 — Microbiology](../07-microbiology/).

**Host–parasite relationships are taxonomic questions with clinical consequences.** Whether an organism can cause disease in humans is partly predicted by how closely related it is to organisms already adapted to humans — relatedness predicts shared physiology, which predicts shared susceptibility.

**Antibiotic resistance is tracked as a taxonomic phenomenon.** Resistance genes move between bacteria, sometimes across distant taxa, and the classification of which organism carries which gene determines how transmission chains are inferred.

**Structure predicts function, and function predicts treatment.** Because two clinically similar infections may be caused by organisms in different domains, the reason a particular antimicrobial is chosen follows from the organism's structure. This is the applied version of the homology-versus-analogy distinction: if two organisms have the same target structure, the same drug may act on both, and if the structure is analogous rather than homologous, it may not.

**Common confusion to retire:** "more advanced" or "more evolved" is not a taxonomic category. Every extant organism has been evolving for the same length of time. A parasite living inside a host is as well adapted to its niche as a human is to ours.

## Key facts

- Binomial nomenclature: **Genus (capitalised) + specific epithet (lower case)**, both italicised. Linnaeus.
- Ranks: Domain → Kingdom → Phylum → Class → Order → Family → Genus → Species.
- Three domains: **Bacteria, Archaea, Eukarya**. Archaea are prokaryotic.
- Cladistics groups by **synapomorphies**; a valid **clade** includes an ancestor and all its descendants.
- **Homolog** = same structure, different function. **Analog** = similar function, different origin.
- **Convergent evolution** produces similar traits in unrelated lineages — similarity ≠ relatedness.
- Biological species concept = interbreeding, reproductively isolated. Fails for asexual organisms, fossils, and ring species.

## Practice questions

**1. Which statement about binomial nomenclature is correct?**

A. Both names should be written in capitals for clarity
B. The specific epithet is capitalised and the genus is written in lower case
C. The two names must be the organism's common name in two languages
D. The genus name may be used alone and is always capitalised

**Answer: D**

Explanation: The genus name alone is sufficient and unambiguous — *Homo*, *Homo sapiens*. The genus is always capitalised and italicised; the specific epithet is never capitalised. C is wrong because the name is Latin or Latinised, not a translation of a common name.

---

**2. Two organisms have wings but are not closely related. Their wings have fundamentally different structures. This indicates**

A. They are the same species
B. Convergent evolution, with independently evolved analogous structures
C. They are homologous structures derived from a common ancestor
D. One evolved from the other

**Answer: B**

Explanation: Similar function without shared structural origin indicates convergent evolution, producing analogous structures. The alternative claim — homology — requires the same underlying structure inherited from a common ancestor, which is not the case here. Similarity of function is not evidence of relatedness.

---

**3. The whale flipper and the human forearm are used for different functions but share the same underlying bone arrangement. They are**

A. Homologous structures
B. Analogous structures
C. The result of convergent evolution
D. Unrelated structures

**Answer: A**

Explanation: Same underlying structure inherited from a common ancestor, serving different functions, is the definition of homology. Analogy would require similar function with different structure. The shared skeletal arrangement is the evidence of common ancestry; the differing function shows that evolution has modified the same plan for different purposes.

---

**4. Under the three-domain system, which organisms are classified as prokaryotic?**

A. Archaea only
B. Bacteria only
C. Bacteria, Archaea, and unicellular eukaryotes
D. Bacteria and Archaea

**Answer: D**

Explanation: Both Bacteria and Archaea lack a membrane-bound nucleus and are prokaryotic. Eukarya contains all organisms with a membrane-bound nucleus, including unicellular ones such as yeast and protozoa, so unicellularity does not imply prokaryote. The older five-kingdom system grouped Bacteria and Archaea together as Monera.

---

**5. A group contains a common ancestor and only some of its descendants. This group is**

A. Identical to a class
B. Paraphyletic
C. Polyphyletic
D. A valid clade

**Answer: B**

Explanation: A clade must include an ancestor and all its descendants. Excluding some descendants produces a paraphyletic group, which is a grouping created by human choice rather than a natural evolutionary unit. A polyphyly group includes organisms from different lineages without including their most recent common ancestor. Both are excluded under cladistic principles, which is the point of the method.

---

**6. Why is the biological species concept difficult to apply to bacteria?**

A. Bacteria cannot be cultured in the laboratory
B. Bacteria are not classified into species
C. Bacteria reproduce asexually, so interbreeding and reproductive isolation cannot be assessed
D. Bacteria have too many chromosomes

**Answer: C**

Explanation: The biological species concept depends on whether individuals can interbreed and produce fertile offspring. Bacteria divide by binary fission and also exchange DNA horizontally, so the reproductive-isolation test cannot be applied; genetic sequence comparison is used instead. A is false — bacteria are routinely cultured. B is false — bacteria are classified into species and given binomial names like any other organism. D is incorrect.

---

**7. Two species of gull in a ring around the pole interbreed with their neighbours, with the degree of interbreeding changing gradually. The difficulty this creates is that**

A. The gulls are all one species
B. There is no objective boundary between one species and the next, since reproductive isolation varies continuously
C. The gulls cannot be identified at all
D. Reproductive isolation is impossible in gulls

**Answer: B**

Explanation: A ring species is a genuine and instructive case. Reproductive isolation between adjacent populations varies gradually rather than switching abruptly, so any line drawn between species is a convention rather than a discovered fact. This shows the limitation of the biological species concept, not a failure of the birds. A, C, and D each overstate or misdescribe the situation.

---

**8. Which statement about the relationship between classification and evolutionary history is correct?**

A. Classification is a set of hypotheses about evolutionary relationships, supported by evidence such as genetic sequences
B. Taxonomic ranks such as class and order correspond to fixed amounts of evolutionary divergence
C. The species category is the only one with a clear definition, and higher ranks are entirely arbitrary
D. Classification is based purely on physical resemblance, which reliably reflects ancestry

**Answer: A**

Explanation: Classification is testable. Genetic sequence comparison is what revised the five-kingdom system into the three-domain system and revealed Archaea as a separate lineage. C is wrong because ranks are conventions; what varies is branching order. D is half true and half misleading — species is well defined, but calling higher ranks "entirely arbitrary" understates the evidence behind groupings such as chordates.

---

**9. A patient is treated with a drug that disrupts 70S ribosomes and later develops a condition affecting cardiac and skeletal muscle. What explains the adverse effect?**

A. Muscle cells contain 70S ribosomes instead of 80S
B. Muscle cells are prokaryotic
C. Mitochondria in muscle cells contain 70S ribosomes, so drug-induced interference with them impairs oxidative phosphorylation and ATP production
D. The drug degraded the muscle proteins directly

**Answer: C**

Explanation: Human cytosolic ribosomes are 80S, so they are not affected, but mitochondria retain bacterial-type 70S ribosomes — a consequence of their endosymbiotic origin. Inhibiting them impairs mitochondrial protein synthesis, which reduces oxidative phosphorylation in ATP-demanding tissue. That explains why cardiac and skeletal muscle are the tissues affected: they have the highest energy demand. A and D are false; muscle cells are eukaryotes with 80S cytosolic ribosomes.

---

**10. Two clinically similar infections are caused by organisms in different domains. Why is it not automatically appropriate to use the same antimicrobial for both?**

A. The antimicrobial's target structure may be present in one organism and absent from the other
B. The organisms will have different names
C. Antibiotics only work on bacteria, so this is irrelevant
D. Different domains cannot be treated at all

**Answer: A**

Explanation: Antimicrobials act on specific structures — a cell wall, a ribosome type, a particular enzyme. If a target exists in one organism but not the other, the same drug will not act on both, and taxonomy is what predicts that difference. This is the homology-versus-analogy distinction applied to treatment: shared structure predicts shared drug susceptibility. C and D are false.