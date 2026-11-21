# QTHome Trainer — Anleitung für Betatester

QTHome Trainer hört mit dir zusammen dein Funkgerät, während du es wie gewohnt benutzt,
und vergleicht den FT8/FT4-Decoder von QTHome mit dem von WSJT-X. So sehen wir, wo unser
Decoder Fehler macht, und können ihn verbessern.

**Er sendet nie und steuert das Funkgerät nie.** Er liest nur das Audio.

## Was du brauchst

- Einen Mac (Apple oder Intel) oder einen PC mit Windows 10/11.
- Das Funkgerät per USB-Kabel mit dem Computer verbunden (seine Soundkarte, z. B. „USB Audio CODEC“).
- Sonst nichts: die WSJT-X-Programme für den Vergleich lädt der Trainer einmal selbst herunter.

## Installieren

1. Öffne die Release-Seite: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Lade **QTHome-Trainer-Mac.pkg** (Mac) oder **QTHome-Trainer-Windows.zip** (Windows) herunter.
3. Mac: Doppelklick auf das .pkg. Wenn der Mac es ablehnt: Rechtsklick auf die Datei → **Öffnen**.
   Windows: öffne das Zip und starte **QTHome Trainer.exe**. Wenn Windows warnt: **Weitere Informationen → Trotzdem ausführen**.

## Das erste Mal

Eine Anleitung in 5 Schritten öffnet sich:

1. **Willkommen**: was der Trainer macht.
2. **Deine Station**: der Locator (4 oder 6 Zeichen, z. B. JN45ab, verwendet wird nur die Gegend), Funkgerät und Antenne.
3. **Audio des Funkgeräts**: wähle die Soundkarte des Funkgeräts und stelle eine FT8-Frequenz ein (z. B. 14,074 MHz USB). Der Pegel soll im grünen Bereich liegen. Am Mac fragt das System beim ersten Mal nach dem Mikrofon: antworte **Erlauben**.
4. **Datenschutz**: was wir senden und ob du Audioausschnitte senden möchtest.
5. **Alles bereit**: drücke **Zuhören starten**.

## Das Fenster

- **Übersicht**: das Hören (Eingang, Pegel mit Hinweis, Spektrum), der **Stationsstatus** (Audio, Vergleich mit WSJT-X, Funkgerät, Uhr, Senden) und deine Zahlen. Die vier Lämpchen oben zeigen dasselbe auf einen Blick: grün ist gut, gelb ansehen, rot beheben.
- **FT8 · FT4**: für jeden Slot die von QTHome und von WSJT-X gelesenen Meldungen (grün = beide, rot = nur WSJT-X, gelb = nur QTHome) und die Übereinstimmung der letzten Slots.
- **CW** und **Skimmer**: siehe unten.
- **Einstellungen**: was gehört wird, Computernutzung, Audioausschnitte, Stationsprofil, Updates.

Lass den Trainer geöffnet (auch minimiert), während du funkst: bei jedem Start hört er von selbst weiter.
Die Computeruhr wird über das Internet geprüft: geht sie falsch, korrigiert der Trainer den Slot-Schnitt selbst.

## CW vom Funkgerät

Im Reiter **CW** setze **CW vom Funkgerät lesen** (bei eingeschaltetem Hören). Höre CW wie immer: alle 30 Sekunden
lesen zwei QTHome-Decoder das Gehörte erneut, und die Rufzeichen werden mit dem Reverse Beacon Network (RBN) geprüft.
Läuft The Rigger, kennt der Trainer auch dein Band und die Prüfung ist genauer.

## Skimmer mit dem SDR-Stick (vorerst nur Mac)

Du brauchst einen RTL-SDR V3 oder V4 mit KW-Antenne (das Funkgerät bleibt frei).
In **Einstellungen** setze **Skimmer mit dem SDR-Stick**, wähle im Reiter **Skimmer** die Bänder und drücke
**Skimmer einschalten**: der Stick jagt selbst dort, wo RBN und Spektrum die meisten Stationen zeigen.
In der Tabelle bedeutet ✓ vom RBN bestätigt, ? vom RBN nie gehört.

## Was an QTHome geht

- Nur nützliche Fälle: schwache Signale, volle Bänder, Meldungen, die nur einer der beiden Decoder gelesen hat.
- **Nie dein Rufzeichen**, nie IP-Adresse, Computername oder persönliche Ordner.
- 15-Sekunden-Audioausschnitte nur mit deiner Zustimmung, höchstens 6 pro Stunde. Sie werden nach 12 Monaten gelöscht.
- Ist das Senden noch nicht aktiv oder fehlt Internet, warten die Fälle auf dem Computer und gehen später von selbst: die Zeile **Senden** im Status zeigt immer den Stand.

## Kostenlose Lizenz für Tester

In der Übersicht findest du deine **Hörstunden**, die Balken zur Lizenz und deinen **Tester-Code** (QT-XXXX-XXXX): er ist anonym. Trage ihn im Formular der Seite [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) zusammen mit deinem Rufzeichen ein.

- **10 Stunden** Hören: QTHome PRO ein Jahr gratis.
- **100 Stunden** in mindestens 3 verschiedenen Monaten: Gründerlizenz, PRO für immer gratis.

Es zählen nur Stunden mit eingeschaltetem Funkgerät und ankommendem Signal.

## Wenn etwas nicht geht

Drücke oben rechts **Melden**, beschreibe, was passiert ist, und sende. Es kommt anonym an; ohne Internet wartet es und geht später.

Von IU1MVI.
