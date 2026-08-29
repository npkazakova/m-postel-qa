# Manual QA Documentation — E-commerce Website (m-postel.ru)

Complete manual testing documentation for a production e-commerce website
(online bedding store): from requirements analysis and a QA roadmap to test
plans, test cases and bug reports. Built as a portfolio project to show
end-to-end manual QA process on a real product.

**Language:** Russian · **Format:** Markdown, module by module

## What's inside

| Folder | Contents |
|---|---|
| `docs/` | project description, requirements for testing, QA roadmap |
| `test-plans/` | smoke / functional / UI test plans |
| `test-cases/` | test cases by module: user registration, catalog, cart, checkout |
| `reports/` | bug report template, example bug reports, statistics by priority/status/module |

**Volume:** 60+ structured test cases (steps, preconditions, expected results),
3 test plans, documented bug reports with severity & priority classification.

**Test design applied:** equivalence partitioning, boundary values, negative
scenarios, UI checklist approach.

## Quick start
1. Start with `docs/roadmap.md` for the process overview
2. See `docs/project-description.md` for the functionality scope
3. Test plans: `test-plans/smoke-test-plan.md` first

---

# Тестирование сайта m-postel.ru

## Описание проекта
Данный проект содержит документацию и планы тестирования для мануального тестирования сайта интернет-магазина постельного белья [m-postel.ru](https://www.m-postel.ru).

## Структура документации

### 📁 Основные документы
- `docs/roadmap.md` - Роадмап работы по тестированию
- `docs/project-description.md` - Описание проекта и функциональности
- `docs/requirements.md` - Требования к тестированию

### 📁 Планы тестирования
- `test-plans/smoke-test-plan.md` - План смоук-тестирования
- `test-plans/functional-test-plan.md` - План функционального тестирования
- `test-plans/ui-test-plan.md` - План UI тестирования

### 📁 Тест-кейсы
- `test-cases/` - Директория с тест-кейсами по модулям
- `test-cases/user-registration.md` - Тест-кейсы регистрации пользователей
- `test-cases/catalog.md` - Тест-кейсы каталога товаров
- `test-cases/cart.md` - Тест-кейсы корзины
- `test-cases/checkout.md` - Тест-кейсы оформления заказа

### 📁 Отчеты
- `reports/` - Директория для отчетов о тестировании
- `reports/bug-reports.md` - Отчеты о найденных багах

## Техническая информация
- **Сайт**: https://www.m-postel.ru
- **CMS**: Bitrix Site Manager
- **Сервер**: nginx/1.18.0
- **PHP**: 7.4.30

## Статус проекта
🟡 В разработке — документация и планы тестирования покрывают 4 модуля (регистрация, каталог, корзина, чекаут)
