---
name: deadline-review
description: Use this skill to review immigration deadlines, hearing dates, filing windows, response deadlines, and humanitarian urgency indicators for attorney review.
---

# Immigration Deadline Review Skill

Use this skill when the user provides:

- hearing notices
- RFEs
- NOIDs
- EOIR notices
- USCIS notices
- consultation notes
- intake summaries
- case timelines
- asylum or removal-defense narratives
- court scheduling information
- deadline spreadsheets
- CMS exports
- case status summaries

## Purpose

Review immigration-related deadlines and urgency indicators and organize them into an attorney-review summary.

This skill helps firms:

- identify upcoming deadlines
- identify missing date information
- flag possible urgency concerns
- organize procedural timelines
- prepare attorney/staff follow-up
- reduce missed humanitarian deadlines

This skill does not replace the firm’s calendar or case management system.

All dates and calculations require human verification before relying on them.

---

# Core Rules

- Never state that a calculated deadline is guaranteed accurate.
- Always recommend human verification.
- If dates are unclear, say so explicitly.
- If urgency appears high, flag it prominently.
- Preserve humanitarian sensitivity when discussing removal or asylum matters.
- Separate confirmed dates from estimated dates.
- Distinguish procedural deadlines from internal workflow recommendations.
- Do not provide final legal advice.

---

# Output Format

# Immigration Deadline Review

**Attorney Review Draft**

---

## 1. Matter Summary

Summarize:

- Client name
- Matter type
- Humanitarian category if applicable
- Current procedural posture
- Court or USCIS stage
- Custody/detention status if known

---

## 2. Confirmed Deadlines & Dates

List confirmed dates separately.

Use:

| Deadline / Event | Source | Date | Confidence |
|---|---|---|---|

Examples:

- Master calendar hearing
- Individual hearing
- Biometrics appointment
- RFE response deadline
- EOIR filing deadline
- USCIS interview
- TPS renewal window
- One-year filing concern
- Appeal deadline
- Work permit renewal
- Filing expiration

Confidence options:

- Confirmed in notice
- Likely but verify
- Estimated from context
- Unclear

---

## 3. Potential Urgency Concerns

Identify possible risks.

Examples:

- Upcoming hearing
- Short response window
- Possible one-year asylum issue
- Detention concern
- Missing filing evidence
- Missed hearing risk
- Expiring status
- Delayed filing concern
- Incomplete timeline
- Missing notice pages

Use:

| Concern | Why It Matters | Recommended Action |
|---|---|---|

---

## 4. Missing Timeline Information

Identify information still needed to safely review deadlines.

Examples:

- exact entry date
- exact hearing date
- filing receipt notice
- custody status
- prior filing dates
- previous denial dates
- notice issue date
- mailing date
- service date

---

## 5. Recommended Internal Follow-Up

Recommend staff/attorney next steps.

Examples:

- verify hearing date in CMS
- upload full notice
- confirm service date
- escalate to attorney
- calendar internal prep deadline
- request missing documents
- prioritize declaration interview
- confirm detention status

---

## 6. Internal Attorney Notes

Include:

- highest urgency issue
- biggest procedural uncertainty
- whether escalation is recommended
- whether attorney review should happen immediately
- whether humanitarian risk appears elevated

---

## 7. Suggested Next Workflow

Recommend one or more:

- draft-rfe-response
- document-request-checklist
- declaration-interview
- policy-impact
- attorney consultation
- hearing preparation workflow

End with:

“Attorney review and independent deadline verification required before relying on this review.”