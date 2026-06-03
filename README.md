## 🚀 Minecraft Daylight Detector Elevator (Skript)

Ein leichtgewichtiges und extrem performantes Skript für Minecraft-Server (Spigot/Paper), das Tageslichtsensoren (Daylight Detectors) in voll funktionsfähige Aufzüge verwandelt. 

### Features
* **Nativ & Performant:** Nutzt ausschließlich die nativen Events `on jump` und `on sneak toggle`. Komplett ohne Server-belastende `on player move`-Schleifen.
* **Dynamische Etagensuche:** Der Aufzug sucht automatisch nach dem nächsten Sensor über oder unter dir (bis zu 60 Blöcke Reichweite). Es sind keine festen Offsets oder harten Distanz-Konfigurationen nötig.
* **Sicherer Teleport:** Spieler werden immer zentriert auf dem Zielblock abgesetzt. Wenn keine Etage gefunden wird oder die Weltgrenzen erreicht werden, bricht das Skript sicher ab, um Glitches zu verhindern.

### Bedienung
* **Nach oben:** Stelle dich auf einen Tageslichtsensor und drücke die **Leertaste (Springen)**.
* **Nach unten:** Stelle dich auf einen Tageslichtsensor und drücke **Shift (Sneaken)**.

### Voraussetzungen
* Minecraft Server (Paper, Purpur oder Spigot)
* Installiertes [Skript-Plugin](https://github.com/SkriptLang/Skript)

_____________________________________________________________________________________________________________________________________________________________
## 🚀 Minecraft Daylight Detector Elevator (Skript)

A lightweight and extremely performance-friendly script for Minecraft servers (Spigot/Paper) that turns daylight detectors into fully functional elevators.

### Features
* **Native & Lightweight:** Relies purely on the native `on jump` and `on sneak toggle` events. Completely avoids server-heavy `on player move` loops.
* **Dynamic Floor Search:** The elevator automatically scans for the next detector above or below you (up to 60 blocks range). No hardcoded offsets or fixed distances required.
* **Safe Teleportation:** Players are perfectly centered on the target block. If no matching floor is found or world bounds are reached, the process cancels safely to prevent glitches.

### How to use
* **Go Up:** Stand on a daylight detector and press **Space (Jump)**.
* **Go Down:** Stand on a daylight detector and press **Shift (Sneak)**.

### Requirements
* Minecraft Server (Paper, Purpur, or Spigot)
* Installed [Skript plugin](https://github.com/SkriptLang/Skript)
