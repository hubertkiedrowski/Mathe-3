# Mathe-Klausurvorbereitung

Dieses Repo dient als **persistenter Speicher** für meine Mathe-Übungen und mein Fehler-Log. Bedient wird es über **Claude Code im Desktop-Tab**, das hier dauerhaft als mein Mathe-Tutor agiert (Regeln siehe [`CLAUDE.md`](./CLAUDE.md)).

## Bedienung

- **Üben:** `Stell mir eine Aufgabe zu ...` (z.B. Stetigkeit, Ableitungen, Reihen). Erst kommt nur die Aufgabe — ich rechne selbst, danach gibt es Tipp, vollständigen Lösungsweg und Skript-Verweis.
- **Wiederholen:** `Fehlerliste` (oder `Wiederholung`) — der Tutor stellt mir die noch offenen Aufgaben aus [`fehler-log.md`](./fehler-log.md) erneut.
- **Mehr Übung:** `mehr davon` für ähnliche Aufgaben.

## Dateien

- `CLAUDE.md` — Rolle und Regeln des Mathe-Tutors.
- `fehler-log.md` — automatisch gepflegte Wiederholungsliste meiner falsch beantworteten Aufgaben (Status: offen / wiederholt / gemeistert).

## Hinweis zu Formeln

Formeln werden **immer als abgesetzte Mathe** mit `$$ ... $$` geschrieben — niemals als Inline-`$...$`, da das im Claude-Code-Tab aktuell nicht rendert.
