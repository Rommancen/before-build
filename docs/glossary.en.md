# Glossary

Short definitions for the core Before Build terms. These definitions follow the canonical rules in [`decision_engine.json`](decision_engine.json).

## Roles

- **Buyer** — the person or group that decides whether to purchase the solution.
- **User** — the person or team that directly uses the solution or receives its operational result.
- **Payer** — the source of the budget or the party that actually bears the cost.
- **Problem owner** — the person or function accountable for the consequences of the unresolved problem.

When these roles differ, validate the incentives, value proposition, and evidence for each role separately.

## Evidence and commitment

- **Behavioral evidence** — observable behavior in a real workflow, such as repeated problem cases, current spending, use of a workaround, access to relevant data, or a concrete change in behavior. Opinions and feature requests are not behavioral evidence by themselves.
- **Economic commitment** — a costly signal that the buyer is willing to pay, such as a paid pilot, deposit, pre-order, purchase order, budget allocation, signed commercial pilot, or paid manual delivery.
- **Operational commitment** — a costly organizational obligation to help run a test, such as committed staff, data or integration access, executive sponsorship, formal procurement, or a migration commitment. Operational commitment alone does not prove willingness to pay.
- **Evidence gate** — the minimum evidence required before an initiative may receive a particular level of investment or permission, such as commercial build or scale. Missing data remains `UNKNOWN`; it does not count as favorable evidence.

## Decisions and assumptions

- **Discovery** — structured work to understand the workflow, problem, roles, alternatives, and constraints before authorizing commercial build.
- **Test** — a time-boxed experiment designed to reduce a specific uncertainty as cheaply as possible and produce a measurable result.
- **Build** — implementation of an agreed solution after the applicable evidence gate is passed. A prototype or technical experiment is not automatically a commercial build.
- **Kill** — stop an initiative when its evidence or test result meets a defined stop condition and continuation is not justified.
- **Reframe** — change the problem, customer, outcome, or solution hypothesis when evidence contradicts the current framing, instead of defending the original scope.
- **Riskiest assumption** — the unproven assumption whose failure would most change the decision to continue, test, build, or stop.

## Related rule

The default behavior when uncertain between advancing and testing is `TEST`. A score, market size, technical prototype, or sunk cost cannot override an evidence gate.