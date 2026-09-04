# Example Intake Record

An anonymized example. It is not a project profile and is not proof of demand.

## Situation

A team asks for “a unified workspace with automated notifications and integrations.” Further discovery shows that staff currently use spreadsheets and email, while the request came from a user who is neither the buyer nor the payer.

## Snapshot

| Field | Example |
|---|---|
| Problem | Handoffs between roles cause requests to be lost and response time to increase. |
| Measurable outcome and deadline | Reduce lost requests by 50% during a 30-day test. |
| User | Operations team |
| Process owner | Head of operations |
| Buyer / payer | `UNKNOWN` |
| Current workaround | Spreadsheet, email, and manual reminders |
| Commitment | `OPERATIONAL`: data access and one staff member committed to the test |
| Evidence | Workflow observation and three real cases; no confirmed budget |
| Current level | `E2` for the problem, `E0–E1` for willingness to pay |

## Decision

- **Status:** `PROCEED TO DISCOVERY`
- **Allowed:** map the workflow, check existing alternatives, and run a limited manual test on one process.
- **Not allowed:** estimate a full platform, write production code, or treat an MVP as approved.
- **Riskiest assumption:** the buyer will pay for fewer lost requests rather than only provide operational access.
- **Next test:** run a paid or explicitly commercial commitment test after demonstrating the result manually.
- **Kill condition:** stop or reframe if the measurable outcome is not observed or buyer/payer is not confirmed by the review date.
- **Decision owner:** discovery lead
- **Review date:** [FILL IN]

Main lesson: a clear feature request and operational access justify discovery or a test, not commercial `BUILD`.

Russian source example: [`example_intake_record.md`](example_intake_record.md).