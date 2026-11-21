## Deloitte Australia Data Analytics Job Simulation

Simulation completed on Forage (November 2026). The data and the client are fictional.

## Task 1: Tableau dashboard
- Question: which factories and device types have the most potential downtime?
- Method: calculated field `Unhealthy` (10 per unhealthy status), bar charts per factory and per device type, dashboard with filter.
- Finding: <daikibo-factory-seiko>

## Task 2: Pay equality classification (Excel)
- Question: classify each equality score as Fair, Unfair or Highly Discriminative.
- Formula used: `=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))`
- P.S.: In the Greek locale of Google Sheets, the equivalent of the above formula is: `=IF(ABS(C2)<=10;"Fair";IF(ABS(C2)<=20;"Unfair";"Highly Discriminative"))`

## Tools
Tableau, Excel / Google Sheets
