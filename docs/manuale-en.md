# QTHome — manual

QTHome is the program for the whole station: radio, log, CW, digital modes, cluster, SDR, satellites, contests and more, in one window. It is one program: the radio, your callsign, the current QSO and the log are the same in every section. Listening and decoding are free.

## Installing

- **Mac**: download `QTHome-Mac.pkg`, open it and follow the steps. QTHome is in Applications.
- **Windows**: download `QTHome-Windows.zip`, open it and drag `QTHome.exe` wherever you like (for example the Desktop), then open it.

QTHome updates itself: when there is a new version it downloads it and installs it when you quit.

## The first time

1. Connect the radio to the computer with the USB cable and turn it on.
2. Open QTHome: the **welcome window** explains the first steps (tick «Don't show again» when you no longer need it), then it asks for your **callsign and locator**. Every function uses them.
3. The radio appears by itself. In **Station** the **Getting started** card shows what is missing (radio, audio, cluster), with a button to do it.
4. On Mac, the first time you listen to the radio, allow the **microphone** for QTHome: it is the audio coming from the radio.
5. For another language: **Settings › Appearance, language and accessibility**.

## The window

- **At the top**: the menus, the state of the radio and of the SDR dongle, your callsign and UTC time.
- **The radio bar** is always visible: radio, band, frequency (VFO A and B), mode, filter, **PTT · TX** (it turns red whenever the radio transmits, whoever keys it; it releases itself after 3 minutes) and **Radio controls** with every control of the front panel.
- **On the left** the sections. By default you see only the essential ones; the others are under **+ More functions** (or always all of them: **Settings › Appearance, language and accessibility**).
- **At the bottom, the waterfall**, above the QSO bar, in Station, Log, Phone, Contest, Cluster, Map, Satellites and Rotator: one click on «Waterfall» folds it.
- **Can't find something?** ⌘K (Ctrl+K on Windows) opens the search: type “SSTV”, “rotator”, “HamQTH” or “licence” and press Enter.
- **At the bottom the QSO bar**: the current QSO, one for the whole program. Type the callsign (Alt+Q gets there from anywhere), reports, name and locator; frequency, band and mode come from the radio. It tells you the country, distance, bearing, which bands he is heard on right now and whether you have worked him. **Enter** saves to the log, **Esc** starts over. While transmitting, **Esc** stops all transmission (FT8, phone, CW, PTT), like Station › Stop all transmission. In the note you can write "POTA IT-0123", "SOTA I/LO-123" or "WWFF IFF-0123": the reference goes into its log field. Saved by mistake? Right after, **Undo** appears: the QSO leaves the log and goes back into the bar. If you are in Europe or Africa, it warns you when you are on phone in the CW/digital part of the band or on 30 m (IARU band plan).
- Without the radio connected (or with the **✎** button) you type frequency, mode, date and UTC time by hand: useful to log a QSO made with a portable rig.
- The cluster, the map, "You can work now", FT8, RTTY/PSK and CW also fill the current QSO: a click on a spot takes the radio to the right frequency and mode and puts the callsign in the bar. With a rotator, **↻ Rotator** turns the antenna towards him.
- Everything works from the keyboard and with a screen reader. For blind or low-vision users: **Settings › Appearance, language and accessibility › Turn on accessibility** (spoken announcements, Morse, S-meter read with ⌘⇧S). It is off by default.

## The sections

- **Station**: the big frequency, S-meter, PTT, radio controls, memories (also from and to CHIRP), who you can work now and open bands.
- **Log**: every QSO, from every section. Search by callsign, country or band; **click a row** to correct or delete it. Paper QSLs (bureau and direct, labels to print) and **electronic QSLs**: LoTW (needs TQSL, free), eQSL, QRZ Logbook and Club Log, HRDLog.net, Wavelog/Cloudlog. Awards and station profiles. If you activate a park or summit, put the reference in the profile (Profiles… › “Activating”): every QSO carries it in the log and in ADIF; in Digital modes the menu next to CQ calls “CQ POTA” or “CQ SOTA”. **Statistics…**: QSOs by year, band, mode and UTC hour, the best day and the confirmed ones. In the profile also put the **power** (W): it goes into every QSO (TX_PWR), picks the power category in contests, and Statistics show the km-per-watt record. Exporting by profile gives the file named the way POTA and WWFF want it. In **Awards…** the “only those still to confirm” box lists what you worked without a confirmation, with the callsigns to ask for a QSL. Among the awards there is ARI's **WAIP** (Italian provinces): the province comes from the QSO (province field when editing the QSO), the ARI contest exchange or “WAIP-XX” in the note.
- **Phone**: listening and recording, the last 60 seconds always savable, 4 voice memories (F1-F4). **FreeDV** (700D, 700E, 700C, 1600): listen from the radio audio and «Hold to talk». **Pi-Star / WPSD**: who comes through your DMR, D-STAR or YSF hotspot, one click into the QSO bar.
- **CW**: the CWEngine decoder, keyer, messages, the skimmer with the SDR dongle. Once on it keeps working while you use other sections. QSOs made here go into the QTHome log. CW decoding is free forever.
- **Digital modes**: FT8 and FT4 like WSJT-X (auto sequence, CQ, auto log), RTTY, PSK31/63, Feld Hell, QRSS, APRS, WSPR and SSTV (images: the mode is recognised automatically, received images stay in the gallery). The band follows the radio. FT8, FT4, RTTY and PSK spots put the radio in the right place and open Digital modes with the station ready. Decodes and QSOs can also go to GridTracker, JTAlert, N1MM or Log4OM, as from WSJT-X (Settings › Radios and programs). With sending on, a double click on a station in GridTracker or JTAlert sets it up in Digital modes (Tx1 ready, you decide when to transmit). In automatic hunting it answers only CQs meant for you: “CQ POTA/SOTA/WWFF” always (portables count again every day), “CQ DX” only if the caller is on another continent, “CQ NA”, “CQ EU”… only if it is yours, “CQ TEST” only with a contest running. **WEFAX**: weather charts from coastal stations (DWD Hamburg, Northwood), straightened and saved automatically. **NAVTEX**: navigational warnings and marine weather (518 and 490 kHz), with messages grouped by subject; every character arrives twice and is rebuilt even if one copy is damaged.
- **Contest**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF and generic; serials, dupes, Cabrillo and SO2R. Enter logs, Esc clears. With a contest started, the QSO bar also asks for the received exchange and every QSO (FT8, CW, RTTY…) goes into the contest; the running contest is shown at the top. The score follows the contest rules (CQ WW, WPX, ARI DX, IARU, VHF) and goes into the Cabrillo; in CQ WW and IARU the zone is filled in from the prefix. Contester tools: band map, callsign suggestions as you type (with the one-character “maybe”), editable F1-F4 messages ({MYCALL} {CALL} {EXCH}) and ESM, Enter that sends CQ, exchange and TU. There is also the ARI FT8 Activity Contest (IAC): 1 point per QSO, multipliers are 4-character squares. Without a connected radio (no CAT) choose band and mode by hand next to the callsign. There is also the **ARRL International DX** for stations outside the USA and Canada (3 points per W/VE station, states and provinces as multipliers). At the top, the **upcoming big contests** with their dates: a click selects it; your exchange (zone, locator, power) is filled in by itself, and a reminder arrives the day before.
- **Satellites and space**: next passes, Doppler, tracking with the rotator and radio correction. Orbits download by themselves. QO-100: pointing from your locator, LNB skew, beacons and conversion between downlink, uplink and LNB output.
- **Cluster and propagation**: DX cluster and Reverse Beacon Network with filters; a click on a spot takes the radio there. Solar data and band conditions. NCDXF/IARU beacons: who is transmitting now on each band, distance and bearing, and which ones were really heard from your continent. “Open now”: band by continent, with the stations really heard from your continent in the last 30 minutes. You can add POTA, SOTA and WWFF portable spots: the park or summit reference goes into the log. **24-hour forecast**: which bands open, hour by hour, towards the QSO station or an area of the world; it is an estimate from the solar flux (the “Open now” spots tell what is really open). The QSO bar shows it when there are no spots towards that station. In **Show** choose only new countries or only stations you have not yet worked on that band. DXCC countries update by themselves every week.
- **Map**: night and greyline, spots, who hears you, EME, Es; a click on a spot works it. "My QSOs" shows where the stations in the log are (green = confirmed). With “Open from you (estimate)” pick a band and the map colours the parts of the world that band reaches now from your station.
- **SDR**: receiver with the RTL-SDR dongle, spectrum and waterfall; click to listen to a frequency.
- **Rotator**: point it by degrees, towards a locator or towards the current QSO, also long path.
- **QTHome Chat**: text and voice rooms between hams, encrypted private messages; nothing stays on the server. **APRS over the internet (APRS-IS)**: APRS messages with your callsign and nearby APRS stations on the Map (light blue).
- **Winlink**: mail over the internet or by radio with the VARA modem (installed separately): inbox, outbox, attachments, ICS-213 form for emergencies. Your Winlink password stays on your computer.
- **Tools**: calculators, Smith chart, antenna lab, pile-up training, **learn CW with the Koch method**, licence quiz. **NanoVNA**: SWR, impedance and 2:1 bandwidth of the antenna, with a tip on whether to shorten or lengthen it.
- **Settings**: your station, radios and external programs (WSJT-X, fldigi, loggers), which radio and audio each function uses, accessories (transmit sequencer (relays before the PTT, for preamps and amplifiers), amplifier, antenna switch, battery, weather, WinKeyer), appearance, language and accessibility. In **My station** you also choose the **bands and modes you use** (“You can work now” and the cluster follow them) and the **alerts**: new country on the air, satellite coming and “you are being heard” (your callsign in spots), in any panel.

## Free and PRO

Listening, decoding and logging are always free. Transmitting from QTHome, automation, advanced contesting and online QSLs are part of PRO; the first 30 days are a full trial. PRO costs **€12 a year**: it covers server and research costs.

## If something goes wrong

- **Check the station**: **Help › Check the station…** tests callsign, radio, audio, clock, internet, licence and updates in one go, with a button to fix each problem.
- **The radio does not appear**: check the USB cable and that the radio is on; then **Settings › Radios and programs › Search for radios again**.
- **No audio**: on Mac, System Settings › Privacy & Security › Microphone › turn QTHome on. On Windows, Settings › Privacy › Microphone.
- **Report a problem**: **Help › Report a problem or an idea…** It is sent anonymously, without callsigns, names or addresses.

## Licences and credits

QTHome is a program by IU1MVI. Its code is written from scratch or builds on libraries whose free licences allow it; no GPL-licensed code is copied into QTHome.

- **ft8_lib** © Kārlis Goba (MIT): base of the FT8/FT4 decoder. Method from the public work of K1JT, K9AN and G4WJS (QEX 2020).
- **wl2k-go** © Martin Hebnes Pedersen LA5NTA (MIT): Winlink B2F protocol; it contains **lzhuf** by Haruyasu Yoshizaki and Haruhiko Okumura.
- **codec2** © David Rowe VK5DGR and contributors (LGPL-2.1): FreeDV. A separate, replaceable library; source: github.com/drowe67/codec2.
- **libusb** (LGPL-2.1): SDR dongle on Mac and Windows, a separate, replaceable library; source: github.com/libusb/libusb.
- **webview** (MIT) for the window; **webrtlsdr** (Apache 2.0) for the SDR dongle in the CW function; **OmniRig** type library © VE3NEA (MIT).
- **Separate programs** QTHome uses if you have installed them, without including them: **WSJT-X** (GPL, K1JT and contributors) for Q65, MSK144, JT65 and the comparison in the Trainer; **VARA** (EA5HVK) for Winlink by radio; **TQSL** (ARRL) for LoTW; **JS8Call** (KN4CRD); **Pi-Star** and **WPSD** on the hotspot.
- **Data**: DXCC entities from AD1C's **cty.dat** (country-files.com); solar data from **hamqsl.com** (N0NBH) and **NOAA SWPC**; ionosondes of the **GIRO** network via **prop.kc2g.com** (KC2G); orbits from **CelesTrak**; spots from DX clusters, the **Reverse Beacon Network**, **PSK Reporter** (N1DQ), **POTA**, **SOTA** and **WWFF**; **Super Check Partial** (supercheckpartial.com); callsign lookup with **HamQTH**; world maps from **Natural Earth** (public domain). **APRS-IS** network (aprs2.net); APRS was created by Bob Bruninga WB4APR.

The full licence texts are in **docs/terze-parti.md** of the public repository SculptWorksLTD/QTHome.

QTHome is made by IU1MVI. If you find it useful, you can buy me a coffee: paypal.me/nerosdmf
