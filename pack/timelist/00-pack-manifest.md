# Pack Manifest — TimeList Product

---

## Metadata

```yaml
pack_id: timelist
pack_name: TimeList как продукт
version: 0.1.0
fpf_edition: v1.0
status: draft
maintainers:
  - name: Игорь Осипов
    contact: iaosipov
created: 2026-08-11
last_updated: 2026-08-11
```

---

## Scope

### What This Pack Covers

- Продукт TimeList (timelist.ru) как ИИ-сервис расшифровки и автопротоколирования совещаний.
- Функциональность: стенограммы, автопротоколы, AI-чат по встрече, экспорт задач, интеграция с Bitrix24.
- Режимы развёртывания: облако и on-premise.
- Сценарии продажи и внедрения: демо, discovery, пилот, обучение.
- Роли пользователей: секретарь-протоколист, менеджер проекта, пассивный участник, ЛПР, интегратор.
- Типичные ошибки и конкурентное позиционирование.

### What This Pack Does NOT Cover

- Научная модель TimeInvest / МСВ — методология тайм-менеджмента, шахты/ракеты.
- Исходный код продукта TimeList.
- Документация API.
- Общие принципы тайм-менеджмента.

---

## Dependencies

### FPF Distinctions Used

| FPF Distinction | How Used in This Pack |
|-----------------|----------------------|
| method vs tool | Methods describe practices; tools are product features. |
| work product | Each WP is a concrete artifact produced by TimeList methods. |
| role | Roles are functional positions when using or selling TimeList. |

### Other SPF Packs

| Pack | Relationship |
|------|--------------|
| _none yet_ | _will link to PACK-timeinvest-method when created_ |

### External References

| Reference | URL | Used In |
|-----------|-----|---------|
| Видеообзор TimeList | https://timelist.ru/videoobzor_302 | TL.M.001 — Демо продукта на живой встрече |
| Тарифы TimeList | https://timelist.ru/pricing | TL.WP.004 — Прайс / коммерческое предложение |

---

## Content Summary

| Section | Item Count | Status |
|---------|------------|--------|
| Distinctions | 10 | draft |
| Roles | 7 | draft |
| Entities | 11 | draft |
| Methods | 9 | current |
| Work Products | 8 | current |
| Failure Modes | 7 | current |
| SoTA Annotations | 10 | draft |
| Maps | 24 | current |

---

## Extended Kinds

| Code | Name | Description | Folder |
|------|------|-------------|--------|
| ENT | Entity | Things in the TimeList domain with attributes and relationships | `02-domain-entities/` |

---

## Entity Index

| ID | Name | Kind | Summary | Status |
|----|------|------|---------|--------|
| TL.D.001 | NoTaker AI vs универсальный ИИ-чат | D | TimeList — специализированный агент, не универсальный чат | draft |
| TL.D.002 | Облако vs On-premise | D | Два режима развёртывания | draft |
| TL.D.003 | Автопротокол vs стенограмма | D | Структурированный протокол vs дословная расшифровка | draft |
| TL.D.004 | Live-бот vs загрузка записи | D | Два канала захвата аудио | draft |
| TL.D.005 | Корпоративный таймбот vs задачник-ассистент | D | Два разных продукта на базе TimeList | draft |
| TL.D.006 | Закрытый контур vs зарубежные сервисы | D | Российский/безопасный vs иностранный | draft |
| TL.D.007 | Боль vs бизнес-процесс | D | Позиционирование корпоративного продукта | draft |
| TL.D.008 | Специализация vs универсальные LLM | D | TimeList заточен под совещания | draft |
| TL.D.009 | Активный vs пассивный участник | D | Два режима участия во встрече | draft |
| TL.D.010 | Пилот vs полноценное внедрение | D | Ограниченный тест vs масштабирование | draft |
| TL.R.001 | Секретарь-протоколист | R | Проверяет и дорабатывает автопротокол | draft |
| TL.R.002 | Менеджер проекта | R | Ведёт обсуждение, не теряет договорённости | draft |
| TL.R.003 | Пассивный участник | R | Получает индивидуальное резюме | draft |
| TL.R.004 | ЛПР / владелец процесса | R | Принимает стандарт и бюджет | draft |
| TL.R.005 | Интегратор / бизнес-консультант | R | Продаёт и внедряет TimeList | draft |
| TL.R.006 | Разработчик чат-бота | R | Подключает бота к чатам | draft |
| TL.R.007 | Методист / тренер | R | Обучает культуре записи | draft |
| TL.ENT.001 | Встреча | ENT | Аудио/видео событие для расшифровки | draft |
| TL.ENT.002 | Стенограмма | ENT | Дословная расшифровка | draft |
| TL.ENT.003 | Автопротокол | ENT | Структурированный результат встречи | draft |
| TL.ENT.004 | Бот TimeList в ВКС | ENT | Участник встречи, записывающий аудио | draft |
| TL.ENT.005 | Спикер | ENT | Идентифицированный участник разговора | draft |
| TL.ENT.006 | AI-ассистент | ENT | Чат по конкретной встрече | draft |
| TL.ENT.007 | Поручение | ENT | Действие из протокола | draft |
| TL.ENT.008 | База знаний встреч | ENT | Хранилище расшифровок и протоколов | draft |
| TL.ENT.009 | Корпоративный таймбот | ENT | Бот в корпоративных чатах | draft |
| TL.ENT.010 | Задачник-ассистент | ENT | Прототип голосового ввода задач | draft |
| TL.ENT.011 | Тариф | ENT | Модель оплаты | draft |
| TL.M.001 | Демо на живой встрече | M | Главный метод продажи | current |
| TL.M.002 | Discovery-продажа | M | Выяснение задачи заказчика | current |
| TL.M.003 | Закрытие возражений | M | Работа с типовыми сомнениями | current |
| TL.M.004 | Создание стенограммы | M | Захват и расшифровка встречи | current |
| TL.M.005 | Выгрузка в Bitrix24 | M | Импорт поручений из протокола | current |
| TL.M.006 | Пилот 3 недели | M | Ограниченное внедрение | current |
| TL.M.007 | Обучение культуры записи | M | Обучение пользователей | current |
| TL.M.008 | Сбор сценариев через чат | M | Выявление сценариев у клиента | current |
| TL.M.009 | Позиционирование статьи | M | Структура лендо-статьи | current |
| TL.WP.001 | Расшифровка | WP | Стенограмма встречи | current |
| TL.WP.002 | Автопротокол | WP | Структурированный документ | current |
| TL.WP.003 | Поручения в Bitrix24 | WP | Задачи из протокола | current |
| TL.WP.004 | Коммерческое предложение | WP | Прайс и тарифы | current |
| TL.WP.005 | Памятка по регламенту | WP | Инструкция для сотрудников | current |
| TL.WP.006 | Демо-доступ | WP | Доступ для самостоятельной проверки | current |
| TL.WP.007 | Лендо-статья | WP | Продающая статья про таймбота | current |
| TL.WP.008 | Отчёт по MAX-чатам | WP | Сводка задач из чатов | current |
| TL.FM.001 | Неверная идентификация спикеров | FM | Ошибка распределения реплик | current |
| TL.FM.002 | Непредсказуемый захват задач | FM | Автопротокол нестабилен | current |
| TL.FM.003 | Дублирование систем | FM | MAX и Bitrix24 конкурируют | current |
| TL.FM.004 | Перегруз сущностями | FM | Слишком много нового в пилоте | current |
| TL.FM.005 | Передача данных в зарубежный сервис | FM | Нарушение 152-ФЗ | current |
| TL.FM.006 | Продвижение не тому ЛПР | FM | Неправильный акцент в позиционировании | current |
| TL.FM.007 | Конкуренция встроенных стенограмм | FM | Клиент не видит разницы | current |

---

## Change Log

| Date | Change | Author |
|------|--------|--------|
| 2026-08-11 | Initial creation from 8 sources | kimi |
| 2026-08-11 | Extracted method, work product and failure mode cards into standalone files (24 maps total) | kimi |
| 2026-08-11 | Added external references: video overview and pricing | kimi |
