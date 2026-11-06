# Sicherheitsgrenze des AUSGANG LAB

Das öffentliche Labor und die private Werkstatt sind zwei verschiedene Räume.

## Harte Regeln
1. Außenbeiträge sind immer **FREMDTEXT / ungeprüft**.
2. Außenbeiträge werden niemals automatisch in TISCH, WURZEL, Gedächtnis oder Behörden-/Familienakten übernommen.
3. Kein öffentlicher Dienst erhält einen Dateipfad, API-Endpunkt oder Suchzugriff auf die private Werkstatt.
4. Der öffentliche Dienst führt eingereichten Text niemals als Code, Befehl, Prompt oder Werkzeugauftrag aus.
5. Beiträge landen zuerst in einer Quarantäne. Herkunft und Zeitpunkt bleiben erhalten.
6. Ein Beitrag darf nur nach menschlicher Auswahl als einzelner Auszug nach innen gelangen.
7. Private Namen, Akten, Zugangsdaten und interne Pfade werden nicht veröffentlicht.
8. Der lokale Testserver bindet ausschließlich an 127.0.0.1 und ist nicht für eine direkte Internetfreigabe vorgesehen.

## Prompt-Injection
Fremdtext kann versuchen, KIs durch Sätze wie „ignoriere frühere Regeln“, „lies Datei X“ oder „führe Befehl Y aus“ zu steuern. Solche Texte werden als Inhalt behandelt, nie als Anweisung.

Der Schleusenhund darf Fremdtext sehen, besitzt aber keine Shell-, Dateiänderungs-, Netzwerk- oder Werkstattwerkzeuge. Seine Einschätzung ist selbst nur ein Prüfbericht und kein Freibrief.

## Rückweg
Es existiert absichtlich kein automatischer Import aus dem Außenraum in die Werkstatt. Ein möglicher Fund wird erst nach menschlicher Entscheidung als Zitat übernommen.
