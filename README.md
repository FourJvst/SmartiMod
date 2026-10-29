# SmartiMod

Eine Fabric-Mod für Minecraft **26.3** mit anpassbarem HUD, Spotify-Anzeige, Itembrowser, Behältersuche und Wegpunkten.

## Download

Lade die neueste `smartimod-<version>.jar` im Bereich **Releases** dieses GitHub-Projekts herunter. Verwende **nicht** die Datei mit `-sources` im Namen – sie enthält nur den Quellcode.

## Voraussetzungen

- Minecraft **26.3**
- Java **25**
- Fabric Loader **0.20.1** oder neuer
- Fabric API für Minecraft 26.3

## Installation

1. Installiere Fabric für Minecraft 26.3.
2. Lade die passende Fabric API herunter.
3. Lege `smartimod-<version>.jar` und die Fabric-API-JAR in den `mods`-Ordner deiner Minecraft-Installation.
4. Starte Minecraft mit dem Fabric-Profil.

### Wegpunkte mit anderen teilen

Zum Teilen muss SmartiMod zusätzlich auf dem **Fabric-Server** installiert sein. Auch jeder ausgewählte Empfänger braucht die Mod auf seinem Client. Öffne im Spiel **Optionen → SmartiMod → Wegpunkte mit Spielern teilen**, wähle einen eigenen Wegpunkt und die gewünschten Spieler aus.

Der Server leitet den Wegpunkt nur an die ausgewählten, kompatiblen Spieler auf derselben Welt und Dimension weiter. Er speichert geteilte Wegpunkte nicht dauerhaft; sie sind beim Empfänger bis zur Trennung vom Server sichtbar.

## Funktionen

- Individuelle HUD-Widgets für Koordinaten, Rüstung, Tränke und Effekte, Spielzeit, FPS, Spotify und Discord-Call-Status.
- Widgets verschieben und skalieren; Position und Größe werden gespeichert.
- Optionale Minimap, standardmäßig deaktiviert.
- Item- und Rezeptbrowser über `/smartimod items` und `/smartimod search <suchtext>`.
- Behältersuche für Truhen, Shulkerboxen und Fässer.
- Wegpunkte mit lokalem Beacon-Strahl und Namensschild:
  - `/smartimod waypoint add <name>`
  - `/smartimod waypoint list`
  - `/smartimod waypoint remove <name>`
- Verschiedene Designs, unter anderem Pink, Neon, Rubinrot und Ozean.
- „Partner Server“-Button im Pausenmenü.

Die Mod speichert eigene Wegpunkte und Spielzeit lokal unter `config` im Minecraft-Spielverzeichnis.

## Spotify

Unter Windows liest SmartiMod Titel, Interpret, Wiedergabestatus und Cover aus der lokalen Mediensteuerung. Spotify muss geöffnet sein und Wiedergabeinformationen bereitstellen. SmartiMod benötigt dafür keine Spotify-Anmeldung, Client-ID oder Spotify-Web-API. Auf anderen Betriebssystemen steht diese Anzeige derzeit nicht zur Verfügung.
