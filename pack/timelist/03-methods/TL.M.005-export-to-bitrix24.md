# TL.M.005 — Формирование протокола и выгрузка поручений в Bitrix24

## Summary

Получение автопротокола встречи, сохранение в Excel и импорт задач в Bitrix24.

---

## Input

Проведённая встреча в TimeList.

## Action

1. Получить автопротокол.
2. Сохранить как Excel.
3. Импортировать задачи в Bitrix24.

## Output

Задачи в Bitrix24 с ответственными и сроками.

## Work Products Produced

- TL.WP.002 — Автопротокол / авторезюме
- TL.WP.003 — Список поручений в Bitrix24

## Failure Modes Addressed

- TL.FM.002 — Непредсказуемый захват задач из протокола
- TL.FM.003 — Дублирование систем контроля задач

## Source

- `DS-strategy/exocortex/reference_timelist_sales.md`
- `lespromhoz-timelist.md`
