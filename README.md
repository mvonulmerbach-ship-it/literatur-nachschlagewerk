# Weltliteratur – Nachschlagewerk

Nachschlagewerk zur Weltliteratur: Werke, Autoren und Einordnung in eigenen Worten.

**Live:** https://mvonulmerbach-ship-it.github.io/literatur-nachschlagewerk/

## Inhalt

97 Artikel in diesen Bereichen: 🗺️ Grundlagen · 📖 Werke (53) · 🧠 Autoren (42) · 📚 Service.

## Funktionen

- Menü ☰ mit allen Bereichen (am Desktop als Seitenleiste), Logo führt zur Startseite.
- Jeder Artikel hat eine eigene Adresse (z. B. `#ueberblick`), Querverweise im Text springen direkt zum Artikel.
- **Suche** über Titel und Text; Treffer im Titel stehen zuerst (exakt, dann Anfang, dann irgendwo im Titel, dann nur im Text).
- Hell/Dunkel oben rechts: ◐ System (Standard) · ☀️ Hell · 🌙 Dunkel. Die Wahl gilt für alle fünf Nachschlagewerke (`localStorage`, Schlüssel `nsw_theme`).
- Begleitet die Lernkarten-App [Weltliteratur – Lernkarten](https://mvonulmerbach-ship-it.github.io/literatur/) (sie bettet es bisher nicht ein). `?theme=dark|light` in der Adresse setzt Hell/Dunkel und hat Vorrang.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die ganze App (HTML, CSS, JavaScript und alle Artikel) |
| `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `icon-maskable.png` | Installation als App |
| `sw.js` | Service Worker für den Offline-Betrieb |

## Auf dem Handy installieren

Seite in Chrome öffnen → Menü ⋮ → „Zum Startbildschirm hinzufügen“ (Safari: Teilen → „Zum Home-Bildschirm“).

## Offline

Nach dem ersten Öffnen läuft das Nachschlagewerk ohne Netz (Service Worker, network first mit Cache als Rückfall).
