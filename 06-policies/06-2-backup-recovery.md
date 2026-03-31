### 6.2 Backup & Recovery Policy

## Zweck

> Sicherstellung der Verfügbarkeit und Wiederherstellbarkeit kritischer Daten und Systeme nach Ausfällen oder Angriffen.

## Geltungsbereich

> Webshop‑Datenbank, CRM, Fileshare „Finanzen“, E‑Mail‑Archive.

## Backup‑Regeln

**3‑2‑1‑Regel:**

* 3 Kopien der Daten
* auf 2 verschiedenen Medien
* 1 Kopie offsite / Cloud

## Frequenz & Retention

| Asset | Frequenz | Retention |
| --- | --- | --- |
| Webshop‑DB | täglich | 30 Tage |
| CRM | täglich | 90 Tage |
| Fileshare | wöchentlich | 1 Jahr |
| E‑Mail | Cloud‑Backup | 1 Jahr |

## Recovery‑Ziele (RPO / RTO)

| Asset | RPO (max. Datenverlust) | RTO (max. Ausfallzeit) |
| --- | --- | --- |
| Webshop‑DB | 24 Stunden | 4 Stunden |
| CRM | 24 Stunden | 8 Stunden |
| Fileshare | 1 Woche | 24 Stunden |

## Test & Review

* **Restore‑Tests**: Mindestens 1× jährlich dokumentiert durchführen
* **Review**: Jährliche Überprüfung der Backup‑Prozesse und RPO/RTO‑Ziele