# QTHome Trainer — guía para beta testers

QTHome Trainer escucha la radio contigo mientras la usas como siempre y compara el
decodificador FT8/FT4 de QTHome con el de WSJT-X. Así vemos dónde se equivoca nuestro
decodificador y lo corregimos.

**Nunca transmite ni controla la radio.** Solo lee el audio.

## Qué necesitas

- Un Mac (Apple o Intel) o un PC con Windows 10/11.
- La radio conectada al ordenador con el cable USB (su tarjeta de sonido, p. ej. «USB Audio CODEC»).
- Nada más: el Trainer descarga solo, una vez, las herramientas de WSJT-X que necesita para comparar.

## Instalar

1. Abre la página de versiones: <https://github.com/SculptWorksLTD/QTHome/releases/latest>
2. Descarga **QTHome-Trainer-Mac.pkg** (Mac) o **QTHome-Trainer-Windows.zip** (Windows).
3. Mac: doble clic en el .pkg. Si el Mac no lo abre: clic derecho en el archivo → **Abrir**.
   Windows: abre el zip y ejecuta **QTHome Trainer.exe**. Si Windows avisa: **Más información → Ejecutar de todas formas**.

## La primera vez

Se abre una guía en 5 pasos:

1. **Bienvenida**: qué hace el Trainer.
2. **Tu estación**: el locator (4 o 6 caracteres, p. ej. JN45ab, solo se usa la zona), la radio, la antena.
3. **Audio de la radio**: elige la tarjeta de sonido de la radio y sintoniza una frecuencia FT8 (p. ej. 14,074 MHz USB). El nivel debe quedar en la zona verde. En el Mac, la primera vez, el sistema pide permiso para el micrófono: responde **Permitir**.
4. **Privacidad**: qué enviamos y si quieres enviar fragmentos de audio.
5. **Todo listo**: pulsa **Empezar a escuchar**.

## La ventana

- **Resumen**: la escucha (entrada, nivel con consejo, espectro), el **Estado de la estación** (audio, comparación con WSJT-X, radio, reloj, envío) y tus números. Las cuatro luces de arriba dicen lo mismo de un vistazo: verde bien, amarillo revisar, rojo arreglar.
- **FT8 · FT4**: para cada slot, los mensajes leídos por QTHome y por WSJT-X (verde = ambos, rojo = solo WSJT-X, amarillo = solo QTHome) y el acuerdo en los últimos slots.
- **CW** y **Skimmer**: ver abajo.
- **Ajustes**: qué escuchar, uso del ordenador, fragmentos de audio, perfil de la estación, actualizaciones.

Deja el Trainer abierto (aunque minimizado) mientras usas la radio: en cada inicio reanuda la escucha solo.
El reloj del ordenador se comprueba por internet: si está desfasado, el Trainer corrige solo el corte de los slots.

## CW de la radio

En la pestaña **CW** marca **Leer el CW de la radio** (con la escucha activa). Escucha CW como siempre: cada 30 segundos
dos decodificadores de QTHome releen lo que oíste y los indicativos se comprueban con la Reverse Beacon Network (RBN).
Si The Rigger está encendido, el Trainer sabe también tu banda y la comprobación es más precisa.

## Skimmer con la llave SDR (solo Mac, por ahora)

Necesitas una llave RTL-SDR V3 o V4 con una antena de HF (la radio queda libre).
En **Ajustes** marca **Skimmer con la llave SDR**; luego en la pestaña **Skimmer** elige las bandas y pulsa
**Encender el skimmer**: la llave busca sola donde la RBN y el espectro muestran más estaciones.
En la tabla ✓ significa confirmado por la RBN, ? nunca oído por la RBN.

## Qué se envía a QTHome

- Solo los casos útiles: señales débiles, bandas llenas, mensajes leídos por uno solo de los dos decodificadores.
- **Nunca tu indicativo**, nunca la dirección IP, el nombre del ordenador ni carpetas personales.
- Fragmentos de audio de 15 segundos solo si aceptaste, máximo 6 por hora. Se borran a los 12 meses.
- Si el envío aún no está activo o no hay internet, los casos esperan en el ordenador y salen solos después: la línea **Envío** del estado siempre dice cómo va.

## Licencia gratis para testers

En el Resumen están tus **horas de escucha**, las barras hacia la licencia y tu **código de tester** (QT-XXXX-XXXX): es anónimo. Escríbelo en el formulario de la página [Beta tester](https://iu1mvi.jimdofree.com/beta-tester/) junto con tu indicativo.

- **10 horas** de escucha: QTHome PRO gratis durante un año.
- **100 horas** en al menos 3 meses distintos: licencia Fundador, PRO gratis para siempre.

Solo cuentan las horas con la radio encendida y señal llegando.

## Si algo falla

Pulsa **Informar** arriba a la derecha, describe lo ocurrido y envía. Llega de forma anónima; sin internet espera en cola y sale después.

Hecho por IU1MVI.
