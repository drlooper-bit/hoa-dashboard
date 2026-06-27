# Hypothesis Validation — Strategic Execution Plan
## Towncryer.biz / Plantation at Leesburg HOA

## 1. Strategic Goal
Produce a binary determination: **PROVEN / UNPROVEN / REFUTED** for the hypothesis that:
> Plantation HOA authorized a $42,300/month golf-course draw, but transfers were systematically omitted from the HOA Balance Sheet and misclassified as LLC revenue. The Jan 2025 article alleges an excess draw of $92,300 (vs $42,300 authorized) and $136,522 in total irregularities.

## 2. Execution Phases (Dependency Chain)

### Phase 1: Evidence Inventory
Map all extracted documents on-hand.
- Path: `D:\HOA\PLA_Financials_extracted\`
- Output: indexed file manifest with dates, types, readability

### Phase 2: Routine Draw Verification
Prove/refute: $42,300/month routine draw is recorded as HOA contra-revenue.
- Required: Jan 2026 and Apr 2026 consolidated statements (account 400109)
- Gate: If missing, re-extract from source PDFs

### Phase 3: FY2024 Transfer Verification
Prove/refute: $695,271.77 transferred FY2024 with no HOA balance sheet entry.
- Required: `golf-course-llc.txt`, audited 2024 statements
- Gate: Cross-check entity definition vs Balance Sheet

### Phase 4: Jan 2025 Excess Draw Verification
Prove/refute: $92,300 Jan 2025 draw, $50,000 excess.
- Required: Jan 2025 monthly statement
- Current status: GAP (binary extraction failure)
- Gate: If file unreadable, attempt re-extraction or seek alternate source

### Phase 5: SPA Root Tracing
Prove/refute: $50k excess sourced from improper 2023/2021 SPA balances.
- Required: Detailed SPA line items from extracted financials index
- Gate: If index truncated, pull full SPA schedule

### Phase 6: Gap Triage & Final Determination
- Aggregate verified vs unverified claims
- Weight evidence by source reliability (audited > extracted > blog)
- Decision: PROVEN / UNPROVEN / REFUTED for each claim component

## 3. Current State (from dashboard)
| Component | Status |
|------------|--------|
| Routine Draw | VERIFIED |
| FY2024 Transfer Total | VERIFIED |
| FY2024 Net Deficit Pattern | VERIFIED |
| Jan 2025 Excess Draw | GAP |
| SPA Root | GAP |
| Overall | IN_REVIEW |

## 4. Dependencies
- Local file access: `D:\HOA\` — ACTIVE
- Blog source: towncryer.biz — PENDING FETCH
- PDF re-extraction: available if needed
- Google Drive upload: DEFERRED (local-only)

## 5. Next Action
Execute Phase 1 (Evidence Inventory) immediately.
