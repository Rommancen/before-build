# Быстрый старт

Before Build помогает решить, что делать с новой идеей или запросом: изучать, тестировать, строить, остановить или переформулировать. Это не доказательство спроса и не замена исследованию клиентов, финансовой модели или технической экспертизе.

## Последовательность

1. **Выберите входящий запрос.** Зафиксируйте его дословно, источник, роли участников, желаемый результат, срочность, владельца решения и дату пересмотра. Начальный статус — `REQUEST / UNVERIFIED`.
2. **Заполните intake-чек-лист.** Пройдите [`intake_checklist.md`](intake_checklist.md) до оценки, архитектуры, PoC или кода. Сначала опишите проблему и реальный workflow, а не список функций.
3. **Создайте intake-карточку.** Скопируйте [`intake_record_template.md`](intake_record_template.md) и отдельно запишите факты, evidence, assumptions, unknowns, альтернативы, роли и текущий workaround.
4. **Проверьте существующие решения.** Используйте [`intake_checklist.md`](intake_checklist.md), чтобы сравнить SaaS, функции текущих платформ, подрядчиков и ручные процессы. Если готовая альтернатива решает задачу, не начинайте собственную разработку без доказанного остаточного дефицита.
5. **Выберите самый дешёвый тест.** Найдите [`riskiest assumption`](glossary.en.md#decisions-and-assumptions) и запланируйте time-boxed тест с измеримым outcome, лимитом капитала и kill condition.
6. **Запишите решение.** Укажите один следующий шаг, владельца решения, дату пересмотра и текущий evidence gate. Если evidence недостаточно, выбирайте `EXPLORE` или `TEST`, а не спекулятивный `BUILD`.

## Документы

- Русский [`intake checklist`](intake_checklist.md).
- Русский [`intake record template`](intake_record_template.md).
- Русский [`example intake record`](example_intake_record.md).
- Английские [`intake checklist`](intake_checklist.en.md), [`intake record template`](intake_record_template.en.md) и [`example intake record`](example_intake_record.en.md).
- Канонический [`decision engine`](decision_engine.json), который определяет evidence gates и правила решения.

## Главное ограничение

`PROCEED TO DISCOVERY` не означает `BUILD AUTHORIZED`. Обычно коммерческий `BUILD` требует `E3` costly commitment, например paid pilot, deposit, purchase order или выделенный бюджет. Операционный доступ сам по себе не доказывает willingness to pay.