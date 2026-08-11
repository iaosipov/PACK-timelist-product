# Ontology: TimeList Product

> Domain ontology per SPF.SPEC.002.
> Complete registry of entity types, key terms, and relationships for this Pack.

---

## 1. Entity Types

| Code | Type | FPF/SPF Concept | Definition | ≠ (what it is NOT) | Source |
|------|------|-----------------|------------|---------------------|--------|
| `M` | Method | U.Method | A repeatable practice for selling, deploying, or using TimeList. | ≠ scenario, ≠ tool | SPF (base) |
| `WP` | Work Product | U.Work + U.Episteme | A concrete artifact produced when applying TimeList methods. | ≠ method description | SPF (base) |
| `FM` | Failure Mode | — (SPF-specific) | A typical error when selling, deploying, or using TimeList. | ≠ code bug | SPF (base) |
| `D` | Distinction | A.7 Strict Distinction | A conceptual boundary that clarifies the TimeList domain. | ≠ fact, ≠ definition | SPF (base) |
| `R` | Role | U.RoleAssignment | A functional position occupied when performing TimeList methods. | ≠ person, ≠ job title | SPF (base) |
| `CHR` | Characteristic | U.Characteristic | A measurable attribute of TimeList quality or usage. | ≠ metric, ≠ indicator | SPF (base) |
| `SOTA` | SoTA Annotation | — (SPF-specific) | A current insight or decision about TimeList with revision criterion. | ≠ literature review | SPF (base) |
| `MAP` | Map | U.Episteme | A visual or structured overview of the TimeList domain. | ≠ content | SPF (base) |
| `ENT` | Entity | U.Object | A thing in the TimeList domain with attributes and relationships. | ≠ role, ≠ method | Pack (extended) |

---

## 2. Domain Glossary

| Term (RU) | Term (EN) | Definition | Parent Concept (SPF) | Related entity |
|-----------|-----------|-----------|---------------------|----------------|
| Таймлист | TimeList | ИИ-сервис расшифровки аудио и автопротоколирования совещаний. | U.System | TL.ENT.001 |
| Стенограмма | Transcript | Дословная текстовая расшифровка встречи с разбивкой по спикерам. | U.Work | TL.WP.001 |
| Автопротокол | Auto-protocol | Структурированный результат встречи (решения, поручения, сроки). | U.Work | TL.WP.002 |
| Бот TimeList | TimeList bot | Участник ВКС, который записывает аудио и отправляет на расшифровку. | U.System | TL.ENT.004 |
| NoTaker AI | NoTaker AI | Класс систем: не универсальный чат, а специализированный агент для фиксации и структурирования содержания встреч. | U.Concept | TL.D.001 |
| On-premise | On-premise | Развёртывание на серверах заказчика. | U.Mode | TL.D.002 |
| Корпоративный таймбот | Corporate timebot | Бот в корпоративных чатах (Битрикс/Telegram/MAX), собирающий задачи из переписки. | U.System | TL.ENT.009 |

---

## 3. Relationships Between Types

| Subject | Relationship | Object | Example |
|---------|-------------|--------|---------|
| Method | produces → | Work Product | TL.M.004 → TL.WP.001 |
| Method | performed by → | Role | TL.M.001 → TL.R.005 |
| Failure Mode | violates ← | Method | TL.FM.001 ← TL.M.004 |
| Entity | participates in → | Method | TL.ENT.004 → TL.M.004 |
| Work Product | consumed by → | Role | TL.WP.002 → TL.R.002 |

---

## 4. Abbreviations

| Abbreviation | Full form (RU) | Full form (EN) | Level |
|-------------|---------------|----------------|-------|
| ВКС | Видеоконференцсвязь | Video conferencing | Pack |
| NDA | Соглашение о неразглашении | Non-disclosure agreement | SPF |
| GPU | Графический процессор | Graphics processing unit | SPF |
| SLA | Соглашение об уровне обслуживания | Service-level agreement | SPF |

---

_Ontology per SPF.SPEC.002. Pack ID: timelist_
