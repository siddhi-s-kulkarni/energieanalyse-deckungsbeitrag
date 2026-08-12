# Energieanalyse Deckungsbeitrag

Portfolio-Projekt zur Demonstration praxisnaher Analysekompetenzen im Bereich Energiewirtschaft mit Fokus auf Bilanzierung, Beschaffung und Deckungsbeitragskalkulation für SLP-Kunden.

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

<img width="1508" height="386" alt="image" src="https://github.com/user-attachments/assets/8621cf7c-69d1-4c3a-b134-582e85433bd2" />



Hier ist die Annahmen Liste für die gesamte Kalkulation.
Die reBAP-Stress-Annahme wird durch die empirische Analyse in https://github.com/siddhi-s-kulkarni/spot-und-ausgleichsenergieanalyse bestätigt.


### 2. KPIs
<img width="610" height="299" alt="image" src="https://github.com/user-attachments/assets/ae657edf-9aec-4be1-a820-1bda15a341ef" />


Hier sind die wichtigsten Ergebnisse zu sehen. Diese Ergebnisse orientieren sich an den Annahmen.


### 3. Sensitivität

<img width="1049" height="438" alt="image" src="https://github.com/user-attachments/assets/1b151095-9b61-483e-bd9d-77813870a122" />





Die Sensitivitätsanalyse zeigt, in welchem Umfang der Deckungsbeitrag bei Veränderungen der Profilabweichung und des Stressaufschlags für reBAP beeinflusst wird.




