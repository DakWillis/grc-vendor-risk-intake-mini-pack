# Control Mapping (Lightweight)

This mapping shows how the vendor risk intake workflow supports common control expectations (framework-agnostic).
Use it to communicate traceability from risk → control → evidence → decision.

## Mapping table

| Intake Area | Control Intent | Evidence Collected | Output Artifact |
|---|---|---|---|
| Vendor identification | Know who you’re engaging and why | Vendor name, service description, business owner | `artifacts/vendor-intake-form.md` |
| Data classification | Understand data sensitivity and regulatory exposure | Data categories (PII/PHI/PCI), retention | `artifacts/vendor-intake-form.md` |
| Access & integration | Restrict access and manage integration risk | Access level, systems integrated, auth method | `artifacts/vendor-intake-form.md` |
| Due diligence | Verify vendor security posture | SOC2/ISO, policies, pen test summary, VM summary | `artifacts/evidence-request-checklist.md` |
| Incident readiness | Ensure vendor can notify/respond | Incident notification SLA, IR summary | `artifacts/evidence-request-checklist.md` |
| Business continuity | Confirm service resilience | BCP/DR summary, RTO/RPO | `artifacts/evidence-request-checklist.md` |
| Decision + accountability | Document approval and conditions | Decision record, conditions, reviewer | `artifacts/vendor-decision-log.csv` |
| Review cadence | Reassess vendors periodically | Next review date, trigger on material change | `docs/01-workflow.md` + decision log |

## Notes
- For higher-risk vendors, attach contract/security requirements and track evidence completion before go-live.
- Material changes that should trigger re-review: data scope change, new integration, acquisition, major incident, new subprocessors.
