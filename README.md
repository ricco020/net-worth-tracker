# Net worth tracker

Free, single-file net worth tracker with monthly snapshots. List what you own and what you owe once, save a snapshot each month, and it shows:

- net worth and liquid net worth (cash and taxable investments minus debts not secured by the home or a vehicle),
- what moved it since last month, line by line (an asset that grew or a debt that shrank adds to net worth), with the debt paid down singled out. The lines always add up exactly to the change in net worth,
- the average monthly change since your first snapshot and the months to reach a goal at that pace (a straight line, not a forecast),
- a CSV export of every snapshot (one column per account or debt) to keep as a backup or open in a spreadsheet.

Use it online: https://ricco020.github.io/net-worth-tracker/

Checked on 300 random histories (1 to 8 snapshots over 5 years, 7 line types, names differing only by case or spaces, 1 397 changed lines) against a separate Python implementation: 0 difference, and the line effects always sum to the change in net worth.

Printable version (assets and debts snapshot with subtotals, 24-month log, chart grid to plot by hand): https://tidysheets.shop/p/net-worth-tracker-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
