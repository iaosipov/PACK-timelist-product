# Service Clauses — TimeList Product

---

## What is a Service Clause

Per SPF: a **service clause** documents a boundary condition, constraint, or commitment that must be respected when using methods in this domain.

---

## Service Clauses Index

| ID | Clause | Type | Applies To |
|----|--------|------|------------|
| TL.SC.001 | 152-ФЗ и персональные данные | Legal | All deployments in Russia |
| TL.SC.002 | Реестр отечественного ПО | Compliance | On-premise and government clients |
| TL.SC.003 | NDA в тарифах | Commercial | Corporate clients |
| TL.SC.004 | Лимит AI-чата до 5 встреч | Functional | AI-ассистент |
| TL.SC.005 | Максимальный размер загружаемой записи 6ч / 3ГБ | Technical | File upload channel |
| TL.SC.006 | Пилот ограничен 3 неделями и 6–7 человек | Project | Pilot method TL.M.006 |
| TL.SC.007 | Корпоративный таймбот ≠ задачник-ассистент | Product boundary | Marketing and sales |
| TL.SC.008 | TimeList не покрывает одновременную речь и плохой звук | Quality constraint | Audio capture |

---

## Detailed Service Clauses

### TL.SC.001 — 152-ФЗ и персональные данные

**Clause**: Для российских юридических лиц передача аудио, содержащего персональные данные, в зарубежные сервисы запрещена. TimeList должен использоваться в закрытом контуре.

**Type**: Legal

**Applies to**: All deployments in Russia

**Related entities**: TL.D.006, TL.FM.005

---

### TL.SC.002 — Реестр отечественного ПО

**Clause**: TimeList включён в реестр отечественного ПО. Это аргумент для госкорпораций и компаний с требованиями импортозамещения.

**Type**: Compliance

**Applies to**: On-premise and government clients

**Related entities**: TL.D.002, TL.D.006

---

### TL.SC.003 — NDA в тарифах

**Clause**: В корпоративных тарифах TimeList предусмотрен NDA.

**Type**: Commercial

**Applies to**: Corporate clients

**Related entities**: TL.D.002, TL.M.003

---

### TL.SC.004 — Лимит AI-чата до 5 встреч

**Clause**: AI-ассистент позволяет задавать вопросы в контексте до 5 встреч. Кросс-базовый поиск — по всей базе с фильтрами и тегами.

**Type**: Functional

**Applies to**: AI-ассистент

**Related entities**: TL.ENT.006, TL.ENT.008

---

### TL.SC.005 — Максимальный размер загружаемой записи 6ч / 3ГБ

**Clause**: Загрузка готовой записи ограничена 6 часами и 3 ГБ.

**Type**: Technical

**Applies to**: File upload channel

**Related entities**: TL.D.004, TL.ENT.004

---

### TL.SC.006 — Пилот ограничен 3 неделями и 6–7 человек

**Clause**: Пилотная формула TimeList + Bitrix24 + MAX-боты рассчитана на 3 недели и 6–7 сотрудников.

**Type**: Project

**Applies to**: Pilot method TL.M.006

**Related entities**: TL.D.010, TL.M.006

---

### TL.SC.007 — Корпоративный таймбот ≠ задачник-ассистент

**Clause**: В маркетинге и продажах корпоративный таймбот и задачник-ассистент продвигаются отдельно. Задачник-ассистент пока не сформирован как продукт.

**Type**: Product boundary

**Applies to**: Marketing and sales

**Related entities**: TL.D.005, TL.ENT.009, TL.ENT.010

---

### TL.SC.008 — TimeList не покрывает одновременную речь и плохой звук

**Clause**: Качество стенограммы зависит от качества аудио. Одновременная речь и плохой звук снижают точность и идентификацию спикеров.

**Type**: Quality constraint

**Applies to**: Audio capture

**Related entities**: TL.FM.001, TL.FM.002, TL.M.007
