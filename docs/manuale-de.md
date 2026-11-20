# QTHome — Handbuch

QTHome ist das Programm für die ganze Station: Funkgerät, Log, CW, digitale Betriebsarten, Cluster, SDR, Satelliten, Conteste und mehr, in einem einzigen Fenster. Es läuft auf deinem Computer, ohne Abo für Hören und Dekodieren.

## Installieren

- **Mac**: lade `QTHome-Mac.pkg` herunter, öffne es und folge den Schritten. QTHome liegt danach unter Programme.
- **Windows**: lade `QTHome-Windows.zip` herunter, öffne es und ziehe `QTHome.exe` an einen Ort deiner Wahl (zum Beispiel auf den Desktop), dann öffne es.

QTHome aktualisiert sich selbst: kommt eine neue Version, lädt es sie herunter und installiert sie beim Beenden.

## Das erste Mal

1. Verbinde das Funkgerät per USB-Kabel mit dem Computer und schalte es ein.
2. Öffne QTHome: das Funkgerät erscheint von selbst im Bereich **Station** (The Rigger ist eingebaut und erkennt die Funkgeräte).
3. Klicke oben rechts auf **Rufzeichen?** und gib dein Rufzeichen und deinen Locator ein.
4. Für eine andere Sprache: **Hilfe › Sprache…**

## Das Fenster

- **Oben**: die Menüs, der Zustand des Funkgeräts und des SDR-Sticks, dein Rufzeichen und die UTC-Zeit.
- **Die Funkgeräteleiste** ist immer sichtbar: Funkgerät wählen, Frequenz (VFO A und B) und Betriebsart lesen und ändern, **PTT · TX** drücken zum Senden (schaltet nach 3 Minuten von selbst ab).
- **Links** die Bereiche, **rechts** der gewählte Bereich. Was noch nicht fertig ist, ist mit „Bald verfügbar“ markiert.
- Alles geht auch mit der Tastatur und mit dem Screenreader; **Hilfe › Stimme** sagt Frequenz, Betriebsart und Signal an.

## Die Bereiche

- **Station**: die verbundenen Funkgeräte, die große Frequenzanzeige, das S-Meter, ein schnelles QSO. Programme wie WSJT-X, fldigi oder JS8Call verbinden sich über QTHome mit dem Funkgerät: die Anleitung steht unter „So verbindest du Programme“.
- **Rotor**: einen Rotor anschließen (Yaesu GS-232 oder Hamlib rotctld) und ihn auf Grad oder einen Locator richten, auch über den langen Weg.
- **Log**: jedes QSO, ADIF-Export und -Import. Unten die **elektronischen QSLs**: LoTW (braucht das kostenlose TQSL), eQSL, QRZ Logbook und Club Log; die Passwörter bleiben auf deinem Computer.
- **Sprechfunk**: Hören und Aufnehmen, die letzten 60 Sekunden immer speicherbar, 4 Sprachspeicher (F1-F4) zum Senden. **FreeDV** (700D, 700E, 700C, 1600): Hören über das Audio des Funkgeräts und „zum Sprechen gedrückt halten“. **Pi-Star / WPSD**: wer über Ihren DMR-, D-STAR-, YSF-Hotspot kommt, mit einem Klick in die QSO-Leiste.
- **CW**: der CWEngine-Decoder, die Taste, die Texte, der Skimmer mit dem SDR-Stick. CW-Dekodieren bleibt für immer kostenlos.
- **Digitale Betriebsarten**: FT8 und FT4 wie WSJT-X (Empfang und Senden), RTTY, PSK, APRS, WSPR, Hell, QRSS und SSTV. Q65, MSK144 und JT65 über das daneben geöffnete WSJT-X (Bereich „Weitere Betriebsarten mit WSJT-X“).
- **Cluster und Ausbreitung**: DX-Cluster und Reverse Beacon Network mit Filtern; ein Klick auf einen Spot bringt das Funkgerät dorthin. Sonnendaten und Bandbedingungen.
- **SDR**: Empfänger mit dem RTL-SDR-Stick, Spektrum und Wasserfall; klicken, um eine Frequenz zu hören.
- **Satelliten und Weltraum**: nächste Überflüge, Doppler, Nachführung mit dem Rotor und Korrektur des Funkgeräts.
- **Fernbedienung und Automatik**: QTHome vom Handy im Heimnetz nutzen, mit PIN. Senden aus der Ferne bleibt aus, bis du es erlaubst.
- **Contest**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF und allgemein; Nummern, Doppelte, Cabrillo. Enter loggt, Esc leert.
- **QTHome Chat**: Text- und Sprachräume unter Funkamateuren; auf dem Server bleibt nichts.
- **Winlink**: Mail über Internet oder per Funk mit dem VARA-Modem (separat installiert): Eingang, Ausgang, Verfassen. Das Winlink-Passwort bleibt auf Ihrem Computer.
- **Karte** und **Werkzeuge**: die Welt jetzt (Spots, wer Sie hört, Greyline, Ionosonden) und Rechner für die Station.
- **KI-Assistent**: schreib, was du willst („stell das Funkgerät auf 14.074 FT8“, „wann kommt die ISS“, „was heißt QSB“). Er arbeitet auf dem Computer, ohne Internet, und sendet nie.

## Kostenlos und PRO

Hören, Dekodieren und Loggen ist immer kostenlos. Senden aus QTHome, Automatik, erweiterter Contest und Online-QSLs gehören zu PRO; die ersten 30 Tage sind ein vollständiger Test. PRO kostet **12 € im Jahr**: damit werden Server und Entwicklung bezahlt.

## Wenn etwas nicht geht

- **Das Funkgerät erscheint nicht**: prüfe das USB-Kabel und ob das Funkgerät an ist; dann **Station › Erneut nach Funkgeräten suchen**.
- **Kein Ton**: am Mac das Mikrofon für QTHome erlauben unter Systemeinstellungen › Datenschutz & Sicherheit.
- **Problem melden**: **Hilfe › Problem oder Idee melden…** Es geht anonym raus, ohne Rufzeichen, Namen oder Adressen.

QTHome ist von IU1MVI. Wenn es dir nützt, kannst du ihm einen Kaffee spendieren: paypal.me/nerosdmf
