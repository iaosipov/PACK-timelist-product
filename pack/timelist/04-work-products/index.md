# Work Products — TimeList Product

---

## What is a Work Product

Per FPF/SPF: a **work product** is a concrete artifact produced by applying a method. It is not the method description and not a role.

---

## Work Products Index

| ID | Work Product | Format | Producer | Consumer |
|----|--------------|--------|----------|----------|
| TL.WP.001 | Расшифровка (стенограмма) | Текст с разбивкой по спикерам; Word/Excel/web | TimeList / секретарь | Участники |
| TL.WP.002 | Автопротокол / авторезюме | Структурированный документ | TimeList / менеджер проекта | Участники, руководитель |
| TL.WP.003 | Список поручений в Bitrix24 | Задачи в Bitrix24 | Интегратор / менеджер проекта | Исполнители |
| TL.WP.004 | Коммерческое предложение | Таблица/документ с тарифами | Интегратор | ЛПР |
| TL.WP.005 | Памятка по регламенту | 2–3 страницы + скриншоты | Методист | Сотрудники |
| TL.WP.006 | Демо-доступ | Доступ к личному кабинету TimeList | Интегратор | Потенциальный заказчик |
| TL.WP.007 | Лендо-статья про корпоративный таймбот | Статья по образцу Глеба | Маркетолог / интегратор | Целевая аудитория |
| TL.WP.008 | Отчёт по задачам из MAX-чатов | Ежедневная/еженедельная сводка | Таймбот | Руководитель |

---

## Detailed Work Product Cards

### TL.WP.001 — Расшифровка (стенограмма) встречи

**Format**: Текст с разбивкой по спикерам; экспорт в Word/Excel/web.

**Definition of Done**:
- Все спикеры идентифицированы/проверены.
- Текст соответствует аудио.
- Нет пропусков ключевых фрагментов.

**Produced by**: TL.M.004

**Consumed by**: TL.R.001, TL.R.002, TL.R.003

**Source**: `DS-strategy/exocortex/reference_timelist_sales.md` + `transcripts/2026-06-08/1324-...txt`

---

### TL.WP.002 — Автопротокол / авторезюме

**Format**: Структурированный документ (Word / Excel / внутренний формат TimeList).

**Definition of Done**:
- Выделены решения.
- Выделены поручения.
- Указаны ответственные и сроки.
- Готов к экспорту задач.

**Produced by**: TL.M.005

**Consumed by**: TL.R.002, TL.R.003, TL.R.004

**Source**: `DS-strategy/exocortex/reference_timelist_sales.md` + `lespromhoz-timelist.md`

---

### TL.WP.003 — Список поручений в Bitrix24

**Format**: Задачи в Bitrix24 (импорт из Excel-протокола TimeList).

**Definition of Done**:
- Каждая задача имеет ответственного.
- Каждая задача имеет дедлайн.
- Актуальный статус.

**Produced by**: TL.M.005, TL.M.006

**Consumed by**: TL.R.002, TL.R.006

**Source**: `lespromhoz-timelist.md`

---

### TL.WP.004 — Прайс / коммерческое предложение

**Format**: Таблица/документ с тарифами.

**Definition of Done**:
- Указаны облачные варианты.
- Указан on-premise пилот.
- Указаны требования к оборудованию (on-premise).

**Produced by**: TL.M.003

**Consumed by**: TL.R.004, TL.R.005

**Source**: `DS-strategy/exocortex/reference_timelist_sales.md`

---

### TL.WP.005 — Памятка по регламенту работы с поручениями

**Format**: 2–3 страницы + 3–4 скриншота из Bitrix24.

**Definition of Done**:
- Привязана к Bitrix24.
- Показывает куда тыкать.
- Согласована с руководителем.
- Обновлена по итогам пилота.

**Produced by**: TL.M.007

**Consumed by**: TL.R.001, TL.R.002, TL.R.004

**Source**: `lespromhoz-timelist.md`

---

### TL.WP.006 — Демо-доступ

**Format**: Доступ к личному кабинету TimeList + примеры расшифровок.

**Definition of Done**:
- Заказчик может «потыкать» самостоятельно.
- Демо проведено на живой встрече.

**Produced by**: TL.M.001

**Consumed by**: TL.R.004, TL.R.005

**Source**: `DS-strategy/exocortex/reference_timelist_sales.md` + `lespromhoz-timelist.md`

---

### TL.WP.007 — Продающая лендо-статья про корпоративный таймбот

**Format**: Статья по образцу Глеба (шок-крючок → боль → методика → решение → инструмент).

**Definition of Done**:
- Угол — бизнес-процесс + ЛПР.
- Не смешивается с задачником-ассистентом.
- Есть призыв к действию.

**Produced by**: TL.M.009

**Consumed by**: Целевая аудитория, TL.R.005

**Source**: `transcripts/2026-06-23/1307-...txt` + `DS-strategy/archive/wp-contexts/WP-57-timelist-promotion.md`

---

### TL.WP.008 — Отчёт по задачам из MAX-чатов

**Format**: Ежедневная/еженедельная сводка статусов по задачам, вычисленных из сообщений.

**Definition of Done**:
- Статусы задач (принято/выполнено/отмена/к прояснению) отражены корректно.
- Не требует от сотрудников отдельного интерфейса.

**Produced by**: TL.M.006

**Consumed by**: TL.R.004, TL.R.006

**Source**: `lespromhoz-timelist.md` + `transcripts/2026-06-23/1358-...wp-41.txt`
