# Research Appraisal and Evidence Interpretation

Use this reference when the query involves study critique, evidence appraisal, or interpreting published literature.

---

## Framework for appraising a study

### 1. Study design classification
Name the design and its appropriateness for the clinical question:

- **Therapeutic questions** → RCT is gold standard; observational if RCT infeasible
- **Diagnostic questions** → cross-sectional diagnostic accuracy study with reference standard; ideally in a representative population
- **Prognostic questions** → prospective cohort with long follow-up
- **Harm questions** → often RCT impossible; use cohort, case-control, or pharmacovigilance
- **Prevalence / incidence** → population-based cross-sectional or cohort
- **Screening questions** → RCT with patient-important outcomes (not just detection rate)
- **Mechanistic** → bench, translational, phase 1/2

Common study design hierarchy (for therapeutic questions):
Systematic review of RCTs → RCT → non-randomized controlled study → cohort → case-control → cross-sectional → case series → case report → expert opinion.

### 2. Population
- **Inclusion criteria**
- **Exclusion criteria**
- **Actual characteristics of enrolled participants**
- **External validity / generalizability** — do these results apply to your patient?

Red flags:
- Trial population much healthier, younger, or less comorbid than real-world patients
- Exclusion of pregnancy, pediatrics, elderly, comorbidities limits applicability
- Race, ethnicity, sex, geographic representation

### 3. Intervention and comparator
- Is the intervention clearly described and reproducible?
- Is the comparator appropriate? (placebo, active control, standard-of-care, historical control)
- Equipoise between arms?
- Dose, route, duration match real-world use?

Red flags:
- Placebo comparator when an established active treatment exists (may be unethical and uninformative for practice)
- Suboptimal comparator dosing
- Co-interventions differing between groups

### 4. Outcomes
- **Primary vs secondary** — the study is powered for the primary; secondary findings are hypothesis-generating
- **Patient-important vs surrogate** — mortality, function, QoL, hospitalization, return to baseline vs lab values, imaging, biomarkers
- **Composite outcomes** — interpret carefully; a significant composite may be driven entirely by its softest component
- **Time to event** vs **point prevalence** vs **binary**
- **Pre-specified vs post-hoc** — post-hoc analyses are hypothesis-generating only

Red flags:
- Surrogate primary outcome where patient-important outcome was measurable
- Composite heavily weighted by least-important component
- Outcome switching (primary changed mid-trial)
- Multiple comparisons without correction

### 5. Effect size and precision
- **Effect size** with **confidence interval**
- **Absolute risk reduction (ARR)**, **relative risk reduction (RRR)**, **NNT / NNH**
- **Hazard ratio** with 95% CI for time-to-event
- **Odds ratio** vs **risk ratio** — OR approximates RR only when outcome is rare

Discipline:
- NEVER quote RRR without ARR and baseline risk
- NEVER quote effect size without CI when available
- Wide CI → imprecision

### 6. Risk of bias
Per Cochrane RoB 2 and similar frameworks:

- **Selection bias** — randomization adequate? allocation concealment? baseline balance?
- **Performance bias** — blinding of participants and providers
- **Detection bias** — blinding of outcome assessors
- **Attrition bias** — completeness of follow-up, handling of missing data, ITT vs per-protocol
- **Reporting bias** — selective outcome reporting, compare to registered protocol
- **Publication bias** — positive studies more likely to be published; funnel plot asymmetry

For observational studies, also consider:
- **Confounding** — measured, unmeasured, residual after adjustment
- **Selection** — how subjects entered the cohort
- **Information bias** — recall, misclassification
- **Reverse causation** — especially for cross-sectional associations
- **Time-related biases** — immortal time bias, lead time bias, length bias

### 7. Generalizability limitations
Does the population, intervention, comparator, and outcome match the patient and clinical situation?
- Efficacy (tight protocol) vs effectiveness (real-world) gap
- Specialist center vs general practice
- Short follow-up vs chronic disease management
- Surrogate outcome success vs clinical benefit

### 8. Integration with existing evidence
- Is this consistent with prior studies, meta-analyses, or guidelines?
- Does it replicate or contradict prior work?
- Is there a systematic review or meta-analysis to contextualize?
- Is the totality of evidence now shifting, or is this one discrepant finding?

### 9. Does it change practice?
The ultimate question:
- Does this change the expected balance of benefits vs harms for a specific patient or population?
- Does it change guideline-level recommendations?
- Is effect size clinically meaningful (not just statistically significant)?
- Is there a feasible, affordable way to implement the finding?

---

## Common statistical pitfalls

### P-value worship
- P < 0.05 does not mean the effect is clinically meaningful
- P > 0.05 does not prove no effect (could be underpowered)
- P-value is a function of both effect size and sample size

### Relative vs absolute
A 50% relative risk reduction sounds dramatic. If it's 2% → 1%, the absolute reduction is 1% and NNT = 100.

### Non-inferiority and equivalence
- **Non-inferiority margin** must be pre-specified and clinically reasonable
- Shows new treatment is not unacceptably worse — does not show it's better
- Easy to pass with poor trial conduct (missing data, sloppy outcomes)

### Surrogate outcomes
- HbA1c does not always equal microvascular/macrovascular outcomes (ACCORD, ADVANCE)
- LDL cholesterol reduction does not always equal CV mortality (torcetrapib, niacin)
- Ejection fraction does not always equal mortality
- Every surrogate needs validated linkage to the patient-important outcome

### Subgroup analyses
- Rarely pre-specified and powered
- Multiple comparisons inflate false-positive rate
- Significance in a subgroup without overall trial significance is almost always hypothesis-generating only
- Credibility increases if biologically plausible, pre-specified, consistent with prior data, with significant interaction p-value

### Post-hoc analyses
Exploratory only. Cannot be used to change the study's conclusions.

### Multiple comparisons
When many outcomes are tested, the probability of at least one false-positive increases. Correct with Bonferroni, false discovery rate, or pre-specification of primary outcome.

### Time-to-event and proportional hazards
- Hazard ratio assumes proportionality over time; check with log-log plot or Schoenfeld residuals
- Median survival vs long-tail survival (HR may understate benefit for patients who benefit durably)

### Intention-to-treat vs per-protocol
- ITT preserves randomization, estimates **effectiveness**
- Per-protocol estimates **efficacy** under ideal adherence
- Non-inferiority trials: present both; ITT alone can falsely support non-inferiority if many participants don't receive the treatment

### Missing data
- Amount (<5% usually fine, >20% concerning)
- Pattern (MCAR, MAR, MNAR)
- Handling (complete case, LOCF, multiple imputation)

### Regression to the mean
Extreme values on first measurement tend to be less extreme on repeat, independent of any intervention. Common trap in uncontrolled before-after studies.

---

## Reporting the appraisal

Structure your output:

1. **The clinical question this study addressed** (PICO if therapeutic: Population, Intervention, Comparator, Outcome)
2. **Study design and its appropriateness**
3. **Key findings with effect size and CI**
4. **Risk of bias assessment**
5. **Generalizability**
6. **How this does or does not change current practice**
7. **What remains uncertain / what further research is needed**

End with an explicit answer: Does this change what I would recommend for this patient? Why or why not?
