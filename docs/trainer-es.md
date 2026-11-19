# QTHome Trainer — guía para los beta testers

QTHome Trainer escucha tu radio contigo mientras usas WSJT-X como siempre, y compara el decodificador FT8/FT4 de QTHome con el de WSJT-X. Así vemos dónde falla nuestro decodificador para corregirlo.

**Nunca transmite y nunca controla la radio.** Solo lee el audio.

## Qué hace falta

- Un Mac (Apple o Intel) o un PC con Windows 10/11.
- La radio conectada al ordenador con su tarjeta de sonido USB (la que usas para WSJT-X).
- **WSJT-X instalado** (gratis: <https://wsjt.sourceforge.io/wsjtx.html>). El Trainer usa su decodificador como referencia. No hace falta que esté abierto.

## Instalar

1. Abre la página de versiones: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Descarga **QTHome-Trainer-Mac.pkg** (Mac) o **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: doble clic en el .pkg. Si el Mac se niega: clic derecho en el archivo → **Abrir**.
   Windows: abre el zip e inicia **QTHome Trainer.exe**. Si Windows avisa: **Más información → Ejecutar de todas formas**.

## La primera vez

1. Escribe tu **locator** (4 o 6 caracteres, p. ej. JN45ab): solo se usa la zona.
2. Marca con qué recibes y tu antena.
3. Decide si envías **fragmentos de audio** (lee el recuadro): ayudan mucho, pero puedes decir que no.
4. **Guardar y empezar**.

## Cada vez

1. Elige la **entrada de audio de la radio** (p. ej. «USB Audio CODEC»).
2. Pulsa **Empezar a escuchar**. En Mac, la primera vez el sistema pide permiso para el micrófono: responde **Permitir**.
3. Pon la radio en una frecuencia FT8 (p. ej. 14,074 MHz USB) y déjala funcionar.

Al final de cada slot de 15 segundos ves una tabla: en cada mensaje, ✓ si QTHome lo decodificó y ✓ si lo hizo WSJT-X.

Si la ventana no puede usar el audio aparece el botón **Abrir en el navegador**: el Trainer se abre en tu navegador, donde el micrófono siempre funciona.

## CW desde la radio

En **Ajustes** marca **CW** y pulsa **Empezar a escuchar** con la tarjeta de sonido de la radio. Escucha CW como siempre: cada 30 segundos dos decodificadores de QTHome releen lo que has oído y los indicativos se comprueban con el Reverse Beacon Network (RBN). Si The Rigger está abierto, el Trainer también sabe en qué banda estás. Solo se envían los casos útiles: un indicativo que el RBN nunca ha oído, o los dos decodificadores en desacuerdo.

## Skimmer con la llave SDR (por ahora solo Mac)

Hace falta una llave RTL-SDR V3 o V4 con una antena HF (la radio queda libre). Marca **Skimmer con la llave SDR**, elige las bandas y pulsa **Encender el skimmer**: la llave caza sola. Va a la banda donde el RBN y el espectro muestran más estaciones, las lee todas a la vez y se mueve en cuanto dejan de llegar indicativos nuevos. Cuantas más bandas elijas, más pruebas hace. Los indicativos se comparan con el RBN; en la tabla ✓ significa confirmado, ? nunca oído por el RBN.

## Qué se envía a QTHome

- Solo los casos útiles: señales débiles, bandas llenas, mensajes decodificados por uno solo de los dos decodificadores.
- **Nunca tu indicativo**, ni la dirección IP, el nombre del ordenador o tus carpetas personales.
- Fragmentos de audio de 15 segundos solo si lo has aceptado, como máximo 6 por hora. Se borran a los 12 meses.

## Si algo no funciona

Pulsa **Informar** arriba a la derecha, cuenta lo que ha pasado y envíalo. Es anónimo; sin internet espera en cola.

Hecho por IU1MVI.
