# Immigration Legal Plugin — Command Reference

## Humanitarian & Asylum Workflows

---

### Intake Workflow

/immigration-legal:intake-asylum

Purpose:
Converts humanitarian intake narratives into structured attorney-review summaries.

Outputs:
- issue spotting
- red flags
- missing information
- evidence checklist
- urgency review
- attorney-review notes

---

### Document Collection Workflow

/immigration-legal:document-request-checklist

Purpose:
Generates humanitarian evidence and document request checklists.

Outputs:
- evidence requests
- corroboration requests
- client-facing request summary
- internal attorney notes

---

### Deadline & Procedural Workflow

/immigration-legal:deadline-review

Purpose:
Reviews hearings, filing windows, RFE dates, procedural urgency, and humanitarian timing concerns.

Outputs:
- deadline summary
- urgency review
- missing timeline data
- escalation recommendations

---

### RFE / NOID Workflow

/immigration-legal:draft-rfe-response

Purpose:
Creates structured attorney-review RFE response frameworks.

Outputs:
- issue mapping
- evidence recommendations
- narrative clarification needs
- urgency review
- response structure

---

### Engagement Letter Workflow

/immigration-legal:draft-engagement-letter

Purpose:
Creates humanitarian engagement letter drafts using firm voice and workflow standards.

Outputs:
- draft engagement letter
- scope definition
- fee placeholders
- attorney-review notes

---

## Future Workflows

/immigration-legal:policy-impact
/immigration-legal:review-form
/immigration-legal:client-status-update
/immigration-legal:declaration-interview
/immigration-legal:hearing-prep
/immigration-legal:country-conditions-review
/immigration-legal:credibility-review

---

## Workflow Chain

Humanitarian Intake
↓
Document Request Checklist
↓
Deadline Review
↓
RFE / NOID Response Framework
↓
Attorney Review
↓
Client Communication
↓
Filing Preparation

---

## System Principles

- Human-in-the-loop by design
- Attorneys remain responsible for legal conclusions
- CMS and calendar remain source of truth
- Claude organizes, drafts, summarizes, and flags
- All outputs require attorney review
- Workflows are designed around how immigration work actually moves

### Policy Impact Workflow

/immigration-legal:policy-impact

Purpose:
Reviews how a USCIS, EOIR, DHS, DOS, court, or immigration policy update may affect a specific humanitarian, asylum, TPS, removal defense, or related matter.

Outputs:
- policy/update summary
- matter-specific impact areas
- uncertainty flags
- attorney-review questions
- recommended follow-up
- MatterOS bridge note when broader caseload review may be needed
