# QTHome — manuale

QTHome è il programma per tutta la stazione: radio, log, CW, modi digitali, cluster, SDR, satelliti, contest e altro, in una sola finestra. Funziona sul computer, senza abbonamenti per ascoltare e decodificare.

## Installare

- **Mac**: scarica `QTHome-Mac.pkg`, aprilo e segui i passi. QTHome si trova in Applicazioni.
- **Windows**: scarica `QTHome-Windows.zip`, aprilo e trascina `QTHome.exe` dove preferisci (per esempio sul Desktop), poi aprilo.

QTHome si aggiorna da solo: quando c'è una versione nuova la scarica e la installa alla chiusura.

## La prima volta

1. Collega la radio al computer con il cavo USB e accendila.
2. Apri QTHome: la radio compare da sola nel pannello **Stazione** (dentro c'è The Rigger, che riconosce le radio).
3. Clicca in alto a destra su **nominativo?** e scrivi il tuo nominativo e il tuo locatore.
4. Se vuoi un'altra lingua: **Aiuto › Lingua…**

## La finestra

- **In alto**: i menu, lo stato della radio e della chiavetta SDR, il tuo nominativo e l'ora UTC.
- **La barra della radio** è sempre visibile: scegli la radio, leggi e cambi la frequenza (VFO A e B) e il modo, premi **PTT · TX** per trasmettere (si spegne da solo dopo 3 minuti).
- **A sinistra** le sezioni; **a destra** il pannello scelto. Le sezioni non ancora pronte sono segnate «In arrivo».
- Tutto si usa anche da tastiera e con lo screen reader; **Aiuto › Voce** legge ad alta voce frequenza, modo e segnale.

## Le sezioni

- **Stazione**: le radio collegate, la frequenza grande, l'S-meter, un QSO veloce. I programmi come WSJT-X, fldigi o JS8Call si collegano alla radio attraverso QTHome: le istruzioni sono sotto «Come collegare i programmi».
- **Rotore**: collega un rotore (Yaesu GS-232 o Hamlib rotctld) e puntalo a gradi o verso un locatore, anche per la via lunga.
- **Log**: ogni QSO, esporta e importa ADIF. In fondo le **QSL elettroniche**: LoTW (serve TQSL, gratuito), eQSL, QRZ Logbook e Club Log; le password restano sul tuo computer.
- **Fonia**: ascolto e registrazione, gli ultimi 60 secondi sempre salvabili, 4 memorie voce (F1-F4) da trasmettere. **FreeDV** (700D, 700E, 700C, 1600): ascolto dall'audio della radio e «tieni premuto per parlare». **Pi-Star / WPSD**: chi passa dal tuo hotspot DMR, D-STAR, YSF, con un clic nella barra QSO.
- **CW**: il decoder CWEngine, il tasto, i messaggi, lo skimmer con la chiavetta SDR. La decodifica CW è gratis per sempre.
- **Modi digitali**: FT8 e FT4 come WSJT-X (ricezione e trasmissione), RTTY, PSK, APRS, WSPR, Hell, QRSS e SSTV. Q65, MSK144 e JT65 attraverso WSJT-X aperto accanto (riquadro «Altri modi con WSJT-X»).
- **Cluster e propagazione**: DX cluster e Reverse Beacon Network con filtri; un clic su uno spot porta la radio lì. Dati solari e condizioni delle bande.
- **SDR**: ricevitore con la chiavetta RTL-SDR, spettro e cascata; clic per ascoltare una frequenza.
- **Satelliti e spazio**: prossimi passaggi, Doppler, inseguimento con il rotore e correzione della radio.
- **Contest**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF e generico; numeri, doppi, Cabrillo. Invio registra, Esc pulisce.
- **QTHome Chat**: stanze di testo e di voce tra OM; sul server non resta niente.
- **Winlink**: posta via internet o via radio con il modem VARA (si installa a parte): in arrivo, in uscita, scrivi. La password Winlink resta sul tuo computer.
- **Mappa** e **Strumenti**: il mondo adesso (spot, chi ti sente, greyline, ionosonde) e i calcolatori per la stazione.
- **Assistente AI**: scrivi cosa vuoi («porta la radio su 14.074 FT8», «quando passa la ISS», «cosa vuol dire QSB»). Lavora sul computer, senza internet, e non trasmette mai.

## Gratis e PRO

Ascoltare, decodificare e tenere il log è sempre gratis. Trasmettere da QTHome, le automazioni, il contest avanzato e le QSL online fanno parte di PRO; i primi 30 giorni sono una prova completa. PRO costa **12 € all'anno**: copre i costi dei server e della ricerca.

## Se qualcosa non va

- **La radio non compare**: controlla il cavo USB e che la radio sia accesa; poi **Stazione › Cerca di nuovo le radio**.
- **Niente audio**: su Mac consenti il microfono a QTHome in Impostazioni di Sistema › Privacy e sicurezza.
- **Segnala un problema**: **Aiuto › Segnala un problema o un'idea…** Parte in modo anonimo, senza nominativi, nomi o indirizzi.

QTHome è realizzato da IU1MVI. Se ti è utile, puoi offrire un caffè: paypal.me/nerosdmf
