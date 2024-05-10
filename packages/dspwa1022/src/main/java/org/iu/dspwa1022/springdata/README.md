# Spring Data

> Diese Anleitung basiert auf der Nutzung von VS Code wie in der Vorlesung vorgeschlagen. Wenn du eine andere IDE verwendest, funktionieren gewisse Kommandos unter Umständen anders.

## Starten & Stoppen der Anwendung

- Öffne die Klasse [`SpringDataApp.java`](./SpringDataApp.java) und starte die `main()`-Meth

> Immer, wenn du Änderungen an der Anwendung vornimmst, musst du die Anwendung stopppen und neu starten

![Beenden der Spring App im Terminal](../../../../../../docs/images/spring-console-stop-app.png)

## Aufgaben

- Nutze den `GET /persons`-Endpunkt, um die vorhandenen Personen abzurufen. Was ist das Ergebnis?
- Leg einige Personen mittels `POST /persons` an
- Schau in die Konsole/die Logs der Anwendung. Was wird dort hinter `Hibernate:` ausgegeben?
- Was passiert, wenn du keinen `name` beim Anlegen mitgibst? Welche Informationen können wir aus den HTTP-Status-Codes ziehen?
- Erweitere die Person-Klasse um eine beliebige neue Eigenschaft und lies/schreib diese über die API