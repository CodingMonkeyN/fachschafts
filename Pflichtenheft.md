# Pflichtenheft - Strichlisten-App für Getränke

## Ausgangssituation

Aktuell verwenden viele Vereine eine Strichliste, um Getränkeverkäufe zu tätigen. Dabei müssen die Vereinsmitglieder entweder im Vorhinein oder in einem bestimmten Interval (bspw. monatlich) die Kosten für ihre Getränke begleichen.

Für die finanzielle Verwaltung ist der Kassenward verantwortlich, welcher Einzahlungen vornimmt und die Kasse für Direktzahlung regelmäßig leert, sowie die gesamte Kassensumme regelmäßig prüft.

Die Getränkebestellungen werden durch den Getränkeward ausgelöst. Dieser muss vorausschauend planen, wann die nächste Getränkebestellung ausgelöst werden muss und welche Getränke in welchem Umfang bestellt werden müssen.

## Probleme

- Nutzer hat nur vor Ort auf der Strichliste Überblick über seine Ausgaben
- Nutzer muss Beträge bar begleichen
- Kassenward muss zwingend vor Ort sein, um Einzahlung zu verifizieren
- Getränkeward hat keinen guten Überblick über Getränkebestand
- Getränkeward muss optimalen Bestellzeitpunkt abschätzen

## Features

**PFLICHT:**
- Virtuelles Lager
- Virtueller Kontostand
- Produkt/Preis Mapping
- Mangementoberfläche
- Rechteverwaltung
- Meherer Sprachen Spupport (I18N)

**OPTINAL:**
- Statistiken
- Push-Benachrichtigungen

## Technik

- Frontend: Angular
  - Warum? Vorwissen vorhanden
- Backend: C#
  - Warum? Vorwissen vorhanden
- Datenbank: PostgreSQL
  - Warum? OpenSource, gute Performance, Struckturierte Daten &rArr; relationales Datenbankschema