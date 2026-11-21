# QTHome Trainer — guide for beta testers

QTHome Trainer listens to your radio along with you while you use it as usual
and compares the QTHome FT8/FT4 decoder with WSJT-X. This shows us where our
decoder gets it wrong, so we can fix it.

**It never transmits and never controls the radio.** It only reads the audio.

## What you need

- A Mac (Apple or Intel) or a Windows 10/11 PC.
- The radio connected to the computer with the USB cable (its sound card, e.g. "USB Audio CODEC").
- Nothing else: the Trainer downloads the WSJT-X tools it needs for the comparison by itself, once.

## Install

1. Open the releases page: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Download **QTHome-Trainer-Mac.pkg** (Mac) or **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: double-click the .pkg. If the Mac refuses: right-click the file → **Open**.
   Windows: open the zip and start **QTHome Trainer.exe**. If Windows warns you: **More info → Run anyway**.

## The first time

A 5-step guide opens:

1. **Welcome**: what the Trainer does.
2. **Your station**: your locator (4 or 6 characters, e.g. JN45ab, only the area is used), radio and antenna.
3. **Radio audio**: choose the radio's sound card and tune an FT8 frequency (e.g. 14.074 MHz USB). The level should sit in the green zone. On the Mac, the first time, the system asks for microphone permission: answer **Allow**.
4. **Privacy**: what we send and whether you want to send audio clips.
5. **All set**: press **Start listening**.

## The window

- **Overview**: listening (input, level with advice, spectrum), **Station status** (audio, comparison with WSJT-X, radio, clock, upload) and your numbers. The four lights at the top say the same at a glance: green is fine, yellow needs a look, red needs fixing.
- **FT8 · FT4**: for each slot, the messages read by QTHome and by WSJT-X (green = both, red = WSJT-X only, yellow = QTHome only) and the agreement over the last slots.
- **CW** and **Skimmer**: see below.
- **Settings**: what to listen to, computer use, audio clips, station profile, updates.

Leave the Trainer open (minimised is fine) while you use the radio: it resumes listening by itself at every start.
The computer clock is checked over the internet: if it is off, the Trainer corrects the slot timing by itself.

## CW from the radio

In the **CW** tab tick **Read CW from the radio** (with listening on). Listen to CW as you always do: every 30 seconds
two QTHome decoders reread what you heard and the callsigns are checked against the Reverse Beacon Network (RBN).
If The Rigger is running, the Trainer also knows your band and the check is more precise.

## Skimmer with the SDR dongle (Mac only, for now)

You need an RTL-SDR V3 or V4 dongle with an HF antenna (the radio stays free).
In **Settings** tick **Skimmer with the SDR dongle**, then in the **Skimmer** tab choose the bands and press
**Start the skimmer**: the dongle hunts by itself where the RBN and the spectrum show the most stations.
In the table ✓ means confirmed by the RBN, ? never heard by the RBN.

## What is sent to QTHome

- Only useful cases: weak signals, crowded bands, messages read by only one of the two decoders.
- **Never your callsign**, never your IP address, computer name or personal folders.
- 15-second audio clips only if you agreed, at most 6 per hour. They are deleted after 12 months.
- If uploading is not active yet or there is no internet, cases wait on your computer and leave by themselves later: the **Upload** line of the status always tells you how things are.

## Free licence for testers

In the Overview you find your **listening hours**, the bars towards the licence and your **tester code** (QT-XXXX-XXXX): it is anonymous. Enter it in the form on the [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) page together with your callsign.

- **10 hours** of listening: QTHome PRO free for one year.
- **100 hours** over at least 3 different months: Founder licence, PRO free forever.

Only hours with the radio on and signal arriving count.

## If something goes wrong

Press **Report** at the top right, describe what happened and send. It arrives anonymously; without internet it waits in the queue and leaves later.

Made by IU1MVI.
