# Gort livestock prices

Irish livestock prices for the Gort Farm Ledger app, updated each morning by a scheduled task.
The app reads these files when it opens.

| File | What it holds |
|---|---|
| `prices.json` | Factory base quotes, official R3 prices, lamb quotes and recent mart reports (€/kg) |
| `kill.json` | Weekly DAFM factory cattle and sheep kill for 2026 |
| `history.json` | Weekly factory quote history |
| `monthly.json` | Monthly average R3 prices paid since January 2025 |

Figures are taken from published sources (Agriland, IFA, Irish Farmers Journal, Irish Examiner,
mart reports, DAFM/EU Commission). Each file records its sources. Nothing is estimated.
