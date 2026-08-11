# Bounded Context: TimeList Product

---

## Domain Name

**TimeList как продукт**

(English: TimeList Product)

---

## Object of Description

**Продукт TimeList** as an object of engineering description.

| Object IS | Object IS NOT |
|-----------|---------------|
| ИИ-сервис расшифровки и автопротоколирования совещаний | Конкретная установка у одного клиента |
| Carrier of measurable attributes (точность, стоимость, скорость) | Учебный курс по тайм-менеджменту |
| Instance of product type | Личный опыт одного пользователя |

---

## Scope (What's In)

| Element | Description | Example |
|---------|-------------|---------|
| **Расшифровка** | Дословная стенограмма встречи с разбивкой по спикерам | Стенограмма совещания в Word |
| **Автопротокол** | Структурированный результат: решения, поручения, сроки | Excel-файл с задачами |
| **AI-ассистент** | Вопросы по конкретной встрече или малому контексту | «Какие решения приняли по пункту 3?» |
| **Интеграция** | Экспорт задач в Bitrix24, бот в MAX/Telegram | Импорт Excel в Bitrix24 |
| **Продажа и внедрение** | Демо, discovery, пилот, обучение | 3-недельный пилот с 6 человек |
| **Позиционирование** | NoTaker AI, закрытый контур, специализация под совещания | Сравнение с встроенными стенограммами |

---

## Non-Goals (What's Out)

| Excluded | Reason | Where It Belongs |
|----------|--------|------------------|
| TimeInvest / МСВ | Научная модель тайм-менеджмента, не продукт | PACK-timeinvest-method (планируется) |
| Шахты/ракеты/яйца/волк | Метафоры методологии, не продукта | PACK-timeinvest-method |
| Исходный код TimeList | Реализация, не доменное знание | Репозиторий разработки 1С/TimeList |
| Общая методология совещаний | Без привязки к инструменту TimeList | PACK-organizer-course |

---

## Truth Criteria

Assertions in this pack are considered justified if:

| Criterion | Test |
|----------|------|
| **Observable indicators** | Можно показать в демо или найти в транскрибации встречи |
| **Verifiable work products** | Есть пример файла, скриншот или цитата из источника |
| **Distinction test** | Можно объяснить разницу одним предложением и привести пример |
| **SoTA + revision criterion** | Указано, какое событие/данные могут изменить утверждение |

**Forbidden**:
- Assertions without observable indicators
- Methods without work products
- SoTA without revision criterion

---

## Downstream Note

**Практическое применение** — outside scope of this pack.

| Pack describes | Downstream uses |
|----------------|-----------------|
| Что такое TimeList и как он работает | Продажные материалы, обучение, интеграции |
| Какие ошибки встречаются | Чек-листы внедрения и аудита |
| Как позиционировать | Лендо-статьи, КП, демо-скрипты |

---

## Key Distinctions

| Distinction | In This Pack |
|-------------|--------------|
| NoTaker AI vs универсальный ИИ-чат | TL.D.001 |
| Облако vs On-premise | TL.D.002 |
| Автопротокол vs стенограмма | TL.D.003 |
| Боль vs бизнес-процесс в позиционировании | TL.D.007 |

---

## Version

| Attribute | Value |
|-----------|-------|
| Bounded context version | 0.1.0 |
| Created | 2026-08-11 |
| Last updated | 2026-08-11 |
| Pack ID | timelist |
