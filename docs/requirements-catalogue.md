# Requirements Catalogue

The final requirements specification (report section 6.3), after ethical review, stakeholder validation and negotiation.

**Priority** (MoSCoW): M = Must have · S = Should have
**SD flags** (sustainability dimensions): S = Social · E = Economic · Env = Environmental

## Functional requirements

| ID | Requirement | Priority | SD | Rationale |
|---|---|:-:|:-:|---|
| FR-ACC-01 | The system shall display verified or employer-confirmed workplace-accessibility information on job postings before application. | M | S | Equal access; fewer unsuitable applications. |
| FR-APP-01 | The system shall allow users to save incomplete applications, resume them later and continue from their previous progress. | M | S | Reduces cognitive and digital-access barriers. |
| FR-NOT-01 | The system shall allow users to customise notification frequency, enable quiet mode and still receive essential service notifications. | S | S | Supports well-being without missing critical updates. |
| FR-PRIV-01 | The system shall not require disability disclosure during registration or initial application, and employers shall not require such disclosure at this stage. | M | S | Protects privacy and autonomy; prevents disclosure pressure. |
| FR-MATCH-01 | Job recommendations shall primarily use skills, qualifications and user preferences; disability information shall not be used as a primary screening factor. | M | S | Skills-first fairness. |
| FR-MATCH-02 | The system shall provide a concise, plain-language explanation of the main factors behind each job recommendation. | S | S | Transparency without cognitive overload. |
| FR-SUP-01 | Supporter or job-coach access shall require explicit user consent, be limited to authorised functions and be revocable by the user. | S | S | Assistance without loss of autonomy. |
| FR-SAFE-01 | Users shall be able to report discriminatory or fraudulent job postings, with reports subject to appropriate review. | M | S, E | Protection from scams and harmful content. |
| FR-EMP-01 ✱ | The system shall automatically verify employer credibility using the business email domain and business registry before employers from that business can create job postings. | M | S, E | Reduces scams with low onboarding effort for SMEs. |
| FR-EMP-02 | Users shall be able to report misleading employer or inclusivity claims, which shall be reviewed before corrective action. | M | S, E | Accountability while protecting legitimate employers. |
| FR-EMP-03 ✱ | The system shall require employers to clearly list the capabilities required for a job before the posting can be published. | M | S | Transparency on genuine job requirements, so disclosure isn't needed. |
| FR-INT-01 ✱ | The system shall require employers to provide multiple interview formats that allow fair assessment of candidates. | M | S | Inclusive recruitment for different needs. |

✱ Revised or added during stakeholder negotiation (see [conflict-analysis.md](conflict-analysis.md#negotiation-outcomes)).

## Non-functional requirements

| ID | Requirement | Priority | SD | Rationale |
|---|---|:-:|:-:|---|
| NFR-ACC-01 | The system shall support keyboard and screen-reader navigation across all core platform functions. | M | S | Prevents exclusion of assistive-technology users. |
| NFR-ACC-02 | The system shall provide captions, transcripts or equivalent text alternatives for relevant content. | M | S | Equal access for hearing, visual or communication needs. |
| NFR-SEC-01 | The system shall protect sensitive personal and disability information through access controls, data minimisation, secure handling and appropriate deletion/retention controls. | M | S, Env | Privacy and dignity; less stored data also means less storage and processing. |

## Constraints

- Employers must complete mandatory posting fields (including required capabilities) before publishing.
- Reported content cannot be taken down by automation alone; a human reviewer decides corrective action.

## Summary

| | Count |
|---|:-:|
| Functional requirements | 12 |
| Non-functional requirements | 3 |
| Must have | 12 |
| Should have | 3 |
