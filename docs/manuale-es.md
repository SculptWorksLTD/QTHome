# QTHome — manual

QTHome es el programa para toda la estación: radio, log, CW, modos digitales, clúster, SDR, satélites, concursos y más, en una sola ventana. Es un solo programa: la radio, el indicativo, el QSO en curso y el log son los mismos en cada sección. Escuchar y decodificar es gratis.

## Instalar

- **Mac**: descarga `QTHome-Mac.pkg`, ábrelo y sigue los pasos. QTHome está en Aplicaciones.
- **Windows**: descarga `QTHome-Windows.zip`, ábrelo y arrastra `QTHome.exe` donde quieras (por ejemplo al Escritorio), luego ábrelo.

QTHome se actualiza solo: cuando hay una versión nueva la descarga y la instala al cerrar.

## La primera vez

1. Conecta la radio al ordenador con el cable USB y enciéndela.
2. Abre QTHome: la **ventana de bienvenida** explica los primeros pasos (marca «No volver a mostrar» cuando ya no la necesites) y luego te pide **indicativo y locator**. Los usan todas las funciones.
3. La radio aparece sola. En **Estación** la tarjeta **Para empezar** muestra lo que falta (radio, audio, clúster), con el botón para hacerlo.
4. En Mac, la primera vez que escuches la radio, permite el **micrófono** a QTHome: es el audio que llega de la radio.
5. Para otro idioma: **Ajustes › Aspecto, idioma y accesibilidad**.

## La ventana

- **Arriba**: los menús, el estado de la radio y de la llave SDR, tu indicativo y la hora UTC.
- **La barra de la radio** siempre visible: radio, banda, frecuencia (VFO A y B), modo, filtro, **PTT · TX** (se pone rojo cuando la radio transmite, la mande quien la mande; se suelta sola a los 3 minutos) y **Mandos de la radio** con todos los mandos del panel frontal.
- **A la izquierda** las secciones. De serie ves solo las esenciales; las demás están en **+ Más funciones** (o todas siempre: **Ajustes › Aspecto, idioma y accesibilidad**).
- **Abajo, la cascada**, encima de la barra QSO, en Estación, Log, Fonía, Concurso, Cluster, Mapa, Satélites y Rotor: un clic en «Cascada» la pliega.
- **¿No encuentras algo?** ⌘K (Ctrl+K en Windows) abre la búsqueda: escribe «SSTV», «rotor», «HamQTH» o «licencia» y pulsa Intro.
- **Abajo la barra QSO**: el QSO en curso, uno solo para todo el programa. Escribe el indicativo (Alt+Q llega desde cualquier sitio), reportes, nombre y localizador; frecuencia, banda y modo vienen de la radio. Te dice el país, la distancia, el rumbo, en qué bandas se le oye ahora y si ya lo has trabajado. **Intro** guarda en el log, **Esc** empieza de nuevo. Mientras transmites, **Esc** detiene toda transmisión (FT8, fonía, CW, PTT), como Estación › Detener toda transmisión. En la nota puedes escribir «POTA IT-0123», «SOTA I/LO-123» o «WWFF IFF-0123»: la referencia va a su campo del log. ¿Guardado por error? Justo después aparece **Deshacer**: el QSO sale del log y vuelve a la barra. En Europa o África te avisa si estás en fonía en la parte CW/digital de la banda o en 30 m (plan de bandas IARU).
- Sin la radio conectada (o con el botón **✎**) frecuencia, modo, fecha y hora UTC se escriben a mano: útil para registrar un QSO hecho en portátil.
- El clúster, el mapa, «Puedes trabajar ahora», FT8, RTTY/PSK y CW también llenan el QSO en curso: un clic en un spot lleva la radio a la frecuencia y al modo correctos y pone el indicativo en la barra. Con un rotor, **↻ Rotor** gira la antena hacia él.
- Todo se usa también con el teclado y con un lector de pantalla. Para personas ciegas o con baja visión: **Ajustes › Aspecto, idioma y accesibilidad › Activar la accesibilidad** (avisos por voz, Morse, S-meter leído con ⌘⇧S). Apagada de serie.

## Las secciones

- **Estación**: la frecuencia grande, el S-meter, el PTT, los mandos de la radio, las memorias (también desde y hacia CHIRP), a quién puedes trabajar ahora y las bandas abiertas.
- **Log**: todos los QSO, de cada sección. Busca por indicativo, país o banda; **clic en una fila** para corregirla o borrarla. QSL de papel (buró y directa, etiquetas para imprimir) y **QSL electrónicas**: LoTW (hace falta TQSL, gratis), eQSL, QRZ Logbook y Club Log, HRDLog.net, Wavelog/Cloudlog. Diplomas y perfiles de estación. Si activas un parque o una cumbre, escribe la referencia en el perfil (Perfiles… › «Activo desde»): cada QSO la lleva en el log y en el ADIF; en los Modos digitales el menú junto a CQ llama «CQ POTA» o «CQ SOTA». **Estadísticas…**: QSO por año, banda, modo y hora UTC, el mejor día y los confirmados. En el perfil pon también la **potencia** (W): va en cada QSO (TX_PWR), elige la categoría de potencia en los concursos y las Estadísticas muestran el récord de km por vatio. Exportar por perfil da el archivo con el nombre que piden POTA y WWFF. En **Diplomas…** la casilla «solo los que faltan por confirmar» lista lo trabajado sin confirmación, con los indicativos a quienes pedir la QSL. Entre los diplomas está el **WAIP** de la ARI (provincias italianas): la provincia viene del QSO (campo provincia al corregir el QSO), del intercambio de los concursos ARI o de «WAIP-XX» en la nota.
- **Fonía**: escucha y grabación, los últimos 60 segundos siempre guardables, 4 memorias de voz (F1-F4). **FreeDV** (700D, 700E, 700C, 1600): escucha desde el audio de la radio y «Mantén pulsado para hablar». **Pi-Star / WPSD**: quién pasa por tu hotspot DMR, D-STAR o YSF, con un clic a la barra QSO.
- **CW**: el decodificador CWEngine, el manipulador, los mensajes, el skimmer con la llave SDR. Encendido sigue trabajando mientras usas otras secciones. Los QSO hechos aquí van al log de QTHome. La decodificación CW es gratis para siempre.
- **Modos digitales**: FT8 y FT4 como WSJT-X (secuencia automática, CQ, log automático), RTTY, PSK31/63, Feld Hell, QRSS, APRS, WSPR y SSTV (imágenes: el modo se reconoce solo, las recibidas quedan en la galería). La banda sigue a la radio. Los spots FT8, FT4, RTTY y PSK llevan la radio al punto justo y abren los Modos digitales con el corresponsal listo. Las decodificaciones y los QSO pueden ir también a GridTracker, JTAlert, N1MM o Log4OM, como desde WSJT-X (Ajustes › Radios y programas). Con el envío activado, un doble clic en una estación en GridTracker o JTAlert la prepara en Modos digitales (Tx1 listo, tú decides cuándo transmitir). En caza automática responde solo a los CQ hechos para ti: «CQ POTA/SOTA/WWFF» siempre (los portátiles valen de nuevo cada día), «CQ DX» solo si quien llama está en otro continente, «CQ NA», «CQ EU»… solo si es el tuyo, «CQ TEST» solo con un concurso iniciado.
- **Concurso**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF y genérico; números, duplicados, Cabrillo y SO2R. Intro registra, Esc limpia. Con un concurso iniciado, la barra QSO también pide el intercambio recibido y cada QSO (FT8, CW, RTTY…) entra en el concurso; arriba se ve el concurso en curso. La puntuación sigue las reglas del concurso (CQ WW, WPX, ARI DX, IARU, VHF) y va al Cabrillo; en CQ WW e IARU la zona se rellena desde el prefijo. Herramientas de concursante: mapa de banda, sugerencias de indicativos mientras escribes (con los «quizá» a un carácter), mensajes F1-F4 editables ({MYCALL} {CALL} {EXCH}) y ESM: Intro envía CQ, intercambio y TU. También está el ARI FT8 Activity Contest (IAC): 1 punto por QSO, multiplicadores los cuadrados de 4 caracteres. Sin radio conectada (sin CAT) elige banda y modo a mano junto al indicativo. También está el **ARRL International DX** para quien está fuera de EE. UU. y Canadá (3 puntos por estación W/VE, multiplicadores estados y provincias). Arriba, los **próximos grandes concursos** con su fecha: un clic lo elige; tu intercambio (zona, locator, potencia) se escribe solo, y el día antes llega un aviso.
- **Satélites y espacio**: próximos pases, Doppler, seguimiento con el rotor y corrección de la radio. Las órbitas se descargan solas. QO-100: apuntamiento desde tu locator, giro del LNB, balizas y conversión entre bajada, subida y salida del LNB.
- **Clúster y propagación**: DX clúster y Reverse Beacon Network con filtros; un clic en un spot lleva la radio allí. Datos solares y condiciones de las bandas. Balizas NCDXF/IARU: quién transmite ahora en cada banda, distancia y rumbo, y cuáles se han oído de verdad desde tu continente. «Abierto ahora»: banda por continente, con las estaciones oídas de verdad desde tu continente en los últimos 30 minutos. Se pueden añadir los spots de portables POTA, SOTA y WWFF: la referencia del parque o la cima va al log. **Previsión 24 horas**: qué bandas abren, hora por hora, hacia el corresponsal del QSO o una zona del mundo; es una estimación a partir del flujo solar (los spots de «Abierto ahora» dicen lo que está abierto de verdad). La barra QSO la muestra cuando no hay spots hacia esa estación, y el asistente responde a «propagation to Japan?». En **Mostrar** elige solo países nuevos o solo las estaciones que aún no has trabajado en esa banda. Los países DXCC se actualizan solos cada semana.
- **Mapa**: noche y greyline, spots, quién te oye, EME, Es; un clic en un spot lo trabaja. «Mis QSO» muestra dónde están las estaciones del log (verde = confirmadas). Con «Abierto desde ti (estimación)» eliges una banda y el mapa colorea las zonas del mundo que esa banda alcanza ahora desde tu estación.
- **SDR**: receptor con la llave RTL-SDR, espectro y cascada; clic para escuchar una frecuencia.
- **Rotor**: apúntalo por grados, hacia un localizador o hacia el QSO en curso, también por el camino largo.
- **QTHome Chat**: salas de texto y voz entre radioaficionados, mensajes privados cifrados; en el servidor no queda nada. **APRS por internet (APRS-IS)**: mensajes APRS con tu indicativo y estaciones APRS cercanas en el Mapa (azul claro).
- **Winlink**: correo por internet o por radio con el módem VARA (se instala aparte): entrada, salida, adjuntos, formulario ICS-213 para emergencias. La contraseña de Winlink se queda en tu ordenador.
- **Herramientas**: calculadoras, carta de Smith, laboratorio de antenas, entrenamiento de pile-up, **aprende CW con el método Koch**, test de examen. **NanoVNA**: ROE, impedancia y banda a 2:1 de la antena, con un consejo para acortarla o alargarla.
- **Asistente IA**: escribe lo que quieres («lleva la radio a 14.074 FT8», «cuándo pasa la ISS», «qué significa QSB»). Trabaja en el ordenador y nunca transmite. Con la ventana en otro idioma distinto del italiano entiende y responde en inglés; con un modelo en el ordenador (Ollama o LM Studio), en cualquier idioma.
- **Ajustes**: tu estación, las radios y los programas externos (WSJT-X, fldigi, logs), qué radio y qué audio usa cada función, los accesorios (secuenciador de transmisión (relés antes del PTT, para preamplificadores y amplificadores), amplificador, conmutador de antena, batería, meteo, WinKeyer), aspecto, idioma y accesibilidad. En **Mi estación** eliges también las **bandas y modos que usas** («Puedes trabajar ahora» y el clúster se ajustan a ellos) y los **avisos**: país nuevo en el aire, satélite en camino y «te están oyendo» (tu indicativo en los spots), en cualquier panel.

## Gratis y PRO

Escuchar, decodificar y llevar el log es siempre gratis. Transmitir desde QTHome, las automatizaciones, el concurso avanzado y las QSL en línea forman parte de PRO; los primeros 30 días son una prueba completa. PRO cuesta **12 € al año**: cubre los costes de servidores e investigación.

## Si algo no va

- **Comprobar la estación**: **Ayuda › Comprobar la estación…** prueba de una vez indicativo, radio, audio, reloj, internet, licencia y actualizaciones, con un botón para arreglar cada problema.
- **La radio no aparece**: revisa el cable USB y que la radio esté encendida; luego **Ajustes › Radios y programas › Buscar de nuevo las radios**.
- **Sin audio**: en Mac, Ajustes del Sistema › Privacidad y seguridad › Micrófono › activa QTHome. En Windows, Configuración › Privacidad › Micrófono.
- **Informar de un problema**: **Ayuda › Informar de un problema o una idea…** Se envía de forma anónima, sin indicativos, nombres ni direcciones.

## Licencias y agradecimientos

QTHome es un programa de IU1MVI. Su código está escrito desde cero o se basa en bibliotecas cuya licencia libre lo permite; ningún código con licencia GPL está copiado dentro de QTHome.

- **ft8_lib** © Kārlis Goba (MIT): base del decodificador FT8/FT4. Método del trabajo público de K1JT, K9AN y G4WJS (QEX 2020).
- **wl2k-go** © Martin Hebnes Pedersen LA5NTA (MIT): protocolo Winlink B2F; contiene **lzhuf** de Haruyasu Yoshizaki y Haruhiko Okumura.
- **codec2** © David Rowe VK5DGR y colaboradores (LGPL-2.1): FreeDV. Biblioteca aparte y sustituible; fuente: github.com/drowe67/codec2.
- **libusb** (LGPL-2.1): llave SDR en Mac y Windows, biblioteca aparte y sustituible; fuente: github.com/libusb/libusb.
- **webview** (MIT) para la ventana; **webrtlsdr** (Apache 2.0) para la llave SDR en la función CW; type library de **OmniRig** © VE3NEA (MIT).
- **Programas aparte** que QTHome usa si los tienes instalados, sin incluirlos: **WSJT-X** (GPL, K1JT y colaboradores) para Q65, MSK144, JT65 y la comparación en el Trainer; **VARA** (EA5HVK) para Winlink por radio; **TQSL** (ARRL) para LoTW; **JS8Call** (KN4CRD); **Pi-Star** y **WPSD** en el hotspot; **Ollama** o **LM Studio** para el asistente.
- **Datos**: entidades DXCC del **cty.dat** de AD1C (country-files.com); datos solares de **hamqsl.com** (N0NBH) y **NOAA SWPC**; ionosondas de la red **GIRO** a través de **prop.kc2g.com** (KC2G); órbitas de **CelesTrak**; spots de DX clusters, **Reverse Beacon Network**, **PSK Reporter** (N1DQ), **POTA**, **SOTA** y **WWFF**; **Super Check Partial** (supercheckpartial.com); búsqueda de indicativos con **HamQTH**; mapas de **Natural Earth** (dominio público). Red **APRS-IS** (aprs2.net); APRS fue creado por Bob Bruninga WB4APR.

El texto completo de las licencias está en **docs/terze-parti.md** del repositorio público SculptWorksLTD/QTHome.

QTHome está hecho por IU1MVI. Si te resulta útil, puedes invitar a un café: paypal.me/nerosdmf
