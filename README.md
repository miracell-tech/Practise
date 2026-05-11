# Practise
# Kundenanalyse mit pandas

## Übersicht
Dieses Übungsprojekt mit frei zugänglichen Daten analysiert Marketing- und Kundendaten mit Python und pandas. Ziel war es, Rohdaten aus einer Excel-Datei zu bereinigen, neue Features zu erstellen und erste statistische Insights über das Kaufverhalten von Kunden zu gewinnen.

##  Tools
- Python
- pandas
- matplotlib
- openpyxl

## Funktionen
- Import von Excel-Daten
- Bereinigung fehlender Werte
- Entfernen von Duplikaten
- Standardisierung von Spaltennamen
- Konvertierung von Datentypen
- Features überischtlicher benennen (Alter, Gesamtausgaben, Gesamtkäufe)
- Entfernung unrealistischer Daten (ausreißer)
-  Zusammenfassung der Daten

## Beispiel-Insights
- Durchschnittliches Kundeneinkommen und Kaufverhalten analysiert
- Gesamt-Ausgaben pro Kunde berechnet
- Auffällige Ausreißer in Alters- und Einkommensdaten erkannt

## Nächste Schritte
- Datenvisualisierung mit matplotlib
- Kundensegmentierung
- Interaktive Dashboards
- Erweiterte statistische Analysen

## Ergebnisse

Nach der Datenbereinigung ergaben sich folgende Ergebnisse:

- Ursprüngliche Datengröße: 2240 Zeilen und 29 Spalten
- Bereinigte Datengröße: 2217 Zeilen und 32 Spalten

###  KPIs:
- Durchschnittsalter der Kunden: ca. 57 Jahre
- Durchschnittliches Einkommen: ca. 51.000
- Durchschnittliche Gesamtausgaben: ca. 599

###  Datenbereinigung
- Fehlende Werte wurden entfernt oder ersetzt
- Duplikate wurden entfernt
- Unrealistische Alters- und Einkommenswerte wurden gefiltert

### Neue berechnete Features
- Alter der Kunden
- Gesamtausgaben pro Kunde
- Gesamtanzahl der Käufe

### Erkenntnisse
- Kunden mit höherem Einkommen geben tendenziell mehr aus
- Die meisten Kunden befinden sich im mittleren Altersbereich
- Einige starke Ausreißer in Einkommen und Alter wurden identifiziert
Beispiel-Insight

Einige Kunden mit sehr hohem Einkommen zeigen geringe Gesamtausgaben. Das zeigt, dass Einkommen nicht automatisch mit Kaufverhalten korreliert.
