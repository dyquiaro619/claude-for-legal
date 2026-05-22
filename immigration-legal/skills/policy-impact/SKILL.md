---
name: policy-impact
description: Use this skill to review how a USCIS, EOIR, DHS, DOS, court, or immigration policy update may affect a specific asylum, humanitarian, removal defense, TPS, or related immigration matter.
---

# Immigration Policy Impact Skill

Use this skill when the user provides:

- a policy update
- agency announcement
- USCIS alert
- EOIR update
- DHS notice
- DOS update
- Federal Register summary
- court decision summary
- practice advisory
- client matter summary
- humanitarian intake summary
- removal defense timeline
- TPS or asylum-related case facts

## Purpose

Analyze how a policy, agency, court, or procedural update may affect a specific immigration matter.

This skill helps attorneys and staff organize:

- what changed
- which case facts may be relevant
- whether the matter may need review
- what questions remain open
- what follow-up may be needed

This skill does not provide final legal advice and does not replace attorney review.

---

# Core Rules

- Do not state that a policy definitely applies unless the provided facts clearly support that conclusion.
- Do not provide final legal advice.
- Do not invent policy details.
- If the policy text is missing or incomplete, say so.
- Separate confirmed facts from assumptions.
- Separate policy summary from matter-specific impact.
- Flag uncertainty clearly.
- Recommend attorney review before action.
- Do not claim to monitor the whole caseload.
- Do not claim automatic compliance.
- Treat MatterOS-level caseload monitoring as outside the scope of this skill.

---

# Output Format

# Immigration Policy Impact Review

**Attorney Review Draft**

---

## 1. Policy / Update Summary

Summarize the provided update in plain language.

Include:

- issuing agency or source if known
- date of update if known
- topic affected
- case types potentially affected
- what appears to have changed
- what is unclear or missing

If no actual policy text was provided, write:

`Policy text not provided. Review is based only on the summary supplied by the user.`

---

## 2. Matter Summary

Summarize the specific client matter.

Include:

- client name if provided
- matter type
- humanitarian category if applicable
- current procedural posture
- relevant dates
- current filing or court stage
- custody/detention status if known
- key facts connected to the update

---

## 3. Potential Impact Areas

Identify possible areas of impact.

Use this table:

| Impact Area | Relevance To Matter | Confidence | Attorney Review Needed |
|---|---|---|---|

Possible impact areas:

- eligibility
- filing strategy
- deadline urgency
- evidence requirements
- country conditions
- TPS designation or renewal
- asylum procedure
- removal defense posture
- work authorization
- humanitarian parole
- client communication
- hearing preparation
- pending RFE / NOID response
- appeal or motion strategy

Confidence options:

- High based on provided facts
- Moderate based on provided facts
- Low / needs more information
- Unknown because policy text is incomplete

---

## 4. Questions For Attorney Review

List questions the attorney should answer before taking action.

Examples:

- Does this update apply to this client’s filing category?
- Does the update affect pending cases or only new filings?
- Does the update change evidence expectations?
- Does the update affect a deadline, filing window, or hearing strategy?
- Does the client need to be contacted?
- Does the firm need to review similar matters?

---

## 5. Recommended Follow-Up

Suggest practical next steps.

Separate into:

### Immediate Follow-Up

### Staff Follow-Up

### Attorney-Only Review

### Client Communication To Hold Until Review

---

## 6. Risk Level

Classify the matter as:

- No apparent impact
- Monitor
- Review recommended
- Urgent attorney review
- Emergency escalation

Explain why.

---

## 7. MatterOS Bridge Note

Include this only if the facts suggest broader caseload exposure:

If this update may affect multiple similar matters, note:

“This appears to be the kind of update that may require caseload-level review. Claude can help analyze this specific matter, but MatterOS-style policy-to-caseload monitoring would be needed to identify all potentially affected active matters across the firm.”

---

## 8. Suggested Next Workflow

Recommend one or more:

- deadline-review
- document-request-checklist
- draft-rfe-response
- client-status-update
- attorney consultation
- caseload review outside Claude

End with:

“Attorney review required before relying on this policy impact review or communicating conclusions to the client.”