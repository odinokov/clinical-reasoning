# Clinical Reasoning — A Claude Skill

Attending-level clinical reasoning for Claude.

## What it does

Loaded into Claude, this skill triggers automatically on medical queries and produces structured responses with:

- Formal problem representation + acuity / red-flag screening
- Structured probabilistic reasoning (pretest probability → test characteristics → qualitative posttest shift)
- Evidence-graded workup and treatment recommendations
- Assay-pitfall-aware lab interpretation
- Actionable pharmacogenomic guidance (CYP, HLA, TPMT/NUDT15, DPYD, G6PD)
- Clinical communication drafts (SOAP, SBAR, consult, patient-friendly)

## Structure

```
clinical-reasoning/
├── SKILL.md                              # Core method, safety rules, router
└── references/
    ├── diagnostic-workup.md              # Differential + workup
    ├── therapeutic-framework.md          # Drug selection, dosing, interactions
    ├── prognostic-scoring.md             # Validated risk scores
    ├── lab-imaging-interpretation.md     # Assay pitfalls, trend reasoning
    ├── prevention-screening.md           # USPSTF, ACIP, SDM
    ├── cross-cutting-domains.md          # Ethics, equity, quality/safety
    ├── communication-formats.md          # SOAP, SBAR, patient-friendly
    ├── research-appraisal.md             # Study critique
    └── pharmacogenomics.md               # Gene-drug pairs
```

## ⚠️ Disclaimer

**Not a medical device. Not a substitute for a qualified clinician.** Outputs must be reviewed by a licensed provider with full patient context before any clinical action. Not cleared by FDA, EMA, or any regulatory body. No warranty or liability. If deployed in clinical workflows, the operator is responsible for clinician oversight, privacy compliance (HIPAA/GDPR/PDPA), and regulatory review.

Guidelines and evidence change. The skill flags uncertainty, but always cross-check against current authoritative sources.

## License

MIT
