# Pomodoro Timer Plus

A lightweight work-organization app that runs locally in your browser. It consists of `index.html` and `style.css` and needs no build step or server.

## English

### Requirements

- A modern browser such as Chromium, Firefox, Safari, or Edge.
- No installation, account, or internet connection is required for the app itself.

### Installation and launch

1. Download or copy `index.html` and `style.css` into the same folder.
2. Open `index.html` in your browser (double-click it, or use the browser's **Open File** command).
3. For a portable backup, keep both files together. The app stores tasks and settings in that browser's local storage.

### Using the app

- Select **DE**, **EN**, or **FR** in the upper-right corner to change the interface language. The choice is saved in the browser.
- Use **Add task** to create a card and choose its priority: Important, Normal, or Break.
- Each card receives a random color that stays the same. Cards in the same stack share one color.
- Click a card title to edit it. Use **Split** to turn a task into two consecutive cards; enter each title and press Enter to confirm.
- Click a card to open or close its stack. Use the arrow buttons to reorder steps. **Done** removes the top card. Clicking the empty pinboard closes open stacks.
- Set the timer duration and the Important-task frequency (0–75%). The remaining non-important tasks are selected evenly. Start the timer to select a task and begin a work session.
- While the timer is running, **Start over** restarts the current session without changing its task. Marking the active task as done ends the work session immediately.
- Use **Save session** to export tasks and settings as a timestamped JSON file. **Load session** imports a JSON session file.

### Data and backups

Tasks and settings are stored in the browser's local storage. They are separate for each browser and browser profile. Use **Save session** to create a portable JSON backup. Keep the HTML and CSS files together; a copy of `index.html` alone will not include the app's styling.

---

## Deutsch

### Voraussetzungen

- Ein aktueller Browser wie Chromium, Firefox, Safari oder Edge.
- Für die Anwendung sind weder Installation noch Konto oder Internetverbindung erforderlich.

### Installation und Start

1. Lade `index.html` und `style.css` herunter oder kopiere beide Dateien in denselben Ordner.
2. Öffne `index.html` im Browser, zum Beispiel per Doppelklick oder über **Datei öffnen**.
3. Bewahre für eine portable Sicherung beide Dateien zusammen auf. Aufgaben und Einstellungen speichert die Anwendung im lokalen Speicher dieses Browsers.

### Verwendung

- Wähle oben rechts **DE**, **EN** oder **FR**, um die Sprache der Oberfläche zu ändern. Die Auswahl wird im Browser gespeichert.
- Über **Aufgabe hinzufügen** erstellst du eine Karte und wählst ihre Priorität: Wichtig, Normal oder Pause.
- Jede Karte erhält eine zufällige Farbe, die gleich bleibt. Karten im selben Stapel haben dieselbe Farbe.
- Klicke auf einen Kartentitel, um ihn zu bearbeiten. Mit **Split** wird eine Aufgabe in zwei aufeinanderfolgende Karten geteilt. Gib beide Titel nacheinander ein und bestätige jeweils mit Enter.
- Ein Klick auf eine Karte öffnet oder schließt ihren Stapel. Mit den Pfeilen sortierst du die Schritte. **Erledigt** entfernt die oberste Karte. Ein Klick auf die freie Pinnwandfläche schließt offene Stapel.
- Stelle die Timerdauer und die Häufigkeit wichtiger Aufgaben (0–75 %) ein. Die übrigen Aufgaben werden gleichmäßig ausgewählt. Starte den Timer, um eine Aufgabe auszuwählen und die Arbeitsphase zu beginnen.
- Während der Timer läuft, startet **Nochmal von vorne** die aktuelle Arbeitsphase neu, ohne die Aufgabe zu wechseln. Wird die aktive Aufgabe als erledigt markiert, endet die Arbeitsphase sofort.
- Mit **Sitzung speichern** exportierst du Aufgaben und Einstellungen in eine JSON-Datei mit Zeitstempel. Über **Sitzung laden** importierst du eine gespeicherte JSON-Sitzung.

### Daten und Sicherungen

Aufgaben und Einstellungen liegen im lokalen Speicher des jeweiligen Browsers und Browserprofils. Mit **Sitzung speichern** kannst du eine übertragbare JSON-Sicherung erstellen. Bewahre `index.html` und `style.css` zusammen auf; ohne die CSS-Datei wird die Gestaltung nicht geladen.
