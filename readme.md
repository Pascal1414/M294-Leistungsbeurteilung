# Leistungsbeurteilung

## Visual Sutdio Code

Als Entwicklungsumgebung wurde Visual Studio Code verwendet.

### Extensions

#### Live Server 
Mit der Live Server Extension kann die webseite angeschaut werden. Im Hintergrund wird ein Server gestartet, der dem Browser die Website liefert.
<br>
<br>

#### Formatter 
Er Formatiert den HTML, CSS oder Javasctipt Code, um schneller und besser arbeiten zu können.

## API
Die API wurde für das Projekt zur Verfügung gestellt. Sie läuft lokal im Hintergrund und stellt die Endpoints zur Verfügung.

## Bedienen
Nach dem anmelden kann man sich eine übersich über alle Aufgaben anzeigen lassen. Diese können als erledigt markiert, gelöscht oder angeklickt werden. Beim anklicken wird man auf eine Seite weitergeleitet in der man die Aufgabe bearbeiten kann.
## Testprotokoll

 | Datum      | Autor         | Title        | Testfall                                                                      | Reproduzieren                                                |
|------------|---------------|--------------|-------------------------------------------------------------------------------|--------------------------------------------------------------|
| 04.10.2022 | Pascal Rieder | Forms        | Forms können nur abgeschickt werden, wenn alle Pflichtfelder ausgefüllt sind. | Ein Form abschicken                                          |
| 04.10.2022 | Pascal Rieder | Login        | Nach erfolgreichem Login wird man auf die Home-Seite weitergeleitet.          | 1. Email und Password eingeben 2. Form absenden              |
| 04.10.2022 | Pascal Rieder | Show Tasks   | Auf der Home-Seite werden alle Tasks formatiert angezeigt.                    | Auf die Home-Seite navigieren                                |
| 04.10.2022 | Pascal Rieder | Navigate     | Beim Anklicken einer Task wird man auf die Vorschauseite geleitet.            | Eine Task auf der Home-Seite anklicken.                      |
| 04.10.2022 | Pascal Rieder | Correct Data | Auf einer Vorschauseite wird die richtige Task angezeigt.                     | Die Vorschauseite ist geöffnet und der Anker ist korrekt.    |
| 04.10.2022 | Pascal Rieder | Correct URL  | Die Vorschauseite wird abhängig von dem Anchor mit dem Inhalt gefüllt.        | Die Vorschauseite ist geöffnet und ein Anchor ist vorhanden. |
| 04.10.2022 | Pascal Rieder | Correct Data | Die bearbeitete Task wird richtig aktualisiert.                               | 1. Task bearbeiten 2. Task speichert 3. Überprüfen           |