# QTHome — Handbuch

QTHome ist das Programm für die ganze Station: Funkgerät, Log, CW, digitale Betriebsarten, Cluster, SDR, Satelliten, Contests und mehr, in einem Fenster. Es ist ein einziges Programm: Funkgerät, Rufzeichen, laufende Verbindung und Log sind in jedem Bereich dieselben. Hören und Dekodieren sind kostenlos.

## Installieren

- **Mac**: `QTHome-Mac.pkg` herunterladen, öffnen und den Schritten folgen. QTHome liegt in Programme.
- **Windows**: `QTHome-Windows.zip` herunterladen, öffnen und `QTHome.exe` an einen beliebigen Ort ziehen (zum Beispiel auf den Desktop), dann öffnen.

QTHome aktualisiert sich selbst: Gibt es eine neue Version, wird sie geladen und beim Beenden installiert.

## Beim ersten Mal

1. Das Funkgerät mit dem USB-Kabel an den Computer anschließen und einschalten.
2. QTHome öffnen: Das **Willkommensfenster** erklärt die ersten Schritte (« Nicht mehr anzeigen » ankreuzen, wenn Sie es nicht mehr brauchen), danach fragt es nach **Rufzeichen und Locator**. Alle Funktionen verwenden sie.
3. Das Funkgerät erscheint von selbst. In **Station** zeigt die Karte **Erste Schritte**, was fehlt (Funkgerät, Audio, Cluster), mit der passenden Schaltfläche.
4. Auf dem Mac beim ersten Hören das **Mikrofon** für QTHome erlauben: das ist das Audio des Funkgeräts.
5. Für eine andere Sprache: **Einstellungen › Aussehen, Sprache und Barrierefreiheit**.

## Das Fenster

- **Oben**: die Menüs, der Zustand von Funkgerät und SDR-Stick, Ihr Rufzeichen und die UTC-Zeit.
- **Die Funkgeräteleiste** ist immer sichtbar: Funkgerät, Band, Frequenz (VFO A und B), Betriebsart, Filter, **PTT · TX** (rot, sobald das Funkgerät sendet, egal wer es tastet; löst sich nach 3 Minuten selbst) und **Funkgerät-Bedienung** mit allen Reglern der Front.
- **Links** die Bereiche. Standardmäßig sehen Sie nur die wichtigsten; die anderen stehen unter **+ Weitere Funktionen** (oder immer alle: **Einstellungen › Aussehen, Sprache und Barrierefreiheit**).
- **Unten der Wasserfall**, über der QSO-Leiste, in Station, Log, Sprechfunk, Contest, Cluster, Karte, Satelliten und Rotor: ein Klick auf « Wasserfall » klappt ihn ein.
- **Etwas nicht gefunden?** ⌘K (Strg+K unter Windows) öffnet die Suche: „SSTV“, „Rotor“, „HamQTH“ oder „Lizenz“ eingeben und Eingabe drücken.
- **Unten die QSO-Leiste**: die laufende Verbindung, eine für das ganze Programm. Rufzeichen eingeben (Alt+Q führt von überall dorthin), Rapporte, Name und Locator; Frequenz, Band und Betriebsart kommen vom Funkgerät. Sie zeigt Land, Entfernung, Richtung, auf welchen Bändern er gerade gehört wird und ob Sie ihn schon gearbeitet haben. **Eingabe** speichert ins Log, **Esc** fängt neu an. Beim Senden stoppt **Esc** jede Sendung (FT8, Fonie, CW, PTT), wie Station › Jede Sendung stoppen. In die Notiz kannst du „POTA IT-0123“, „SOTA I/LO-123“ oder „WWFF IFF-0123“ schreiben: die Referenz kommt in ihr Log-Feld. Versehentlich gespeichert? Direkt danach erscheint **Rückgängig**: das QSO verlässt das Log und kommt zurück in die Leiste. In Europa oder Afrika gibt es einen Hinweis, wenn du in Sprechfunk im CW-/Digitalbereich des Bandes oder auf 30 m bist (IARU-Bandplan).
- Ohne verbundenes Funkgerät (oder mit der Schaltfläche **✎**) werden Frequenz, Betriebsart, Datum und UTC-Zeit von Hand eingegeben: praktisch für eine Portabel-Verbindung.
- Auch Cluster, Karte, „Jetzt arbeiten“, FT8, RTTY/PSK und CW füllen die laufende Verbindung: ein Klick auf einen Spot bringt das Funkgerät auf Frequenz und Betriebsart und das Rufzeichen in die Leiste. Mit Rotor dreht **↻ Rotor** die Antenne zu ihm.
- Alles geht auch mit der Tastatur und mit einem Bildschirmleser. Für blinde oder sehbehinderte Funkamateure: **Einstellungen › Aussehen, Sprache und Barrierefreiheit › Barrierefreiheit einschalten** (Sprachansagen, Morse, S-Meter-Ansage mit ⌘⇧S). Standardmäßig aus.

## Die Bereiche

- **Station**: große Frequenzanzeige, S-Meter, PTT, Funkgerät-Bedienung, Speicher (auch von und zu CHIRP), wer gerade arbeitbar ist und offene Bänder.
- **Log**: alle Verbindungen aus allen Bereichen. Suche nach Rufzeichen, Land oder Band; **Klick auf eine Zeile** zum Korrigieren oder Löschen. Papier-QSL (Büro und direkt, Etiketten zum Drucken) und **elektronische QSL**: LoTW (TQSL nötig, kostenlos), eQSL, QRZ Logbook und Club Log. Diplome und Stationsprofile. Wenn Sie einen Park oder Gipfel aktivieren, tragen Sie die Referenz im Profil ein (Profile… › „Aktiviere“): Jedes QSO trägt sie im Log und im ADIF; in den Digitalbetriebsarten ruft das Menü neben CQ „CQ POTA“ oder „CQ SOTA“. **Statistik…**: QSOs nach Jahr, Band, Betriebsart und UTC-Stunde, der beste Tag und die bestätigten. Im Profil auch die **Leistung** (W) eintragen: sie geht in jedes QSO (TX_PWR), wählt die Leistungsklasse in Contesten, und die Statistik zeigt den Rekord km pro Watt. Der Export pro Profil liefert die Datei mit dem Namen, den POTA und WWFF verlangen. In **Diplome…** listet das Kästchen „nur noch zu bestätigende“ alles Gearbeitete ohne Bestätigung, mit den Rufzeichen, bei denen man die QSL anfragt.
- **Sprechfunk**: Hören und Aufnehmen, die letzten 60 Sekunden immer speicherbar, 4 Sprachspeicher (F1-F4). **FreeDV** (700D, 700E, 700C, 1600): Hören über das Audio des Funkgeräts und « Zum Sprechen gedrückt halten ». **Pi-Star / WPSD**: wer über Ihren DMR-, D-STAR- oder YSF-Hotspot kommt, mit einem Klick in die QSO-Leiste.
- **CW**: der CWEngine-Dekoder, Taste, Texte, Skimmer mit dem SDR-Stick. Eingeschaltet läuft er weiter, während Sie andere Bereiche nutzen. Verbindungen von hier landen im QTHome-Log. CW-Dekodierung bleibt für immer kostenlos.
- **Digitale Betriebsarten**: FT8 und FT4 wie WSJT-X (automatische Folge, CQ, automatisches Log), RTTY, PSK31/63, Feld Hell, QRSS, APRS, WSPR und SSTV (Bilder: die Betriebsart wird automatisch erkannt, empfangene Bilder bleiben in der Galerie). Das Band folgt dem Funkgerät. FT8-, FT4-, RTTY- und PSK-Spots bringen das Funkgerät an die richtige Stelle und öffnen die Digitalmodi mit der Gegenstation. Dekodierungen und QSOs können auch an GridTracker, JTAlert, N1MM oder Log4OM gehen, wie von WSJT-X (Einstellungen › Funkgeräte und Programme). Bei eingeschaltetem Senden bereitet ein Doppelklick auf eine Station in GridTracker oder JTAlert sie in den Digitalmodi vor (Tx1 bereit, senden entscheidest du). Bei der automatischen Jagd antwortet es nur auf CQs, die Ihnen gelten: „CQ POTA/SOTA/WWFF“ immer (Portabelstationen zählen jeden Tag neu), „CQ DX“ nur, wenn der Rufer auf einem anderen Kontinent ist, „CQ NA“, „CQ EU“… nur für Ihren, „CQ TEST“ nur bei laufendem Contest.
- **Contest**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF und allgemein; Nummern, Doppelte, Cabrillo und SO2R. Eingabe loggt, Esc löscht. Läuft ein Contest, fragt auch die QSO-Leiste nach dem empfangenen Austausch, und jedes QSO (FT8, CW, RTTY…) kommt in den Contest; oben steht der laufende Contest. Die Punktzahl folgt den Contest-Regeln (CQ WW, WPX, ARI DX, IARU, VHF) und kommt ins Cabrillo; bei CQ WW und IARU wird die Zone aus dem Präfix vorausgefüllt. Contest-Werkzeuge: Bandkarte, Rufzeichenvorschläge beim Tippen (mit „vielleicht“ bei einem Zeichen Unterschied), bearbeitbare F1-F4-Texte ({MYCALL} {CALL} {EXCH}) und ESM: Eingabe sendet CQ, Austausch und TU. Dazu kommt der ARI FT8 Activity Contest (IAC): 1 Punkt pro QSO, Multiplikatoren sind 4-stellige Felder. Ohne verbundenes Funkgerät (kein CAT) wählen Sie Band und Betriebsart von Hand neben dem Rufzeichen. Es gibt auch den **ARRL International DX** für Stationen außerhalb der USA und Kanadas (3 Punkte pro W/VE-Station, Bundesstaaten und Provinzen als Multiplikatoren). Oben die **nächsten großen Conteste** mit Datum: ein Klick wählt ihn aus; dein Austausch (Zone, Locator, Leistung) wird von selbst eingetragen, und am Vortag kommt eine Erinnerung.
- **Satelliten und Weltraum**: nächste Überflüge, Doppler, Nachführung mit Rotor und Funkgerät-Korrektur. Die Bahndaten laden sich selbst. QO-100: Ausrichtung von Ihrem Locator, LNB-Drehung, Baken und Umrechnung zwischen Downlink, Uplink und LNB-Ausgang.
- **Cluster und Ausbreitung**: DX-Cluster und Reverse Beacon Network mit Filtern; ein Klick auf einen Spot bringt das Funkgerät dorthin. Sonnendaten und Bandbedingungen. NCDXF/IARU-Baken: wer jetzt auf jedem Band sendet, Entfernung und Richtung, und welche wirklich von Ihrem Kontinent gehört wurden. „Jetzt offen“: Band × Kontinent, mit den Stationen, die in den letzten 30 Minuten wirklich von Ihrem Kontinent gehört wurden. POTA-, SOTA- und WWFF-Portabel-Spots lassen sich dazunehmen: die Park- oder Gipfelreferenz kommt ins Log. **24-Stunden-Vorhersage**: welche Bänder Stunde für Stunde zum QSO-Partner oder in eine Weltregion öffnen; eine Schätzung aus dem Solarflux (die Spots unter „Jetzt offen“ zeigen, was wirklich offen ist). Die QSO-Leiste zeigt sie, wenn es keine Spots zu dieser Station gibt, und der Assistent beantwortet „propagation to Japan?“. Unter **Zeigen** nur neue Länder oder nur Stationen, die du auf dem Band noch nicht gearbeitet hast. Die DXCC-Länder aktualisieren sich jede Woche von selbst.
- **Karte**: Nacht und Greyline, Spots, wer Sie hört, EME, Es; ein Klick auf einen Spot arbeitet ihn. „Meine QSOs“ zeigt, wo die Stationen im Log sind (grün = bestätigt). Mit „Offen von Ihnen aus (Schätzung)“ wählen Sie ein Band, und die Karte färbt die Weltregionen, die dieses Band jetzt von Ihrer Station aus erreicht.
- **SDR**: Empfänger mit dem RTL-SDR-Stick, Spektrum und Wasserfall; Klick zum Hören einer Frequenz.
- **Rotor**: nach Grad, zu einem Locator oder zur laufenden Verbindung drehen, auch über den langen Weg.
- **QTHome Chat**: Text- und Sprachräume unter Funkamateuren, verschlüsselte private Nachrichten; auf dem Server bleibt nichts.
- **Winlink**: Mail über Internet oder per Funk mit dem VARA-Modem (separat installiert): Eingang, Ausgang, Anhänge, ICS-213-Formular für den Notfunk. Das Winlink-Passwort bleibt auf Ihrem Computer.
- **Werkzeuge**: Rechner, Smith-Diagramm, Antennenlabor, Pile-up-Training, **CW lernen mit der Koch-Methode**, Prüfungsquiz.
- **KI-Assistent**: schreiben Sie, was Sie wollen („Funkgerät auf 14.074 FT8“, „wann kommt die ISS“, „was bedeutet QSB“). Er arbeitet auf dem Computer und sendet nie. Ist das Fenster nicht auf Italienisch, versteht und antwortet er auf Englisch; mit einem Modell auf dem Computer (Ollama oder LM Studio) in jeder Sprache.
- **Einstellungen**: Ihre Station, Funkgeräte und externe Programme (WSJT-X, fldigi, Logbücher), welches Funkgerät und welches Audio jede Funktion nutzt, Zubehör (Endstufe, Antennenumschalter, Batterie, Wetter, WinKeyer), Aussehen, Sprache und Barrierefreiheit. Unter **Meine Station** wählen Sie auch die **Bänder und Betriebsarten, die Sie nutzen** („Du kannst jetzt arbeiten“ und der Cluster richten sich danach) und die **Hinweise**: neues Land in der Luft, Satellit kommt und „Du wirst gehört“ (dein Rufzeichen in Spots), in jedem Bereich.

## Kostenlos und PRO

Hören, Dekodieren und Loggen sind immer kostenlos. Senden aus QTHome, Automatik, erweiterter Contest und Online-QSL gehören zu PRO; die ersten 30 Tage sind eine vollständige Probe. PRO kostet **12 € im Jahr**: das deckt Server- und Forschungskosten.

## Wenn etwas nicht geht

- **Das Funkgerät erscheint nicht**: USB-Kabel prüfen und ob das Funkgerät eingeschaltet ist; dann **Einstellungen › Funkgeräte und Programme › Funkgeräte erneut suchen**.
- **Kein Audio**: auf dem Mac Systemeinstellungen › Datenschutz & Sicherheit › Mikrofon › QTHome einschalten. Unter Windows Einstellungen › Datenschutz › Mikrofon.
- **Problem melden**: **Hilfe › Problem oder Idee melden…** Der Bericht ist anonym, ohne Rufzeichen, Namen oder Adressen.

## Lizenzen und Dank

QTHome ist ein Programm von IU1MVI. Sein Code ist neu geschrieben oder baut auf Bibliotheken auf, deren freie Lizenz das erlaubt; kein GPL-lizenzierter Code ist in QTHome kopiert.

- **ft8_lib** © Kārlis Goba (MIT): Grundlage des FT8/FT4-Decoders. Methode aus der öffentlichen Arbeit von K1JT, K9AN und G4WJS (QEX 2020).
- **wl2k-go** © Martin Hebnes Pedersen LA5NTA (MIT): Winlink-B2F-Protokoll; enthält **lzhuf** von Haruyasu Yoshizaki und Haruhiko Okumura.
- **codec2** © David Rowe VK5DGR und Mitwirkende (LGPL-2.1): FreeDV. Eigene, austauschbare Bibliothek; Quelltext: github.com/drowe67/codec2.
- **libusb** (LGPL-2.1): SDR-Stick auf Mac und Windows, eigene, austauschbare Bibliothek; Quelltext: github.com/libusb/libusb.
- **webview** (MIT) für das Fenster; **webrtlsdr** (Apache 2.0) für den SDR-Stick in der CW-Funktion; Typbibliothek von **OmniRig** © VE3NEA (MIT).
- **Eigenständige Programme**, die QTHome nutzt, wenn sie installiert sind, ohne sie mitzuliefern: **WSJT-X** (GPL, K1JT und Mitwirkende) für Q65, MSK144, JT65 und den Vergleich im Trainer; **VARA** (EA5HVK) für Winlink per Funk; **TQSL** (ARRL) für LoTW; **JS8Call** (KN4CRD); **Pi-Star** und **WPSD** auf dem Hotspot; **Ollama** oder **LM Studio** für den Assistenten.
- **Daten**: DXCC-Gebiete aus AD1Cs **cty.dat** (country-files.com); Sonnendaten von **hamqsl.com** (N0NBH) und **NOAA SWPC**; Ionosonden des **GIRO**-Netzes über **prop.kc2g.com** (KC2G); Bahndaten von **CelesTrak**; Spots aus DX-Clustern, dem **Reverse Beacon Network**, **PSK Reporter** (N1DQ), **POTA**, **SOTA** und **WWFF**; **Super Check Partial** (supercheckpartial.com); Rufzeichensuche mit **HamQTH**; Weltkarten von **Natural Earth** (gemeinfrei).

Die vollständigen Lizenztexte stehen in **docs/terze-parti.md** im öffentlichen Repository SculptWorksLTD/QTHome.

QTHome stammt von IU1MVI. Wenn es Ihnen nützt, können Sie einen Kaffee spendieren: paypal.me/nerosdmf
