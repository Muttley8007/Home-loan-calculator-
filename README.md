# Mortgage Ledger v1.2

Standalone mortgage-ledger prototype.

## v1.2 changes
- Added Edit for ledger transactions and recurring series.
- Editing Repeat Until earlier removes future generated instances.
- Editing Repeat Until later adds generated instances using the same recurring rule.
- Editing amount, type, date, description or frequency updates the saved series.
- Delete removes the entire recurring series.
- No confirmation prompt is used for shortening or extending Repeat Until.
- Existing v1.1 backups remain import-compatible.

The app stores data locally in the browser. Export backups regularly.


## v1.3
- Added an Indefinite option for recurring ledger entries. When selected, the series repeats for the life of the loan without requiring a far-future Repeat Until date.
