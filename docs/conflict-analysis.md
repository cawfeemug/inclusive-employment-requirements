# Conflict Analysis & Resolution

Report sections 3.2 and 4.0–6.2. Many requirements pulled against each other or against a stakeholder's interests. Each conflict was identified, discussed in a structured team review, and resolved with a documented trade-off.

## Conflict matrix

| ID | Conflict | Tension | Impact | Resolution |
|---|---|---|---|---|
| C01 | FR-MATCH-01 vs FR-PRIV-01 | Personalisation vs privacy | Disability data could improve matching but enable discrimination | Match on skills, qualifications and preferences; disclosure not required |
| C02 | FR-MATCH-01 vs employer screening needs | Fairness vs efficiency | Employers may want more candidate information for screening | Keep skills-first matching; disability is never a primary screening factor |
| C03 | FR-MATCH-02 vs simplicity | Transparency vs usability | Detailed explanations may overwhelm some users | Concise, plain-language explanations |
| C04 | FR-SUP-01 vs assisted employment | Autonomy vs support | Unrestricted supporter access compromises autonomy | Explicit, limited, revocable consent |
| C05 | FR-INT-01 vs employer participation | Inclusion vs cost | Alternative interviews need extra employer resources | Offer multiple formats that still allow fair assessment |
| C06 | FR-EMP-01 vs employer participation | Trust vs onboarding cost | Verification adds onboarding effort | Proportionate, automated verification |
| C07 | FR-EMP-02 vs employer reputation | Transparency vs fairness to employers | False reports could unfairly harm employers | Reports reviewed before any action |
| C08 | FR-SAFE-01 / FR-EMP-02 vs moderation resources | Safety vs operating cost | Extensive moderation increases cost | Automated flagging plus targeted human review |
| C09 | FR-NOT-01 vs timely communication | Well-being vs communication | Fewer notifications may cause missed opportunities | Customisable, but essential notifications always delivered |
| C10 | NFR-SEC-01 vs functionality | Privacy vs data availability | Excess retention increases privacy risk | Collect only necessary data; access and retention controls |
| C11 | NFR-SEC-01 vs environmental efficiency | Data protection vs footprint | Excess retention increases storage and processing | Data minimisation, retention limits, secure deletion |

## How conflicts were evaluated

The team used a **deontological (duty-based) framework**. Each requirement was judged on whether it upheld users' rights to privacy, autonomy, equality, dignity and accessibility, rather than only on outcomes. This led to several requirements being **strengthened** rather than just retained:

| Requirement | Decision |
|---|---|
| FR-PRIV-01 | Strengthened: disclosure optional, and employers cannot require it at the initial stage |
| FR-MATCH-01 | Strengthened: disability is not a primary screening factor |
| FR-SUP-01 | Strengthened: consent must be explicit and revocable |
| NFR-SEC-01 | Strengthened: data minimisation, secure handling and deletion added |

## Negotiation outcomes

Stakeholder validation flagged three requirements as **Needs Revision**. These were negotiated with employer stakeholders:

| Original requirement | Concern raised | Outcome |
|---|---|---|
| FR-PRIV-01: no mandatory disability disclosure | Some roles have genuine physical requirements for legal or safety reasons | FR-PRIV-01 kept; **FR-EMP-03 added**: employers must list the capabilities a job requires before publishing |
| FR-EMP-01: employer verification before posting | Heavy auditing would deter small and medium businesses | **FR-EMP-01 revised**: automatic verification via business email domain and business registry |
| FR-INT-01: job seekers can request alternative interviews | Some alternatives could bypass genuine skill assessment | **FR-INT-01 revised**: employers must provide multiple formats that still allow fair assessment |
