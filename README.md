# 🪄 SNO EchoState Universal Controller (Auto-Revert)
Home Assistant Blueprint

Version
**EchoState** ist ein hochflexibler, ausfallsicherer und intelligenter Universal Controller für Home Assistant. Er befreit dich vom mühsamen Erstellen redundanter Automatisierungen durch seine **Auto-Revert Magie**.
## 🌟 Das Konzept: Auto-Revert
Anstatt mühsam "Einschalt-" und "Ausschalt-" Automatisierungen zu trennen, wählst du in EchoState einfach deine Haupt-Geräte (Lichter, Schalter, Rollos). EchoState aktiviert diese beim Auslösen und setzt sie nach einer Wartezeit oder einem Statuswechsel (z.B. keine Bewegung mehr) vollautomatisch wieder in den Ursprungszustand zurück.
## 🚀 Features
 * **Validator-Bypass-Technologie:** Absolut resistent gegen den berüchtigten Home Assistant data['target'] Speicher-Fehler.
 * **Dynamisches Dashboard:** Schreibt live präzise Statusberichte (mit Gerätenamen und übersetzten Zuständen) in einen Text-Helfer für dein Dashboard.
 * **Live-Abbruch (Monitor):** Überwacht während der Wartezeit optional einen zweiten Sensor (z.B. Helligkeit), um bei Änderungen sofort abzubrechen.
 * **Auto-Revert Rollos:** Was beim Start geöffnet wird, wird beim Rückfall automatisch geschlossen (und umgekehrt).
 * **Zusatz-Aktionen:** Freie Blöcke für Push-Benachrichtigungen oder Szenen.
## 📥 Installation
Klicke auf den folgenden Button, um den Blueprint direkt in deinen Home Assistant zu importieren:
Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.
*Alternativ:* Kopiere den Inhalt der sno-echostate.yaml manuell in deinen blueprints/automation/ Ordner.
## 📚 Dokumentation
 * Ausführliche FAQ & Benutzeranleitung
 * Changelog
 * Entwickler-Dokumentation
## 🐛 Fehler & Feedback
Du hast einen Bug gefunden oder einen Feature-Wunsch?
👉 Erstelle ein Issue auf GitHub
