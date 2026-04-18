# Branch B — Therapeutic Framework

Use this reference when the query concerns drug selection, dosing, interactions, monitoring, or treatment strategy.

---

## # Treatment framework

Organize options by tier. Include only tiers applicable to the clinical question:

- **First-line** — preferred based on efficacy, safety, guideline support
- **Second-line** — when first-line is contraindicated, ineffective, or not tolerated
- **Third-line / refractory** — for treatment-resistant disease
- **Adjunctive / supportive** — given alongside disease-modifying therapy
- **Empiric** — before diagnostic confirmation, based on most likely pathology
- **Maintenance** — long-term continuation after induction or remission
- **Palliative / comfort-directed** — when goals prioritize symptom relief
- **Off-label** — label explicitly; note the accepted indication
- **Investigational** — label explicitly; note trial phase if known

---

## For each intervention

Document:

### Therapeutic role and goal
Classify as:
- **Curative** (e.g., antibiotic for bacterial infection)
- **Disease-modifying** (e.g., DMARD, statin)
- **Symptom control** (e.g., analgesic, antiemetic)
- **Prophylactic** (e.g., DVT prophylaxis, secondary prevention)

### Mechanism of action
Molecular target, pathway, and downstream effect. Name the receptor, enzyme, or process.

### Pharmacokinetics (when clinically decisive)
- Absorption (bioavailability, food effect)
- Distribution (Vd, protein binding if relevant)
- Metabolism — especially CYP substrate status (1A2, 2B6, 2C9, 2C19, 2D6, 2E1, 3A4/5), UGT, phase II
- Elimination route (renal, hepatic, biliary, fecal)
- Half-life and time to steady state
- Active metabolites

### Clinical use case
Indication, line of therapy, target population.

### Evidence basis
Classify as:
- **Guideline-supported** (specify issuing society and year only if confident)
- **RCT-supported** (note effect size with confidence interval when known)
- **Observational** (cohort, case-control, registry)
- **Expert-consensus**
- `[uncertain — verify]`

Include GRADE certainty when known (high / moderate / low / very low).

### Quantitative benefit (when confident)
- Absolute risk reduction (ARR)
- Number needed to treat (NNT)
- Effect size with confidence interval
- On **patient-important outcomes**, not surrogates alone

### Major risks and adverse effects
Include NNH for serious events when known. Distinguish:
- Common mild effects
- Uncommon serious effects
- Rare life-threatening effects

### Black-box warnings and REMS requirements
When applicable, name the specific warning and REMS program requirements (e.g., clozapine monitoring, isotretinoin iPLEDGE, TNF-α inhibitor hepatitis B/TB screening).

### Contraindications
Distinguish **absolute** (do not use) from **relative** (use with caution or enhanced monitoring).

### Drug-drug interactions
Key categories to screen:
- **CYP inducers** (rifampin, phenytoin, carbamazepine, St John's wort)
- **CYP inhibitors** (azoles, macrolides, protease inhibitors, grapefruit juice, SSRIs)
- **P-glycoprotein** substrates/inhibitors
- **QT-prolonging** stacking (macrolides, fluoroquinolones, methadone, antipsychotics, ondansetron)
- **Serotonergic overlap** (SSRIs, SNRIs, MAOIs, triptans, tramadol, linezolid, methylene blue)
- **Bleeding risk stacking** (anticoagulants, antiplatelets, NSAIDs, SSRIs)
- **Potassium** (ACEi/ARB + K-sparing diuretic + NSAID + trimethoprim)

### Drug-disease interactions
- Renal: which agents accumulate, which need dose reduction, which are contraindicated
- Hepatic: which need adjustment by Child-Pugh class
- Cardiac: QT prolongation, negative inotropy, AV nodal blockade
- Psychiatric: serotonergic burden, anticholinergic burden, lowering seizure threshold

### Pharmacogenomic considerations
Include when established gene-drug pairs apply. See `references/pharmacogenomics.md` for full list. Common actionable pairs:
- CYP2C19 → clopidogrel, PPIs, voriconazole, citalopram
- CYP2D6 → codeine, tramadol, tamoxifen, many SSRIs, atomoxetine
- HLA-B*57:01 → abacavir
- HLA-B*15:02 → carbamazepine, oxcarbazepine, phenytoin
- HLA-B*58:01 → allopurinol
- TPMT / NUDT15 → thiopurines (azathioprine, mercaptopurine)
- DPYD → fluoropyrimidines (5-FU, capecitabine)
- G6PD → oxidant drugs (dapsone, primaquine, rasburicase, nitrofurantoin)
- UGT1A1 → irinotecan

### Monitoring requirements
- Baseline labs or tests required before initiation
- On-therapy monitoring (labs, drug levels, EKG, imaging)
- Intervals (e.g., weekly × 4, then monthly, then every 3 months)
- Response markers

### Escalation, switching, combination, discontinuation triggers
- When to add a second agent
- When to switch
- When to increase dose
- When to stop (completion, futility, toxicity, patient preference)

### Duration of therapy
- Defined duration (e.g., 7-day antibiotic course)
- Indefinite with reassessment triggers
- Lifelong

---

## # Management modifiers

Adjust management based on patient factors:

### Age
- **Pediatric:** weight-based dosing (mg/kg with max), developmental pharmacokinetics, age-specific contraindications (tetracyclines <8yr, fluoroquinolones, aspirin and Reye)
- **Geriatric:** deprescribing framework, Beers criteria (potentially inappropriate meds), STOPP/START criteria, frailty-informed dosing, anticholinergic and sedative burden

### Pregnancy / lactation
- Teratogenicity (avoid category X absolutely; reassess prior D categories individually)
- Trimester-specific risk (e.g., ACEi/ARB second-third trimester)
- Transfer into breast milk (consult LactMed)
- Known safe alternatives for common conditions

### Renal impairment
- Specify eGFR or CrCl threshold triggering adjustment
- Distinguish **Cockcroft-Gault CrCl** (for drug dosing labels) from **CKD-EPI eGFR** (for CKD staging)
- Agents to avoid entirely (e.g., nitrofurantoin at CrCl <30, metformin at eGFR <30)
- Dialysis considerations (dialyzable vs not, supplemental dosing after HD)

### Hepatic impairment
- Child-Pugh class thresholds (A: 5–6, B: 7–9, C: 10–15)
- Agents requiring dose reduction (e.g., benzodiazepines except lorazepam/oxazepam/temazepam)
- Agents to avoid (most NSAIDs, some statins at advanced stages)

### Immunosuppression
- Live vaccine avoidance (MMR, varicella, zoster live, yellow fever, BCG, oral typhoid, rotavirus in household contacts)
- Opportunistic infection screening and prophylaxis (PJP, CMV, TB, hepatitis B reactivation)
- Dose implications for concurrent infection risk

### Frailty / performance status
- ECOG 0–4
- Karnofsky Performance Scale 0–100
- Clinical Frailty Scale 1–9
- Cancer therapy and other high-toxicity regimens typically require ECOG ≤2

### Comorbidities
Common adjustments for HF, COPD, CKD, cirrhosis, psychiatric illness, seizure disorder.

### Allergy history
- Distinguish **true IgE-mediated allergy** from **intolerance** (e.g., GI upset) and **non-immediate reactions** (rash)
- Cross-reactivity:
  - Penicillin–cephalosporin: historically overstated; risk is ~1–2% with same R1 side chain; lower with different side chain
  - Penicillin–carbapenem: very low
  - Sulfonamide antibiotics–non-antibiotic sulfonamides: no reliable cross-reactivity
- Skin testing and graded challenge for uncertain labels

### Prior treatment failure or known resistance
Specify prior regimens, response/failure pattern, known resistance mechanisms.

### Severe / fulminant / refractory disease
Name the threshold (e.g., severe UC = Truelove-Witts, severe asthma = step 4+ failure, refractory depression = ≥2 adequate trials).

---

## # Antimicrobial stewardship

Activate for infection-related therapeutic queries.

- **Likely pathogens** by syndrome, patient population, and local epidemiology
- **Empiric regimen** with explicit spectrum justification (don't over-broaden; don't under-cover MDR risk)
- **De-escalation plan** triggered by culture/susceptibility results
- **Duration** with stop criteria (e.g., uncomplicated cystitis 3–5d, uncomplicated CAP 5d, VAP 7d, left-sided endocarditis 4–6wk)
- **Source control** requirements (drainage, debridement, device removal)
- **IV-to-PO transition criteria:** clinical improvement, afebrile, tolerating PO, functioning GI tract, oral agent with adequate bioavailability
- **Allergy-directed alternatives** before labeling patient penicillin-allergic for life
- **Stewardship checkpoints:** 48–72h reassessment for all inpatient antibiotics

---

## Reminder: patient-important outcomes

Before recommending any therapy, ask:
- Is the evidence based on a **patient-important outcome** (mortality, QoL, hospitalization, functional status) or a **surrogate** (lab value, imaging change, biomarker)?
- If surrogate only, flag explicitly.
