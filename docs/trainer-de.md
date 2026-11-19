# QTHome Trainer — Anleitung für Betatester

QTHome Trainer hört mit dir zusammen dein Funkgerät, während du WSJT-X wie gewohnt benutzt, und vergleicht den FT8/FT4-Decoder von QTHome mit dem von WSJT-X. So sehen wir, wo unser Decoder Fehler macht, und können ihn verbessern.

**Er sendet nie und steuert das Funkgerät nie.** Er liest nur das Audio.

## Was du brauchst

- Einen Mac (Apple oder Intel) oder einen PC mit Windows 10/11.
- Das Funkgerät über seine USB-Soundkarte mit dem Computer verbunden (dieselbe wie für WSJT-X).
- **WSJT-X installiert** (kostenlos: <https://wsjt.sourceforge.io/wsjtx.html>). Der Trainer nutzt seinen Decoder als Referenz. Es muss nicht geöffnet sein.

## Installieren

1. Öffne die Release-Seite: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Lade **QTHome-Trainer-Mac.pkg** (Mac) oder **QTHome-Trainer-Windows.zip** (Windows) herunter.
3. Mac: Doppelklick auf das .pkg. Wenn der Mac es ablehnt: Rechtsklick auf die Datei → **Öffnen**.
   Windows: öffne das Zip und starte **QTHome Trainer.exe**. Wenn Windows warnt: **Weitere Informationen → Trotzdem ausführen**.

## Das erste Mal

1. Gib deinen **Locator** ein (4 oder 6 Zeichen, z. B. JN45ab): verwendet wird nur die Gegend.
2. Kreuze an, womit du empfängst und welche Antenne du hast.
3. Entscheide, ob du **Audioausschnitte** sendest (lies den Kasten): sie helfen sehr, du kannst aber nein sagen.
4. **Speichern und beginnen**.

## Jedes Mal

1. Wähle den **Audioeingang des Funkgeräts** (z. B. „USB Audio CODEC“).
2. Drücke **Hören starten**. Am Mac fragt das System beim ersten Mal nach dem Mikrofon: antworte **Erlauben**.
3. Stelle das Funkgerät auf eine FT8-Frequenz (z. B. 14,074 MHz USB) und lass es laufen.

Am Ende jedes 15-Sekunden-Zeitfensters siehst du eine Tabelle: bei jeder Nachricht ✓, wenn QTHome sie dekodiert hat, und ✓, wenn WSJT-X sie dekodiert hat.

Wenn das Fenster kein Audio nutzen kann, erscheint ein Knopf **Im Browser öffnen**: der Trainer öffnet sich im Browser, wo das Mikrofon immer funktioniert.

## CW vom Funkgerät

Kreuze unter **Einstellungen** **CW** an und drücke **Hören starten** auf der Soundkarte des Funkgeräts. Hör CW wie gewohnt: alle 30 Sekunden lesen zwei Decoder von QTHome nochmals, was du gehört hast, und die Rufzeichen werden mit dem Reverse Beacon Network (RBN) geprüft. Läuft The Rigger, kennt der Trainer auch dein Band. Gesendet werden nur nützliche Fälle: ein Rufzeichen, das der RBN nie gehört hat, oder die beiden Decoder sind sich nicht einig.

## Skimmer mit dem SDR-Stick (vorerst nur Mac)

Du brauchst einen RTL-SDR-Stick V3 oder V4 mit einer KW-Antenne (das Funkgerät bleibt frei). Kreuze **Skimmer mit dem SDR-Stick** an, wähle die Bänder und drücke **Skimmer einschalten**: der Stick jagt von selbst. Er geht auf das Band, wo RBN und Spektrum die meisten Stationen zeigen, liest alle gleichzeitig und wechselt, sobald keine neuen Rufzeichen mehr kommen. Je mehr Bänder du wählst, desto mehr Tests macht er. Die Rufzeichen werden mit dem RBN verglichen; in der Tabelle heißt ✓ bestätigt, ? vom RBN nie gehört.

## Was an QTHome geht

- Nur nützliche Fälle: schwache Signale, volle Bänder, Nachrichten, die nur einer der beiden Decoder dekodiert hat.
- **Nie dein Rufzeichen**, keine IP-Adresse, kein Computername, keine persönlichen Ordner.
- Audioausschnitte von 15 Sekunden nur mit deiner Zustimmung, höchstens 6 pro Stunde. Sie werden nach 12 Monaten gelöscht.

## Kostenlose Lizenz für Tester

Bei den Zahlen finden Sie Ihre **Hörstunden** und Ihren **Tester-Code** (QT-XXXX-XXXX): Er ist anonym und enthält Ihr Rufzeichen nicht. Tragen Sie ihn zusammen mit Ihrem Rufzeichen im Formular der Seite [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) ein.

- **10 Stunden** Hören: QTHome PRO ein Jahr kostenlos.
- **100 Stunden** in mindestens 3 verschiedenen Monaten: Gründer-Lizenz, PRO für immer kostenlos.

Es zählen nur Stunden mit eingeschaltetem Funkgerät und empfangenem Signal, und nur solche, die bereits bei QTHome angekommen sind.

## Wenn etwas nicht geht

Drücke oben rechts **Melden**, beschreibe, was passiert ist, und sende es. Es ist anonym; ohne Internet wartet es in einer Warteschlange.

Von IU1MVI.
