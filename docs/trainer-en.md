# QTHome Trainer — guide for beta testers

QTHome Trainer listens to your radio along with you while you use WSJT-X as
usual, and compares the QTHome FT8/FT4 decoder with WSJT-X's. This shows us
where our decoder fails so we can fix it.

**It never transmits and never controls the radio.** It only reads the audio.

## What you need

- A Mac (Apple or Intel) or a Windows 10/11 PC.
- The radio connected to the computer through its USB sound card (the one you use for WSJT-X).
- **WSJT-X installed** (free: <https://wsjt.sourceforge.io/wsjtx.html>). The Trainer uses its decoder as the reference. It does not need to be open.

## Install

1. Open the releases page: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Download **QTHome-Trainer-Mac.pkg** (Mac) or **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: double-click the .pkg. If the Mac refuses: right-click the file → **Open**.
   Windows: open the zip and start **QTHome Trainer.exe**. If Windows warns you: **More info → Run anyway**.

## First time

1. Enter your **locator** (4 or 6 characters, e.g. JN45ab): only the area is used.
2. Tick what you receive with and your antenna.
3. Decide whether to send **audio clips** (read the box): they help a lot, but you can say no.
4. **Save and start**.

## Every time

1. Pick the **radio audio input** (e.g. "USB Audio CODEC").
2. Press **Start listening**. On a Mac the system asks for microphone permission the first time: answer **Allow**.
3. Tune the radio to an FT8 frequency (e.g. 14.074 MHz USB) and let it run.

At the end of each 15-second slot you see a table: for each message, ✓ if QTHome decoded it and ✓ if WSJT-X did.

If the window cannot use the audio, an **Open in the browser** button appears: the Trainer opens in your browser, where the microphone always works.

## CW from the radio

In **Settings** tick **CW** and press **Start listening** on the radio's sound card.
Listen to CW as usual: every 30 seconds two QTHome decoders re-read what you heard and the callsigns are checked
against the Reverse Beacon Network (RBN). If The Rigger is running, the Trainer also knows your band.
Only useful cases are sent: a callsign the RBN never heard, or the two decoders disagreeing.

## Skimmer with the SDR dongle (Mac only, for now)

You need an RTL-SDR V3 or V4 dongle with an HF antenna (your radio stays free).
Tick **Skimmer with the SDR dongle**, choose the bands and press **Start the skimmer**: the dongle hunts on its own:
it goes to the band where the RBN and the spectrum show most stations, reads all of them at once and moves as soon as
no new callsigns arrive. The more bands you choose, the more tests it runs. Callsigns are compared with the RBN;
in the table ✓ means confirmed, ? never heard by the RBN.

## What is sent to QTHome

- Only useful cases: weak signals, crowded bands, messages decoded by only one of the two decoders.
- **Never your callsign**, IP address, computer name or personal folders.
- 15-second audio clips only if you agreed, at most 6 per hour. They are deleted after 12 months.

## Free license for testers

In the numbers you'll find your **listening hours** and your **tester code** (QT-XXXX-XXXX): it's anonymous and doesn't contain your callsign. Enter it in the form on the [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) page together with your callsign.

- **10 hours** of listening: QTHome PRO free for one year.
- **100 hours** over at least 3 different months: Founder license, PRO free forever.

Only hours with the radio on and signal coming in count, and only those already received by QTHome.

## If something goes wrong

Press **Report** at the top right, describe what happened and send it. It is anonymous; without internet it waits in a queue.

Made by IU1MVI.
