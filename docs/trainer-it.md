# QTHome Trainer — guida per i beta tester

QTHome Trainer ascolta la radio insieme a te mentre la usi come sempre e
confronta il decoder FT8/FT4 di QTHome con quello di WSJT-X. Così impariamo
dove il nostro decoder sbaglia e lo correggiamo.

**Non trasmette mai e non comanda la radio.** Legge solo l'audio.

## Cosa serve

- Un computer Mac (Apple o Intel) oppure Windows 10/11.
- La radio collegata al computer con il cavo USB (la sua scheda audio, es. «USB Audio CODEC»).
- Nient'altro: i programmi di WSJT-X che servono per il confronto il Trainer li scarica da solo, una volta.

## Installare

1. Apri la pagina delle versioni: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Scarica **QTHome-Trainer-Mac.pkg** (Mac) oppure **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: doppio clic sul .pkg. Se il Mac dice che non può aprirlo: tasto destro sul file → **Apri**.
   Windows: apri lo zip e avvia **QTHome Trainer.exe**. Se Windows avvisa: **Ulteriori informazioni → Esegui comunque**.

## La prima volta

Si apre una procedura in 5 passi:

1. **Benvenuto**: cosa fa il Trainer.
2. **La tua stazione**: il locatore (4 o 6 caratteri, es. JN45ab, serve solo a sapere la zona), la radio, l'antenna.
3. **L'audio della radio**: scegli la scheda audio della radio e sintonizza una frequenza FT8 (es. 14,074 MHz USB). Il livello deve stare nella zona verde. Sul Mac, la prima volta, il sistema chiede il permesso del microfono: rispondi **Consenti**.
4. **Riservatezza**: cosa mandiamo e se vuoi mandare gli spezzoni audio.
5. **Tutto pronto**: premi **Comincia ad ascoltare**.

## La finestra

- **Panoramica**: l'ascolto (ingresso, livello con il consiglio, spettro), lo **stato della stazione** (audio, confronto con WSJT-X, radio, orologio, invio) e i tuoi numeri. Le quattro lucine in alto dicono lo stesso a colpo d'occhio: verde va bene, giallo da guardare, rosso da sistemare.
- **FT8 · FT4**: per ogni slot, i messaggi letti da QTHome e da WSJT-X (verde = tutti e due, rosso = solo WSJT-X, giallo = solo QTHome) e l'accordo tra i due negli ultimi slot.
- **CW** e **Skimmer**: vedi sotto.
- **Impostazioni**: cosa ascoltare, uso del computer, spezzoni audio, profilo della stazione, aggiornamenti.

Lascia il Trainer aperto (anche ridotto a icona) mentre usi la radio: a ogni avvio riprende l'ascolto da solo.
L'orologio del computer viene controllato via internet: se sbaglia, il Trainer corregge da solo il taglio degli slot.

## CW dalla radio

Nella scheda **CW** spunta **Leggi il CW dalla radio** (con l'ascolto acceso). Ascolta il CW come fai sempre:
ogni 30 secondi due decoder di QTHome rileggono quello che hai sentito e i nominativi vengono controllati con il
Reverse Beacon Network (RBN). Se The Rigger è acceso, il Trainer sa anche su che banda sei e il controllo è più preciso.

## Skimmer con la chiavetta SDR (solo Mac, per ora)

Serve una chiavetta RTL-SDR V3 o V4 con un'antenna HF collegata (la radio resta libera).
In **Impostazioni** spunta **Skimmer con la chiavetta SDR**, poi nella scheda **Skimmer** scegli le bande e premi
**Accendi lo skimmer**: la chiavetta va a caccia da sola dove il RBN e lo spettro mostrano più stazioni.
Nella tabella ✓ vuol dire confermato dal RBN, ? mai sentito dal RBN.

## Cosa parte verso QTHome

- Solo i casi utili: segnali deboli, bande affollate, messaggi letti da uno solo dei due decoder.
- **Mai il tuo nominativo**, mai indirizzo IP, nome del computer o cartelle personali.
- Spezzoni audio di 15 secondi solo se hai acconsentito, al massimo 6 all'ora. Vengono cancellati dopo 12 mesi.
- Se l'invio non è ancora attivo o manca internet, i casi restano in coda sul computer e partono da soli dopo: la riga **Invio** dello stato dice sempre com'è.

## Licenza gratis per i tester

Nella Panoramica trovi le **ore di ascolto**, le barre verso la licenza e il tuo **codice tester** (QT-XXXX-XXXX): è anonimo. Scrivilo nel modulo della pagina [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) insieme al nominativo.

- **10 ore** di ascolto: QTHome PRO gratis per un anno.
- **100 ore** in almeno 3 mesi diversi: licenza Fondatore, PRO gratis per sempre.

Contano solo le ore con la radio accesa e il segnale che arriva.

## Se qualcosa non va

Premi **Segnala** in alto a destra, scrivi cosa è successo e invia. Arriva in modo anonimo; se non c'è internet resta in coda e parte dopo.

Realizzato da IU1MVI.
