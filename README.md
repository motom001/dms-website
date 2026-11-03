# Ablago – Startseite

*[English](README.en.md)*

Quellcode der Startseite von **Ablago**, der Dokumentenablage für zu Hause und kleine Betriebe. Die Seite wird über GitHub Pages veröffentlicht.

- Ablago selbst: [motom001/dms](https://github.com/motom001/dms)
- Paketkatalog: [motom001/dms-registry](https://github.com/motom001/dms-registry)

## Grundsätze

- **Statisches HTML**, ohne Baustufe und ohne Abhängigkeiten. `index.html` lässt sich direkt im Browser öffnen.
- **Keine Cookies, kein Tracking, keine Statistik.** Die Seite lädt nichts von anderen Anbietern: Bilder liegen hier im Repository, Schriften kommen vom Gerät der Besucher.
- **GitHub Pages** verarbeitet als Betreiber beim Aufruf technisch notwendige Daten wie die IP-Adresse. Darauf weist die Seite offen hin.
- **Barrierefrei:** guter Kontrast, Bedienung per Tastatur, „Bewegung reduzieren“ wird beachtet.
- **Hell und dunkel** nach der Einstellung des Geräts.

## Aufbau

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (Deutsch) |
| `en/index.html` | Startseite (Englisch) |
| `impressum.html`, `datenschutz.html` | Impressum und Datenschutz (mit kurzer englischer Fassung) |
| `.well-known/security.txt` | Kontakt für Sicherheitsmeldungen (RFC 9116) |
| `favicon.svg`, `favicon.ico`, `apple-touch-icon.png` | Symbole für Browser und Handy |
| `bilder/` | Bilder der Startseite |
| `marke/` | **Logo und Farben für alle Repositories** – Dateien, Regeln und Rechte, siehe [marke/README.md](marke/README.md) |

## Stand

Online unter **https://ablago.app** (Deutsch) und **https://ablago.app/en/** (Englisch), mit Impressum, Datenschutz und `/.well-known/security.txt`. Geplant: Unterseiten je Zielgruppe und die Pakete live aus dem Katalog.

## Lizenz

Der Code steht unter der [Apache License 2.0](LICENSE). Name und Logo von Ablago sind davon nicht erfasst, siehe [NOTICE](NOTICE).
