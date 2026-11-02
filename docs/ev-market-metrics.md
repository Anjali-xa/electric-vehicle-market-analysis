# Electric Vehicle Market Metrics

## Metrics to define
| Metric | Recommended treatment |
|---|---|
| Vehicle registrations | Count records after deduplicating registration IDs |
| Market share | EV registrations / all vehicle registrations for the same geography and period |
| Model mix | Registrations grouped by make and model |
| Range | Preserve the source unit; convert only in a documented derived field |
| Charging availability | Report charger counts with geography and connector definitions |

## Data checks
- Standardise manufacturer and model names without losing source values.
- Confirm whether records represent registrations, sales, or active vehicles.
- Harmonise geography codes and reporting periods.
- Check duplicate vehicle identifiers and impossible model years.
- Keep kilometres and miles distinct until conversion is explicit.
- Separate battery-electric and plug-in hybrid categories where possible.

## Analysis questions
1. How are registrations changing by year and region?
2. Which manufacturers and models lead within each segment?
3. Is market share changing at different rates across regions?
4. How does charging infrastructure coverage vary geographically?

## Comparability
Policy incentives, reporting coverage, and vehicle classification differ by jurisdiction. Record these limitations before comparing regions.