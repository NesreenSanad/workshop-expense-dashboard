# Workshop Expense Analysis Dashboard

An Arabic (right-to-left) dashboard that turns a metal machining workshop's daily expense records and bank statements into a clear monthly picture of where the money goes.

> **Demo data:** all amounts and names in this version are anonymised. The real dashboard runs on the workshop's private data.

**Live demo:** [open the dashboard](https://nesreensanad.github.io/workshop-expense-dashboard/)

## What it shows

- Executive summary: total spend, monthly average, highest and lowest months, labour cost share
- Monthly spending, and the change from one month to the next
- Labour cost as a share of each month's spending
- Expenses compared with bank debits and credits
- Bank balance range per month, and the balance over time
- Spending by source as a treemap and a ranked table

## My role

I'm the systems analyst behind this project, part of a wider effort to digitise my family's metal machining workshop. I:

- Analysed how the workshop records daily expenses and bank movements
- Defined the questions the owners need answered and the rules for grouping expenses
- Designed the dashboard layout and charts for non-technical, Arabic-speaking users
- Directed AI tools (Claude) to build and refine the implementation, and checked every figure against the source records

## Tech

A single self-contained HTML page with plain JavaScript and SVG charts. It has no dependencies and works offline, in light and dark mode.
