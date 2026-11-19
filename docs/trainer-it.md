# QTHome Trainer — guida per i beta tester

QTHome Trainer ascolta la radio insieme a te mentre usi WSJT-X come sempre e
confronta il decoder FT8/FT4 di QTHome con quello di WSJT-X. Così impariamo
dove il nostro decoder sbaglia e lo correggiamo.

**Non trasmette mai e non comanda la radio.** Legge solo l'audio.

## Cosa serve

- Un computer Mac (Apple o Intel) oppure Windows 10/11.
- La radio collegata al computer con la sua scheda audio USB (quella che usi per WSJT-X).
- **WSJT-X installato** (gratuito: <https://wsjt.sourceforge.io/wsjtx.html>). Il Trainer usa il suo decoder come metro di paragone. Non deve essere aperto.

## Installare

1. Apri la pagina delle versioni: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Scarica **QTHome-Trainer-Mac.pkg** (Mac) oppure **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: doppio clic sul .pkg. Se il Mac dice che non può aprirlo: tasto destro sul file → **Apri**.
   Windows: apri lo zip e avvia **QTHome Trainer.exe**. Se Windows avvisa: **Ulteriori informazioni → Esegui comunque**.

## La prima volta

1. Scrivi il tuo **locatore** (4 o 6 caratteri, es. JN45ab): serve solo a sapere la zona.
2. Spunta cosa usi per ricevere e che antenna hai.
3. Decidi se mandare **spezzoni audio** (leggi il riquadro): aiutano molto, ma puoi dire di no.
4. **Salva e comincia**.

## Ogni volta

1. Scegli l'**ingresso audio della radio** (es. "USB Audio CODEC").
2. Premi **Comincia ad ascoltare**. Sul Mac la prima volta il sistema chiede il permesso del microfono: rispondi **Consenti**.
3. Sintonizza la radio su una frequenza FT8 (es. 14,074 MHz USB) e lascia lavorare.

Alla fine di ogni slot di 15 secondi vedi la tabella: per ogni messaggio, ✓ se l'ha letto QTHome e ✓ se l'ha letto WSJT-X.

Se la finestra non riesce a usare l'audio, compare il tasto **Apri nel browser**: il Trainer si apre nel tuo browser e lì il microfono funziona sempre.

## CW dalla radio

In **Impostazioni** spunta **CW** e premi **Comincia ad ascoltare** sulla stessa scheda audio della radio.
Ascolta il CW come fai sempre (in banda, in un QSO, in un contest): ogni 30 secondi due decoder di QTHome
rileggono quello che hai sentito e i nominativi letti vengono controllati con il Reverse Beacon Network (RBN).
Se The Rigger è acceso, il Trainer sa anche su che banda sei e il controllo è più preciso.
Parte verso QTHome solo ciò che serve: un nominativo che il RBN non ha mai sentito, o i due decoder in disaccordo.

## Skimmer con la chiavetta SDR (solo Mac, per ora)

Serve una chiavetta RTL-SDR V3 o V4 con un'antenna HF collegata (la radio resta libera).
Spunta **Skimmer con la chiavetta SDR**, scegli le bande e premi **Accendi lo skimmer**: la chiavetta va a caccia
da sola: si mette sulla banda dove il RBN e lo spettro mostrano più stazioni, le legge tutte insieme e, appena lì
non arrivano più nominativi nuovi, si sposta dove c'è più attività. Più bande scegli, più prove fa.
I nominativi vengono confrontati con il RBN; nella tabella ✓ vuol dire confermato, ? mai sentito dal RBN.

## Cosa parte verso QTHome

- Solo i casi utili: segnali deboli, bande affollate, messaggi letti da uno solo dei due decoder.
- **Mai il tuo nominativo**, mai indirizzo IP, nome del computer o cartelle personali.
- Spezzoni audio di 15 secondi solo se hai acconsentito, al massimo 6 all'ora. Vengono cancellati dopo 12 mesi.

## Licenza gratis per i tester

Nei numeri trovi le **ore di ascolto** e il tuo **codice tester** (QT-XXXX-XXXX): è anonimo, non contiene il tuo nominativo. Scrivilo nel modulo della pagina [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) insieme al nominativo.

- **10 ore** di ascolto: QTHome PRO gratis per un anno.
- **100 ore** in almeno 3 mesi diversi: licenza Fondatore, PRO gratis per sempre.

Contano solo le ore con la radio accesa e il segnale che arriva, e solo quelle già arrivate a QTHome.

## Se qualcosa non va

Premi **Segnala** in alto a destra, scrivi cosa è successo e invia. Arriva in modo anonimo; se non c'è internet resta in coda e parte dopo.

Realizzato da IU1MVI.
