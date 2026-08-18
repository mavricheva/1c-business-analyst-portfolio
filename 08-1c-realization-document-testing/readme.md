# Тестирование документа «Реализация» в 1С

## Описание проекта

Функциональное тестирование документа «Реализация» в конфигурации 1С ERP
для салона красоты. Проверено соответствие формы, списка, табличных
частей, проведения, создания на основании и печатной формы требованиям ТЗ.

## Моя роль

Тестировщик / 1С-аналитик.

- Проанализировала требования ТЗ к документу «Реализация».
- Подготовила чек-лист и тест-кейс TC-001.
- Проверила позитивные и негативные сценарии.
- Зарегистрировала 7 дефектов с шагами воспроизведения и ожидаемым результатом.

## Объект тестирования

Документ «Реализация» в подсистеме «Продажи».

Проверялись: список и форма, шапка, ТЧ «Товары» и «Услуги», автоподстановка
цен и расчёт сумм, создание на основании «Предварительной записи», проведение,
движения по регистрам, создание ПКО и печатная форма.


## Артефакты

| Материал | Описание |
|---|---|
| [Чек-лист](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/chek-list.pdf) | Проверка формы, ТЧ, проведения, связанных документов и печати |
| [Тест-кейс TC-001](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/TC-001.pdf) | Комплексный сценарий проверки «Реализации» |
| [BR-001](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-001.pdf) | Отсутствует поле «Сумма документа» |
| [BR-002](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-002.pdf) | Некорректный отбор в ТЧ «Товары» |
| [BR-003](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-003.pdf) | Некорректный отбор в ТЧ «Услуги» |
| [BR-004](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-004.pdf) | Невозможно проверить запрет редактирования суммы |
| [BR-005](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-005.pdf) | Отсутствие контроля изменения цены |
| [BR-006](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-006.pdf) | Отсутствует склад в печатной форме |
| [BR-007](https://github.com/mavricheva/1c-business-analyst-portfolio/blob/main/08-1c-realization-document-testing/BR-007.pdf) | Неполный перенос данных из «Предварительной записи» |

## Результаты

Подготовлены чек-лист, тест-кейс и семь отчётов о дефектах.
Зафиксированы ожидаемое и фактическое поведение, шаги воспроизведения,
приоритет и серьёзность, версия системы и окружение, связь с требованиями ТЗ.

## Тестовое окружение

1С:Предприятие 8.3, конфигурация JUST LOOK 1.0.0.1, платформа 8.3.27.1508,
тонкий клиент, Windows 11, пользователь Администратор.

## Стек

Функциональное тестирование, 1С:Предприятие 8.3, тест-кейсы, чек-листы,
отчёты о дефектах, анализ ТЗ
