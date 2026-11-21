# QTHome — guide for beta testers

A separate program is no longer needed: QTHome now does the Trainer's job.

## How to switch it on

1. Open QTHome and go to **Settings › Help improve CW**.
2. Tick **Help improve CW (anonymous)**.
3. Choose the **radio audio input** (e.g. "USB Audio CODEC").
4. If you like, also allow sending **audio clips** of doubtful cases.

Then listen to CW as usual. Every 30 seconds two QTHome decoders reread what arrived and the callsigns are checked against
the Reverse Beacon Network (RBN). If the CW function's skimmer is on (SDR dongle), its callsigns are checked every 2 minutes
too. **It never transmits and never controls the radio.**

FT8 and FT4 are no longer needed: QTHome decodes them with the WSJT-X engine, downloaded automatically the first time.

## What is sent to QTHome

- Only useful cases: the two decoders disagreeing, callsigns the RBN never heard, strong stations not read.
- **Never your callsign**, IP address, computer name or personal folders; the locator only to 4 characters.
- Audio clips only if you agreed, at most 6 per hour, deleted after 12 months.
- If uploading is not on yet or there is no internet, cases wait on your computer and leave by themselves later.

## Reports

Beta testers use QTHome as usual and, when something goes wrong or they have an idea, press **Report**: it arrives anonymously, with the program log needed to understand the problem.

Made by IU1MVI.
