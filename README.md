# Auto RTP End (Fabric 1.21.11)

Client-Mod: Hotkey (Standard: R, änderbar unter Steuerung) schaltet das automatische
Ausführen von `/rtp end` an/aus. Das Intervall ist in `RtpEndClient.java` (INTERVAL_TICKS).

## Bauen
1. JDK 21 installieren
2. Im Ordner: `gradle wrapper --gradle-version 9.2.1` (einmalig, erzeugt gradlew)
3. `./gradlew build` (Windows: `gradlew.bat build`)
4. Jar liegt in `build/libs/rtpend-1.0.0.jar` -> in den mods-Ordner (zusammen mit Fabric API)
