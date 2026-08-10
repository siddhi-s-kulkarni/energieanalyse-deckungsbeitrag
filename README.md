# Energieanalyse Deckungsbeitrag

Portfolio-Projekt zur Demonstration praxisnaher Analysekompetenzen im Bereich Energiewirtschaft — mit Fokus auf Bilanzierung, Beschaffung und Deckungsbeitragskalkulation für SLP-Kunden.

Dieses Projekt präsentiert eine Analyse des Deckungsbeitrags eines Stadtwerks für die Versorgung seiner Kunden mit einem SLP (Standardlastprofil).

Der Deckungsbeitrag berechnet sich wie folgt:
Umsatzerlöse – Beschaffungskosten – Ausgleichsenergiekosten  
Ausgleichsenergiekosten entstehen aufgrund von Abweichungen zwischen der prognostizierten und der tatsächlichen Last und werden unter Zugrundelegung eines angenommenen reBAP-Preises berechnet.

Die Berechnung erfolgt tagesgenau (365 Tage) mit Excel.

## Information zu den Sheets

Die grün gefärbten Sheets sind selbst erstellte Dateien oder eigene Berechnungen. Sheets ohne Farbe sind Quelldateien.

„Übersicht“ bietet einen Überblick über die jeweilige Datei und deren Zweck.

Das Sheet mit den Hauptberechnungen ist das Kunde-SLP-Tagesmodell.

## Datenquellen

- **Lastprofil:** BDEW-Standardlastprofil H25 (Haushaltskunden), veröffentlicht 18.03.2025. Das BDEW H25-Profil wird gemäß den Anwendungshinweisen mit der offiziellen Dynamisierungsfunktion verrechnet (Koeffizienten identisch zur historischen VDEW H0-Formel), um die monatlichen Blockwerte in ein realistisches, tagesscharfes Profil zu überführen. Die Dynamisierungsfunktion sowie die zugehörigen Anwendungshinweise sind im Original-Blatt Quelle_BDEW_Dynamisierung dokumentiert.
- **Beschaffungspreise:** Reale Day-Ahead-Preise 2025 (SMARD, Bundesnetzagentur)
- **Feiertagskalender:** Gesetzliche Feiertage Hessen 2025

## Wichtige Daten/Ergebnisse

### 1. Annahmen

<img width="1368" height="357" alt="image" src="https://github.com/user-attachments/assets/100a4e43-97df-4043-b139-91cb684c95c9" />

Hier ist die Annahmen Liste für die gesamte Kalkulation.
Die reBAP-Stress-Annahme wird durch die empirische Analyse in https://github.com/siddhi-s-kulkarni/spot-und-ausgleichsenergieanalyse bestätigt.


### 2. KPIs

<img width="490" height="270" alt="image" src="https://github.com/user-attachments/assets/068f6a80-100b-417f-ab44-10a799261744" />

Hier sind die wichtigsten Ergebnisse zu sehen. Diese Ergebnisse orientieren sich an den Annahmen.


### 3. Sensitivität

<img width="921" height="409" alt="image" src="https://github.com/user-attachments/assets/56d2ed1a-6568-48b3-b309-e40aa6b190fd" />

Die Sensitivitätsanalyse zeigt, in welchem Umfang der Deckungsbeitrag bei Veränderungen der Profilabweichung und des Stressaufschlags für reBAP beeinflusst wird.




