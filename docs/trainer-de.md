# QTHome — Anleitung für Betatester

Ein eigenes Programm ist nicht mehr nötig: QTHome übernimmt jetzt die Arbeit des Trainers.

## So schaltest du es ein

1. Öffne QTHome und gehe zu **Einstellungen › Hilf, CW zu verbessern**.
2. Setze **Hilf, CW zu verbessern (anonym)**.
3. Wähle den **Audioeingang des Funkgeräts** (z. B. „USB Audio CODEC“).
4. Wenn du willst, erlaube auch das Senden von **Audioausschnitten** zweifelhafter Fälle.

Dann höre CW wie immer. Alle 30 Sekunden lesen zwei QTHome-Decoder das Empfangene erneut, und die Rufzeichen werden mit dem
Reverse Beacon Network (RBN) geprüft. Ist der Skimmer der CW-Funktion an (SDR-Stick), werden auch seine Rufzeichen alle
2 Minuten geprüft. **Er sendet nie und steuert das Funkgerät nie.**

FT8 und FT4 braucht es nicht mehr: QTHome dekodiert sie mit der WSJT-X-Engine, die es beim ersten Mal selbst lädt.

## Was an QTHome geht

- Nur nützliche Fälle: Abweichungen zwischen den Decodern, vom RBN nie gehörte Rufzeichen, nicht gelesene starke Stationen.
- **Nie dein Rufzeichen**, keine IP-Adresse, kein Computername, keine persönlichen Ordner; der Locator nur mit 4 Zeichen.
- Audioausschnitte nur mit Zustimmung, höchstens 6 pro Stunde, nach 12 Monaten gelöscht.
- Ist das Senden noch nicht aktiv oder fehlt Internet, warten die Fälle auf dem Computer und gehen später von selbst.

## Kostenlose Lizenz für Tester

Auf derselben Seite: deine **Hörstunden**, die Balken zur Lizenz und dein **Tester-Code** (QT-XXXX-XXXX, anonym).
Trage ihn mit deinem Rufzeichen im Formular der Seite [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) ein.

- **10 Stunden** Hören: QTHome PRO ein Jahr gratis.
- **100 Stunden** in mindestens 3 verschiedenen Monaten: Gründerlizenz, PRO für immer gratis.

Es zählen nur Abschnitte, in denen wirklich CW ankommt.

Von IU1MVI.
