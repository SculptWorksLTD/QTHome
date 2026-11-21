# QTHome — manuale

QTHome è il programma per tutta la stazione: radio, log, CW, modi digitali, cluster, SDR, satelliti, contest e altro, in una sola finestra. È un programma solo: la radio, il nominativo, il QSO in corso e il log sono gli stessi in ogni sezione. Ascoltare e decodificare è gratis.

## Installare

- **Mac**: scarica `QTHome-Mac.pkg`, aprilo e segui i passi. QTHome si trova in Applicazioni.
- **Windows**: scarica `QTHome-Windows.zip`, aprilo e trascina `QTHome.exe` dove preferisci (per esempio sul Desktop), poi aprilo.

QTHome si aggiorna da solo: quando c'è una versione nuova la scarica e la installa alla chiusura.

## La prima volta

1. Collega la radio al computer con il cavo USB e accendila.
2. Apri QTHome: la **finestra di benvenuto** spiega i primi passi (spunta «Non mostrare più» quando non ti serve), poi ti chiede **nominativo e locatore**. Li usano tutte le funzioni.
3. La radio compare da sola. Nella **Stazione** la scheda **Per cominciare** mostra cosa manca (radio, audio, cluster), con il tasto per farlo.
4. Su Mac, la prima volta che ascolti la radio, consenti il **microfono** a QTHome: è l'audio che arriva dalla radio.
5. Se vuoi un'altra lingua: **Impostazioni › Aspetto, lingua e accessibilità**.

## La finestra

- **In alto**: i menu, lo stato della radio e della chiavetta SDR, il tuo nominativo e l'ora UTC.
- **La barra della radio** è sempre visibile: radio, banda, frequenza (VFO A e B), modo, filtro, **PTT · TX** (diventa rosso quando la radio trasmette, chiunque la comandi; si rilascia da solo dopo 3 minuti) e **Comandi radio** con tutti i comandi del pannello frontale.
- **A sinistra** le sezioni. Di serie vedi solo quelle essenziali; le altre sono sotto **+ Altre funzioni** (o tutte sempre: **Impostazioni › Aspetto, lingua e accessibilità**).
- **In basso la cascata**, sopra la barra QSO, in Stazione, Log, Fonia, Contest, Cluster, Mappa, Satelliti e Rotore: un clic su «Cascata» la piega.
- **Non trovi qualcosa?** ⌘K (Ctrl+K su Windows) apre la ricerca: scrivi «SSTV», «rotore», «HamQTH» o «licenza» e premi Invio.
- **In basso la barra QSO**: il QSO in corso, uno solo per tutto il programma. Scrivi il nominativo (Alt+Q ci arriva da ovunque), rapporti, nome e locatore; frequenza, banda e modo li prende dalla radio. Ti dice il paese, la distanza, la direzione, su che bande lo si sente adesso e se lo hai già collegato. **Invio** salva nel log, **Esc** ricomincia. Mentre trasmetti, **Esc** ferma ogni trasmissione (FT8, fonia, CW, PTT), come Stazione › Ferma ogni trasmissione. Nella nota puoi scrivere «POTA IT-0123», «SOTA I/LO-123» o «WWFF IFF-0123»: il riferimento va nel suo campo del log. Salvato per sbaglio? Subito dopo compare **Annulla salvataggio**: il QSO esce dal log e torna nella barra. Se sei in Europa o in Africa ti avvisa quando sei in fonia nella parte CW/digitali della banda o sui 30 m (band plan IARU).
- Senza la radio collegata (o col tasto **✎**) frequenza, modo, data e ora UTC si scrivono a mano: utile per registrare un QSO fatto col portatile.
- Il QSO in corso lo riempiono anche il cluster, la mappa, «Puoi lavorare ora», FT8, RTTY/PSK e il CW: un clic su uno spot porta la radio sulla frequenza e nel modo giusto e mette il nominativo nella barra. Con un rotore, **↻ Rotore** gira l'antenna verso di lui.
- Tutto si usa anche da tastiera e con lo screen reader. Per chi non vede o vede poco: **Impostazioni › Aspetto, lingua e accessibilità › Accendi l'accessibilità** (annunci a voce, Morse, S-meter letto con ⌘⇧S). È spenta di serie.

## Le sezioni

- **Stazione**: la frequenza grande, l'S-meter, il PTT, i comandi della radio, le memorie (anche da e per CHIRP), chi puoi lavorare adesso e le bande aperte. **S-meter in dBm**: in Impostazioni › Radio e programmi si legge in unità S e dBm e si tara con un segnale noto. **Radio FlexRadio** (SmartSDR) trovate da sole nella rete di casa. **Ponti vicini** da RepeaterBook (file esportato dal sito) con un clic in memoria; **Scrivi nella radio** carica le memorie nelle Icom via CI-V (le altre radio e i portatili con CHIRP). **Paddle USB** (Impostazioni › Accessori): keyer iambico che manipola la radio con la linea DTR della porta USB.
- **Log**: tutti i QSO, da ogni sezione. Cerca per nominativo, paese o banda; **clic su una riga** per correggerla o cancellarla. QSL cartacee (bureau e diretta, etichette da stampare) e **QSL elettroniche**: LoTW (serve TQSL, gratuito), eQSL, QRZ Logbook e Club Log, HRDLog.net, Wavelog/Cloudlog. Diplomi e profili di stazione. Se vai in attivazione da un parco o una cima, scrivi il riferimento nel profilo (Profili… › «Attivo da»): ogni QSO lo porta nel log e nell’ADIF; nei Modi digitali il menu accanto a CQ chiama «CQ POTA» o «CQ SOTA». **Statistiche…**: QSO per anno, banda, modo e ora UTC, il giorno migliore e i confermati. Nel profilo metti anche la **potenza** (W): finisce in ogni QSO (TX_PWR), sceglie la categoria di potenza nei contest e le Statistiche mostrano il record di km per watt. L’esportazione per profilo dà il file col nome che vogliono POTA e WWFF. In **Diplomi…** la casella «solo quelli da confermare» elenca ciò che hai lavorato senza conferma, con i nominativi a cui chiedere la QSL. Fra i diplomi c'è il **WAIP** dell'ARI (province italiane): la provincia viene dal QSO (campo provincia nella correzione del QSO), dallo scambio dei contest ARI o da «WAIP-XX» nella nota. Diplomi anche **WCA** (castelli), **ILLW** (fari) e **JCC** (città giapponesi): il riferimento viene da SIG/SIG_INFO dell'ADIF o dalla nota («WCA I-00123»).
- **Fonia**: ascolto e registrazione, gli ultimi 60 secondi sempre salvabili, 4 memorie voce (F1-F4). **FreeDV** (700D, 700E, 700C, 1600): ascolto dall'audio della radio e «Tieni premuto per parlare». **Pi-Star / WPSD**: chi passa dal tuo hotspot DMR, D-STAR o YSF, con un clic nella barra QSO.
- **CW**: il decoder CWEngine, il tasto, i messaggi, lo skimmer con la chiavetta SDR. Si accende e resta acceso anche mentre usi le altre sezioni. I QSO fatti qui vanno nel log di QTHome. La decodifica CW è gratis per sempre.
- **Modi digitali**: FT8 e FT4 come WSJT-X (sequenza automatica, CQ, log automatico), RTTY, PSK31/63, Feld Hell, QRSS, APRS, WSPR e SSTV (immagini: il modo si riconosce da solo, quelle ricevute restano nella galleria). La banda segue la radio. Gli spot FT8, FT4, RTTY e PSK portano la radio nel punto giusto e aprono i Modi digitali con il corrispondente pronto. Le decodifiche e i QSO possono andare anche a GridTracker, JTAlert, N1MM o Log4OM, come da WSJT-X (Impostazioni › Radio e programmi). Con l'invio acceso, un doppio clic su una stazione in GridTracker o JTAlert la prepara nei Modi digitali (Tx1 pronto, la trasmissione la decidi tu). In caccia automatica risponde solo ai CQ fatti per te: «CQ POTA/SOTA/WWFF» sempre (i portatili valgono di nuovo ogni giorno), «CQ DX» solo se chi chiama è di un altro continente, «CQ NA», «CQ EU»… solo se è il tuo, «CQ TEST» solo con un contest avviato. **WEFAX**: le carte meteo delle stazioni costiere (DWD Hamburg, Northwood), dritte e salvate da sole. **NAVTEX**: avvisi ai naviganti e meteo marino (518 e 490 kHz), con i messaggi divisi per argomento; ogni carattere arriva due volte e si ricostruisce anche se una copia è rovinata. **Olivia e Contestia** (tutte le combinazioni di toni e banda, ricezione e trasmissione).
- **Contest**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF e generico; numeri, doppi, Cabrillo e SO2R. Invio registra, Esc pulisce. Con un contest avviato, anche la barra QSO chiede lo scambio ricevuto e ogni QSO (FT8, CW, RTTY…) entra nel contest; in alto si vede il contest in corso. Il punteggio segue le regole del contest (CQ WW, WPX, ARI DX, IARU, VHF) e finisce nel Cabrillo; nel CQ WW e nello IARU la zona si scrive da sola dal prefisso. Strumenti da contester: mappa della banda, suggerimenti dei nominativi mentre scrivi (con i «forse» a un carattere), messaggi F1-F4 modificabili ({MYCALL} {CALL} {EXCH}) e ESM, cioè Invio che manda CQ, scambio e TU. C'è anche l'ARI FT8 Activity Contest (IAC): 1 punto a QSO, moltiplicatori i quadrati di 4 caratteri. Senza radio collegata (niente CAT) scegli banda e modo a mano accanto al nominativo. C’è anche l’**ARRL International DX** per chi è fuori da USA e Canada (3 punti per ogni stazione W/VE, moltiplicatori stati e province). In alto i **prossimi grandi contest** con la data: un clic lo sceglie; il tuo scambio (zona, locatore, potenza) si scrive da solo, e il giorno prima arriva un avviso.
- **Satelliti e spazio**: prossimi passaggi, Doppler, inseguimento con il rotore e correzione della radio. Le orbite si scaricano da sole. QO-100: puntamento dal tuo locatore, rotazione dell'LNB, beacon e conversione tra downlink, uplink e uscita dell'LNB.
- **Cluster e propagazione**: DX cluster e Reverse Beacon Network con filtri; un clic su uno spot porta la radio lì. Dati solari e condizioni delle bande. Beacon NCDXF/IARU: chi trasmette adesso su ogni banda, distanza e direzione, e quali sono stati sentiti davvero dal tuo continente. «Aperto adesso»: banda per continente, con le stazioni sentite davvero dal tuo continente negli ultimi 30 minuti. Si possono aggiungere gli spot dei portatili POTA, SOTA e WWFF: il riferimento del parco o della cima finisce nel log. **Previsione 24 ore**: quali bande aprono, ora per ora, verso il corrispondente del QSO o una zona del mondo; è una stima dal flusso solare (gli spot di «Aperto adesso» dicono cosa è aperto davvero). La barra QSO la mostra quando non ci sono spot verso quella stazione. In **Mostra** scegli solo i paesi nuovi o solo le stazioni che non hai ancora collegato su quella banda. I paesi DXCC si aggiornano da soli ogni settimana.
- **Mappa**: notte e greyline, spot, chi ti sente, EME, Es; un clic su uno spot lo lavora. «I miei QSO» mostra dove sono le stazioni del log (verde = confermate). Con «Aperto da te (stima)» scegli una banda e la mappa colora le zone del mondo che quella banda raggiunge adesso dalla tua stazione.
- **SDR**: ricevitore con la chiavetta RTL-SDR, spettro e cascata; clic per ascoltare una frequenza. Con la chiavetta anche le **navi (AIS)**, sulla Mappa e verso OpenCPN in NMEA, e gli **aerei (ACARS)**.
- **Rotore**: puntalo a gradi, verso un locatore o verso il QSO in corso, anche per la via lunga.
- **QTHome Chat**: stanze di testo e di voce tra OM, messaggi privati cifrati; sul server non resta niente. **APRS su internet (APRS-IS)**: messaggi APRS col tuo nominativo e le stazioni APRS vicine sulla Mappa (in azzurro). **Rete mesh AREDN**: con il computer collegato a un nodo, i nodi raggiungibili, i servizi della rete e la qualità dei collegamenti. **Packet radio AX.25** (terminale per BBS e nodi, con Direwolf o un TNC) e **Meshtastic** (messaggi LoRa, nodi sulla Mappa).
- **Winlink**: posta via internet o via radio col modem VARA (si installa a parte): in arrivo, in uscita, allegati, modulo ICS-213 per le emergenze. La password Winlink resta sul tuo computer.
- **Strumenti**: calcolatori, carta di Smith, laboratorio antenne, allenamento al pile-up, **impara il CW col metodo Koch**, quiz per la patente. **NanoVNA**: ROS, impedenza e banda a 2:1 dell'antenna, con un consiglio se accorciare o allungare.
- **Impostazioni**: la tua stazione, le radio e i programmi esterni (WSJT-X, fldigi, logger), quale radio e quale audio usa ogni funzione, gli accessori (sequenziatore di trasmissione (relè prima del PTT, per preamplificatori e amplificatori), amplificatore, commutatore d'antenna, batteria, meteo, WinKeyer), aspetto, lingua e accessibilità. In **La mia stazione** scegli anche le **bande e i modi che usi** («Puoi lavorare ora» e il cluster si regolano su quelli) e gli **avvisi**: paese nuovo in aria, satellite in arrivo e «ti sentono» (il tuo nominativo negli spot), in qualunque pannello.

## Gratis e PRO

Ascoltare, decodificare e tenere il log è sempre gratis. Trasmettere da QTHome, le automazioni, il contest avanzato e le QSL online fanno parte di PRO; i primi 30 giorni sono una prova completa. PRO costa **12 € all'anno**: copre i costi dei server e della ricerca.

## Se qualcosa non va

- **Controlla la stazione**: **Aiuto › Controlla la stazione…** prova in un colpo nominativo, radio, audio, orologio, internet, licenza e aggiornamenti, e per ogni problema ha il tasto per sistemarlo.
- **La radio non compare**: controlla il cavo USB e che la radio sia accesa; poi **Impostazioni › Radio e programmi › Cerca di nuovo le radio**.
- **Niente audio**: su Mac, Impostazioni di Sistema › Privacy e sicurezza › Microfono › accendi QTHome. Su Windows, Impostazioni › Privacy › Microfono.
- **Segnala un problema**: **Aiuto › Segnala un problema o un'idea…** Parte in modo anonimo, senza nominativi, nomi o indirizzi.

## Licenze e ringraziamenti

QTHome è un programma di IU1MVI. Il suo codice è scritto da zero o parte da librerie con licenze libere che ne permettono l'uso; nessun codice con licenza GPL è copiato dentro QTHome.

- **ft8_lib** © Kārlis Goba (MIT): base del decoder FT8/FT4. Metodo dal lavoro pubblico di K1JT, K9AN e G4WJS (QEX 2020).
- **wl2k-go** © Martin Hebnes Pedersen LA5NTA (MIT): protocollo Winlink B2F; contiene **lzhuf** di Haruyasu Yoshizaki e Haruhiko Okumura.
- **codec2** © David Rowe VK5DGR e collaboratori (LGPL-2.1): FreeDV. È una libreria a parte, sostituibile; sorgente: github.com/drowe67/codec2.
- **libusb** (LGPL-2.1): chiavetta SDR su Mac e Windows, libreria a parte, sostituibile; sorgente: github.com/libusb/libusb.
- **webview** (MIT) per la finestra; **webrtlsdr** (Apache 2.0) per la chiavetta SDR nella funzione CW; type library di **OmniRig** © VE3NEA (MIT).
- **Programmi separati** che QTHome usa se li hai installati, senza includerli: **WSJT-X** (GPL, K1JT e collaboratori) per Q65, MSK144, JT65 e per il confronto nel Trainer; **VARA** (EA5HVK) per Winlink via radio; **TQSL** (ARRL) per LoTW; **JS8Call** (KN4CRD); **Pi-Star** e **WPSD** sull'hotspot.
- **Dati**: paesi DXCC da **cty.dat** di AD1C (country-files.com); dati solari da **hamqsl.com** (N0NBH) e **NOAA SWPC**; ionosonde della rete **GIRO** tramite **prop.kc2g.com** (KC2G); orbite da **CelesTrak**; spot da DX cluster, **Reverse Beacon Network**, **PSK Reporter** (N1DQ), **POTA**, **SOTA** e **WWFF**; **Super Check Partial** (supercheckpartial.com); ricerca nominativi con **HamQTH**; carte del mondo **Natural Earth** (dominio pubblico). Rete **APRS-IS** (aprs2.net); APRS è stato ideato da Bob Bruninga WB4APR. Ponti da **RepeaterBook.com**.

Il testo completo delle licenze sta in **docs/terze-parti.md** della repo pubblica SculptWorksLTD/QTHome.

QTHome è realizzato da IU1MVI. Se ti è utile, puoi offrire un caffè: paypal.me/nerosdmf
