# MediTrack SRS — Validation Findings

**Review basis:** Checklist v0.1 and the supplied MediTrack SRS.

## Agreed problems to discuss and confirm

| ID | Requirement(s) | Finding | Why it matters |
|---|---|---|---|
| F-01 | R-04, R-05 | Appointment duration is inconsistent: one requirement fixes 15 minutes, while another allows 10–30 minutes. | Doctors and receptionists may follow different appointment lengths. |
| F-02 | R-02 | “Quickly” has no measurable response-time target. | The clinic cannot objectively test booking performance. |
| F-03 | R-03 | Double booking prevention is stated, but simultaneous booking behaviour is not explained. | Two users may try to reserve the same slot at the same time. |
| F-04 | R-06 | Reminder timing is not specified. | Patients may receive reminders too early or too late to prevent missed appointments. |
| F-05 | R-09 | “Securely” is vague; access permissions and security controls are not defined. | Medical information may be accessed or exposed improperly. |
| F-06 | R-08 | “User-friendly for all age groups” is not measurable. | Elderly patients may face difficulty using the system. |
| F-07 | R-10 | Walk-in booking is supported, but emergency walk-in handling is not described. | Emergency patients may not receive an appropriate process. |
| F-08 | R-11 | “Active appointments” is undefined. | Users may disagree about which appointments count toward the limit of three. |
| F-09 | R-12 | “Normal working hours” is not defined. | Availability expectations cannot be checked. |
| F-10 | R-13 | “Clinic policy” is not included or referenced by a clear document/version. | Overdue payment handling may be inconsistent. |
| F-11 | R-07 | The requirement combines cancellation, schedule updating, and receptionist notification. | It is difficult to verify each obligation separately. |
| F-12 | R-01, R-07 | Booking confirmation and cancellation confirmation are not specified. | Patients may not know whether an action succeeded. |
| F-13 | None | No requirement describes clinic administrator responsibilities. | Important system management tasks may be missed. |
| F-14 | None | No requirement describes data protection officer responsibilities. | Privacy oversight and compliance tasks are unclear. |
| F-15 | None | No requirement defines expected capacity or response performance for busy Monday mornings. | The system may slow down during the clinic’s busiest period. |

## Main risks

1. Double bookings caused by unclear handling of simultaneous requests.
2. Missed appointments because reminder timing is missing.
3. Exposure of medical information because access rules are not defined.
4. Elderly patients being unable to use the system.
5. Emergency walk-in patients not having a defined process.
6. Slow booking during busy Monday mornings.
7. Disputes caused by unclear appointment limits or overdue-payment policy.

## Suggested improvements

- Resolve the conflict between R-04 and R-05.
- Replace vague words with measurable values and defined terms.
- Specify booking conflict handling and confirmation messages.
- Define reminder timing and delivery method.
- Define role-based access to patient records and measurable security controls.
- Add clear requirements for elderly users, emergency walk-ins, clinic administrators, and the data protection officer.
- Define active appointments, working hours, overdue-payment policy, and Monday peak-load expectations.

## Pair discussion record

Student A and Student B should compare their independently completed runs, discuss every different answer, and confirm which findings are agreed.

**Agreed findings after discussion:** [Complete this section with your partner.]
