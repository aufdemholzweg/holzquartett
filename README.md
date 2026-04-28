# 🌲 HOLZEN! 🌲 - Das Holzlernspiel

Willkommen beim **HOLZEN!**, einem digitalen Lernspiel für Lehramtsstudierende und Berufsschüler. 

Dieses Lernspiel wurde im Rahmen meiner Masterarbeit an der **Leibniz Universität Hannover** (Studiengang Lehramt an Berufsbildenden Schulen, Fachrichtung Holztechnik) entwickelt. Das Thema der Arbeit lautet: *"Gamification in der beruflichen Lehrkräfteausbildung: Entwicklung und didaktische Einbettung eines Lernspiels zur Förderung intrinsisch motivierter Lernprozesse"*.

Es überträgt das beliebte Spielprinzip von "Supertrumpf" in den fachlichen Kontext mit Wissen über Holzarten zum spielerischen Vermitteln und Lernen.

## 🎮 Das Spielprinzip
Ziel ist es, dem Gegner alle Karten abzunehmen, indem man gezielt technische Eigenschaften wählt, in denen das eigene Holz überlegen ist (z. B. höhere Dichte oder geringeres Schwindverhalten).

## ✨ Features
* **Zwei Spielmodi:**
  
  * 🤖 **Einzelspieler:** Trainiere dein Wissen gegen einen computergesteuerten Gegner.
  * 🌍 **Multiplayer:** Spiele in Echtzeit gegen Mitstudierende oder Freunde (inkl. QR-Code Lobby).
* **30+ Holzarten** mit realen technischen Daten (basierend auf DIN-Normen).
* **Wissens-Datenbank:** Detaillierte Infos, Bilder (Maserung & Detailansicht) und Verbreitungsgebiete.
* **Gamification:** Sammle Flammen für Siege und aktiviere den **"Run-Modus"** bei 5 Gewinnen in Folge! 🔥

## 📜 Spielregeln
Das Spiel basiert auf dem klassischen „Supertrumpf“-Prinzip, erweitert um didaktische Elemente:

1. **Ziel:** Gewinne alle Karten des Gegners.
2. **Ablauf:** Die aktive Person wählt eine Eigenschaft ihrer obersten Karte, die den größtmöglichen Vorteil verspricht.

### Die Eigenschaften & Gewinnlogik
Nicht immer ist der höhere Wert besser! Die Logik orientiert sich an der fachlichen Realität:

* **⬆️ Höherer Wert gewinnt bei:**
  * 💎 **Druckfestigkeit** ($N/mm^2$)
  * ⚖️ **Rohdichte** ($kg/m^3$)
  * 📐 **E-Modul** ($N/mm^2$)
  
* **⬇️ Niedrigerer Wert gewinnt bei:**
  * 🛡️ **Dauerhaftigkeitsklasse** (DK 1 ist besser als DK 5)
  * ↔️ **Quellen/Schwinden** (%)
  * 💰 **Preisstufe** (Günstiger gewinnt)

### Rundenentscheidung
* **Sieg:** Wer den "besseren" Wert hat, erhält beide Karten und legt sie unter den eigenen Stapel. Die Person bleibt am Zug.
* **Gleichstand (Das Quiz):** Haben beide Karten den exakt gleichen Wert (z. B. beide Preisstufe 3), startet das **Stechen**! 
  * Es erscheint eine Fachfrage (Multiple Choice).
  * Wer die Frage innerhalb des Zeitlimits (10 Sek.) am schnellsten richtig beantwortet, gewinnt die Runde.
  * Bei falscher Antwort gewinnt automatisch der Gegner.


## 🛠️ Technik & Daten

* **Datenbasis:** Die Holzdaten basieren auf DIN 68364, DIN EN 338 und DIN EN 350.
* **Backend:** Spielstände und Statistiken werden über **Google Firebase** synchronisiert.
* **Hosting:** GitHub.com

## ⚖️ Lizenz & Credits

Der Quellcode dieses Projekts, das Spielkonzept sowie die Quizfragen sind lizenziert unter der **CC BY 4.0** Lizenz.

**Sounds:**
Soundeffekte von [freesound.org).



Viel Spaß beim "Holzen"! 🌲🪚
