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


## v1.4
- Added editable Starting Mortgage Excess in Loan Setup.
- Each month now shows Mortgage Excess beside Credits, Debits and Difference.
- Mortgage Excess starts from the entered opening amount and carries forward each month's Difference.
- A negative Mortgage Excess is highlighted; a positive value is kept visually neutral so it is not presented as spending money.
- Existing backups remain import-compatible and default Mortgage Excess to $0 until entered.
