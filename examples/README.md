# Примеры работ

Анонимизированные образцы документов из реального проекта (Mobile QA, медицинский SaaS на Flutter).

> Названия продукта, реальные данные пациентов, скриншоты и видео не публикуются — NDA.
> Все примеры обезличены и приведены как демонстрация подхода и оформления.

---

## Содержание

### 🐞 Баг-репорты — [`/bug-reports/`](./bug-reports/)

| ID | Заголовок | Severity | Статус |
|----|-----------|----------|--------|
| [BUG-001](./bug-reports/BUG-001-payment-input-field.md) | Поле суммы платежа принимает только `0` и точку | Critical | Confirmed |
| [BUG-002](./bug-reports/BUG-002-missing-push-notifications.md) | Push-уведомления отсутствуют в production-сборке | High | Escalated |
| [BUG-003](./bug-reports/BUG-003-delete-dialog-ux.md) | Диалог удаления без контекста, равноправные кнопки | Medium | Reported |
| [BUG-004](./bug-reports/BUG-004-discount-silent-cap.md) | Тихий cap скидки на 99% без подсказки | Low | Reported |

### ✅ Чек-листы — [`/checklists/`](./checklists/)

- [Smoke-чек-лист: пациенты, счета, скидки](./checklists/checklist-smoke-patients-invoices.md)

### 📄 Технические документы — [`/technical-docs/`](./technical-docs/)

- [Готовность приложения к автоматизации (Flutter)](./technical-docs/automation-readiness-flutter.md)

---

## Как я оформляю баг-репорты

Каждый репорт содержит: **ID · Severity · Priority · Окружение · Предусловия · Шаги · Ожидаемый результат · Фактический результат · Доказательства · Примечания.**
Статусы строго разделены: **Pass / Partial / Fail / Not tested** — без размытых формулировок.
