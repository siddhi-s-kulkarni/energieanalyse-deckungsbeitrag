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

Das Sheet mit den Hauptberechnungen ist die Kunde_SLP-Tagesmodell.

### Datenquellen

- **Lastprofil:** BDEW-Standardlastprofil H25 (Haushaltskunden), veröffentlicht 18.03.2025. Das BDEW H25-Profil wird gemäß den Anwendungshinweisen mit der offiziellen Dynamisierungsfunktion verrechnet (Koeffizienten identisch zur historischen VDEW H0-Formel), um die monatlichen Blockwerte in ein realistisches, tagesscharfes Profil zu überführen. Die Dynamisierungsfunktion sowie die zugehörigen Anwendungshinweise sind im Original-Blatt Quelle_BDEW_Dynamisierung dokumentiert.
- **Beschaffungspreise:** Reale Day-Ahead-Preise 2025 (SMARD,Bundesnetzagentur)
- **Feiertagskalender:** Gesetzliche Feiertage Hessen 2025


