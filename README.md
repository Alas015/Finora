# Finora — Personal Finance Manager

A local-first Progressive Web App starter for personal budgeting.

## Run locally
Because service workers require localhost or HTTPS, run a local server in this folder:
- Python: `python -m http.server 8000`
- Open `http://localhost:8000`

## Included in this first build
- Overview dashboard: balances, income, expenses, savings, recent activity
- Transactions: add, search and filter income/expenses
- Accounts: cash, bank and custom accounts with opening balances
- Monthly category budgets
- Savings goals
- Debt records
- Basic reports
- AZN/USD/EUR/TRY display currency selector
- Azerbaijani and English interface
- Dark and light themes
- IndexedDB local persistence
- JSON backup/restore and CSV export
- PWA manifest and offline service worker

## Important scope notes
- This is an early working foundation, not a finished accounting product.
- Changing the display currency currently changes formatting only; it does not perform historical exchange-rate conversion.
- Account transfers, recurring transactions, attachments/receipts, investments, advanced reports, multi-device cloud sync, authentication and encryption are planned next.
- The current database is local to the browser profile. Export backups regularly. Cloud sync requires a backend and secure authentication.
