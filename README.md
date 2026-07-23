# FinanceFlow — Budget Tracker

A single-file, client-side personal budget tracker built with plain HTML,
CSS, and JavaScript — no backend, no build step, no installation. Just open
the HTML file in a browser and start tracking your finances.

## Features

- **Transactions** — log income and expenses with categories, and browse
  them in a filterable, categorized list.
- **Recurring items** — track recurring bills, subscriptions, and regular
  income.
- **Budgets & planning** — set budget limits per category and track spending
  against them.
- **Dashboards & charts** (via [Chart.js](https://www.chartjs.org/)):
  - Cash flow over a configurable number of months
  - Income/expense breakdown (donut chart)
  - Savings trend
  - Net worth over time
  - Spending trend and category breakdown
- **Receipt scanning (OCR)** — upload a photo of a receipt and automatically
  extract its text using [Tesseract.js](https://tesseract.projectnaptha.com/),
  making manual transaction entry faster.
- **Dark / light theme** — toggle between color themes.
- **Multilingual UI** — switch between English and Indonesian (Bahasa
  Indonesia) at any time; the choice is remembered.
- **Fully local** — all data (transactions, budgets, recurring items,
  language/theme preference) is stored in the browser's `localStorage`
  under keys prefixed `ff_`. Nothing is sent to a server; there are no
  accounts and no external API keys required (Chart.js and Tesseract.js are
  loaded as client-side libraries only).

## Getting started

No installation needed — this is a static, single-page app.

1. Download or clone this repository.
2. Open `BudgetTrackerWebApp.html` directly in any modern browser (double-click it, or right-click → Open with → your browser).
3. Start adding transactions, budgets, and recurring items — everything is saved automatically to your browser's local storage.

> **Note:** Since data is stored in `localStorage`, it is tied to a specific
> browser profile on a specific device. Clearing browser data/cache will
> erase your entries. There is currently no export/import or cloud sync
> feature.

## Tech stack

- Vanilla HTML / CSS / JavaScript (no framework, no build tooling)
- [Chart.js](https://www.chartjs.org/) for data visualization
- [Tesseract.js](https://tesseract.projectnaptha.com/) for receipt OCR

## License

No license file is currently included in this repository. Add one (e.g. MIT)
if you intend to share or open-source this project.
