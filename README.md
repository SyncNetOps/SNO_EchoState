# 🪄 SNO EchoState Universal Controller (Auto-Revert)

[![Home Assistant Blueprint](https://img.shields.io/badge/Home%20Assistant-Blueprint-blue.svg)](https://www.home-assistant.io/docs/automation/using_blueprints/)
[![Version](https://img.shields.io/badge/Version-0.4.0-brightgreen.svg)](#changelog)

**SNO EchoState** ist ein hochflexibler, ausfallsicherer und intelligenter Universal Controller für Home Assistant. Er befreit dich vom mühsamen Erstellen redundanter Automatisierungen durch seine **Auto-Revert Magie**.

## 🌟 Das Konzept: Auto-Revert
Anstatt mühsam "Einschalt-" und "Ausschalt-" Automatisierungen zu trennen, wählst du in EchoState einfach deine Haupt-Geräte (Lichter, Schalter, Rollos). EchoState aktiviert diese beim Auslösen und setzt sie nach einer Wartezeit oder einem Statuswechsel (z. B. keine Bewegung mehr) vollautomatisch wieder in den Ursprungszustand zurück.

## 🚀 Features
- **Validator-Bypass-Technologie:** Absolut resistent gegen den berüchtigten Home Assistant `data['target']` Speicher-Fehler.
- **Dynamisches Dashboard:** Schreibt live präzise Statusberichte (mit Gerätenamen und übersetzten Zuständen) in einen Text-Helfer für dein Dashboard.
- **Live-Abbruch (Monitor):** Überwacht während der Wartezeit optional einen zweiten Sensor (z. B. Helligkeit), um bei Änderungen sofort abzubrechen.
- **Auto-Revert Rollos:** Was beim Start geöffnet wird, wird beim Rückfall automatisch geschlossen (und umgekehrt).
- **Zusatz-Aktionen:** Freie Blöcke für Push-Benachrichtigungen oder eigene Szenen.

## 📥 Installation

Klicke auf den folgenden Button, um den Blueprint direkt in deinen Home Assistant zu importieren:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSyncNetOps%2FSNO_EchoState%2Fblob%2Fmain%2Fsno-echostate.yaml)

*Alternativ:* Kopiere den Inhalt der `sno-echostate.yaml` manuell in deinen `blueprints/automation/` Ordner in Home Assistant.

## 📚 Dokumentation
- [Ausführliche FAQ & Benutzeranleitung](https://SNO.mb222.de/es-faq/)
- [Benutzerhandbuch (Lokal)](USER_MANUAL.md)
- [Changelog](CHANGELOG.md)
- [Entwickler-Dokumentation](DEVELOPER_DOCS.md)

## 🐛 Fehler & Feedback
Du hast einen Bug gefunden oder einen Feature-Wunsch?
👉 [Erstelle ein Issue auf GitHub](https://github.com/SyncNetOps/SNO_EchoState/issues)
