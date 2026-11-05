# Design decisions

## Records and schedules are different tasks

The existing research synthesis identifies scattered prescriptions and reports as a retrieval problem. The design therefore gives upload, viewing and organization their own flow. A document upload does not imply a confirmed medicine schedule. Scheduling remains an explicit reviewed action.

## Represent uncertainty honestly

The proposed care loop records a patient's confirmation and distinguishes local recording from later synchronization. After 30 minutes without confirmation, the caregiver sees an unconfirmed state and last-sync context. This is a project-specific design policy, not a medical threshold or proof that a medicine was missed. The design does not infer replacement-dose advice or promise automatic calls.

## Consent controls access

One account can hold patient and caregiver roles. Switching roles grants no access by itself. Patient acceptance authorizes the care relationship; payment is not a substitute for consent. Additional caregiver approval and schedule permissions follow the recorded project policy. Their real security enforcement requires implementation and validation.

## Readable, bilingual interaction

The Android-first design uses Bengali and English coverage, readable medicine details and direct confirm/later actions. The documented system uses Inter and Noto Sans Bengali, functional blue and light surfaces. Notification permission, alarm access and reminder testing are visible dependencies rather than reliability promises.

## Preserve records when a plan changes

The owner-approved policy retains prior records and local reminders after Premium expiry. Paid sync and monitoring stop; new uploads beyond the Free allowance are blocked with an explanation. This separates previously stored care information from ongoing paid services. Billing, storage and cross-channel entitlement remain design proposals requiring provider and engineering validation.

## Research and measurement boundaries

The owner confirmed eight qualitative interviews/home observations, with five caregivers and three older patients. Preparation relies on the existing synthesis, not a fresh analysis of raw participant data. The small sample does not establish prevalence or effectiveness. Composite personas and dialogue communicate themes and are not participant verbatims.

The case-study measurement section proposes dose-confirmation, retrieval, caregiver-engagement and commercial targets. Those are hypotheses for future testing, not achieved results. Recording a confirmation alone cannot establish clinical adherence.

## Presentation approval is scoped

The V5 export was approved and all sixteen fixed-width JPEGs were inspected in the recorded delivery review. That approval covers the static case-study composition. Existing product logs still retain incomplete full-frame visual audits, native route playback and device/backend checks. The selected daily-care gallery is a local HTML rendering of design definitions, not an exact native Figma export or proof of a running Android product.
