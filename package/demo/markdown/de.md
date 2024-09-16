---
title: stringyfy
description: Eine einfache npm-Bibliothek, die eine Reihe von Hilfsfunktionen zur Manipulation und Transformation von Zeichenketten in JavaScript bereitstellt.
meta:
  - name: Schlüsselwörter
    content: stringyfy, npm, Bibliothek, Dienstprogramm, Funktionen, manipulieren, transformieren, Zeichenketten, JavaScript
  - name: author
    content: stringyfy
  - name: date
    content: 2021-10-01
  - property: og:image
    content: https://cdn.jsdelivr.net/gh/stringyfy/assets/images/logo.png
sidebar: auto
category: Bibliotheken
---

# stringyfy

## Beschreibung

`stringyfy` ist eine einfache npm-Bibliothek, die eine Reihe von Hilfsfunktionen zur Manipulation und Transformation von Zeichenketten in JavaScript bereitstellt. Sie ist leichtgewichtig, einfach zu verwenden und hat keine Abhängigkeiten.

## Installation

Um `stringyfy` zu installieren, verwenden Sie den folgenden Befehl:

```bash
npm install stringyfy
```

## Verwendung

Hier ist ein einfaches Beispiel für die Verwendung von `stringyfy`:

```javascript
const stringyfy = require('stringyfy');

let str = "Hallo, Welt!";

let result = stringyfy.reverse(str);

console.log(result); // Ausgabe: "!tleW ,ollaH"
```

## API

### `reverse(str)`

Kehrt die gegebene Zeichenkette um.

### `capitalize(str)`

Schreibt den ersten Buchstaben der gegebenen Zeichenkette groß.

### `lowercase(str)`

Konvertiert alle Zeichen in der gegebenen Zeichenkette in Kleinbuchstaben.

### `uppercase(str)`

Konvertiert alle Zeichen in der gegebenen Zeichenkette in Großbuchstaben.

## Mitwirken

Pull-Requests sind willkommen. Für größere Änderungen öffnen Sie bitte zuerst ein Issue, um zu besprechen, was Sie ändern möchten.

## Lizenz

MIT