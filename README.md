## FOREST BY XYZIN

Forest Workshop ist ein BepInEx-5-Mod für die originale PC-Version von
**The Forest**. Das Menü bündelt Zielhilfe, Waffenoptionen, Spielerfunktionen,
ESP, Bewegung, Weltkontrolle und Item-Verwaltung in einer übersichtlichen
Oberfläche.

## Menü öffnen und bedienen

- `F7` öffnet oder schließt das Menü.
- `F8` schaltet den Aimbot direkt ein oder aus.
- Mit der linken Maustaste werden Schalter, Regler und Auswahlelemente bedient.
- Das Menü kann an der oberen Leiste verschoben werden.
- Lange Seiten besitzen eine Scrollleiste.
- Alle Gameplay-Schalter sind beim ersten Start deaktiviert.
- Einstellungen werden in `BepInEx/config/com.theforest.workshop.cfg`
  gespeichert.

## AIM

Der AIM-Tab enthält die Zielhilfe für Projektile und den optionalen Kamera-Lock.

- **Aimbot:** Aktiviert die Zielhilfe.
- **Camera lock on LMB:** Bewegt beim Halten der linken Maustaste die Kamera
  weich zum gewählten Ziel.
- **Aim speed:** Bestimmt die Geschwindigkeit des Kamera-Locks.
- **Supported weapons:** Separate Unterstützung für Bogen, Armbrust und Speere.
- **Weapon mode:** Automatische oder waffenspezifische Einstellungen.
- **Target mode:** Kann Kannibalen, Tiere, andere Koop-Spieler oder automatisch
  alle freigegebenen Gruppen wählen. Der eigene Spieler wird ausgeschlossen.
- **Visible check:** Ignoriert Ziele hinter Gelände und Gebäuden.
- **Movement prediction:** Berechnet die Bewegung des Ziels voraus.
- **Gravity compensation:** Berücksichtigt den Geschossabfall.
- **FOV circle:** Zeigt den Zielbereich mit frei wählbarer Farbe und Größe.
- **Target-lock marker:** Markiert das aktuell gewählte Ziel.
- **Projectile target line:** Zeichnet eine Linie vom eigenen Projektil zum Ziel.

Der Aimbot bevorzugt den Kopf, sofern am Ziel ein gültiger Kopf-Transform
gefunden wird.

## WEAPONS

Dieser Tab verändert lokale Waffen und Projektile.

- Unbegrenzte Pfeile und Bolzen
- Pfeilarten: Automatic, Normal, Bone, Modern, Burning und Poisoned
- Sofortiges Nachladen von Bogen und Armbrust
- Schnellfeuer für die Armbrust mit einstellbarer Feuerrate
- Separate Projektilgeschwindigkeit für Bogen und Armbrust
- Deaktivierbare Projektil-Schwerkraft
- Einstellbare Verzögerung, bis Pfeile und Bolzen aufgehoben werden können
- Dauerhaft sichtbares Fadenkreuz
- Vorausberechnete Flugbahn
- Nahkampfschaden, Angriffsgeschwindigkeit und Reichweite
- One-Hit für Bäume, Kannibalen und Tiere
- Explosionsradius und Explosionsschaden

Explosionsmodifikatoren werden nur auf lokal erzeugte beziehungsweise lokal
besessene Explosionen angewendet.

## SURVIVAL

Der Survival-Tab enthält Funktionen für den lokalen Spieler.

- God Mode
- Kein Hunger oder Durst
- Unbegrenzte Energie und Ausdauer
- Unbegrenzter Sauerstoff
- Kein Erfrieren
- Keine Infektionen oder Lebensmittelvergiftung
- Maximale geistige Gesundheit
- Unbegrenzte Taschenlampenbatterie
- Unbegrenzter Feuerzeugtreibstoff
- Unbegrenztes Haarspray
- Kostenloses Bauen

## MOVEMENT & TELEPORT

- **Fly mode:** Freie Bewegung in Blickrichtung der Kamera.
- **Noclip:** Deaktiviert die Kollision des lokalen Spielers.
- **No fall damage:** Verhindert Fallschaden.
- **Movement speed:** Multipliziert Lauf-, Sprint-, Seitwärts- und
  Schwimmgeschwindigkeit.
- **Jump height:** Verändert die Sprunghöhe.
- **Fly speed:** Bestimmt die Fluggeschwindigkeit.

Flugsteuerung:

- `W`, `A`, `S`, `D` – bewegen
- `Leertaste` – nach oben
- `Linke Strg-Taste` – nach unten
- `Linke Umschalttaste` – schneller fliegen

Teleport-Funktionen:

- **To Cursor:** Teleportiert auf die Oberfläche unter dem Fadenkreuz.
- **Back:** Kehrt zur Position vor dem letzten Teleport zurück.
- **Slots 1–3:** Speichern und laden drei dauerhafte Positionen.

## ESP

ESP wird über den Hauptschalter **Cannibal ESP** aktiviert. Danach lassen sich
die gewünschten Zielgruppen getrennt einschalten.

- Kannibalen und Mutanten
- Tiere
- Andere Koop-Spieler
- Aufhebbare Weltgegenstände
- Höhleneingänge

Darstellungsoptionen:

- Boxen
- Snaplines
- Namen beziehungsweise Typen
- Entfernung
- Lebensbalken für unterstützte Kannibalen
- Maximale Reichweite
- Sichtbar-/Verdeckt-Farben
- Eigene Farben für Tiere, Spieler, Items und Höhlen
- Performance-, Balanced- und Quality-Modus

Das optionale Radar zeigt Gegner und die zusätzlich aktivierten Tier- und
Spielergruppen. Reichweite und Größe sind einstellbar. Item-Suchen werden zur
Schonung der Bildrate nur einmal pro Sekunde aktualisiert.

## WORLD & BUILDING

### Zeit und Wetter

- Lokale Tageszeit festlegen
- Spielgeschwindigkeit von Pause (`0.00x`) bis `5.00x`
- Clear, Light Rain, Medium Rain und Heavy Rain
- Lokales Höhlenlicht

### Bauen

- Kostenloses Bauen
- Platzieren unabhängig von normalen Blockierungen
- Unzerstörbare Gebäude
- Schutz für Baumhäuser, wenn der tragende Baum gefällt wird
- Reichweite für Weltaktionen
- Nahe Baupläne sofort fertigstellen
- Nahe Gebäude vollständig reparieren

### Welt und Farming

- Nachwachsende Bäume
- Sofortiges Pflanzenwachstum
- Automatisches Einsammeln naher Gegenstände
- Reichweite des Pickup-Magneten
- Multiplikator für eingesammelte Mengen

### KI und Spawner

- Kannibalen passiv stellen
- Kannibalen einfrieren
- Tiere einfrieren
- Nahe Gegner oder Tiere entfernen
- Ausgewählte Mutanten und Tiere erzeugen

## ITEMS & SPAWNER

### Inventar

- Unbegrenzte normale Stapelkapazität
- Unbegrenzte Baumaterialien
- Unbegrenzte Medizin und Nahrung
- Unbegrenzte Wurfwaffen und Sprengstoffe
- Unbegrenzte Pfeile, Bolzen und Speere
- Alle sicheren normalen Items geben
- Ausgewähltes Item duplizieren oder ablegen

Pfeile bleiben absichtlich auf maximal **25**, weil größere Pfeilstapel den
Bogen des Spiels instabil machen können. Story-, Quest-, Spezial- und ungültige
Debug-Items werden bei Sammelaktionen und im Spawner übersprungen.

### Item-Spawner

- Suche nach Anzeigename oder Item-ID
- Kategorien für Waffen, Munition, Materialien, Nahrung und Rüstung
- Einstellbare Menge
- Favoritenliste
- Item direkt ins Inventar geben
- Item als Weltgegenstand erzeugen

## SETTINGS

- Profile: Custom, Legit, Combat und Building
- Frei belegbare Menü- und Aimbot-Hotkeys
- UI-Skalierung
- Auflösungsvorgaben für 1080p, 2K, 4K und 8K
- Anzeige des aktuellen Sitzungsmodus
- Einzelne Tabs oder alle Einstellungen zurücksetzen

Die zuletzt geöffnete Seite und die Scrollpositionen werden gespeichert.

## Koop und Host-Funktionen

Lokale Funktionen wie Bewegung, Spielerwerte, Inventar, Zielhilfe und ESP
funktionieren grundsätzlich als Host und als normaler Client.

Folgende Aktionen benötigen in einer Koop-Sitzung den Host:

- Wetter ändern
- Gebäude reparieren
- Baupläne sofort fertigstellen
- Gegner oder Tiere entfernen
- Mutanten und Tiere erzeugen
- Items als Weltobjekte erzeugen

Das Menü blockiert diese Aktionen bei normalen Clients, um unnötige
Synchronisationsfehler zu verhindern.

## Installation

Die Datei `ForestWorkshop.dll` gehört nach:

```text
The Forest/BepInEx/plugins/ForestWorkshop.dll
```

Danach die 64-Bit-Version von The Forest starten, einen Spielstand laden und
`F7` drücken.
