# Before Build

**Repository slug:** `before-build`

A lightweight, opinionated template for validating product and custom-development requests before estimation, prototyping, and build.

Before Build helps prevent common mistakes: building from a feature request, treating interviews as demand, ignoring existing alternatives, confusing operational access with willingness to pay, and turning a technical prototype into an unsolicited MVP.

## Who it is for

Founders, product managers, consultants, agencies, and development teams that need to decide whether an incoming request should become discovery, an experiment, or a build.

This template does not replace customer research, financial modeling, legal review, or technical due diligence. It helps distinguish interest in an idea from evidence that justifies spending.

## Contents

- [`docs/decision_engine.json`](docs/decision_engine.json) — the canonical decision engine: evidence levels, gates, kill/reframe triggers, test selection, and allocation rules.
- [`docs/intake_checklist.md`](docs/intake_checklist.md) — a short mandatory triage for every new request.
- [`docs/intake_record_template.md`](docs/intake_record_template.md) — a reusable record for evidence, alternatives, commitment, and the decision.
- [`docs/example_intake_record.md`](docs/example_intake_record.md) — an anonymized example showing why a feature request leads to `TEST`, not `BUILD`.
- [`docs/project_decision_profile_template.json`](docs/project_decision_profile_template.json) — a project-specific configuration that does not replace or weaken the decision engine.

## Quick start

1. Copy this repository for a new project.
2. Create an instance of `intake_record_template.md` for the first request.
3. Complete `intake_checklist.md` before estimation, architecture, or code.
4. Keep facts, assumptions, unknowns, and contradictory evidence separate.
5. Choose the cheapest test for the current riskiest assumption.
6. Do not start a commercial build before the applicable evidence gate — usually `E3` costly commitment.

Every decision must explicitly record a measurable outcome, one next action, a decision owner, and a review date. Urgency may change the test timeline, but it does not lower the evidence gate.

## Non-negotiable rules

> Problem before solution. Behavior before opinion. Costly commitment before commercial build. Capital follows evidence.

- `UNKNOWN` remains `UNKNOWN`.
- Several weak signals do not automatically become strong evidence.
- Market size, scorecards, technical feasibility, and sunk cost do not override the evidence gate.
- An existing alternative closes the request until a specific remaining gap is demonstrated.
- `PROCEED TO DISCOVERY` does not mean `BUILD AUTHORIZED`.
- Operational commitment does not prove willingness to pay.
- Urgency, deadlines, stakeholder pressure, and money already spent are not exceptions to the evidence gate.

## How to use and publish

This is an opinionated framework, not a ready-made application. Copy the repository, create a separate intake record for each request, and adapt only project-specific gates that can be verified. Do not weaken the canonical `decision_engine.json` to justify a decision that has already been made.

Before publishing a copy, review its Git history: deleting a file from the current state does not remove its contents from history. Do not publish history containing client materials, personal data, secrets, or internal documents.

## License

Distributed under the [MIT License](LICENSE).

---

# Русская версия

Лёгкий шаблон для проверки продуктовых и заказных запросов до оценки, прототипирования и разработки.

Шаблон помогает не допускать типичных ошибок: строить по feature request, считать интервью спросом, игнорировать готовые альтернативы, путать операционный доступ с готовностью платить и превращать технический prototype в незаказанный MVP.

## Для кого

Для founders, product managers, консультантов, агентств и команд разработки, которым нужно решить, стоит ли превращать входящий запрос в Discovery, эксперимент или build.

Шаблон не заменяет customer research, финансовую модель, юридическую экспертизу или технический due diligence. Он помогает не перепутать интерес к идее с основанием для затрат.

## Содержимое

- [`docs/decision_engine.json`](docs/decision_engine.json) — канонический decision engine: evidence levels, gates, kill/reframe triggers, правила выбора теста и allocation.
- [`docs/intake_checklist.md`](docs/intake_checklist.md) — короткий обязательный triage для каждого нового запроса.
- [`docs/intake_record_template.md`](docs/intake_record_template.md) — копируемая карточка для фиксации evidence, альтернатив, commitment и решения.
- [`docs/example_intake_record.md`](docs/example_intake_record.md) — короткий обезличенный пример: почему feature request приводит к `TEST`, а не к `BUILD`.
- [`docs/project_decision_profile_template.json`](docs/project_decision_profile_template.json) — копируемая настройка для конкретного проекта; не заменяет и не ослабляет decision engine.

## Быстрый старт

1. Скопируйте этот репозиторий для нового проекта.
2. Создайте экземпляр `intake_record_template.md` для первого запроса.
3. Пройдите `intake_checklist.md` до любой оценки, архитектуры или кода.
4. Храните факты, assumptions, unknowns и противоречащее evidence раздельно.
5. Выберите самый дешёвый тест для текущей riskiest assumption.
6. Не начинайте коммерческий build до применимого evidence gate — обычно `E3` costly commitment.

Перед любым решением должны быть явно записаны: измеримый outcome, один следующий шаг, владелец решения и дата пересмотра. Срочность запроса меняет срок теста, но не снижает evidence gate.

## Правила без исключений

- `UNKNOWN` остаётся `UNKNOWN`.
- Несколько слабых сигналов не становятся сильным evidence автоматически.
- Размер рынка, scorecard, техническая возможность и sunk cost не отменяют evidence gate.
- Готовая альтернатива закрывает запрос, пока не доказан конкретный остаточный дефицит.
- `PROCEED TO DISCOVERY` не означает `BUILD AUTHORIZED`.
- Операционный commitment не доказывает willingness to pay.
- Срочность, дедлайн, давление стейкхолдеров и уже потраченные деньги не являются исключением из evidence gate.

## Лицензия

Распространяется по лицензии [MIT](LICENSE).
