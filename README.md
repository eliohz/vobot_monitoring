# Vobot Ticket Counter

**Vobot Ticket Counter** ist ein Ferienprojekt, das die Vobot-Plattform nutzt, um eine einfache Ticketzähler-Anwendung zu erstellen. Diese Anwendung zeigt fortlaufend die Ticketnummer auf dem Display und steuert die Farbänderung des Umgebungslichts je nach Ticketzahl.

## Funktionen
- **Ticketanzeige**: Zeigt die aktuelle Ticketnummer.
- **Umgebungslichtsteuerung**: Farbänderung basierend auf der Ticketnummer (grün, gelb, rot).
- **Einfache Nutzung**: Anpassbare Schriftgröße und einfache Steuerung der Vobot-Peripheriegeräte.

## Installation und Konfiguration
Für die Installation und Konfiguration des Vobot-Systems folgen Sie bitte der offiziellen Anleitung auf [dock.myvobot.com](https://dock.myvobot.com/developer/getting_started/).

## Load code to Device with Thonny
Download [Thonny](https://thonny.org/)

app -> MicroPython device /apps -> run manifest.yml

## Edit Bool (API)
curl -X POST https://eliohz.com/api/ticket-status   -H "Content-Type: application/json"   -d '{"status": false}'

curl -X POST https://eliohz.com/api/ticket-status   -H "Content-Type: application/json"   -d '{"status": true}'
