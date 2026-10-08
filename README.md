# Deutsch üben

Interaktive Deutsch-Übungstests nach GER-Niveau, gehostet mit GitHub Pages.

## Aufbau

- `index.html` – Startseite mit allen Tests
- `tests.js` – Liste der Tests (Titel, Niveau, Link …)
- `tests/` – ein HTML-Datei pro Test

## Neuen Test hinzufügen

1. Die HTML-Datei des Tests in den Ordner `tests/` legen.
2. In `tests.js` einen neuen Eintrag ergänzen, z. B.:

```js
{
  id: "a2-2-lesen",
  level: "A2.2",
  title: "Lesetest A2.2",
  description: "Kurze Texte und Anzeigen verstehen.",
  href: "tests/a2-2-lesen.html",
  skills: ["Lesen"],
  minutes: 30,
  points: 20,
  storageKey: "deutsch-a22-lesen-v1",
  added: "2026-10-15"
}
```

`storageKey` muss für jeden Test eindeutig sein, damit die Startseite den Fortschritt richtig anzeigt.

## Hinweis

Die Lösungen stehen im Quelltext der Testseiten. Die Tests sind für Übung und Selbstkontrolle gedacht, nicht für Prüfungen mit Bewertung unter Aufsicht.
