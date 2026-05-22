---
name: draft-engagement-letter
description: Use this skill to draft an attorney-review engagement letter for a family-based immigration matter using the firm’s voice, scope, fee structure, client obligations, and review standards.
---

# Draft Engagement Letter Skill

Use this skill when the user asks Claude to draft an engagement letter for a family-based immigration matter.

## Purpose

Create a draft engagement letter for attorney review.

This skill should use the intake summary, firm profile, matter type, client names, fee structure, and scope details provided by the user.

## Core Rules

- This is a draft for attorney review.
- Do not create a final legal agreement.
- Do not invent fees, deadlines, filing strategies, or legal conclusions.
- If fee information is missing, insert `[FEE TO CONFIRM]`.
- If scope is unclear, insert `[SCOPE TO CONFIRM]`.
- If client names are missing, insert `[CLIENT NAME TO CONFIRM]`.
- If firm name is missing, insert `[FIRM NAME TO CONFIRM]`.
- Do not promise outcomes.
- Do not guarantee processing times.
- Do not say the case will be approved.
- Include client responsibilities clearly.
- Include attorney-review reminder at the end.

## Draft Output Format

Produce the engagement letter in this structure:

# Draft Engagement Letter

**Attorney Review Draft — Not Final**

[DATE]

[CLIENT NAME]  
[CLIENT ADDRESS]

Re: Engagement for [MATTER TYPE]

Dear [CLIENT NAME],

## 1. Introduction

Thank the client for choosing the firm and briefly describe the purpose of the engagement letter.

## 2. Scope of Representation

Describe the specific immigration matter.

Examples:

- Preparation and filing of Form I-130
- Preparation and filing of Form I-485
- Family-based adjustment of status
- Consular processing
- K-1 fiancé visa
- Spousal petition
- Related supporting documents

If the exact scope is unclear, use:

`[SCOPE TO CONFIRM]`

Possible humanitarian matter types include:

- Affirmative asylum
- Defensive asylum
- Removal defense
- TPS
- CAT protection
- Withholding of removal
- Humanitarian parole
- U visa
- VAWA
- Related humanitarian immigration relief

## 3. Services Included

List what the firm will do, such as:

- Review client-provided information
- Identify required supporting documents
- Prepare immigration forms and supporting materials
- Draft cover letters or legal support letters if included
- Communicate with the client about case preparation
- Submit filings if included in scope
- Respond to routine case preparation questions

## 4. Services Not Included

Unless specifically included in the signed agreement, this engagement does not automatically include:

- Appeals
- Federal litigation
- Emergency stay motions
- Bond hearings
- Separate immigration benefits
- Family derivative matters not specifically listed
- Country conditions expert reports
- Psychological evaluations

Clarify exclusions, such as:

- Appeals
- Motions
- Responses to RFEs or NOIDs unless separately agreed
- Court representation
- Waivers
- Criminal immigration analysis
- New facts or changed circumstances outside this matter
- Government filing fees
- Translation, medical exams, or third-party costs

## 5. Client Responsibilities

Explain that the client must:

- Provide complete and truthful information
- Submit requested documents on time
- Notify the firm about address changes
- Disclose prior immigration issues, arrests, removals, or denials
- Review all forms and documents before signing
- Pay legal fees and government fees as required

## 6. Fees and Costs

If fee information is provided, summarize it.

If not, write:

`Legal fee: [FEE TO CONFIRM]`

`Government filing fees: Separate and subject to current USCIS fee schedule.`

`Other costs: [COSTS TO CONFIRM]`

## 7. No Guarantee of Outcome

State that the firm cannot guarantee approval, processing time, or government action.

## 8. Communication

Describe how the firm and client will communicate.

If unknown, use:

`[COMMUNICATION PROCESS TO CONFIRM]`

## 9. Review and Signature

Include a short closing paragraph asking the client to review the letter and contact the firm with questions before signing.

## 10. Signature Blocks

Include:

[FIRM NAME TO CONFIRM]  
By: [ATTORNEY NAME TO CONFIRM]

Client: [CLIENT NAME TO CONFIRM]

## Internal Attorney Review Notes

After the letter, include a separate internal section:

- Missing information
- Scope items to confirm
- Fee items to confirm
- Any risk issues from the intake summary
- Items that should not be sent without attorney approval

End with:

“Attorney review required before sending this engagement letter to the client.”