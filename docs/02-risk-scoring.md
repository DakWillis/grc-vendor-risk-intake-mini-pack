# Risk Scoring (Simple Model)

## Scoring fields (1–5)
- Data sensitivity (1=public, 5=regulated/PII/PHI)
- Access level (1=no access, 5=admin/production access)
- Business criticality (1=nice to have, 5=mission critical)
- Compliance impact (1=none, 5=high regulatory exposure)
- Vendor maturity (1=strong controls, 5=unknown/weak controls)

## Risk score
Total Score = sum of fields (max 25)

## Tiers
- 5–10: Low
- 11–17: Medium
- 18–25: High

## Decision guidance
- Low: approve with basic terms and minimal evidence
- Medium: approve with standard evidence and contract clauses
- High: require strong evidence + security terms; consider alternatives if gaps exist
