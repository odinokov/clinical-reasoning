# Pharmacogenomics Reference

Use this reference when the query involves gene-drug interactions, specific CYP or HLA variants, or PGx-guided dosing.

---

## Principles

- **PGx changes dosing, selection, or monitoring for specific drug-gene pairs** — not all medications have actionable PGx data.
- **Genotype predicts phenotype, but not perfectly** — drug interactions, organ function, and other factors modify the relationship.
- Use **CPIC (Clinical Pharmacogenetics Implementation Consortium)** and **DPWG (Dutch Pharmacogenomic Working Group)** as primary sources; FDA PGx labels as regulatory reference.
- Flag clinically actionable findings explicitly — not every variant is actionable.

---

## CYP2C19

Key substrates: clopidogrel, PPIs, citalopram/escitalopram, voriconazole, some SSRIs, sertraline, tricyclics.

### Phenotype categories
- **Ultra-rapid metabolizer (UM):** *1/*17, *17/*17
- **Rapid metabolizer (RM):** *1/*17
- **Normal metabolizer (NM):** *1/*1
- **Intermediate metabolizer (IM):** *1/*2, *1/*3
- **Poor metabolizer (PM):** *2/*2, *2/*3, *3/*3

### Actionable implications

**Clopidogrel** (prodrug requiring CYP2C19 activation):
- IM/PM: reduced active metabolite → reduced platelet inhibition → increased thrombotic risk, especially after PCI
- Consider alternative antiplatelet (prasugrel, ticagrelor) in PM after PCI
- FDA boxed warning references PM status

**PPIs** (CYP2C19 substrates, reverse implication):
- PM: higher drug exposure, stronger acid suppression, potentially better H. pylori eradication
- UM: lower exposure, may require higher dose or alternative agent

**Voriconazole:**
- PM: elevated levels, toxicity risk
- UM: subtherapeutic levels, treatment failure risk
- Therapeutic drug monitoring supplements but does not replace PGx consideration

**Citalopram / escitalopram:**
- PM: reduced metabolism, increased QT prolongation risk, dose cap recommended
- UM: may need higher dose or alternative

---

## CYP2D6

Key substrates: codeine, tramadol, hydrocodone, oxycodone (partial), tamoxifen, many antidepressants (paroxetine, fluoxetine, venlafaxine, tricyclics), antipsychotics (risperidone, aripiprazole, haloperidol), atomoxetine, metoprolol.

### Phenotype categories
Based on activity score summing allele values:
- **Ultra-rapid metabolizer (UM):** score >2.25 (gene duplications on active alleles)
- **Normal metabolizer (NM):** score 1.25–2.25
- **Intermediate metabolizer (IM):** score 0.25–1.25
- **Poor metabolizer (PM):** score 0

### Actionable implications

**Codeine and tramadol** (prodrugs activated by CYP2D6 to morphine / O-desmethyltramadol):
- UM: excessive conversion → toxicity, respiratory depression (deaths reported in children, post-tonsillectomy)
- PM: inadequate analgesia
- **FDA contraindicates codeine in children <12 and after T&A in children <18**; caution in breastfeeding mothers (infant respiratory depression from morphine in breast milk)
- Avoid both agents in UM; avoid in PM for efficacy reasons

**Tamoxifen** (prodrug activated to endoxifen):
- PM: reduced endoxifen, potentially reduced efficacy in breast cancer
- Avoid strong CYP2D6 inhibitors (e.g., paroxetine, fluoxetine) in patients on tamoxifen
- Routine PGx testing for tamoxifen is not standard; conflicting evidence on outcomes

**Antidepressants (TCAs, paroxetine, fluoxetine, venlafaxine):**
- PM: higher exposure, more side effects, consider dose reduction or alternative
- UM: lower exposure, consider alternative agent

**Antipsychotics (risperidone, aripiprazole):**
- PM: higher exposure, dose reduction recommended

---

## CYP2C9 and VKORC1

Key substrates: warfarin, NSAIDs (celecoxib, ibuprofen, naproxen), phenytoin, losartan, sulfonylureas.

### Warfarin
- **CYP2C9 *2, *3** → reduced warfarin metabolism → lower dose requirement
- **VKORC1 -1639G>A** → increased warfarin sensitivity → lower dose requirement
- Combined genotype explains significant dose variability; online dosing algorithms incorporate both
- **DOACs are largely replacing warfarin**; PGx-guided warfarin dosing is most relevant where DOAC unsuitable (mechanical valves, antiphospholipid syndrome, severe CKD)

### Phenytoin
- CYP2C9 IM/PM: higher exposure at standard dose, increased toxicity risk, consider lower starting dose

---

## CYP3A4/5

Key substrates: tacrolimus, cyclosporine, many statins (simvastatin, atorvastatin, lovastatin), calcium channel blockers, midazolam, many chemotherapy agents.

### Tacrolimus
- **CYP3A5 expressers (CYP3A5*1)** → higher metabolism → require higher dose to achieve target trough
- **CYP3A5 non-expressers (*3/*3)** → require lower dose
- Target trough still guides therapy; PGx informs starting dose

---

## TPMT and NUDT15

Key substrates: azathioprine, mercaptopurine, thioguanine (thiopurines).

### Actionable implications
- **TPMT low/deficient activity or variant:** excessive 6-TGN accumulation → severe myelosuppression, life-threatening
- **NUDT15 variants** particularly relevant in East Asian, Hispanic, and South Asian populations; missed by TPMT testing alone
- **CPIC recommends both TPMT and NUDT15 testing before starting thiopurines**
- Dose reduction or alternative agent based on phenotype

---

## DPYD

Key substrates: 5-fluorouracil, capecitabine, tegafur.

### Actionable implications
- **DPYD variants (*2A, *13, D949V, HapB3)** → reduced DPD activity → severe 5-FU/capecitabine toxicity (myelosuppression, mucositis, hand-foot, death)
- European regulators (EMA) and increasingly U.S. practice recommend pre-treatment DPYD screening
- Dose reduction (25–50% or avoidance) based on genotype
- Even heterozygous variants can cause severe toxicity; family screening relevant

---

## UGT1A1

Key substrates: irinotecan, raltegravir, atazanavir.

### Actionable implications
- **UGT1A1*28** (Gilbert syndrome variant, 7TA repeat): reduced glucuronidation
- Increased irinotecan toxicity risk (neutropenia, diarrhea) in homozygotes
- Dose reduction considered in *28/*28; no action typically needed for indirect hyperbilirubinemia from Gilbert syndrome alone

---

## HLA alleles

Pharmacogenetically relevant HLA alleles identify patients at high risk for severe cutaneous and systemic reactions.

### HLA-B*57:01 — abacavir
- Abacavir hypersensitivity reaction (fever, rash, GI, respiratory, can be fatal on rechallenge)
- **HLA-B*57:01 testing is required before starting abacavir**; positive → do not use
- NNT to prevent one HSR reaction with screening ~13

### HLA-B*15:02 — carbamazepine, oxcarbazepine, phenytoin
- SJS/TEN risk strongly associated, particularly in patients of Han Chinese, Thai, Malay, Filipino, and other Southeast Asian ancestry
- **FDA recommends HLA-B*15:02 testing before starting carbamazepine in patients of these ancestries**
- Positive → avoid carbamazepine, oxcarbazepine, phenytoin; lamotrigine also has some risk
- HLA-A*31:01 is an additional risk allele for carbamazepine hypersensitivity in broader populations

### HLA-B*58:01 — allopurinol
- SJS/TEN risk; higher frequency in Han Chinese, Thai, Korean populations
- Consider testing before starting allopurinol, especially in high-risk ancestries
- Positive → febuxostat is an alternative (check for CV comorbidity)

### HLA-B*13:01 — dapsone
- Dapsone hypersensitivity syndrome risk

### HLA-B*15:11, HLA-DRB1*07:01 — various
- Emerging associations with specific drug reactions

---

## G6PD deficiency

Not an HLA or CYP variant but a common enzyme deficiency with clinically actionable drug implications.

Drugs causing hemolysis in G6PD-deficient patients:
- **High-risk:** dapsone, primaquine, methylene blue (high dose), rasburicase, nitrofurantoin, fava beans
- **Moderate risk:** sulfonamides (some), quinolones (some)
- **Lower but real risk:** aspirin (high dose), vitamin K (high dose)

Screen before rasburicase for tumor lysis syndrome. Screen before primaquine / tafenoquine for malaria.

---

## CYP1A2 and caffeine / theophylline / clozapine

- Smoking induces CYP1A2; patients who stop smoking may have dramatic increase in exposure to clozapine, theophylline
- Monitor and consider dose adjustment around smoking cessation

---

## Thiopurine methyltransferase in practice

Combined **TPMT + NUDT15** phenotyping is now CPIC standard before starting thiopurines. Severe myelosuppression can occur within weeks of initiation in variant carriers who don't have dose adjustment.

---

## Caveats

- **Phenoconversion:** drug-drug interactions can convert a genotypic NM to phenotypic IM (e.g., strong CYP2D6 inhibitors make everyone act like PMs)
- **Organ function** (especially renal and hepatic) affects drug exposure independently of genotype
- **Age-related changes** in enzyme expression
- **Ethnicity-specific allele frequencies** mean testing panels should be comprehensive
- **PGx testing is rarely emergent**; don't hold critical therapy for PGx if alternatives are unavailable and the patient urgently needs the drug

---

## When to recommend PGx testing

Consider when:
- Prescribing a drug with well-established actionable PGx pair
- Patient has had unexpected severe adverse reaction to a prior drug
- Family history of drug reactions
- Planning long-term therapy where optimization matters (antidepressants, antiplatelets, chemotherapy)
- Specific ancestry with known HLA risk for a contemplated drug

PGx is NOT typically indicated as a routine screen absent a clinical scenario.
