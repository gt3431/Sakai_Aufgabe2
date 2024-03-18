# Sakai_Aufgabe2

## Name und Identifikationsnummer
UC 1.03 (Alarm bei zu hoher Herzfrequenz)
## Beschreibung
Überschreitet die Herzrequenz während dem Test einen bestimmten wert soll ein Alarm ausgegeben werden
## Beteiligte Akteure
Diagnostiker:in, Proband:in
## Status
Programmierung offen
## Verwendete Anwendungsfälle
UC 1.07 (Abbruch des Leistungstests)
## Auslöser
Herzfrequenz über 150BPM
## Vorbedingungen
UC 1.01 (Probandin anlegen), UC 1.02 (Leistungstest anlegen)
## Invarianten
Aufzeichnung darf nicht gestoppt werden
## Nachbedingung/Ergebnis
Eventueller Abrruch der Messung (UC 1.07)
## Standardablauf
Diagnostiker starte den Test. Proband beendet den Test. Normalerweise tritt keine Alarmeldung auf
## Alternative Ablaufschritte
Sollte Herzfrequenz beim Test zu hoch werden wird die Warnung ausgegeben und eventuell wird vom Diagnostiker der Test abgebrochen
## Hinweise
Pulsschwelle ist noch zu klären
## Änderungsgeschichte
13:02; 18.03.2024; Tobias Gasteiger
