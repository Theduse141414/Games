# Games

## Pong

Ein klassisches Pong-Spiel im Browser – eine einzelne HTML-Datei, keine Abhängigkeiten.
Läuft am Computer und auf dem Handy.

**Starten:** `pong/index.html` im Browser öffnen.

### Am Computer
- **1 Spieler** gegen den Computer (Schwierigkeit: leicht / mittel / schwer)
  – Steuerung: `W`/`A`/`S`/`D`, Pfeiltasten oder Maus
- **2 Spieler** an einer Tastatur – Spieler 1: `W`/`A`/`S`/`D`, Spieler 2: Pfeiltasten
  (hoch/runter bewegt den Schläger, links/rechts vor und zurück)
- `P` / `Esc` = Pause, `M` = Menü, `F` = Vollbild (auch als Buttons oben rechts)

### Auf dem Handy (Touch)
- **2 Spieler an einem Bildschirm:** Jeder Spieler steuert mit dem Finger auf seiner
  Bildschirmhälfte – beide gleichzeitig (Multitouch).
  - **Hochformat:** Spieler 1 unten, Spieler 2 oben – ideal, wenn das Handy zwischen
    beiden auf dem Tisch liegt. Punktestand, Pause- und Endbildschirm erscheinen für
    jeden Spieler richtig herum.
  - **Querformat:** Spieler 1 links, Spieler 2 rechts.
- **1 Spieler:** einfach auf dem Bildschirm wischen.
- Menü, Pause und „Nochmal“ per Antippen; kurze Vibration bei Treffern (wenn unterstützt).

### Vorschieben & Schwung
- Die Schläger lassen sich bis zu **1/10 der Feldlänge** ins Feld schieben (die helle Zone
  an beiden Enden). Am Handy: Finger Richtung Gegner bewegen.
- Wer den Ball **mit Schwung** trifft – also den Schläger im Moment des Treffers nach vorne
  bewegt –, macht ihn deutlich schneller (bis +70 %). Schwung-Bälle leuchten orange.
  Der nächste normale Treffer nimmt das Tempo wieder heraus.
- Der Computer holt auf „mittel“ und „schwer“ ebenfalls manchmal Schwung.

Wer zuerst 7 Punkte hat, gewinnt. Der Ball wird mit jedem Treffer schneller; der
Abprallwinkel hängt davon ab, wo er den Schläger trifft.

## Neon Overrun (Entwurf)

Cyberpunk-Survivor in 2D-Pixel-Art, Top-Down – eine einzelne HTML-Datei ohne Abhängigkeiten
(alle Sprites werden im Code erzeugt). Für Handy im Hochformat mit einer Hand gebaut.

**Starten:** `neon-overrun/index.html` im Browser öffnen.

### Steuerung
- **Handy:** irgendwo auf den Bildschirm tippen und ziehen = schwebender Joystick. Waffen feuern automatisch.
  Drei Buttons im Daumenbogen: **DASH** (kurz unverwundbar), **EMP** (Nova, lädt sich durch Kills auf), **II** (Pause).
  Im Menü lassen sich die Buttons auf **Linkshänder** umstellen.
- **PC:** `WASD`/Pfeile, `Leertaste` = Dash, `E` = EMP, `P`/`Esc` = Pause, `1`–`3` = Perk wählen.

### Ablauf
- Gegner lassen Datensplitter fallen → Erfahrung → **Level-Up mit Auswahl aus 3 Perks**
  (5 Waffen, 12 Mods, jeweils mehrstufig).
- **Alle 3 Level erscheint ein Boss** (Enforcer MK-III, Netrunner Hydra, Konzern-Titan – danach stärker im Kreis).
  Besiegte Bosse lassen einen **Boss-Kern** fallen: Auswahl aus 3 von 9 **Spezial-Perks**
  (z. B. Chrom-Herz, Bullet-Time, Orbital-Uplink, Klon-Drohne).
- Gegnertypen: Drohne, Gang-Punk, Kamikaze-Bot, Spitter (schießt), Mech-Brute, seltene Elite-Varianten,
  jede Minute ein Drohnenschwarm.
