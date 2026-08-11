# Failure Modes — TimeList Product

---

## What is a Failure Mode

Per SPF: a **failure mode** is a typical error when applying methods in this domain. It is not a code bug, not a random mistake, and not a personal fault.

---

## Failure Modes Index

| ID | Failure Mode | When It Happens | Effect |
|----|---------------|------------------|--------|
| [TL.FM.001](./TL.FM.001-speaker-identification.md) | Неверная идентификация спикеров | TrueConf без активных окон, плохой звук, несколько голосов одновременно | Ручная доработка протокола |
| [TL.FM.002](./TL.FM.002-task-capture-unpredictable.md) | Непредсказуемый захват задач из протокола | Плохое аудио, нечёткие формулировки | Менеджер тратит время на доработку |
| [TL.FM.003](./TL.FM.003-task-system-duplication.md) | Дублирование систем контроля задач | MAX и Bitrix24 используются параллельно | Задачи теряются, дисциплина падает |
| [TL.FM.004](./TL.FM.004-pilot-entity-overload.md) | Перегруз сущностями в пилоте | Одновременно запускают TimeList, Bitrix24, ботов | Ничего не приживается |
| [TL.FM.005](./TL.FM.005-foreign-service-data-leak.md) | Передача данных в зарубежный сервис | Использование ChatGPT для расшифровки | Штраф до 6 млн, утечка данных |
| [TL.FM.006](./TL.FM.006-wrong-lpd-targeting.md) | Продвижение не тому ЛПР | Акцент только на личной боли высшего руководителя | Посыл не резонирует |
| [TL.FM.007](./TL.FM.007-vcs-built-in-transcripts.md) | Конкуренция со встроенными стенограммами | Клиент сравнивает с Контур.Толк/Телемост/Дион | Выбор более дешёвого решения |
