# Traceability Matrix

This matrix traces each requirement backwards to the evidence that justifies it and forwards to the user story that captures it.

**Evidence → Stakeholder need → Requirement → User story**

| Requirement | Evidence | Need | User story | Priority |
|---|---|---|---|:-:|
| FR-ACC-01 | INT-01, SF-01 | N01 | US-01 | M |
| NFR-ACC-01 | SF-02 | N02 | US-02 | M |
| NFR-ACC-02 | SF-02 | N03 | US-02 | M |
| FR-MATCH-01 | INT-03, SF-05 | N07 | US-03 | M |
| FR-MATCH-02 | SF-06 | N08 | US-03 | S |
| FR-APP-01 | INT-02, SF-03 | N04 | US-04 | M |
| FR-NOT-01 | INT-02, risk register | N05 | US-05 | S |
| FR-EMP-01 | INT-03, SF-10 | N12 | US-06 | M |
| FR-EMP-03 | Negotiation (employer) | — | — *(gap)* | M |
| FR-INT-01 | SF-07 | N09 | US-07 | M |
| FR-PRIV-01 | INT-01, SF-04 | N06 | US-08 | M |
| NFR-SEC-01 | INT-01, INT-03, risk register | N13 | US-08 | M |
| FR-SUP-01 | SF-08 | N10 | US-09 | S |
| FR-SAFE-01 | SF-09 | N11 | US-10 | M |
| FR-EMP-02 | SF-09 | N11, N12 | US-10 | M |

## Evidence key

All interview and survey evidence is **simulated** (see [elicitation/](../elicitation/)).

| ID | Source | Finding |
|---|---|---|
| INT-01 | Interview: physical disability | Accessibility information needed before applying; disclosure should be user-controlled |
| INT-02 | Interview: cognitive disability | Plain language, smaller steps, save drafts, control notifications |
| INT-03 | Interview: employer | Assess skills before seeing disability information; verification builds trust |
| SF-01 | Survey | Accessibility information is highly valued |
| SF-02 | Survey | Accessible navigation, assistive-technology support, alternative formats |
| SF-03 | Survey | Save and resume applications |
| SF-04 | Survey | Disability disclosure should be optional |
| SF-05 | Survey | Skills should be prioritised over disability |
| SF-06 | Survey | Transparency in job recommendations |
| SF-07 | Survey | Flexible interview methods |
| SF-08 | Survey | Supporter access requires consent |
| SF-09 | Survey | Discrimination, scams and misleading information should be reportable |
| SF-10 | Survey | Employer verification is important |

## Coverage check

- **Every requirement traces back to evidence.** 14 of 15 trace to interview or survey findings. FR-EMP-03 comes from stakeholder negotiation.
- **Every requirement but one has a user story.** The gap is FR-EMP-03, which was added during negotiation.
- **Weakest evidence:** NFR-ACC-01/02, FR-MATCH-02, FR-SUP-01 and FR-INT-01 are supported by survey evidence only. A next iteration should include interviews with the groups behind them.
