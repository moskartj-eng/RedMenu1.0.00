# Red Texture Menu 1.1.0  (Fabric, Minecraft 1.21.11)

Befehl: `/redmenu`

Packs ablegen in `.minecraft/redclient/packs` (.zip oder entpackte Ordner).

## Bedienung
- Tab TEXTURES: Kategorie links, Textur anklicken = auswaehlen (nochmal = abwaehlen), Rechtsklick = markieren.
  Rechts oben steht die Auswahlliste. Unten rechts: **Anwenden** (baut das Pack) und **Done** (laedt alle Resource Packs neu).
- Tab HUD: Akzentfarbe, Hintergrundfarbe (Hex moeglich), Menue-Textur (Muster oder eine Textur aus deinen Packs kacheln),
  Deckkraft, Scroll-Glaette, Motion Blur, Sound-Lautstaerke, Tipp-Sounds an/aus.

## Wie "Anwenden" funktioniert
Die ausgewaehlten Texturen werden unveraendert (inkl. .mcmeta fuer Animationen) in ein Pack
`resourcepacks/RedClient_Selection/` kopiert. Done aktiviert es ganz oben und laedt neu.
Leere Auswahl + Anwenden entfernt das Pack wieder.

## Bauen
    gradle build        (oder ./gradlew build, wenn du den Wrapper hast)
Die Jar liegt danach in build/libs/. Mappings: Yarn. Versionen in gradle.properties pruefen.
