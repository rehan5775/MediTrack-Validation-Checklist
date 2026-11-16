# MediTrack SRS — Validation Findings

**Review basis:** The supplied MediTrack SRS and Checklist v0.1. The two runs in this file are prepared sample reviews; partners should verify them before submission.

## Comparison of Run A and Run B

Both sample reviews identify the same overall result: CL-013 and CL-014 are Yes; the remaining checklist items are No. The reviewers give different wording and examples for some reasons, but no answer-level disagreement appears in these prepared runs.

## Main findings

| ID | Requirement(s) | Finding | Why it matters |
|---|---|---|---|
| F-01 | R-04, R-05 | Appointment duration is inconsistent: 15 minutes in R-04 and 10–30 minutes in R-05. | Staff may apply different appointment lengths. |
| F-02 | R-02 | “Quickly” has no measurable response-time target. | Booking performance cannot be tested objectively. |
| F-03 | R-03 | Double-booking prevention is stated, but simultaneous booking behaviour is not explained. | Two patients may be offered the same slot. |
| F-04 | R-06 | Reminder timing is missing. | Patients may still miss appointments. |
| F-05 | R-09 | “Securely” is vague; access permissions and security controls are missing. | Private medical records may be exposed. |
| F-06 | R-08 | “User-friendly for all age groups” is not measurable. | Elderly patients may struggle to use the system. |
| F-07 | R-10 | Walk-in booking is supported, but emergency walk-in handling is not described. | Emergency patients may not receive a clear process. |
| F-08 | R-11 | “Active appointments” is undefined. | The three-appointment limit may be interpreted differently. |
| F-09 | R-12 | “Normal working hours” is not defined. | System availability cannot be checked precisely. |
| F-10 | R-13 | “Clinic policy” is not included or referenced. | Overdue-payment handling may be inconsistent. |
| F-11 | R-07 | Cancellation, schedule update, and receptionist notification are combined in one requirement. | Each action is harder to verify separately. |
| F-12 | R-01, R-07 | Booking and cancellation confirmations are not specified. | Patients may not know whether their action succeeded. |
| F-13 | None | Clinic administrator responsibilities are not defined. | Administrative system tasks may be missed. |
| F-14 | None | Data protection officer responsibilities are not defined. | Privacy oversight is unclear. |
| F-15 | None | Monday peak-time capacity and performance targets are missing. | The system may become slow during busy periods. |

## Main risks

1. Double bookings due to unclear handling of simultaneous requests.
2. Missed appointments because reminder timing is not defined.
3. Medical data exposure because access rules are missing.
4. Elderly patients having difficulty using the system.
5. Emergency walk-in patients lacking a defined process.
6. Slow performance on busy Monday mornings.
7. Confusion about appointment limits and overdue payments.

## Suggested improvements

- Resolve the conflict between R-04 and R-05.
- Replace vague terms with measurable values.
- Define simultaneous booking handling and booking confirmations.
- Specify reminder timing and delivery method.
- Define role-based access and measurable security controls.
- Add clear requirements for elderly users and emergency walk-ins.
- Define administrator and data protection officer responsibilities.
- Clarify active appointments, working hours, clinic payment policy, and Monday peak-load expectations.

## Pair discussion record

**Prepared comparison:** The two sample runs show the same Yes/No results. The partners should review the answers together, confirm whether they agree, and record any changes here.

**Agreed findings:** The 15 issues listed above are the main SRS gaps identified by these sample reviews.
