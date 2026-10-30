# Stakeholder Analysis & Risk Register

Report sections 1.1–1.2. This covers who the platform affects, what each group needs, and which risks had to shape the requirements before any were written.

## Stakeholder register

| Stakeholder | Role / interest | Main needs | Ethical concerns | Engagement method |
|---|---|---|---|---|
| Job seekers with physical disabilities | Seeking accessible employment | Workplace-accessibility information; accessible job opportunities | Mobility barriers, discrimination, unwanted disability disclosure | Interviews, surveys, usability testing |
| Job seekers with visual or hearing disabilities | Rely on assistive technologies | Screen-reader compatibility; captions, transcripts or other alternative formats | Poor interface design could exclude them from the platform | Accessibility testing with real users and assistive technologies |
| Job seekers with learning or cognitive disabilities | Difficulty with complex information | Plain language; clear instructions | Complicated forms create unequal access or cause drop-off | Easy-read surveys, supported interviews |
| Job seekers with mental health conditions | Experience anxiety or stress | Flexible communication | Disability labels could lead to stigma or unfair automated decisions | One-to-one interviews, anonymous surveys |
| Employers | Advertise vacancies, recruit | Job-posting tools; candidate search | Intentional or unintentional discrimination | Interviews, workshops, surveys |
| Platform administrators & support | Manage accounts, reports, safety | Moderation tools; accessibility training | Access to sensitive data; inconsistent moderation | Internal workshops, operational interviews |
| Disability NGOs / employment support organisations | Support job seekers, advise employers | Consent-based support access; verified employer information | Must respect user independence | Expert interviews, requirements workshops |
| Government employment agencies | Promote employment inclusion | Transparent reporting; accessibility compliance | Excessive data sharing creates privacy concerns | Policy review, expert consultation |
| Technology, cloud & AI providers | Hosting, communications, security | Clear technical requirements; secure data handling | Bias, excessive data collection, security risk | Technical review |

## Ethical risk register

| Risk | Affected | Likelihood | Impact | Level | Mitigation → requirement |
|---|---|---|---|---|---|
| Unauthorised disclosure of disability information | Job seekers | Medium | Very high | **Critical** | Optional disclosure, consent, role-based access, encryption → FR-PRIV-01, NFR-SEC-01 |
| Algorithmic discrimination | Job seekers | Medium | Very high | **Critical** | Skills-first matching, fairness testing, explanations → FR-MATCH-01, FR-MATCH-02 |
| Inaccessible user interface | Users with disabilities | Medium | Very high | **Critical** | Accessibility standards, assistive-technology testing → NFR-ACC-01, NFR-ACC-02 |
| Discriminatory job advertisements | Job seekers | High | High | **Critical** | Posting guidelines, flagging, human moderation → FR-SAFE-01 |
| Fake employers / employment scams | Job seekers | Medium | High | High | Employer verification, user reporting → FR-EMP-01, FR-SAFE-01 |
| Pressure to disclose disability | Job seekers | Medium | High | High | Disability fields optional at registration and application → FR-PRIV-01 |
| False inclusive-employer claims | Job seekers, genuine employers | Medium | High | High | Evidence-based badges, reporting of false claims → FR-EMP-02 |
| Complex application forms | Users with cognitive disabilities | High | Medium | High | Plain language, save-and-return → FR-APP-01 |
| Unauthorised caregiver access | Job seekers, caregivers | Low | High | Medium | Time-limited, revocable consent → FR-SUP-01 |
| Excessive or stressful notifications | Users with cognitive / psychosocial needs | Medium | Medium | Medium | Frequency controls, quiet mode → FR-NOT-01 |
