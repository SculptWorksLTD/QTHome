# Software di terze parti · Third-party software

QTHome, QTHome Trainer e QTHome Mothership includono:

- **ft8_lib** — © 2018 Kārlis Goba — licenza MIT.
  Il decoder FT8/FT4 di QTEngine parte da questa libreria.

  > Permission is hereby granted, free of charge, to any person obtaining a copy
  > of this software and associated documentation files (the "Software"), to deal
  > in the Software without restriction, including without limitation the rights
  > to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  > copies of the Software, and to permit persons to whom the Software is
  > furnished to do so, subject to the following conditions:
  >
  > The above copyright notice and this permission notice shall be included in all
  > copies or substantial portions of the Software.
  >
  > THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  > IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  > FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  > AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  > LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  > OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  > SOFTWARE.

- **webview** (finestra) — licenza MIT.
- **webrtlsdr** (chiavetta RTL-SDR nella funzione CW) — licenza Apache 2.0.
- **OmniRig** type library — © VE3NEA — licenza MIT.

- **libusb 1.0.27** (accesso alla chiavetta SDR su Mac) — © libusb project — licenza LGPL-2.1.
  È inclusa come libreria separata (`Contents/Frameworks/libusb-1.0.dylib`) e si può sostituire con un'altra
  versione compatibile. Sorgente: https://github.com/libusb/libusb/releases/tag/v1.0.27
- **codec2 1.2.0** (FreeDV) — © David Rowe VK5DGR e collaboratori — licenza LGPL-2.1.
  È inclusa come libreria separata (Mac `Contents/Frameworks/libcodec2.dylib`, Windows `libcodec2.dll` accanto a
  `QTHome.exe`) e si può sostituire con un'altra versione compatibile. Sorgente: https://github.com/drowe67/codec2/releases/tag/1.2.0
- **wl2k-go** (protocollo Winlink B2F) — © 2014-2017 Martin Hebnes Pedersen LA5NTA — licenza MIT (testo come ft8_lib
  qui sopra). Contiene **lzhuf**, derivato dal lavoro di Haruyasu Yoshizaki e Haruhiko Okumura, di uso libero.
- **Reverse Beacon Network** (telnet.reversebeacon.net): il Trainer legge gli spot pubblici per controllare i
  nominativi letti dal CW e dallo skimmer; non manda nulla al RBN.

## Programmi separati (non inclusi)

QTHome li usa se l'OM li ha installati; restano programmi a sé, con le loro licenze, e non vengono distribuiti con QTHome:
**WSJT-X** (GPL-3, K1JT e collaboratori: ponte UDP per Q65, MSK144, JT65; confronto nel Trainer), **VARA HF/FM** (EA5HVK,
porte TCP per Winlink via radio), **TQSL** (ARRL, per LoTW), **JS8Call** (KN4CRD, API TCP), **Pi-Star** e **WPSD** (cruscotto
dell'hotspot), **Hamlib rigctld** e **flrig** se l'OM li preferisce.

## Dati e servizi

- **cty.dat** di Jim Reisert AD1C (country-files.com): paesi DXCC e zone, aggiornato ogni settimana.
- **hamqsl.com** di Paul Herrman N0NBH e **NOAA Space Weather Prediction Center**: dati solari.
- **GIRO** (Global Ionospheric Radio Observatory) tramite **prop.kc2g.com** di Andrew Rodland KC2G: misure delle ionosonde.
- **RepeaterBook.com**: elenco dei ponti (file esportato dall'OM per uso personale o API con il suo token).
- **Direwolf** (GPL, WB2OSZ): solo come programma esterno installato dall'OM, collegato in KISS TCP per il packet radio.
- **GSM 06.10** (ETSI): codec della voce di EchoLink riscritto dalla norma; tabelle 4.1-4.6 della norma (le stesse di **libgsm**, Copyright 1992 Jutta Degener e Carsten Bormann, Technische Universität Berlin, licenza libera); nessun codice di libgsm copiato, solo confronto nelle prove.
- **EchoLink®** (marchio di Synergenics, LLC): protocollo pubblico (RTP/RTCP su UDP 5198-5199, server di elenco su TCP 5200); QTHome non è un prodotto di Synergenics.
- **Meshtastic**: API client pubblica (protobuf su TCP 4403 o seriale) per parlare con la radio LoRa dell'OM.
- **Olivia** di Pawel Jalocha (SP9VRC): codifica riscritta dalla specifica pubblicata dall'ARRL e dalla guida UKHAS.
- **AREDN**: stato del nodo letto dall'API sysinfo.json del firmware AREDN.
- **CelesTrak** (T.S. Kelso): orbite dei satelliti.
- DX cluster, **Reverse Beacon Network**, **PSK Reporter** (Philip Gladstone N1DQ), **POTA**, **SOTA**, **WWFF**: spot.
- **Super Check Partial** (supercheckpartial.com), **HamQTH** (OK2CQR), **Natural Earth** (dominio pubblico), **WSPRnet**.
- **APRS-IS** (aprs2.net): rete internet di APRS, usata solo se la si accende; APRS è un’idea di Bob Bruninga WB4APR.
- Metodo di decodifica FT8/FT4 dal lavoro pubblico di K1JT, K9AN e G4WJS (QEX, 2020). Metodo Koch per imparare il CW
  (Ludwig Koch, 1936) e spaziatura Farnsworth come le descrive l'ARRL.
