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
- **OmniRig** type library — © VE3NEA — licenza MIT.

- **libusb 1.0.27** (accesso alla chiavetta SDR su Mac) — © libusb project — licenza LGPL-2.1.
  È inclusa come libreria separata (`Contents/Frameworks/libusb-1.0.dylib`) e si può sostituire con un'altra
  versione compatibile. Sorgente: https://github.com/libusb/libusb/releases/tag/v1.0.27
- **Reverse Beacon Network** (telnet.reversebeacon.net): il Trainer legge gli spot pubblici per controllare i
  nominativi letti dal CW e dallo skimmer; non manda nulla al RBN.

WSJT-X non è incluso: il Trainer usa quello installato sul computer come programma separato.
