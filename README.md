# 🛡️ Purple RP Management Bot
### *Professionelle Discord Roleplay Verwaltung*

![Python](https://img.shields.io/badge/Sprache-Python%203.10+-blue)
![Library](https://img.shields.io/badge/Library-discord.py%202.0+-green)
![License](https://img.shields.io/badge/Lizenz-Single--Server-red)
![Entwickler](https://img.shields.io/badge/Entwickler-PurplxWasTaken-yellow)

---

## ✨ Hauptfunktionen

* **🛂 Automatisiertes Einreise-System**: Nahtlose Verwaltung vom "Ankömmling" zum "Bürger" mit dem `/einreise` Befehl.
* **🏢 Fraktions-Datenbank**: Erstelle und verwalte Fraktionen mit einem integrierten Warn-System für Fraktionsleiter.
* **🚫 Intelligente Sicherheit**: Erkennt automatisch Nutzer mit 3+ Verwarnungen beim Beitritt und setzt eine automatische Sperre.
* **🛠️ Wartungsmodus**: Sperre den Server für Updates mit einem Befehl, inklusive Countdown und benutzerdefiniertem Grund.
* **📋 Logging-System**: Jede Team-Aktion wird in einem Log-Channel protokolliert, um volle Transparenz zu gewährleisten.

---

## 🚀 Befehlsübersicht

### **Team & Moderation**
| Befehl | Beschreibung | Berechtigung |
| :--- | :--- | :--- |
| `/einreise` | Schließt die Einreise für einen User offiziell ab. | Team+ |
| `/warn` | Erteilt eine permanente Verwarnung (3 = Auto-Sperre). | Team+ |
| `/sperre` | Sperrt einen User manuell von den Server-Rollen aus. | Team+ |
| `/staffstatus` | Überprüft dein aktuelles Berechtigungslevel. | Jeder |

### **Fraktions-Verwaltung**
| Befehl | Beschreibung | Berechtigung |
| :--- | :--- | :--- |
| `/frakadd` | Registriert eine neue Fraktion und einen Leiter. | HighTeam |
| `/frakwarn` | Erteilt einer Fraktion eine offizielle Verwarnung. | HighTeam |
| `/frakliste` | Zeigt alle Fraktionen und deren Warn-Status an. | Jeder |

---

### **Erwerben**

Interresse geweckt? kontaktiere **@purplxwastaken** auf **discord** um eine lizenz für eine eigene version des bots zu erhalten.

---

## ⚙️ Einrichtung & Installation

> **Hinweis:** Dieser Bot ist ein Premium-Produkt mit Einzelserver-Lizenz. Die Ersteinrichtung erfordert eine manuelle Konfiguration der IDs für maximale Sicherheit.

1. **Dateien vorbereiten**: Stelle sicher, dass `UserData.JSON`, `Fraktionen.json` und `maintenance.json` im selben Ordner wie der Bot liegen.
2. **IDs konfigurieren**: Öffne `RP Bot.py` und gehe zu **Sektion 1 (EINRICHTUNG)**.
3. **Werte einsetzen**: Ersetze die Platzhalter (z.B. `000000000...`) mit deinen spezifischen Channel-, Rollen- und Guild-IDs.
4. **Intents**: Aktiviere den **Server Members Intent** im Discord Developer Portal.
5. **Starten**: Starte das Skript über die Konsole mit `python "RP Bot.py"`.

---

## 🔒 Sicherheit & Lizenzierung
Diese Software ist geschützt und auf die während des Setups autorisierte Guild-ID beschränkt. Dieser "Guild-Lock" stellt sicher, dass der Bot exklusiv für deine Community bleibt. Eine unbefugte Weitergabe oder Änderung der Kern-Logik ist streng untersagt.

---
*Entwickelt von **@purplxwastaken***.  
*Für Support oder Lizenzfragen kontaktiere den Entwickler direkt per DM.*
