# User Stories

Report section 5.2. There are 10 user stories, each with Given/When/Then acceptance criteria and an INVEST check. All 10 stories passed every INVEST criterion: Independent, Negotiable, Valuable, Estimable, Small, Testable.

> **Note:** US-06 and US-07 were written before stakeholder negotiation revised FR-EMP-01 and FR-INT-01 (see [negotiation outcomes](conflict-analysis.md#negotiation-outcomes)), so their criteria reflect the earlier versions of those requirements.

---

### US-01 · Workplace accessibility information
**Requirement:** FR-ACC-01 · **Sustainability:** Social (inclusivity, accessibility)

> As a **job seeker with disabilities**, I want to view workplace accessibility information and job requirements on job listings, so that I know whether it will be difficult to work there.

- **Given** a job seeker views a job listing, **when** the listing loads, **then** workplace-accessibility information and job requirements are shown.
- **Given** the job seeker uses assistive technology, **when** they access the accessibility information, **then** it is compatible with supported assistive technologies.

### US-02 · Keyboard, screen-reader and text alternatives
**Requirements:** NFR-ACC-01, NFR-ACC-02 · **Sustainability:** Social (inclusivity, accessibility)

> As a **job seeker with disabilities**, I want to navigate the platform using a keyboard and screen reader, and access text alternatives for multimedia, so that I can use the platform independently.

- **Given** a job seeker uses only a keyboard or screen reader, **when** they use the platform, **then** they can operate all interactive elements and complete key tasks without a mouse.
- **Given** the platform contains multimedia content, **when** the job seeker accesses it, **then** captions, transcripts or text alternatives are available.

### US-03 · Fair, explainable job recommendations
**Requirements:** FR-MATCH-01, FR-MATCH-02 · **Sustainability:** Social (inclusivity, privacy)

> As a **job seeker**, I want job recommendations driven by my skills, with clear explanations, so that I am matched fairly and understand the system's logic.

- **Given** the system generates recommendations, **when** the matching algorithm runs, **then** it uses skills, qualifications and preferences, and does not use disability information as a primary screening factor.
- **Given** a recommended job is displayed, **when** the job seeker views it, **then** a concise, plain-language explanation of the main match factors is shown.

### US-04 · Save and resume applications
**Requirement:** FR-APP-01 · **Sustainability:** Social (accessibility)

> As a **job seeker**, I want to save applications, so that I can continue working on them later.

- **Given** a job seeker is interested in a job, **when** they start an application, **then** the system creates an application for that job.
- **Given** an unfinished application, **when** the job seeker stops editing, **then** the system saves it.
- **Given** a saved application, **when** the job seeker opens it, **then** it can be edited and saved again.

### US-05 · Notification control
**Requirement:** FR-NOT-01 · **Sustainability:** Social (accessibility, well-being)

> As a **user**, I want to customise notification frequency and enable quiet mode, so that I can manage notifications without missing essential service notifications.

- **Given** notification settings are available, **when** the user changes the frequency, **then** the system saves and applies it.
- **Given** quiet mode is enabled, **when** the quiet period is active, **then** non-essential notifications are suppressed or delayed.
- **Given** quiet mode is enabled, **when** an essential service notification is due, **then** it is still delivered.

### US-06 · Employer verification
**Requirement:** FR-EMP-01 · **Sustainability:** Economic (verification), Social (trust & safety)

> As a **user**, I want employers to be verified before posting jobs, so that job listings are legitimate.

- **Given** an employer wants to post a job, **when** they submit their employer account for verification, **then** the system performs the required proportionate verification checks.
- **Given** the employer has passed verification, **when** they post a job, **then** the listing can be published.
- **Given** the employer does not meet the verification criteria, **when** they attempt to post a job, **then** the system prevents publishing until verification is completed.

### US-07 · Alternative interview formats
**Requirement:** FR-INT-01 · **Sustainability:** Social (inclusivity, accessibility)

> As a **job seeker with accessibility needs**, I want to request an alternative interview method, so that I can take part in recruitment using a suitable arrangement.

- **Given** a job seeker is invited to an interview, **when** they need an alternative interview method, **then** the system lets them submit a request to the employer.
- **Given** a request has been submitted, **when** the employer receives it, **then** the employer can review and respond based on the reasonable arrangements available.
- **Given** an alternative arrangement is available and agreed, **when** the employer confirms it, **then** the system records and communicates the agreed method to the job seeker.

### US-08 · Optional disclosure and data protection
**Requirements:** FR-PRIV-01, NFR-SEC-01 · **Sustainability:** Social (privacy, accessibility), Environmental (less stored data)

> As a **job seeker**, I want registration to omit mandatory disability disclosure and my sensitive data to be protected, so that I don't have to worry about misuse of my disability information or data breaches.

- **Given** a job seeker registers or starts an initial application, **when** they fill in required fields, **then** the system does not require disability disclosure.
- **Given** the system collects personal or disability information, **when** it is collected, **then** only information necessary for the service is collected.
- **Given** sensitive information is no longer required, **when** the retention period expires, **then** the system securely deletes it according to the retention policy.

### US-09 · Consent-based supporter access
**Requirement:** FR-SUP-01 · **Sustainability:** Social (accessibility)

> As a **job seeker**, I want help from a supporter or job coach only when I accept, so that I get assistance with finding and applying for jobs.

- **Given** a job seeker wants assistance, **when** they request help, **then** they can invite an authorised supporter or job coach.
- **Given** a supporter is connected, **when** they provide assistance, **then** they can only use the functions the job seeker authorised.
- **Given** the job seeker no longer wants assistance, **when** they remove the supporter, **then** the support relationship and access end.

### US-10 · Reporting harmful or misleading content
**Requirements:** FR-SAFE-01, FR-EMP-02 · **Sustainability:** Social (inclusivity), Economic (verification)

> As a **job seeker**, I want to report discriminatory, fraudulent or misleading job and employer information, so that it can be reviewed and addressed.

- **Given** a job seeker finds questionable content, **when** they report it, **then** they can submit a report and select or describe the reason.
- **Given** a report is submitted, **when** the system receives it, **then** it is recorded and queued for review.
- **Given** a reviewer assesses the report, **when** the content is found inappropriate, fraudulent, discriminatory or misleading, **then** appropriate corrective action is taken.

---

**Coverage gap:** FR-EMP-03 (employers must list required capabilities) was added during negotiation and has no user story yet.
